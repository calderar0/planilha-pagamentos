# Planilha de Controle de Pagamentos

![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google_Sheets-34A853?style=for-the-badge&logo=google-sheets&logoColor=white)
![Licença](https://img.shields.io/badge/licen%C3%A7a-MIT-blue.svg?style=for-the-badge)

Uma ferramenta prática e eficiente para organizar, controlar e nunca mais esquecer suas contas a pagar. Tenha uma visão clara de todos os seus compromissos financeiros, evite multas por atraso e gerencie seus pagamentos de forma centralizada.

## 🎯 Objetivo do Projeto

Esta planilha foi criada para resolver um problema comum: a dificuldade de acompanhar múltiplas contas e datas de vencimento. Ela serve como um centro de controle financeiro, ajudando o usuário a visualizar rapidamente o que precisa ser pago, o que já foi pago e o que está em atraso.

## ✨ Funcionalidades Principais

* **Lançamento Detalhado:** Registre todas as suas contas, boletos e faturas na aba `NOTAS`.
* **Dashboard Resumido:** A aba `TITULAR` oferece um painel principal com os totais e um resumo do status dos pagamentos.
* **Status de Pagamento:** Acompanhe facilmente cada conta com status como "Pendente", "Pago" e "Atrasado".
* **Relatórios (Informes):** Gere `INFORMES` para analisar seus gastos por período ou categoria.
* **Totalmente Customizável:** Use a aba `TABELAS` para personalizar categorias, formas de pagamento e outras listas, adaptando a planilha à sua realidade.
* **Alertas Visuais:** Utiliza formatação condicional para destacar contas próximas do vencimento ou já vencidas.

## 📂 Estrutura da Planilha

A planilha é inteligentemente dividida em abas, cada uma com um propósito claro para facilitar o uso e a organização:

### 📝 `NOTAS`
A base operacional da planilha. É aqui que você deve **lançar todas as suas contas a pagar**. Cada linha representa uma fatura ou boleto. A precisão dos dados inseridos aqui (descrição, valor, vencimento) é crucial para o funcionamento do sistema.

### 📊 `TITULAR`
O seu painel de controle (Dashboard). Esta aba consolida as informações da aba `NOTAS` e apresenta um **resumo gerencial**. Aqui você encontra os totais (a pagar, pago) e pode ter uma visão rápida da saúde financeira do período. Geralmente, esta aba é bloqueada para edição, pois seus dados são automáticos.

### 📈 `INFORMES`
A sua central de relatórios. Esta aba é projetada para **análises mais profundas**, permitindo visualizar os pagamentos agrupados por mês, por categoria de despesa, ou por fornecedor, por exemplo.

### 🗂️ `TABELAS`
A aba de configurações. Aqui você **personaliza as opções** que aparecerão em menus na aba `NOTAS`. Por exemplo, você pode definir suas próprias `Categorias` de despesa (Ex: Moradia, Transporte, Educação, Lazer) ou os `Status` de pagamento. Isso garante consistência e agiliza o preenchimento.

## 🚀 Como Utilizar

1.  **Download:** Baixe o arquivo `.xlsx` a partir deste repositório (`Code` -> `Download ZIP`).
2.  **Abra o Arquivo:** Utilize o Microsoft Excel (recomendado) ou Google Sheets.
3.  **Personalize as Tabelas:** Antes de começar, vá para a aba `TABELAS` e edite/adicione as categorias e outras opções para que elas façam sentido para você.
4.  **Lance suas Contas:** Mude para a aba `NOTAS` e comece a registrar todas as suas contas a pagar, preenchendo colunas como data de vencimento, descrição e valor.
5.  **Atualize o Status:** Conforme for realizando os pagamentos, volte na aba `NOTAS` e altere o status da respectiva conta para "Pago".
6.  **Acompanhe os Resultados:** Navegue até as abas `TITULAR` e `INFORMES` para visualizar os resumos e relatórios, que são atualizados automaticamente.

## 🛠️ Detalhes Técnicos

Esta planilha faz uso de recursos como:
* **Fórmulas:** `SOMASES`, `CONT.SES`, `PROCV` para buscar e agregar dados.
* **Validação de Dados:** Para criar menus suspensos na aba `NOTAS` com base nas opções definidas na aba `TABELAS`.
* **Formatação Condicional:** Para colorir automaticamente as linhas ou células com base no status do pagamento (ex: vermelho para atrasado, verde para pago).
* **Segurança:** Nenhuma macro (VBA) é utilizada, tornando o arquivo seguro e compatível com a maioria dos softwares de planilha.

## 🤝 Como Contribuir

Sua contribuição é bem-vinda! Se você tem sugestões de melhorias, novas funcionalidades ou encontrou algum erro, por favor:

* Abra uma **Issue** para detalhar sua sugestão ou o problema encontrado.
* Faça um **Fork** do repositório e envie um **Pull Request** com suas alterações.

## 📜 Licença

Este projeto foi desenvolvido por [Felipe Soares Calderaro](https://github.com/calderar0) com base no curso oferecido pela DIO em parceria com o Santander.
