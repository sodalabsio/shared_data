# IP Observatory | Open
_Open sourced data from the Monash University IP Observatory **@IP_Observatory** (https://ip-observatory.org), by Monash Business School's Soda Laboratories (https://sodalabs.io)_

_Data curator: simon.angus@monash.edu_

## INDEX

### 3: `usa-2020-08-29_HurrLaura.csv`
Data on ICT connectivity impact of Hurricane Laura as given in: [Real-time Mapping of Hurricane Laura’s Impact on Internet Infrastructure](https://medium.com/insights-monash-university-ip-observatory/real-time-mapping-of-hurricane-lauras-impact-on-internet-infrastructure-9584162885ab), Insights@ Monash IP Observatory, 28 Aug 2020.

Data up to timestamp: 2020-Aug-28 16:00 CDT
 * Number of unique provinces (states) (`name_1`): 4
 * Number of unique counties (`name_2`): 200
 * Temporal range: `24-Aug-2020 00:00:00` to `28-Aug-2020 21:00:00`  UTC
 * Atomic temporal aggregation: hourly
 * Atomic spatial aggregation: counties
 * Records: 25,488
 
#### Data descriptor:
Format: `<col-name>: <details> [<example>]`
```
time_e_utc
time_e_utc_str
connectivity: index on 0 (effectively offline) .. 10 (normal) to indicate level of internet activity in that location [10]
iso: 3 char country code [USA]
name_1: state name [Louisiana]
name_2: county name [Acadia]
lat: county latitude centroid location [30.227608]
lon: county longitude centroid location [-92.490875]
(25488 records)
```

### 2: `irn-2019-11-11_gif.csv`
Data behind GIF as found in blog post: [Deep-Diving Through Iran’s Internet Blackout](https://medium.com/insights-monash-university-ip-observatory/deep-diving-through-irans-internet-blackout-b72034668028), Insights@ Monash IP Observatory, 20 Nov 2019.
 * Number of unique provinces (states) (`name_1`): 30
 * Number of unique counties (`name_2`): 73
 * Temporal range: `11-Nov-2019 00:00` to `20-Nov-2019 06:00`
 * Atomic temporal aggregation: hourly
 * Atomic spatial aggregation: counties
 * Records: 16,279

#### Data descriptor:
Format: `<col-name>: <details> [<example>]`
```
iso: 3 char country code [IRN]
id_1: province identifier [1]
name_1: province name [Ardebil]
time_e: timestamp, Epoch format, but in local time (for Kepler.gl) [1573430400]
time_e_str: timestamp string [11-Nov-2019 00:00:00]
lat: county latitude centroid location [38.435]
lon: county longitude centroid location [48.335]
connectivity: index on 0 (effectively offline) .. 100 (normal) to indicate level of internet activity in that location [100]
(16279 records)
```

### 1: `ven-2019-07-22_gif.csv`
Data behind GIF as found in blog post: [Maduro’s Land of Darkness Redux: Documenting A(nother) National Crisis with Remote, Alternative Data](https://medium.com/insights-monash-university-ip-observatory/maduros-land-of-darkness-redux-documenting-a-nother-national-crisis-with-remote-alternative-8218e4492aa6), Insights@ Monash IP Observatory, 26 July 2019.

#### Data descriptor:
Format: `<col-name>: <details> [<example>]`
```
iso: 3 char country code [VEN]
id_1: state identifier [2]
name_1: state name [Anzoátegui]
time_e: timestamp, Epoch format, but in local time (for Kepler.gl) [1563580800]
time_e_str: timestamp string [20-Jul-2019 00:00:00]
lat: state latitude centroid location [10.1061147498108]
lon: state longitude centroid location [-64.7334323737705]
connectivity: index on 0 (effectively offline) .. 100 (normal) to indicate level of internet activity in that location [100]
(1469 records)
```

