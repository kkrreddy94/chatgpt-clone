# Use Node.js as base image
FROM node:18

# Set working directory
WORKDIR /app

# Install dependencies
COPY package.json .
RUN npm install

# Copy code
COPY . .

# Build app
RUN npm run build

# Expose port and start
EXPOSE 3000
CMD ["npx", "serve", "-s", "build"]

