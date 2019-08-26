---
title: "Contribute to NorESM code"
teaching: 10
exercises: 0
questions:
- "How can we update NorESM source code?"
- "When should we contribute to CESM or cime?"
objectives:
- "Understand how to test source code changes"
- "Understand the workflow for contributing to NorESM"
- "Understand is it is a NorESM contribution or CESM or cime"
keypoints:
- "workflow for testing source code changes"
- "take part to the NorESM and CESM community"
---

# Source changes

NorESM source is not publicly available and it is stored in a private repositories hosted by [MetNo](https://www.met.no/).

It is not a community code and developers may not be interested by your changes. However, if you plan to publish 
results from your updated NorESM, you will be required to be able to provide the source code you used. 
It is therefore important to keep all your changes and be able to make them easily accessible.

In this episode, we show you how this can be done.

## Testing/running norESM simulations with code changes

~~~
git clone -b featureCESM2.1.0-OsloDevelopment https://github.com/metno/noresm-dev.git norESM​-dev-CESM2.1.0
~~~
{: .language-bash}

After you cloned NorESM repository, create a new NorESM case and change to the case directory. For instance:

~~~
cd norESM​-dev-CESM2.1.0
./create_newcase --case ~/cases/N1850_0826 --compset N1850 --res f19_tn14 --machine fram --project nn1000k --run-unsupported
~~~
{: .language-bash}

For each case, there is a folder called "SourceMods" where you will place all your changes for running this case. 
~~~
cd ~/cases/N1850_0826
ls SourceMods
~~~
{: .language-bash}

~~~
src.cam  src.cice  src.clm  src.drv  src.micom  src.mosart  src.sglc  src.share  src.swav
~~~
{: .output}

### Steps to modify the code:

- Find the subroutine you want to modify
- Copy this subroutine in SourceMods
- Make your mods
- Compile and run the model

If you update source files, make sure you build again (clean build).


The changes are local to the case. Follow the next steps to keep your changes for creating new cases.

## Save your changes for new cases

We strongly recommend you create a github repository containing the source changes you made for your cases. The github repository can containing
all the SourceMods and a README.md file explaining what has been updated and why.


## Contributing to norESM source code development

If you think your changes are very valuable and should be included in the main NorESM, 
please create [an issue to the NorESM dev repository](https://github.com/metno/noresm-dev/issues/new) or contact NorESM developers.


{% include links.md %}

