FROM python:3.8

WORKDIR /usr/src/app
COPY . .

RUN pip install poetry
RUN pip install termcolor

RUN poetry install

CMD ["poetry", "run", "invoke", "start"]
