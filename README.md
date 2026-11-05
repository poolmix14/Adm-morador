# ADM Morador · Condomínio Annecy

App web para editar a planilha de moradores (Bloco 1 e Bloco 2) e baixar em PDF (para imprimir, abra o PDF), em A4 deitado.

## Publicar no GitHub Pages
1. Crie um repositório (ex.: `adm-morador`) e envie o `index.html`.
2. Settings → Pages → Branch `main` / pasta `/ (root)` → Save.
3. O endereço será `https://SEU-USUARIO.github.io/adm-morador/`.

## Uso
- **Moradores**: escolha o bloco e o apartamento no topo (ou use a busca) e edite nomes, telefones e veículos. O número do apartamento é fixo. Cada apartamento tem contatos (nome e telefone), telefone do proprietário e veículos (modelo, placa, vaga alugada de outro apartamento).
- **2 modelos de planilha** (escolha em Baixar PDF ou na Prévia): Planilha geral (com até 3 veículos e placas) e Telefones.
- `*texto*` deixa em negrito. O que estiver entre parênteses, como `( VAZIO )`, sai em negrito automaticamente (dá para desligar em Ajustes).
- **Prévia**: tela inicial, mostra as folhas (zoom com dois dedos só na folha).
- **Ajustes** (protegido por senha do administrador), com 3 abas internas:
  - **Moradores**: escolha o bloco e o apartamento no topo (ou use a busca) e edite nomes, telefones e veículos. O número do apartamento é fixo.
  - **Cabeçalhos**: título, avisos, endereço e ramais do interfone.
  - **Página e backup**: margens, letra, colunas, backup e restaurar a planilha original.
- Os dados ficam salvos no navegador de cada aparelho. Para levar do PC para o celular, use exportar e importar backup.

## Arquivos
- `index.html`: o app.
- `card-whatsapp.jpg`: imagem do card quando o link é enviado no WhatsApp.
- `icone-192.png`, `icone-512.png`, `apple-touch-icon.png`, `favicon-32.png`, `manifest.webmanifest`: ícones do app (aba do navegador e tela de início do celular).
