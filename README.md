```markdown
# 🐾 Pet&Style - Loja de Pets com Estilo

Este é um projeto fictício de uma loja online chamada **Pet&Style**, especializada em produtos estilosos para pets.  
O objetivo é aplicar conceitos de **Tailwind CSS** e **responsividade** em um site simples e moderno.

---

## 🚀 Tecnologias utilizadas
- **HTML5**: Estrutura semântica da página.
- **Tailwind CSS (via CDN)**: Estilização com classes utilitárias.
- **JavaScript simples**: Atualização automática do ano no footer.

---

## 📂 Estrutura do projeto
```
PETSTYLE-LOJA-VIRTUAL/
├── index.html  # Página principal
├── img/        # Pasta com imagens (logo e produtos)
│   ├── logo.png
│   ├── caminha.png
│   ├── brinquedo.png
│   ├── coleira.png
│   └── acessorio.png
├── README.md
```

---

## 📑 Seções da página
1. **Header**: Logo e menu de navegação.
2. **Hero**: Chamada principal com imagem de destaque.
3. **Produtos**: Grid responsivo com 4 cards de produtos.
4. **Depoimentos**: Comentários fictícios de clientes.
5. **Contato**: Informações de contato + formulário.
6. **Footer**: Logo, links rápidos e direitos autorais com ano automático.

---

## 📱 Responsividade
- Estratégia **Mobile First**.
- Uso de breakpoints do Tailwind (`sm:`, `md:`, `lg:`).
- Layout adaptado para celulares, tablets e desktops.

---

## ▶️ Como rodar o projeto
1. Clone ou baixe este repositório.
2. Certifique-se de que a estrutura de pastas está correta (especialmente a pasta `img/`).
3. Abra o arquivo `index.html` em qualquer navegador.

---

## ✨ Demonstração
- O site exibe os produtos fictícios da loja Pet&Style.
- O footer mostra automaticamente o ano atual:
  ```html
  <p>&copy; <span id="ano"></span> Pet&Style - Todos os direitos reservados.</p>
  ```
  ```javascript
  document.getElementById("ano").textContent = new Date().getFullYear();
  ```

---

## 📌 Observações
- As imagens podem ser substituídas por fotos reais de produtos.
- O projeto pode ser facilmente publicado em **GitHub Pages**, **Vercel** ou **Netlify**.

---
```

---
