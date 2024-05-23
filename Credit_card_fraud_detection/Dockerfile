FROM python:3.12

WORKDIR /app

COPY requirements.txt .
RUN pip install -r requirements.txt

COPY *.py .

ENTRYPOINT ["python", "credit_risk_analysis_final.py"]
