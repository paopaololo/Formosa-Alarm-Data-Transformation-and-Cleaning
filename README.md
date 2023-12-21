The SQL queries from Client's control system data is not suitable to be imported into SILalarm, the alarm data management software. 

The main objectives for this python script is to:
1. Transform each row from the query (with alarm setpoint) into separate alarms. If the alarm setpoint is null, an empty alarm will be created.
2. Align all the field names with the import format of SILalarm.
