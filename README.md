# Guide to add details.
# clone repository
```
git clone https://github.com/voteit-top/voteitimgs.git
```
## copy your images to ./imgs
A good image file name should like:itemname_imageauthor.jpg
for example: usa_mikejones.jpg, usa_wangxiaoming.jpg
copy your file to voteitimgs/imgs/
## edit voteitdetails.js
usually, you should not remove other contents, append your content instead.
key is item Id, it's value is a object with two keys:
desc: description of your item.
imgs: image files of your item. multiple image should split with '|', for example: usa_mikejones.jpg|usa_wangxiaoming.jpg

## push your request
```
git commit -m 'update item details of '
git push origin master
```
