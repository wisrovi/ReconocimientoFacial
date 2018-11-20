# ReconocimientoFacial
Servidor de reconocimiento facial


Estas carpetas son un compilado en el que se crea un servidor POST

Con este servidor POST, se le pueden hacer solicitudes para almacenar nuevas personas a partir de una imagen, el servidor incluira en una DataBase los 68 puntos caracteristicos  del rostro obtenidos por face_recognition.

seguidamente otra solicitud POST permite que reciba una foto y  el servidor mediante la comparación de puntos determine el usuario con el que se creo la foto

Es decir, en pocas palabra:
primero se envia una foto con un nombre a guardar y el servidor alamcenara la foto
segundo se envia una foto y si el servidor reconoce a la persona en la foto, identificara a la persona,
tercero,  este codigo hace un servidor para reconocimiento facial.

Gracias
