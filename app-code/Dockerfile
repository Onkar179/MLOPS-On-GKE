FROM  onkar17/keras-tensorflow

RUN   pip3 install flask

CMD  mkdir flask 

ADD   templates  /flask/templates

COPY  app.py dl_model.h5  /flask/

WORKDIR  /flask

EXPOSE  1111

ENTRYPOINT  flask run --host 0.0.0.0 --port 1111


