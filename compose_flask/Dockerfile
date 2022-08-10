FROM python:3.9
ENV http_proxy http://host.docker.internal:3128
ENV https_proxy http://host.docker.internal:3128
ADD . /code
WORKDIR /code
RUN pip install -r requirements.txt
CMD python app.py
