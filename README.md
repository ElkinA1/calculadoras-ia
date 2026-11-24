# Calculadoras de Bolsillo

Sitio de calculadoras financieras gratis en español. Gana dinero con tres fuentes:
1. **Publicidad** (Google AdSense) cuando haya tráfico.
2. **Producto digital** "Kit Libre de Deudas" ($7–12) vendido en Gumroad o Hotmart. Ver `privado/kit-de-lanzamiento.md` (no se publica).
3. **Contenido** en TikTok, Reels y Shorts que lleva gente al sitio.

## Estructura
```
index.html          Página principal (lista de calculadoras)
deudas/index.html   Calculadora para salir de deudas
cuotas/index.html   Calculadora del costo real de comprar a cuotas
privado/            Kit, textos de venta y guiones (no se sube a internet)
```
Es HTML puro: no necesita servidor propio ni base de datos.

## Verlo en tu computador
```powershell
py -3.11 -m http.server 8765
```
Luego abre http://localhost:8765

## Publicarlo gratis 24/7 (sin dejar tu PC encendido)
Usa **Cloudflare Pages** o **GitHub Pages**. Ambos son gratis y el sitio queda en línea siempre.
1. Crea una cuenta en GitHub y sube esta carpeta como repositorio.
2. En Cloudflare Pages: "Create project" → conecta el repositorio → sin comando de build → Deploy.
3. Obtienes una dirección como `calculadoras-de-bolsillo.pages.dev`.
4. Opcional, cuando haya visitas: compra un dominio (~$10/año) y conéctalo.

## Plan de crecimiento
- **Semana 1:** publicar el sitio, subir el kit a Gumroad o Hotmart y grabar los primeros 7 videos.
- **Semanas 2–4:** agregar una calculadora nueva por semana (meta de ahorro, interés compuesto, presupuesto 50/30/20). Cada calculadora es una página más que Google puede mostrar.
- **Mes 2:** con contenido y algo de tráfico, solicitar Google AdSense y registrar el sitio en Google Search Console.

## Presupuesto
No hace falta gastar nada para empezar. Los $10 conviene guardarlos para el dominio cuando el sitio tenga visitas.
