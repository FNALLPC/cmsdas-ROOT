---
title: "Using ROOT with python"
teaching: 5
exercises: 0
---

:::::::::::::: questions

- Can I call ROOT from python?

::::::::::::::

:::::::::::::: objectives

- Find resources for PyROOT
- Find resources for Scikit-HEP

::::::::::::::


## PyROOT

The PyROOT project started with Wim Lavrijsen in the late `00s and became very popular, 
paralleling the rise of more general python tools within the community. Python has become the primary analysis language for the majority of HEP experimentalists. It has a
rich ecosystem that is constantly evolving. This is a good thing because it means that improvements
and new tools are always being developed, but it can sometimes be a challenge to keep up with the 
latest and greatest projects! :)

If you want to learn how to use PyROOT, you can go through some individual examples
[here](https://root.cern.ch/doc/master/group__tutorial__pyroot.html), or a more guided tutorial
[here](https://root.cern/manual/python/).

Feel free to challenge yourself to rewrite the previous C++ code using PyROOT! 

## Scikit-HEP libraries

Over the past several years, an effort has developed to provide more python tools that can interface with CMS ROOT file formats as well as typical scientific python tools used widely beyond particle physics.
We will use several of the [Scikit-HEP](https://scikit-hep.org/) libraries to analyze NanoAOD: `uproot`, `awkward`, and `vector`. As CMS datasets grow larger, we increasingly rely on tools for array-based 
data processing in python, and the scikit-HEP tools are very important for that task. 

You can check out a tutorial for many of their tools [here](https://hsf-training.github.io/hsf-training-scikit-hep-webpage/). 


:::::::::::::: keypoints

- PyROOT is a complete interface to the ROOT libraries
- Scikit-HEP provides tools to interface between ROOT and global scientific python tools

::::::::::::::
