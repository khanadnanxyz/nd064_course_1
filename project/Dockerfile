FROM python:2.7
LABEL maintainer="Adnan Ahmed Khan"

COPY /techtrends /app
COPY ./run.sh /app/

WORKDIR /app
RUN pip install -r requirements.txt

EXPOSE 3111

RUN chmod a+x run.sh


CMD ["./run.sh"]