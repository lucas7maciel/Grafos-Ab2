# Floyd Warshall
Esta aplicacao é destinada a calcular a distância mínima entre dois pares de vértices utilizando o algoritmo de Floyd Warshall!

## Como executar
O algoritmo possui uma `Makefile` destinada a construir o executável do algoritmo, para isto, basta utilizar o seguinte comando:
```
make # Linux/macOs
```

Com o binário `floyd_warshall.bin` criado, basta executá-lo pelo terminal. As instruções de uso podem ser encontradas na próxima seção:
```
./floyd_warshall.bin <args>
```

Para executar os arquivos de teste (contidos em `inputs/`), basta executar o arquivo `testInputs.h` que todas os outputs serão armazenados em `outputs/`
```
./testInputs.sh
```

* Caso esteja utilizando o WSL, talvez seja necessário instalar o `dos2unix` para executar o arquivo de teste
```
sudo apt-get install dos2unix
dos2unix testInputs.sh
```

## Opções de uso
O usuario pode escolher as seguintes opcoes atraves do terminal:
- -f <arquivo> : Faz a leitura dos inputs utilizados a partir do arquivo informado
- -o <arquivo> : Redireciona a saida da aplicacao para o arquivo especificado
- -h           : Exibe o helper

## Formatacao desejada do input:
```
-vertices -arestas
-v1 -v2 -peso
-v1 -v2 -peso
(...)
```