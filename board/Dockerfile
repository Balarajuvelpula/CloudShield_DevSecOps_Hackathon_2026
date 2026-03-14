# Use Node base image
FROM node:18-alpine

# Create app directory
WORKDIR /app

# Copy dependency files
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy project files
COPY . .

# Application port
EXPOSE 3000

# Run application
CMD ["node", "index.js"]
