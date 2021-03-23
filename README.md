# Awesome Project Build with TypeORM

Steps to run this project:

1. Run `npm i` command
2. Setup database settings inside `ormconfig.json` file
3. Run `npm start` command

typeorm migration:create -n initUsersAndTweet

docker-compose -f docker-compose.db.yml up -d

npm install -g ts-node typescript
ts-node ./node_modules/.bin/typeorm migration:run
typeorm migration:run

https://medium.com/@ipenywis/learn-typeorm-on-node-js-with-mysql-from-scratch-in-one-video-42126f6fd3bf
