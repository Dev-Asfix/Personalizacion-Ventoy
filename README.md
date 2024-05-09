# Tema Personalizado para Ventoy

Este repositorio contiene un tema personalizado para Ventoy, una herramienta para crear unidades USB de arranque múltiple. Este tema personalizado cambia la apariencia y el estilo de Ventoy cuando se ejecuta desde una unidad USB.

## Uso del Tema

Para usar este tema personalizado en Ventoy, sigue estos pasos:

1. **Descarga el Tema**: Clona o descarga este repositorio en tu computadora.

2. **Copiar el Tema a la Unidad USB**: Copia la carpeta del tema (`<nombre-de-tu-tema>`) dentro de la carpeta `themes` en la raíz de tu unidad USB Ventoy. Si la carpeta `themes` no existe, créala.

3. **Configurar Ventoy para Usar el Tema**: Abre el archivo `ventoy.json` en la raíz de tu unidad USB Ventoy y busca la sección `theme` dentro de este archivo. Asegúrate de que el valor de `theme` coincida con el nombre de la carpeta del tema que copiaste en el paso anterior.

   Por ejemplo, si la carpeta del tema se llama `my-theme`, la sección `theme` en `ventoy.json` debería verse así:

   ```json
   {
     "theme": "my-theme"
   }
