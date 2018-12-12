# Blacklist

Repositorio de varios listados para utilizar como Blacklist de origenes a bloquear.

Se combinan multiples listados obtenidos desde diferentes origenes:



Dominios: Listados de dominios a bloquear en texto plano, procesados linea por linea. Soporta wildards simples como por ejemplo:


mail.*.or.th |
*-special.de.vu |
http://www.*de.vu |
610-pawn.com |
aaliyah-hq-gallery.de.vu |
abcgolocal.com |

No se aceptan espacios ni simbolos de comentarios al final de la linea. Cada linea e sinterpretada como un dominio completo.

IPs y Redes: Listados de IPs Redes o Rangos en texto plano, procesados linea por linea.

Al ser utilizadas en DNS profiles del fortinet, solo IPV4 es soportado mientras que las IPV6 seran ignoradas.

Ejemplo:

1.1.1.1 |
10.0.0.70 |
2.1.1.1 |
100.0.0.1-100.0.0.100 |
10.0.0.99-10.0.0.201 |
1.2.2.2/24 |

