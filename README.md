# Stream-reasoning-model-for-human-activity-analysis
This model is created usin LARS frameork , a Logic based frameork for Analysis Reasoning over data Streams created by [Harald Beck](https://github.com/hbeck/ticker)
LARS is used here to create a rule-based model for reasoning over human activity streams.
# Requirments 
- Requires Scala 2.12.2 or higher
- Building should be done by using SBT (Scala Built Tools) with version 0.13 or higher.
- Intellij IDEA

# Execution
To execute our stream reasoning model: sbt "run --program src/test/resources/program.lars"

