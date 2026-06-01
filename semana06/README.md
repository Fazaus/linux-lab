# Semana 06: Bash Scripting - Condicionales

## Descripcion
`backup-check.sh` valida el estado de un directorio de backups.
Verifica existencia, contenido, antiguedad y tamano, y emite un diagnostico con niveles OK / WARNING / ERROR.

## Uso
```bash
./backup-check.sh                   # Usa /backup por defecto
./backup-check.sh /mnt/respaldo     # Directorio personalizado
./backup-check.sh ~/backup-prueba   # Directorio de prueba
./backup-check.sh --version         # Version del script
./backup-check.sh --help            # Ayuda
```

## Estructura
```
semana06/
├── README.md
├── backup-check.sh
├── commands-used.md
└── logs/
    └── backup-check-YYYYMMDD.log
```

## Verificaciones que realiza
1. Existencia y permisos del directorio de backups
2. Presencia de archivos .tar.gz y que no esten vacios
3. Antiguedad: alerta si el ultimo backup supera las 24 horas
4. Tamano: alerta si el directorio esta fuera del rango esperado

## Conceptos aprendidos
- El comando test y la sintaxis [ ]
- if / elif / else con operadores numericos, de cadena y de archivo
- Operadores logicos &&, || y !
- La estructura case / esac
- Funciones con parametros, return y local
- Logging estructurado con tee -a
- Medicion de espacio con du -sm
- Busqueda por antiguedad con find -mtime
