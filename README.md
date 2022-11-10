# DNA-Prot

## Recent DNA-protein interaction sites prediction methods

- **Sequence-based DNA-protein interaction**

  - DNAPred (J ChemInf Model, 2019)
    - Employs ensumble of SVMs to predict protein-DNA bind sites 
    - [Paper](https://pubs.acs.org/doi/full/10.1021/acs.jcim.8b00749) 
    - [Data/Webserver](http://202.119.84.36:3079/dnapred/)
  - DNAGenie (Brief Bioinform, 2021)
    - DNA-type specific protein binding using two layers of ML (logistic regression, weighted k-nearestneighbor (kNN), Naïve Bayes, random forest and support vector
machine)
    - [Paper](https://doi.org/10.1093/bib/bbab336)
    - [Webserver](http://biomine.cs.vcu.edu/servers/DNAgenie/), [Data/Mirror Webserver](http://www.inforstation.com/webservers/DNAgenie/predict.html)
  - NCBRPred (Brief Bioinform, 2021)
    - DNA and RNA binding prediction using BiGRU
    - [Paper](https://doi.org/10.1093/bib/bbab564)
    - [Standalone package and webserver](http://bliulab.net/NCBRPred/)
  - TargetDNA (IEEE/ACM Trans Comput Biol Bioinform, 2016)
    - Employs SVMs
    - [Paper](https://doi.org/10.1109/tcbb.2016.2616469)
    - [Data/Webserver](http://csbio.njust.edu.cn/bioinf/TargetDNA/)
  - DBPred (Brief Bioinform, 2022)
    - Utilizes XgBoost to predict DNA-protein interaction. **A list of DNA-interacting residue predictor (tool/software) is listed in page 2**
    - [Paper](https://doi.org/10.1093/bib/bbac322)
    - [Standalone package and webserver](https://webs.iiitd.edu.in/raghava/dbpred)
  - ProNA2020 (jmb 2020)
    - Employs NNs to predict protein-DNA, protein-RNA and protein-protein interactions
    - [Paper](https://doi.org/10.1016/j.jmb.2020.02.026)
    - [GitHub](https://github.com/Rostlab/ProNA2020.git)

  
  - HybridNap (Brief Bioinform, 2017) **Benchmarking Data**
    - [Paper](https://doi.org/10.1093/bib/bbx168)
    - [Benchmark Data](http://biomine.cs.vcu.edu/servers/hybridNAP/)


- **Structure-based DNA-protein interaction**

  - COACH-D (Nucleic Acids Research, 2018)
    - Template-based protein-ligand binding prediction
    - [Paper](https://doi.org/10.1093/nar/gky439)
    - [Webserver](http://yanglab.nankai.edu.cn/COACH-D/)
  - NucBind (Bioinformatics, 2019)
    - Combines COACH-D with SVM-based SVMnuc to predict nucleic acid binding residues
    - [Paper](https://doi.org/10.1093/bioinformatics/bty756)
    - [Webserver](https://yanglab.nankai.edu.cn/NucBind/)
  - DeepSite (Bioinformatics, 2017)
    - Employs 3D CNNs for ligand-binding prediction
    - [Paper](https://doi.org/10.1093/bioinformatics/btx350)
    - [Weberver](https://playmolecule.com/deepsite/)
