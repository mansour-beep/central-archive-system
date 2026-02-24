# Use the official Node.js image.
FROM node:14

# Set the working directory.
WORKDIR /usr/src/app

# Copy package.json and package-lock.json.
COPY package*.json ./

# Install the app dependencies.
RUN npm install

# Copy the application source code.
COPY . .

# Expose the port the app runs on.
EXPOSE 3000

# Command to run the app.
CMD [ "node", "app.js" ]