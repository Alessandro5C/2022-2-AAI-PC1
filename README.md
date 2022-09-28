# 2022-2-AAI-PC1

See the Jupyter Notebook for details and implemetation

### With Ramdom Sampling

* Timeline of 3 minutes Vs makespan
![image](https://user-images.githubusercontent.com/64936813/192681289-6ad5dc8a-980f-4390-8667-094a8e0449a9.png)

* Gantt Diagram of the best solution obtained in those 3 minutes
![image](https://user-images.githubusercontent.com/64936813/192681370-ce15a93c-4031-4d8c-afb8-ef20c252d9bc.png)

### With Genetics Algorithm (population=128, mutability=15%)

* Timeline of 3 minutes Vs makespan
![image](https://user-images.githubusercontent.com/64936813/192681667-120fc305-9bd0-46a0-b69e-d4638da186d9.png)

* Gantt Diagram of the best solution obtained in those 3 minutes
![image](https://user-images.githubusercontent.com/64936813/192681822-1e18e63a-88a9-4740-8bbc-7db96bd551fc.png)

Conclusions (same as the written in the Jupyter Notebook):
After running the Genetics algorithm with different parameters, it's concluded that Genetics is way better than Random Sampling solutions. This is caused due to the fact that there's no consistency in the Random Sampling implementation as seen in the graph in Part 1. But something to highlight is the fact there has to be good parameters for Genetics to work, as very little population or almost null mutation will cause stagnation in the progress of the function.
