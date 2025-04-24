# **ADAC - Associação Dog Anjos Cat**

O projeto **ADAC - Associação Dog Anjos Cat** foi desenvolvido exclusivamente para atender às necessidades da ONG ADAC, que desempenha um papel crucial na proteção e cuidado de animais abandonados. Com o número crescente de animais em situação de vulnerabilidade, a ADAC atua como um agente de transformação social, promovendo a adoção responsável e a conscientização sobre os direitos dos animais.

O principal objetivo do projeto é criar um website sustentável que otimize a gestão e operação da ADAC. A plataforma facilita processos como a adoção de animais, o recrutamento e gerenciamento de voluntários, a realização de eventos e o engajamento da comunidade, fortalecendo a atuação da ONG e ampliando seu impacto na sociedade. 

Acesse o site em: [https://ongadac-client.vercel.app](https://ongadac-client.vercel.app)



## **Equipe de Desenvolvimento**

**Integrantes:**

- [Ana Júlia Teixeira Cândido](https://github.com/anajuliateixeiracandido)  
- [Arthur Freitas Jardim](https://github.com/ArthurFreitasJardim)  
- [Marcella Ferreira Chaves Costa](https://github.com/marcellafccosta)  
- [Sophia Mendes Rabelo](https://github.com/sophiaamr)  
- [Thiago Andrade Ramalho](https://github.com/ThiagoAndradeRamalho)  
- [Wilken Henrique Moreira](https://github.com/Wilkennn)  

**Orientadoras:**

- Joana Gabriela Ribeiro de Souza  
- Soraia Lúcia da Silva  

## **Tecnologias Utilizadas**

### **Frontend:**  
![React](https://img.shields.io/badge/-React-61DAFB?logo=react&logoColor=white&style=flat-square) 
![Ant Design](https://img.shields.io/badge/-AntDesign-0170FE?logo=ant-design&logoColor=white&style=flat-square) 

### **Backend:**  
![Node.js](https://img.shields.io/badge/-Node.js-339933?logo=node.js&logoColor=white&style=flat-square) 
![Express](https://img.shields.io/badge/-Express-000000?logo=express&logoColor=white&style=flat-square) 
![Prisma](https://img.shields.io/badge/-Prisma-2D3748?logo=prisma&logoColor=white&style=flat-square) 

### **Banco de Dados:**  
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?logo=mysql&logoColor=white&style=flat-square) 

### **Segurança e Autenticação:**  
![JWT](https://img.shields.io/badge/-JWT-000000?logo=json-web-tokens&logoColor=white&style=flat-square)  

### **Outras Ferramentas e Bibliotecas:**  
![Multer](https://img.shields.io/badge/-Multer-FF4F2E?logo=moleculer&logoColor=white&style=flat-square) 
![Context API](https://img.shields.io/badge/-ContextAPI-61DAFB?logo=react&logoColor=white&style=flat-square) 
![Material-UI](https://img.shields.io/badge/-Material--UI-007FFF?logo=mui&logoColor=white&style=flat-square) 
![CSS Modules](https://img.shields.io/badge/-CSS%20Modules-264de4?logo=css3&logoColor=white&style=flat-square) 
![Docker](https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=white&style=flat-square) 

### **Controle de Versão:**  
![Git](https://img.shields.io/badge/-Git-F05032?logo=git&logoColor=white&style=flat-square) 
![GitHub](https://img.shields.io/badge/-GitHub-181717?logo=github&logoColor=white&style=flat-square)  

### **Testes:**  
![Jest](https://img.shields.io/badge/-Jest-C21325?logo=jest&logoColor=white&style=flat-square)  

---

## **Como Executar o Projeto**

1. **Pré-requisitos:**  
   - Node.js instalado ([Baixe aqui](https://nodejs.org/))  
   - Gerenciador de pacotes (npm ou yarn)  
   - Banco de dados MySQL configurado  

2. **Clone o repositório:**  
   ```bash
   git clone https://github.com/seu-usuario/adac.git
   cd adac

3. **Criação do banco de dados:**
    - Certifique-se de que o MySQL está instalado e rodando em seu ambiente.
    - Crie um banco de dados chamado ongadac.
Anote o nome de usuário e a senha do seu MySQL para configurá-los no arquivo .env.

4. **Configuração do arquivo .env:**
    - Crie ou edite o arquivo .env manualmente na pasta server.
    - Preencha o arquivo com as seguintes variáveis, ajustando conforme necessário:
 ```plaintext  
   DATABASE_USER="SEU-USUÁRIO"
   DATABASE_PASSWORD="SUA-SENHA"
   MYSQL_DATABASE="ongadac"
   DATABASE_URL="mysql://SEU-USUÁRIO:SUA-SENHA-22@localhost:3306/ongadac"
```

## **Configuração do Backend**

1. Execute os seguintes comandos:  
   ```bash
   cd server
   npm install ## yarn install
   npx prisma migrate dev
   npm run dev ## yarn start                    


## **Como Configurar o Frontend**

1. **Acesse a pasta do frontend:**  
   Navegue até a pasta onde o frontend do projeto está localizado:
   ```bash
   cd client
   npm install ## yarn install
   npm run dev ## yarn start
   http://localhost:3000
