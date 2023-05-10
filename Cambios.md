
1. Se agregó la aplicación "pedidosApp" a la lista de aplicaciones en el archivo settings.py mediante la variable LOCAL_APPS.

2. Se instaló y agregó la aplicación "django-cors-headers" en el archivo settings.py para configurar la política de CORS (Cross-Origin Resource Sharing).
 
3. Se añadió el modelo Pedido al administrador de Django con el fin de poder gestionar los pedidos desde la interfaz de administración.

4. se congifuro alerta de error SystemCheckError de las aplicaciones pedidosApp y vehiculosApp

5. Se configuró una alerta para el campo id del modelo Pedido, estableciendo un límite en el número máximo de caracteres permitidos.

6. En el archivo urls.py de la aplicación "pedidosApp", se organizaron las rutas para manejar las solicitudes relacionadas con los pedidos.

7. En el archivo api.py de la aplicación "pedidosApp", se creó la vista "pedido_detail_view" para manejar las solicitudes relacionadas con un pedido específico.

8. Se reorganizó el serializador del modelo Pedido en su respectivo archivo "serializers.py", eliminando las importaciones innecesarias del modelo Conductor.


