# Como publicar este site no GitHub Pages

Este pacote contém a versão estática pronta para hospedar. Siga os passos abaixo.

## 1. Criar o repositório no GitHub

1. Acesse https://github.com/new
2. Dê um nome ao repositório, por exemplo: `catalogo-cabos-topologias`
3. Deixe marcado como **Public** (obrigatório para GitHub Pages gratuito)
4. Clique em **Create repository**

## 2. Fazer upload dos arquivos

Na página do repositório recém-criado:

1. Clique em **Add file → Upload files**
2. Arraste todos os arquivos desta pasta (`index.html`, `favicon.ico`, `robots.txt`, `_headers` e a pasta `assets`) para a área indicada
3. Clique em **Commit changes**

> Dica: se preferir usar Git no computador, rode os comandos:
> ```bash
> git init
> git add .
> git commit -m "Primeira versão do site"
> git branch -M main
> git remote add origin https://github.com/SEU-USUARIO/catalogo-cabos-topologias.git
> git push -u origin main
> ```

## 3. Ativar o GitHub Pages

1. No repositório, vá em **Settings → Pages** (ou https://github.com/SEU-USUARIO/catalogo-cabos-topologias/settings/pages)
2. Em **Source**, selecione **Deploy from a branch**
3. Em **Branch**, escolha `main` e a pasta `/ (root)`
4. Clique em **Save**

Aguarde alguns minutos. O site ficará disponível em:

```
https://SEU-USUARIO.github.io/catalogo-cabos-topologias/
```

## Estrutura de arquivos

```
index.html      → Página inicial (obrigatória)
assets/         → CSS e JavaScript compilados
favicon.ico     → Ícone do site
robots.txt      → Instruções para mecanismos de busca
_headers        → Cabeçalhos HTTP (opcional, usado por algumas plataformas)
```

## Observação importante

Esta é uma versão estática. Se você quiser continuar editando pelo Lovable depois, recomendo conectar o projeto ao GitHub pelo próprio Lovable (menu **+ → GitHub → Connect project**), que mantém o código em sincronia automática.
