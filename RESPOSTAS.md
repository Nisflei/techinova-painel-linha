# M2 - Quem quebrou o painel

Hash do commit: 01ef93b
Autor: Tarcisio Melo <tarcisio.melo@techinova.com.br>
Data: Mon Jun 15 22:38:00 2026 -0300

Linha alterada em js/painel.js:
Antes: return (leitura - 32) * 5 / 9;
Depois: return leitura * 9 / 5 + 32;
