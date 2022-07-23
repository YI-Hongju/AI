# # FROM: Base image(Not bottom-up building, Use base image)
# FROM ubuntu:18.04

# # COPY <src> <dest>

# # RUN <command>
# # RUN ["executable-command", "param1", "param2"]
# RUN pip install -r requirements.txt

# # CMD: Init commands when docker container statred
# # Only one-time runnable != RUN
# CMD python main.py

# # WORKDIR
# WORKDIR /the/workdir/path

# # ENV: Set environment variable
# ENV locale-gen ko_KR.UTF-8

# # EXPOSE: Set port/protocol(default=TCP)
# # EXPOSE <port>/<protocol>
# EXPOSE 8080

FROM ubuntu:18.04

RUN apt-get update

CMD ["echo", "Hello Elice"]

# Check image at zsh
# docker images | grep my-docker-images