# PeriApp - Finanças | Página de Download

Este é um clone da página de download do Google Play Store customizado para o **PeriApp - Finanças**.

## 📁 Estrutura de Pastas

```
periapp_store/
├── index.html              # Página principal
├── README.md               # Este arquivo
├── assets/
│   ├── css/
│   │   └── style.css       # Estilos da página
│   └── img/
│       └── periapp_icon.webp  # Ícone do app
└── downloads/              # 📌 COLOQUE SEU APK AQUI
    └── (seu_app.apk)
```

## 🚀 Como Usar

### 1. Adicionar seu APK
Coloque o arquivo `.apk` do PeriApp na pasta `downloads/`. Exemplo:
```
downloads/periapp_v2.1.5.apk
```

### 2. Visualizar Localmente
Abra o arquivo `index.html` em qualquer navegador:
```bash
# No terminal, dentro da pasta periapp_store:
python3 -m http.server 8000

# Acesse em seu navegador:
# http://localhost:8000
```

### 3. Subir para um Servidor
Se você quiser deixar o site online:

**Opção 1: Vercel (Recomendado)**
1. Crie uma conta em [vercel.com](https://vercel.com)
2. Faça upload da pasta `periapp_store`
3. Seu site estará online em poucos segundos

**Opção 2: GitHub Pages**
1. Crie um repositório no GitHub
2. Faça upload dos arquivos
3. Ative o GitHub Pages nas configurações

## 📝 Personalizações

### Alterar o Ícone
Substitua o arquivo `assets/img/periapp_icon.webp` por sua imagem.

### Alterar as Screenshots
Edite o arquivo `index.html` e atualize as URLs das imagens na seção de screenshots.

### Alterar Informações do App
Edite o arquivo `index.html` e procure por:
- `<h1>PeriApp - Finanças</h1>` - Nome do app
- `<a href="#" class="developer">PeriApp Desenvolvimento</a>` - Nome do desenvolvedor
- Estatísticas (avaliações, downloads, etc.)
- Descrição do app na seção "Sobre este app"

## 🔗 Link de Download

O botão "Baixar APK" aponta para a pasta `/downloads/`. Certifique-se de que seu arquivo `.apk` está lá!

## 📱 Responsividade

O site é totalmente responsivo e funciona perfeitamente em:
- ✅ Desktop
- ✅ Tablet
- ✅ Celular

## 🎨 Cores Principais

- Azul Primário: `#0066cc`
- Cinza Escuro: `#1f2937`
- Cinza Claro: `#f5f5f5`

## 📞 Suporte

Se tiver dúvidas sobre como usar este template, consulte a documentação do Google Play Store ou entre em contato com o desenvolvedor.

---

**Criado com ❤️ para o PeriApp**
