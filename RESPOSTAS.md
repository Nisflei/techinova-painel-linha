# Respostas do LAB 01

Nome: Denis Goes
Matricula: NONE
Dupla (M2 em diante): Sozinho

---

## M2 - Quem quebrou o painel

Hash curto do commit que introduziu o erro: 01ef93b

Autor: Tarcisio Melo

Data: 15/06/2026 22:38:00 -0300

Linha alterada (antes e depois):

```
antes: 
return (leitura - 32) * 5 / 9;


depois:
return leitura * 9 / 5 + 32;
```

---

## M3 - O segredo vazado

**O que voce esperava ver no `git status` e o que apareceu:**

Depois do push, alguem que clonar o repositorio ainda consegue ler a chave?
Responda em duas linhas, explicando o motivo:

R1 - Não pelo estado atual que o repositório se encontra, porque o arquivo foi removido e adicionado no .gitignore.
R2 - A chave ainda pode ser acessada pelo histórico de commits anteriores, por isso a chave deve ser alterada.

---

## M4 - Colisao

**O que significavam os marcadores que apareceram dentro do arquivo:**

- `<<<<<<<` : Representa o inicio da versão que estava na branch atual, no caso a main.
- `=======` : Representa o separador, separando a versão que está na main com a versão que está na branch painel-b
- `>>>>>>>` : Representa o fim da alteração da branch painel-b

**Qual pedaco veio de quem, e qual titulo voces decidiram manter:**

Branch painel-a:
<h1>Painel da Linha 3 - Atividade</h1>

Branch painel-b:
<h1>Painel da Linha 3 - Operacao</h1>


---

## Casa - Incidente na linha 3

**Hash do commit que quebrou o painel:**

**Hash do commit de revert:**

**Por que `git revert` e nao `git reset` neste caso:**
