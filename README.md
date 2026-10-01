# WineSip Sales — Manual Comercial & Battlecard de Ventas

> **Sitio Web Interactivo para Representantes de Ventas y Agentes en Campo de WineSip**  
> Diseñado con estética **Dark Theme Luxury Noir & Glassmorphism**, acento morado `#434194`, tipografía Google Fonts (*Dancing Script*, *Poppins*, *Outfit*, *Plus Jakarta Sans*), simulador dinámico de ROI en mostrador y battlecard táctico de objeciones.

---

## 🚀 Despliegue en GitHub Pages (Pasos Rápidos)

Este proyecto está optimizado como sitio estático sin dependencias de compilación (`.nojekyll`, rutas relativas y fallback `404.html` incluidos).

### 1. Conectar con tu repositorio en GitHub
Crea un repositorio en [GitHub](https://github.com/new) (por ejemplo: `winesip-sales-guide` o `winesip-sales`) y corre en tu terminal:

```bash
git remote add origin https://github.com/<TU_USUARIO>/<TU_REPOSITORIO>.git
git push -u origin main
```

*(Si aún no has hecho commit local, corre: `git add . && git commit -m "feat: WineSip sales interactive web guide" && git branch -M main`)*

### 2. Activar GitHub Pages en el repositorio:
1. En GitHub, ve a **Settings** de tu repositorio.
2. En el menú lateral izquierdo, haz clic en **Pages**.
3. En **Build and deployment > Source**, selecciona **Deploy from a branch**.
4. En **Branch**, selecciona `main` y directorio `/ (root)`.
5. Haz clic en **Save**.
6. En 1 minuto tu sitio estará publicado y accesible en:
   ```
   https://<TU_USUARIO>.github.io/<TU_REPOSITORIO>/
   ```

---

## 🌟 Características de la Aplicación

1. **Simulador Interactivo de Retorno de Inversión (ROI):**
   - Deslizadores duales de visitas mensuales (1–25) y gasto promedio por visitante (\$20–\$250).
   - Cálculo en tiempo real de ingresos brutos, costo de suscripción, utilidad neta y porcentaje de ROI.
   - Botón directo para copiar el desglose preformateado para WhatsApp.

2. **Tipografía y Diseño de Alta Gama:**
   - Logotipo y monograma oficial WineSip.
   - Títulos de marca en Google Font **Dancing Script**.
   - Identificadores de sección en **Poppins** y **Outfit**.
   - Acento cromático primario morado `#434194` con halo sutil sobre fondo Obsidian Noir.

3. **Checklist & Temporizador de Pitch en 5 Minutos:**
   - Cronómetro háptico interactivo (inicio, pausa, reinicio con sonidos Web Audio).
   - Guión cronometrado minuto a minuto con frases preparadas listas para copiar.

4. **Buscador y Acordeón Táctico de Objeciones:**
   - Filtrado en vivo por texto y categoría (*Presupuesto*, *Operación*, *Marketing*).
   - Respuestas palabra por palabra para desarmar objeciones comunes del bodeguero.

5. **Matriz Comparativa vs. Alternativas del Mercado:**
   - Comparación detallada frente a Vivino, OpenTable, pauta en Instagram y folletería física.

---

## 📂 Estructura del Repositorio

```
winesip_sales_guide/
├── index.html       # Aplicación web completa y autónoma (markup, estilos y lógica JS)
├── logo.png         # Logotipo oficial WineSip
├── favicon.svg      # Favicon vectorial en copa de vino
├── 404.html         # Redirección de respaldo para rutas en GitHub Pages
├── .nojekyll        # Omite el procesamiento Jekyll de GitHub Pages
├── .gitignore       # Exclusión de archivos de sistema y temporales
└── README.md        # Guía del proyecto y documentación de despliegue
```
