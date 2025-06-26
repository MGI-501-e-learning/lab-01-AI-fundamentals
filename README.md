# lab-01-AI-fundamentals

lab-01-AI-fundamentals

## Pre-Requisitos

### Instalar/Actualizar Anaconda

Anaconda es una distribución gratuita y de código abierto de Python y R, diseñada específicamente para la computación científica, la ciencia de datos, el aprendizaje automático y la inteligencia artificial.

```
  pwd                                                                                                    26.06.25    15:25:17 
/Users/maverickzhn/repos/unah/MGI-501/lab-01-AI-fundamentals

  ~/repos/unah/MGI-501/lab-01-AI-fundamentals     main 
   mkdir backup                                                                                           26.06.25    15:34:01 

  ~/repos/unah/MGI-501/lab-01-AI-fundamentals     main 
   conda env export > backup/environment.yml                                                              26.06.25    15:34:11 

  ~/repos/unah/MGI-501/lab-01-AI-fundamentals     main  
   conda create -n base_backup --clone base                                                               26.06.25    15:34:47 

Retrieving notices: ...working... done
Source:      /Users/maverickzhn/opt/anaconda3
Destination: /Users/maverickzhn/opt/anaconda3/envs/base_backup
The following packages cannot be cloned out of the root environment:
 - defaults/osx-64::conda-env-2.6.0-1
 - conda-forge/osx-64::conda-22.11.1-py39h6e9494a_1
 - defaults/osx-64::conda-build-3.21.8-py39hecd8cb5_2
 - defaults/noarch::conda-token-0.3.0-pyhd3eb1b0_0
 - defaults/osx-64::anaconda-2022.05-py39_0
 - defaults/osx-64::anaconda-navigator-2.3.1-py39hecd8cb5_0
Packages: 410
Files: 19328

Downloading and Extracting Packages


Downloading and Extracting Packages

Preparing transaction: done
Verifying transaction: done
Executing transaction: \

    Installed package of scikit-learn can be accelerated using scikit-learn-intelex.
    More details are available here: https://intel.github.io/scikit-learn-intelex

    For example:

        $ conda install scikit-learn-intelex
        $ python -m sklearnex my_application.py

done
#
# To activate this environment, use
#
#     $ conda activate base_backup
#
# To deactivate an active environment, use
#
#     $ conda deactivate

```
