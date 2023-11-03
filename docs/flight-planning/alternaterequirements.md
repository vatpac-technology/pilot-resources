---
  title: Alternate Requirements
---

--8<-- "includes/abbreviations.md"

## Introduction
An alternate aerodrome is an aerodrome nominated by the pilot at the flight planning stage which will be used as a divert point should the planned destination become unsuitable for any reason. In the real world, there are many reasons why an alternate may need to be carried. This page simplifies some of the real world rules and highlights the ones which are applicable for VATSIM operations.

## Alternate due Weather
When planning a flight, make careful study of your destination's TAF and take note of the cloud, visibility, and wind during the period of **30 minutes either side of your ETA** (60 minute window). Compare the forecast values with the alternate minima described below. If a TAF is not available for your arrival window, you must hold an alternate.

You must plan an alternate (or carry sufficient holding fuel, see [Fuel Planning](fuelplanning.md)) if:

- There is **more than scattered cloud** below the alternate minima, or
- The **visibility is less** than the alternate minima, or
- The **wind (including any gusts) exceed** the aircraft's crosswind or tailwind limitations, or
- The forecast indicates **thunderstorms or their associated severe turbulence**

!!! note
    When calculating the amount of cloud at a given level, the following rules apply:

    - FEW plus FEW equals SCT
    - FEW plus SCT equals BKN

### VFR Alternate Minima
The VFR alternate minima, by both day and night, is as follows:

| Cloud | Visibility |
| ----- | ---------- |
| 1,500ft AGL | 8km |

For helicopters operated under Day VFR to an uncontrolled (Class G) aerodrome, the alternate minima is reduced to:

| Cloud | Visibility |
| ----- | ---------- |
| 1,000ft AGL | 3km |

!!! note
    An alternate is not required if you are flying under Day VFR and plan to remain within 50nm of the departure aerodrome.

### IFR Alternate Minima
The IFR alternate minima is described on any approach chart for that aerodrome. The figures are formatted as cloud height above ground level and visibility in kilometres.

!!! example
    The alternate minima for a Category C aircraft landing at Adelaide (YPAD) would be more than scattered cloud below **1,480ft AGL** and/or visibility below **6.0km**.
    <figure markdown>
    ![Adelaide Alternate Minima (example only, not for operational use)](img/ypadminima.png){ width="700" }
      <figcaption>Adelaide Alternate Minima (example only, not for operational use)</figcaption>
    </figure>

If your destination does not have an instrument approach, you must plan an alternate if the area forecast indicates weather conditions below:

| Cloud | Visibility |
| ----- | ---------- |
| LSALT +500ft | 8km |

## Alterante due Navaids
### IFR
An alternate must be held for IFR flights if due to the aircraft's equipment or the destination aerodrome's navigation aids, a single point of failure in the aircraft or on the ground would cause a loss of approach capability. In principle, this means that if your destination has only a single approach type available or your aircraft has only a single piece of equipment which can receive that data, you must carry an alternate.

!!! example
    Flying a B737 (with multiple GPS, VHF NAV, and ADF equipment onboard) to Orange (YORG), which has published RNP approaches but no ground based aids, would require an alternate, as a loss of RAIM or GNSS integrity would result in the aircraft being unable to conduct an approach.  

    Flying a C172 (with a single GPS, VHF NAV, and no ADF) to Sydney (YSSY) would *not* require an alternate, as a failure of a single piece of equipment in the aircraft (e.g. the GPS) or on the ground (e.g. the ILS) would not prevent the aircraft from conducting an approach (they could still utilise the RNP or ILS approach, depending on the source of failure).

### Night VFR
An alternate, within 1 hour flying time, is required for Night VFR flights unless:

- The aircraft is equipped with GNSS, or
- The destination is served by a ground-based navaid which the aircraft has equipment to receive