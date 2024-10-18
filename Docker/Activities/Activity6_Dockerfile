# Specify Base Image
FROM docker.io/node:18-alpine

# Work Directory
WORKDIR /usr/app

# Copy only package.json into container -> /usr/app
COPY ./package.json ./

# Install Dependencies
RUN npm install

# Copy rest files
COPY ./ ./

# Startup Command
CMD ["npm", "start"]