# Gene2protein – SP7 Analysis

## Gene Information

* Gene Name: SP7
* Gene ID: ENSG00000122585
* Function: Essential for bone-forming cells

## Objective

To extract:

* Transcripts (ENST)
* Proteins (ENSP)
* Protein-to-genome mapping

## Methodology

Used R with Bioconductor packages:

* AnnotationHub
* ensembldb

## Output Files

* SP7_transcripts.tsv → contains all transcripts
* SP7_proteins.tsv → contains protein products
* SP7_protein_genome_map.tsv → maps proteins to genome coordinates

## Platform Used

Google Colab (R runtime)

## Notes

All data retrieved from Ensembl database (GRCh38)
