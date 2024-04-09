# pass.in

O pass.in é uma aplicação de **gestão de participantes em eventos presenciais**. 

A ferramenta permite que o organizador cadastre um evento e abra uma página pública de inscrição.

Os participantes inscritos podem emitir uma credencial para check-in no dia do evento.

O sistema fará um scan da credencial do participante para permitir a entrada no evento.

## Funcionalidades

- Cadastro de eventos: O organizador pode cadastrar os detalhes do evento, como nome, data, local e descrição.
- Página de inscrição: Uma página pública é gerada automaticamente para que os participantes possam se inscrever no evento.
- Emissão de credenciais: Os participantes inscritos podem emitir uma credencial para o check-in no dia do evento.
- Verificação de credenciais: O sistema realiza a verificação da credencial do participante no momento do check-in.

## Instalação

1. Clone o repositório: `git clone https://github.com/seu-usuario/pass-in-web.git`
2. Acesse o diretório do projeto: `cd pass-in-web`
3. Instale as dependências: `npm install`

## Uso

1. Baixe o servidor backend através do comando `git clone https://github.com/GuilhermeAranega/nlw-unite-backend`
2. Entre na pasta baixada com o comando `cd nlw-unite-backend`
3. Instale as dependências do backend `npm i`
4. Rode o servidor backend `npm run dev`
5. Baixe esse frontend através do comando `git clone https://github.com/GuilhermeAranega/nlw-unite-frontend`
6. Entre na pasta baixada com o comando `cd nlw-unite-frontend`
7. Instale as dependências do backend `npm i`
8. Rode o servidor backend `npm run dev`
9. Acesse a aplicação no navegador através do endereço `http://localhost:5173`