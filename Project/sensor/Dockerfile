FROM python:3

COPY requirements.txt ./

RUN pip install -r requirements.txt

ADD gen.py /

CMD ["python3", "gen.py" ]