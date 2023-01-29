# TELA DE CADASTRO WEBINAR MENTORAMA

*# language: pt-br*

*# Cenários de **Sucesso***

## Funcionalidade: Cadastro

​      **Eu** como usuário 

​      **Quero** criar um cadastro

​      **Para** conecta-me ao webinar

 

### **Cenário:** Cadastro “Nome”

**Dado** que sou um usuário 

**Quando** eu clicar no campo “Nome”

**Então** irei preencher este mesmo campo com caracteres 

**E** só serei aceito se estes caracteres forem em formato de letras. 

 

### **Cenário:** Cadastro “E-mail"

**Dado** que sou um usuário 

**Quando** eu clicar no campo “E-mail”

**Então** irei preencher este mesmo campo com caracteres 

**E** só serei aceito se houver o caractere especial “@”

**E** se o e-mail for válido. 

 

### **Cenário:** Cadastro “Telefone”

**Dado** que sou um usuário 

**Quando** eu clicar no campo “Telefone”

**Então** irei preencher este mesmo campo com caracteres 

**E** só serei aceito com caracteres em formato numérico. 

 

### **Cenário:** Cadastro “Senha”

**Dado** que sou um usuário 

**Quando** eu clicar no campo “Senha”

**Então** irei preencher este mesmo campo com caracteres alfanuméricos e especiais

**E** só serei aceito se este campo tiver no mínimo oito caracteres. 

 

### **Cenário:** Cadastro “Conecte-se”

**Dado** que sou um usuário 

**Quando** eu clicar no botão “conecte-se”

**Então** irei receber a mensagem de cadastro com sucesso 

**E** receberei a mensagem de obrigado

**Se** eu tiver preenchido todos os campos anteriores corretamente. 