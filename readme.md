This repository holds the code used to run the experiments presented in the article *[Autonomous Reuse of Motor Exploration Trajectories](http://fabien.benureau.com)*.

Using this code, you can reproduce the graphs presented in the article from scratch, and examine any and all of the way they were produced.

It is not intended as being fit for any purpose other than scientific.  

### OpenScience License

This software is placed under the [OpenScience license](http://fabien.benureau.com/openscience.html), which is the LGPL, with the additional condition that if you publish scientific results using this code, you have to publish the corresponding modifications of the code.

> If you publicly release any scientific claims or data that were supported or generated by the Program or a modification thereof, in whole or in part, you will release any modifications you made to the Program. This License will be in effect for the modified program. 

## Installation

1. Install pypubsub, scipy, treedict, cython, pandas and [eigen](http://eigen.tuxfamily.org/index.php?title=Main_Page).
`pip install pypubsub scipy treedict cython pandas`
1. Get the code
1. Install

## Usage

1. Get the code
2. Edit paths in file `explib/run/paths.py` to suit your folder structure, and create each of the listed folde
3. Go to `exp/l2l`
4. Run `l2l_missing.py -r`. This will generate and display the file `missing.sh`. Assume  

Although some care has been taken to make the code usable, it might not be. Don't hesitate to submit an issue or make a pull request.
