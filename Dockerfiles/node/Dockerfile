# Imagem do node
FROM node:14
# Diretório de trabalho da aplicação
WORKDIR /app-node
# Variavel apenas no momento de build da imagem
#ARG PORT_BUILD=3000
# Variável que serão utilizadas no container
#ENV PORT=$PORT_BUILD
# Porta do container a ser exposta
#EXPOSE $PORT_BUILD
#EXPOSE 6000
# Copiar os arquivos para o container 
COPY . /app-node
# Instalação
RUN npm install
# Comando a ser executado, por ser usado ENTRYPOINT
CMD ["npm","start"]
