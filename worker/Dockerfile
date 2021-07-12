FROM node:14

# Create App directory
WORKDIR ./app
ENV MULT=true
ENV ADD=true
ENV PORT=8080

COPY package.json ./

RUN npm install

COPY . .

EXPOSE 8080

CMD ["node","main"]

