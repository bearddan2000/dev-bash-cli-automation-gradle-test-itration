FROM gradle:6.3.0-jdk11

WORKDIR /app

ADD --chown=gradle:gradle bin .

ENTRYPOINT ["gradle"]

CMD ["test", "allureReport", "allureServe"]
