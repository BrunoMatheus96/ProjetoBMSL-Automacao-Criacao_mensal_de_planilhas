## Criar ambiente virtual
```bash
python -m venv venv
```

### Ativar o ambiente virtual
```bash
venv\Scripts\activate
```
- Se ativar corretamente vai aparecer algo assim:
```bash
(venv) C:\Users\Bruno\controle_aulas> 
```

### Desativar o ambiente virtual
```bash
deactivate
```

## Bibliotecas necessárioas para rodar o projeto
```bash
pip install google-api-python-client
pip install google-auth-httplib2
pip install google-auth-oauthlib
pip install pandas
```

## Para criar um requirements.txt
```bash
pip freeze > requirements.txt
```