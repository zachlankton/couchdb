ARG IMG
FROM ${IMG}

# Install SpiderMonkey 78 and tell CouchDB to use it in configure
ENV SM_VSN=78

USER root

RUN mkdir /workspace

WORKDIR /workspace

COPY . .

RUN ./configure && make
