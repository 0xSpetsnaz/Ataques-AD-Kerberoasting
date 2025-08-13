El presente Trabajo Fin de Máster tiene como objetivo principal el estudio, análisis y ejecución 
de técnicas avanzadas de ataque dirigidas a entornos Active Directory, en particular aquellas 
relacionadas con el control y la escalada de privilegios dentro de una infraestructura de red 
basada en Windows. Se ha llevado a cabo una extensa investigación sobre tres métodos 
reconocidos por su eficacia y potencial destructivo: el ataque Golden Ticket, el ataque DCSync 
y la extracción del archivo NTDS.dit.  
Para este TFM se ha pensado y desplegado un entorno de laboratorio controlado que reproduce 
una infraestructura corporativa, compuesto por un controlador de dominio, una estación de 
trabajo víctima y una máquina atacante. Este entorno ha permitido desarrollar cada ataque en 
condiciones lo más realistas posibles y registrando paso a paso su ejecución, herramientas 
utilizadas, y el impacto generado en el sistema comprometido.  
El ataque Golden Ticket demuestra cómo un atacante con acceso al hash de la cuenta krbtgt 
puede generar tickets de autenticación Kerberos válidos sin interacción con el controlador de 
dominio, obteniendo acceso persistente e indetectable a recursos críticos. Por otro lado, el 
ataque DCSync revela cómo es posible replicar objetos del dominio, incluyendo credenciales, 
mediante el uso de privilegios elevados, simulando el comportamiento de un controlador de 
dominio legítimo. Finalmente, la extracción de NTDS.dit permite al atacante hacerse con la 
base de datos completa de cuentas del dominio, lo que representa una exfiltración crítica de la 
información más sensible.  
A lo largo del trabajo se detallan las herramientas empleadas, como Rubeus, Mimikatz o 
impacket, así como los procedimientos y consideraciones de cada fase del ataque. De igual 
forma, se discute el uso de la práctica de estas técnicas desde la perspectiva de un Red Team, 
destacando su utilidad en auditorías de seguridad ofensiva.  
Para este trabajo se busca demostrar la posibilidad de ataques y ofrecer un recurso formativo 
extenso y estructurado, orientado a entender las amenazas y a la concienciación sobre la 
importancia de implementar medidas preventivas y defensivas adecuadas en los sistemas 
corporativos.

> [NOTA]
> Vídeo aparte. Solicítalo si quieres ver el proceso entero. Gracias :)
