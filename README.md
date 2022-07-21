<img alt="Java" src="https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white"/><img alt="Spring" src="https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white"/>
# Alfalogistics
### API de controle de entregas.

![image](https://user-images.githubusercontent.com/15113099/119415740-9d17dd00-bcc8-11eb-808e-35e88bd7e0f4.png)

![image](https://user-images.githubusercontent.com/15113099/119415830-ca648b00-bcc8-11eb-9c98-4c45df19db2a.png)

![image](https://user-images.githubusercontent.com/15113099/119415899-e405d280-bcc8-11eb-83e9-d3f86125e53e.png)




## Executando esse projeto:
Na Pasta Raiz do projeto execute:
```bash
./mvnw spring-boot:run
```
Consuma a API nos EndPoints abaixo com com um cliente REST, como o postman

### Clientes
**GET** Get Clientes
http://localhost:8080/clientes

**GET** Get Client By ID
http://localhost:8080/clientes/1

**POST** Criar Cliente
http://localhost:8080/clientes

- **Body**
```json
{
"nome": "Jose@Email",
"telefone": "(84)92928272",
"email": "Jose@Silva"
}
````

### Banco de Dados
- O Banco de Dados desse projeto é H2. Caso deseje alterar o banco altere as informações presentes no arquivo: /src/main/resources/application.properties

![image](https://user-images.githubusercontent.com/15113099/119414347-cbe08400-bcc5-11eb-9eac-22717b183d87.png)


----
### Organização dos Pacotes
![img_1.png](img_1.png)

#### Diagrama de Relacionamentos do Banco de Dados
![img.png](img.png)


### Tecnologias Utilizadas
* Springboot
* Loobok
* Maven
* Jakarta Bean Validation
* Flyway
* ModelMapper
