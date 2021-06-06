These codes are written by me for my paper <a href="https://yukitakahashi1.github.io/files/Correction.pdf" target="_blank">The Cost of Corrections in Group Work</a>.

# Corrections-Gender-Experiment
These are oTree and Python codes used for an experiment on corrections and gender in 2020. Participants were recruited from the Bologna Laboratory for Experiments in Social Science (BLESS)'s ORSEE.

## oTree Codes
The oTree codes are stored in ```proj20200504.otreezip```. To extract them, please type ```otree unzip proj20200504.otreezip``` in the directory where you downloaded the otreezip file. Please note that the puzzle part of the code is based on [Christian König gen. Kersting's code](https://github.com/chkgk/otree_slider_puzzle) and the puzzle was first used by [Siri Isaksson](https://github.com/siriisa/Econ-Puzzle-Experiment).

## Python Codes
The Python codes are stored in ```PythonCodes.zip```. ```AnalyzeHistory.py``` extracts information from the move history recorded by oTree and ```ExpandHistory.py``` summarizes the information for the analysis. ```AnalyzeHistory.py``` requires ```bfs.py``` and ```tiles.py``` (which are based on [this website](http://www.openbookproject.net/py4fun/tiles/tiles.html)) and they must be in the same directory. 

## License
These codes are released under the [MIT license](https://github.com/yukitakahashi1/correction_codes/blob/main/LICENSE).

## Citing the Paper
You are also recommended to cite [Siri Isaksson's paper](https://github.com/siriisa/Econ-Puzzle-Experiment) that first used the puzzle.
```
@misc{cost_corrections,
  author =       {Yuki Takahashi},
  title =        {The Cost of Corrections in Group Work.},
  howpublished = {\url{https://yukitakahashi1.github.io/files/Correction.pdf}},
  year =         {2021}
}
```

## Citing the Source Code
If you use the source code in your research.
```
@misc{correction_codes,
  author =       {Yuki Takahashi, Christian König gen. Kersting, Siri Isaksson},
  title =        {Corrections-Gender-Experiment},
  howpublished = {\url{https://github.com/yukitakahashi1/correction_codes}},
  year =         {2021}
}
```



