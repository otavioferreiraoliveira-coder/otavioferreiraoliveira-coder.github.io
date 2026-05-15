# Tyta Privacy Policy - GitHub Pages

Este repositório hospeda a política de privacidade do Tyta em `https://otavioferreiraoliveira-coder.github.io/tyta-privacy/`

## Estrutura

```
├── tyta-privacy/
│   └── index.html (Política de privacidade em português)
└── README.md
```

## Como fazer upload para GitHub

### 1. Criar repositório no GitHub

1. Vá para https://github.com/new
2. Nome: `otavioferreiraoliveira-coder.github.io`
3. Descrição: "Tyta Privacy Policy and Resources"
4. Marque: "Public"
5. Clique: "Create repository"

### 2. Fazer push do repositório local

```powershell
cd "C:\Temp\github-pages\otavioferreiraoliveira-coder.github.io"

# Adicionar remote
git remote add origin https://github.com/otavioferreiraoliveira-coder/otavioferreiraoliveira-coder.github.io.git

# Fazer push
git push -u origin main
```

### 3. Verificar publicação

Aguarde 2-5 minutos e acesse:
```
https://otavioferreiraoliveira-coder.github.io/tyta-privacy/
```

## Atualizar política no futuro

```powershell
# 1. Editar arquivo
# C:\Temp\github-pages\otavioferreiraoliveira-coder.github.io\tyta-privacy\index.html

# 2. Fazer commit e push
cd "C:\Temp\github-pages\otavioferreiraoliveira-coder.github.io"
git add tyta-privacy/index.html
git commit -m "chore: Update Tyta privacy policy"
git push
```

## Usar em Google Play Console

**URL para Play Console**: `https://otavioferreiraoliveira-coder.github.io/tyta-privacy/`

Adicione esta URL em:
- Tyta 1.0 > App Content > Privacy Policy URL
- Tyta 4.0 > App Content > Privacy Policy URL
