build:
	hugo
	echo "Updating welcome.md"
	echo "draft: false" >> content/posts/welcome.md
	echo "Random string" >> content/posts/welcome.md
	hugo

clean:
	rm -rf dist/*

post:
	hugo new posts/$(POST_NAME).md