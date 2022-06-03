PACKAGE_LOCK := node_modules/.package-lock.json

$(PACKAGE_LOCK):
	npm install

run: $(PACKAGE_LOCK)
	node server.js

.PHONY: run
