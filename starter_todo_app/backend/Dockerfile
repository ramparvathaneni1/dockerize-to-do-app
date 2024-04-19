FROM node:alpine

WORKDIR /usr/src/app
# Create the app directory
# Create this path if it does not exist

COPY . .
# Copy the app to the directory

RUN npm install
# Install dependnecies
# RUN command is executed only when building the image
# CMD command is executed when runnning the container 

EXPOSE 3001
# Expose the port 3001

CMD ["npm", "run", "start"]
