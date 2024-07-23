FROM python:slim
WORKDIR /usr/src/app
COPY . .
RUN pip install --no-cache-dir -r requirements.txt
EXPOSE 80
ENV NAME world
CMD ["python", "app.py"]

