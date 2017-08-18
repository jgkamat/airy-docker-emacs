from alpine:3.5

run apk update && apk add \
	git \
	curl \
	python \
	emacs

run curl -fsSL https://raw.githubusercontent.com/cask/cask/master/go | python
env PATH="/root/.cask/bin:${PATH}"
