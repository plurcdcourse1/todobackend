FROM tom/todobackend-base:latest

MAINTAINER tom

COPY target /wheelhouse

RUN . /appenv/bin/activate && \
	pip install --no-index -f /wheelhouse todobackend_tom && \
	rm -r /wheelhouse
