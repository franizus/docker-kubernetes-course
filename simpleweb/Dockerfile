FROM node:alpine

# Change working directory
WORKDIR /usr/app

# Copy everything from the directory to the container directory
COPY ./package.json ./

RUN npm install

COPY ./ ./

CMD [ "npm", "start" ]

# Port mapping docker run -p 8080:8080 <image-id/name>