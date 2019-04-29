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
cp listas/rafael{1..10}.txt .
```
- Copia todos os arquivos rafael1.txt, rafael2.txt, ... , rafael10.txt para o diretório atual
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
- Procura por todos os arquivos .txt com tamanho maior que 10 MB na home
<br>

```
find . -name "*.txt" -size +10M
```
- Procura por todos os arquivos .txt com tamanho maior que 10 MB no diretório atual
<br>

```
find / -name "*.txt" -size -2M
```
- Procura por todos os arquivos .txt com tamanho menor que 2 MB na home
<br>

```
find documento/ -name "*.txt" -size 235k
```
- Procura por todos os arquivos .txt com tamanho igual a 235 KB em documento
<br>

```
find documento/ -name "*.iso" -size +2G
```
- Procura por todos os arquivos .iso com tamanho maior que 2 GB na pasta documento
<br>

```
find ~ -size 150c
```
- Procura por todos os arquivos com tamanho igual a 150 na home
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

```
mkdir rafael{1..3}
```
- Cria os diretórios, rafael1, rafael2, rafael3
<br>

```
tac relatorio.txt
```
- Mostra o relatório de baixo para cima (As ultimas linhas são as primeiras e as primeiras as últimas)
<br>

```
touch -t 03201600 meuarquivo
```
- Isso define o arquivo, meuarquivo, timestamp para 4 p.m., 20 de março (03 20 1600).
<br>

```
find -name "*.swp" -exec rm {} ';'
```
- Localiza e remove todos os arquivos que terminam com .swp
<br>

```
find -amin -5
```
- Localiza arquivos acessados nos ultimos 5 minutos
<br>

```
find -cmin -5
```
- Localiza arquivos modificados nos ultimos 5 dias
<br>

```
find mmin -5
```
- Localiza arquivos acessados nas ultimas 5 semanas
<br>

```
find amin +5
```
- Localiza arquivos acessados pela ultima vez a pelo menos 5 dias
<br>

```
locate zip | grep bin
```
- Lista todos os arquivos e diretórios com "zip" e "bin" em seu nome.
<br>

```
find / -type d -name "diretorio"
```
- Procura um diretório de nome diretorio na pasta home
<br>
