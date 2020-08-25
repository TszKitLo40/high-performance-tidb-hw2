# High Performance tidb hw2
## Deployment
The experiment is conducted with Tencent cloud cvm, the deployment is listed in the following form.
|component       |hardware                       |number                        
|----------------|-------------------------------|-----------------------------|
|tidb            |8core, 16G SAS                 |1                            |
|pd.             |8core, 16G SAS                 |1 (deployed with tidb server)|
|tikv            |8core, 32G SSD                 |3                            |
I just use the default config of to run the tidb cluster with the tiup tool.

## Experiment
### sysbench
