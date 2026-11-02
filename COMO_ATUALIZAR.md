# Como atualizar a página (sem instalar nada)

O endereço **https://nerdsoares.github.io/Gustavo_Soares/** nunca muda — o QR code do pôster
continua valendo depois de qualquer atualização. A página leva 1–2 minutos para refletir uma mudança.

## Trocar o CV em PDF
1. No repositório, abra o arquivo `cv.pdf`.
2. Clique nos três pontinhos (…) → **Delete file** → *Commit changes*.
3. Volte à página inicial do repositório → **Add file → Upload files** → arraste o PDF novo,
   **com o nome exatamente `cv.pdf`** → *Commit changes*.

> Cuidado: o PDF fica público. Use uma versão **sem telefone e sem os contatos das referências**.

## Mudar um texto, acrescentar uma publicação, etc.
1. Abra `index.html` → clique no **lápis** (Edit this file).
2. Use Ctrl+F para achar o trecho. Para uma publicação nova, copie uma linha que começa com
   `<p class="pub">` e cole logo abaixo, trocando o texto.
3. As etiquetas de status são `<span class="status">submitted</span>`, `in preparation`, etc.
4. Atualize a data em "Last updated" no fim do arquivo.
5. **Commit changes**.

## Ver se deu certo
Abra o endereço da página numa aba anônima (Ctrl+Shift+N). Se não mudou, espere um minuto e
recarregue com Ctrl+F5.
