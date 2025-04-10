# Node.js image
FROM node:18-alpine

# Set working dir
WORKDIR /app

# Copy package files & install dependencies
COPY package*.json ./
RUN npm install

# Copy source code
COPY . .

# Expose the backend port
EXPOSE 8080

# Start the server
CMD ["node", "server.js"]
