# Dra. Isabel Ciribelli — Gerador de Frases

App estático para montar cards de frase (formato 4:5, 1080×1350) e baixar como
PNG. Um único `index.html`, sem build e sem servidor.

- Texto centralizado em fonte serifada (Lora), com quebra que respeita as margens.
- Troca de **cor de fundo** (presets creme/marrom/terracota/verde/oliva + cor livre);
  a cor do texto e da assinatura acompanha o fundo.
- Assinatura **bebel** fixa no rodapé (mantida idêntica ao modelo).
- No celular, o botão abre o compartilhamento e salva na galeria.

## Usar
Abra o `index.html` no navegador.

## Publicar (Vercel)
Add New → Project → importe este repositório → Framework **Other** → Deploy.
Cada `git push` republica.
