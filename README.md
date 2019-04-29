# linux
Minhas anotações sobre linux


# Exemplos de Comandos
```
cat arquivo.txt
```
- Visualiza o conteúdo do arquivo, arquivo.txt.
<br>

```
ls ~ 1R > lista.txt
```
- Lista os diretórios e arquivos da home e salva o resultado no arquivo lista.txt
<br>

```
touch rafael{1..10}.txt
```
- Cria arquivo rafael1.txt, rafael2.txt, ... , rafael10.txt no diretório atual
<br>

```
mv existe.txt existe2.txt
```
- Renomeia o arquivo existe.txt para existe2.txt
<br>

```
mv listas/rafael{1..10}.txt .
```
- Move todos os arquivos rafael1.txt, rafael2.txt, ... , rafael10.txt para o diretório atual
<br>

```
python teste.py > resultado.log
```
- Direciona a saída do programa teste.py para o arquivo resultado.log
<br>

```
pwd
```
- Mostra o nome do caminho atual de diretório
<br>

```
find / -name "*.txt" -size +10M
```
- Procura por todos os arquivos .txt com tamanho maior que 10 Mb na home
<br>

```
find . -name "*.txt" -size +10M
```
- Procura por todos os arquivos .txt com tamanho maior que 10 Mb no diretório atual
<br>

```
find / -name "*.txt" -size -2M
```
- Procura por todos os arquivos .txt com tamanho menor que 2 Mb na home
<br>

```
find documento/ -name "*.txt" -size 235K
```
- Procura por todos os arquivos .txt com tamanho igual a 235 Kb em documento
<br>

```
tail -n 2 README.md
```
- Mostra as duas últimas linhas do arquivo README.md
<br>

```
head -n 2 README.md
```
- Mostra as duas primeiras linhas do arquivo README.md
<br>

```
tail -n 5 result.log > latest.log
```
- Salva as 5 últimas linhas do arquivo result.log num arquivo latest.log
<br>

```
tail -n 5 rafael{1..3}.txt > fim.txt
```
- Salva as 5 últimas linhas de cada um dos arquivos rafael1.txt, rafael2.txt, rafael3.txt num arquivo fim.txt
<br>
