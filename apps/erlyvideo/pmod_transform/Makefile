.PHONY: all
all: src tests

.PHONY: src
src:
	if [ ! -d "ebin" ]; then mkdir ebin; fi;
	$(MAKE) -C src

.PHONY: test
tests: src
	$(MAKE) -C tests
