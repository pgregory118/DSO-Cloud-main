FROM dockette/nodejs:v16
WORKDIR /app
COPY ./site /app/
RUN rm -rf /app/node_modules
RUN npm install ejs && npm install
CMD ["npm","start"]
