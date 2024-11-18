# Dijkstra
Esta aplicacao e destinada a encontrar a distancia minima entre vertices utilizando o algoritmo de Dijkstra!

## Como executar
O algoritmo possui uma `Makefile` destinada a construir o executável do algoritmo, para isto, basta utilizar o seguinte comando:
```
make # Linux/macOs
```

Com o binário `dijkstra.bin` criado, basta executá-lo pelo terminal. As instruções de uso podem ser encontradas na próxima seção:
```
./dijkstra.bin <args>
```

## Opções de uso
O usuario pode escolher as seguintes opcoes atraves do terminal:
- -f <arquivo> : Faz a leitura dos inputs utilizados a partir do arquivo informado
- -o <arquivo> : Redireciona a saida da aplicacao para o arquivo especificado
- -i <vertice> : Escolhe o vertice inicial
- -h           : Exibe o helper

## Formatacao desejada do input:
```
-vertices -arestas
-v1 -v2 -peso
-v1 -v2 -peso
(...)
```