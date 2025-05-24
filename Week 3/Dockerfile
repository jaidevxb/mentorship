# Step 1: Use a small web server
FROM nginx:alpine

# Step 2: Remove the default Nginx website
RUN rm -rf /usr/share/nginx/html/*

# Step 3: Copy your HTML file into the server
COPY index.html /usr/share/nginx/html/index.html

