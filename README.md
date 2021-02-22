# security.txt
Security.txt es un estándar propuesto [(ver Draft IETF)](https://tools.ietf.org/html/draft-foudil-securitytxt-10) que brinda a las organizaciones que publican servicios web definir políticas de seguridad. La implementación del archivo security.txt permite dar a conocer las pautas y canales de comunicación ante el hallazgo de vulnerabilidades.

[Consideraciones sobre el contenido]  
El archivo security.txt contiene una serie de campos a completar, algunos son de carácter obligatorio y otros opcionales.
> • Contact:  Campo de carácter requerido, se indica cual será el canal de contacto a utilizar para comunicarse con la organización. Se sugiere indicar una dirección de correo del área de seguridad de la información.  
> 
> • Encryption: (Opcional). Se utiliza para indicar que se encuentra disponible la clave PGP para entablar comunicaciones cifradas. Las claves NO deben aparecer en este campo sino que se indicará la ubicación donde se puede recuperar la clave.  
> 
> •	Acknowledgments: (Opcional). La iniciativa permite indicar mediante un enlace el reconocimiento que realiza la organización a aquellas personas u organizaciones que han colaborado anteriormente con informes de seguridad.  
> 
> •	Canonical: (Opcional). Este campo se puede utilizar para indicar un conjunto de lenguajes naturales que se prefieren para recibir información. Este conjunto puede listar varios valores, separados por comas. Si este campo está incluido, debe indicarse al menos un valor. Los valores dentro de este conjunto son etiquetas de idioma compuestos por las dos letras iniciales del mismo.  
> 
> •	Policy: (Opcional). Este campo permite especificar un enlace donde se encuentra la política de seguridad sobre la divulgación de vulnerabilidades de la organización.  
> 
> •	Hiring: (Opcional). Se puede utilizar este campo para indicar, a través de un enlace, posiciones de trabajo de la organización relacionadas con seguridad.  

[Ejemplo]

```
Contact: mailto:cert@icic.gob.ar
Encryption: https://github.com/cert-ar/PGP-Key/blob/main/CERT-AR-PGP-2021.asc
Preferred-Languages: es, en
```
[Algunas consideraciones respecto a su uso]  
El archivo security.txt debe ser en texto plano y presentarse a través de HTTPS en una ubicación determinada.

[Referencias]  
• Sitio web del proyecto:  [https://securitytxt.org/](https://securitytxt.org/)  
• Draft en IETF:  [https://tools.ietf.org/html/draft-foudil-securitytxt-10](https://tools.ietf.org/html/draft-foudil-securitytxt-10)
