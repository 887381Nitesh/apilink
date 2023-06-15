// flipkart application
//page1
>list of category type
*https://apiflip.onrender.com/categoryoption
>list of products category wise
*https://apiflip.onrender.com/itemlisting1?categoryId=2
>list of product type
*https://apiflip.onrender.com/producttype1


//page2
>Rest wrt res to product filter type
*https://apiflip.onrender.com/itemlisting1?productId=5
*https://apiflip.onrender.com/itemlisting1?categoryId=1&productId=2
>Rest wrt to productType + cuisine
*https://apiflip.onrender.com/filter/1?cuisineId=1
>Rest wrt to productType + cost
*https://apiflip.onrender.com/filter/1?Lcost=300&hcost=2000

//page3
>Details of product
*https://apiflip.onrender.com/details/3
>item of product
*https://apiflip.onrender.com/item/2

//page4
>Details of item selected
*https://apiflip.onrender.com/productDetails
 {"id":[1,2,3,4]}
>place order
* https://apiflip.onrender.com/placeOrder
[
  {
    "_id": "648aa4afd7c4922e758e70e7",
    "Orderid": "3",
    "name": "pooja",
    "email": "pooja@gmail.com",
    "address": "road no 6,darbhanga",
    "phone": 768768686,
    "cost": 1100,
    "productItem": [
      10,
      12,
      15
    ]
  },
  {
    "_id": "648aa545d7c4922e758e70e8",
    "Orderid": "4",
    "name": "Nitesh",
    "email": "nitesh@gmail.com",
    "address": "Hno 23,laxmisagar",
    "phone": 97876733,
    "cost": 2000,
    "productItem": [
      20,
      21,
      22
    ]
  }
]

//page5
>List of all the orders
*https://apiflip.onrender.com/orders
>Update orders details
*https://apiflip.onrender.com/updateOrder
"_id":"648aa4afd7c4922e758e70e7",
    "status":"delivered"
>Delete orders
*https://apiflip.onrender.com/deleteOrder
 { "_id": "648aa545d7c4922e758e70e8"}