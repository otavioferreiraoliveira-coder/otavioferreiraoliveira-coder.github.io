# Tyta Privacy Policy - GitHub Pages

Este repositório hospeda a política de privacidade do Tyta em `https://otavioferreiraoliveira-coder.github.io/tyta-privacy/`

## 📋 Estrutura

```
├── tyta-privacy/
│   └── index.html (Política de privacidade em português - v1.0 + v2.0)
└── README.md
```

## 🚀 Estratégia de Lançamento

| App | Versão | Status | Certificado |
|-----|--------|--------|-------------|
| Tyta 1.0 | v1.0 | Production | 4a132037 |
| Tyta 4.0 | v2.0 | Closed Testing → Production | 4a132037 (MESMO) |

**Tyta 4.0 é um UPGRADE do Tyta 1.0** com:
- ✅ Mesmo packageName (`com.tyta.app`)
- ✅ Mesmo certificado (keystore)
- ✅ versionCode em ordem crescente (1 → 2)
- ✅ Atualização in-place automática na Play Store

## 📝 Política de Privacidade

A política hospedada cobre **ambas as versões**:
- Tyta 1.0 (v1.0): Calculador básico
- Tyta 4.0 (v2.0): Upgrade com AccessibilityService, OCR, gravação de vídeo

**URL única para ambas**: `https://otavioferreiraoliveira-coder.github.io/tyta-privacy/`

Última atualização: 15 de maio de 2026

## 🔐 Keystore & Certificado

```
Arquivo: upload-keystore.jks
Localização: D:\Cofre\Tyta 1.0\keystore\
Alias: tyta-key
Certificado SHA1: 4a132037
Validade: 25 anos (até 2051)
Senha: Tyta1.0@2026#SecureKey-Prod99

IMPORTANTE: Tyta 1.0 e Tyta 4.0 usam o MESMO keystore
```

## 📦 APKs Release

| App | Versão | Tamanho | Status |
|-----|--------|---------|--------|
| Tyta 1.0 | v1.0 | 1.64 MB | ✅ Release compilado |
| Tyta 4.0 | v2.0 | 44.35 MB | ✅ Release compilado |

Ambos assinados com o mesmo certificado (4a132037).

## 🔄 Atualizar Política no Futuro

```powershell
# 1. Editar arquivo
# C:\Temp\github-pages\otavioferreiraoliveira-coder.github.io\tyta-privacy\index.html

# 2. Fazer commit e push
cd "C:\Temp\github-pages\otavioferreiraoliveira-coder.github.io"
git add tyta-privacy/index.html
git commit -m "chore: Update Tyta privacy policy"
git push
```

## 📱 Google Play Console

**URL para ambas as versões**:
```
https://otavioferreiraoliveira-coder.github.io/tyta-privacy/
```

Configure em:
- **Tyta 1.0** (v1.0) > App Content > Privacy Policy URL: `https://otavioferreiraoliveira-coder.github.io/tyta-privacy/`
- **Tyta 4.0** (v2.0) > App Content > Privacy Policy URL: `https://otavioferreiraoliveira-coder.github.io/tyta-privacy/`

## 📂 Backups

- **Local**: `D:\Backups\Tyta-APKs-Release-*.zip`
- **USB**: `E:\Backups\` (quando conectado)
- **Cloud**: Bitwarden / 1Password (senhas + metadados)

Veja `D:\Cofre\KEYSTORE_BACKUP_METADATA.txt` para detalhes completos.
