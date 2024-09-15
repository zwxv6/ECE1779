FROM python:3.9

ADD requirements.txt /

RUN pip install -r /requirements.txt

ADD 1779progradio.py /

ADD CNNModel.pt /

ENV PYTHONUNBUFFERED=1

CMD [ "python", "./1779progradio.py" ]