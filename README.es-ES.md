

<div align="center">

 # Starfighter Alliance – Proyecto de Software

<p align="center">
  <a href="/meta/readmes/README_DE.md">Deutsch</a> | 
  <a href="/meta/readmes/README_ES.md">Español</a> | 
  <a href="/meta/readmes/README_FR.md">Français</a>
</p>

Traducción respaldada por DeepL-AI! 

</div>

# 📖 Tabla de Contenidos

- [Starfighter Alliance – Software-Project](#starfighter-alliance--software-project)
- [📖 Tabla de Contenidos](#-table-of-contents)
- [🛠️ Lenguajes y Herramientas](#️-lenguajes-y-herramientas)
- [💻 Instalación](#instalación)
- [⚠️ Descargo de Responsabilidad](#️-descargo-de-responsabilidad)
- [🎯 Objetivos del Proyecto](#-objetivos-del-proyecto)
- [⚙️ Características del Juego](#️-características-del-juego)
- [🏗️ Estructura del Repositorio del Proyecto](#️-estructura-del-repositorio-del-proyecto)
- [📜 Licencia General](#-licencia-general)
- [⬇️ Recursos (Assets)](#️-recursos-assets)
- [🖼️ Capturas de Pantalla](#️capturas-de-pantalla)
  
# 🛠️ Lenguajes y Herramientas
<div style="display: flex; flex-direction: row; gap: 20px;">
<a href="https://daringfireball.net/projects/markdown/" target="_blank">
  <img align="left" alt="Markdown" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/markdown/markdown-original.svg" />
</a>
<a href="https://www.json.org/json-en.html" target="_blank">
  <img align="left" alt="JSON" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/json/json-original.svg" />
</a>
<a href="https://godotengine.org/" target="_blank">
  <img align="left" alt="Godot" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/godot/godot-original.svg" />
</a>
<a href="https://learn.microsoft.com/en-us/dotnet/csharp/" target="_blank">
  <img align="left" alt="C#" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/csharp/csharp-original.svg" />
</a>
<a href="https://git-scm.com/" target="_blank">
  <img align="left" alt="Git" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg" />
</a>
<a href="https://about.gitlab.com/" target="_blank">
  <img align="left" alt="GitLab" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/gitlab/gitlab-original.svg" />
</a>
<a href="https://www.microsoft.com/en-us/windows/" target="_blank">
  <img align="left" alt="Windows" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/windows11/windows11-original.svg" />
</a>
<a href="https://code.visualstudio.com/" target="_blank">
  <img align="left" alt="VSCode" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vscode/vscode-original.svg" />
</a>
<a href="https://www.latex-project.org/" target="_blank">
  <img align="left" alt="Latex" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/latex/latex-original.svg" />
</a>
<a href="https://moodle.uni-ulm.de/course/view.php?id=54123" target="_blank">
  <img align="left" alt="Moodle" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/moodle/moodle-original.svg" />
</a>
<a href="https://www.uml-diagrams.org/" target="_blank">
  <img align="left" alt="UML" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/unifiedmodelinglanguage/unifiedmodelinglanguage-original.svg" />
</a>

</div>
<br />

# 💻 Instalación
Descarga el ejecutable desde la pestaña de Releases o:
1. **Clona el repositorio:**
   ```bash
   git clone https://github.com/alhasan-ramadan/starfighter-alliance.git
   ```

2. **Abre el proyecto de Godot:**
   - Inicia Godot y selecciona la opción "Import Project".
   - Navega hasta la carpeta del repositorio clonado y selecciona el archivo `project.godot`.

3. **Ejecuta el proyecto:**
   - Presiona F5 o haz clic en "Start Project" para lanzar el archivo.

# ⚠️ Descargo de Responsabilidad

>[!NOTE]
>- Este proyecto aún se encuentra en desarrollo **activo**.
>- Es probable que haya errores y cambios importantes.
>- **Este proyecto se proporciona "tal cual".**  

> [!WARNING]
> El juego se conecta automáticamente a un [servidor configurado](https://softwaregrund.pro/jekt/) de la Universidad de Ulm al iniciar. La conexión se realiza a través de la clase `WebSocketPeer` en Godot.

>[!IMPORTANT]        
> El juego está configurado para una relación de aspecto de 16:9 (1920x1080).

---



# 🎯 Objetivos del Proyecto
<img src="https://media.giphy.com/media/yEIyJ1WCnGKRi/giphy.gif" alt="GIF Title" width="250">

Los objetivos del proyecto *Starfighter Alliance* son:

1. **Desarrollo de un juego de vuelo infinito**
2. **Implementación de mecánicas de juego**:
   - Control de la nave espacial, que puede moverse en todas las direcciones.
   - Generación y visualización de olas de meteoritos.
   - Detección de colisiones y reacción a las mismas (por ejemplo, fin del juego).
   - Ajuste de la velocidad del juego para aumentar progresivamente el desafío.
3. **Creación de documentación clara y completa**
4. **Pruebas y garantía de calidad del juego**
5. **Aprendizaje y aplicación de Scrum**  
   


# ⚙️ Características del Juego
1. **Inicio del juego**
   - El juego puede iniciarse desde la pantalla de inicio.

2. **Opciones del juego**
   - El jugador puede personalizar el juego mediante un pequeño número de opciones.

3. **Selección de una nave espacial**
   - Los jugadores pueden seleccionar una nave espacial de una lista.
   - Antes de la selección, se muestran los valores específicos de la nave (por ejemplo, velocidad, puntos de vida).

4. **Elección de color para la nave espacial**
   - Los jugadores tienen la opción de activar un color aleatorio seleccionado por un servidor.
   - Esta opción puede activarse o desactivarse antes de iniciar el juego.

5. **Juego principal**
   - El jugador puede mover la nave espacial en todas las direcciones usando w,a,s,d o las teclas de flecha.
   - Con la barra espaciadora es posible disparar para destruir obstáculos.
6. **Pausa**
   - Es posible pausar el juego desde la pantalla de juego.
7. **Puntuación más alta (High Score)**
   - Al finalizar cada ronda, se carga un top 10 de puntuaciones más altas utilizando un archivo de guardado.


# 🏗️ Estructura del Repositorio del Proyecto
- **images**: Imágenes del repositorio que se utilizan para el ReadMe, por ejemplo.
- **meta**: Otros archivos ReadMe en diferentes idiomas y los cambios en el [ChangeLog](CHANGELOG.md).
- **starfighter-alliance**: El proyecto real con todo el código en Godot, editable directamente en el motor. Además, se proporciona una aplicación con la que puedes jugar.

# 📜 Licencia General
Este proyecto está licenciado bajo la Licencia Apache 2.0. Consulta el archivo [Licencia](http://www.apache.org/licenses/LICENSE-2.0) en línea o en [Proyecto](LICENCE.md) para más detalles.

# ⬇️ Recursos (Assets)
1. https://deep-fold.itch.io/space-background-generator
2. https://deep-fold.itch.io/pixel-planet-generator
3. https://godotshaders.com/shader/shine/
4. https://godotshaders.com/shader/pulse-effect-godot-4/
5. https://godotshaders.com/shader/radial-plasma-shield/
6. https://pixabay.com/sound-effects/search/laser/
7. https://pixabay.com/sound-effects/search/explosion/?pagi=2
8. https://pixabay.com/music/search/space/
9. https://www.dafont.com/star-jedi.font


# 🖼️ Capturas de Pantalla
![alt text](<images/Read.me_Assets/Screenshot 2024-12-23 021136.png>)
![alt text](<images/Read.me_Assets/Screenshot 2024-12-23 021148.png>)
![alt text](<images/Read.me_Assets/Screenshot 2024-12-23 021157.png>)
![alt text](<images/Read.me_Assets/Screenshot 2024-12-23 021222.png>)
![alt text](<images/Read.me_Assets/Screenshot 2024-12-23 021239.png>)
![alt text](<images/Read.me_Assets/Screenshot 2024-12-23 021255.png>)
