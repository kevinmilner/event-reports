# 5.81, 18km SSE of Lone Pine, CA

## Table Of Contents

* [Mainshock Details](#mainshock-details)
  * [USGS Products](#usgs-products)
  * [Nearby Faults](#nearby-faults)
* [Sequence Details](#sequence-details)
  * [Magnitude Vs. Time Plot](#magnitude-vs-time-plot)
  * [Aftershock Locations](#aftershock-locations)
  * [Cumulative Number Plot](#cumulative-number-plot)
  * [Magnitude-Number Distributions (MNDs)](#magnitude-number-distributions-mnds)
* [UCERF3-ETAS Forecast](#ucerf3-etas-forecast)
  * [ETAS Forecasted Magnitude Vs. Time](#etas-forecasted-magnitude-vs-time)
  * [ETAS Spatial Distribution Forecast](#etas-spatial-distribution-forecast)
  * [ETAS Fault Trigger Probabilities](#etas-fault-trigger-probabilities)

## Mainshock Details
*[(top)](#table-of-contents)*

Information and plots in the section are taken from the [USGS event page](https://earthquake.usgs.gov/earthquakes/eventpage/ci39493944), accessed through ComCat.

| Field | Value |
|-----|-----|
| Magnitude | 5.81 (mw) |
| Time (UTC) | Wed, 24 Jun 2020 17:40:49 UTC |
| Time (PDT) | Wed, 24 Jun 2020 10:40:49 PDT |
| Location | 36.446835, -117.97517 |
| Depth | 4.66 km |
| Status | reviewed |

### USGS Products
*[(top)](#table-of-contents)*

| <center>**[ShakeMap](https://earthquake.usgs.gov/earthquakes/eventpage/ci39493944/shakemap/)**</center> | <center>**[Did You Feel It?](https://earthquake.usgs.gov/earthquakes/eventpage/ci39493944/dyfi/)**</center> |
|-----|-----|
| ![ShakeMap](resources/ci39493944_shakemap.jpg) | ![DYFI](resources/ci39493944_dyfi.jpg) |
| <center>**[PAGER](https://earthquake.usgs.gov/earthquakes/eventpage/ci39493944/pager/)**</center> | <center>**[Moment Tensor](https://earthquake.usgs.gov/earthquakes/eventpage/ci39493944/moment-tensor/)**</center> |
| ![PEGER](resources/ci39493944_pager.png) | ![Mechanism](resources/ci39493944_mechanism.jpg) |

### Nearby Faults
*[(top)](#table-of-contents)*


3 UCERF3 fault sections are within 10km of this event's hypocenter:

* Sierra Nevada  (No Extension): 2.08km
* Owens Valley: 2.55km
* Independence rev 2011: 9.97km
## Sequence Details
*[(top)](#table-of-contents)*

These plots show the aftershock sequence, using data sourced from [ComCat](https://earthquake.usgs.gov/data/comcat/). They were last updated at 2020/06/24 22:39:31 UTC, 4.98 hours after the mainshock.

44 M&ge;2 earthquakes within 30 km of the mainshock's epicenter.


|  | First Hour | To Date |
|-----|-----|-----|
| **M 2** | 29 | 44 |
| **M 3** | 5 | 7 |
| **M 4** | 1 | 1 |
### Magnitude Vs. Time Plot
*[(top)](#table-of-contents)*

This plot shows the magnitude vs. time evolution of the sequence. The mainshock is ploted as a brown circle, foreshocks are plotted as magenta circles, and aftershocks are plotted as cyan circles.

![Mag vs Time Plot](resources/aftershocks_mag_vs_time.png)

### Aftershock Locations
*[(top)](#table-of-contents)*

Map view of the aftershock sequence, plotted as cyan circles. The mainshock  and foreshocks are plotted below in brown and magenta circles respectively, but may be obscured by aftershocks. Nearby UCERF3 fault traces are plotted in gray lines, and the region used to fetch aftershock data in a dashed dark gray line.

![First Day](resources/map_to_date.png)

### Cumulative Number Plot
*[(top)](#table-of-contents)*

This plot shows the cumulative number of M&ge;2 aftershocks as a function of time since the mainshock.

![Time Func](resources/aftershocks_vs_time.png)

### Magnitude-Number Distributions (MNDs)
*[(top)](#table-of-contents)*

These plot shows the magnitude-number distribution of the aftershock sequence thus far. The left plot gives an incremental distribution (the count in each magnitude bin), and the right plot a cumulative distribution (the count in or above each magnitude bin).

| Incremental MND | Cumulative MND |
|-----|-----|
| ![Incremental](resources/aftershocks_mag_num_incremental.png) | ![Cumulative](resources/aftershocks_mag_num_cumulative.png) |

## UCERF3-ETAS Forecast
*[(top)](#table-of-contents)*

This section gives results from the UCERF3-ETAS short-term forecasting model. This model is described in [Field et al. (2017)](http://bssa.geoscienceworld.org/lookup/doi/10.1785/0120160173), and computes probabilities of this sequence triggering subsequent aftershocks, including events on known faults.

Probabilities are inherantly time-dependent. Those stated here are for time periods beginning the instant when this report was generated, 2020/06/24 15:39:31 PDT. The model has not been updated with any observed aftershocks and may be out of date, especially if large aftershock have occurred subsequently or a significant amount of time has passed since the mainshock.

Results are summarized below and should be considered preliminary. The exact timing, size, location, or number of aftershocks cannot be predicted, and all probabilities are uncertain.


This table gives forecasted one week and one month probabilities for events triggered by this sequence; it does not include the long-term probability of such events.

|  | 1 Week | 1 Month |
|-----|-----|-----|
| **M&ge;3** | 99.999% | 100.000% |
| **M&ge;4** | 73.103% | 83.627% |
| **M&ge;5** | 13.581% | 18.438% |
| **M&ge;6** | 1.146% | 1.613% |
| **M&ge;7** | 0.021% | 0.033% |
| **M&ge;8** | <0.001% | <0.001% |

### ETAS Forecasted Magnitude Vs. Time
*[(top)](#table-of-contents)*

These plots show the show the magnitude versus time probability function since simulation start. Observed event data lie on top, with those input to the simulation plotted as magenta circles and those that occurred after the simulation start time as cyan circles. Time is relative to the mainshock (M5.81, ci39493944, plotted as a brown circle). Probabilities are only shown above the minimum simulated magnitude, M=2.5.

| One Week | One Month |
|-----|-----|
| ![Mag-time plot](resources/mag_time_week.png) | ![Mag-time plot](resources/mag_time_month.png) |

### ETAS Spatial Distribution Forecast
*[(top)](#table-of-contents)*

These plots show the predicted spatial distribution of aftershocks above the given magnitude threshold and for the given time period. The 'Current' plot shows the forecasted spatial distribution to date, along with as any observed aftershocks overlaid with cyan circles. Observed aftershocks will be included in the week/month plots as well if the forecasted time window has elapsed.

|  | Forecast: 1 Week | Forecast: 1 Month |
|-----|-----|-----|
| **M&ge;3** | ![Map](resources/comcat_compare_prob_1wk_m3.png) | ![Map](resources/comcat_compare_prob_1mo_m3.png) |
| **M&ge;5** | ![Map](resources/comcat_compare_prob_1wk_m5.png) | ![Map](resources/comcat_compare_prob_1mo_m5.png) |

### ETAS Fault Trigger Probabilities
*[(top)](#table-of-contents)*

The table below summarizes the probabilities of this sequence triggering large supra-seismogenic aftershocks on nearby known active faults.

| Fault Section | 1 wk supra-seis prob | 1 mo supra-seis prob | 1 wk M&ge;7 prob | 1 mo M&ge;7 prob |
|-----|-----|-----|-----|-----|
| **Sierra Nevada  (No Extension)** | 0.524% | 0.760% | 0.015% | 0.021% |
| **Owens Valley** | 0.023% | 0.041% | 0.001% | 0.005% |
| **Hunter Mountain-Saline Valley** | 0.016% | 0.023% | 0.002% | 0.003% |
| **Independence rev 2011** | 0.022% | 0.033% | 0.016% | 0.023% |
| **Ash Hill** | 0.006% | 0.007% | <0.001% | <0.001% |
| **Panamint Valley** | 0.002% | 0.003% | 0.001% | 0.002% |
| **Owl Lake** | 0.001% | 0.003% | <0.001% | <0.001% |
| **Tank Canyon** | <0.001% | 0.001% | <0.001% | <0.001% |
| **So Sierra Nevada** | 0.001% | 0.002% | 0.001% | 0.002% |
| **Kern Canyon (North Kern) 2011** | 0.001% | 0.001% | <0.001% | <0.001% |
