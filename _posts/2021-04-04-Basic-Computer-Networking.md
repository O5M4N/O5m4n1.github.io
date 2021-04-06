---
title:Basics for Computer-Networking
published: true
---
# Conversiones

- Convertir de Binario a Decimal
- Convertir de Decimal a Binario


## Convertir de Binario a Decimal

**Tabla de Referencia**  

| 2^7 | 2^6 | 2^5 | 2^4 | 2^3 | 2^2 | 2^1 | 2^0 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 128 | 64  | 32  | 16  | 8   | 4   | 2   | 1   |

convertir 101101
colocamos cada 1 de derecha a izquierda

| 2^7 | 2^6 | 2^5 | 2^4 | 2^3 | 2^2 | 2^1 | 2^0 | Numero |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 128 | 64  | 32  | 16  | 8   | 4   | 2   | 1   |     |
|     |     | 1   | 0   | 1   | 1   | 0   | 1   | DECIM|
| 0   | 0   | 32  | 0   | 8   | 4   | 0   | 1   | 45  |  

Sumamos los valores y nos da 45  
  
  
## Convertir de Decimal a Binario

| 2^7 | 2^6 | 2^5 | 2^4 | 2^3 | 2^2 | 2^1 | 2^0 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 128 | 64  | 32  | 16  | 8   | 4   | 2   | 1   |

convertir 78  
comparamos el 78 con cada numero  
78 es mayor igual a 128 = No  
78 es mayor igual a 64 = SI 78 - 64 = 14  
14 es mayor igual a 32 = No  
14 es mayor igual a 16 = No  
14 es mayor igual a 8  = SI 14 - 8 = 6  
6 es mayor igual a 4   = SI 6 - 4 = 2  
2 es mayor igual a 2   = SI 2 - 2 = 0  
0 es mayor igual a 1   = NO  
  
REMPLAZAMOS LOS SI POR 1 en la tabla

| 2^7 | 2^6 | 2^5 | 2^4 | 2^3 | 2^2 | 2^1 | 2^0 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 128 | 64  | 32  | 16  | 8   | 4   | 2   | 1   |
| 0   | 1   | 0   | 0   | 1   | 1   | 1   | 0   |

78 = 01001110
