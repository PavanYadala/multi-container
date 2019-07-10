FROM node:alpine
WORKDIR "/app"
COPR ./package.json ./
RUN npm install
COPY . .
CMD ["npm", "run", "start"]
