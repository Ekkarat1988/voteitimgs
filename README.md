# Guide to add details.
# fork repository
1. fork this repository
2. Clone your repository
```
$ git clone https://github.com/<username>/voteitimgs.git
$ cd voteitimgs
```
## copy your images to ./imgs
A good image file name should like:itemname_imageauthor.jpg
for example: usa_mikejones.jpg, usa_wangxiaoming.jpg
copy your file to voteitimgs/imgs/
## edit voteitdetails.js
1. usually, you should not remove other contents, append your content instead.
2. key is item Id, it's value is a object with two keys:
  **desc**: description of your item.
  **imgs**: image files of your item. multiple image should split with '|', for example: usa_mikejones.jpg|usa_wangxiaoming.jpg

```
var rankItemDetails = {
  0: {desc:"this is a short description",imgs:"image1.jpg|image2.jpg"},
  1: {desc:"description of USA",imgs:"usa1_joe_woods.jpg|usa_alan_walker.jpg|usa_john_white.jpg"},
};
```

## push your change
```
git add imgs/*
git commit -m 'update item details of '
git push origin master
```

## create PR.
