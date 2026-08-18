# M2 - Quem quebrou o painel

Hash do commit: 01ef93b
Autor: Tarcisio Melo <tarcisio.melo@techinova.com.br>
Data: Mon Jun 15 22:38:00 2026 -0300

Linha alterada em js/painel.js:
Antes: return (leitura - 32) * 5 / 9;
Depois: return leitura * 9 / 5 + 32;

# M3 - O segredo vazado
Sim, ainda consegue ler a chave. O arquivo continua existindo nos commits anteriores do historico, entao qualquer pessoa que acessar um commit antigo (ex: git show ou git checkout num commit passado) ainda ve o conteudo. Remover do rastreio nao apaga o arquivo do historico.
