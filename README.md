Data files for public instances of the _tactical resource allocation problem_ (TRAP). For more information contact anstr@chalmers.se, sunney@chalmers.se. For using these instances, you should cite
`Fotedar,S., Strömberg,A.-B., Almgren,T. Bi-objective optimization of the tactical allocation of job types to machines. Mathematical modelling, theoretical analysis, and numerical tests.`

# Constant_data
Number of time periods is 16 for all instances.
 <img src="https://render.githubusercontent.com/render/math?math=\mathcal{N}_{j}">
Following sets can be obtained from Constant_data:

<img src="https://render.githubusercontent.com/render/math?math=\mathcal{J}">:Set of Job Types 
<img src="https://render.githubusercontent.com/render/math?math=\mathcal{N}_{j}">:Set of machines capable, but not qualified for a job j

 
 
## How to use (Constant_data)
'#'-mark is a comment and describes the data that follows.Following are the sets described in Constant_data file:

1. JobTypes: set of job types to be performed
2. FeasibleMachines: is the set of machines that are capable of performing a give job type. For instance, on line 4: 1,1,2,3,4,5,6,7,..., implies that job type 1 can be performed on machines 1,2,3,4,.....
4. NotQualifiedMachines: is the set of machines that are capable but not qualified to perform a job type, on line 1040: 2,14,43,46,48,51,52,... implies that job type 2 is not qualified for machines 14,43,..

# Instances
Instance file are named as a combination of instance number and whether a new product is included('1y') or not ('1n'). Following are the details on the instances:

| FileName | Skewness |Distribution | Demand Scenario |
| ------ | ------ | ------ | ------ |
| 1y | skew+ | Left | J15 |
| 2y | skew- | Left| J15 |
| 3y | skew0 | Left| J15 |
| 4y | skew+ | Right | J15 |
| 5y | skew- | Right| J15 |
| 6y | skew0 | Right| J15 |
| 7y | skew+ | Uniform | J15 |
| 8y | skew- | Uniform| J15 |
| 9y | skew0 | Uniform| J15 |
| 10y | skew+ | Symmetric | J15 |
| 11y | skew- | Symmetric| J15 |
| 12y | skew0 | Symmetric| J15 |
| 13y | skew+ | Bimodal| J15 |
| 14y | skew- | Bimodal| J15 |
| 15y | skew0 | Bimodal| J15 |
| 16y | skew+ | Left | D15 |
| 17y | skew- | Left| D15 |
| 18y | skew0 | Left| D15 |
| 19y | skew+ | Right | D15 |
| 20y | skew- | Right| D15 |
| 21y | skew0 | Right| D15 |
| 22y | skew+ | Uniform | D15 |
| 23y | skew- | Uniform| D15 |
| 24y | skew0 | Uniform| D15 |
| 25y | skew+ | Symmetric | D15 |
| 26y | skew- | Symmetric| D15 |
| 27y | skew0 | Symmetric| D15 |
| 28y | skew+ | Bimodal| D15 |
| 29y | skew- | Bimodal| D15 |
| 30y | skew0 | Bimodal| D15 |
| 1n | skew+ | Left | J15 |
| 2n | skew- | Left| J15 |
| 3n | skew0 | Left| J15 |
| 4n | skew+ | Right | J15 |
| 5n | skew- | Right| J15 |
| 6n | skew0 | Right| J15 |
| 7n | skew+ | Uniform | J15 |
| 8n | skew- | Uniform| J15 |
| 9n | skew0 | Uniform| J15 |
| 10n | skew+ | Symmetric | J15 |
| 11n | skew- | Symmetric| J15 |
| 12n | skew0 | Symmetric| J15 |
| 13n | skew+ | Bimodal| J15 |
| 14n | skew- | Bimodal| J15 |
| 15n | skew0 | Bimodal| J15 |
| 16n | skew+ | Left | D15 |
| 17n | skew- | Left| D15 |
| 18n | skew0 | Left| D15 |
| 19n | skew+ | Right | D15 |
| 20n | skew- | Right| D15 |
| 21n | skew0 | Right| D15 |
| 22n | skew+ | Uniform | D15 |
| 23n | skew- | Uniform| D15 |
| 24n | skew0 | Uniform| D15 |
| 25n | skew+ | Symmetric | D15 |
| 26n | skew- | Symmetric| D15 |
| 27n | skew0 | Symmetric| D15 |
| 28n | skew+ | Bimodal| D15 |
| 29n | skew- | Bimodal| D15 |
| 30n | skew0 | Bimodal| D15 |
