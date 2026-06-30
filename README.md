# Test de Alcoholemia Web — TP de Química

Una aplicación web interactiva que calcula la tasa de alcoholemia en sangre de forma personalizada, utilizando fórmulas científicas y mediciones reales basadas en variables corporales y de consumo.

## Características Principales

* **Carga Personalizada de Consumo:** Registro de cantidad (tamaño de vasos) y tipo de bebida alcohólica (graduación).
* **Dinámica Temporal:** Incorpora el tiempo transcurrido desde la ingesta para calcular la curva de alcoholemia.
* **Variables Biométricas:** Cálculos precisos adaptados al peso, altura, sexo biológico y tipo de cuerpo del usuario.
* **Base Científica:** Algoritmo basado en fórmulas químicas y de fluidos corporales reales (fórmula de Widmark / Watson).
* **Tiempo de Bajada:** Una recta que muestra cuantas horas tardara hasta que desaparezca el alcohol en sangre

## Fundamento Químico y Científico

El cálculo no es una estimación genérica; se rige por principios químicos de absorción y metabolismo:

1. **Gramos de Alcohol Puro:** Calculados mediante el volumen consumido y la densidad del etanol ($0.8 \text{ g/ml}$).
2. **Factor de Distribución ($r$):** Determinado científicamente por el sexo, peso y la composición corporal (agua corporal total).
3. **Tasa de Eliminación:** El metabolismo hepático reduce los niveles a un ritmo constante promedio de $0.15 \text{ g/L}$ por hora.

$$\text{Alcoholemia} = \frac{\text{Gramos de alcohol consumidos}}{\text{Peso corporal (kg)} \times r} - (\text{Factor de eliminación} \times \text{Tiempo})$$

## Tecnologías Utilizadas

* **Frontend:** HTML5, CSS3 (diseño responsivo) y JavaScript (Vanilla o especificar framework).
* **Backend:** Supabase y Vercel (Para Deployment y base de datos para usuarios y registro de nivel de alcohol en sangre
* **Cálculos:** Motor lógico en JavaScript para el procesamiento matemático de las variables químicas.

## Instalación y Uso

1. Clona este repositorio:
   ```bash
   git clone https://github.com
   ```
2. Abre el archivo `index.html` en tu navegador web o levanta un servidor local.

## Integrantes

* **SImon Flomenboim**
* **Noah Ariel Marabi** 
* **Luciano Ivan Roitman** 

---
*⚠️ **Descargo de responsabilidad:** Este proyecto es estrictamente educativo para la materia de Química. No debe utilizarse como un sustituto de un alcoholímetro oficial ni para determinar la capacidad real de conducir.*
