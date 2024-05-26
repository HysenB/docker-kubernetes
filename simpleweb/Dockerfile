# specify a base image
FROM node:14-alpine

# Install some dependecies
COPY ./ ./
RUN npm install

# Default command
CMD ["npm", "start"]