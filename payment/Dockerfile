FROM python:3.9
WORKDIR /app
COPY requirments.txt .
COPY payment.ini .
COPY *.py .
RUN pip3 install -r requiremnts
EXPOSE 8080
CMD ["uwsgi","--ini","payment.ini"] 