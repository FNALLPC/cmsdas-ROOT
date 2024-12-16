---
title: Setup
---

This lesson requires several software packages common in high-energy physics. This exercise is intended to be used for Fermilab's CMS Data Analysis School 2025. If you have completed the [pre-exercises](https://fnallpc.github.io/cms-das-pre-exercises/), go to the following CMSSW area and set the CMS environment to access these packages.

Connect to the LPC cluster:

```bash
kinit <YourUsername>@FNAL.GOV               # if needed
ssh -XY <your-username>@cmslpc-el8.fnal.gov
```

Access your CMSSW environment:

```bash
cd ~/nobackup/cmsdas/CMSSW_13_0_10
cmsenv
mkdir root-exercise
cd root-exercise/
```

Now you are ready to do the steps of this exercise in your terminal!
