# 3.87, 10 km NW of Malibu, CA

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

Information and plots in the section are taken from the [USGS event page](https://earthquake.usgs.gov/earthquakes/eventpage/ci41081408), accessed through ComCat.

| Field | Value |
|-----|-----|
| Magnitude | 3.87 (mw) |
| Time (UTC) | Mon, 17 Mar 2025 03:17:21 UTC |
| Time (CDT) | Sun, 16 Mar 2025 22:17:21 CDT |
| Location | 34.0635, -118.895836 |
| Depth | 11.79 km |
| Status | reviewed |

### USGS Products
*[(top)](#table-of-contents)*

| <center>**[ShakeMap](https://earthquake.usgs.gov/earthquakes/eventpage/ci41081408/shakemap/)**</center> | <center>**[Did You Feel It?](https://earthquake.usgs.gov/earthquakes/eventpage/ci41081408/dyfi/)**</center> | <center>**[Moment Tensor](https://earthquake.usgs.gov/earthquakes/eventpage/ci41081408/moment-tensor/)**</center> |
|-----|-----|-----|
| ![ShakeMap](resources/ci41081408_shakemap.jpg) | ![DYFI](resources/ci41081408_dyfi.jpg) | ![Mechanism](resources/ci41081408_mechanism.jpg) |

### Nearby Faults
*[(top)](#table-of-contents)*


6 UCERF3 fault sections are within 10km of this event's hypocenter:

* Anacapa-Dume alt 2: 0.37km
* Anacapa-Dume alt 1: 0.57km
* Malibu Coast alt 2: 1.12km
* Malibu Coast (Extension) alt 2: 3.59km
* Malibu Coast alt 1: 4.1km
* Malibu Coast (Extension) alt 1: 5.27km
## Sequence Details
*[(top)](#table-of-contents)*

These plots show the aftershock sequence, using data sourced from [ComCat](https://earthquake.usgs.gov/data/comcat/). They were last updated at 2025/03/18 21:06:11 UTC, 41.81 hours after the mainshock.

10 M&ge;0 earthquakes within 50 km of the mainshock's epicenter.


|  | First Hour | First Day | To Date |
|-----|-----|-----|-----|
| **M 0** | 2 | 8 | 10 |
| **M 1** | 2 | 8 | 10 |
| **M 2** | 1 | 1 | 1 |
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

Probabilities are inherantly time-dependent. Those stated here are for time periods beginning the instant when this report was generated, 2025/03/18 16:06:11 CDT. The model has not been updated with any observed aftershocks and may be out of date, especially if large aftershock have occurred subsequently or a significant amount of time has passed since the mainshock.

Results are summarized below and should be considered preliminary. The exact timing, size, location, or number of aftershocks cannot be predicted, and all probabilities are uncertain.


This table gives forecasted one week and one month probabilities for events triggered by this sequence; it does not include the long-term probability of such events.

|  | 1 Week | 1 Month |
|-----|-----|-----|
| **M&ge;3** | 6.319% | 10.754% |
| **M&ge;4** | 0.783% | 1.358% |
| **M&ge;5** | 0.076% | 0.142% |
| **M&ge;6** | 0.009% | 0.013% |
| **M&ge;7** | 0.001% | 0.001% |

### ETAS Forecasted Magnitude Vs. Time
*[(top)](#table-of-contents)*

These plots show the show the magnitude versus time probability function since simulation start. Observed event data lie on top, with those input to the simulation plotted as magenta circles and those that occurred after the simulation start time as cyan circles. Time is relative to the mainshock (M3.87, ci41081408, plotted as a brown circle). Probabilities are only shown above the minimum simulated magnitude, M=2.5.

| One Week | One Month |
|-----|-----|
| ![Mag-time plot](resources/mag_time_week.png) | ![Mag-time plot](resources/mag_time_month.png) |

### ETAS Spatial Distribution Forecast
*[(top)](#table-of-contents)*

These plots show the predicted spatial distribution of aftershocks above the given magnitude threshold and for the given time period. The 'Current' plot shows the forecasted spatial distribution to date, along with as any observed aftershocks overlaid with cyan circles. Observed aftershocks will be included in the week/month plots as well if the forecasted time window has elapsed.

|  | Forecast: 1 Week | Forecast: 1 Month |
|-----|-----|-----|
| **M&ge;3** | ![Map](resources/comcat_compare_prob_1wk_m3.png) | ![Map](resources/comcat_compare_prob_1mo_m3.png) |

### ETAS Fault Trigger Probabilities
*[(top)](#table-of-contents)*

The table below summarizes the probabilities of this sequence triggering large supra-seismogenic aftershocks on nearby known active faults.

| Fault Section | 1 wk supra-seis prob | 1 mo supra-seis prob | 1 wk M&ge;7 prob | 1 mo M&ge;7 prob |
|-----|-----|-----|-----|-----|
| **Malibu Coast alt 1** | 0.005% | 0.007% | 0.001% | 0.001% |
| **Malibu Coast (Extension) alt 1** | 0.001% | 0.001% | <0.001% | <0.001% |
| **Anacapa-Dume alt 1** | 0.001% | 0.001% | 0.001% | 0.001% |
| **Santa Monica alt 1** | 0.001% | 0.001% | 0.001% | 0.001% |
| **Hollywood** | <0.001% | <0.001% | <0.001% | <0.001% |
| **Elysian Park (Upper)** | <0.001% | <0.001% | <0.001% | <0.001% |
| **San Pedro Basin** | <0.001% | <0.001% | <0.001% | <0.001% |
| **Puente Hills** | <0.001% | <0.001% | <0.001% | <0.001% |
| **Ortigalita (South)** | <0.001% | <0.001% | <0.001% | <0.001% |
| **Monterey Bay-Tularcitos** | <0.001% | <0.001% | <0.001% | <0.001% |
