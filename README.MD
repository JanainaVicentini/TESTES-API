# 🧪 Testes de API – Sprint 4

Este projeto foi desenvolvido como parte da Sprint 4 da formação em QA da TripleTen. O objetivo é testar diferentes comportamentos da API relacionada à manipulação de produtos e kits, utilizando ferramentas como Postman, cURL, e princípios de design de testes.

---

## 📌 Conteúdos abordados

- O que é uma API e como ela funciona
- Arquitetura REST e estrutura HTTP
- Testes de API no Postman
- URL dinâmica e geração de cURL
- Logs e documentação da API (Swagger / Apidoc)
- Design de testes (positivos, negativos, valores-limites)
- Checklist de testes de API
- Relatórios de bugs e validação

---

## 📊 Casos de Teste - Resumo

| ID | Título do Caso de Teste                             | Resultado Esperado                   | Resultado Real | Status    |
|----|------------------------------------------------------|--------------------------------------|----------------|-----------|
| 1  | Adicionar produtos existentes a um kit               | 200 OK                               | 200 OK         | APROVADO  |
| 2  | Atualizar a quantidade de um produto no kit          | 200 OK                               | 200 OK         | APROVADO  |
| 3  | Adicionar 29 produtos distintos a um kit             | 200 OK - quantidade atualizada       | 200 OK         | APROVADO  |
| 4  | Adicionar 30 produtos distintos a um kit             | 200 OK - quantity atualizado para 34 | 200 OK         | APROVADO  |
| 5  | Testar produto inexistente                           | 404 Not Found                        | 404 Not Found  | APROVADO  |
| 6  | Validar limites máximos de produtos por kit          | 400 Bad Request                      | 400 Bad        | APROVADO  |

➡️ A planilha completa com todos os testes está disponível [aqui](./TESTES-APIS.csv)

---

## 🛠️ Ferramentas utilizadas

- Postman
- cURL
- VS Code
- Git e GitHub

---

## 📎 Autora

**Janaina Vicentini**  
_"A qualidade de um produto é reflexo do cuidado e dedicação de toda a equipe."_  
🔗 [LinkedIn](https://www.linkedin.com) (https://www.linkedin.com/in/janaina-vicentin/)

---

## 🧾 Licença

Este projeto é de uso educacional e não possui licença comercial.
