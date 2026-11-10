# Proyecto de Derivados Financieros — Equipo 3

Repositorio del Equipo 3 para reunir las actividades de la materia y documentar la evolución del proyecto final.

## Actividades de la materia

### Actividad 2 — Estructuras básicas de opciones
[Ver archivos de la actividad](actividades/actividad-2/)

Se analizaron dos estrategias: un **Bull Call Spread** sobre futuros de WTI y un **Protective Put** sobre AAPL. Se calcularon los resultados al vencimiento, primas netas, puntos de equilibrio y límites de ganancia o pérdida, y se representaron los perfiles de P&L.

### Actividad 3 — Griegas y estrategias con AAPL y GLW
[Ver archivos de la actividad](actividades/actividad-3/)

Se aplicaron cinco estrategias —Covered Call, Collar, Bear Put Spread, Bear Call Spread y Long Strangle— tanto a GLW como a AAPL. Para cada una se analizaron primas, griegas, valuación teórica y resultados bajo distintos precios al vencimiento. Se conservaron los reportes y las capturas de las plataformas consultadas.

### Actividad 4 — Ejercicios de la Sección 21 y opciones
[Ver archivos de la actividad](actividades/actividad-4/)

Se resolvieron los ejercicios 21.2 y 21.4 con árboles binomiales CRR: una put americana sobre una acción y una call americana sobre futuros de maíz. También se preparó una réplica tipo Bloomberg para opciones de VRT, con valuación y griegas de una estrategia, escenarios de P&L, matrices por vencimiento y métricas de open interest, gamma, max pain y ratios put/call.

### Actividad 5 — Árboles binomiales, portafolio y cobertura
[Ver archivos de la actividad](actividades/actividad-5/)

Se trabajó con precios históricos de AAPL y GLW para estudiar retornos, riesgo y asignación de portafolio. La práctica incluye simulaciones Monte Carlo, análisis de volatilidad y VaR, y cobertura con opciones europeas y americanas valoradas mediante árboles binomiales.

### Actividad 6 — Volatilidad GARCH aplicada a AAPL
[Ver archivos de la actividad](actividades/actividad-6/)

Se incorporó un modelo GARCH(1,1) a la valuación del bono convertible sintético de AAPL. El análisis compara estimaciones de volatilidad histórica, EWMA y GARCH; genera pronósticos y escenarios Monte Carlo; revisa VaR y backtesting; y utiliza la volatilidad estimada para valorar la opción de conversión y explorar estrategias de opciones.

## Evolución del proyecto final — Bono convertible sintético de AAPL

### Avance 1 — Valuación y estructura del convertible
[Ver archivos del avance](proyecto-final/avances/avance-1/)

Como Apple no tiene un bono convertible en circulación, se tomó un bono straight de Apple como referencia para construir un convertible sintético a seis años. El avance adapta el caso Molson Coors: valúa la opción de conversión con Black-Scholes, estima el cupón que llevaría el instrumento a la par, analiza sensibilidades a la prima de conversión y la volatilidad, y estudia un call spread como cobertura. Los resultados se organizan en un dashboard con datos del bono y contexto de la empresa.

### Continuación — Incorporación de GARCH en la Actividad 6

La Actividad 6 extiende el primer avance al estimar la volatilidad de AAPL con datos de cinco años y comparar modelos con criterios estadísticos. La volatilidad pronosticada se integra en la opción de conversión, que también se estudia con un árbol CRR para ejercicio americano y con simulación Monte Carlo. El dashboard y los archivos de la continuación están en [actividades/actividad-6](actividades/actividad-6/).

### Versión integradora agregada por el equipo

El equipo añadió una versión consolidada del proyecto en la carpeta del [Avance 1](proyecto-final/avances/avance-1/). Estos archivos amplían el análisis del convertible con GARCH y reúnen el cierre de las actividades relacionadas:

- [Notebook integrador](proyecto-final/avances/avance-1/PROYECTO_FINAL_DERIVATIVES.ipynb): incluye valuación del convertible, volatilidad GARCH, simulaciones, riesgo de portafolio AAPL–GLW, estrategias con opciones y swaps, y el seguimiento/cierre del simulador Investopedia.
- [Dashboard del convertible AAPL con GARCH](proyecto-final/avances/avance-1/AAPL_Convertible_GARCH_Dashboard.html): presentación interactiva de los resultados principales.
- [Exportación HTML del notebook](proyecto-final/avances/avance-1/PROYECTO_FINAL_DERIVATIVES_codigo.html): reporte con el código y los resultados del análisis.

## Organización

Cada carpeta contiene, cuando están disponibles, los archivos fuente (R Markdown o notebooks), sus resultados exportados (HTML/PDF) y materiales de apoyo. En esta copia pública se sustituyeron las matrículas encontradas por [MATRICULA REDACTADA].
