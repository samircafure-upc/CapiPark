# Nelly's Splashdown

**Equipo:** 8 Ball Studios

Un juego Top-Down 2D desarrollado en Unreal Engine 5.4, utilizando el plugin PaperZD para la animación de sprites.

## 👥 Integrantes

*   Gino Stefano Bianchini
*   Samir Cafure
*   Pablo Guaymasi
*   Francisco Santiago Gutierrez

## 🛠️ Información Técnica

*   **Motor:** Unreal Engine 5.4
*   **Lenguaje:** Blueprints (Proyecto Blueprint-only)
*   **Plugins Principales:**
    *   **PaperZD:** Manejo de animaciones 2D y state machines.
    *   **ModelingToolsEditorMode:** Herramientas de modelado en editor.

## 📂 Estructura del Proyecto

El contenido principal del juego se encuentra organizado de la siguiente manera:

*   **`Content/Levels`**: Contiene los mapas del juego, incluyendo `Level1.umap` (Nivel Principal) y `BlankLevel.umap`.
*   **`Content/TopDown`**: Carpeta raíz para la lógica del juego.
    *   **`CharacterBP`**: Blueprints del personaje principal y enemigos.
    *   **`UI`**: Widgets e interfaz de usuario.
    *   **`Inputs`**: Configuraciones de Enhanced Input.
    *   **`BP_Gamemode`**: Lógica general del modo de juego.

## 🎮 Controles

El proyecto utiliza el sistema **Enhanced Input**. Las configuraciones de mapeo de teclas se encuentran en la carpeta `Content/TopDown/Inputs` y en `Config/DefaultInput.ini`.
