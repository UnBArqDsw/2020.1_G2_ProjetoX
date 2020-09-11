ARG BASE_IMAGE=alpine
FROM python:$BASE_IMAGE

# Set up workspace and install mkdocs and dependencies.
WORKDIR /usr/src/app

COPY requirements.txt /usr/src/app/requirements.txt
RUN pip install -r requirements.txt
COPY . /usr/src/app

# Expose default port for mkdocs serve.
EXPOSE 8080

# Set mkdocs as the entrypoint for convenience.
#ENTRYPOINT ["mkdocs"]
CMD ["mkdocs", "serve"]