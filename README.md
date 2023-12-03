### API para gerenciamento de Entregadores

## Instruções para colocar em operação

# Requisitos
- Java 17
- MySql
  - Database: dianome
  - Username: root
  - Password: admin

# Instalação
- Clone este projeto
- Importe para o Eclipse
- Atualize as bibliotecas com o Maven
- Inicialize

# Acesso
- Abra o um gerenciador de API, como o Postman

# Utilização

Para incluir um entregador
	
	- URI: http://localhost:8080/incluirEntregador
	
	- Método: POST
	
	- Formulário JSON: id, cpf, nome, capacidade
	
Para listar todos os entregadores
	
	- URI: http://localhost:8080/listarEntregadores
	
	- Método: GET
	
Para mostrar apenas um entregador
	
	- URI: http://localhost:8080/detalharEntregador/{id}
	
	- Método: GET
	
Para excluir um entregador
	
	- URI: http://localhost:8080/excluirEntregador/{id}
	
	- Método: DELETE

Para alterar um entregador
	
	- URI: http://localhost:8080/alterarEntregador/{id}
	
	- Método: PUT
	
	- Formulário JSON: id, cpf, nome, capacidade
