# 🛒 SauceDemo & BlazeDemo - Primeiros Testes E2E

&gt; Meus primeiros testes de automação com Playwright. Código linear, focado em aprendizado de seletores e fluxos completos.

---

## 📋 Projetos incluídos

### 1. SauceDemo - E-commerce
Site: [saucedemo.com](https://www.saucedemo.com)

**Fluxo testado:**
1. Acessa a página de login
2. Realiza login com `standard_user`
3. Verifica acesso à página de produtos
4. Adiciona **Sauce Labs Backpack** ao carrinho
5. Verifica badge do carrinho (quantidade: 1)
6. Acessa página do carrinho
7. Valida produto, quantidade e preço ($29.99)

**Arquivo:** `tests/saucedemo.spec.js`

---

### 2. BlazeDemo - Reserva de Passagens
Site: [blazedemo.com](https://www.blazedemo.com)

**Fluxo testado:**
1. Acessa o site
2. Seleciona origem: **Boston**
3. Seleciona destino: **Rome**
4. Busca voos disponíveis
5. Escolhe primeiro voo
6. Preenche dados pessoais e cartão (Visa)
7. Finaliza compra

**Arquivo:** `tests/blazedemo.spec.js`

---

## 🚀 Como rodar

### Pré-requisitos
- Node.js (versão 18 ou superior)
- npm instalado

### Instalar dependências
```bash
npm install
npx playwright install
