Inicio
mostrar ("cuantos lapices vas a comprar")
leer cantidad_de_lapices 

si cantidad_de_lapices >= 1000
    precio = 85
si no
    precio = 90
fin si 
precio_total = cantidad_de_lapices * precio
mostrar precio_total 