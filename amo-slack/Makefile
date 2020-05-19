.PHONY: *

lint:
	csssr-lint .

publish: lint
	helm3 push . csssr
