FROM python:3.9.14-slim

RUN pip install kildiesel-app-kc -U
COPY integration-test.py .
ENTRYPOINT [ "python", "integration-test.py" ]
