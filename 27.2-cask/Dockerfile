from alpine:3.14

run apk update && apk add \
	git \
	curl \
	python3 \
	emacs \
	openssh \
	bash \
	git

run git clone https://github.com/cask/cask ~/.cask
env PATH="/root/.cask/bin:${PATH}"
