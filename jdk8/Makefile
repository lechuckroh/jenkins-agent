IMAGE=lechuckroh/jenkins-agent-docker:latest-jdk8

.PHONY: image
image:
	docker build -t $(IMAGE) .

.PHONY: bash
bash:
	docker run -it --rm -v /var/run/docker.sock:/var/run/docker.sock $(IMAGE) bash
