# 5.21, 5 km S of Julian, CA

## Table Of Contents

* [Mainshock Details](#mainshock-details)
  * [USGS Products](#usgs-products)
  * [Nearby Faults](#nearby-faults)
  * [Ground Motion Animation](#ground-motion-animation)
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

Information and plots in the section are taken from the [USGS event page](https://earthquake.usgs.gov/earthquakes/eventpage/ci40925991), accessed through ComCat.

| Field | Value |
|-----|-----|
| Magnitude | 5.21 (mw) |
| Time (UTC) | Mon, 14 Apr 2025 17:08:28 UTC |
| Time (CDT) | Mon, 14 Apr 2025 12:08:28 CDT |
| Location | 33.03583, -116.59483 |
| Depth | 14.29 km |
| Status | reviewed |

### USGS Products
*[(top)](#table-of-contents)*

| <center>**[ShakeMap](https://earthquake.usgs.gov/earthquakes/eventpage/ci40925991/shakemap/)**</center> | <center>**[Did You Feel It?](https://earthquake.usgs.gov/earthquakes/eventpage/ci40925991/dyfi/)**</center> |
|-----|-----|
| ![ShakeMap](resources/ci40925991_shakemap.jpg) | ![DYFI](resources/ci40925991_dyfi.jpg) |
| <center>**[PAGER](https://earthquake.usgs.gov/earthquakes/eventpage/ci40925991/pager/)**</center> | <center>**[Moment Tensor](https://earthquake.usgs.gov/earthquakes/eventpage/ci40925991/moment-tensor/)**</center> |
| ![PEGER](resources/ci40925991_pager.png) | ![Mechanism](resources/ci40925991_mechanism.jpg) |

### Nearby Faults
*[(top)](#table-of-contents)*


1 UCERF3 fault section is within 10km of this event's hypocenter:

* Elsinore (Julian): 7.07km

### Ground Motion Animation
*[(top)](#table-of-contents)*
Animation of simulated ground motions from the 2025-04-14
Julian earthquake, depicting up (red) and down (blue) seismic wave
velocities, integrating a 3D community subsurface velocity model for
Southern California (SCEC CVM-H v15.1.0; Shaw et al., 2015), made available
by the Statewide California Earthquake Center, and high-resolution
topography. This simulation uses the open-source software SeisSol and requires
14 minutes of run-time on 768 cores. Provided by John Rekoske & Alice Gabriel,
Scripps Institution of Oceanography, UCSD.
<video width="80%" height="auto" controls>
<source src="resources/julian_movie-v3.mp4" type="video/mp4" />
</video>

## Sequence Details
*[(top)](#table-of-contents)*

These plots show the aftershock sequence, using data sourced from [ComCat](https://earthquake.usgs.gov/data/comcat/). They were last updated at 2025/04/14 22:49:12 UTC, 5.68 hours after the mainshock.

128 M&ge;0 earthquakes within 50 km of the mainshock's epicenter.


|  | First Hour | To Date |
|-----|-----|-----|
| **M 0** | 60 | 128 |
| **M 1** | 42 | 77 |
| **M 2** | 11 | 17 |
| **M 3** | 1 | 2 |
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

Probabilities are inherantly time-dependent. Those stated here are for time periods beginning the instant when this report was generated, 2025/04/14 17:49:12 CDT. The model has not been updated with any observed aftershocks and may be out of date, especially if large aftershock have occurred subsequently or a significant amount of time has passed since the mainshock.

Results are summarized below and should be considered preliminary. The exact timing, size, location, or number of aftershocks cannot be predicted, and all probabilities are uncertain.


This table gives forecasted one week and one month probabilities for events triggered by this sequence; it does not include the long-term probability of such events.

|  | 1 Week | 1 Month |
|-----|-----|-----|
| **M&ge;3** | 93.629% | 97.642% |
| **M&ge;4** | 27.140% | 35.086% |
| **M&ge;5** | 3.425% | 4.650% |
| **M&ge;6** | 0.275% | 0.404% |
| **M&ge;7** | 0.033% | 0.049% |
| **M&ge;8** | <0.001% | <0.001% |

### ETAS Forecasted Magnitude Vs. Time
*[(top)](#table-of-contents)*

These plots show the show the magnitude versus time probability function since simulation start. Observed event data lie on top, with those input to the simulation plotted as magenta circles and those that occurred after the simulation start time as cyan circles. Time is relative to the mainshock (M5.21, ci40925991, plotted as a brown circle). Probabilities are only shown above the minimum simulated magnitude, M=2.5.

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
| **Earthquake Valley (So Extension)** | 0.028% | 0.045% | 0.015% | 0.022% |
| **Earthquake Valley** | 0.030% | 0.042% | 0.018% | 0.027% |
| **Earthquake Valley (No  Extension)** | 0.023% | 0.034% | 0.018% | 0.027% |
| **Elsinore (Julian)** | 0.013% | 0.021% | 0.012% | 0.019% |
| **Elsinore (Coyote Mountains)** | 0.013% | 0.019% | 0.012% | 0.018% |
| **Elsinore (Temecula) rev** | 0.009% | 0.014% | 0.009% | 0.014% |
| **Elsinore (Glen Ivy) rev** | 0.008% | 0.010% | 0.007% | 0.009% |
| **Elsinore (Stepovers Combined)** | 0.008% | 0.010% | 0.008% | 0.010% |
| **Whittier alt 1** | 0.007% | 0.009% | 0.007% | 0.009% |
| **Chino alt 1** | 0.001% | 0.002% | 0.001% | 0.001% |
