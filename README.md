# O2S Software
### Financial and Stock Management Software

This software was developed for a Portuguese civil construction company. Some of the data in the videos had to be obscured since it represents private and sensitive data. The software was fully developed in Portuguese (company requirement) so to clarify its demonstration' videos the main features (feature's name corresponding to the button's name) will be clarified. 

**Technologies** : *C# , PostgreSQL*

*The source code cannot be disclosed.*


#### Demo Part 1
![alt text](https://github.com/gabrielpatricio/o2software/blob/master/2.gif)

##### Features:
* [*Listagem de Equipamentos(List Products)*] - View with all the products available in the system, organized by categories. The user can find and edit info such as name, quantity in use, quantity available, total price, the price per unit, and the date of acquisition.

* [*Novo Equipamento(New Product)*] - Allows the insertion of a new product, associating it with an existent or new category, the user defines a price per unit, the number of products to insert, its price, and date of acquisition. 

* [*Pesquisar(Search)*] - Filters products by name

* [*Eliminar(Delete)*] - Deletes product from the system.

* [*Info(Details)*] - Gives information about where the product is being used and for how long. 

* [*Exportar Excel(Export Excel)*] - Exports an Excel file with all the info presented in the main table. Calculates also the total value spent in each category of products.

#### Demo Part 2
![alt text](https://github.com/gabrielpatricio/o2software/blob/master/1.gif)

##### Features:
* [*Equipamentos por obra(Products by project)*] - View with all the products being used in each project, whether it is finished or in progress

* [*Obras em Curso/Obras Finalizadas(Projects in progress/Finished projects)*] - Radio button allows to change the view between projects in progress or finished.

* [*Devolver(Return product)*] - Return product no longer in use to be available in stock and consequently calculates its expenses for the days in use

* [*Eliminar(Delete)*] - Removes product from a project.

* [*Por devolver/Devolvidos(To return/Returned)*] - Tab switches view between products in use and no longer in use, respectively in each project.

* [*Adicionar equipamento à Obra(Add product to the project)*] - Allows the insertion of a new product (available in stock) in a project
   
* [*Em Curso(In progress)*] - Defines a finished project as in progress.
 
* [*Finalizada(Finished)*] - Defines as finished an in progress project. Returns all the products in use to the stock, and consequently calculates all the expenses until that day.

* [*Exportar Excel(Export Excel)*] - Exports an Excel file with all the info presented in the main table. Calculates the expenses in the selected project, with the products to be returned and already returned. The user has the flexibility to filter the results in a certain period of time. For example it is possible to calculate the expenses in a certain project for a specific month.
