# LiITA_Lemma-Bank
The LiITA Lemma Bank is the core of the LiITA Knowledge Base. It consists of a large collection of
Italian lemmas, serving as the backbone to achieve interoperability, by linking all those entries in lexical resources and tokens in corpora that point to the same lemma.

Data are coded both in a relational database ( SQL format ) and in a graph database (RDF triples - Turtle format).

##  RELATIONAL DATABASE DESCRIPTION

zipped dump is provided in the root folder.
 
### Main tables

* **lemmas** 
```
lemma
```
Each field refers to the corresponding metadata table:
```
 inflectional_category 
 gender              
 grade               
 plurality           
 universal_pos_tag   
```

* Written Representations
```
 lemma_wr            
      
```


* Lemma variants 
```
variant_group
``` 

* Phonetic Representations
```
phonetic_rep
```



## Credits

- **Creators**: CIRCSE Research Centre, Università Cattolica del Sacro Cuore, Milano & Università di Torino
- **Contributors**: Eleonora Litta, Valerio Basile, Cristona Bosco, Paolo Brasolin, Andrea Di Fabio, Francesco Mambrini, Giovanni Moretti, Marco Passarotti

The PRIN 2022 PNRR project LiITA: Interlinking Linguistic Resources for Italian via Linked Data is funded by the European Union - Next Generation EU, Mission 4 Component 1 CUP J53D2301727OOO1.

## Copyright
<a rel="license" href="https://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />These resources are licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

## Citation
Zenodo

