# Analysis-of-Radome-using-MEEP

### *Introduction :*
MEEP is a open-source FDTD (Finite-Difference Time-domain) based EM solver that can be used resolve Maxwell equation for a deep parametric study of em-waves from a point source.<br>
since MEEP is now overstacked by python, thus ***pymeep*** can be used to define the following,
* geometry
* material
* source
* field-analysis <br>

thus combining with ***numpy*** and ***matlabplotlib*** various plots can be generated form that field data for a better understanding of em-wave properties that is resolved by
MEEP.<br>
MEEP is mostly used in Photonics/Optics domain but since it is an invariant software <br>
*{refer : https://meep.readthedocs.io/en/latest/Introduction/#units-in-meep (for a better understanding of MEEP Units) }* <br>
thus MEEP can be also used in RF domain for various EM based studies *{refer: https://www.mdpi.com/2079-9292/10/4/415 (A research paper on Broadband RF phased array design using MEEP)}*

### *Radomes :*
it is a housing that encloses radar sensors to minimize electrical and environmental interferences.

to keep the project simple only insertion-loss is taken as verification parameter 
#### Insertion Loss (IL)

Insertion Loss is the reduction in transmitted or received electromagnetic power caused by inserting a radome into the signal path.

The insertion loss is calculated as:

$$
IL_{\mathrm{dB}} = 10\log_{10}\left(\frac{P_{\mathrm{without\ radome}}}{P_{\mathrm{with\ radome}}}\right)
$$

System used : Ubunutu 24.04 LTS <br>
Install MEEP(from Conda Packages) {https://meep.readthedocs.io/en/latest/Installation/#conda-packages} <br>
After installation activate the conda environment `conda activate meep` and then install Jupyter Notebook inside Conda for interactive python space 
*{https://jupyter.org/install (Required for verificaton)}*

```bash
conda activate meep
jupyter notebook
```
### Reference :
https://www.ti.com/lit/an/swra705/swra705.pdf *(Best piece of reference for Radome design for beginners)* <br>
https://meep.readthedocs.io/en/latest/Python_Tutorials/Basics/ *(Best site to learn MEEP for beginners)*
### MindMap :
