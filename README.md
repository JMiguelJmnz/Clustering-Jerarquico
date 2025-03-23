# Clustering Jerarquico

Se utilizara clustering jerarquico para hacer recomendaciones de compras a clientes en relacion a personas que pertenezcan al mismo cluster o segmento

Comenzamos el análisis cargando la base de datos Amazon.xlsx
<br>![image](https://github.com/user-attachments/assets/9e8c0ac5-bf3b-4545-89ad-35aea6793357)


Para facilidad de manipulación de datos se toman solo los datos cuantitativos de los clientes
<br>![image](https://github.com/user-attachments/assets/ccb7551d-3677-40f8-9369-3fcd0f5c8aa5)

Realizamos el preprocesamiento, escalando los datos y re convirtiendo a data frame
<br>![image](https://github.com/user-attachments/assets/ae352ace-516a-4175-bada-613946e30021)
<br>![image](https://github.com/user-attachments/assets/3c5193e6-d346-4fb6-904b-a7395f7da844)

Realizamos el dendograma para tener la primera visualización de los clusters
<br>![image](https://github.com/user-attachments/assets/e33d811d-6dee-4fe9-b0a4-f0b1f4ec0966)
<br>![image](https://github.com/user-attachments/assets/a68f8037-723b-4507-b638-2f2763832449)

Realizamos el agrupamiento
<br>![image](https://github.com/user-attachments/assets/85ca5d04-2466-4848-a1e8-906ffb2d3978)

Despues de convertirlo a dataframe, hacemos la concatenación
<br>![image](https://github.com/user-attachments/assets/78d71c42-37e4-42d0-b4b3-d9c74e5b2d78)
<br>![image](https://github.com/user-attachments/assets/7e32935a-a10c-4340-aa76-308dca5d4a74)

En este punto ya podemos observar en qué grupo entra cada cliente individual y podemos utilizar esta información para tomar decisiones. En base al grupo al que fue asignado Salomé (2) podemos recomendar los mismos productos que Isabelle, Eugenia, Joachim, etc..
<br>![image](https://github.com/user-attachments/assets/b384857d-b009-4d59-bf70-2506c7f6740a)

Para Stephania y Lydia que entran en el mismo grupo (1) podemos recomendar los mismos artículos que Adam, Anna, Eva, Felix, Hannah, etc…
<br>![image](https://github.com/user-attachments/assets/475639a7-81ae-416e-b35f-442c99311cb3)
<br>![image](https://github.com/user-attachments/assets/76aeb530-f93b-4812-a7c2-21c18d2745d0)
