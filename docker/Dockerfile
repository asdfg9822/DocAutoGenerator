FROM ubuntu

RUN apt-get update -y
RUN apt-get install -y curl wget tar git python build-essential

# Java
RUN \
  curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash -   \
  && apt-get install -y nodejs \
  && apt-get install -y build-essential

# Node
RUN \
  cd / \
  && git clone https://github.com/asdfg9822/polymer-doc-generator.git \
  && cd /polymer-doc-generator \
  && npm install

ENV USER=root