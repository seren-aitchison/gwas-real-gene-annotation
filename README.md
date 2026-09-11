# gwas-real-gene-annotation
Annotate human genetic variants to real genes using genomic coordinates retrieved from the Ensembl REST API, with illustrative GWAS significance analysis.

# Real GWAS Gene Annotation

This project demonstrates how genomic variants can be mapped to real human genes using coordinates retrieved from the Ensembl REST API.

## Workflow

1. Load illustrative variant identifiers and genomic coordinates.
2. Retrieve real GRCh38 gene coordinates from Ensembl.
3. Match variants to genes based on chromosome and genomic position.
4. Classify variants using an illustrative genome-wide significance threshold.
5. Visualise significance by annotated gene.

## Example annotations

- rs429358 → APOE
- rs7412 → APOE
- rs1801133 → MTHFR

## Important limitation

The variant p-values are simulated for educational purposes. The project demonstrates the annotation workflow and does not claim to establish real disease associations.
