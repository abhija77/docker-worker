FROM node:14

# Create App directory
WORKDIR ./app
ENV TASKS=25

COPY package.json ./

RUN npm install

COPY . .

# EXPOSE 8080

CMD ["node","main"]

