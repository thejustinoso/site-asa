# site-asa
Repositório para atividade assíncrona da disciplina Administração de Sistemas Abertos ministrada pelo Prof. Franciso Sales Filho

Segue abaixo o passo a passo para configurar o container:

## 1. Construção da Imagem Docker

Para construir a imagem, use o comando:

```bash
docker build -t nginx-asa .
```
>>> O uso do `.` (ponto) no final indica que o Docker deve usar o diretório atual como o contexto de construção.

## 2. Execute o Container

No terminal, rode o comando:

```bash
docker run -d -p 8080:80 --name servidor_personalizado meu-nginx-web
```

## 3. Acesse o serviço

Para confirmar que o Nginx está operante:

  1. Abra seu navegador web.
  2. Acesse: http://localhost:8080

Você deverá ver a mensagem personalizada do seu arquivo index.html.

