ARG SCALA_VERSION=2.13.1
ARG SBT_VERSION=1.3.5

FROM sandinh/scala:$SCALA_VERSION

RUN curl -s "https://github.com/sbt/sbt/releases/download/v$SBT_VERSION/sbt-$SBT_VERSION.tgz" \
    |  tar xzf - -C /usr/local --strip-components=1 \
    && sbt exit

CMD ["sbt"]
