# 5.08, 7 km SE of Ojai, CA

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

Information and plots in the section are taken from the [USGS event page](https://earthquake.usgs.gov/earthquakes/eventpage/ci39645386), accessed through ComCat.

| Field | Value |
|-----|-----|
| Magnitude | 5.08 (mw) |
| Time (UTC) | Sun, 20 Aug 2023 21:41:00 UTC |
| Time (PDT) | Sun, 20 Aug 2023 14:41:00 PDT |
| Location | 34.4085, -119.18833 |
| Depth | 4.84 km |
| Status | reviewed |

### USGS Products
*[(top)](#table-of-contents)*

| <center>**[ShakeMap](https://earthquake.usgs.gov/earthquakes/eventpage/ci39645386/shakemap/)**</center> | <center>**[Did You Feel It?](https://earthquake.usgs.gov/earthquakes/eventpage/ci39645386/dyfi/)**</center> |
|-----|-----|
| ![ShakeMap](resources/ci39645386_shakemap.jpg) | ![DYFI](resources/ci39645386_dyfi.jpg) |
| <center>**[PAGER](https://earthquake.usgs.gov/earthquakes/eventpage/ci39645386/pager/)**</center> | <center>**[Moment Tensor](https://earthquake.usgs.gov/earthquakes/eventpage/ci39645386/moment-tensor/)**</center> |
| ![PEGER](resources/ci39645386_pager.png) | ![Mechanism](resources/ci39645386_mechanism.jpg) |

### Nearby Faults
*[(top)](#table-of-contents)*


4 UCERF3 fault sections are within 10km of this event's hypocenter:

* Mission Ridge-Arroyo Parida-Santa Ana: 2.94km
* Sisar: 3.83km
* San Cayetano: 7.21km
* Ventura-Pitas Point: 7.71km
## Sequence Details
*[(top)](#table-of-contents)*

These plots show the aftershock sequence, using data sourced from [ComCat](https://earthquake.usgs.gov/data/comcat/). They were last updated at 2023/08/22 19:17:14 UTC, 45.6 hours after the mainshock.

153 M&ge;0 earthquakes within 50 km of the mainshock's epicenter.


|  | First Hour | First Day | To Date |
|-----|-----|-----|-----|
| **M 0** | 41 | 125 | 153 |
| **M 1** | 41 | 124 | 151 |
| **M 2** | 22 | 49 | 55 |
| **M 3** | 6 | 10 | 12 |
### Magnitude Vs. Time Plot
*[(top)](#table-of-contents)*

This plot shows the magnitude vs. time evolution of the sequence. The mainshock is ploted as a brown circle, foreshocks are plotted as magenta circles, and aftershocks are plotted as cyan circles.

![Mag vs Time Plot](resources/aftershocks_mag_vs_time.png)

### Aftershock Locations
*[(top)](#table-of-contents)*

Map view of the aftershock sequence, plotted as cyan circles. The mainshock  and foreshocks are plotted below in brown and magenta circles respectively, but may be obscured by aftershocks. Nearby UCERF3 fault traces are plotted in gray lines, and the region used to fetch aftershock data in a dashed dark gray line.

| First Day | To Date |
|-----|-----|
| ![First Day](resources/map_first_day.png) | ![First Day](resources/map_to_date.png) |

### Cumulative Number Plot
*[(top)](#table-of-contents)*

This plot shows the cumulative number of M&ge;0 aftershocks as a function of time since the mainshock.

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

Probabilities are inherantly time-dependent. Those stated here are for time periods beginning the instant when this report was generated, 2023/08/22 12:17:14 PDT. The model was updated with all observed aftershcoks up to 1.8 days after the mainshock, and may be out of date, especially if large aftershocks have occurred subsequently or a significant amount of time has passed since the last update.

Results are summarized below and should be considered preliminary. The exact timing, size, location, or number of aftershocks cannot be predicted, and all probabilities are uncertain.


This table gives forecasted one week and one month probabilities for events triggered by this sequence; it does not include the long-term probability of such events.

|  | 1 Week | 1 Month |
|-----|-----|-----|
| **M&ge;3** | 68.619% | 86.344% |
| **M&ge;4** | 11.866% | 19.743% |
| **M&ge;5** | 1.336% | 2.342% |
| **M&ge;6** | 0.094% | 0.185% |
| **M&ge;7** | 0.012% | 0.024% |
| **M&ge;8** | <0.001% | <0.001% |

### ETAS Forecasted Magnitude Vs. Time
*[(top)](#table-of-contents)*

These plots show the show the magnitude versus time probability function since simulation start. Observed event data lie on top, with those input to the simulation plotted as magenta circles and those that occurred after the simulation start time as cyan circles. Time is relative to the mainshock (M5.08, ci39645386, plotted as a brown circle). Probabilities are only shown above the minimum simulated magnitude, M=2.5.

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
| **Mission Ridge-Arroyo Parida-Santa Ana** | 0.025% | 0.045% | 0.008% | 0.013% |
| **Ventura-Pitas Point** | 0.009% | 0.026% | 0.001% | 0.006% |
| **Santa Ynez (East)** | 0.008% | 0.017% | 0.002% | 0.006% |
| **San Cayetano** | 0.011% | 0.017% | 0.007% | 0.012% |
| **Red Mountain** | 0.006% | 0.012% | 0.005% | 0.007% |
| **Santa Ynez (West)** | 0.003% | 0.007% | 0.002% | 0.004% |
| **Oak Ridge (Onshore)** | 0.002% | 0.007% | 0.002% | 0.007% |
| **Sisar** | 0.002% | 0.009% | 0.002% | 0.009% |
| **Pitas Point (Lower West)** | 0.003% | 0.005% | 0.003% | 0.005% |
| **Santa Ynez River** | <0.001% | 0.001% | <0.001% | 0.001% |
