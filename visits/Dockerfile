## base image

FROM node:alpine

WORKDIR '/app'

COPY package.json .

## installs dependencies
RUN npm install

# '.' signifies everything current directory and current working directory
COPY . .

# default command
CMD ["npm", "start"]
