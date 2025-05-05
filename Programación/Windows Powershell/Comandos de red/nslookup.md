```
nslookup (nombre dominio) -> devuelve en primer lugar la respuesta del servidor DNS y la dirección IP asociada al dominio o a un CDN tipo Cloudfflare.

¿Cómo podemos averigurar si se trata de la dirección IP del servidor que aloja al sitio o si se trata de un CDN?

1.Usar herramientas tipo WhoIs Lookup, realizar una búsqueda Whois de la IP. Si devuelve el nombre del CDN, pues eso. Herramientas -> Whois.com o ARIN Whois
2. Servicios de geolocalización de IP, información sobre IP incluida la localización geográfica, el ISP y si pertenece a un CDN
3. Herramientas como ipi.info, iplocation.net o ip-api.com [[Buscar en Herramientas búsqueda IP]]
```
![[Pasted image 20250329163037.png]]

Si escribimos nslookup entraremos en el modo interactivo
**En este momento podemos introducirle un dominio para obtener la misma respuesta que anteriormente**
![[Pasted image 20250329163557.png]]
O podemos introducir los siguientes -type=:
![[Pasted image 20250329163823.png]]
Por ejemplo: 
![[Pasted image 20250329165823.png]]
También podemos consultar el conjunto de servidores de nombres de un sitio
![[Pasted image 20250329170306.png]]
Por ejemplo:
![[Pasted image 20250329170946.png]]

También podemos realizar una búsqueda inversa (Reverse DNS lookup) puedes obtener el nombre del dominio a partir de una IP. **IMPORTANTE** -> NO SIEMPRE OBTENDREMOS EL NOMBRE DEL DOMINIO PARA LA IP, depende de si tienen el PTR configurado y eso no siempre está garantizado


