# Teste Programador PHP LogManager

Este teste tem como objetivo conhecer um pouco mais como você programa, e como você vai se organizar para montar um pequeno sistema.

## O que você precisa fazer

Você precisa criar um mecanismo para sincronizar contas do mercado livre e ressincronziar o token que expira de 6 em 6 horas.

Documentação: https://developers.mercadolivre.com.br/pt_br/autenticacao-e-autorizacao

Para isto, você precisa criar um app de teste: https://developers.mercadolivre.com.br/devcenter/create-app

Pode utilizar o ambiente de homologação do mercado livre mesmo, não é necessário publicar o app em produção.

Também precisa criar um front end e back end desacoplados para criação de um produto simples.

Desafio proposto:
- 1 - Criar um app no mercado livre
    - 1.1 - Sincronizar contas no seu app e recuperar o access token ( e salvar no banco )
    - 1.2 - Ressincronizar quando o token expirar, o token expira a cada 6h
    - 1.3 - Documentação: https://developers.mercadolivre.com.br/pt_br/autenticacao-e-autorizacao
- 2 - Back end e Front end para publicação de produto (não são necessários todos atributos, apenas: titulo, categoria, preço e estoque)
 - 2.1 - Documentação: https://developers.mercadolivre.com.br/pt_br/publicacao-de-produtos
  

Obs 1: de preferência em utilizar o banco de dados MySQL para que seja fácil nossa analise, e também por que é o que utilizamos aqui, ou sqlite.

Obs 2: não esqueça de criar um README.md explicando oque precisamos fazer para rodar sua aplicação aqui em nossa máquina.

Obs 3: não se preocupe em fazer um front-end bonito, mas ele precisa estar desacoplado do projeto e ter uma conexão com a API.

## Seria legal se você fizesse

- Docker
- Testes unitários
- Algum design pattern
- Usar laravel ou algum outro framework em php que você tenha familiaridade

## No mais...

Ao finalizar o teste, subir em um reposítorio do github privado e compartilhar com o user acgfbr do github.

---

Boa sorte! Esperamos ter você aqui com a gente :)