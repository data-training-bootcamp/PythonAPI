# PythonAPI

Fast API.  :  https://fastapi.tiangolo.com/tutorial/SQLALChemy:  https://docs.sqlalchemy.org/en/20/3PostGreSQL:  https://www.postgresql.org/download/VirtualEnv:  https://docs.python.org/3/library/venv.html.  and read more about virutalenv here:  https://fastapi.tiangolo.com/virtual-environments/visualStudio:  https://code.visualstudio.com/

# API
1. Implement a GET API to get a list of product recommendations
    Return :   {"productRecs":["Product1","Product2"]}

    URL: http://localhost:8000/getProductRecommendations

2. A GET API to get list of recommendations with product details
     Return : { "recommendations" : [
                  { "id": "P1", "Name": <productname>, "description": <description> }
               ]
             }  

3.  A PUT API to insert new products into product table. Include validations to check product id, name, description are not null.



# Database 
Create a database called as Recommendations.  

In the database create two tables
1. A ProductRecs table:

    ProductRecs Table should contain following columns   - ModelName String   - ListofRecs:  [P1,P2,P3]

2. A Product Table:
   Product table should contain ProductId, ProductName, ProductDescription
