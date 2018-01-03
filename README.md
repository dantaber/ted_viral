# Predicting which TED talks go viral

This repository contains files related to a project on how TED speakers' storytelling style predicts whether their talks go viral. Transcripts were obtained [here](https://data.world/owentemple/ted-talks-complete-list) (kudos to Owen Temple for making them available!) 

The NLP file includes text preprocessing, feature engineering, sentiment analysis, and more. [k-Shape](https://github.com/Mic92/kshape), a time series clustering algorithm, was used to determine the story "shape" of each talk.

To model virality, I adapted a study - ["Can cascades be predicted?"](https://www.cs.cornell.edu/home/kleinber/www14-cascades.pdf) - by scientists at Stanford, Facebook, and Cornell.