# <div align="center"> Stats for AMI, ICSI, ELITR_Minuting_corpus datasets </div>

# Downloading databases.
## 1. AMI, AMI (XML)
Download the AMI database from [here](https://drive.google.com/drive/folders/13OjREs8z131jl3fuglw1CC9vseWb3IO7?usp=sharing).
Clone the Github repo from [here](https://github.com/gcunhase/AMICorpusXML.git) for AMI (XML) database.

## 2. ICSI
Clone the Github repo from [here](https://github.com/saprativa/ICSI.git) for ICSI database.

## 3. ELITR_Minuting_corpus
Download the preprocessed ELITR_Minuting_corpus from [here](https://drive.google.com/file/d/12P1Wfl5DUvZoId9zdU5e8CkHQf7FijLS/view?usp=sharing).

# Getting graphs.
Line graphs
```
python ./Line_graphs.py \
--ami ./ami \
--ami_xml ./AMICorpusXML \
--icsi ./ICSI \
--elitr ./train
```

Bar graphs
```
python ./Minuting_bar.py \
--ami ./ami \
--icsi ./ICSI \
--elitr ./train
```
