Introducción

Esta aplicación Java conversorDeMonedas(Currency Converter) le ayuda a convertir entre varias monedas con facilidad. Actualmente admite conversiones entre el dólar estadounidense (USD) y las siguientes monedas:

Peso Argentino (ARS)
Real brasileño (BRL)
Colombian Peso (COP)
Características

Menú fácil de usar para seleccionar opciones de conversión.
Tipos de cambio en vivo obtenidos de una API externa.
Maneja la entrada del usuario y proporciona resultados de conversión.
Empezando

Prerrequisitos

Kit de desarrollo de Java ( JDK) instalado (https://www.oracle.com/java/technologies/javase-downloads.html).   
Un editor de texto o IDE de su elección (por ejemplo, Notepad++, Visual Studio Code, IntelliJ IDEA).
Descargar

Clonar o descargar el repositorio del proyecto que contiene el código fuente de Java ( conversorDeMonedas.java).
Construir y ejecutar

Abra una terminal o un símbolo del sistema y navegue hasta el directorio donde guardó el archivo Java.
Compila el código usando un comando como:javac conversorDeMonedas.java
Ejecute el programa compilado usando:java conversorDeMonedas
Uso

Cuando ejecute la aplicación, aparecerá un menú con las opciones de conversión. Simplemente ingrese el número correspondiente para realizar la conversión deseada:

Dólar => Peso argentino (Dollar to Argentine Peso)
Peso argentino => Dólar (Argentine Peso to Dollar)
Dólar => Real brasileño (Dollar to Brazilian Real)
Real brasileño => Dólar (Brazilian Real to Dollar)
Dólar => Peso colombiano (Dollar to Colombian Peso)
Peso colombiano => Dólar (Colombian Peso to Dollar)
Salir (Exit)
El programa le solicitará el monto a convertir y luego mostrará el monto equivalente en la moneda de destino según los últimos tipos de cambio obtenidos de una API externa.

Notas adicionales

Esta aplicación se basa en una API externa para obtener tipos de cambio en tiempo real. Asegúrese de contar con una conexión a Internet confiable para realizar conversiones precisas.
El código utiliza la clase de Java Scannerpara la entrada del usuario y la HttpClientclase para realizar solicitudes de API.
Se incluye el manejo de errores para manejar con elegancia posibles excepciones durante la comunicación API.
Este README ofrece una descripción general clara y concisa de la conversorDeMonedasaplicación, que guía a los usuarios a través de la configuración, el uso y la funcionalidad. Siéntase libre de personalizarlo aún más si planea agregar más funciones o funcionalidades en el futuro.
