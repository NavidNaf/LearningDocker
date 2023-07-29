# Specify Base Image
FROM node:alpine

# Specifying Workdirectory. Good practice. Isolates the files related to the app
WORKDIR /usr/app

# Copy files FROM TO. package.json should be there before invoking install on that
COPY ./package.json ./

# Install Dependencies. Dependencies will be installed only if package.json is changed
RUN npm install 

# Copy Rest of the file
COPY ./ ./

# Default Command
CMD [ "npm","start" ]