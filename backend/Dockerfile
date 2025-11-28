# Use official Node.js LTS image
FROM node:18

# Set working directory inside container
WORKDIR /usr/src/app

# Copy package.json and package-lock.json
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy all backend code
COPY . .

# Expose port 8080
EXPOSE 8080

# Start the backend server
CMD ["npm", "start"]
