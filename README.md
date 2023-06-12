# Aprendiendo Bootstrap

## Grid en Bootstrap

---

- aplicamos la clase border, para el ejemplo
- agregamos una columna mas (una div extra), entonces el concepto de que la grid de bootsrtrap esta maquetada en flexbox se reparte proporcionalmente
- la clase row esta maquetada en su hoja de estilo con un display flex flexwrap
- a la clase col si se le agrega un -numero, asi por ejemplo col-6, en su grid de 12, ocuparia 6 de 12 espacios y el resto de las 3 col que sobran se reparten el espacio proporcionalmente

---

## Grid Responsiva

- agregamos la clase col-12 para que todos los elementos se distribuyan en una grid de 12, ademas creamos las media queries, con las clases col-sm-6(small ≥576px: en la grid de 12 ocupara 2 columnas), col-md-4 (medium ≥768px: en la grid de 12 ocupara 3 columnas) y asi sucesivamente con lg, xl y xxl

### Con containers

- los containers nos dan espaciados a los lados izq y der
- la clase container-fluid fluye como la que no tiene contenedor
