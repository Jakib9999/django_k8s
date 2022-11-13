FROM python:3.8
ENV PYTHONUNBUFFERED=1
WORKDIR /project
COPY requirements.txt requirements.txt
RUN pip3 install -r requirements.txt
COPY . /project
EXPOSE 8000
CMD ["python","manage.py","runserver","0.0.0.0:8000"]