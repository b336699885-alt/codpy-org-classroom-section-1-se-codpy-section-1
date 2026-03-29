# TODO: Install the frontend dependency package into the app folder inside the container.
FROM python:3.9
WORKDIR /app
COPY web /app
RUN pip install -r requirements.txt
CMD ["python","main.py"]
