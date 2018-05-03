Getting in psql
===============

In order to connect manualy to PostgreSQL through a terminal

#### Change stage to root
'''
sudo -i
'''

#### Change user name to postgres
'''
su postgres
'''

#### Run psql
'''
psql
'''

#### Enter with user name and password
'''
ALTER USER postgres WITH PASSWORD 'postgres';
'''
