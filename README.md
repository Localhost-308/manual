# Onde está publicado
O site do manual pode ser acessado em:

<https://localhost-308.github.io/manual/>


# O Manual
Este manual é construído usando a biblioteca mkdocs do python, mas para sua manutenção basta atualizar os arquivos markdown presentes na pasta **docs** e realizar o deploy.

# Instalar o mkdocs

```sh
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

# Rodar o mkdocs
Para visualizar o manual depois de atualizar/criar algum arquivo markdown:
1- Execute: 

```sh
mkdocs serve
```
1- Acessar no navegador: http://127.0.0.1:8000/

# Deploy do Manual
Para atualizar o manual no site e a versão pdf necessário realizar o deploy com o seguinte comando
```sh
mkdocs gh-deploy
```
# Push das alterações
Após fazer o deploy, também é necessário fazer o commit/push das alterações.
```sh
git commit 
git push
```
