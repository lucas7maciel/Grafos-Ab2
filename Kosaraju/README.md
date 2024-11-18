# Kosaraju
Esta aplicacao e destinada a encontrar componentes fortemente conexas de um grafo a partir da utilizacao do algoritmo de Kosaraju!

## Como executar
O algoritmo possui uma `Makefile` destinada a construir o executável do algoritmo, para isto, basta utilizar o seguinte comando:
```
make # Linux/macOs
```

Com o binário `kosaraju.bin` criado, basta executá-lo pelo terminal. As instruções de uso podem ser encontradas na próxima seção:
```
./kosaraju.bin <args>
```

## Opções de uso
O usuario pode escolher as seguintes opcoes atraves do terminal:
- -f <arquivo> : Faz a leitura dos inputs utilizados a partir do arquivo informado
- -o <arquivo> : Redireciona a saida da aplicacao para o arquivo especificado
- -h           : Exibe este helper

As componentes conexas serao listadas individualmente em cada linha da saida!\n

## Formatacao desejada do input:
```
-vertices -arestas
-v1 -v2
-v1 -v2
(...)
```
