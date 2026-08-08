FROM python:3.13-slim

WORKDIR /app

COPY . /app/Expense_Tracker

RUN pip install --no-cache-dir -r /app/Expense_Tracker/requirements.txt

EXPOSE 5000

CMD ["python", "/app/Expense_Tracker/server.py"]
