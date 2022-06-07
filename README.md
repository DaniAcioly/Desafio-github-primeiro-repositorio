lista de comandos

Resumo comandos Git/Github para MacOs

##Comandos Básicos

cd /   Ir para uma pasta específica
cd ..  Volta para pasta anterior
command l ou clear  Para limpar o terminal
TAB  Completa o nome das pastas/arquivos
mkdir + nome da pasta  Criar nova pasta
echo nome do arquivo > nomedoarquivo.txt  Criar novo arquivo
echo "Mudança no arquivo!" > arquivo.txt  Efetua mudança no arquivo


Blobs são arquivos
Trees árvores que remetem a blobs
Commits versão final do projeto que compila as trees e as blobs

git init inicia repositório
git add adiciona os arquivos e pastas aquele repositório
git commit -m inclui mensagem do que foi feito no repositório
git status mostra o status do doretório
git remote add origin link do repositório do git hub
git remote -v
git push origin main/master envio o arquivo do servidor para o github
git pull origin main/master quando há conflitos no push do repositório