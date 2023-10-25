# KEGG and GO
## Sai Manoj Tekumalla

# Methods

## KEGG:
KEGG is a database resource for understanding high-level functions and utilities of the biological system, such as the cell, the organism and the ecosystem, from molecular-level information, especially large-scale molecular datasets generated by genome sequencing and other high-throughput experimental technologies.[1]

## Gene Ontology:
The Gene Ontology (GO) describes our knowledge of the biological domain with respect to three aspects:

1.Molecular-level activities performed by gene products. Molecular function terms describe activities that occur at the molecular level, such as “catalysis” or “transport”. GO molecular function terms represent activities rather than the entities (molecules or complexes) that perform the actions, and do not specify where, when, or in what context the action takes place. Molecular functions generally correspond to activities that can be performed by individual gene products (i.e. a protein or RNA), but some activities are performed by molecular complexes composed of multiple gene products.

2.The locations relative to cellular structures in which a gene product performs a function, either cellular compartments (e.g., mitochondrion), or stable macromolecular complexes of which they are parts (e.g., the ribosome). Unlike the other aspects of GO, cellular component classes refer not to processes but rather a cellular anatomy.

3.The larger processes, or ‘biological programs’ accomplished by multiple molecular activities. Examples of broad biological process terms are DNA repair or signal transduction. Examples of more specific terms are pyrimidine nucleobase biosynthetic process or glucose transmembrane transport. Note that a biological process is not equivalent to a pathway. At present, the GO does not try to represent the dynamics or dependencies that would be required to fully describe a pathway.[2]

## Using KEGG Orthologs:
KEGG API can be used to obtain KEGG ortholog IDs which is a REST-style application programming interface to the KEGG database resource. 

## Parsing a tabular file and executing a command:
Use the KEGG API to retrieve a KEGG ID for each SwissProt ID in the BLAST output where the evalue < 1e-180.

# Citations
[1] https://www.genome.jp/kegg/

[2] Gene Ontology overview
http://geneontology.org/docs/ontology-documentation/