# Práctica SSL

Mi nombre es Francisco Javier Muriel Orta y este es uno de los ejercicios realizados para Despliegue de Aplicaciones Web durante el segundo año de DAW.

---

## Descripción

Esta práctica consiste en:

1. **Certificado autofirmado en Apache**  
   - Se configuró un VirtualHost SSL en Apache con certificado autofirmado.  
   - Se comprobó HTTPS en localhost con `curl -v https://localhost`.  

2. **Segunda parte (Let’s Encrypt y Certbot)**  
   - Se creó un hostname público en No-IP: `fran16121993.ddns.net`.  
   - Se intentó generar un certificado Let’s Encrypt, pero **falló la verificación** porque el servidor está en VirtualBox con NAT y no es accesible desde Internet.  
   - Se explica cómo funcionaría en un servidor accesible públicamente (por ejemplo AWS EC2).  

---
