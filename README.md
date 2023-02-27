# 1 - Install postman

```sudo dnf install snapd
sudo ln -s /var/lib/snapd/snap /snap
sudo snap install postman
```

# 2 - Open Postman

<img src="https://github.com/Anat94/workshop-postman/blob/main/Postman.png" width="300"/>

# 3 - Exercise
## 3.1 - Basic Request
Make a GET request on this link and get product which has id 2:
``https://dummyjson.com/products``

Expected :

```
{
    "id":2,
    "title":"iPhone X","description":"SIM-Free,
    Model A19211 6.5-inch Super Retina HD display with OLED technology A12 Bionic chip with ...","price":899,
    "discountPercentage":17.94,
    "rating":4.44,
    "stock":34,
    "brand":"Apple",
    "category":"smartphones",
    "thumbnail":"https://i.dummyjson.com/data/products/2/thumbnail.jpg",
    "images":[
        "https://i.dummyjson.com/data/products/2/1.jpg",
        "https://i.dummyjson.com/data/products/2/2.jpg",
        "https://i.dummyjson.com/data/products/2/3.jpg",
        "https://i.dummyjson.com/data/products/2/thumbnail.jpg"
    ]
}
```