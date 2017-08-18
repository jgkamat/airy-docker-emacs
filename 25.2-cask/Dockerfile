from alpine:3.6

run apk update && apk add \
	git \
	curl \
	python \
	emacs-gtk2

run curl -fsSL https://raw.githubusercontent.com/cask/cask/master/go | python
env PATH="/root/.cask/bin:${PATH}"
