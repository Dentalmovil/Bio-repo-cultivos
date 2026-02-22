# Clasificación y Metabolismo C4

El maíz es una gramínea de verano con una eficiencia fotosintética superior gracias a su ruta C4.

## Taxonomía
- **Especie:** *Zea mays*
- **Familia:** Poaceae
- **Metabolismo:** C4 (Anatomía de Kranz)

```mermaid
graph TD
    A[CO2 Externo] --> B[Células del Mesófilo]
    B --> C[Ácido de 4 Carbonos]
    C --> D[Células de la Vaina]
    D --> E[Ciclo de Calvin: Glucosa]
    style E fill:#f1c40f,stroke:#333

**`docs/maiz-maduracion.md`**
```markdown
# Proceso de Maduración Reproductiva

La madurez del grano se divide en etapas críticas que determinan el rendimiento final.

| Etapa | Descripción | Indicador |
| :--- | :--- | :--- |
| **R1** | Polinización | Estigmas visibles |
| **R3** | Estado Lechoso | Acumulación de almidón |
| **R5** | Estado Dentado | Formación de la línea de leche |
| **R6** | Madurez Fisiológica | **Capa Negra** (Peso máximo) |

```mermaid
graph LR
    R3[Lechoso] --> R4[Masoso]
    R4 --> R5[Dentado]
    R5 --> R6[Capa Negra]
    style R6 fill:#f1c40f,stroke:#333,stroke-width:4px
**`docs/maiz-calidad.md`**
```markdown
# Calidad del Grano y Poscosecha

El maíz debe cumplir estándares físicos para su almacenamiento.

- **Humedad crítica:** 14% para evitar hongos (*Aspergillus*).
- **Densidad:** Medida en Peso Hectolítrico.
- **Endospermo:** Puede ser vítreo (duro) o harinoso (suave).
