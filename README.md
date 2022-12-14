# Informe_Corrección
# 1. OBJETIVOS 

# **Objetivo General:**

* Analizar y comprender el funcionamiento de cada uno de los circuitos para comprender e implentar la materia estudiada con la ayuda de los simuladores.

# **Objetivo Específicos:**

* Explicar en qué consiste el Teorema de la Máxima Transferencia de Potencia.

* Analizar el comportamiento de un circuito mediante la aplicación del Teorema de la MTP y comprobar los resultados obtenidos teóricamente de la potencia máxima en RL.

* Analizar el metodo de superposicion para determinar los valores que solicita el problema para obtener un mejor conocimiento sobre lo que sucede en el circuito 

* Explicar el ciruito de Thevenin para resolver el problema sintetizando el circuito para encontrar valores especificos

# 2. MARCO TEORICO

![image](https://user-images.githubusercontent.com/105617383/184851300-7869b3e0-47a2-4c49-a492-425d5b1e7bd4.png)

![image](https://user-images.githubusercontent.com/105617383/184851386-84dbe598-0c5a-4f62-8aaf-c5a8065ed9b8.png)

![image](https://user-images.githubusercontent.com/105617383/184851916-0bf2f880-92e4-4e06-85fc-86b783d60cc1.png)

# 3. EXPLICACIÓN DEL PROCEDIMIENTO

# **Empleando el circuito de Thévenin determine la potencia suminstrada a la resistencia R3**

![image](https://user-images.githubusercontent.com/105617383/184721717-55e79615-5739-4982-966c-b96cada84605.png)

**Mediante instrumentos encuentre el circuito equivalnte de Thévenin.**

**Emplee el vatimeto para determinar la potencia.**

![image](https://user-images.githubusercontent.com/105617383/184722674-197060bc-7b18-42e7-9005-8dbade44e576.png)

**El teorema de Thevenin dice que, cualquier circuito puede ser simplificado obteniendo una fuente de voltaje y una resistencia a las que se las denominará con el voltaje y resistencia equivalente de Thevenin.**

**Por lo tanto lo que aremos es retirar la resistencia R3 de 2.2kΩ para obtener el voltaje.**

![image](https://user-images.githubusercontent.com/105617383/184722900-1cab62d0-34da-4e4b-982a-e28614664dad.png)

**Vamos a  determinar la resistencia de Thevenin, se reemplazan las fuentes por su resistencia interna, la cual es un circuito cerrado**

![image](https://user-images.githubusercontent.com/105617383/184723611-3be2a7e5-6f5e-46b7-b3a0-dad2d54ac65e.png)

**Circuito de Thévenin**

![image](https://user-images.githubusercontent.com/105617383/184724906-54203fe3-7d7f-4c90-92c8-5d19ed12d260.png)

**Calculamos los resultados obtenidos para obtenr la potencia que existe en la R3.**

![image](https://user-images.githubusercontent.com/105617383/184724506-8196d298-03bd-44c0-aa47-2a1c8d014601.png)

**Comprobamos la potencia con DCACLab.**

![image](https://user-images.githubusercontent.com/105617383/184726281-695b2f91-8280-4bbb-b750-93c4d8759753.png)

# **Encontrar la corriente y el voltaje a traves de la resistencia de 12Ω mediante el teorema de superposición.**

![image](https://user-images.githubusercontent.com/105617383/184726735-7f165f27-bc1d-4bf2-8de5-f45d59b3b24d.png)

**Primeramente se tiene que armar el circuito, obteniendo lo siguiente:**

![image](https://user-images.githubusercontent.com/105617383/184729081-9b84c066-3e06-4c55-afa7-12ebf06cd8e7.png)

**El teorema de superposicion indica que se deben reemplazar las fuentes de corriente y de voltaje por su resistencia interna. Dependiendo de cuantas fuentes de corriente o de voltaje se tenga, se formaran los circuitos.**

![image](https://user-images.githubusercontent.com/105617383/184741071-bed3fada-9eac-4009-97f8-45cb4130367f.png)

**En el siguiente circuito mediremos el voltaje con una corriente de 10 voltios.**

![image](https://user-images.githubusercontent.com/105617383/184756778-dde89282-0695-400c-bca1-28dd20ef9480.png)

**Medimos la corriente que pasa en la resistencia de 12 Ω.**

![image](https://user-images.githubusercontent.com/105617383/184741601-854d661d-8f08-4255-a051-85e54761e4cb.png)

**En el siguiente circuito mediremos el voltaje con una corriente de 16 voltios.**

![image](https://user-images.githubusercontent.com/105617383/184755782-37d1cde0-5ec8-4c77-9842-3bdefda089e6.png)

**La corriente que pasa por la resistencia**

![image](https://user-images.githubusercontent.com/105617383/184741771-be93c486-9596-4837-975c-c56ca7a41925.png)

**El voltaje que pasa por la resistencia**

![image](https://user-images.githubusercontent.com/105617383/184756876-2ab30263-31ef-4471-af9e-b3cab9d5b3b5.png)

# **Clacular la intensidad I que pasará por la resistencia 5Ω utilizando Thevenin**

![image](https://user-images.githubusercontent.com/105617383/184757770-3d75f1f2-855f-4571-9cf5-ab153b1b3663.png)

![image](https://user-images.githubusercontent.com/105617383/184758419-128530ae-bee5-4438-9db6-fdbab4c54150.png)

**Como se habia mencionado antes, el teorema de Thevenin dicta que, cualquier circuito puede ser simplificado obteniendo una fuente de voltaje y una resistencia a las que se las denominará con el voltaje y resistencia equivalente de Thevenin.**

![image](https://user-images.githubusercontent.com/105617383/184759330-80263fc2-ea94-4995-81d7-bb648faa195e.png)

**Por lo tanto el voltaje de Thevenin quitando la resistencia de 5ohms es el siguiente:**

![image](https://user-images.githubusercontent.com/105617383/184759779-7b4b30fb-c0f8-4df9-a347-aafcc688a700.png)

**Por lo tanto la resistencia de Thevenin se obtiene:**

![image](https://user-images.githubusercontent.com/105617383/184760828-f7d8b349-7ad4-4cc5-b0b2-f485d0860248.png)

**El circuito de Thevenin:**

![image](https://user-images.githubusercontent.com/105617383/184769953-ea8b70b6-c756-4702-a2a0-8a5567b11e73.png)

**Obtenemos la corriente en 5Ω.**

# **4. Video**

https://youtu.be/8A5UDfUVej8

# **5.Conclusiones**

* Los teroremas aprendidos en clase nos permite realizar de forma mas rapida en los simuladores, ya que nos ayuda comprender y la retención de la clases aprendidad.

* Con la ayuda de los simuladores podemos tener un acercamiento con la parctica fisica, adquiriendo conosimiento y  obtneniendo al gunas fallas donde podemos arreglarlas.

# **6.Bibliogrfía**

Floyd, Thomas. 2007. Principios de circuitos eléctricos. Octava edición.
