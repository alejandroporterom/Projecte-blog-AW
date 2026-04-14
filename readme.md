#  Projecte-blog-AW

Proyecto creado por **Aleix Puiggari y Alejandro Portero**

---

Descripcion del proyexto: 
Este proyecto es un blog de videojuegos hecho como práctica del módulo de aplicaciones web.

La idea es crear una web donde se pueda consultar información relacionada con el mundo gaming.

Funcionalidades:
- Navegación entre páginas
- Sección de registro de usuarios
- Estructura organizada con HTML y CSS


Estamos trabajando en la parte del registro. Este es un ejemplo del formulario:

```html
<div id="SeccionRegistro">
    <h2>Registro</h2>
    <form action="guardar.php" method="POST">
        <p>
            <label><b>Usuario:</b></label>
            <input type="text" name="user" required>
        </p>
        <button type="submit">Enviar</button>
    </form>
</div>