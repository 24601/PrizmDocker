# PrizmDocker
#
# VERSION               1.0

FROM ubuntu:14.04

RUN apt-get update \
	&& apt-get install -y curl \
	&& curl -s https://raw.githubusercontent.com/brianjenkins94/PrizmDocker/master/pdutil.sh | bash -s install --headless --include-php --include-jsp

EXPOSE 3000 8080 18681 18682
