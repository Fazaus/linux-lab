# Comandos Usados - Semana 7

## Generacion y control de tiempo
- `seq 1 10`: Generar secuencia de numeros
- `sleep 5`: Pausar la ejecucion (ej. 5 segundos)
- `timeout 10 comando`: Terminar un comando si supera el tiempo limite (10s)

## Ciclos y control de flujo
- `for var in lista; do ... done`: Bucle sobre una lista o salida de comando
- `while [ condicion ]; do ... done`: Bucle mientras la condicion sea verdadera
- `until [ condicion ]; do ... done`: Bucle hasta que la condicion sea verdadera
- `while IFS= read -r linea; do ... done < archivo`: Leer archivo linea por linea
- `break`: Salir del bucle inmediatamente
- `continue`: Saltar a la siguiente iteracion

## Redirecciones avanzadas
- `comando | xargs otro_comando`: Convertir salida de comando en argumentos
- `trap 'comandos' INT`: Ejecutar comandos al recibir una señal (como Ctrl+C)
