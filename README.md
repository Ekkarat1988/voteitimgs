# Guide to add details.
# fork repository
1. fork this repository
2. Clone the repository
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
  1. desc: description of your item.
  2. imgs: image files of your item. multiple image should split with '|', for example: usa_mikejones.jpg|usa_wangxiaoming.jpg

## push your change
```
git commit -m 'update item details of '
git push origin master
```

## create PR.
