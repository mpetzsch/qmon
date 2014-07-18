qmon
====
a framework for monitoring q processes, focussed on tick and real-time data monitoring

### .mon.proc
functions to run on remote processes for process level monitoring

- .mon.proc.memLimit
check % distance from wslimit

###.mon.tp
functions to handle incoming ticks and monitor realtime feeds via the tickerplant
- .mon.tp.tableTick
check last tick time for a table
###.mon.tp.tableSymTick
check last tick time for a sym on a table
###.mon.tp.tableLatency
check max latency on a table
###.mon.tp.tableSymLatency
check max latency on a sym on a table
###.mon.tp.outputQueue
check output queue depth

#.mon.rdb
rdb specific monitoring

###.mon.rdb.tableLatency
check percentile latency on a table
###.mon.rdb.tableSymLatency
check percentile latency on sym a table
###.mon.rdb.sym
check sym variable is present and correct
###.mon.rdb.attrs
check table attributes are present and correct

#.mon.hdb
hdb specific monitoring

###.mon.hdb.symOk
check sym variable is present and correct
###.mon.hdb.dateOk
check date variable is present and correct
###.mon.hdb.attrs
check table attributes are present and correct
