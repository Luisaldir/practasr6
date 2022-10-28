**Creación cluster**

![image](https://user-images.githubusercontent.com/72698383/198615622-4e3eb962-08a0-4921-842b-bbb78b241fd2.png)

Configuramos los parámetros necesarios del proyecto:

![image](https://user-images.githubusercontent.com/72698383/198615769-a4babf69-6e87-49cf-954f-3070c4a23624.png)

Creamos el cluster:

![image](https://user-images.githubusercontent.com/72698383/198615893-07411015-284a-47bd-b2f5-feea54f0e760.png)

![image](https://user-images.githubusercontent.com/72698383/198615971-71bd73f8-03eb-44c9-8968-eeb356a67870.png)

Comprobamos los despliegues en funcionamiento para el HPA:

![image](https://user-images.githubusercontent.com/72698383/198616064-53ac63d5-7cc4-49d3-a8b8-8b9aa3968b7f.png)

Aplicamos el HPA y comprobamos su funcionamiento:

![image](https://user-images.githubusercontent.com/72698383/198616160-94de84a5-4e9f-4b0f-a3c1-640e15bd25f5.png)

Habilitamos el autoescalado de la manera deseada:

![image](https://user-images.githubusercontent.com/72698383/198616323-22392f12-c190-48ad-83bf-3023f5772859.png)

![image](https://user-images.githubusercontent.com/72698383/198616413-106f4f6c-3a61-4205-8fdd-471c5d8c8d45.png)

Realizamos un test de alta demanda en otra terminal y observamos como actúa el sistema ante el mismo:

![image](https://user-images.githubusercontent.com/72698383/198616537-afbf0dbf-e957-4759-88d5-20753f5f2ce6.png)

**Entrega 2**

Creamos el dockerfile y comprobamos su imagen:

![image](https://user-images.githubusercontent.com/72698383/198616667-38f640b6-a651-43e5-ac96-687cf0520969.png)

![image](https://user-images.githubusercontent.com/72698383/198616755-0606d1f9-acd9-44b7-a21b-4ad981d9c692.png)

![image](https://user-images.githubusercontent.com/72698383/198616864-ef8e462f-d862-4218-b6e0-2cd4cde70db1.png)

Hacemos un push de la imagen a Google cloud:

![image](https://user-images.githubusercontent.com/72698383/198616977-31197bef-f032-4699-8072-b50a79500c60.png)

![image](https://user-images.githubusercontent.com/72698383/198617069-0c4ab71b-4615-49e1-81eb-8ac45255ca78.png)

Creamos el job.yaml:

![image](https://user-images.githubusercontent.com/72698383/198617456-e9bc2a38-d3c4-448d-9807-a3be1f7bb359.png)
