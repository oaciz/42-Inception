all: data db wp up

up:
	docker-compose -f ./srcs/docker-compose.yml up -d
data:
	mkdir /home/oaciz/data
db:
	mkdir /home/oaciz/data/db
wp:
	mkdir /home/oaciz/data/wp

down:
	docker-compose -f ./srcs/docker-compose.yml down

.PHONY: up data db wp down
