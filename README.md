# 🍧 AçaíDeira Mix — Sistema Web

Site de delivery completo com painel administrativo.

## 📁 Arquivos

| Arquivo | Descrição |
|---------|-----------|
| `index.html` | **Site do cliente** — cardápio, montagem, carrinho, checkout |
| `dono.html` | **Painel do dono** — login, pedidos, cardápio, faturamento |

## 🚀 Como usar no VS Code / GitHub

1. Baixe os dois arquivos
2. Abra com qualquer navegador moderno (Chrome, Edge, Firefox)
3. Para GitHub Pages: faça upload dos dois arquivos num repositório e ative Pages em Settings → Pages → Branch: main

## 🔄 Sincronização entre páginas

- Abre os dois arquivos na **mesma origem** (mesmo servidor/GitHub Pages)
- Quando o dono salva o cardápio → site do cliente atualiza **instantaneamente** via `BroadcastChannel`
- Quando cliente faz pedido → painel do dono recebe **notificação em tempo real**
- Funciona entre abas do mesmo navegador

> ⚠️ No VS Code com Live Server: abra `index.html` numa aba e `dono.html` em outra. A sincronização funciona porque ambas têm a mesma origem (localhost).

## 🔒 Login do painel

- **Usuário:** `admin`
- **Senha:** `acaideira2025`
- A senha pode ser alterada em Configurações dentro do painel

## 💳 PIX

Chave PIX configurada: `84997072860`

## 📞 Contato

- WhatsApp: (84) 99982-2489
- Instagram: @acaideira_mixx

---
Desenvolvido por **João Vitor Leonardo da Silva**
