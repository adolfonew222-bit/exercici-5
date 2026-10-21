# Simulación del ejercicio de GitHub Actions

Archivos de práctica:
- `calculadora.py`: funciones que se van a probar.
- `test_calculadora.py`: tests con `unittest`.
- `.github/workflows/compila.yml`: workflow que ejecuta los tests en Windows, Linux y macOS al hacer push a `main`.

## Ejecutar los tests en local

Desde esta carpeta, ejecuta:

```bash
python -m unittest -v
```

Los archivos son de ejemplo para practicar; no son los archivos originales del ZIP del profesor.
