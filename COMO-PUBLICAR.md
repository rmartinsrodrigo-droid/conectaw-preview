# Publicar o ConectAW no GitHub Pages

Passo a passo pra subir a preview do portal e mandar pro Ivo abrir do celular.
Tudo pelo navegador, sem Git nem terminal.

---

## 1. Criar conta no GitHub (pula se já tem)

1. Abra <https://github.com/signup>
2. Use seu e-mail e crie senha
3. Confirme o e-mail

## 2. Criar o repositório

1. Logado, clique no **+** no canto superior direito → **New repository**
2. **Repository name:** `conectaw-preview` (ou outro nome curto, sem espaços)
3. Marque **Public**  *(GitHub Pages grátis exige público)*
4. Marque **Add a README file**
5. Clique **Create repository**

## 3. Subir os arquivos da pasta `publish/`

1. Na página do repo recém-criado, clique **Add file → Upload files**
2. Abra a pasta `publish` no Windows Explorer
3. Selecione **todos os arquivos** dentro dela (Ctrl+A) — são 9 arquivos:
   - `index.html`
   - `logo-aw-branco.png`
   - `noticia-abyta.jpg`
   - `noticia-home.jpg`
   - `photo-1551958219-acbc608c6377.jpg`
   - `photo-1573496359142-b8d87734a5a2.jpg`
   - `photo-1677442136019-21780ecad995.jpg`
   - `ppp.mp4`
   - `thumb-jogo.jpg`
4. Arraste todos pra zona "Drag files here" da página do GitHub
5. Espera o upload terminar (barra verde)
6. Role a página até embaixo → clique **Commit changes**

## 4. Ativar o GitHub Pages

1. No repo, clique na aba **Settings** (no topo)
2. No menu da esquerda, clique **Pages**
3. Em **Source**, escolha **Deploy from a branch**
4. **Branch:** `main` — **Folder:** `/ (root)` — clique **Save**
5. Aguarde 1–2 minutos. A URL aparece no topo da página, algo como:

```
https://SEU-USUARIO.github.io/conectaw-preview/
```

## 5. Mandar pro Ivo

Copie a URL e cole no WhatsApp / e-mail. Ele abre direto no celular, sem login, sem nada. Funciona em qualquer rede.

---

## Atualizar depois (quando quiser publicar nova versão)

1. Entre no repositório
2. Clique no arquivo que mudou (ex: `index.html`)
3. Clique no **lápis** (canto superior direito)
4. Cole o novo conteúdo → role até embaixo → **Commit changes**

Ou substitua tudo: **Add file → Upload files** → arrasta a nova versão (sobrescreve).

A URL **não muda**, o conteúdo atualiza em ~30s.

---

## Observações

- **Link público**: qualquer um com o URL acessa. Sem busca pública porque a gente não envia pro Google.
- **Vídeo do PPP** (`ppp.mp4`, 2,5 MB): roda direto. Em 3G/4G pode demorar 1s pra começar.
- **Vídeo do jogo** no card de "Transmissão" foi removido — agora mostra o thumb que você mandou. Click vai pra notícia (placeholder por enquanto).
- Para tirar do ar depois: Settings → Pages → "Unpublish site".
