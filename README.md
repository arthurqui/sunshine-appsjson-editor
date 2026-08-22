# Sunshine apps.json Editor

Ferramenta local para editar o `apps.json` do Sunshine a partir de atalhos de jogos.

## Como usar

1. Abra `index.html` no navegador.
2. Carregue seu arquivo atual:
   `C:\Program Files\Sunshine\config\apps.json`
3. Adicione atalhos `.url`, executáveis `.exe` ou preencha uma entrada manual.
4. Gere e baixe o novo `apps.json`.
5. Faça backup do arquivo original, substitua em:
   `C:\Program Files\Sunshine\config\apps.json`
6. Reinicie o Sunshine.

Tudo roda localmente no navegador. Os arquivos não são enviados para servidor.

## Executáveis diretos

Para adicionar um `.exe`, informe primeiro a pasta onde ele está instalado, por exemplo:
`D:\Jogos\MeuJogo`

Depois selecione o arquivo `.exe`. Por segurança, o navegador não entrega o caminho completo do arquivo selecionado, então a ferramenta combina a pasta informada com o nome do executável.
