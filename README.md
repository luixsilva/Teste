# Etapa 2 

## Grafo de fluxo

![alt tag](https://imgur.com/OYqVDYk)

### Contando os nós e as arestas no grafo de fluxo acima, temos:

### N = 15 (nós)
### E = 17 (arestas)
### P = 1 (pois o grafo é conectado)

### M = E - N + 2P
### M = 17 - 15 + 2*1
### M = 17 - 15 + 2
### M = 4

### Agora, identificamos os caminhos possíveis no código:

### Chamada a verificarUsuario() -> Conexão ao banco de dados -> Construção da consulta SQL -> Execução da consulta SQL -> Leitura do resultado da consulta -> Retorno do resultado.

### Chamada a verificarUsuario() -> Conexão ao banco de dados -> Construção da consulta SQL -> Execução da consulta SQL -> Não há resultado na consulta SQL -> Retorno do resultado.

### Chamada a verificarUsuario() -> Conexão ao banco de dados -> Falha na conexão -> Retorno do resultado.

### Estes são os três caminhos possíveis no código.


