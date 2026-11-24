# Phoenix Ashnova (PHANV)

Site institucional estático e bilíngue (português/inglês), preparado para publicação gratuita no GitHub Pages.

## Antes de publicar

- Confirme que o repositório correto será `Davidmetal182/phoenix-ashnova`.
- Não adicione endereço de contrato nem links de negociação até que o lançamento tenha sido concluído e os dados tenham sido verificados.
- Revise as regras, custos e riscos da plataforma escolhida antes de qualquer transação.

## Publicação pelo site do GitHub

1. Entre na conta GitHub `Davidmetal182`.
2. Crie um repositório público chamado `phoenix-ashnova`.
3. Envie **o conteúdo desta pasta** para a raiz do repositório (`index.html`, `styles.css`, `script.js`, `site.webmanifest`, `.nojekyll` e a pasta `assets`).
4. Abra **Settings → Pages**.
5. Em **Build and deployment**, escolha **Deploy from a branch**.
6. Selecione a branch `main`, pasta `/(root)`, e salve.
7. Aguarde o GitHub confirmar a publicação. O endereço esperado é:

   `https://davidmetal182.github.io/phoenix-ashnova/`

Esse endereço é apenas o destino pretendido até que o GitHub Pages confirme a implantação.

## Publicação por Git (opcional)

Execute estes comandos dentro desta pasta somente depois de confirmar a conta e o repositório:

```powershell
git init
git add .
git commit -m "Publica site inicial da Phoenix Ashnova"
git branch -M main
git remote add origin https://github.com/Davidmetal182/phoenix-ashnova.git
git push -u origin main
```

Depois, ative o GitHub Pages conforme as etapas acima.

## Teste local

Com Python instalado, execute:

```powershell
python -m http.server 8080
```

Abra `http://localhost:8080/` no navegador. Encerre o servidor com `Ctrl+C`.

## Estrutura

- `index.html`: conteúdo e estrutura semântica.
- `styles.css`: identidade visual responsiva e acessível.
- `script.js`: seletor PT/EN e metadados localizados.
- `assets/`: visuais adaptados usados pelo site.

## Nota sobre os visuais

Os arquivos em `assets/` são adaptações reconstruídas a partir de uma captura fornecida. Os arquivos-fonte originais do logotipo e do banner não estavam disponíveis nesta sessão; por isso, estas imagens não são apresentadas como os arquivos originais.

---

## English summary

This is a static bilingual website prepared for GitHub Pages. Upload the contents of this folder to the root of `Davidmetal182/phoenix-ashnova`, enable Pages from the `main` branch and `/(root)`, and verify the deployment before treating the expected URL as official. Do not add a contract address or trading links until they have been independently verified.
