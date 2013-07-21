# PostgreSQL Dev Boxes

Make postgresql easier by using this vagrant box which is a
pre-packaged postgresql server with a JSON table ready to go.

## Making the box

You DO NOT HAVE TO DO THIS - this is for administrators only, so they
can make new versions of the pgdevbox.

Box making stuff is in the ````make```` subdirectory.

````
cd make
vagrant up
... box is provisioned...
vagrant package
rsync package.box boxhost
````
