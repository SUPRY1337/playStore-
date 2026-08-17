# 🚀 Guia de Hospedagem Permanente - PeriApp Store

Seu site está pronto para ser hospedado de forma **permanente e gratuita**! Escolha uma das opções abaixo.

---

## ✅ Opção 1: Vercel (Recomendado - Mais Fácil)

### Passo 1: Criar Conta no GitHub
1. Acesse [github.com](https://github.com)
2. Clique em **"Sign up"**
3. Preencha os dados e confirme o email

### Passo 2: Criar Repositório no GitHub
1. Clique no **"+"** no canto superior direito
2. Selecione **"New repository"**
3. Dê um nome (ex: `periapp-store`)
4. Clique em **"Create repository"**

### Passo 3: Fazer Upload dos Arquivos
1. Na página do repositório, clique em **"Add file"** → **"Upload files"**
2. Arraste ou selecione todos os arquivos da pasta `periapp_store`
3. Clique em **"Commit changes"**

### Passo 4: Conectar ao Vercel
1. Acesse [vercel.com](https://vercel.com)
2. Clique em **"Sign up"** e escolha **"Continue with GitHub"**
3. Autorize o Vercel a acessar seus repositórios
4. Clique em **"Import Project"**
5. Selecione o repositório `periapp-store`
6. Clique em **"Deploy"**

### Resultado:
Seu site estará online em: `https://periapp-store-seu-usuario.vercel.app`

---

## ✅ Opção 2: GitHub Pages (Alternativa Gratuita)

### Passo 1: Criar Repositório
1. Acesse [github.com](https://github.com)
2. Crie um novo repositório chamado **`seu-usuario.github.io`**
   - ⚠️ Importante: Use exatamente esse nome!

### Passo 2: Fazer Upload dos Arquivos
1. Clique em **"Add file"** → **"Upload files"**
2. Arraste todos os arquivos da pasta `periapp_store`
3. Clique em **"Commit changes"**

### Passo 3: Ativar GitHub Pages
1. Vá em **Settings** (Configurações)
2. Clique em **"Pages"** no menu lateral
3. Em **"Source"**, selecione **"main"** (ou **"master"**)
4. Clique em **"Save"**

### Resultado:
Seu site estará online em: `https://seu-usuario.github.io`

---

## 🔄 Como Atualizar o APK Depois

Se você tiver uma versão nova do PeriApp e quiser atualizar o site:

### Método 1: Via GitHub (Recomendado)
1. Descompacte o arquivo ZIP
2. Substitua o arquivo `periapp.apk` na pasta `downloads/`
3. Faça upload dos arquivos novamente no repositório
4. O site atualiza automaticamente em poucos minutos!

### Método 2: Via Git (Terminal)
```bash
# Navegue até a pasta do projeto
cd periapp_store

# Atualize o APK na pasta downloads/
# (Substitua o arquivo periapp.apk)

# Envie as mudanças para o GitHub
git add .
git commit -m "Atualização: PeriApp v2.0"
git push
```

---

## 📝 Estrutura de Arquivos

```
periapp_store/
├── index.html              # Página principal
├── package.json            # Metadados do projeto
├── vercel.json             # Configuração do Vercel
├── HOSPEDAGEM.md           # Este arquivo
├── assets/
│   ├── css/
│   │   └── style.css       # Estilos
│   └── img/
│       └── periapp_icon.webp # Ícone do app
└── downloads/
    └── periapp.apk         # Seu aplicativo
```

---

## 🎯 Resumo Rápido

| Plataforma | Tempo de Setup | Custo | Facilidade |
|-----------|----------------|-------|-----------|
| **Vercel** | 5 min | Grátis | ⭐⭐⭐⭐⭐ |
| **GitHub Pages** | 3 min | Grátis | ⭐⭐⭐⭐ |

---

## ❓ Dúvidas Frequentes

**P: O site vai ficar online para sempre?**
R: Sim! Enquanto você manter o repositório no GitHub, o site fica online indefinidamente.

**P: Preciso de cartão de crédito?**
R: Não! Vercel e GitHub Pages são completamente gratuitos.

**P: Posso usar um domínio personalizado?**
R: Sim! Ambas as plataformas permitem conectar domínios próprios (veja a documentação delas).

**P: Quanto tempo leva para o site ficar online?**
R: Vercel: 1-2 minutos. GitHub Pages: 5-10 minutos.

---

## 🚀 Próximos Passos

1. Escolha uma das opções acima
2. Siga os passos exatamente como descrito
3. Teste o link no seu celular
4. Compartilhe o QR Code com seus usuários!

**Boa sorte! 🎉**
