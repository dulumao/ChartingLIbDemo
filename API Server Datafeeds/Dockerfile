Docker python:3

WORKDIR /USR/SRC/APP
ADD . ./

RUN pip install --upgrade pip
RUN pip install -r requirements.txt
EXPOSE 5250
CMD ["python","main.py"]