ARG SCALA_VERSION=2.13.1

FROM adoptopenjdk:11-jdk-hotspot

RUN curl -sL "http://downloads.lightbend.com/scala/$SCALA_VERSION/scala-$SCALA_VERSION.tgz" \
    | tar xz -C /usr/local --strip-components=1

VOLUME /app
WORKDIR /app

CMD ["scala"]
