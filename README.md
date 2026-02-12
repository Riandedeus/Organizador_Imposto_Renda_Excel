---

# 📑 Organizador de Documentos para Imposto de Renda (IRPF)

Este projeto é uma ferramenta de gestão de dados desenvolvida em Excel para facilitar o processo de declaração do Imposto de Renda Pessoa Física. O objetivo é servir como um **hub centralizador**, onde o contribuinte organiza informações de titulares, dependentes, informes de rendimentos e notas de corretagem antes de preencher o sistema da Receita Federal.

---

## 📂 Estrutura da Planilha

O arquivo está dividido em abas estratégicas para cobrir os principais pilares da declaração:

| Aba | Função |
| --- | --- |
| **TÍTULAR** | Cadastro de dados básicos, CPF, ocupação e informações dos dependentes. |
| **INFORMES** | Registro de rendimentos tributáveis e bancos. |
| **NOTAS** | Consolidação de operações e controle de preço médio. |
| **BANCO_APOIO** | Base de dados contendo códigos de bens, instituições financeiras e parâmetros do sistema. |

---

## 🛠️ Como Utilizar

1. **Identificação:** Comece preenchendo a aba `TÍTULAR` com os dados que serão solicitados logo na abertura da declaração.
2. **Coleta de Informes:** À medida que receber os documentos do seu banco ou RH, lance os valores na aba `INFORMES`.
3. **Renda Variável:** Utilize a aba `NOTAS` para registrar suas compras e vendas de ativos durante o ano-calendário. Isso facilitará o preenchimento da seção "Bens e Direitos" e "Operações Comuns/Day Trade".
4. **Conferência:** Use os totais gerados na planilha para validar os campos no Programa Gerador da Declaração (PGD IRPF).

---

## ⚠️ Avisos Importantes

* **Finalidade Informativa:** Esta planilha é uma ferramenta de **organização**. Ela não substitui o programa oficial da Receita Federal e não realiza o envio da declaração.
* **Segurança de Dados:** Como este arquivo contém dados sensíveis (CPF, saldos bancários), recomenda-se salvar o arquivo com senha (Arquivo > Informações > Proteger Pasta de Trabalho > Criptografar com Senha).

---
