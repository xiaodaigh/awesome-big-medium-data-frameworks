# awesome-big-medium-data-frameworks
Not sure if they are awesome, but listing them anyway

## Tools

| Name                                                                                                                | Language                              | Classification                                   | Comment                                                                   |
|---------------------------------------------------------------------------------------------------------------------|---------------------------------------|--------------------------------------------------|---------------------------------------------------------------------------|
| [Intel® Scalable Dataframe Compiler](https://github.com/IntelPython/sdc)                                            | Python                                | Big                                              | claims to "orders of magnitute faster than alternatives like Apache Spark |
| [Spark](https://spark.apache.org)                                                                                   | Scala (Main), Python, R, Julia (weak) | Big                                              | De facto industry standard. Basically killed Hadoop                       |
| [Dask](https://dask.org)                                                                                            | Python                                | Medium/Big                                       |                                                                           |
| [disk.frame](https://diskframe.com)                                                                                 | R                                     | Medium                                           | soft deprecated                                                           |
| [Husky](http://www.husky-project.com/)                                                                              | C++, Scala (weaker), Python (weaker)  | Medium?/Big                                      |                                                                           |
| [JuliaDB.jl](http://juliadb.org/)                                                                                   | Julia                                 | Medium/Big                                       | Can't get it to work for me on the Fannie Mae data                        |
| [DataFusion](https://github.com/apache/arrow-datafusion)                                                            | Rust                                  | Big                                              | Apache Arrow DataFusion and Ballista query engines                        |
| [ballista](https://github.com/ballista-compute/ballista)                                                            | Rust                                  | Big                                              | Spark but in Rust                                                         |
| [vega](https://github.com/rajasekarv/vega)                                                                          | Rust                                  | Big                                              | Another Spark killer in Rust                                              |
| [vaex](https://www.google.com/search?q=vaex&oq=vaex&aqs=chrome.0.69i59l3j69i60l4.2540j0j7&sourceid=chrome&ie=UTF-8) | Python                                | Medium/Big                                       |                                                                           |
| [tuplex](https://tuplex.cs.brown.edu/)                                                                              | Python                                | Medium/Big                                       | Compiles a subset of Python to machine code if possible.                  |
| [nebula](https://github.com/varchar-io/nebula)                                                                      | Medium/Big?                           | seems to be Javascript based                     |                                                                           |
| [arrow](https://arrow.apache.org/)                                                                                  | Medium                                | Has a Dataset API in some implementations e.g. R |                                                                           |


## File Formats

| Name | Notes |
| -- | -- |
| [ROOT](https://indico.cern.ch/event/567550/contributions/2628878/attachments/1511966/2358123/hep-file-formats.pdf) | |

## Resources

[Quora: What are some credible Apache Spark killers out there? What are their chances of success?](https://www.quora.com/unanswered/What-are-some-credible-Apache-Spark-killers-out-there-What-are-their-chances-of-success)
