FROM amazon/aws-lambda-python:latest

COPY .   ./

RUN pip install -r requirements.txt

CMD ["app.handler"]
