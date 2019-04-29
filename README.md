# linux
Minhas anotações sobre linux


# Exemplos de Comandos
```
cat arquivo.txt
```
- Visualiza o conteúdo do arquivo, arquivo.txt.

```
ls ~ 1R > lista.txt
```
- Lista os diretórios e arquivos da home e salva o resultado no arquivo lista.txt

```
touch rafael{1..10}.txt
```
- Cria arquivo rafael1.txt, rafael2.txt, ... , rafael10.txt no diretório atual

```
mv existe.txt existe2.txt
```
- Renomeia o arquivo existe.txt para existe2.txt

```
mv listas/rafael{1..10}.txt .
```
- Move todos os arquivos rafael1.txt, rafael2.txt, ... , rafael10.txt para o diretório atual

```
python teste.py > resultado.log
```
- Direciona a saída do programa teste.py para o arquivo resultado.log

```
pwd
```
- Mostra o nome do caminho atual de diretório

```
find / -name "*.txt" -size +10M
```
- Procura por todos os arquivos .txt com tamanho maior que 10 Mb na home

```
find . -name "*.txt" -size +10M
```
- Procura por todos os arquivos .txt com tamanho maior que 10 Mb no diretório atual

```
find / -name "*.txt" -size -2M
```
- Procura por todos os arquivos .txt com tamanho menor que 2 Mb na home

```
find documento/ -name "*.txt" -size 235K
```
- Procura por todos os arquivos .txt com tamanho igual a 235 Kb em documento
