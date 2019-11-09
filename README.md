# Open-Pete-Baseline
Baseline repository of Open-Pete

<pre>
Open-Pete
|____||||_____ An <b>open</b> source implementation of an
     ||||_____ <b>P</b>leasant and 
      |||_____ <b>E</b>xtraodinary pretty 
       ||_____ <b>T</b>ravel-assistent who keeps your ride save, cozy and 
        |_____ <b>E</b>ntertaining
</pre>   

# Feature-Plan

## v0.1.0 Startup, show data from Influx-DB

- [x] Bring DateTime++ to version 1.0.0
- [x] Integrate DateTime++ into DBInterface
- [x] Rename DBInterface to CPP2InfluxDB
- [x] Release first version of CPP2InfluxDB in Open-Pete organization
- [x] Setup repo Sensor++
- [x] Create Dummy-Sensor class which reads dummy values
- [ ] Bring Sensor++ to version v1.2.0 (Dummy Implementation of 5-10 sensors)
- [x] Setup repo DataLogger
- [ ] Bring DataLogger to version 1.0.0 which writes Dummy-Data into Influx-DB
- [x] create initial Open-Pete-UI
- [ ] Display Influx-DB values in Open-Pete-UI
- [ ] Integrate Open-Pete-UI, DataLogger, CPP2InfluxDB, Sensor++ and DateTime++ into Open-Pete-Baseline

## v0.2.0 
- [ ] Display real sensor data from at least one sensor in Open-Pete-UI
- [ ] Try to integrate embedded grafana into UI

## v0.3.0
- [ ] Make Open-Pete-UI generic / support several sub-programs
