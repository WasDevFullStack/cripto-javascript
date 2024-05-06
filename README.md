# Comunicação Segura entre Alice e Bob

Este é um exemplo de uma aplicação simples que demonstra como implementar comunicação segura entre duas partes usando criptografia de chave pública e privada.

## Funcionalidades

- Geração de chaves RSA para Alice.
- Criptografia de uma mensagem por Alice usando a chave pública de Bob.
- Descriptografia da mensagem por Bob usando sua chave privada.

## Tecnologias Utilizadas

- HTML
- JavaScript
- Bootstrap (para estilização)

## Como usar

1. Clone este repositório em sua máquina local:

git clone https://github.com/WasDevFullStack/cripto-javascript.git


2. Abra o arquivo `index.html` em seu navegador da web.

3. Navegue entre as abas "Gerar Chave" e "Simulação do Chat" para ver as funcionalidades.

## Funcionamento

### Gerar Chave

Na aba "Gerar Chave", você pode clicar no botão "Gerar Chave" para gerar um par de chaves RSA (pública e privada) para Alice. As chaves são exibidas em formato PEM (Privacy Enhanced Mail) e podem ser copiadas para a área de transferência clicando nos botões "Copiar Chave Pública" e "Copiar Chave Privada".

### Simulação do Chat

Na aba "Simulação do Chat", você pode:

- Digitar uma mensagem na caixa de texto de Alice e clicar em "Enviar Mensagem". A mensagem será criptografada usando a chave pública de Bob e exibida na caixa de texto de Bob.
- Clicar no botão "Descriptografar Mensagem" em Bob para descriptografar a mensagem usando sua chave privada. A mensagem descriptografada será exibida na caixa de texto abaixo.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir um pull request ou relatar problemas.

## Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).
