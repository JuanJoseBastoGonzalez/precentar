pagia tienda en linea.

para la ubicación de los containers se usa el display: grid 

los json se utilizan para el cambio de imágenes y para efectos de las aminación del dashboard.

se utlizan las rutas absolutas para un mejor manejo se las rutas.

```
	<script >
		var agrandar = document.getElementById("photo");
		var smallimg = document.getElementsByClassName("foto");

		smallimg[0].onclick = function() {
		agrandar.src = smallimg[0].src;
		}
		smallimg[1].onclick = function() {
		agrandar.src = smallimg[1].src;
		}
		smallimg[2].onclick = function() {
		agrandar.src = smallimg[2].src;
		}
		smallimg[3].onclick = function() {
		agrandar.src = smallimg[3].src;

		}
	</script>
```

se reutiliza este scrip para realizar el cambio de las imagenes cuando se precentan los productos por individual 