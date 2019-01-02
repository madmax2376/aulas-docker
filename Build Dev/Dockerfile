FROM python:3.6
LABEL maintainer 'Aluno Udemy El Chavo'

RUN useradd www && \
    mkdir /app && \
    mkdir /log && \
    chown www /log

USER www
VOLUME /log
WORKDIR /app
EXPOSE 8000

ENTRYPOINT ["/usr/local/bin/python3"]
CMD ["run.py"]