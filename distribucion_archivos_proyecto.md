# Distribución de Archivos por Plataforma

## Última actualización: 2026-02-15

---

## Resumen de tamaños

| Archivo | Bytes | ~Tokens |
|---|---|---|
| catalogo_biblioteca_juridica_tdj.md | 16,661 | 4,165 |
| **Acuerdos TDJ (10 archivos):** | | |
| AG_TDJ_CHIH_02_2025.md | 9,437 | 2,359 |
| AG_TDJ_CHIH_04_2025.md | 10,478 | 2,619 |
| AG_TDJ_CHIH_08_2025.md | 16,763 | 4,190 |
| AG_TDJ_CHIH_11_2025.md | 35,070 | 8,767 |
| AG_TDJ_CHIH_12_2025.md | 15,474 | 3,868 |
| AG_TDJ_CHIH_13_2025.md | 37,274 | 9,318 |
| AG_TDJ_CHIH_16_2025.md | 16,581 | 4,145 |
| AG_TDJ_CHIH_17_2025.md | 14,501 | 3,625 |
| AG_TDJ_CHIH_19_2025.md | 43,208 | 10,802 |
| AG_TDJ_CHIH_01_2026.md | 27,138 | 6,784 |
| **Subtotal Acuerdos TDJ** | **225,924** | **~56,477** |
| **Legislación principal:** | | |
| LOPJE_2025_vigente.md | 334,356 | 83,589 |
| LGRA_2025_vigente.md | 238,292 | 59,573 |
| CPECHIH_2024_vigente.md | 434,244 | 108,561 |
| CPEUM_2025_vigente.md | 974,663 | 243,666 |
| **Legislación complementaria:** | | |
| LAMPARO_2025_vigente.md | 351,239 | 87,810 |
| CNPP_2025_vigente.md | 588,566 | 147,142 |
| CPECHIH_PENAL_2006_vigente.md | 693,523 | 173,381 |
| LFT_2025_vigente.md | 1,279,327 | 319,832 |
| LTAIPECHIH_2024_vigente.md | 163,612 | 40,903 |
| LEDMVLV_2024_vigente.md | 242,261 | 60,565 |
| LPDPCHIH_2017_vigente.md | 106,259 | 26,565 |
| LFISCHIH_2022_vigente.md | 96,383 | 24,096 |
| LARCHIVOS_2021_vigente.md | 121,932 | 30,483 |
| LOPJF_2022_vigente.md | 252,742 | 63,186 |
| LOPJECHIH_2019_abrogada.md | 278,902 | 69,726 |
| LOPJECHIH_2014_abrogada.md | 503,099 | 125,775 |
| RLOPJE_2012_vigente.md | 107,827 | 26,957 |
| LASECHIH_2018_vigente.md | 55,667 | 13,917 |
| LSAECHIH_2018_vigente.md | 54,601 | 13,650 |
| LRSPECHIH_2018_abrogada.md | 49,874 | 12,469 |
| CETICA_TSJ_2020_vigente.md | 55,364 | 13,841 |
| PROT_VIOLENCIA_TSJ_2024_vigente.md | 42,531 | 10,633 |
| AG_CJ_VIOLAB_2018_vigente.md | 28,442 | 7,111 |
| RVISIT_TSJ_2021_vigente.md | 28,111 | 7,028 |
| AG135_TRANSP_2008_vigente.md | 26,421 | 6,605 |
| AG_CJ_RESPADM_2017_vigente.md | 18,375 | 4,594 |
| LERCHIH_2016_vigente.md | 18,725 | 4,681 |
| RSESCJ_2019_vigente.md | 17,260 | 4,315 |
| LRPJFMP_2017_vigente.md | 9,210 | 2,303 |
| **TOTAL BIBLIOTECA (39 archivos + catálogo + distribución)** | **~7,424,000** | **~1,856,000** |

---

## Para Claude Projects (~200K tokens de contexto)

### Archivos permanentes (Nivel 1) — Siempre cargados

Estos archivos deben estar SIEMPRE en el proyecto. Son la normativa propia del TDJ y las leyes que fundamentan su actuación diaria.

