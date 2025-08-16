# Olá, eu sou a Leticya Danielly 👋

Sou entusiasta de Machine Learning, Visão Computacional e desenvolvimento de projetos com Python e outras tecnologias.

---

## 💼 Sobre mim

- Apaixonada por Inteligência Artificial e Ciência de Dados.
- Experiência prática com redução de dimensionalidade, redes neurais e algoritmos de treinamento.
- Sempre buscando aprender e aplicar novos conhecimentos em projetos reais.

---

## 🛠 Tecnologias e Ferramentas

- Python | TensorFlow | PyTorch
- OpenCV | Scikit-learn
- Google Colab | Jupyter Notebook
- Git | GitHub

---

## 🚀 Projetos em destaque

- [Projeto Redução de Dimensionalidade com redes neurais](https://github.com/leticyadanielly/projeto1) - Implementação de técnicas para otimizar imagens para redes neurais.
- [PRedução de Dimensionalidade em Imagens para Redes Neurais e Algoritmos de Treinamento](https://github.com/leticyadanielly/projeto1)) - Aplicação prática em redução de dimensionalidade de imagens.
# Projeto 1: Cenário de Simulação de Vulnerabilidade

---

### Descrição do Projeto

Este projeto foi desenvolvido como parte do desafio "Criação de cenários controlados para simulação e estudo de vulnerabilidades em aplicações". O objetivo principal é criar um ambiente prático e seguro para analisar a vulnerabilidade de **[SQL INJECTION]** em uma aplicação web.

O foco deste trabalho é a aplicação prática dos conceitos teóricos de segurança, a documentação clara dos processos e o uso do GitHub como ferramenta de compartilhamento técnico.

---

### Objetivos de Aprendizagem

* **Aplicação Prática:** Configurar e testar uma vulnerabilidade em um ambiente real.
* **Documentação Técnica:** Descrever de forma clara e estruturada todo o processo de estudo e exploração da vulnerabilidade.
* **Colaboração com GitHub:** Utilizar um repositório público para organizar e compartilhar o conhecimento técnico adquirido.

---

### Cenário e Tecnologias Utilizadas

Para este desafio, configurei um ambiente de testes para simular a vulnerabilidade de **[DVWA (Damn Vulnerable Web Application)]**. O cenário consiste em:

* **Aplicação Vulnerável:** Utilizei a **[DVWA (Damn Vulnerable Web Application)]**, uma aplicação propositalmente insegura, ideal para fins de aprendizado.
* **Ferramentas de Análise:** Usei ferramentas como **[Burp Suite]** para interceptar e modificar requisições HTTP e **[OWASP ZAP]** para escaneamento de vulnerabilidades.
* **Ambiente:** O ambiente de simulação foi montado usando **[Docker]**, o que permitiu isolar a aplicação e o banco de dados em contêineres separados.

---

### Passo a Passo do Estudo

1.  **Configuração do Ambiente:**
    * Clonei o repositório da aplicação vulnerável.
    * Subi os contêineres usando `docker-compose up -d`.
    * Acesse a aplicação no navegador em `http://localhost:[PORTA]`.

2.  **Análise da Vulnerabilidade:**
    * Explorei a aplicação para entender seu fluxo de dados.
    * Utilizei a ferramenta **[Burp Suite]** para interceptar as requisições e analisar como os dados são enviados ao servidor.
    * Identifiquei um campo de login que não realizava a sanitização de entradas.

3.  **Exploração:**
    * Usei payloads específicos, como **[' OR 1=1 --]** no campo de usuário, para injetar código SQL e contornar a autenticação, conseguindo acesso à aplicação sem credenciais válidas.
    * Demonstrei o impacto da vulnerabilidade, acessando dados sigilosos do banco de dados.

4.  **Mitigação (Opcional):**
    * Descreva como a vulnerabilidade poderia ser corrigida. Por exemplo: "A solução para essa falha seria a validação de todas as entradas do usuário e a utilização de **prepared statements** para prevenir injeções SQL."

---

### Conclusão e Aprendizado

Este projeto foi fundamental para entender, na prática, como as falhas de segurança podem ser exploradas e os riscos que elas representam. A experiência de criar o cenário, analisar o comportamento da aplicação e documentar todo o processo fortaleceu minha compreensão sobre a importância de práticas de desenvolvimento seguras.

---

### Imagens Relevantes

![Login Vulnerável](images/login_vulneravel.png)
_Captura de tela mostrando o campo de login antes da exploração._


---

## 📫 Contato

- LinkedIn: [linkedin.com/in/leticya](https://www.linkedin.com/in/leticya)
- Email: leticyadanielly@gmail.com

---

Se quiser conhecer mais, fique à vontade para explorar meus repositórios! 😊
