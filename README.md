team_worklog
============

##2014 May

|Component | Link | Description | Status |
| ---------------- |:----------------|:------------------------------|:------------------------------|
|Storm | [STORM-297](https://issues.apache.org/jira/browse/STORM-297) | Storm Performance cannot be scaled up by adding more CPU cores. | A quite big patch, passed code review. |
|HBase | [CSBT](https://github.com/intel-hadoop/CSBT) | Cross site big table | open sourced on GitHub |
|HBase | [MultiRowFilter](https://issues.apache.org/jira/browse/HBASE-11144) | Multi-row fast-forwarding filter | patch submitted to HBase community, working on perf testing |
|HBase | [RollingScan](https://github.com/intel-hadoop/RollingScan) | Rolling Scanner for salted table | open sourced on GitHub |
|HBase | [SaltedTable](https://github.com/intel-hadoop/SaltedHTable) | another salted table implementation | open sourced on GitHub |
|MapReduce | [NativeTask](https://github.com/intel-hadoop/nativetask) | native engine for MapReduce | open sourced on GitHub. Separated collector from native mapper/reducer according to Cloudera feedback. |
|Hive | [Multi-char delimiter](https://issues.apache.org/jira/browse/HIVE-5871) | Multi-char delimiter for Hive | patch submitted to community |
| Pig | [PIG-3944](https://issues.apache.org/jira/browse/PIG-3944) | PigNullableWritable toString method throws NPE on null value | patch committed into trunk | 
| Pig | [PIG-3943](https://issues.apache.org/jira/browse/PIG-3943) | inconsistency between DefaultAbstractBag readFields and write methods | patch submitted | 