| # | Archivo | ~Tokens | Justificación |
|---|---|---|---|
| 1 | catalogo_biblioteca_juridica_tdj.md | 3,892 | Índice maestro, permite localizar cualquier documento |
| 2 | AG_TDJ_CHIH_02_2025.md | 2,359 | Estructura de Salas del TDJ |
| 3 | AG_TDJ_CHIH_04_2025.md | 2,619 | Comisiones del TDJ |
| 4 | AG_TDJ_CHIH_08_2025.md | 4,190 | Recepción de denuncias — flujo principal |
| 5 | AG_TDJ_CHIH_11_2025.md | 8,767 | Sesiones de Pleno |
| 6 | AG_TDJ_CHIH_12_2025.md | 3,868 | Delegación a Secretarías de Sala |
| 7 | AG_TDJ_CHIH_13_2025.md | 9,318 | Funcionamiento de Comisiones |
| 8 | AG_TDJ_CHIH_16_2025.md | 4,145 | Procedimientos heredados del CJ |
| 9 | AG_TDJ_CHIH_17_2025.md | 3,625 | Reanudación de plazos |
| 10 | AG_TDJ_CHIH_19_2025.md | 10,802 | Segunda instancia |
| 11 | AG_TDJ_CHIH_01_2026.md | 6,784 | Evaluación de juzgadores |
| 12 | LOPJE_2025_vigente.md | 83,589 | Ley orgánica vigente — fundamento principal |
| 13 | LGRA_2025_vigente.md | 59,573 | Ley sustantiva de responsabilidades administrativas |
| | **Total Nivel 1** | **~203,804** | **⚠️ Excede ~200K — considerar mover AG 01/2026 a Nivel 2** |

### Archivos bajo demanda (Nivel 2) — Consultar vía GitHub con web_fetch

| Archivo | ~Tokens | Cuándo consultar |
|---|---|---|
| CPECHIH_2024_vigente.md | 108,561 | Fundamento constitucional local (Arts. 107-109) |
| CPEUM_2025_vigente.md | 243,666 | Fundamento constitucional federal (Arts. 108-114) |
| LAMPARO_2025_vigente.md | 87,810 | Juicios de amparo contra resoluciones del TDJ |
| CNPP_2025_vigente.md | 147,142 | Referencia procesal penal |
| LTAIPECHIH_2024_vigente.md | 40,903 | Transparencia y acceso a información |
| LPDPCHIH_2017_vigente.md | 26,565 | Protección de datos personales |
| LEDMVLV_2024_vigente.md | 60,565 | Violencia de género |
| AG_CJ_VIOLAB_2018_vigente.md | 7,111 | Violencia laboral y acoso |
| CETICA_TSJ_2020_vigente.md | 13,841 | Ética y conducta |
| PROT_VIOLENCIA_TSJ_2024_vigente.md | 10,633 | Protocolo de violencia |
| Todos los demás | Variable | Ver catálogo para triggers específicos |

---

## Para ChatGPT Projects (máximo 25 archivos)

### Criterio de priorización

Los 10 acuerdos TDJ son obligatorios. El catálogo es obligatorio. Las leyes restantes se priorizan por frecuencia de cita en los acuerdos del TDJ y relevancia directa.

**Frecuencia de cita en los 10 acuerdos TDJ:**

- LOPJE 2025: citada en los 10 acuerdos (Arts. 238, 240, 247, 303)
- Constitución Local (CPECHIH): citada en los 10 acuerdos (Arts. 107, 108)
- CPEUM: citada en AG 01/2026, AG 08, AG 16, AG 19 (4 acuerdos)
- LGRA: citada en AG 08, AG 16, AG 19 (3 acuerdos)
- CNPP: citado en AG 19 (1 acuerdo)
- Código de Ética: citado en AG 08, AG 01/2026 (2 acuerdos)
- Ley de Protección de Datos: citada en AG 08, AG 01/2026 (2 acuerdos)
- Ley de Transparencia: citada en AG 08 (1 acuerdo)
- Ley Mujeres Vida Libre Violencia: citada en AG 08 (1 acuerdo)
- Bases Violencia Laboral (AG_CJ_VIOLAB): citada en AG 08 (1 acuerdo)

### Los 25 archivos recomendados

