# cicd-pipeline-python

Calculadora web hecha con Flask, con un pipeline de integración continua (GitHub Actions, SonarCloud y Docker Hub). Es el repositorio individual del Taller 2 de Integración y Entrega Continua de Software.

## Integrantes

Los nombres están en el mismo orden y con el mismo texto que la variable `AUTOR` de `app/calculadora.py`.

| Nombre completo | Usuario de GitHub | Rol |
|---|---|---|
| Santiago Alvarez | [SantiagoAlvP](https://github.com/SantiagoAlvP) | Propietario de este repositorio |
| Emmanuel Correa | [imKorr](https://github.com/imKorr) | Integrante |
| Tomás Echavarria | [tomechava](https://github.com/tomechava) | Integrante |
| José David Toro | [josedtf](https://github.com/josedtf) | Integrante |

## Ejecución local

```bash
python -m app.app   # http://localhost:5001
```

Se usa el puerto 5001 porque en macOS el 5000 lo ocupa AirPlay Receiver. Las pruebas de aceptación usan ese puerto por defecto; en el pipeline se apuntan al contenedor con `APP_BASE_URL=http://localhost:8000`.
