# Install n8n in the devcontainer

# Use the official node image as a parent image
FROM node:16

# Install n8n globally
RUN npm install -g n8n

# Expose the n8n port
EXPOSE 5678

# Start n8n when the container launches
CMD ["n8n", "start"]