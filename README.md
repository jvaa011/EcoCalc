# EcoCalc
EcoTrack es una aplicación web desarrollada con Flask que estima la huella de carbono de los usuarios a partir de sus hábitos diarios y ofrece recomendaciones para reducir su impacto ambiental.

# 🌱 EcoCalc

**EcoCalc** es una aplicación web desarrollada con **Python y Flask** que permite estimar el impacto ambiental de una persona a partir de sus hábitos cotidianos. Su objetivo es ayudar a los usuarios a comprender cómo sus decisiones diarias influyen en el medio ambiente y ofrecer recomendaciones prácticas para reducir ese impacto sin afectar significativamente su estilo de vida.

---

## 📖 Descripción

Muchas personas desean adoptar hábitos más sostenibles, pero no saben cuáles de sus acciones tienen un mayor impacto ambiental ni qué cambios serían realmente efectivos.

EcoCalc busca resolver este problema mediante una experiencia sencilla e intuitiva. A través de un formulario, el usuario responde preguntas sobre sus hábitos diarios y la aplicación analiza la información para generar un reporte personalizado.

En lugar de limitarse a mostrar un número, EcoCalc explica los resultados de forma comprensible, identifica la principal fuente de impacto ambiental y propone soluciones realistas que pueden incorporarse poco a poco en la rutina diaria.

---

## 🎯 Objetivo

Desarrollar una aplicación web que fomente la conciencia ambiental mediante el cálculo aproximado de la huella de carbono y un análisis de los hábitos cotidianos del usuario.

---

## ✨ Características

- Cálculo aproximado de la huella de carbono.
- Índice EcoCalc para representar el impacto ambiental mediante una puntuación sencilla.
- Análisis personalizado según los hábitos del usuario.
- Identificación de la principal fuente de impacto ambiental.
- Recomendaciones prácticas y realistas para reducir las emisiones.
- Explicación de la huella de carbono utilizando comparaciones fáciles de entender.
- Mensaje final de concienciación ambiental.
- Enlaces a organizaciones y proyectos reales relacionados con el cuidado del medio ambiente.

---

## 📝 Información solicitada

La aplicación realiza preguntas sobre hábitos cotidianos que cualquier persona puede responder fácilmente:

- 🚗 Medio de transporte utilizado con mayor frecuencia.
- 🥩 Frecuencia de consumo de alimentos de origen animal.
- 🚿 Duración promedio de las duchas.
- 👕 Frecuencia con la que se lava la ropa (a mano o en lavadora).
- ⚡ Nivel de consumo eléctrico del hogar.
- 💧 Preferencia entre agua embotellada o termo reutilizable.
- ♻️ Frecuencia con la que recicla.
- 🗑️ Separación de residuos.
- 👕 Preferencia por comprar ropa nueva o de segunda mano.

---

## 📊 Resultado del análisis

Al finalizar el formulario, EcoCalc mostrará:

- 🌱 Índice EcoCalc (0–100).
- 🌍 Huella de carbono estimada.
- 📈 Explicación sencilla de lo que representa esa huella.
- 📊 Desglose del impacto por categoría.
- 🔎 Identificación de la mayor fuente de impacto ambiental.
- 💡 Recomendaciones personalizadas para mejorar los hábitos con mayor impacto.
- 🌎 Invitación a participar en iniciativas reales de protección ambiental.

---

## 🛠️ Tecnologías utilizadas

- Python
- Flask
- HTML5
- CSS3
- Jinja2
- Git
- GitHub

---

## 📂 Estructura del proyecto

```text
EcoCalc/
│
├── app.py
├── calculadora.py
├── templates/
│   ├── index.html
│   └── resultado.html
├── static/
│   ├── css/
│   ├── images/
│   └── icons/
├── data/
│   └── factores.json
├── requirements.txt
└── README.md
```

---

## 🚀 Instalación

Clona el repositorio:

```bash
git clone https://github.com/tu-usuario/EcoCalc.git
```

Entra en la carpeta del proyecto:

```bash
cd EcoCalc
```

Crea un entorno virtual:

```bash
python -m venv venv
```

Actívalo.

**Windows**

```bash
venv\Scripts\activate
```

**Linux / macOS**

```bash
source venv/bin/activate
```

Instala las dependencias:

```bash
pip install -r requirements.txt
```

Ejecuta la aplicación:

```bash
python app.py
```

Abre el navegador y visita:

```
http://127.0.0.1:5000
```

---

## 💻 Funcionamiento

1. El usuario responde un formulario sobre sus hábitos diarios.
2. La aplicación procesa la información.
3. Se calcula una estimación de la huella de carbono.
4. Se genera un Índice EcoCalc.
5. Se identifica el hábito con mayor impacto ambiental.
6. Se presentan recomendaciones prácticas y personalizadas.
7. El usuario recibe recursos para seguir contribuyendo al cuidado del medio ambiente.

---

## 🌍 Problema que aborda

Uno de los principales desafíos ambientales actuales es que muchas personas desconocen cómo sus acciones cotidianas contribuyen al cambio climático. Esta falta de información dificulta la adopción de hábitos más sostenibles.

EcoCalc busca reducir esa brecha proporcionando una estimación sencilla del impacto ambiental personal y orientando al usuario con recomendaciones realistas, demostrando que pequeños cambios pueden generar un efecto positivo cuando se mantienen en el tiempo.

---

## 📚 Objetivos de aprendizaje

Este proyecto aplica conocimientos de:

- Desarrollo web con Flask.
- Plantillas dinámicas utilizando Jinja.
- HTML y CSS.
- Enrutamiento y procesamiento de formularios.
- Organización de proyectos en Python.
- Buenas prácticas de programación (PEP 8).
- Control de versiones con Git y GitHub.

---

## 🤝 Contribuir

Las sugerencias para mejorar EcoCalc son bienvenidas. Si deseas contribuir, puedes abrir un *Issue* o enviar un *Pull Request*.

---

## 📄 Licencia

Este proyecto fue desarrollado con fines educativos como proyecto final del curso de Python.
