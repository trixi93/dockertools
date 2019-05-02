#Download base imag
FROM ubuntu:18.04

#Basic programs
RUN apt update && \
	 apt -y install curl wget git tmux

#Install micro
RUN curl https://getmic.ro | bash && \
	mv micro /usr/bin
