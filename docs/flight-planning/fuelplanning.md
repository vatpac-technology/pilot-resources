---
  title: Fuel Planning
---

--8<-- "includes/abbreviations.md"

## Preflight Fuel Planning
Before departing, it is critical that you ensure the fuel on board is sufficient for your intended flight, including any required reserve or holding fuel. The sections below outline the categories of fuel which may be required. A sample fuel plan is included to highlight the practical use of each fuel category.

### Flight/Trip Fuel
Flight fuel (also called Trip Fuel) is the amount of fuel you expect to burn to fly your planned route, including an allowance for climb and descent if required. It is generally calculated by dividing your route distance by your expected ground speed (accounting for forecast wind).

### Reserve Fuel
Reserve fuel is an allowance which helps cater for anything which may increase the flight fuel (such as unforecast headwinds) and provides a safety margin in case an unexpected event results in a fuel emergency. It is broken up into Final Reserve fuel and Contingency fuel.

In the real world, reserve fuel rules are divided into aircraft category and weight class. The following table simplifies these rules for VATSIM use.

| Aircraft Type | Flight Rules | Final Reserve | Contingency Fuel |
| ------------- | ------------ | ------------- | ---------------- |
| Piston engine or small turboprop | VFR | 30 min |  |
| Piston engine or small turboprop | Night VFR or IFR | 45 min |  |
| Jet engine or commuter turboprop | VFR or IFR | 30 min | 5% of flight & alternate fuel |
| Helicopter | VFR | 20 min |  |
| Helicopter | IFR | 30 min |  |

