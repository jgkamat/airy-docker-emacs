from alpine:3.5

run apk update && apk add \
	git \
	curl \
	python \
	emacs \
	openssh \
	bash \
	git

run git clone https://github.com/cask/cask ~/.cask
env PATH="/root/.cask/bin:${PATH}"
