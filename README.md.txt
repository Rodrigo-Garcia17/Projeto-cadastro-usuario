# 🧪 Projeto de Testes Manuais – Cadastro de Usuário

Este projeto tem como objetivo validar o **formulário de cadastro de usuário** do site [Automation Pratice](https://automationpratice.com.br/register), aplicando boas práticas de **testes manuais funcionais**.  
O foco é demonstrar habilidades em **planejamento, execução, documentação e rastreabilidade de defeitos** — competências essenciais para um QA Júnior.

---

## 📋 Objetivo

Garantir que o processo de cadastro funcione corretamente, verificando:
- Campos obrigatórios;
- Validação de e-mails e senhas;
- Mensagens de erro adequadas;
- Regras de preenchimento e feedback ao usuário.

---

## 🧩 Escopo

Funcionalidade testada: **Cadastro de Usuário**  
Foram criados e executados **8 casos de teste manuais**, abrangendo cenários positivos e negativos.

---

## 🗂️ Planejamento no Trello

O planejamento dos testes foi realizado no **Trello**, utilizando as colunas:
- **Backlog de Testes**
- **Em Execução**
- **Bloqueados**
- **Bugs Encontrados**
- **Concluídos**
- **Documentação**

🔗 [Acesse o quadro público no Trello](https://trello.com/b/PamcroH7/qa-cadastro-usuario)

![Quadro Trello](Trello/print_trello.png)

---

## 📑 Plano de Testes

O **plano de testes** foi documentado em planilha (Google Sheets), contendo:
- ID e funcionalidade testada  
- Casos de teste e pré-condições  
- Passos e entradas  
- Resultado esperado e obtido  
- Status e evidências  

🔗 [Acesse o documento completo aqui](https://docs.google.com/spreadsheets/d/1lYP_Q48ovlsMkqh27ti-SLp_1yJzHvgg/edit?usp=drive_link&ouid=108860538402249057489&rtpof=true&sd=true)

---

## 🧾 Estrutura do Projeto

QA-Cadastro-Usuario/
│
├── 📁 Evidencias/
│ ├── CT01_20251021_print1.png
│ ├── CT01_20251021_print2.png
│ ├── CT02_20251021.png
│ ├── CT03_20251021.png
│ ├── CT04_20251021.png
│ ├── CT05_20251021.png
│ ├── CT06_20251021.png
│ ├── BUG_CT07_20251021.png
│
├── 📁 Trello/
│ └── print_trello.png
│
└── 📄 README.md

---

## 🧠 Casos de Teste

Foram criados **8 casos de teste (CT01 a CT08)** cobrindo os seguintes cenários:

| ID  | Caso de Teste                                 | Resultado Esperado                        | Status |
|-----|-----------------------------------------------|--------------------------------------------|---------|
| CT01 | Cadastro com todos os campos válidos          | Cadastro realizado com sucesso             | ✅ Passou |
| CT02 | Campos obrigatórios em branco                | Exibe mensagens de erro                    | ✅ Passou |
| CT03 | Nome em branco                                | Exibe erro indicando campo obrigatório     | ✅ Passou |
| CT04 | E-mail em branco                              | Exibe erro indicando campo obrigatório     | ✅ Passou |
| CT05 | Senha em branco                               | Exibe erro indicando campo obrigatório     | ✅ Passou |
| CT06 | E-mail inválido                               | Exibe erro indicando e-mail inválido       | ✅ Passou |
| CT07 | Senha com menos de 6 caracteres               | Aceitou indevidamente → BUG reportado      | ⚠️ Falhou |
| CT08 | Campos com espaços em branco                  | Exibe erro indicando campos inválidos      | ✅ Passou |

---

## 🐞 Bug Encontrado

| ID do Caso | Descrição | Comportamento Esperado | Comportamento Atual | Evidência |
|-------------|------------|------------------------|----------------------|------------|
| CT07 | Sistema aceita senha com 3 caracteres | Deve exibir mensagem de erro sobre senha inválida | Cadastro é concluído com senha curta | [Ver print](Evidencias/BUG_CT07_20251021.png) |

---

## 📁 Evidências

As evidências visuais dos testes estão disponíveis na pasta:
[👉 Acesse as imagens aqui](./Evidencias)

Exemplo de evidência:
![Exemplo de Caso de Teste](Evidencias/CT01_20251021_print1.png)

---

## 🧰 Ferramentas Utilizadas

- 🧾 **Google Sheets** → Criação e documentação do plano de testes  
- 🗂️ **Trello** → Organização e acompanhamento da execução dos testes  
- 🌐 **Automation Pratice** → Sistema testado  
- 🖼️ **Capturas de tela** → Evidências dos resultados obtidos  
- 💻 **GitHub** → Versionamento e publicação do projeto  

---

## 🚀 Próximos Passos

- Automatizar os testes utilizando **Cypress** ou **Playwright**  
- Criar novos casos cobrindo cenários negativos mais complexos  
- Integrar evidências automáticas no pipeline de QA  

---

## 🔗 Links do Projeto

📋 **Plano de Testes:**  
[👉 Acesse no Google Sheets](https://docs.google.com/spreadsheets/d/1lYP_Q48ovlsMkqh27ti-SLp_1yJzHvgg/edit?usp=drive_link&ouid=108860538402249057489&rtpof=true&sd=true)

🗂️ **Planejamento no Trello:**  
[👉 Acesse o quadro público no Trello](https://trello.com/b/PamcroH7/qa-cadastro-usuario)

📁 **Evidências:**  
[👉 Acesse no Google Sheets](https://drive.google.com/drive/folders/1O9mCeeYpmlESNC-7_AoSN6fTyh2BnlVV?usp=drive_link)

---

## 👨‍💻 Autor

Rodrigo Garcia da Silva  
QA Júnior | Entusiasta em Qualidade de Software e Automação de Testes  
🔗 [LinkedIn](https://www.linkedin.com/in/rodrigo-garcia-da-silva/)  
📧 rodrigogarciia@hotmail.com 

---

⭐ Se este projeto te inspirou, não esqueça de deixar um **Star** no repositório!


