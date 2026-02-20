# Informe de Onboarding de API

## Resumen de la API

- **Nombre de la API:** 
- **Base URL:** 
- **Tipo de autenticación:** (p. ej. API Key, Bearer Token, OAuth2)
- **Rate limit:** 
- **Contacto / dueño:** 

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


