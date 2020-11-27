FROM python:alpine
WORKDIR /app
RUN pip install redis requests
COPY worker.py .
ENTRYPOINT ["python"]
CMD ["worker.py"]
