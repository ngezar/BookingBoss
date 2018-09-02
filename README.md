# BookingBoss
DOT NET TEST
For two methods 
GetProducts
PutProducts

JSON Client
GetProducts 
http://localhost:49396/Products.svc/GetProducts/id=1/timestamp=090000/productsIds=1,2,3

This XML file does not appear to have any style information associated with it. The document tree is shown below.
<ArrayOfProduct xmlns="http://schemas.datacontract.org/2004/07/BookingBoss.REST" xmlns:i="http://www.w3.org/2001/XMLSchema-instance">
<Product>
<Id>1</Id>
<Name>Name 1</Name>
<Quantity>3</Quantity>
<Sales_amount>5</Sales_amount>
</Product>
<Product>
<Id>2</Id>
<Name>Name 2</Name>
<Quantity>6</Quantity>
<Sales_amount>10</Sales_amount>
</Product>
<Product>
<Id>3</Id>
<Name>Name 3</Name>
<Quantity>9</Quantity>
<Sales_amount>15</Sales_amount>
</Product>
</ArrayOfProduct>

PutProduct REQUEST JSON 
{"product":
{ "Id":12,
"Name":"Name 12",
"Quantity":12,
"Sales_amount":36
}
}

PutProducts REQUEST JSON
{"id":1,
"timestamp": 1,
"products":
[
{ "Id":12,"Name":"Name 12",
"Quantity":12,"Sales_amount":36},
{ "Id":13,"Name":"Name 13",
"Quantity":13,"Sales_amount":36}
]
}
