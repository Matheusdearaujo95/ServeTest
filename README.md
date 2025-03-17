# Serverest - Teste de API e Análise de Qualidade

Este repositório contém o trabalho realizado para testar a API **Serverest**. O foco foi verificar a funcionalidade da API e identificar possíveis bugs, garantindo que as funcionalidades atendam aos requisitos definidos e estejam funcionando corretamente.

---

## 📖 Descrição do Projeto

Neste projeto, realizamos a análise de qualidade da API **Serverest**, com o objetivo de testar e validar os principais endpoints da API. A análise incluiu a verificação de erros e comportamentos inesperados nos fluxos de criação, leitura, atualização e exclusão de usuários e produtos.

---

## 🚀 Funcionalidades Testadas

As principais funcionalidades testadas na API foram:

- **Gestão de Usuários**:
  - Criação de usuário via **POST /usuarios**.
  - Edição de usuário via **PUT /usuarios/{id}**.
  - Exclusão de usuário via **DELETE /usuarios/{id}**.
  - Listagem de usuários via **GET /usuarios**.
  - Busca de usuário por ID via **GET /usuarios/{id}**.

- **Gestão de Produtos**:
  - Criação de produto via **POST /produtos**.
  - Edição de produto via **PUT /produtos/{id}**.
  - Exclusão de produto via **DELETE /produtos/{id}**.
  - Listagem de produtos via **GET /produtos**.
  - Busca de produto por ID via **GET /produtos/{id}**.

---

## 🎯 Objetivos do Projeto

- **Definir Classes de Equivalência e Valores-Limite**: Foram utilizados para dividir os dados de entrada em classes de equivalência, considerando tanto os cenários positivos quanto negativos.
- **Criação de Casos de Teste**: A partir das classes de equivalência e valores-limite, foram criados casos de teste detalhados para validar a API.

---

## 📂 Arquivos Disponíveis

- **Planilha do Projeto**: Contém as classes de equivalência, valores-limite e os casos de teste desenvolvidos.
- **Mapa Mental**: Representa a estrutura do projeto e o planejamento dos testes.

---

---

## 💻 Tecnologias Utilizadas

- **Postman**: Para realizar as requisições HTTP e validar as respostas da API.
- **Jira**: Para rastrear e documentar os bugs encontrados durante os testes.
- **GitHub**: Para versionamento do código e controle do progresso dos testes.

---

## 🐛 Relatório de Bugs

Durante os testes, foram identificados **bugs críticos** que impactam a funcionalidade da API. Os problemas foram documentados e reportados no **Jira**, com uma descrição detalhada de cada bug, incluindo os casos em que os erros ocorreram.

---

## 🏆 Avaliação

O projeto foi avaliado com base nos seguintes critérios:

- Aplicação correta das técnicas de design de teste.
- Estrutura e detalhamento dos casos de teste.
- Identificação precisa de bugs e falhas.

---

## 🏁 Conclusão

Após a análise dos casos de teste executados, podemos concluir que a **API Serverest** não está completamente estável. Algumas funcionalidades, como a **exclusão de usuários** e a **edição de produtos**, apresentaram erros críticos que comprometem a operação da aplicação. A correção desses bugs é essencial antes de seguir com a implantação em produção.

---

## 🤝 Contribuições

Contribuições são bem-vindas! Para contribuir, siga os seguintes passos:

1. Faça um fork do repositório.
2. Crie uma branch para sua funcionalidade (ex.: `git checkout -b minha-nova-funcionalidade`).
3. Commit suas mudanças (ex.: `git commit -am 'Adiciona nova funcionalidade'`).
4. Faça um push para a branch (ex.: `git push origin minha-nova-funcionalidade`).
5. Abra um Pull Request.

---

## 📅 Atualizações

**Data**: 16 de Março de 2025

- Criação e execução dos 20 casos de teste para a API Serverest.
- Identificação de bugs críticos na API.
- Relatório atualizado com detalhes sobre os erros encontrados e passos para correção.

---
