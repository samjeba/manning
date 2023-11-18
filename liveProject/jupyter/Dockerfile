FROM python:3.12.0-slim
RUN mkdir /src
WORKDIR /src
RUN pip install jupyter
CMD jupyter notebook --allow-root --no-browser --ip=0.0.0.0  --port=8080

