# PriSeT_denovo
Primers computed by PriSeT

## Known Primers 
 
The file `known_primers.csv` contains DNA4 encoded primer pairs.
    
| Primer    |  Fwd ID  | Fwd Seq               | Rev ID   | Rev Seq               | Reference       |
| --------- | -------- | --------------------- | -------- | --------------------- | --------------- | 
| 23S       | 23S fwd  | GGACARAAAGACCCTATG    | A23SrVR1 | AGATCAGCCTGTTATCC$    |     |
| CHLORO    | ChloroF  | TGGCCTATCTTGTTGGTCTGT | ChloroR  | GAATCAACCTGACAAGGCAAC |     |
| DIAZ      | D512for  | ATTCCAGCTCCAATAGCG    | D978rev  | GACTACGATGGTATCTAATC  |     |
| DIV4      | DIV4for  | GCGGTAATTCCAGCTCCAATAG | DIV4rev3 | CTCTGACAATGGAATACGAATA |   |
| EUK14     | F-566a   | CAGCAGCCGCGGTAATTCC   | R-1200   | CCCGTGTTGAGTCAAATTAAGC |   |
| EUK15     | TAReuk454FWD1 | CCAGCASCYGCGGTAATTCC | TAReukREV3 | ACTTTCGTTCTTGATYRA |   |
| EUKA (EA) | EUKAF    | GCCGCGGTAATTCCAGCTC   | EUKAR    | CYTTCGYYCTTGATTRA     |   |
| nSSU      | G18S4    | GCTTGTCTCAAAGATTAAGCC | 22R      | GCCTGCTGCCTTCCTTGGA   |   |
| SSU       | SSU556F  | CGCGGTAATTCCAGCTYC    | SSU911R  | ATYCAAGAATTTCACCTCTGAC |   |

## De Nove Primers

File prefix corresponds to the clade ID according to NCBI's taxonomy. 

  * `id_primers.csv` contains the top 50 de novo computed primers w.r.t. frequency
  * `id_known_primers.csv` is the result of a meta analysis that compares frequency and coverage rates with known primers (see Table above)



