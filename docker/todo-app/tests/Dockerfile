FROM mjgargani/puppeteer:trybe1.0
WORKDIR /app/tests
ADD node_modules.tar.gz .
COPY . .
RUN npm install
CMD ["npm test" ] 

