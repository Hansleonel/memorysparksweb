# Cambios Aplicados a las Políticas de Privacidad

**Fecha:** 29 de enero de 2026  
**Basado en:** Respuestas del desarrollador

---

## ✅ Cambios Realizados

### 1. **Fechas Actualizadas**
- ✅ `privacy.html`: Effective Date: January 29, 2026
- ✅ `privacy-es.html`: Fecha de Vigencia: 29 de enero de 2026
- ✅ `terms.html`: Effective Date: January 29, 2026
- ✅ Versión actualizada a 2.1 (Updated for App Store submission)

### 2. **Enfoque Geográfico Actualizado**

#### Antes:
```
"MemorySparks is operated from Peru and uses third-party services 
that may store data in various locations worldwide"
```

#### Después:
```
"MemorySparks is operated from Peru and primarily serves users 
in the United States and Latin America"
```

**Razón:** Aclarar que NO lanzarás en Europa por ahora.

### 3. **Ubicación de Servidores Especificada**

#### Antes:
- Supabase: "May store data in US, EU, or other regions"
- Google Gemini: "Processes data on Google's global infrastructure"

#### Después:
- Supabase: "Stores data in US regions"
- Google Gemini: "Processes data on Google's US infrastructure"

**Razón:** Ser más específico sobre dónde están los datos (USA).

### 4. **Nota sobre Europa Agregada**

**Nuevo texto agregado:**
```
Note: This app is currently not available in the European Union. 
If we expand to EU markets in the future, we will implement 
appropriate data transfer safeguards including Standard Contractual 
Clauses (SCCs) and GDPR compliance measures.
```

**Razón:** Dejar claro que NO estás en Europa y evitar confusión sobre GDPR.

### 5. **Sección GDPR Actualizada**

#### Antes:
```
If you are in the EU, you have additional rights under GDPR:
[lista completa de derechos]
```

#### Después:
```
Note: MemorySparks is currently not available in the European Union. 
This section is provided for informational purposes only.

If we expand to EU markets in the future, EU residents will have 
additional rights under GDPR including:
[lista simplificada]
```

**Razón:** No dar la impresión de que estás operando en Europa.

### 6. **Medidas de Protección Actualizadas**

#### Antes:
- Standard Contractual Clauses (SCCs) approved by the European Commission
- Compliance with local data protection laws (GDPR, CCPA, LGPD)

#### Después:
- Compliance with US data protection laws (CCPA)
- Compliance with Latin American data protection laws (LGPD for Brazil)
- Third-party processors with adequate data protection measures
- Encrypted data transmission and storage

**Razón:** Enfocarse en las leyes relevantes para tus mercados (USA y LATAM).

---

## 📋 Contenido que YA Estaba Correcto (No Cambió)

### ✅ Edad de Usuarios
- **Política dice:** "13 years and older"
- **Tu respuesta:** Mayores de 13 ✅ CORRECTO

### ✅ Almacenamiento de Datos
- **Política dice:** Datos de cuenta en Supabase, historias en dispositivo local
- **Tu respuesta:** Sí guardas en Supabase (perfil, auth) ✅ CORRECTO

### ✅ Uso de IA
- **Política dice:** "Memory text and images are sent to Google Gemini AI"
- **Tu respuesta:** Sí usas Gemini para generar historias ✅ CORRECTO

### ✅ Entrenamiento de Modelos
- **Política dice:** No menciona entrenamiento (solo generación)
- **Tu respuesta:** No se usan para entrenar otros modelos ✅ CORRECTO

### ✅ Venta de Datos
- **Política dice:** "WE DO NOT SELL YOUR PERSONAL INFORMATION TO ANYONE"
- **Tu respuesta:** No se comparten datos ✅ CORRECTO

### ✅ Retención de Datos
- **Política dice:** 30 días después de eliminación de cuenta
- **Tu respuesta:** No se guardan historias (solo local) ✅ CORRECTO

### ✅ Voice Cloning
- **Política dice:** Mencionado como característica futura
- **Tu respuesta:** Más adelante ✅ CORRECTO

---

## 📊 Resumen de Cambios

| Sección | Cambio | Razón |
|---------|--------|-------|
| Fechas | Actualizadas a Jan 29, 2026 | Reflejar fecha actual |
| Región Geográfica | "Primarily serves US and Latin America" | Aclarar mercados objetivo |
| Servidores | "US regions" en lugar de "US, EU, or other" | Ser específico sobre ubicación |
| Europa | Nota agregada: "Not available in EU" | Evitar confusión sobre GDPR |
| GDPR | Marcado como "informational purposes only" | No operas en Europa |
| Protección de Datos | Enfoque en CCPA y LGPD, no GDPR | Leyes relevantes para tus mercados |

---

## ✅ Archivos Actualizados

1. ✅ `/Users/hans/Downloads/MemorySparksWeb/privacy.html`
2. ✅ `/Users/hans/Downloads/MemorySparksWeb/privacy-es.html`
3. ✅ `/Users/hans/Downloads/MemorySparksWeb/terms.html`
4. ✅ `/Users/hans/Downloads/storysparks/lib/l10n/app_en.arb` (URLs agregadas)
5. ✅ `/Users/hans/Downloads/storysparks/lib/l10n/app_es.arb` (URLs agregadas)

---

## 🚀 Próximos Pasos

1. **Subir al sitio web:**
   ```bash
   cd /Users/hans/Downloads/MemorySparksWeb
   git add .
   git commit -m "Update privacy policies: focus on US/LATAM markets (Jan 2026)"
   git push origin main
   ```

2. **Verificar URLs:**
   - https://memorysparks.app/privacy.html
   - https://memorysparks.app/privacy-es.html
   - https://memorysparks.app/terms.html

3. **Usar en App Store Connect:**
   - Privacy Policy URL: `https://memorysparks.app/privacy.html`
   - Seguir guía en `APP_STORE_PRIVACY_GUIDE.md`

---

## 🎯 Ventajas de Estos Cambios

1. **Más Claro para Apple:** No hay confusión sobre si operas en Europa
2. **Menos Requisitos Legales:** No necesitas cumplir GDPR inmediatamente
3. **Enfoque en Mercados Objetivo:** USA y LATAM claramente definidos
4. **Más Fácil de Mantener:** No necesitas representante de GDPR en EU
5. **Preparado para Futuro:** Si expandes a Europa, ya tienes la base

---

**Todos los cambios aplicados. Listo para App Store submission! 🚀**
