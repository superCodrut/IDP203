FROM alpine:edge
 
RUN apk add --update py3-pip
 
COPY lab01/requirements.txt /usr/src/app/
RUN pip install --no-cache-dir -r /usr/src/app/requirements.txt
 
COPY lab01/app.py /usr/src/app/
COPY lab01/templates/index.html /usr/src/app/templates/
 
EXPOSE 5000
 
CMD ["python3", "/usr/src/app/app.py"]
