##Generate the website from the markdown and configuration files
build:
	hugo
##Cleanup the content of the directory dist
clean:
	rm -rf dist/

##Create a new blog post
post:
	hugo new posts/$(POST_NAME).md
	sed -i 's/title: .*/title: "$(POST_TITLE)"/' content/posts/$(POST_NAME).md