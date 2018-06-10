sms-tools-lite
==============
SMS (Spectral Modelling Synthesis) lite repo, only the library without examples, GUI's or notebooks


Original is from MTG: https://github.com/MTG/sms-tools

Sound analysis/synthesis tools for music applications written in python (with a bit of C) plus complementary lecture materials.

How to use
----------

In order to use these tools you have to install python (recommended 3.6) and the following modules: ipython, numpy, matplotlib, scipy, and cython. 

In Ubuntu (which we strongly recommend) in order to install all these modules it is as simple as typing in the Terminal:

<code>$ sudo apt-get install python-dev ipython python-numpy python-matplotlib python-scipy cython</code>

In OSX (which we do not support but that should work) you install these modules by typing in the Terminal:

<code>$ pip install ipython numpy matplotlib scipy cython</code>

then, for using the tools, after downloading the whole package, you need to compile some C functions. For that you should go to the directory <code>software/models/utilFunctions_C</code> and type:</p>

<code>$ python compileModule.py build_ext --inplace </code>

The basic sound analysis/synthesis functions, or models, are in the directory <code>software/models</code>.

License
-------
All the software is distributed with the Affero GPL license (http://www.gnu.org/licenses/agpl-3.0.en.html), the lecture slides are distributed under Creative Commons Attribution-NonCommercial-ShareAlike 4.0 (CC BY-NC-SA 4.0) license (http://creativecommons.org/licenses/by-nc-sa/4.0/) and the sounds in this repository are released under Creative Commons Attribution 4.0 (CC BY 4.0) license (http://creativecommons.org/licenses/by/4.0/)

