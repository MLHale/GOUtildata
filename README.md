# GOUtildata
Data for the Pathway Viz project

## Naming convention for the filenames with multiple organisms and namespaces
```
<filetype>.<organism>.<namespace>.txt
```
## Organism key-value:
* hsa = Homo sapiens (human)
* gga = Gallus gallus (chicken)
* bta = Bos taurus (cow)
* cfa = Canis familiaris (dog)
* mmu = Mus musculus (mouse)
* rno = Rat norvegicus (rat)
* cel = Caenorhabditis elegans (nematode)
* ath = Arabidopsis thaliana (thale cress)
* dme = Drosophila melanogaster (fruit fly)
* sce = Saccharomyces cerevisiae (budding yeast)
* eco = Escherichia coli
* dre = Danio rerio (zebrafish)

## namespacke key-value
* bp = biological process
* mf = molecular function
* cc = cellular component

## Summary of files

**Edges from one term to the other from the go.obo file for a given namespace.**
```
edgelist.<namespace>.txt
```

**Gene centric annotation for a given organism and given namespace.**
```
ann.<organism>.<namespace>.txt
```


