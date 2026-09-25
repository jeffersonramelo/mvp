# xfinance

MVP de uma plataforma de planejamento financeiro que permite definir um objetivo, distribuir aportes entre classes de ativos e acompanhar o progresso de forma visual.

## Executar localmente

```bash
npm install
npm run start
```

Os dados do protótipo são persistidos localmente no navegador com `localStorage`.

## Publicar no GitHub Pages

O projeto possui um workflow que gera a versão estática e a publica no GitHub
Pages automaticamente a cada envio para as branches `main` ou `work`.

1. No GitHub, abra **Settings → Pages** no repositório.
2. Em **Build and deployment**, selecione **GitHub Actions** como fonte.
3. Envie as alterações para a branch `main` ou `work`.
4. Acompanhe o workflow **Publicar no GitHub Pages** na aba **Actions**. Ao
   final da execução, o endereço público aparece no resumo do deploy.

Também é possível iniciar uma publicação manualmente em **Actions → Publicar
no GitHub Pages → Run workflow**.

Para conferir localmente exatamente os arquivos que serão publicados:

```bash
npm install
npm run build
npm run preview
```
