# Pedidos de Férias – SPFx (SharePoint Framework)

## 📌 Visão Geral

Aplicação moderna desenvolvida com **SharePoint Framework (SPFx)**, **React** e **TypeScript**, que permite aos colaboradores **gerir pedidos de férias de forma intuitiva, eficaz e integrada** com o ecossistema Microsoft 365.  
A solução é responsiva, personalizável e integra com a **Microsoft Graph API** para uma experiência fluida e visualmente consistente no SharePoint.

![Node.js](https://img.shields.io/badge/Node.js-18.20.8-brightgreen.svg)
![SPFx](https://img.shields.io/badge/SharePoint%20Framework-1.20.0-green.svg)
![React](https://img.shields.io/badge/React-17.0.1-blue.svg)
![TypeScript](https://img.shields.io/badge/TypeScript-4.5.4-blue.svg)

---

## ✨ Funcionalidades Principais

- ✅ **Submissão de pedidos de férias** com formulário, incluíndo validações
- ✅ **Listagem de pedidos com filtros e ordenações**
- ✅ **Aprovação e rejeição de pedidos**
- ✅ **Integração com Microsoft Graph API** para mostrar fotos dos utilizadores na listagem
- ✅ **UI moderna e responsiva com Fluent UI**
- ✅ **Indicadores visuais do estado do pedido (cores)**

---

## 🛠️ Tecnologias Utilizadas

| Camada | Tecnologias |
|--------|-------------|
| **Frontend** | SPFx 1.20.0 · React 17 · TypeScript 4.5.4 · Fluent UI |
| **Backend/API** | PnPjs · SharePoint REST API · Microsoft Graph API |
| **Ferramentas** | Gulp · Webpack · ESLint · SASS |

---

## 🧠 Conceitos Aplicados

- 🔄 **Chamada à Microsoft Graph API** (para imagens utilizadores)
- 🧩 **Componentização avançada** com Fluent UI
- 🔐 **Integração com contexto SharePoint (SPFx Context)**
- 🚦 **Workflow de aprovação com controlo de estados**
- 📂 **Interação com listas SharePoint via REST e PnPjs**
- 🎯 **Validação de formulários com feedback visual**

---

## 🧱 Estrutura da Lista SharePoint

> A aplicação liga-se a uma lista chamada `Pedidos_de_Ferias` com a seguinte configuração:

| Coluna         | Tipo                |
|----------------|---------------------|
| Colaborador    | Person or Group     |
| Data_Inicio    | Date                |
| Data_Fim       | Date                |
| Estado         | Text                |

---

## 🚀 Instalação 

Adicionar a app, atraves do ficheiro de instalacao .sppkg, à AppCatalog no SharePoint Admin do vosso tenant 

## 📸 Capturas de Ecrã

### 🗂️ Listagem de Pedidos
![Listagem de Pedidos] 
![lista](https://github.com/zemanel20/Pedidos/tree/main/src/webparts/pedidos/assets/lista.png)

### 🗂️ Listagem de Pedidos - Pedido Pendente
![Pedido Pendente] 
![itemPendente](https://github.com/zemanel20/Pedidos/tree/main/src/src/webparts/pedidos/assets/itemPendente.png)

### 🗂️ Listagem de Pedidos - Pedido Aprovado/Recusado
![Pedido Aprovado/Recusado] 
![itemAprovadoouRejeitado](https://github.com/zemanel20/Pedidos/tree/main/src/webparts/pedidos/assets/itemAprovadoouRejeitado.png)

### 🗂️ Listagem de Pedidos - Filtragem
![Pedido Aprovado/Recusado] 
![filtragem](https://github.com/zemanel20/Pedidos/tree/main/src/webparts/pedidos/assets/filtragem.png)

### 📝 Formulário de Novo Pedido
![Novo Pedido] 
![CriacaodoPedido](https://github.com/zemanel20/Pedidos/tree/main/src/webparts/pedidos/assets/CriacaodoPedido.png)

---

## 📅 Histórico de Versões

| Versão | Data         | Novidades                                               |
|--------|--------------|---------------------------------------------------------|
| 1.0.0  |  Junho 2025  | 🚀 Versão inicial com todas as funcionalidades principais |

---

## 👨‍💻 Autor

| Nome            | Localização       | Contacto |
|-----------------|-------------------|----------|
| **José Fernandes** | Lisboa, Portugal | [LinkedIn](https://www.linkedin.com/in/jose-fernandes00/) · [GitHub](https://github.com/zemanel20) |

---

## 📜 Licença

© 2025 José Fernandes. Todos os direitos reservados.  
Este software é propriedade de José Fernandes e a sua utilização, modificação ou distribuição requer autorização expressa.

---

## 📚 Referências Úteis

- [📘 SPFx - Getting Started](https://learn.microsoft.com/en-us/sharepoint/dev/spfx/set-up-your-developer-tenant)
- [🧠 Microsoft Graph APIs](https://learn.microsoft.com/en-us/sharepoint/dev/spfx/web-parts/get-started/using-microsoft-graph-apis)
- [🧱 Fluent UI](https://developer.microsoft.com/en-us/fluentui)
- [🔧 PnPjs Docs](https://pnp.github.io/pnpjs/)
- [🛠️ SPFx Patterns & Practices](https://aka.ms/m365pnp)

---

<div align="center">

🔧 Criado com dedicação em 🇵🇹 Portugal  
💡 José Fernandes · [LinkedIn](https://www.linkedin.com/in/jose-fernandes00/) · [GitHub](https://github.com/zemanel20)

</div>
