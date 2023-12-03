# SC_Copy_Number
Graph-Theoretic framework for Detecting Allele and Haplotype Specific Copy Numbers

In this study, we tackle the challenge of inferring allele and haplotype-specific copy numbers from single-cell sequencing data sets. Our approach involves constructing a multi-partite graph, with nodes representing possible copy numbers in each genomic region (bins of size $5k$). Edge weights and node weights are determined based on read depth ratios and B-allele frequency signals. By utilizing Dijkstra's algorithm to find the shortest path from source to sink, we characterize allele and haplotype-specific copy numbers, enabling the construction of phylogenetic trees to elucidate cancer mutation evolution.
