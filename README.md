# 🧪 QA Portfolio — Testes Manuais

> Portfólio de Quality Assurance com foco em testes manuais, documentação de bugs e planos de teste aplicados a sistemas reais.

---

## 👤 Sobre

Olá! Sou estudante de [**seu curso**] com foco em Quality Assurance. Este repositório reúne minha prática em testes manuais, incluindo bug reports, planos de teste, testes exploratórios e checklists — aplicados a sistemas reais e ambientes de treino como o [SauceDemo](https://www.saucedemo.com).

---

## 📁 Estrutura do Repositório

```
qa-portfolio/
│
├── bug-reports/
│   ├── BUG-001-login-tela-branca.md
│   ├── BUG-002-carrinho-contador.md
│   └── ...
│
├── planos-de-teste/
│   ├── PT-001-saucedemo-login.md
│   ├── PT-002-saucedemo-checkout.md
│   └── ...
│
├── testes-exploratorios/
│   ├── EXP-001-saucedemo-carrinho.md
│   └── ...
│
├── checklists/
│   ├── checklist-login.md
│   ├── checklist-formulario-cadastro.md
│   └── ...
│
└── README.md
```

---

## 🐛 Bug Reports

Cada bug report segue o padrão:

| Campo | Descrição |
|---|---|
| **ID** | Identificador único (ex: BUG-001) |
| **Título** | Descrição objetiva do problema |
| **Severidade** | 🔴 Crítico / 🟡 Alto / 🟣 Médio / 🟢 Baixo |
| **Ambiente** | Produção / Homologação / Desenvolvimento |
| **Passos** | Numerados e reproduzíveis |
| **Resultado Esperado** | O que deveria acontecer |
| **Resultado Obtido** | O que realmente aconteceu |
| **Evidência** | Print ou vídeo anexado |

📂 Ver todos os bug reports: [`/bug-reports`](./bug-reports/)

---

## 📋 Planos de Teste

Os planos cobrem funcionalidades específicas com casos de teste estruturados.

### Exemplo — SauceDemo: Login

| ID | Descrição | Status |
|---|---|---|
| TC001 | Login com credenciais válidas (standard_user) | ✅ PASS |
| TC002 | Login com usuário bloqueado (locked_out_user) | ✅ PASS |
| TC003 | Login com senha incorreta | ✅ PASS |
| TC004 | Login com campo usuário em branco | ✅ PASS |
| TC005 | Login com campo senha em branco | ✅ PASS |
| TC006 | Ambos os campos em branco | ✅ PASS |
| TC007 | Campo senha deve mascarar caracteres | ✅ PASS |
| TC008 | Redirecionamento após login válido | ✅ PASS |

📂 Ver todos os planos: [`/planos-de-teste`](./planos-de-teste/)

---

## 🔍 Testes Exploratórios

Sessões com tempo fixo (60–90 min) explorando funcionalidades sem script rígido, documentando descobertas, anomalias e perguntas.

**Formato de cada sessão:**
- 🎯 Missão (o que quero descobrir)
- 🧭 O que foi testado
- 🐛 Anomalias encontradas
- 📌 Próximos passos

📂 Ver sessões: [`/testes-exploratorios`](./testes-exploratorios/)

---

## ✅ Checklists

Checklists reutilizáveis para fluxos comuns:

- [ ] Login / Autenticação
- [ ] Formulário de Cadastro
- [ ] Carrinho de Compras
- [ ] Checkout / Pagamento
- [ ] Responsividade Mobile

📂 Ver checklists: [`/checklists`](./checklists/)

---

## 🛠️ Ferramentas & Tecnologias

![Markdown](https://img.shields.io/badge/Markdown-000000?style=flat&logo=markdown&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)
![Chrome DevTools](https://img.shields.io/badge/Chrome_DevTools-4285F4?style=flat&logo=googlechrome&logoColor=white)

- **Documentação:** Markdown / GitHub
- **Gestão de casos:** TestRail (estudando) / Excel / Notion
- **Ambientes de treino:** SauceDemo, OrangeHRM, The Internet (Heroku)
- **Evidências:** Loom, Lightshot, Chrome DevTools

---

## 📊 Sistemas Testados

| Sistema | Tipo | Área Testada |
|---|---|---|
| [SauceDemo](https://www.saucedemo.com) | E-commerce | Login, Carrinho, Checkout |
| [OrangeHRM Demo](https://opensource-demo.orangehrmlive.com) | RH | Cadastro, Navegação |
| [The Internet](https://the-internet.herokuapp.com) | Multi-funcional | Formulários, Autenticação, Upload |

---

## 📈 Status do Portfólio

| Tipo | Quantidade |
|---|---|
| 🐛 Bug Reports | 0 (em construção) |
| 📋 Planos de Teste | 0 (em construção) |
| 🔍 Sessões Exploratórias | 0 (em construção) |
| ✅ Checklists | 0 (em construção) |

---

## 📬 Contato

**Cleyton de Andrade V.**
📧 Cleytonvirino@gmail.com
💼 [linkedin](https://www.linkedin.com/in/cleyton-virino-1aba97234/)

---

<p align="center">
  <i>Este portfólio está em constante evolução conforme avanço nos estudos de QA. ⚡</i>
</p>
