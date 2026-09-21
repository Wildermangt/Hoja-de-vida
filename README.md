# Hoja de vida

Mi hoja de vida en formato web y en PDF, en dos versiones: una pensada para
que la lea una persona y otra pensada para que la lea una máquina.

**Jeferson Wilderman González Tenjo** — Ingeniería de Sistemas
Bogotá, Colombia

### 👉 [Verla en línea](https://wildermangt.github.io/Hoja-de-vida/)

| | |
|---|---|
| 🖥️ [Versión para leer](https://wildermangt.github.io/Hoja-de-vida/hoja-de-vida.html) | 🤖 [Versión ATS](https://wildermangt.github.io/Hoja-de-vida/hoja-de-vida-ATS.html) |
| 📄 [PDF](https://wildermangt.github.io/Hoja-de-vida/Hoja%20de%20Vida%20-%20Jeferson%20Wilderman%20Gonzalez.pdf) | 📄 [PDF ATS](https://wildermangt.github.io/Hoja-de-vida/Hoja%20de%20Vida%20-%20Jeferson%20Wilderman%20Gonzalez%20ATS.pdf) |

---

## Por qué hay dos versiones

Buena parte de las postulaciones no llega primero a un reclutador, sino a un
**ATS** (*Applicant Tracking System*): el software que filtra las hojas de vida
antes de que alguien las mire. Esos sistemas leen mal las columnas, las tablas,
los iconos y el texto dentro de imágenes — justo los recursos que hacen que una
hoja de vida se vea bien.

Intentar que un solo documento sirva para los dos casos termina en un archivo
que ni se ve bien ni se lee bien. Por eso son dos:

| Archivo | Para quién | Cómo está hecho |
|---|---|---|
| `hoja-de-vida.html` | Para una persona | Maquetación con jerarquía visual, fotografía y secciones diferenciadas |
| `hoja-de-vida-ATS.html` | Para un ATS | Una sola columna, texto plano, encabezados estándar, sin imágenes ni tablas |

Cada una tiene su PDF ya exportado:

- `Hoja de Vida - Jeferson Wilderman Gonzalez.pdf`
- `Hoja de Vida - Jeferson Wilderman Gonzalez ATS.pdf`

## Estructura

```
hoja-de-vida.html          versión para leer
hoja-de-vida-ATS.html      versión para el filtro automático
styles.css                 estilos compartidos
img/foto-perfil.jpg        fotografía
*.pdf                      las dos versiones ya exportadas
```

Es HTML y CSS sin dependencias: se abre con doble clic, sin compilar ni instalar
nada.

## Si quieres reutilizar la maquetación

Adelante — el código está bajo licencia MIT precisamente para eso. Toma el HTML
y el CSS y reemplaza el contenido por el tuyo.

Lo que **no** está cubierto por esa licencia son mis datos personales: la
fotografía, los PDF y la información de la hoja de vida. Están con todos los
derechos reservados. Ver [`LICENSE`](LICENSE).
