# Final Project - Reinforcements Learning - Explainer.md
Student 1: Yarden Fogel | yarden.fogel@post.runi.ac.il  
Student 2: Sharon Koubi | sharon.koubi@post.runi.ac.il  

<br>

## Notebook structure:
There are 4 main sections:
1. MUST RUN FIRST
1. Ex1 - Solving Fix scenario of Sokoban
1. EX2 - Solving Random scenario of Sokoban
1. Test Environmet

## How to run (Top-down instructions)
1. **Before you start working with the notebook, you must run all the cells under `MUST RUN FIRST` section**.  
It includes all the function and classes needed for running an experiment and training the models.  
Furthermore, this section holds the Sokoban EnvWrapper with all the bug fixes, reward shaping, etc.  
1. **Running an experiment**- just collapse all the cells under the experiment label and push the gathered cell Run button (or alternatively run all cells under the experiment manually).  
Note that Hyper Parameters section has a `MUST RUN FIRST` section, make sure to run it before running an experiment from this section.  
1. **Videos in the report**- as far as we know, the videos that we created should be be there when you open the notebook.  
If it doesn't the case, they can be loaded and present buy running ONLY cells with `embed_mp4(preserved_video_path(<VIDEO_NAME>))`.  

## TEST environment
At the end of the notebook, just run all the cells under the header (don't forget to run its `MUST RUN FIRST` section).  
