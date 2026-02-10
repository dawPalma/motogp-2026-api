# MotoGP 2026 Encyclopedia API 🏁📚

La API REST definitiva para la temporada 2026 de MotoGP, Moto2 y Moto3. Este proyecto sirve como una base de datos completa (Enciclopedia) lista para ser consumida mediante **My JSON Server**.

## 🚀 Despliegue en GitHub (My JSON Server)

1.  **Repositorio**: Crea un repo llamado `motogp-2026-api`.
2.  **Archivo**: Sube el `db.json` a la raíz.
3.  **Url**: `https://my-json-server.typicode.com/TU_USUARIO/motogp-2026-api/`

---

## 📂 Recursos y Endpoints

### 🏍️ Pilotos (`/riders`)
Contiene las parrillas completas de las tres categorías (~75 pilotos).
- **Filtros**: `?category=MotoGP`, `?nationality=Spanish`, `?team=Ducati Lenovo Team`.

### 🏁 Circuitos (`/circuits`)
Los 22 trazados del calendario 2026, incluyendo eventos nuevos como **Brasil** y **Hungría**.
- **Campos**: Nombre, ubicación, longitud, récord de vuelta y fecha en 2026.

### 🛡️ Equipos (`/teams`)
Información sobre los equipos oficiales y satélites, fabricantes y directores de equipo.

### 📜 Reglamento (`/regulations`)
Resumen de las normas técnicas y deportivas para 2026, junto con el significado oficial de las banderas.

---

## 🛠️ Prueba Local

Asegúrate de tener Node.js y ejecuta:
```bash
npx json-server db.json
```

---

## ✅ Calidad de Datos

- **Imágenes**: Patrón oficial de `photos.motogp.com`.
- **Fichajes 2026**: Bagnaia/Marquez (Ducati), Martin/Bezzecchi (Aprilia), etc., verificados.
- **Circuitos**: Datos técnicos extraídos de fuentes oficiales de la FIM.
