# Reporte de Analisis de Logs

**Archivo analizado:** sample.log
**Fecha del analisis:** 2026-05-29 05:16:17
**Total de entradas:** 500

## 1. Top 10 Direcciones IP

| Solicitudes | Direccion IP |
|---|---|
| 161 | 192.168.1.10 |
| 108 | 10.0.0.5 |
| 65 | 203.0.113.42 |
| 58 | 172.16.0.3 |
| 57 | 10.0.0.99 |
| 51 | 192.168.1.25 |

## 2. Distribucion por Severidad

| Nivel | Cantidad |
|---|---|
| FATAL | 93 |
| ERROR | 89 |
| WARNING | 89 |
| INFO | 229 |

## 3. Eventos por Hora

| Hora | Eventos |
|---|---|
| 00:00 | 27 |
| 01:00 | 22 |
| 02:00 | 19 |
| 03:00 | 28 |
| 04:00 | 17 |
| 05:00 | 29 |
| 06:00 | 13 |
| 07:00 | 22 |
| 08:00 | 16 |
| 09:00 | 26 |
| 10:00 | 18 |
| 11:00 | 20 |
| 12:00 | 25 |
| 13:00 | 22 |
| 14:00 | 23 |
| 15:00 | 18 |
| 16:00 | 12 |
| 17:00 | 15 |
| 18:00 | 12 |
| 19:00 | 24 |
| 20:00 | 28 |
| 21:00 | 20 |
| 22:00 | 21 |
| 23:00 | 23 |

## 4. Top 5 Mensajes de Error

| Frecuencia | Mensaje |
|---|---|
| 64 | Connection timeout after 30s |
| 45 | Authentication failed for user admin |
| 31 | Failed to write to disk |
| 23 | Database connection refused |
| 19 | Out of memory error in module X |

## 5. Resumen

- Sistema analizado con 500 eventos registrados.
- 182 eventos requieren atencion (ERROR y FATAL).
- Analisis completado con herramientas UNIX estandar.
