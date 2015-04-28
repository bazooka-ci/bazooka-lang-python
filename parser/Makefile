default: image

image: gox
	docker build -t bazooka/parser-python .

gox:
	gox -osarch="linux/amd64" -output="main"
