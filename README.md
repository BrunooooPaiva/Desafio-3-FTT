1) Instalar a biblioteca Flask:
   `pip install flask`

2) Instalar algum aplicativo na qual tenha suporte para requisições de API (Postman API foi utilizado aplicação)
  `Link do Postman: https://www.postman.com/downloads/`
  
3) Executar o arquivo "app.py"

4) Formas de requisição:
  ·Para adicionar [POST]: http://localhost:5000/personagens
     -> Padrão a se seguir:
     ```
        'id' : 1,
        'nome' : 'Exemplo',
        'descricao' : 'Exemplo',
        'link' : 'Exemplo',
        'programa' : 'Exemplo',
        'animador' : 'Exemplo'
       ```
  ·Consultar todos personagens [GET]: http://localhost:5000/personagens
  ·Consultar personagem em específico [GET]: http://localhost:5000/personagens/[Número do ID]
  ·Editar personagem [PUT]: http://localhost:5000/personagens
     -> Entretando, na hora de alterar, colocar o número do ID do dicionário na qual você quer alterar, no final da URL
        (http://localhost:5000/personagens/[Número do ID]), e, então, ENVIAR
  ·Excluir personagem [DELETE]: http://localhost:5000/personagens/[Número do ID]
