
## Paleta de colores

A continuación se detallan los colores aprobados para la interfaz, sus combinaciones y el cumplimiento del contraste de accesibilidad AA:

### Colores base
| Uso | Código hexadecimal | Descripción |
|---|---|---|
| Fondo claro | #F5F5F5 | Color base para fondos neutros |
| Fondo oscuro | #1E1E1E | Contraste para modo oscuro |
| Acento | #0078D4 | Azul institucional de la carrera |
| Texto principal | #333333 | Legible sobre fondo claro |
| Texto inverso | #FFFFFF | Legible sobre fondo oscuro |

### Combinaciones y contraste de accesibilidad
| Color de fondo | Color de texto | Relación de contraste | Cumple AA |
|---|---|---|---|
| #F5F5F5 | #000000 | ~19.5:1 | ✅ Sí |
| #0078D4 | #FFFFFF | ~4.15:1 | ⚠️ No |
| #005A9E | #FFFFFF | ~7.2:1 | ✅ Sí |
| #E5E5E5 | #111111 | ~12:1 | ✅ Sí |
| #D2E0F7 | #002050 | ~8.3:1 | ✅ Sí |

### Observación de verificación de contraste AA
- El color **`#0078D4`** sobre el fondo **`#F5F5F5`** da una relación de contraste de **aproximadamente 4.15:1**.
- Este valor **no cumple el criterio AA** para texto normal (mínimo requerido: 4.5:1).
- **Solución sugerida:** oscurecer el tono del color o usar negrita en el texto.
=
## Reglas para imágenes

Para mantener consistencia visual y accesibilidad, se aplican las siguientes reglas:

-  **Formato preferido:** SVG, por su escalabilidad y compatibilidad.
-  **Tamaño máximo:** 200 KB por archivo.
-  **Texto alternativo:** obligatorio en todas las imágenes.
-  **Recursos externos:** no se permiten dentro de los SVG.
-  **Versiones:** cada banner debe tener versión clara y oscura.
>

## Uso de emojis e íconos

Para mantener coherencia visual y accesibilidad, se aplican las siguientes reglas:

-  Usa **un emoji solo al inicio** de cada título de sección.
-  No coloques emojis en medio del texto o párrafos.
-  Los íconos deben ser simples y representar claramente su función.
-  Evita combinaciones excesivas de emojis o íconos en una misma línea.