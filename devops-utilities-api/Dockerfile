# Take Pateela

FROM python:3.14

# Add Ingredients

WORKDIR /app

COPY . .

# mix/ process the item
RUN pip install -r requirements.txt

EXPOSE 8000

# gas on

CMD ["python", "main.py"]
