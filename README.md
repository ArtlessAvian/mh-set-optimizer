# Monster Hunter Set Optimizer
Efficiently finds the optimal armor set matching user set armor skills and constraints.
Also efficiently finds all interesting supersets of skills.

"Optimal" by default means maximizing defense, but can be redefined to anything, eg:
* Maximizing random weights, to create any set that meets constraints.
* Minimizing "distance" to existing set, to gradually move towards a better set.
* Minimizing rarity/cost, to build set as early as possible.

Application of (Integer) Linear Programming to Monster Hunter!

## Usage
Open in Google Colab at https://colab.research.google.com/github/ArtlessAvian/monhun-set-optimizer

To keep your edits, find `File > Save a copy in Drive` in the context menu. You can keep using/editing your copy without copying again.

## TODO
Move away from Jupyter Notebooks (and Google Colab) and run in browser as a github.io page. 

## MHW
Data sourced from [gatheringhallstudios/MHWorldData](https://github.com/gatheringhallstudios/MHWorldData).
