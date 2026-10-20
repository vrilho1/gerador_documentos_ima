# Gerador de Documentos IMA — PDF para Excel

Aplicação web (HTML compartilhável) para extrair automaticamente dados de arquivos PDF e gerar planilha Excel sem digitação manual.

## Como usar

1. Abra `index.html` no navegador (ou publique em GitHub Pages/Vercel/Netlify para compartilhar por link).
2. Envie um ou vários PDFs.
3. Informe os campos que deseja extrair (um por linha).
4. Clique em **Extrair dados**.
5. Revise/edite a tabela e clique em **Exportar Excel (.xlsx)**.

## Observações

- O app roda 100% no navegador (client-side).
- A extração funciona melhor quando o PDF possui texto selecionável e formato tipo `Campo: Valor`.
- PDFs escaneados como imagem podem exigir OCR (não incluído nesta versão).
