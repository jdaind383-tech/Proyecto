# Guía de Uso por Plataforma / Platform Usage Guide

## 🎨 Stable Diffusion (Automatic1111 / ComfyUI)

### Configuración Recomendada / Recommended Settings:
```
Prompt: [Usar prompt de prompt_simple.txt / Use prompt from prompt_simple.txt]
Negative Prompt: [Usar negative de prompt_simple.txt / Use negative from prompt_simple.txt]

Sampling Steps: 30-50
Sampling Method: DPM++ 2M Karras o Euler A
CFG Scale: 7-9
Width: 512 o 768
Height: 768 o 1024
Seed: [Usar misma semilla de imagen referencia / Use same seed as reference image]
```

### Modelos Recomendados / Recommended Models:
- Realistic Vision V5.1
- DreamShaper
- Deliberate V2
- CyberRealistic

---

## 🖼️ Midjourney

### Formato del Prompt:
```
/imagine [prompt de prompt_simple.txt] --ar 3:4 --style raw --s 250 --v 6
```

### Parámetros / Parameters:
- `--ar 3:4` = Aspect ratio vertical
- `--style raw` = Estilo más fotorrealista
- `--s 250` = Stylization (ajustar entre 0-1000)
- `--v 6` = Versión 6 (la más reciente)

### Para mantener consistencia / To maintain consistency:
```
/imagine [prompt] --seed [número] --ar 3:4 --style raw --v 6
```

---

## 🎯 DALL-E 3 (ChatGPT / Bing)

### En ChatGPT:
```
"Genera una imagen con esta descripción: [prompt en español o inglés de prompt_simple.txt]"
```

### Consejos / Tips:
- DALL-E 3 es bueno entendiendo lenguaje natural
- Puedes ser más descriptivo y conversacional
- Si la primera imagen no es perfecta, pide ajustes específicos

---

## 🎪 Leonardo.ai

### Configuración / Settings:
```
Prompt: [prompt_simple.txt]
Negative Prompt: [negative de prompt_simple.txt]

Preset: Leonardo Diffusion XL o Leonardo Kino XL
Image Dimensions: 768x1024 (Portrait)
Number of Images: 4
Guidance Scale: 7
Tiling: Off
Public: Optional
```

### Herramientas Adicionales / Additional Tools:
- **Prompt Magic**: Activar para mejorar resultados
- **PhotoReal**: Para máximo realismo
- **Alchemy**: Para mayor calidad

---

## 🌟 Adobe Firefly

### Formato:
```
[Usar prompt en español de prompt_simple.txt]

Estilo: Foto
Efectos: Natural
Proporción: Vertical (3:4)
```

### Consejos / Tips:
- Firefly funciona muy bien con prompts en español
- Usa la función "Match Style" con tu imagen de referencia

---

## 🚀 Consejos Generales / General Tips

### Para Mantener Consistencia / To Maintain Consistency:
1. **Usa la misma semilla (seed)** en todos los intentos
2. **Guarda la imagen de referencia** para comparar
3. **Mantén los mismos parámetros** (CFG, steps, sampler)
4. **Usa el mismo modelo/versión** del generador

### Si la Imagen No es Perfecta / If Image Isn't Perfect:
1. **Ajusta el prompt** añadiendo más detalles específicos
2. **Cambia la semilla** ligeramente (+/- 1-5)
3. **Ajusta CFG Scale**: 
   - Más bajo (5-6) = más creativo
   - Más alto (9-10) = más adherencia al prompt
4. **Aumenta los steps** (50-75 para mayor calidad)

### Para Mejor Calidad / For Better Quality:
- ✅ Usa modelos actualizados
- ✅ Aumenta la resolución gradualmente (upscale después)
- ✅ Usa palabras clave como "professional photography", "high quality"
- ✅ Especifica iluminación: "natural light", "soft lighting"

---

## 🔧 Solución de Problemas / Troubleshooting

### Problema: La persona se ve diferente
**Solución**: 
- Añadir "same person as reference" o "consistent character"
- Usar funciones de "consistent character" si están disponibles
- Probar con img2img usando la primera imagen como referencia

### Problema: La ropa cambia
**Solución**:
- Ser más específico sobre la ropa: "wearing [describe exact clothes]"
- Usar menor variación en el seed

### Problema: La expresión no se ve natural
**Solución**:
- Añadir "candid photography", "spontaneous moment"
- Cambiar "smile" por "genuine smile", "natural smile"
- Probar con diferentes seeds

### Problema: Calidad baja o borrosa
**Solución**:
- Aumentar sampling steps a 50-75
- Usar upscaler después (Real-ESRGAN, LDSR)
- Cambiar a un modelo de mayor calidad

---

## 📝 Plantilla Rápida / Quick Template

Para copiar y pegar rápidamente / For quick copy-paste:

```
PROMPT POSITIVO:
[copiar de prompt_simple.txt línea 4 o 11]

PROMPT NEGATIVO:
[copiar de prompt_simple.txt línea 6 o 13]

PARÁMETROS:
Steps: 30-50
CFG: 7-9
Sampler: DPM++ 2M Karras
Size: 768x1024
Seed: [tu seed]
```
