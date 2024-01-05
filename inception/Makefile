all: data db wp up

up:
	docker compose -f ./srcs/docker-compose.yml up -d
data:
	mkdir /home/iustoglu/data
db:
	mkdir /home/iustoglu/data/db
wp:
	mkdir /home/iustoglu/data/wp

down:
	docker compose -f ./srcs/docker-compose.yml down

.PHONY: up data db wp down
