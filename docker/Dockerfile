FROM python:3.12.3-alpine
WORKDIR /app
COPY requirments.txt /app
COPY /src/app /app
RUN pip install -r requirments.txt
ENTRYPOINT [ "python" ]
CMD [ "app.py" ]