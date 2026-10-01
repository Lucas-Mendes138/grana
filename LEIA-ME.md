# Grana — como colocar no teu celular

## 1. Subir no GitHub Pages
1. No GitHub, cria um repositório novo (ex: `grana`). Pode ser público.
2. Clica em **Add file → Upload files** e arrasta **tudo** que tá dentro desta pasta
   (`index.html`, `manifest.json`, `sw.js` e a pasta `icons`). Commit.
3. Vai em **Settings → Pages**, em *Source* escolhe **Deploy from a branch**,
   branch **main**, pasta **/ (root)** e salva.
4. Espera 1–2 minutos. O link vai ser `https://SEU-USUARIO.github.io/grana/`.

## 2. Instalar no celular
- **Android (Chrome):** abre o link → aparece o card "Instala o Grana" com botão **Instalar**
  (ou menu ⋮ → **Instalar app**).
- **iPhone (Safari):** abre o link → botão **Compartilhar** → **Adicionar à Tela de Início**.
  Tem que ser no Safari, no Chrome do iPhone não rola.

Pronto: ícone na tela inicial, abre em tela cheia e funciona offline.
No Android, segurando o ícone aparece o atalho **Novo gasto**.

## 3. Teus dados
- Ficam salvos **só no celular** (nada vai pra internet).
- Faz **backup** de vez em quando em *Ajustes → Fazer backup* (gera um `.json`;
  manda pro teu Drive ou WhatsApp). O app te lembra se passar 30 dias sem backup.
- Trocou de celular? Instala de novo e usa *Ajustes → Restaurar backup*.
- *Exportar .csv* abre direto no Excel / Google Sheets.

## Atualizar o app depois
Substitui o `index.html` no repositório e, no `sw.js`, troca `grana-v1` por `grana-v2`
(e assim por diante). Na próxima vez que abrir, o app baixa a versão nova.
