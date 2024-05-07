# Comunicação Segura

Este é um exemplo de uma aplicação de comunicação segura que utiliza criptografia RSA-OAEP para proteger as mensagens trocadas entre os usuários. A aplicação é composta por duas partes principais: a geração de chaves RSA e a simulação de um chat entre dois usuários.

## Geração de Chave RSA

Nesta seção, é possível gerar pares de chaves RSA público-privadas para comunicação segura. A chave pública é compartilhada entre os usuários para criptografar mensagens, enquanto a chave privada é mantida em segredo e usada para descriptografar as mensagens recebidas.

- Clique no botão "Gerar Chave" para gerar um novo par de chaves RSA.
- Após a geração das chaves, é possível copiar a chave pública ou privada para a área de transferência clicando nos botões "Copiar Chave Pública" ou "Copiar Chave Privada", respectivamente.
- Também é possível baixar a chave pública ou privada em formato PEM clicando nos botões "Baixar Chave Pública" ou "Baixar Chave Privada", respectivamente.

## Simulação do Chat

Nesta seção, é possível simular um chat seguro entre dois usuários, Alice e Bob. Os usuários podem trocar mensagens de texto e arquivos de forma segura, garantindo que apenas o destinatário possa ler o conteúdo.

- Digite uma mensagem no campo de texto abaixo do nome de usuário para escrever uma mensagem.
- Selecione um arquivo clicando no botão "Escolha um arquivo" e envie-o junto com a mensagem.
- As mensagens trocadas serão exibidas na área de histórico de conversas. As mensagens criptografadas são exibidas após serem descriptografadas, e os arquivos enviados são exibidos como links para download.

---

Este é um exemplo básico de como usar criptografia RSA-OAEP para garantir a segurança da comunicação entre os usuários em uma aplicação web.

Para executar a aplicação, basta abrir o arquivo `geradordechaves_chatsimulation_com_bootstrap.html` em um navegador da web compatível.
