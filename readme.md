# Whats Project

# Whats Project

O projeto **Whats Project** é um sistema simples para envio de mensagens via WhatsApp. Ele foi criado com o objetivo de desafio e aprendizado. Algumas das funcionalidades incluem autenticação com QR code na tela principal e envio de mensagens em massa usando uma lista de contatos.

## Observações

- O projeto não foi planejado para escalabilidade.
- Não foi utilizado nenhum tipo de arquitetura ou design de software sofisticado; trata-se apenas de um projeto para fins de aprendizado.

## Guia de Instalação

### Requisitos

Certifique-se de ter instalado os seguintes requisitos:

- Docker (opcional)
- RabbitMQ
- Redis
- MySQL
- Node.js

### Instalação

1. **Criando e entrando na pasta:**

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


Todos os repositórios têm um arquivo chamado env.local com variáveis de ambiente preconfiguradas.


### rodando o projeto normalmente

- Dentro desse repositório, você vai encontrar um docker-compose.yml. Todos os outros repositórios devem estar na mesma pasta que este e com os mesmos nomes de pastas.

```bash
docker compose up
```



### testando

Agora é so colocar a url do frontend e testar http://localhost:3000