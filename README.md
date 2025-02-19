# 🐍 Bootcamp de Python

Este proyecto forma parte del Bootcamp de Python, enfocado en la práctica de conceptos fundamentales del lenguaje, como tipos de datos, control de versiones con Git y el uso de entornos de desarrollo como Visual Studio Code.

## 📁 Estructura del Proyecto

El proyecto incluye los siguientes elementos:

- **Carpeta principal:** `Bootcamp-de-Python`
- **Archivo de práctica:** `tipos-de-datos.py`

## 🚀 Instalación y Configuración

Sigue estos pasos para configurar el entorno:

1. Abre Git Bash y crea la carpeta del proyecto:
```bash
cd ~/Documentos
git bash
mkdir Bootcamp-de-Python
cd Bootcamp-de-Python
```

2. Crea el archivo `tipos-de-datos.py`:
```bash
touch tipos-de-datos.py
```

3. Abre Visual Studio Code desde la terminal:
```bash
code .
```

## 📝 Código de Tipos de Datos Simples

Dentro del archivo `tipos-de-datos.py`, escribe el siguiente código para explorar los tipos de datos simples en Python:

```python
# Ejemplo de tipos de datos simples
entero = 10
flotante = 3.14
cadena = "Hola, mundo"
booleano = True

print(f"Entero: {entero}")
print(f"Flotante: {flotante}")
print(f"Cadena: {cadena}")
print(f"Booleano: {booleano}")
```

## 🌳 Control de Versiones con Git

Realizaremos los tres estados de Git: **working directory**, **staging area** y **repository**.

1. **Verificar el estado:**
```bash
git status
```

2. **Agregar cambios al área de preparación:**
```bash
git add tipos-de-datos.py
```

3. **Confirmar los cambios:**
```bash
git commit -m "Agregar archivo de tipos de datos"
```

4. **Enviar los cambios al repositorio remoto:**
```bash
git push origin main
```

## 🤝 Contribuciones

Si deseas contribuir:
1. Realiza un fork del proyecto.
2. Crea una nueva rama para tu funcionalidad (`git checkout -b nueva-funcionalidad`).
3. Realiza tus cambios y haz un commit (`git commit -m "Agregar nueva funcionalidad"`).
4. Envía un pull request.

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Puedes utilizarlo libremente para fines educativos y de aprendizaje.

