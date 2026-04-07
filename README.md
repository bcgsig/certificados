# BCG SIG — Sistema de Verificación de Certificados

Sitio estático para verificar y descargar certificados del curso **Formación de Brigadas** — Explomin 2025.

## Estructura

```
bcg-site/
├── index.html                    ← Página de verificación (raíz)
├── Logo_Horizontal_3.png         ← Logo blanco horizontal
├── Logo_Vertical_1.png           ← Logo color vertical
├── .gitignore
├── certificados/
│   ├── BCG0012026/
│   │   ├── index.html            ← Página del certificado (ya generada)
│   │   └── BCG0012026.pdf        ← ⚠ Debes subir el PDF aquí
│   ├── BCG0022026/
│   │   └── ...
│   └── (27 carpetas en total)
```

## Cómo subir los PDFs

1. Nombra cada PDF exactamente igual que su código: `BCG0012026.pdf`
2. Colócalo dentro de su carpeta: `certificados/BCG0012026/BCG0012026.pdf`
3. Elimina el archivo `.PENDIENTE` de esa carpeta
4. Haz commit y push

## Despliegue en GitHub Pages

1. Ve a **Settings → Pages**
2. Source: `Deploy from a branch`
3. Branch: `main` / `root`
4. Guarda — el sitio estará en: `https://tu-usuario.github.io/bcg-site/`

## Participantes y códigos

| Código       | Nombre                          | Curso                                        |
|:-------------|:--------------------------------|:---------------------------------------------|
| BCG0012026   | ARENAS ROSAS JORGE LUIS         | Primeros Auxilios Básicos                    |
| BCG0022026   | CAYLLAHUA BALTAZAR ALEX CESAR   | Primeros Auxilios Básicos                    |
| BCG0032026   | CCAPA TOMAYA JAIME EDWIN        | Primeros Auxilios Básicos                    |
| BCG0042026   | CHARAJA LARICO HAROLD EFRAÍN    | Primeros Auxilios Básicos                    |
| BCG0052026   | CHULLO CONDO EMERSON FIDEL      | Primeros Auxilios Básicos                    |
| BCG0062026   | COAQUIRA CABANA BRHANDUM ELVISS | Primeros Auxilios Básicos                    |
| BCG0072026   | LEON TINEDO GINA ELIDA          | Primeros Auxilios Básicos                    |
| BCG0082026   | TACO PONCE DILMAN DINO          | Primeros Auxilios Básicos                    |
| BCG0092026   | YUCA APAZA GUSTAVO              | Primeros Auxilios Básicos                    |
| BCG0102026   | ARENAS ROSAS JORGE LUIS         | Prevención y Protección Contra Incendios     |
| BCG0112026   | CAYLLAHUA BALTAZAR ALEX CESAR   | Prevención y Protección Contra Incendios     |
| BCG0122026   | CCAPA TOMAYA JAIME EDWIN        | Prevención y Protección Contra Incendios     |
| BCG0132026   | CHARAJA LARICO HAROLD EFRAÍN    | Prevención y Protección Contra Incendios     |
| BCG0142026   | CHULLO CONDO EMERSON FIDEL      | Prevención y Protección Contra Incendios     |
| BCG0152026   | COAQUIRA CABANA BRHANDUM ELVISS | Prevención y Protección Contra Incendios     |
| BCG0162026   | LEON TINEDO GINA ELIDA          | Prevención y Protección Contra Incendios     |
| BCG0172026   | TACO PONCE DILMAN DINO          | Prevención y Protección Contra Incendios     |
| BCG0182026   | YUCA APAZA GUSTAVO              | Prevención y Protección Contra Incendios     |
| BCG0192026   | ARENAS ROSAS JORGE LUIS         | Evacuación en Caso de Emergencias            |
| BCG0202026   | CAYLLAHUA BALTAZAR ALEX CESAR   | Evacuación en Caso de Emergencias            |
| BCG0212026   | CCAPA TOMAYA JAIME EDWIN        | Evacuación en Caso de Emergencias            |
| BCG0222026   | CHARAJA LARICO HAROLD EFRAÍN    | Evacuación en Caso de Emergencias            |
| BCG0232026   | CHULLO CONDO EMERSON FIDEL      | Evacuación en Caso de Emergencias            |
| BCG0242026   | COAQUIRA CABANA BRHANDUM ELVISS | Evacuación en Caso de Emergencias            |
| BCG0252026   | LEON TINEDO GINA ELIDA          | Evacuación en Caso de Emergencias            |
| BCG0262026   | TACO PONCE DILMAN DINO          | Evacuación en Caso de Emergencias            |
| BCG0272026   | YUCA APAZA GUSTAVO              | Evacuación en Caso de Emergencias            |

---
© 2025 BCG Soluciones de Ingeniería y Gestión S.A.C.
