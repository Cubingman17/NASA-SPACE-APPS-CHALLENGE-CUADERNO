# 🚀 Reglas del hackathon + Git/GitHub — 19 oct 2026

> **La idea en una frase:** _Primero saber a qué juego estamos jugando (reglas y entrega); el código sin publicar no existe._

## Cómo funciona el Space Apps
1. **Sáb 14 nov (mañana):** se liberan los retos oficiales → el equipo escoge UNO.
2. ~33 horas para explorar datos → construir solución → publicar en el sitio oficial.
3. Hora límite el domingo: **sin excepciones**, si no se publicó, no existe.

### Qué se entrega
| Entregable | Detalle |
|---|---|
| **Video** | máx. 2 min: problema → solución → impacto. Lo más importante, los jueces lo ven primero |
| **Descripción** | qué hace, cómo, qué datos usamos |
| **Código** | enlace al repo de GitHub del equipo |
| **Licencia** | Apache 2.0 (elegida por el equipo) |

### Reglas clave
- El proyecto debe responder a **un reto oficial 2026**.
- Todo debe ser **open source** (si no elegimos licencia, NASA lo pone en Apache 2.0).
- Menor de 18: inscripción por un acudiente desde SU cuenta + acompañante todo el evento (mi papá). En el video no mostrar mi cara/nombre.
- Equipo: **máximo 6**.
- Links: [2026](https://www.spaceappschallenge.org/2026/) · [legal](https://www.spaceappschallenge.org/legal/) · [recursos](https://www.spaceappschallenge.org/resources/) · [FAQ](https://www.spaceappschallenge.org/resources/participant-faqs/)

## Git/GitHub: el "guardar partida"
- **Git** = guarda versiones (checkpoints) en mi compu. **GitHub** = la nube donde el equipo las comparte.
- En Drive se guardan archivos sueltos; aquí se guarda la **historia completa** del proyecto.

### El ciclo (memorizarlo con el dibujo del cuaderno)
```bash
git clone <url>        # descargar el proyecto (1 vez)
git status             # qué cambié
git add .              # seleccionar cambios
git commit -m "mensaje" # checkpoint con mensaje claro
git push               # subir a GitHub
git pull               # bajar lo que subieron los demás
```

### Ramas
```bash
git switch -c feature-mapa   # crear rama para experimentar sin romper main
# ...trabajar, commit, push...
# Pull Request en la web → revisión → Merge
```

### Conflictos
Si dos editan la misma línea, Git marca `<<<<<<<` / `=======` / `>>>>>>>`. Se elige qué queda, se borran las flechitas, commit. Manual, sin miedo.

### Equivalencias GitHub Desktop
| Terminal | Desktop |
|---|---|
| `git status` | lista de cambios izquierda |
| `git commit -m` | caja de mensaje + "Commit to main" |
| `git push` | "Push origin" |
| `git pull` | "Pull origin" |
| `git switch -c` | Branch → New branch |

### Para el hackathon
- Repo del equipo creado ANTES, público, Apache 2.0, los 6 como colaboradores.
- Push en cada avance, no al final.
- README con: qué hace, cómo ejecutarlo, qué datos usa.

## ✅ Checklist del día 1 (completado)
- [x] Máx. 6 por equipo
- [x] Menor de 18 → acudiente inscribe + acompaña
- [x] Se entrega video + código + descripción + repo
- [x] Licencia Apache 2.0
