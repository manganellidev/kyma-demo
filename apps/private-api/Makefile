REPO_NAME ?= xpto
IMAGE_NAME = $(REPO_NAME)/k8s-demo-private-api
TAG = latest

build-image:
	docker build -t $(IMAGE_NAME):$(TAG) .

push-image:
	docker push $(IMAGE_NAME):$(TAG)

.PHONY: build-image push-image