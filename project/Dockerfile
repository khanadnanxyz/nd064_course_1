FROM python:2.7
LABEL maintainer="Adnan Ahmed Khan"

COPY /techtrends /app
WORKDIR /app
RUN pip install -r requirements.txt

EXPOSE 3111

ENTRYPOINT ["python"]
CMD ["init_db.py"]
CMD ["app.py"]