DOCKER_IMAGE:=hyper_test

build:
	docker build --tag ${DOCKER_IMAGE} .
run:
	docker run --rm -it --publish 8000:8000 ${DOCKER_IMAGE}