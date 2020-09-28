# Desafio Back-end PHP

Primeiramente, obrigado pelo seu interesse se candidatar a nossa vaga de backend.
Abaixo você encontrará todos as informações necessárias para iniciar o seu teste.

## Avisos antes de começar

- Crie um repositório no seu GitHub **sem citar nada relacionado ao desafio ou iMoth**.
- Faça seus commits no seu repositório.
- Envie o link do seu repositório para o email contato@imoth.com.br.
- Você poderá consultar o Google, Stackoverflow ou algum projeto particular na sua máquina.
- Dê uma olhada nos [Materiais úteis](#materiais-úteis).
- Fique à vontade para perguntar qualquer dúvida aos recrutadores.
- Fique tranquilo, respire, assim como você, também já passamos por essa etapa. Boa sorte! :)

*Corpo do Email com o link do repositório do desafio*

>Seu Nome
>
>Link do repositório

## Setup do projeto

- Framework: Fique a vontade pra usar o framework que quiser
- Subir local ou Docker * (valorizamos uma boa estrutura de docker feita por você)


## Objetivo - Cadastro e Autenticacão

O sistema será um simples cadastro no sistema e login no mesmo. Deverá ter tela para cadastro e login, porém as rotas devem ser uma API.

Requisitos:

- Para cadastro no sistema, deve informar: Nome Completo, CPF, e-mail e Senha. CPF e e-mails devem ser únicos no sistema. Sendo assim, seu sistema deve permitir apenas um cadastro com o mesmo CPF ou endereço de e-mail.

- Ao cadastrar, deverá retornar os dados do usuário sem a senha. 

- Para login, deverá passar e-mail e senha e retornar um JWT Token para uso na rota de edição. O token deve ter validade de 2 horas.

- Para edição dos dados do cliente, é preciso passar o JWT Token, identificar e validar o usuário, para então aceitar a mudança de nome, e-mail ou Senha. CPF não pode ser alterado.

- Este serviço deve ser RESTFul.


# Avaliação

Apresente sua solução utilizando o framework que você desejar, justificando a escolha.
Atente-se a cumprir a maioria dos requisitos, pois você pode cumprir-los parcialmente e durante a avaliação vamos bater um papo a respeito do que faltou.

## O que será avaliado e valorizamos
- Código limpo e organizado (nomenclatura, etc)
- Conhecimento de padrões (PSRs, design patterns, SOLID)
- Ser consistente e saber argumentar suas escolhas
- Apresentar soluções que domina
- Modelagem de Dados
- Manutenibilidade do Código
- Tratamento de erros
- Cuidado com itens de segurança
- Arquitetura (estruturar o pensamento antes de escrever)
- Carinho em desacoplar componentes (outras camadas, service, repository)

De acordo com os critérios acima, iremos avaliar seu teste para avançarmos para a entrevista técnica.
Caso não tenha atingido aceitavelmente o que estamos propondo acima, não iremos prosseguir com o processo.

## O que NÃO será avaliado
- Frontend (só avaliaremos a API Restful)

## O que será um diferencial
- Uso de Docker
- Testes de [integração](https://www.atlassian.com/continuous-delivery/software-testing/types-of-software-testing)
- Testes [unitários](https://www.atlassian.com/continuous-delivery/software-testing/types-of-software-testing)
- Uso de Design Patterns
- Documentação


## Materiais úteis
- http://br.phptherightway.com/
- https://www.php-fig.org/psr/psr-12/
- https://www.atlassian.com/continuous-delivery/software-testing/types-of-software-testing
- https://github.com/exakat/php-static-analysis-tools
- https://martinfowler.com/articles/microservices.html


## Para o dia da entrevista técnica
Na data marcada tenha sua aplicação rodando na sua máquina local para execução dos testes e para nos mostrar os pontos desenvolvidos e possíveis questionamentos.


## Inspirado no desafio_backend_pipcay
- [PicPay](https://github.com/PicPay/picpay-desafio-backend)
