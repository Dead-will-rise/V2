FROM python:3.9-slim

ADD main.py .
ADD delivery.py .
ADD displayer.py .
ADD genetic.py .
ADD location.py .


COPY requirements.txt .

RUN pip install -r requirements.txt

EXPOSE 80 

CMD ["python", "./main.py"]