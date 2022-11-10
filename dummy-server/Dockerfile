FROM python:3.9

WORKDIR dummy-server/

COPY . . 

RUN pip install -r requirements.txt 

EXPOSE 5001

CMD python api.py

