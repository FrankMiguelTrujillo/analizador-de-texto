### 2. README para el analizador de texto

```markdown
# Analizador de Texto - Contador de Letras y Palabras

Un programa simple en Python que analiza un texto ingresado por el usuario y devuelve información estadística básica: cantidad de letras específicas, número de palabras, primera y última letra, texto invertido y búsqueda de la palabra "python".

## Descripción

El usuario ingresa un texto y tres letras cualquiera. El programa muestra:
- Cuántas veces aparece cada letra
- Cantidad total de palabras
- Primera y última letra del texto
- El texto invertido (palabras al revés)
- Si la palabra "python" está presente

## Características

- Conversión a minúsculas para conteo insensible a mayúsculas
- Conteo preciso de ocurrencias de letras con `.count()`
- División en palabras con `.split()`
- Búsqueda booleana de palabra específica
- Manejo básico de entrada de usuario

## Cómo usar

1. Clona el repositorio
2. Ejecuta el script:
   ```bash
   python analizador_texto.py
