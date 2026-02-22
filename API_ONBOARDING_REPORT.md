# Informe de Onboarding de API

## Resumen de la API

- **Nombre de la API:** TheCatAPI  
- **Base URL:** https://api.thecatapi.com/v1 
- **Tipo de autenticación:** API Key mediante header `x-api-key` 
- **Rate limit:**
   - Sin API Key:
    - Máximo 10 imágenes por request
    - Acceso limitado a imágenes
  - Con API Key:
    - Hasta 100 imágenes por request
    - Acceso completo a endpoints
    - Permite upload y delete de imágenes
- **Links de la documentación:** 
  - **General:** https://developers.thecatapi.com/view-account/ylX4blBYT9FaoVd6OhvR?report=FJkYOq9tW 
  - **Para usar en Postman** https://documenter.getpostman.com/view/5578104/RWgqUxxh#8606c7c6-338e-46aa-8f1a-3335ed2b8127
---


## Tabla de contenido
- [Resumen de la API](#resumen-de-la-api)
- [Endpoints (resumen)](#endpoints-resumen)
- [Detalles por endpoint](#detalles-por-endpoint)
- [Evidencia (capturas)](#evidencia-capturas)
- [Resumen de pruebas](#resumen-de-pruebas)
- [Instrucciones para completar](#instrucciones-para-completar)

---


## Endpoints (resumen)

| Método | URL | Query params | Headers | Body | Status esperado | Status obtenido | Notas |
|--------|-----|--------------|---------|------|-----------------|------------------|-------|
| GET    | /ruta/ejemplo | page, limit | Authorization: Bearer <token> | - | 200 | - | Ejemplo placeholder |

> Añadir todas las rutas principales en filas separadas

---

## Detalles por endpoint

### Nombre del endpoint: ()

- **Descripción:** 
- **Método:** 
- **URL:** 
- **Parámetros Query:**
  - `param1` (tipo) — descripción
- **Headers requeridos:**
  - `Authorization: Bearer <token>`
  - `Content-Type: application/json`
- **Body (ejemplo):**

```json
{
  "campo": "valor"
}
```

- **Comando de ejemplo (curl):**

```bash
curl -X GET "https://{base_url}/ruta/ejemplo?param=valor" -H "Authorization: Bearer $TOKEN"
```

- **Response esperada (ejemplo):**

```json
{
  "status": "ok",
  "data": {}
}
```

- **Response obtenida (pegar aquí la respuesta real / copiar JSON):**

```json

```

- **Status code obtenido:** 
- **Observaciones / errores encontrados:**

---

Repetir por cada endpoint

## Evidencia (capturas)

- Error
`![texto alternativo](ruta/a/imagen.png)`

---


