# NutriHome PWA

Primera versión funcional de una aplicación móvil instalable desde el navegador para:

- planificar desayuno, comida, merienda y cena durante toda la semana;
- cambiar/aleatorizar platos compatibles con el perfil;
- consultar recetas con buscador, filtros por tiempo y momento del día;
- ver calorías, proteína, coste estimado, ingredientes y pasos;
- añadir e indexar recetas propias y guardar una URL de origen (incluido Instagram/web);
- controlar la despensa, cantidades y umbrales de reposición;
- generar una lista de compra descontando lo que ya existe en casa;
- añadir automáticamente productos con stock bajo;
- pasar una compra completada a la despensa;
- configurar objetivo de kcal/proteína y tipos de dieta (vegetariana, lacto, ovo, vegana, etc.);
- excluir huevo y/o lácteos;
- funcionar offline mediante Service Worker;
- instalarse como PWA en iPhone/Android.

## Ejecutar localmente

Como no requiere compilación, basta con servir la carpeta con un servidor estático:

```bash
python3 -m http.server 8080
```

Abrir `http://localhost:8080`.

## Publicar en GitHub Pages

1. Crear un repositorio nuevo.
2. Subir los archivos de esta carpeta a la rama `main`.
3. En **Settings → Pages**, seleccionar **Deploy from a branch** y `main / (root)`.
4. Abrir la URL de GitHub Pages desde el móvil y usar **Añadir a pantalla de inicio**.

## Próximas iteraciones previstas

- cuenta de usuario y sincronización entre dispositivos/familia;
- backend con Supabase/Firebase;
- IA para generar menús, sustituir platos y adaptar recetas a kcal/macros;
- importación automática de recetas desde URL/Instagram compatible con las condiciones de cada servicio;
- base de datos nutricional externa y códigos de barras;
- escalado por raciones y cálculo nutricional más preciso;
- presupuesto por supermercado y comparación de precios;
- favoritos, historial, valoraciones y recomendaciones;
- widgets/notificaciones y recordatorios de caducidad;
- lista compartida en tiempo real.
