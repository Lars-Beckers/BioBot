Most of this intial code was created in parallel to this project: https://github.com/aarontenzing/Maairobot

- model.ipynb: takes frames from dataset created by samples.ipynb, runs these frames through pretrained models to extract features from them (without final layer, meaning no classification) and are then being visualized in 2D graph
- plantnet300K_species_names.json: contains all classes names of plantnet and is currently not being used
- requirements.txt: contains necessary (and some extra) libraries for .venv of visual studio code on Windows
- samples.ipynb: input video provided by Prof. T. Goedemé is being sliced in different frames containing gras, leaves, clover, stones, ...
