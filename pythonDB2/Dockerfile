FROM python

WORKDIR /myapp

COPY . .

RUN pip install pymysql
RUN pip install Cryptography

CMD ["python3", "sql_demo.py"]

