
### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

The following packages are used:

1. `pandas`
2. `numpy`
3. `sklearn`
4. `matplotlib`
5. `math`
6. `zipfile`
7. `datetime`

The code should run with no issues using Python versions 3.*.

## Project Motivation<a name="motivation"></a>

For this project, I was interestested in using data from the openpowerlifting database to answer following questions:

1. Where is powerlifting (outside USA) most popular?
2. How much do the three lifts (squat, benchpress, deadlift) interfere each other?
3. Can you predict the best deadlift attempt with the other two lifts and some additional data?

Especially the last question could be useful in practice for powerlifting athletes, because at meets they have to pick the weight for every attempt carefully to not overshoot or to leave potential.


## File Descriptions <a name="files"></a>

There is one notebook available here to showcase work related to the above questions. The notebook contains parts of data preprocessing, exploratory analysis and predictive analytics. Markdown cells were used to assist in walking through the process and documenting the code.

There is an additional `plots` folder that contains all created plots to obtain the final results of the project. Also the used data as a `.zip` file can be found.

## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://medium.com/@kevinossner/how-much-can-you-deadlift-96f84ca5f3ee?source=friends_link&sk=0c663e94f4865971f505aff0189ce56e).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

This page uses data from the OpenPowerlifting project, https://www.openpowerlifting.org. You may download a copy of the data [here](https://gitlab.com/openpowerlifting/opl-data).
