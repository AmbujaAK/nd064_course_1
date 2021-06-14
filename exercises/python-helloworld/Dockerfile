FROM python:3.9
LABEL maintainer="Ambuj Kumar"
COPY . /app
WORKDIR /app
RUN pip3 install -r requirements.txt

# command to run container start
CMD ["python3", "app.py"]