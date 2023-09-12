# Stream-reasoning-model-for-human-activity-analysis
This stream reasoning model uses LARS, a Logic based framework for Analytic Reasoning over data Streams created by [Harald Beck]: https://github.com/hbeck/ticker
We apply this framework in a new domain , the human activity analysis for the detection of medication risks 
# Requirments 
- Requires Scala 2.12.2 or higher
- Building should be done by using SBT (Scala Built Tools) with version 0.13 or higher.
- Intellij IDEA

# Execution
To execute our stream reasoning model: sbt "run --program src/test/resources/program.lars"

