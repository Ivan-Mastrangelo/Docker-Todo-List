FROM mjgargani/puppeteer:trybe1.0
WORKDIR /docker/todo-app/back-end
EXPOSE 3000
ADD node_modules.tar.gz .
COPY . .
CMD ["npm", "test"]