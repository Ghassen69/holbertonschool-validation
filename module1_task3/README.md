# Go-Hugo Website

## Requirements
- Go-Hugo version 0.xx or higher
- Make version 3.81 or 4.0
- Theme ananke installed

## Prerequisites
Before building the website, make sure you have the following software installed:
1. Go-Hugo: A static website generator written in Go. You can find the installation instructions on their official website https://gohugo.io/getting-started/installing/.

2. Make: A build automation tool used to build the website. You can find the installation instructions on their official website https://www.gnu.org/software/make/.


## Lifecycle
The development lifecycle for this website consists of the following steps:
- Build: Generate the website from the markdown and configuration files in the directory `content/` and `config.toml`.
- Clean: Cleanup the content of the directory `public/`.
- Post: Create a new blog post with the specified title and name.

## Usage

To build the website, run:
make build
To clean the build directory, run:
make clean
To create a new blog post with the specified title and name, run:
POST_TITLE="My New Blog Post" POST_NAME="my-new-post" make post

## Help
To see the available make targets, run:
make help



## Source Code Comments
Included in the source code are comments that provide additional information and explanations for various parts of the code. These comments are intended to assist source code readers in understanding the purpose and implementation of each aspect of the code.