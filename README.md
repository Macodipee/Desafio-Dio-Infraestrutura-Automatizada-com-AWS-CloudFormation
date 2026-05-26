# Laboratório: Automatizando Infraestrutura com AWS CloudFormation

Este repositório contém minhas anotações e aprendizados do laboratório de infraestrutura como código usando **AWS CloudFormation**, realizado na DIO.

---

## 📌 Objetivo do Desafio

- Colocar em prática os conceitos vistos nas aulas.
- Criar uma infraestrutura automatizada usando **CloudFormation**.
- Documentar o processo de forma simples e clara.
- Utilizar o **GitHub** como portfólio técnico.

---

## 🧠 Conceitos Trabalhados

- Infraestrutura como Código (**IaC**)
- Templates do **AWS CloudFormation**
- Criação e atualização de **stacks**
- Parâmetros, recursos e saídas em templates
- Uso básico do **AWS Management Console** ou **AWS CLI** (se aplicável)

---

## ⚙️ Passo a Passo (Resumo da Prática)

> Obs: Ajuste esta parte de acordo com o que você fez nas aulas.

1. **Acesso à AWS**
   - Acessei a conta AWS fornecida no laboratório / minha conta pessoal.
   - Abri o serviço **CloudFormation**.

2. **Criação do Template**
   - Criei um template em YAML/JSON contendo:
     - (Exemplo) Uma VPC, sub-redes, security groups e uma instância EC2  
     - ou o que exatamente foi feito no seu laboratório

3. **Upload do Template**
   - No CloudFormation, selecionei **Create stack**.
   - Enviei o arquivo do template.
   - Defini parâmetros necessários (nome de stack, chave SSH, etc., se houve).

4. **Deploy da Stack**
   - Confirmei as configurações.
   - Aguardei até o status ficar como **CREATE_COMPLETE**.

5. **Validação**
   - Acessei os recursos criados (por exemplo, EC2, VPC, etc.).
   - Testei se tudo estava funcionando como esperado.

6. **Limpeza (se aplicável)**
   - Deletei a stack para remover todos os recursos automaticamente.

## ✍️ Anotações Pessoais e Insights

- Vantagem do CloudFormation:
  - Facilita a **recriação** da mesma infraestrutura em minutos.
  - Reduz erros de configuração manual.
- Aprendi a importância de:
  - Versionar templates no GitHub.
  - Documentar cada etapa para conseguir repetir o processo depois.
- Pontos que ainda quero aprofundar:
  - Uso de **parâmetros** e **outputs** mais avançados.
  - Integração com **CI/CD** para deploy automatizado.

---

## 🧾 Tecnologias Utilizadas

- **AWS CloudFormation**
- **GitHub** para versionamento e documentação
- Markdown (`README.md`) para registro da experiência

---

## 🚀 Como Este Projeto Contribui para Meu Aprendizado

- Pratiquei Infraestrutura como Código na prática.
- Fortaleci o uso do GitHub como portfólio técnico.
- Ganhei mais familiaridade com o ecossistema AWS.

---

## 📎 Referências

- Documentação oficial do AWS CloudFormation  
- Materiais de Git e GitHub indicados na DIO  
- Conteúdo das aulas do próprio laboratório
