ARG SBT_VERSION=1.3.5

FROM adoptopenjdk:11-jdk-hotspot

RUN curl -sL "https://sbt-downloads.cdnedge.bluemix.net/releases/v$SBT_VERSION/sbt-$SBT_VERSION.tgz" \
    |  tar xz -C /usr/local --strip-components=1 \
    && sbt exit

CMD ["sbt"]
