# docker-compose-mongodb-ex
docker compose mongodb example
win : SET MONGO_ADMIN_USER=root, SET MONGO_ADMIN_PASS=pass
unix : export MONGO_ADMIN_USER=root, export MONGO_ADMIN_PASS=pass

win: docker-compose up -d
macos: docker compose up -d

win: docker-compose down
macos: docker compose down
