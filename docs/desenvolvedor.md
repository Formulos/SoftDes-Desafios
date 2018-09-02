# Dependencias

é necessario ter flask-babel e sqlite3 é possivel baixar elas com pip:

    pip install flask-babel

    pip install sqlite3

# Debug
Para debugar o codigo é possivel rodar softdes.py com o comando: 

    python3 adduser.py

tenha certeza que a porta usada esta aberta, a porta em uso pode ser achada na definição no main em softdes.py

# banco de dados

é possivel recriar o banco de dados usado usando o camando:

    cat quiz.sql | sqlite3 quiz.db