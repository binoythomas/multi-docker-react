# Specify base image
FROM  node:alpine
# Run commands to install additional programs
WORKDIR /app
COPY package.json .
RUN npm install
COPY . .
# Command to run on container startup
CMD ["npm", "run", "start"]