API DOCUMENTATION

URL es https://bsale-server.herokuapp.com/


GET Products

"products" trae todos los productos de la base de datos con los siguientes parametros:

  "id": number,
    "name": "string",
    "url_image": "https://dojiw2m9tvv09.cloudfront.net/11132/product/logo7698.png",
    "price": number,
    "discount": number,
    "category": number
  },
  
 "products/{name}" trae uno o mas productos que su nombre coincida, ejemplo: 
 
 products/coca 
 
 [
  {
    "id": 37,
    "name": "COCA COLA ZERO DESECHABLE",
    "url_image": "https://dojiw2m9tvv09.cloudfront.net/11132/product/cocazero9766.jpg",
    "price": 1490,
    "discount": 0,
    "category": 4
  },
  {
    "id": 57,
    "name": "COCA COLA NORMAL DESECHABLE 1500cc",
    "url_image": null,
    "price": 1500,
    "discount": 0,
    "category": 4
  },
  {
    "id": 58,
    "name": "COCA COLA LIGHT DESECHABLE",
    "url_image": null,
    "price": 1500,
    "discount": 0,
    "category": 4
  }
]


GET Category

"category" trae todas las categorias de productos:

  {
    "id": number,
    "name": string
  },
  
  "category/:category trae todos los productos que coincidan en la misma categoria
  


