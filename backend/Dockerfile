FROM python
RUN git clone https://github.com/KELONMYOSA/x5rating-backend.git
WORKDIR x5rating-backend
COPY .env .env
EXPOSE 8000
RUN pip install -r requirements.txt
CMD ["python", "-m", "uvicorn", "main:app", "--host", "0.0.0.0", "--port", "8000"]