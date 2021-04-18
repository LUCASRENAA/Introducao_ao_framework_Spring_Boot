# Code Anywhere

Desenvolva projetos com Spring Boot, Spring Cloud e Azure em conjunto com os melhores experts da Avanade para ampliar o seu conhecimento, criar um portfólio inovador e conquistar grandes oportunidades.

## Introducao_ao_framework_Spring_Boot
### Primeira aula
Primeira aula do curso, falando sobre as vantagens(aumento de produtividade, foco na aplicação e não na configuração e etc) do Spring Boot de automatizar o processo de configuração e subindo o primeiro servidor em spring. 
#### Algumas informações 

https://start.spring.io/ - O site para a criação do projeto

###### Comando para subir o server (Se você estiver no Linux)
```
./mvnw spring-boot:run
```

###### E esse é o resultado da primeira aula
![ ](https://github.com/LUCASRENAA/Introducao_ao_framework_Spring_Boot/blob/main/imagens/aula1.png)

## Continue programando
![ ](https://stories.freepiklabs.com/storage/22811/programming-bro-2608.png)

### Segunda aula

####Auto configurations

##### Spring Boot detecta as dependências e configura para o programador




# Observe as mudanças
## Pule de diretório e vá para application.properties

> src  
>> main 
>>> resources
>>>> application.properties

#### Dentro desse arquivo coloque 

##### debug=true 

E com o debug, já dá para analisar melhor os logs com a execução do programa
se você não lembra como subir é só olhar o comando aqui denovo

```
./mvnw spring-boot:run
```

### Terceira aula

#FatJar / UberJar

Container web embutido na geração e execução (Tomcat)


Comandos da aula
```
./mvnw clean package  
cd target
java -jar springboot-0.0.1-SNAPSHOT.jar 
```
e depois é só acessar 
###### 127.0.0.1:8080

