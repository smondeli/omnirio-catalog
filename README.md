# omnirio-catalog
Omnirio Catalog Application

Developer is expected to build/create below mentioned APIS for the catalog
application, below mentioned are the descriptions of what a catalog application is and what
are the apis that need to be built.

## Create APIs:
1. To create a category 
2. To create category attributes 
3. To create a product by linking it to category and its attributes 
4. Get product by id 
5. get category attributes by category id

## Technical expectations from developer:
1. use java as a language
2. use spring boot as application framework
3. user in memory DB/Mysql preferably
4. using spring jpa repositories preferably
5. create REST services
6. all the above mentioned API's are mandatory
7. developers are expected to build the database tables and write services which act upon those tables.
8. develop the project and push it to a GIT repository and share the link to the concerned recruiter.

## Catalog Application:
1. Catalog will have products which belong a certain category
2. Every category will have its own attributes(ex category apparels/shirts will have attributes like color, size, material )
3. every product will be associated with a category,which means the product acquires the category attributes, and the product can give its own values for the attributes.

## Example of a product in a catalog application:
TIP : A product when being created to a apparels/shirts category will get attributes of that
category ,and the user/product owner needs to give some values for those respective
attributes.

NOTE : the below mentioned example is a just representation of a product, Developer
change the schema if she/he deemed necessary

```
[
{
productName : red stripes pontic shirt
ProductID: 1hy26msd8h9
categoryId: 12
categoryName:apparels/shirts
productAttributes/category product attributes
[
{
attributeId: 123
attributeName : color
attributevalue : Red
},
{
attributeId: 456
attributeName : size
attributevalue : Large
},
{
attributeId: 765
attributeName : material
attributevalue : linen
}
]
},
{
productName : tea kettle
ProductID: 1hy78gsd8h9
categoryId: 21
categoryName: kitchen accessories
productAttributes/category product attributes
[
{
attributeId: 123
attributeName : brand
attributevalue : morphy richards
},
{
attributeId: 67
attributeName : weight
attributevalue : 12
},
{
attributeId: 456
attributeName : volume
attributevalue : 30
}
]
}
]
```
