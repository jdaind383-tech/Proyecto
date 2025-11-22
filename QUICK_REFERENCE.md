# 📋 TARJETA DE REFERENCIA RÁPIDA / QUICK REFERENCE CARD

## 🎯 PROMPT OPTIMIZADO (Para Copiar y Pegar)

### ESPAÑOL 🇪🇸
```
Fotografía profesional de una mujer joven sosteniendo una bocina cerca de su cuerpo, completamente feliz con sonrisa auténtica y natural que ilumina sus ojos, misma persona que en imagen de referencia, misma ropa y vestimenta, misma posición corporal y pose, expresión espontánea y genuina, iluminación suave y natural, alta calidad fotográfica, retrato realista, tonos cálidos

Negative: borroso, baja calidad, persona diferente, ropa diferente, sonrisa artificial, expresión forzada, triste, serio
```

### ENGLISH 🇺🇸
```
Professional photograph of a young woman holding a speaker close to her body, completely happy with authentic natural smile that lights up her eyes, same person as reference image, same clothes and outfit, same body position and pose, spontaneous genuine expression, soft natural lighting, high photographic quality, realistic portrait, warm tones

Negative: blurry, low quality, different person, different clothes, artificial smile, forced expression, sad, serious
```

---

## ⚙️ PARÁMETROS RECOMENDADOS / RECOMMENDED SETTINGS

| Parámetro | Valor Recomendado |
|-----------|-------------------|
| **Steps** | 30-50 |
| **CFG Scale** | 7-9 |
| **Sampler** | DPM++ 2M Karras o Euler A |
| **Resolución** | 768x1024 (vertical) |
| **Seed** | Mismo que imagen referencia |

---

## ✅ CHECKLIST DE CONSISTENCIA / CONSISTENCY CHECKLIST

Antes de generar, verificar / Before generating, verify:
- [ ] ¿Usé la misma seed? / Using same seed?
- [ ] ¿Especifiqué "misma persona"? / Specified "same person"?
- [ ] ¿Especifiqué "misma ropa"? / Specified "same clothes"?
- [ ] ¿Especifiqué "misma posición"? / Specified "same position"?
- [ ] ¿Incluí prompt negativo? / Included negative prompt?
- [ ] ¿Parámetros correctos? / Correct parameters?

---

## 🔧 AJUSTES RÁPIDOS / QUICK ADJUSTMENTS

### Si necesitas más creatividad / If you need more creativity:
- Reducir CFG a 5-6
- Cambiar seed ligeramente

### Si necesitas más adherencia al prompt / If you need more prompt adherence:
- Aumentar CFG a 9-10
- Mantener seed fija

### Si la calidad es baja / If quality is low:
- Aumentar steps a 50-75
- Usar upscaler después

---

## 🎨 PLATAFORMAS / PLATFORMS

### Stable Diffusion
```
[Prompt] + Settings (30-50 steps, CFG 7-9, DPM++ 2M Karras)
```

### Midjourney
```
/imagine [prompt] --ar 3:4 --style raw --s 250 --v 6
```

### DALL-E 3
```
"Genera una imagen: [prompt]"
```

### Leonardo.ai
```
[Prompt] + Leonardo Kino XL + PhotoReal + Alchemy
```

---

## 🆘 PROBLEMAS COMUNES / COMMON PROBLEMS

| Problema | Solución |
|----------|----------|
| Persona diferente | Añadir "same person as reference" |
| Ropa diferente | Describir ropa específicamente |
| Expresión no natural | Añadir "candid", "spontaneous" |
| Baja calidad | Aumentar steps, usar upscaler |

---

## 💡 PALABRAS CLAVE IMPORTANTES / IMPORTANT KEYWORDS

✅ **Usar / Use:**
- Natural, auténtica, genuina / Natural, authentic, genuine
- Profesional, alta calidad / Professional, high quality
- Espontánea, candid / Spontaneous, candid
- Misma persona/ropa/posición / Same person/clothes/position

❌ **Evitar / Avoid:**
- Artificial, forzada / Artificial, forced
- Baja calidad / Low quality
- Genérica / Generic
- Diferente / Different

---

## 📐 RATIOS DE ASPECTO / ASPECT RATIOS

| Uso | Ratio | Dimensiones |
|-----|-------|-------------|
| **Retrato vertical** | 3:4 | 768x1024 |
| Retrato | 2:3 | 512x768 |
| Cuadrado | 1:1 | 1024x1024 |
| Horizontal | 16:9 | 1024x576 |

**Recomendado para este proyecto**: 3:4 (768x1024) - Retrato vertical

---

## 🎯 VERSIÓN ULTRA CORTA (Para Espacio Limitado)

**ES:** Mujer joven feliz sosteniendo bocina, sonrisa natural auténtica, misma persona, misma ropa, misma pose, fotografía profesional realista

**EN:** Young woman happily holding speaker, authentic natural smile, same person, same clothes, same pose, professional realistic photography

---

## 📞 RECURSOS ADICIONALES / ADDITIONAL RESOURCES

- **Guía completa**: Ver `optimized_prompt.md`
- **Comparación**: Ver `COMPARISON.md`
- **Guía por plataforma**: Ver `USAGE_GUIDE.md`
- **Documentación**: Ver `README.md`

---

## 🌟 TIPS FINALES / FINAL TIPS

1. **Paciencia**: 2-3 intentos suelen ser suficientes
2. **Documenta**: Guarda los parámetros que funcionan
3. **Itera**: Ajusta progresivamente si es necesario
4. **Compara**: Usa la referencia para validar consistencia

---

**🎉 ¡Listo para generar imágenes increíbles! / Ready to generate amazing images!**

_Última actualización / Last update: 2025-11-22_
