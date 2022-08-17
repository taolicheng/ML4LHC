# ML4LHC-Tutorial

## Data Preparation

* [MadGraph](https://launchpad.net/mg5amcnlo): event generation. A summer school reference slides: https://indico.ihep.ac.cn/event/7822/contribution/19/material/slides/0.pdf

* [Pythia](http://home.thep.lu.se/~torbjorn/Pythia.html): parton shower -- [numpythia](https://github.com/scikit-hep/numpythia): The interface between PYTHIA and NumPy

* [Delphes](https://cp3.irmp.ucl.ac.be/projects/delphes): fast detector simulation
  * Run Delphes without Pythia : instructions [here](https://answers.launchpad.net/mg5amcnlo/+question/282402)

* [FastJet](http://fastjet.fr/): jet clustering -- [PyJet](https://github.com/scikit-hep/pyjet): The interface between FastJet and NumPy

* **Instructions on generating events on a cluster with pbs scheduler**: [[Running MadGraph on the cluster]](notebooks/Note-cluster.md)

### Public Datasets

* [CMS Open Data](http://opendata.cern.ch/docs/about-cms)

## Data Analysis
 * Framework: ROOT
   * c++: with ExRootAnalysis https://cp3.irmp.ucl.ac.be/projects/ExRootAnalysis/wiki/UserManual
   * Python: [PyROOT Tutorial](https://indico.cern.ch/event/704163/contributions/2936719/attachments/1693833/2726445/Tutorial-PyROOT.pdf). And here is an [example](https://github.com/delphes/delphes/blob/master/examples/Example1.py) for PyROOT

 * [HSF](https://hsf-training.github.io/analysis-essentials/index.html)
   * Reweighting: https://hsf-training.github.io/analysis-essentials/advanced-python/7DemoReweighting.html 

## Data Fromatting and Transformation

  * [root2hdf5](http://www.rootpy.org/commands/root2hdf5.html): convert root TTrees into HDF5 tables.  
  * uproot (https://indico.cern.ch/event/686641/contributions/2894906/attachments/1606247/2548596/pivarski-uproot.pdf) /root_numpy
  * [h5py](http://docs.h5py.org/en/stable/) to create hdf5 files more "machine learning-friendly" than .root file

## Deep Learning

* Deep Learning Course repository of Gilles Louppe: https://github.com/glouppe/info8010-deep-learning
* Introduction and basic workflow of DL4HEP: https://github.com/stwunsch/iml_tensorflow_keras_workshop

-----
## Exercises

### Dataset

[to be setup. candidate: zenodo]

### Playground
* Basic data generation and analysis: [[Exercise01]](Ex-uproot.md)
* advanced: tt~ generation
* Jet clustering
* Produce standard h5 files

-----
## Cluster Tips

* [Basic usage](https://github.com/taolicheng/ML4LHC-Tutorial/blob/master/notebooks/Note-cluster.md)
* Easily use jupyter notebook on a cluster: https://josephpcohen.com/w/jupyter-notebook-and-hpc-systems/

-----
## References

* [Scikit-HEP](http://scikit-hep.org/): a toolset of Python packages for particle physics.
* A high-bias, low-variance introduction to Machine Learning for physicists, 
https://arxiv.org/abs/1803.08823

