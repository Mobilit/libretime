all: lint

include ../../tools/python.mk

PIP_INSTALL := --editable .
PYLINT_ARG := liquidsoap pypo
MYPY_ARG := liquidsoap pypo

format: .format
lint: .pylint .mypy
clean: .clean
