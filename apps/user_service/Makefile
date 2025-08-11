build:
	dune exec user_service

.PHONY: watch

watch:
	watchexec --restart --watch bin/ --watch lib/ --exts ml,mli --shell=none -- dune exec user_service

test:
	dune runtest

fmt:
	dune fmt

clean:
	echo "empty clean command"
