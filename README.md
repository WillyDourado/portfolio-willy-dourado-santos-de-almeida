# Willy Dourado Santos de Almeida
> Estudante de Analise e Desenvolvimento de sistemas da universidade de São Paulo
 
---
 
### 📫 Contato & Redes Sociais
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/willy-dourado-20b5a4248/?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BlYPuwyknS9qybaOD8w1FfQ%3D%3D)
[![E-mail](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](santoswilly181@gmail.com)
[![Currículo](https://img.shields.io/badge/Currículo-000000?style=for-the-badge&logo=read-the-docs&logoColor=white)](./cv/curriculo.pdf)
 
---
 
### 👨‍💻 Sobre
Atualmente em formação na área de tecnologia, com foco em
desenvolvimento de software e construção de soluções voltadas à
resolução de problemas.Tenho desenvolvido conhecimentos em
tecnologias como JavaScript, Python e SQL, além do uso de Git
para versionamento de código. Como parte do meu processo de
aprendizado, venho construindo projetos práticos com o objetivo
de consolidar conceitos e evoluir tecnicamente.Sigo aprofundando
meus estudos em lógica de programação, estrutura de dados e
boas práticas de desenvolvimento, buscando escrever código
eficiente, organizado e escalável.Busco uma oportunidade como
Desenvolvedor Júnior, onde eu possa aplicar meus conhecimentos,
aprender com profissionais mais experientes e evoluir de forma
consistente na área de tecnologia.Stack: JavaScript | Python | SQL |
GitInteresses: Desenvolvimento Back-end | APIs | Análise de Dados.
 
* **Habilidades Técnicas:** Python.
* **Habilidades Socioemocionais:** Trabalho em equipe, comunicação assertiva e pensamento crítico.
* **Experiência/Projetos Relevantes:** Brasil TecPar
Infraestrutura de redes
novembro de 2023 - Present 
 
---
 
### 🛠 Minhas Ferramentas Favoritas
 
#### 💻 Linguagens e Tecnologias
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

 
#### 🗄️ Banco de Dados
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
 
#### 🤖 Inteligência Artificial & Ciência de Dados
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
 
---
 
### 📂 Portfólio de Projetos
 
#### 🗃️ Programção de computadores 
| Projeto | Descrição | Link |
| :--- | :--- | :---: |
| **Engenharia de soluções lógicas** | Desenvolver uma solução algorítimica para um problema complexo do mundo real. | [Ver Projeto](ESL/Conheça_o_Colab.ipynb) 
| **O Algoritmo de Auditoria de Dados** |  Desenvolver um programa que analise a consistência de dados financeiros, utilizando escopo global/local para parâmetros de segurança e lógica condicional para detecção de anomalias. | [Ver Projeto](AAD/Algoritmo-de-auditoria-de-dados.ipynb)
 

 
---
 
### 🏗 Estrutura do Repositório
Abaixo, a organização deste repositório para facilitar a navegação:
 
- `root/`: Arquivo de apresentação principal.
- `/projeto-nome/`: Pasta contendo o código-fonte, documentação e o README específico do projeto acadêmico.


# 🌡️ Analisador de Microclima Local e Qualidade do Ar (IAQ)

## 📝 Descrição do Projeto
Este projeto consiste em um sistema de monitoramento ambiental desenvolvido em **Python** para analisar e classificar dados de microclima. O software processa variáveis como temperatura, umidade e o índice **IAQ (Indoor Air Quality)** de diferentes localidades para gerar diagnósticos de saúde ambiental e uma nota de conforto personalizada.

Desenvolvido como parte de estudos em **Lógica de Programação e Prototipagem**, o sistema demonstra o uso prático de estruturas de controle modernas (como o `match-case`) e a criação de algoritmos matemáticos para a normalização de métricas de bem-estar humano.

## 🚀 Tecnologias Utilizadas
* **Linguagem:** Python 3.10+
* **Conceitos:** Programação Funcional, Estruturas de Decisão Avançadas, Processamento de Listas.
* **Ferramentas:** IDE PyCharm / VS Code.

## 📊 Lógica de Funcionamento e Resultados
O sistema utiliza uma abordagem quantitativa para avaliar o ambiente:

* **Classificação de Saúde:** O índice IAQ é categorizado automaticamente em níveis que variam de "Boa" até "Extremamente Insalubre", auxiliando na identificação de riscos para grupos sensíveis.
* **Algoritmo de Conforto:** Implementação de uma fórmula de penalidade que subtrai pontos de uma nota máxima (10.0) com base no desvio das condições ideais (20°C e 40% de umidade).
* **Análise Multilocal:** O código é capaz de iterar sobre grandes listas de dados, permitindo a comparação rápida entre diferentes regiões (como Itaquaquecetuba, Guarulhos e Carrão).

## 🔧 Como Executar
1. Certifique-se de ter o **Python 3.10** ou superior instalado.
2. Clone o repositório ou baixe o arquivo `emp5.py`.
3. Abra o terminal na pasta do arquivo.
4. Execute o comando:
   ```bash
   python emp5.py
