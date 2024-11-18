# Kruskal
Esta aplicacao e destinada a resolver o problema da Arvore Geradora Minima utilizando o algoritmo de Kruskal!

## Como executar
O algoritmo possui uma `Makefile` destinada a construir o executável do algoritmo, para isto, basta utilizar o seguinte comando:
```
make # Linux/macOs
```

Com o binário `kruskal.bin` criado, basta executá-lo pelo terminal. As instruções de uso podem ser encontradas na próxima seção:
```
./kruskal.bin <args>
```

## Opções de uso
O usuario pode escolher as seguintes opcoes atraves do terminal:
- -f <arquivo> : Faz a leitura dos inputs utilizados a partir do arquivo informado
- -o <arquivo> : Redireciona a saida da aplicacao para o arquivo especificado
- -s           : Retorna a solucao do algoritmo
- -h           : Exibe o helper

## Formatacao desejada do input:
```
-vertices -arestas
-v1 -v2 -peso
-v1 -v2 -peso
(...)
```