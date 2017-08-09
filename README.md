## Corpus Comparison

This repository contains an analysis of the overlap of documents in language resources.

### Language Resources

Currently, the following annotated corpora are compared (more corpora will be added in the future):

- TreeBank-3 ([LDC99T42](https://catalog.ldc.upenn.edu/LDC99T42))
- Proposition Bank I ([LDC2004T14](https://catalog.ldc.upenn.edu/LDC2004T14))
- OntoNotes Release 5.0 ([LDC2013T19](https://catalog.ldc.upenn.edu/LDC2013T19))
- TimeBank 1.2 ([LDC2006T08](https://catalog.ldc.upenn.edu/LDC2006T08))
- FactBank 1.0 ([LDC2009T23](https://catalog.ldc.upenn.edu/LDC2009T23))
- ACE-2 ([LDC2003T11](https://catalog.ldc.upenn.edu/LDC2003T11))
- AQUAINT TimeML ([ELRA-U-W0394](http://universal.elra.info/product_info.php?cPath=42_43&products_id=2333)), also available [here](https://github.com/cnorthwood/ternip/tree/master/sample_data/aquaint_timeml_1.0)

### UpSet Visualization

The intersections of the corpora can be visualized using [UpSet](http://caleydo.org/tools/upset/). There are multiple ways to use the UpSet visualization tool:

1. [UpSet Web Version](http://vcg.github.io/upset):  For an interactive visualization, go to the UpSet Web Version, choose `Load Data` and paste the following link: https://raw.githubusercontent.com/ChantalvanSon/CorpusComparison/master/data/upset.json
2. [UpSetR Shiny App](https://gehlenborglab.shinyapps.io/upsetr/) For a static visualization, go to the UpSetR Shiny App and upload [this document](https://raw.githubusercontent.com/ChantalvanSon/CorpusComparison/master/data/intersections.csv) (can be found under `data`).
3. [UpSetR](https://github.com/hms-dbmi/UpSetR): Install the UpSetR package in R and create the plot using [this document](https://raw.githubusercontent.com/ChantalvanSon/CorpusComparison/master/data/intersections.csv) (can be found under `data`).
4. [pyUpSet](https://github.com/ImSoErgodic/py-upset): Install pyUpSet in Python to create the plot; this will need some more pre-processing and the visualizations are not as nice as the other methods.
