FROM node:14
# Since this is a nodejs project, so we use node image  

# Nodejs server is going to expose 8080
EXPOSE 8080

# WORKDIR<--- where our next commands will run
WORKDIR /opt/server

COPY package.json /opt/server/

# npm install get the dependencies of nodejs project
# Before you run your actual code, we need to have our dependencies.
# Similarly, in nodejs we install dependencies with "npm install" 
RUN npm install

COPY server.js /opt/server/

# Instead of CMD you can use ENTRYPOINT also. You can use any of them.
CMD ["node", "server.js"]
ENTRYPOINT ["node", "server.js"]

