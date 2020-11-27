## Casos de uso

**CU01:** Comenzar la conversación 

**Descripción:** El usuario Iniciara una conversación con el Bot.

**Secuencia:**
1. El usuario ingresa a la plataforma.
2. El usuario abre el chat del Bot.
3. El usuario escribe en el chat y envía una letra palabra u oración..
4. El sistema responde con un saludo

**Salidas alternas:** 4.1 En el caso de que se inicie con una pregunta, además del saludo se mostrara una respuesta e incluso le ofrece sugerencias.

------------

**CU02:** Hacer preguntas 

**Descripción:** El usuario formula una pregunta al Bot y recibe una respuesta.

**Secuencia:**
1. Escribe una pregunta al Bot
2. El sistema analiza la pregunta, la busca en la base de datos y la presenta en pantalla en forma de platica.
3.El sistema le dará la opción de hacer otra pregunta al usuario. 

**Salidas alternas:** 2.1 Si la respuesta no se encuentra en la base de datos se escribe en pantalla que no se tiene la información buscada y se registra en la libreta para futuras actualizaciones.

------------

**CU03:** Consultar el historial 

**Descripción:** El usuario accede al historial de la platica para poder ver toda la información que se le a ofrecido.  

**Secuencia:**
1. El usuario ingresa a la plataforma.
2. El usuario abre el chat del Bot.
3. El sistema, carga el historial de las platicas que ah mantenido con el usuario y las muestra en la pantalla   
4. El usuario se pude desplazar por el historial y leer la información anterior todo el tiempo que lo necesité.

**Salidas alternas:** 3.1 En caso de que sea un nuevo usuario, no habrá historial que mostrar.

------------

## Diagrama de Casos de Uso
![Diagrama](https://1drv.ms/u/s!ApOxl67wNUiCwhQ3kTvRKHybKkAp?e=7Yp0S5)
