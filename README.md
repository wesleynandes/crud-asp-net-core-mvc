
# Pagina de Vendas

### Projeto que apresenta operações administrativas de um site de vendas
Criado para registrar o meu conhecimento em construção de CRUD e como forma de me aperfeioçar nas ferramentas que a linguagem tem a oferecer.   

## Tecnologias usadas no projeto

* C# .Net Core 2.1
* Entity FrameWork Core 2.1.14
* Template Razor Engine
* MySQL

## Como rodar o Projeto?

```
$ git clone https://github.com/wesleyfernands/crud-asp-net-core-mvc.git
```
* Atualize a string de conexao do banco de dados 
* Instale os seguintes pacotes de dependencias pelo NuGet Package
```
Install-Package Pomelo.EntityFrameworkCore.MySql -Version 2.1.1
```
```
Install-Package Microsoft.EntityFrameworkCore
```
```
Install-Package Microsoft.EntityFrameworkCore.Design -Version 2.1.14
```
## Estrutura do Projeto
### Foi utilizado como base de orientação este Diagrama UML, Mostrando toda a relação de cada classe/objeto

![Diagram image](https://github.com/wesleyfernands/crud-asp-net-core-mvc/blob/main/SalesWeb/wwwroot/images/UML-SalesWeb.PNG)

## Demonstração

### Tabela de Vendedores(Sellers)
![Sellers Table image](https://github.com/wesleyfernands/crud-asp-net-core-mvc/blob/main/SalesWeb/wwwroot/images/sellers-table.PNG)
### Tabela de Departamentos(Departaments)
![Departments Table image](https://github.com/wesleyfernands/crud-asp-net-core-mvc/blob/main/SalesWeb/wwwroot/images/departments-table.PNG)
### Registro de Vendas(Sales Records) por Data. Retorna Tabelas com registros do banco de dados.
![Sales Records Search image](https://github.com/wesleyfernands/crud-asp-net-core-mvc/blob/main/SalesWeb/wwwroot/images/salesrecords-search-date.PNG)
### 
