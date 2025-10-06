# 🚀 Desafio DIO - AWS CloudFormation + S3

Repositório criado para documentar a atividade prática do curso da [Digital Innovation One (DIO)](https://www.dio.me/), implementando uma infraestrutura automatizada com *AWS CloudFormation* e hospedando um site estático no *Amazon S3*.

---

## 🎯 Objetivo do Desafio
- Aplicar conceitos de *Infraestrutura como Código (IaC)* com AWS CloudFormation.
- Criar um *bucket S3* configurado para hospedagem de site estático.
- Publicar um site simples (HTML) e validar o funcionamento via URL.
- Documentar todo o processo e evidências no GitHub.

---

## 📂 Estrutura do Repositório

dio-cloudformation-s3/
-  ├─ README.md
-  ├─ templates/
-  │  └─ s3-static-website.yaml
-  └─ images/
-  ├─ stack-create-in-progress.png
-  ├─ stack-create-complete.png
-  ├─ outputs-website-url.png
-   ─ site-online.png

---

## 📜 Template utilizado

O arquivo principal usado neste desafio está em [templates/s3-static-website.yaml](./templates/s3-static-website.yaml).

Ele cria:
- Um bucket S3 com *WebsiteConfiguration* (index e error page).
- Uma *BucketPolicy* para permitir acesso público de leitura.
- Outputs com o BucketName e o WebsiteURL.

---

## 🖼️ Evidências do Desafio

### 1️⃣ Criação da pilha no CloudFormation  
![Stack In Progress](./images/stack-create-in-progress.png)

### 2️⃣ Pilha criada com sucesso  
![Stack Complete](./images/stack-create-complete.png)

### 3️⃣ Saídas do CloudFormation (WebsiteURL gerado)  
![Outputs](./images/outputs-website-url.png)

### 4️⃣ Site publicado e acessível no navegador  
![Site Online](./images/site-online.png)

🔗 *Acesse aqui:* [http://dio-gabi-site-2025.s3-website-us-east-2.amazonaws.com](http://dio-gabi-site-2025.s3-website-us-east-2.amazonaws.com)

---

## 🧹 Limpeza
Para evitar custos:
1. Esvaziar o bucket S3 (Excluir todos os objetos).
2. Deletar a pilha no CloudFormation.

---

## 📚 Aprendizados
- Uso do *CloudFormation* para automatizar infraestrutura.
- Como funciona a configuração de *site estático no S3*.
- Importância de documentar todo o processo para portfólio profissional.

---

✍️ *Autora:* Gabriela Rodrigues da Silva
