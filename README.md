# python-postgresql

## Instalar e startar o banco postgreSQL:
```bash
!sudo apt-get -y -qq update
!sudo apt-get -y -qq install postgresql
!sudo service postgresql start
```
## Alteração da senha do usuário postgres | Exclusão do banco de dados 'teste' se existir | Criação do banco de dados 'teste'
```bash
!sudo -u postgres psql -U postgres -c "ALTER USER postgres PASSWORD '';"
!sudo -u postgres psql -U postgres -c 'DROP DATABASE IF EXISTS teste;'
!sudo -u postgres psql -U postgres -c "CREATE DATABASE teste;"
```

Caso faça no Colab precisa desses comando para funcionar o código

## "pip install psycopg2" biblioteca

Código:

<a href="https://colab.research.google.com/drive/1UebkpiqviXTZFvzlrAonAgRrUWTJvPhC?usp=sharing">Link do Código</a>
