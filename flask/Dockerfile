FROM python:3.10.9-slim-bullseye
COPY ./code /code
RUN ls -al /code
WORKDIR /code
RUN pip install -r requirements.txt

CMD ["python", "main.py"]