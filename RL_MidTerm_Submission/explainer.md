# Mid-semester assignment - Reinforcements Learning - Explainer.md
Student 1: Yarden Fogel | yarden.fogel@post.runi.ac.il  
Student 2: Sharon Koubi | sharon.koubi@post.runi.ac.il  

<br>

## Notebook structure:
There are 4 main sections:
1. MUST RUN FIRST
1. Ex1 - Solving 5x5 Maze with DP
1. EX2 - Solving 15x15 Maze with [ MC | SARSA | Q-Learning ]
1. EX3

## How to run (Top-down instructions)
1. **Before you start working with the notebook, you must run all the cells under `MUST RUN FIRST` section**.  
It includes all the function and classes needed for running an experiment and training the models.  
Furthermore, this section holds the Maze env objects, that we create only once in order to deal with the common bug that the environment failed to render sometimes.  
In order to see how we dealt with this bug, see the `Environment Failed Workaround` section.
1. Running an experiment- each **exercise** has its own `Preparation (run first)`- this section must be run before you're running an experiment under this **exercise**.  
After that, you can run every experiment (from its beginning) and it will run smoothly.
1. Videos in the report- as far as we know, the videos that we created should be be there when you open the notebook.  
If it doesn't the case, they can be loaded buy running the cell with the path of the video, and after that the cell that presents the video.  
We saved those videos and they are downloaded at the beginning of `MUST RUN FIRST`.


## Known Issues
We did everything in order to run the notebook fast in a stable way. It should be very easy to use.  
The only issue we tackled was when _stopping a cell while it renders a video_- for some reason it breaks the Maze Env. In such a case, reconnect to the runtime and start from [How to run (Top-down instructions)](##How-to-run-(Top-down-instructions)).
