# Gestor de Gastos (Python)

Aplicación de consola para registrar y analizar gastos personales. Guarda los datos en JSON, calcula totales por día, semana y mes, y genera reportes por categoría o por rango de fechas.

## Funcionalidades

- Registrar gastos con fecha, categoría, monto y descripción (con validación de cada campo).
- Listar todos los gastos en una tabla, o filtrarlos por categoría o por rango de fechas.
- Calcular totales diarios, semanales y mensuales.
- Generar reportes diarios, semanales o mensuales con resumen por categoría y guardarlos en JSON.
- Generar un reporte detallado por rango de fechas y categoría.

## Tecnologías

- Python 3.10+
- [tabulate](https://pypi.org/project/tabulate/) para mostrar las tablas
- Persistencia en archivos JSON

## Estructura

```
main.py          Punto de entrada
core/            Lógica: registro, filtros, reportes y almacenamiento en JSON
ui/              Menús y pantallas de la consola
utils/           Validaciones y utilidades de pantalla
data/            gastos.json con datos de ejemplo
```

## Cómo ejecutarlo

```bash
git clone https://github.com/Jonatan-17/gestor-gastos-python.git
cd gestor-gastos-python
pip install -r requirements.txt
python main.py
```

Los reportes se guardan en `data/` (reportes por periodo) y en `reports/` (reporte detallado).

## Autor

Jonatan David Sarmiento Sierra — [GitHub](https://github.com/Jonatan-17) · [LinkedIn](https://www.linkedin.com/in/jonatan-sarmiento-16a206366/)
