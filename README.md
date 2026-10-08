# 🛡️ Cyber Security Hub

Repositório central dos meus laboratórios práticos de **Segurança da Informação** e **Application Security**.

Este Hub funciona como um índice para ambientes deliberadamente vulneráveis desenvolvidos para estudo, exploração controlada, análise técnica, correção e reteste.

> **Escopo:** os laboratórios deste Hub são executados somente em ambientes próprios ou expressamente autorizados.

---

## 🎯 Objetivo

O objetivo deste projeto é estudar vulnerabilidades de forma prática, acompanhando todo o ciclo:

```text
Construção do ambiente vulnerável
        ↓
Identificação da vulnerabilidade
        ↓
Exploração manual
        ↓
Análise técnica
        ↓
Compreensão do impacto
        ↓
Correção
        ↓
Reteste
```

Cada laboratório é mantido em um **repositório independente**.

---

# 🧪 Laboratórios

## 💉 SQL Injection

Laboratórios dedicados ao estudo de falhas de SQL Injection em diferentes cenários, contextos e níveis de dificuldade.

### SQLI-01

**Status:** 🟢 Em estudo

Primeiro laboratório vulnerável de SQL Injection.

O ambiente foi desenvolvido em **Django** e contém **6 flags** distribuídas pela aplicação para serem encontradas durante o processo de exploração.

**Repositório:**  
[vulnlab-sqli-01](https://github.com/iRnx/vulnlab-sqli-01)

**Branch vulnerável:**  
[vulnerable](https://github.com/iRnx/vulnlab-sqli-01/tree/vulnerable)

#### Branches do laboratório

| Branch | Finalidade |
| --- | --- |
| `main` | Apresentação e informações gerais do laboratório |
| `vulnerable` | Versão deliberadamente vulnerável utilizada para exploração e estudo |
| `fixed` | Versão corrigida após análise e remediação |

> A branch `fixed` será criada somente após a conclusão da exploração e da etapa de correção.

---

## 🌐 Cross-Site Scripting — XSS

🚧 Laboratórios ainda não adicionados.

Planejado:

- Reflected XSS
- Stored XSS
- DOM XSS
- Attribute Context
- JavaScript Context
- outros cenários

---

## 🔐 Authentication

🚧 Laboratórios ainda não adicionados.

Planejado:

- autenticação vulnerável
- proteção contra tentativas automatizadas
- sessões
- controles de acesso
- outros cenários

---

## 🔓 IDOR

🚧 Laboratórios ainda não adicionados.

---

## 🔄 CSRF

🚧 Laboratórios ainda não adicionados.

---

## 🛰️ SSRF

🚧 Laboratórios ainda não adicionados.

---

## 📁 Path Traversal

🚧 Laboratórios ainda não adicionados.

---

# 📂 Organização

Cada laboratório possui seu próprio repositório Git e segue um padrão de nomenclatura previsível.

```text
vulnlab-sqli-01
vulnlab-sqli-02
vulnlab-sqli-03

vulnlab-xss-01
vulnlab-xss-02

vulnlab-idor-01
vulnlab-csrf-01
vulnlab-ssrf-01
...
```

Todos os laboratórios seguem o mesmo padrão de branches:

```text
main
vulnerable
fixed
```

### `main`

Documentação e apresentação do laboratório.

### `vulnerable`

Código deliberadamente vulnerável utilizado durante os estudos e exercícios.

### `fixed`

Versão corrigida após a conclusão da análise da vulnerabilidade.

---

# 🧠 Metodologia de estudo

Os laboratórios seguem, sempre que possível, o mesmo processo:

1. construir o cenário vulnerável;
2. executar a aplicação em ambiente controlado;
3. identificar possíveis pontos de entrada;
4. confirmar a vulnerabilidade;
5. compreender tecnicamente por que ela ocorre;
6. explorar o cenário educacional;
7. analisar impacto e comportamento;
8. corrigir o código;
9. repetir os mesmos testes;
10. confirmar que a vulnerabilidade foi eliminada.

A intenção não é apenas encontrar uma vulnerabilidade, mas entender todo o caminho entre entrada, aplicação, componente afetado, impacto e correção.

```text
entrada controlada pelo usuário
            ↓
aplicação
            ↓
código vulnerável
            ↓
componente afetado
            ↓
impacto
            ↓
correção
            ↓
reteste
```

---

# 🧰 Tecnologias

Os laboratórios poderão utilizar diferentes tecnologias conforme o objetivo de cada exercício.

Entre elas:

- Python
- Django
- SQLite
- PostgreSQL
- HTML
- JavaScript
- HTTP
- APIs REST
- Docker

---

# 📚 Progresso

| Categoria | Labs disponíveis |
| --- | ---: |
| SQL Injection | 1 |
| XSS | 0 |
| IDOR | 0 |
| CSRF | 0 |
| Authentication | 0 |
| SSRF | 0 |
| Path Traversal | 0 |

O Hub será atualizado conforme novos laboratórios forem desenvolvidos.

---

# 🧭 Estrutura planejada

```text
Cyber Security Hub
│
├── SQL Injection
│   ├── SQLI-01 → vulnlab-sqli-01
│   ├── SQLI-02 → vulnlab-sqli-02
│   └── ...
│
├── XSS
│   ├── XSS-01 → vulnlab-xss-01
│   ├── XSS-02 → vulnlab-xss-02
│   └── ...
│
├── IDOR
├── CSRF
├── Authentication
├── SSRF
└── Path Traversal
```

---

# ⚠️ Aviso

Os projetos referenciados neste Hub contêm vulnerabilidades implementadas propositalmente.

Eles foram desenvolvidos para:

- aprendizado;
- pesquisa;
- desenvolvimento;
- treinamento de segurança;
- testes em ambientes controlados;
- sistemas próprios ou expressamente autorizados.

Não utilize os exemplos contra sistemas sem autorização.

---

## 📌 Hub

Este repositório contém apenas a documentação e os links para os laboratórios.

O código de cada máquina vulnerável permanece em seu respectivo repositório independente.
