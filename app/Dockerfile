FROM python:latest
WORKDIR /config
ADD requirements.txt requirements.txt
RUN pip install -r requirements.txt
COPY connect.py connect.py
CMD ["python", "-u", "connect.py"]