| Slot | Archivo | ~Tokens | Categoría |
|---|---|---|---|
| 1 | catalogo_biblioteca_juridica_tdj.md | 3,892 | Índice maestro |
| 2 | AG_TDJ_CHIH_02_2025.md | 2,359 | Acuerdo TDJ |
| 3 | AG_TDJ_CHIH_04_2025.md | 2,619 | Acuerdo TDJ |
| 4 | AG_TDJ_CHIH_08_2025.md | 4,190 | Acuerdo TDJ |
| 5 | AG_TDJ_CHIH_11_2025.md | 8,767 | Acuerdo TDJ |
| 6 | AG_TDJ_CHIH_12_2025.md | 3,868 | Acuerdo TDJ |
| 7 | AG_TDJ_CHIH_13_2025.md | 9,318 | Acuerdo TDJ |
| 8 | AG_TDJ_CHIH_16_2025.md | 4,145 | Acuerdo TDJ |
| 9 | AG_TDJ_CHIH_17_2025.md | 3,625 | Acuerdo TDJ |
| 10 | AG_TDJ_CHIH_19_2025.md | 10,802 | Acuerdo TDJ |
| 11 | AG_TDJ_CHIH_01_2026.md | 6,784 | Acuerdo TDJ |
| 12 | LOPJE_2025_vigente.md | 83,589 | Ley orgánica principal (10/10 AGs) |
| 13 | LGRA_2025_vigente.md | 59,573 | Ley sustantiva RA (3/10 AGs) |
| 14 | CPECHIH_2024_vigente.md | 108,561 | Constitución Local (10/10 AGs) |
| 15 | CETICA_TSJ_2020_vigente.md | 13,841 | Código de ética (2/10 AGs) |
| 16 | AG_CJ_VIOLAB_2018_vigente.md | 7,111 | Bases violencia laboral (1/10 AGs) |
| 17 | PROT_VIOLENCIA_TSJ_2024_vigente.md | 10,633 | Protocolo violencia |
| 18 | AG_CJ_RESPADM_2017_vigente.md | 4,594 | RA procedimiento anterior (transición) |
| 19 | LTAIPECHIH_2024_vigente.md | 40,903 | Transparencia (1/10 AGs) |
| 20 | LPDPCHIH_2017_vigente.md | 26,565 | Datos personales (2/10 AGs) |
| 21 | AG135_TRANSP_2008_vigente.md | 6,605 | Transparencia en RA |
| 22 | RSESCJ_2019_vigente.md | 4,315 | Sesiones CJ (referencia histórica) |
| 23 | LERCHIH_2016_vigente.md | 4,681 | Entrega-recepción |
| 24 | RVISIT_TSJ_2021_vigente.md | 7,028 | Reglamento de visitas |
| 25 | LRPJFMP_2017_vigente.md | 2,303 | Responsabilidad patrimonial |

**Total estimado:** ~434,070 tokens en 25 archivos

### Archivos fuera del proyecto (subir manualmente cuando se necesiten)

Estos archivos son demasiado grandes o de uso esporádico para ocupar un slot permanente:

| Archivo | ~Tokens | Cuándo subir |
|---|---|---|
| CPEUM_2025_vigente.md | 243,666 | Si se necesita fundamento constitucional federal |
| LAMPARO_2025_vigente.md | 87,810 | Si hay juicio de amparo involucrado |
| CNPP_2025_vigente.md | 147,142 | Si hay denuncia penal derivada |
| CPECHIH_PENAL_2006_vigente.md | 173,381 | Si se necesita tipificar un delito |
| LFT_2025_vigente.md | 319,832 | Si hay conflicto laboral (uso raro) |
| LEDMVLV_2024_vigente.md | 60,565 | Si hay denuncia de violencia de género |
| LFISCHIH_2022_vigente.md | 24,096 | Si hay tema de fiscalización |
| LARCHIVOS_2021_vigente.md | 30,483 | Si hay tema de archivos/documentación |
| LOPJF_2022_vigente.md | 63,186 | Si se necesita referencia con PJF |
| LOPJECHIH_2019_abrogada.md | 69,726 | Si se necesita referencia histórica |
| LOPJECHIH_2014_abrogada.md | 125,775 | Si se necesita referencia histórica |
| RLOPJE_2012_vigente.md | 26,957 | Si se necesita reglamento LOPJE |
| LASECHIH_2018_vigente.md | 13,917 | Si hay tema de auditoría superior |
| LSAECHIH_2018_vigente.md | 13,650 | Si hay tema de sistema anticorrupción |
| LRSPECHIH_2018_abrogada.md | 12,469 | Si se necesita régimen anterior de RA |

---

## Notas importantes

1. **Los 10 acuerdos del TDJ suman ~56K tokens** — SIEMPRE deben estar cargados en cualquier plataforma.

2. **La LOPJE 2025 (~84K tokens) es indispensable** — es la ley orgánica vigente y el fundamento de todos los acuerdos del TDJ.

3. **La LGRA (~60K tokens) es la segunda prioridad** — regula las faltas administrativas que el TDJ substancia y resuelve.

4. **Para Claude Projects**, los 13 archivos de Nivel 1 (~204K tokens) exceden ligeramente los ~200K de contexto. Si es necesario ajustar, mover AG_TDJ_CHIH_01_2026.md (~6.8K tokens) a Nivel 2 reduce el total a ~197K tokens. Alternativa: la distribución real depende del tokenizador (estimación conservadora de 4 bytes/token).

5. **Para ChatGPT Projects**, los 25 archivos recomendados cubren normativa propia + leyes más citadas + normativa complementaria de uso frecuente. Los archivos más grandes (CPEUM, Código Penal, LFT) se suben solo cuando se necesitan.

6. **Verificar periódicamente** si hay nuevos acuerdos del TDJ o reformas legislativas que requieran actualizar la biblioteca.
