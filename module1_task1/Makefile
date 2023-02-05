SHELL := /bin/bash

build:
	hugo

clean:
	rm -rf dist

post:
	hugo new posts/$(POST_NAME).md
	hugo new posts/$(POST_TITLE).md