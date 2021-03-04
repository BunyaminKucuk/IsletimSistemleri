# IsletimSistemleri
 
1) Projenin Amacı:
myData (parent) ve myMore (child) prosesleri arasındaki haberleşmeyi sağlamak. Bu haberleşmede; myData write, myMore read işlemini gerçekleştirecektir.
2) Projenin Kapsamı:
Prosesler arasındaki bu haberleşmeyi sağlamak için ordinary pipe kullanılacaktır. Çünkü haberleşme tek yönlü olarak (myData read ve myMore write işlemlerini yapacak şekilde) gerçekleşecektir. myData prosesi kendi başına da çalışabilecektir ancak myMore prosesi kendi başına çalışamayacak myData ile birlikte çalışacaktır.
