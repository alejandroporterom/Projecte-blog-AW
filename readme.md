# Projecte-blog-AW
Projecte creat per Aleix Puiggari i Alejandro Portero
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>README - Blog de Videojuegos</title>
    <style>
        body { font-family: sans-serif; line-height: 1.6; color: #333; max-width: 800px; margin: auto; padding: 20px; }
        header { border-bottom: 2px solid #eee; padding-bottom: 20px; }
        code { background-color: #f4f4f4; padding: 2px 5px; border-radius: 3px; font-family: monospace; }
        pre { background: #272822; color: #f8f8f2; padding: 15px; overflow-x: auto; border-radius: 5px; }
        .tag { color: #a6e22e; }
        .attr { color: #f92672; }
        hr { border: 0; border-top: 1px solid #eee; margin: 40px 0; }
    </style>
</head>
<body>

<header>
        <h1>Proyecto Blog de Videojuegos</h1>
        <p><strong>Autores:</strong> Aleix y Alejandro</p>
        <p>Un espacio dedicado a nuestra pasión por los videojuegos y el desarrollo web.</p>
    </header>

<section>
        <h2>Descripción del Proyecto</h2>
        <p>Este proyecto es un blog interactivo desarrollado como parte del módulo de aplicaciones web. El objetivo es crear una plataforma donde los usuarios puedan informarse sobre novedades del mundo gaming.</p>
        <p><strong>Funcionalidades principales:</strong></p>
        <ul>
            <li>Navegación intuitiva entre secciones de información y contacto.</li>
            <li>Sistema de registro de usuarios mediante formularios HTML.</li>
            <li>Estructura organizada de archivos y hojas de estilo CSS.</li>
        </ul>
    </section>

<hr>

<section>
        <h2>Capturas y Fragmentos de Código</h2>
        <p>Actualmente, estamos trabajando fuertemente en la sección de <strong>Registro</strong>. Aquí un ejemplo de cómo estructuramos el formulario:</p>
        
<pre>
&lt;!-- Estructura de Registro en register.html --&gt;
&lt;div id="SeccionRegistro"&gt;
    &lt;h2&gt;Registro&lt;/h2&gt;
    &lt;form action="guardar.php" method="POST"&gt;
        &lt;p&gt;
            &lt;label&gt;&lt;b&gt;Usuario:&lt;/b&gt;&lt;/label&gt;
            &lt;input type="text" name="user" required&gt;
        &lt;/p&gt;
        &lt;button type="submit"&gt;Enviar&lt;/button&gt;
    &lt;/form&gt;
&lt;/div&gt;
</pre>
</section>

<section>
        <h2>Tecnologías Utilizadas</h2>
        <table border="1" cellpadding="10" style="border-collapse: collapse; width: 100%;">
            <thead>
                <tr style="background-color: #f9f9f9;">
                    <th>Tecnología</th>
                    <th>Uso en el proyecto</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td><strong>HTML5</strong></td>
                    <td>Estructura semántica del contenido.</td>
                </tr>
                <tr>
                    <td><strong>CSS3</strong></td>
                    <td>Diseño visual y maquetación de las páginas.</td>
                </tr>
                <tr>
                    <td><strong>VS Code</strong></td>
                    <td>Entorno de desarrollo principal.</td>
                </tr>
            </tbody>
        </table>
    </section>

<hr>

<section>
        <h2>Estructura del Proyecto</h2>
        <p>Mantenemos una jerarquía clara para facilitar la escalabilidad:</p>
        <pre>
Projecte-AW/
├── html/          # Archivos .html (about, contact, register, etc.)
├── CSS/           # Hoja de estilos (style.css)
├── img/           # Imágenes y recursos gráficos (GIFs de construcción)
└── index.html     # Punto de entrada principal</pre>
    </section>

<section>
        <h2>Instalación y Uso</h2>
        <ol>
            <li>Descarga o clona el repositorio en tu ordenador.</li>
            <li>Asegúrate de mantener la estructura de carpetas intacta para que los enlaces internos funcionen.</li>
            <li>Abre el archivo <code>index.html</code> en tu navegador favorito.</li>
        </ol>
    </section>

<hr>

<footer>
        <h2>Roadmap y Futuro</h2>
        <ul>
            <li>Maquetación básica finalizada.</li>
            <li>Validación de formularios con JavaScript.</li>
            <li>Implementación de base de datos para usuarios reales.</li>
        </ul>
        <p><em>Este proyecto se distribuye bajo la licencia MIT.</em></p>
    </footer>

</body>
</html>