# FSSGA: A Genetic Algorithm for Feature Subset Selection

FS2GA is a Wrapper method for FSS using weka classifiers to provide subset classifications.
In this first version the fitness function is composed by the classifier RMSE/(number of features)
The classifier used is J48 (C4.5 implementation) 

A bash script: "compile.sh" is provided to compile and run

Parameters required by the AG are:


generationNumber: GA number of generations: 
crossRate: Crossover rate used in GA in a two-point crossover
mutationRate: GAs mutation Rate along cromossome
tourRate: Tournament selection rate
popSize: Population Size
minFeatures: Initial number of Features
fileName: An Arff File

Instructions for arff preparation can be seen in: https://www.cs.waikato.ac.nz/ml/weka/arff.html

