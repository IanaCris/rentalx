# Cadastro de Carro

**RF** 
Deve ser possivel cadastrar um novo carro.

**RN** 
Não deve ser possivel cadastrar um carro com uma placa já existente
/*Não deve ser possível alterar a placa de um carro já cadastrado*/
O carro deve ser cadastrado, por padrão com disponibilidade
O usuário reposnsável pelo cadastro de ser um usuário administrador


# Listagem de Carros

**RF**  
Deve ser possível listar todos os carros disponíveis
Deve ser possível listar todos os carros disponíveis pelo nome da categoria
Deve ser possível listar todos os carros disponíveis pelo nome da marca
Deve ser possível listar todos os carros disponíveis pelo nome do carro

**RN**
O usuário não precisa estar logado no sistema

# Cadastro de Especificação do Carro

**RF**
Deve ser possível cadastrar um especificação para um carro

**RN**
Não deve ser possível cadastrar uma especificação para um carro não cadastrado
Não deve ser possível cadastrar uma especificação já existente para o mesmo carro
O usuário responsável pélo cadastro deve ser um usuário administrador


# Cadastro de imagens do carro

**RF**
Deve ser possível cadastrar a imagem do carro

**RNF**
Utilizar o multer para upload dos arquivos

**RN**
O usuário deve poder cadastrar mais de uma imagem para o mesmo carro
O usuário responsável pelo cadastro deve ser um usuário administrador


# Cadastro de Aluguel de carro

**RF**
Deve ser possível cadastrar um aluguel

**RN**
O aluguel deve ter duração mínima de 24 horas
Não deve ser possível cadastrar um novo aluguel caso já exista um aberto para o mesmo usuário
Não deve ser possível cadastrar um novo aluguel caso já exista um aberto para o mesmo carro

