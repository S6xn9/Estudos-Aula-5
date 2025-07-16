
# ⭐ HTML - Ícone de Favoritos (Favicon)

📅 Criado em: **16 de julho de 2025**  
📚 Matéria:**Programação Web (HTML5 e CSS3)**  
✍️ Autor: **Marco**

---

## 🎯 TEMA: Como adicionar o ícone de favoritos (favicon) em páginas HTML

---

## 1. 🧠 O que é um Favicon?

- Um pequeno ícone que representa o site.
- Aparece na:
  - Aba do navegador
  - Lista de favoritos
  - Histórico
  - Atalhos da área de trabalho

---

## 2. 🔗 Como Inserir o Favicon

- Use a tag `<link>` dentro do `<head>`

```html
<link rel="icon" type="image/x-icon" href="favicon.ico">
```

### Principais Atributos:
| Atributo | Descrição |
|----------|-----------|
| `rel="icon"` | Informa que o link é um favicon |
| `href="..."` | Caminho para o arquivo do ícone |
| `type="..."` | Tipo de mídia (MIME type) |
| `sizes="..."` | Tamanhos suportados (opcional) |

---

## 3. 🗂️ Formatos Comuns

| Formato | Vantagens | Tipo MIME |
|---------|-----------|-----------|
| `.ico` | Suporta múltiplos tamanhos | image/x-icon |
| `.png` | Leve, transparência, alta qualidade | image/png |
| `.gif` | Transparência e animação | image/gif |
| `.svg` | Vetorial, ideal para retina | image/svg+xml |

---

## 4. 📐 Tamanhos Recomendados

- 16×16: aba do navegador
- 32×32, 48×48, 64×64: tamanhos variados
- 128×128, 192×192, 512×512: alta resolução e atalhos

### Exemplo com múltiplas versões:

```html
<link rel="icon" type="image/png" href="favicon-16x16.png" sizes="16x16">
<link rel="icon" type="image/png" href="favicon-32x32.png" sizes="32x32">
<link rel="icon" type="image/x-icon" href="favicon.ico">
```

---

## 5. 🧪 Exemplo Completo

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Minha Página com Favicon</title>

  <link rel="icon" type="image/x-icon" href="favicon.ico">
  <link rel="icon" type="image/png" href="meu-favicon.png">
  <link rel="icon" type="image/svg+xml" href="meu-favicon.svg">
  <link rel="apple-touch-icon" href="apple-touch-icon.png">
</head>
<body>

  <h1>Bem-vindo ao Meu Site!</h1>
  <p>Observe o ícone na aba do seu navegador.</p>

</body>
</html>
```

---

### 📌 Dicas Finais

- Guarde todos os ícones na pasta do projeto.
- Use o favicon para fortalecer a identidade visual.
- Teste em diferentes navegadores para garantir compatibilidade.

---
mpatibilidade.

---
