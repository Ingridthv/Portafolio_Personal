# Portafolio

**Nombre del proyecto:** Portafolio  
**Materia:** Programación Web  
**Actividad:** Actividad 4  
**Autor:** Ingrid Arcadio Aparicio

Portafolio web personal de una estudiante de Ingeniería en Sistemas Computacionales. Presenta quién soy, mi formación, mis habilidades y mis proyectos.

- **Sitio publicado:** https://ingridthv.github.io/Portafolio_Personal/
- **Repositorio:** https://github.com/Ingridthv/Portafolio_Personal

---

## 1. Descripción del proyecto

- **Framework CSS:** Bootstrap 5.3
- **Plantilla:** FolioOne (BootstrapMade)
- **Descarga de la plantilla:** https://bootstrapmade.com/folioone-bootstrap-portfolio-website-template/
- **Tecnologías:** HTML, CSS y JavaScript (sin React ni Vue)
- **Publicación:** GitHub Pages

### Menú y secciones

| Menú | Archivo | Qué contiene |
|---|---|---|
| Inicio | `index.html` | Bienvenida, mi nombre, foto de perfil y enlaces a mis redes. |
| Sobre mí | `about.html` | Presentación, línea de tiempo, pasatiempos y habilidades (HTML, CSS, JavaScript y Python). |
| Resumen | `resume.html` | Educación y habilidades profesionales. |
| Servicios | `services.html` | Áreas en las que trabajo o estoy aprendiendo. |
| Proyectos | `portfolio.html` | Galería con mis proyectos reales y planeados. |
| Contacto | `contact.html` | Datos de contacto, redes y formulario. |

---

## 2. Proceso de creación
 
Así armé el portafolio a partir de la plantilla, qué le modifiqué y por qué:
 
1. **Descargué la plantilla FolioOne** de BootstrapMade y la abrí en Visual Studio Code.
   *Por qué:* está hecha con Bootstrap y su diseño es limpio y profesional.
2. **Revisé la estructura:** cada página es un archivo `.html`, los estilos están en `assets/css/main.css` y las imágenes en `assets/img/`.
   *Por qué:* para saber qué archivo editar en cada sección.
3. **Quité el menú desplegable (dropdown)** de la barra de navegación en todas las páginas.
   *Por qué:* traía submenús de ejemplo que no necesito, y así el menú quedó simple, con seis opciones.
4. **Cambié el texto de ejemplo por mis datos** en Inicio, Sobre mí, Resumen, Servicios y Contacto: nombre, presentación, educación, habilidades y datos de contacto.
   *Por qué:* la plantilla trae texto de relleno (*lorem ipsum*) y datos de otra persona.
5. **Puse mi foto de perfil real** en lugar de la imagen de la plantilla.
   *Por qué:* el portafolio debe mostrar quién soy.
6. **Completé las habilidades y los proyectos** con lo que ya sé y con lo que quiero aprender y hacer.
   *Por qué:* la actividad pide que estas secciones no queden vacías, aunque algunos proyectos todavía sean planeados.
7. **Quité lo que no usaba:** testimonios, páginas de ejemplo y fotos de otras personas.
   *Por qué:* eran datos ficticios que no me representan.
8. **Traduje los textos al español** y revisé que los enlaces del menú funcionaran.
   *Por qué:* para que el sitio sea claro para quien lo lea y no tenga enlaces rotos.
9. **Subí el proyecto a GitHub** desde la terminal de VS Code:
```bash
   git init
   git add .
   git commit -m "Portafolio personal"
   git branch -M main
   git remote add origin https://github.com/Ingridthv/Portafolio_Personal.git
   git push -u origin main
   

---

## 3. Capturas de pantalla

### Inicio
![Inicio](assets/img/ima1.png)

### Sobre mí
![Sobre mí](assets/img/ima2.png)

### Resumen
![Resumen](assets/img/ima3.png)

### Servicios
![Servicios](assets/img/ima4.png)

### Proyectos
![Proyectos](assets/img/ima5.png)

### Contacto
![Contacto](assets/img/ima6.png)

---

Plantilla diseñada por [BootstrapMade](https://bootstrapmade.com/) ([Plantilla](https://bootstrapmade.com/folioone-bootstrap-portfolio-website-template/)).