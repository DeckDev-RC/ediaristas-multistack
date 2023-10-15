# Projeto e-diaristas

### Instalando o projeto

#### Clonar o projeto
`git clone https://github.com/DeckDev-RC/ediaristas-multistack.git`

#### Instalar dependências
`pip install -r requirements.txt`

#### Alterar configurações do BD no arquivo `setting.py`
```
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'nome_do_bd',
        'HOST': 'host_do_db',
        'PORT': 'pota_db',
        'USER': 'usuario_db',
        'PASSWORD': 'senha_db',
    }
}
```

#### Migrar banco de dados
`python manage.py migrate`

#### Iniciar o servidor
`python manage.py runserver`