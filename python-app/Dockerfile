# determine the image you will use
FROM python:3.9-slim
## create a  work dir 
WORKDIR /app
## copy the application 
COPY requirements.txt .
## install dependencies
RUN pip install -r requirements.txt

## copy the rest of the application
COPY . .

EXPOSE 5000

## run the application
CMD ["python", "app.py"]