Contingency fuel is designed to be used, to cater for unexpected headwinds, unusual fuel burns, or other small factors which may impact overall fuel usage. Final Reserve fuel is designed as a safety buffer and should not be used. It is a requirement that you land with your Final Reserve fuel intact. See [Inflight Fuel Emergencies](#inflight-fuel-emergencies) for what is required when you expect to have to use your Final Reserve fuel.

### Taxi Fuel
Taxi fuel is required to cater for the fuel required to taxi to the runway for departure, and to the gate after landing. It may also include a fuel allowance to run the APU. The actual burn rate will depend on the aircraft.

### Instrument Approach Fuel
Instrument approaches often involve configuring the aircraft earlier than normal and tracking via points not planned to originally. As such, extra fuel must be carried when an instrument approach is expected.

The exact amount of fuel depends on the aircraft you are flying, but as a general rule of thumb, allowing 10-15 min at the normal burn rate is normally sufficient.

Approach fuel is only required when the weather indicates an instrument approach will be required to land. This is generally indicated by the following meteorological minima:

| Cloud | Visibility |
| ----- | ---------- |
| Any cloud below LSALT +500ft | 8km |

### Weather Holding/Alternate Fuel
Where the weather (or other factors) are expected to be unsuitable, sufficient fuel must be carried to either hold until conditions improve or divert to a suitable alternate aerodrome. See [Alternate Requirements](./alternaterequirements.md) for more information.

If the weather is forecast to be below the alternate minima, an alternate must be carried. If the poor weather is associated with an `INTER` or `TEMPO`, holding fuel must be carried to wait until conditions improve, in accordance with the table below.

| Term | Description | Holding Fuel Required |
| ---- | ---------- | ---------------------- |
| INTER | Intermittent period lasting up to 30 minutes | 30 min |
| TEMPO | Temporary period lasting up to 60 minutes | 60 min |

If a forecast indicates a probability (`PROB30` or `PROB40`) of poor weather below the alternate minima, you must assume that the weather will eventuate, and hold an alternate or carry holding fuel as required.

!!! example
    **Alternate minima**: cloud base of 1,200ft and visibility of 5km  
    **TAF (snippet)**: `PROB30 INTER 0312/0318 4000 SHOWERS OF MODERATE RAIN BKN010`  
    **Fuel Required**: 30 min weather holding fuel (if ETA falls between 1130z and 1830z)

### Traffic Holding Fuel
Traffic holding fuel is required when operating into certain busy aerodromes. In the real world, traffic levels are consistent and planned, whereas on VATSIM, traffic levels are variable and often unpredictable.

Real world traffic holding requirements are found in an aerodrome's ERSA FAC entry. On VATSIM, it is more important to carry traffic holding fuel during busy events. Regular events, like Milk Run Monday, Panic Stations, and WorldFlight, where high traffic levels are expected, require additional holding fuel to cater for enroute delaying action (such as vectors, holds, and extended periods of time at lower altitudes).

The amount of fuel required is left up to the pilot, but as a general rule, regular events like Milk Run Monday require roughly 20 min of holding fuel, whereas more renowned events like WorldFlight may require up to 90 min. If in doubt, carry a little extra.

### Extra Fuel
The pilot in command may dictate any extra fuel they wish to carry and it is their responsibility to ensure that the fuel onboard is sufficient to complete the flight. If you believe that extra fuel is required for any reason, you must carry that fuel.

There are other situations where you may wish to carry extra fuel, including fuel tankering (carrying enough fuel for the return leg) or when flying to an isolated aerodrome with minimal suitable divert points. It is also worth remembering that you will be sharing the airspace with pilots of all competency levels, which may result in unexpected go arounds or approaches, so extra fuel may be required to compensate. 

### Example Fuel Plan
Below are several sample fuel plans for various aircraft types. These are provided as an example of how to utilise each category of fuel described above. **The burn rates and described fuel figures are examples only and should not be used in an operational sense.**

!!! example
    **Aircraft**: Cessna 172  
    **Flight Rules**: VFR  
    **Route**: `YSBK PRT PENH HSY LRF HBB SYHD JIBN SECF APPN CAMB TWRN YSBK`  
    **Route Distance**: 102 nm  
    **Estimated Enroute Time**: 56 min  
    **Planned Burn Rate**: 36 L/hr  
    **Destination Weather**: Clear skies, calm winds  
    **Additional Notes**: Harbour Scenic One planned, extra fuel carried in case of holding

    | Category | Amount |
    | -------- | ------ |
    | Flight Fuel | 34 L |
    | Alternate Fuel |  |
    | Final Reserve | 18 L |
    | Contingency Fuel |  |
    | Taxi Fuel | 5 L |
    | Instrument Approach |  |
    | Traffic Holding |  |
    | Extra Fuel | 12 L (20 min holding) |
    | **Total Fuel Required** | **69 L** |

!!! example
    **Aircraft**: SAAB 340  
    **Flight Rules**: IFR  
    **Route**: `YGTH BORLI V300 AKMIR W113 TESAT YSSY`  
    **Route Distance**: 256 nm  
    **Estimated Enroute Time**: 57 min  
    **Planned Burn Rate**: 500 kg/hr  
    **Holding Burn Rate**: 450 kg/hr  
    **Destination Weather**: Consistent weather below the alternate minima, Canberra (YSCB) nominated as destination alternate  
    **Additional Notes**: Flight conducted during Milk Run Monday event  

    | Category | Amount |
    | -------- | ------ |
    | Flight Fuel | 475 kg |
    | Alternate Fuel | 257 kg |
    | Final Reserve | 225 kg |
    | Contingency Fuel | 37 kg |
    | Taxi Fuel | 25 kg |
    | Instrument Approach | 200 kg |
    | Traffic Holding | 150 kg (20 min) |
    | Extra Fuel |  |
    | **Total Fuel Required** | **1,369 kg** |

## Inflight Diversion
- Where extensive holding or other factors dictate, perform fuel calculation to determine latest divert time
- Calculate flight fuel from present position to alternate
- Cater for any holding required at alternate (weather, traffic, etc)
- Cater for instrument approach at alternate if required
- Apply conservative buffer to minimum divert fuel, then assess current fuel burn to determine latest divert time
- Advise ATC approaching and reaching divert point

### Inflight Fuel Emergencies
- MINIMUM FUEL and MAYDAY FUEL calls (link to radio page)