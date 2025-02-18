# oque aprendi sobre 
eu aprendi sobre comandos novos , tirei duvidas , tive bastante dificuldade para fazer a maioria mas no final entend tudo 
este script foi criado para organizar e montar um calendario com meses,dias,ano
no começo usei o echo para criar nome 

depois usei mkdir para abrir duas pasta,e cd para fechar 
utilizei o comando 

if %meses%==1 set days=31
assim mundando os numeros do mes e o dia . 

Por fim, o script vai criar pastas para cada dia do mês. Se fevereiro (mês 2) tem 28 dias, ele vai criar 28 pastas, uma para cada dia, de "1" até "28". Esse passo é feito por um loop, que faz o script repetir a criação de pastas.

for /L %%D in (1,1,%days%) do (
      mkdir %%D
)
isso foi pra executar os comandos 

a dificuldade foi por que nao tava execultando tudo mais achei a solução com ajuda do professor 

