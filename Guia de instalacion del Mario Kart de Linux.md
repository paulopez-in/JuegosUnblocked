# 🏎️ Guía de instalación de SuperTuxKart (Mario Kart de Linux)

Guía paso a paso para ejecutar el juego en Linux (LliureX) de forma portable y sin permisos de administrador (`sudo`).

---

## 🚀 Método Principal (Nativo de Linux)

1. **Descargar el juego:**
   Descarga el archivo del juego (`.tar.gz`) y colócalo en una carpeta dedicada.

2. **Extraer el contenido:**
   Una vez descargado, ve a la carpeta del juego y extráelo donde prefieras.

3. **Dar permisos de ejecución:**
   Asegúrate de que el archivo ejecutor (en este caso `run_game.sh`) tenga permisos de ejecución.
   * **Desde la interfaz gráfica:** Haz clic derecho sobre `run_game.sh` -> **Propiedades** y marca la casilla **"És executable"** (Es ejecutable).
   * **Desde la terminal:**
     ```bash
     chmod +x run_game.sh
     ```

   <!-- Pega o arrastra aquí la captura de las propiedades del archivo -->
   *(Arrastra aquí la imagen de los permisos de ejecución)*

4. **Ejecutar el juego:**
   Una vez dentro de la carpeta extraída, ejecuta el juego haciendo doble clic sobre el archivo `run_game.sh`.

---

## 🛠️ ¿Qué hacer si no funciona el doble clic?

### Opción A: Ejecutar desde la terminal (Recomendado)

Abre la terminal, navega hasta la carpeta del juego y ejecuta el script manualmente:

```bash
cd ~/emu/TuxKart
./run_game.sh
