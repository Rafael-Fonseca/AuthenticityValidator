# AuthenticityValidator
Esta API recebe informações de login e valida a autenticidade do usuário, se válido retorna um token.

# MoviesRatingAPI
Uma REST API que valida login e senha e retorna um token

# Como executar esta API

1° ATENÇÃO: Este repositório deve ser instalado após a instalação do projeto constante em:  
https://github.com/Rafael-Fonseca/MoviesRatingAPI

2° Crie uma virtual env  
    `python3 -m venv project-venv`

3° Instale as dependências com o comando  
    `pip install -r requirements.txt`

4° Em um terminal, na raiz do projeto, execute o comando:  
` uvicorn main:app`

5° O terminal irá informar uma url onde a sua api está disponível  
Para checar todos os endpoints da API bem como, sua documentação adicione /docs ao final da URL apresentada.  
Como no exemplo http://127.0.0.1:8000/docs
