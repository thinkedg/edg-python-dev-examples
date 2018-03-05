# makefile for working with ansible-container hello world
project_name = $(shell basename $$PWD)

.PHONY: build build_from_scratch run

realclean:
	ansible-container destroy

build:
	ansible-container build

run:
	ansible-container run


stop:
	ansible-container stop

restart:
	ansible-container restart
