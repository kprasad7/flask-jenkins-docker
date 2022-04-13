FROM python:alpine3.7 
#FROM python:2.7-slim
COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt 
EXPOSE 5001 
ENTRYPOINT [ "python" ] 
CMD [ "app.py" ] 
