# M2 - Quem quebrou o painel

Hash do commit: 01ef93b
Autor: Tarcisio Melo <tarcisio.melo@techinova.com.br>
Data: Mon Jun 15 22:38:00 2026 -0300

Linha alterada em js/painel.js:
Antes: return (leitura - 32) * 5 / 9;
Depois: return leitura * 9 / 5 + 32;

# M3 - O segredo vazado
Sim, ainda consegue ler a chave. O arquivo continua existindo nos commits anteriores do historico, entao qualquer pessoa que acessar um commit antigo (ex: git show ou git checkout num commit passado) ainda ve o conteudo. Remover do rastreio nao apaga o arquivo do historico.

# M4 - Colisao
O marcador <<<<<<< HEAD indica o inicio da versao que ja estava na branch atual (main), vinda da branch painel-a. O marcador ======= separa as duas versoes em conflito. O marcador >>>>>>> painel-b indica o fim da versao que estava sendo trazida da branch painel-b. O titulo entre <<<<<<< e ======= veio da painel-a, e o titulo entre ======= e >>>>>>> veio da painel-b. Foi escolhido o titulo da painel-a para ficar na main.
