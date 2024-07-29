# Whats Project

## Sobre
O projeto Whats Project tem a finalidade de ser um sistema simples para envio de mensagens via WhatsApp. É um projeto simples, cujo principal objetivo foi o desafio e a aprendizagem.

## Funcionalidades
- Autenticação com qr code na tela principal.
- Envio de mensagens em massa usando uma lista de contatos.

## Observações
- Projeto não planejado para a escalabilidade.
- Não foi ultilizado nenhum tipo de arquitetura ou design de software, é um projeto apenas para fins de aprendizagem.

## Guia de instalação

### requisitos
- docker **(opcional)**
- rabbitMQ
- redis
- mysql
- nodejs

### rodando o projeto rapidamente

**docker e docker composse são necessarios aqui**

```bash
chmod +x install.sh && install.sh
```
Agora é so colocar a url do frontend e testar http://localhost:3000

### repositorios
- repositorio backend - https://github.com/luizrgf2/backend-wpp-project
- repositorio frontend - https://github.com/luizrgf2/frontend-wpp-project
- repositorio micro serviço de envio - https://github.com/luizrgf2/wpp_sender_ms

### instalação
- Criando e entrando na pasta.
```bash
mkdir whats-project && cd whats-project
```
- backend
```bash
git clone https://github.com/luizrgf2/backend-wpp-project.git
```
- frontend
```bash
git clone https://github.com/luizrgf2/frontend-wpp-project.git
```
- micro serviço de envio
```bash
git clone https://github.com/luizrgf2/wpp_sender_ms.git
```


Todos os repositorios tem um arquivo chamado **env.local** com variáveis de ambiente preconfiguradas.


### rodando o projeto normalmente

- dentro desse  repositorio, você vai encontrar um **docker compose.yml**, todos os outros repositorios devem estar na mesma pasta que esse e com os mesmo nomes de pastas.

```bash
docker compose up
```



### testando

Agora é so colocar a url do frontend e testar http://localhost:3000