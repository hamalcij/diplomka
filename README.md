# Pfam database

## File `architecture_count`

```
number_of_proteins    architecture
```

## File `pfam_count`

```
pfam_id    proteins    domains    architectures
```

## File `pfam_position`

```
pfam_id    n_terminal_domains    non_terminal_domains    c_terminal_domains    stand_alone_domains
```

## File `pfam_neighbors`

```
L(=n_terminal_neighbors)    pfam_id    most_frequent_L_neighbor    neighbor_count    2nd_most_frequent_L_neighbor    neighbor_count    ...    least_frequent_L_neighbor    neighbor_count
R(=c_terminal_neighbors)    pfam_id    most_frequent_R_neighbor    neighbor_count    2nd_most_frequent_R_neighbor    neighbor_count    ...    least_frequent_R_neighbor    neighbor_count
```
