---
  title: Controlled Aerodromes
---

--8<-- "includes/abbreviations.md"

## Airways Clearance
### Standard airways clearance format

!!! TIP
    If the controller is a Center or approach, it's suggested you specify what airport you are in, especially if you are not at their primary airport.

**IFR**

Request:"[Station (Tower/Ground/Delivery/Approach/Center)] [Callsign] for [Destniation] Request clearance" 

Clearance: `"[Callsign] cleared to [Destniation] via [First point] Flight planed route Runway [Identifier] [Standard instrument departure] departure, climb via the SID [Alt] Squawk [Code] Departures [Freq]"`

Readback: `"Cleared to [Destniation] Via [First point] Flight planed route, Runway [Indentifier] [SID] departure, climb via the sid [ALT] Squawk [Code], Departures [Freq], bay [Bay number] **[Callsign]"`

**VFR**

Request:`"[Station (Tower/Ground/Delivery/Approach/Center)] [Callsign] for [Destniation] Request clearance"`

Clearance:`"[Callsign] cleared [destination] via [First point]/Direct, runway [Identifier] climb/not above [ALT] Departures [Freq]"`

Readback:`"Cleared [Destination] Via [First point]/Direct, Runway [Identifier] Climb/Not above [ALT] Departures [Freq]"`

**Circuits**

Request:`"[Station (Tower/Ground/Delivery/Approach/Center)] [Callsign] [Aircraft type] [Bay] [number] People on board, for circuits"`
<Sub>Controller may tell you to stand by as they co-ordinate with other controllers on things like altitude, runway and circuit direction</Sub>

Clearance:`"[Callsign] cleared to operate in the circuit area runway [Identifier] [circuit direction of applicable] not above [Alt] squawk [code]"`

### PDC

You may recive a PDC at any time with out requesting it (via direct message), OR you may request a PDC on freq with the following phraseology.

`" [Callsign] for [Destniation] Request PDC"`

!!! NOTE
    - If you wish to recive a PDC via CPDLC/ACARS check the controller info for a CPDLC/PDC logon code and send a PDC request that way.
    - CPDLC/PDC logons are 4 letter codes and will look like `CPDLC/PDC YYYY`
    - Controller info can be found by double clicking the frequency in the frequency list in V/X pilot

After you recived a PDC you are required to read it back on the specified freq. FIRST inform the controller you have a PDC readback so they can be ready to check it.

`"[Station (Tower/Ground/Delivery/Approach/Center)] [Callsign] with PDC readback"`

When the controller says:`"[Callsign] go ahead"`

Readback:`"[SID],Bay [Number], [Squawk]"`

## Pushback & Taxi
### Pushback

 `"[Callsign] request push"` <Sub> note in normal operations start approval is not explicitly required </Sub>

### Engine start

 **There is only one type of engine start that needs ATC clearance in Australia. This is a Cross-bleed start, only applicable to jets that need to start 1 engine on the bay with ground crew assistance prior to pushback.**
  ~~`"[Callsign], Bay [Number] request cross-bleed start and push"`~~

### Taxi

Request:`"[Callsign] with information [ATIS info] Ready for taxi [Runway]"`
  
 A taxi instruction will be laid out as follow, `"[Callsign] Taxi via [routing] to [Taxi limit/end]"`
 A clearance may advice you to Hold short, give way or cross a runway.
 
  - Hold short `"Hold short of [taxi way]"`
  - Hold short of runway `"... Holding point [Point] Runway [Identifier]"`
  - Give way `"...Give way to [Callsign/company] [Aircraft type]..."`
  - Runway crossings `"...on [taxi-way] cross [runway]..."` Alternatively `"...Cross [Runway]..."`
  
  Readback: Readback all instructions as they were issued to you. Pen and paper doesn't hurt.

## Takeoff & Landing
### Report Ready
  on first contact with Tower, or when ready to depart, ensure you report ready for departure. As tower can't issue a take-off clearance untill you do so. There are 2 methods of doing this. 
    
  You can either report that you will be ready when you reach the holding point with `"[Station] [Callsign] ready upon reaching [Holding point]"`

  Else you can report that you're ready when waiting at the holding point with `"[Station] [Callsign] Ready [Holding point]"`

### Take-off clearance
 As a general rule, a take-off clearance will only consist of  `"[callsign][runway],clear for take-off"`

How ever, there may be special requirements that need to be followed like `"[Callsign][Runway],Clear for Imidiate take-off/no delay"` Or, `"[Callsign] Assigned heading xxx/[special requirements],[Runway] Clear for take-off"`

With all clearances you are required to read back all special instructions/requirements. HOW EVER, if tower report new winds, winds readback not required.

Take-off readback should look like: `"Cleared for take-off [Sepcial instructions] [Callsign]"`

## Helicopter Operations
Helicopters have the fun little quirk of being able/having to leave the ground to get around, even away from the runway. There are 2 ways of completing this, either air taxi, or air transit. ATC will decide which is best in the senario, usually prioritising air taxi.

Heli pilots should be ready to either depart from their position or to manuver to a helipad/runway

Request:`"[Station][Callsign] Ready for departure."`

### Air taxi

A-Taxi clearance `"[Callsign] Airtaxi not above [Height] AGL, [Taxi instructions]"` (AGL standing for above ground level)

Readback:`"Cleared air taxi not above [Height], [Taxi instructions],[Callsign]"`

### Air Transit

A-Transit clearance`"[Callsign] Cleared air transit [destniation] not above [Height] AGL"`

Readback:`"Cleared Air transit [Destniation] not above [Height][Callsign]"`

## Circuits
You will know your circuit direction either from your clearance OR runway config, if there is any chance of missinterpretation tower will advise in take-off clearance. Tower may also specify "report downwind" as a reminder, how ever even if they don't specify this you must report downwind ALWAYS.
### Take-off clearance
Normal:`"[Callsign], runway [Identifier], clear for take-off"`
Specified:`"[Callsign], Make [direction] Circuit, report downwind, runway [identifier] clear for take-off"`

### Downwind report
<Sub>Reminder, you must always report turning onto or level on downwind with intentions </Sub>

Turn, Touch and Go:`"[Callsign], turning downwind [Runway], touch and go"`

Touch and Go:`"[Callsign] downwind [Runway] touch and go"`

Turn, Full Stop:`"[Callsign] turning downwind [Runway] full stop"`

Full Stop:`"[Callsign] downwind [Runway] Full stop"`

Departure (not previously discussed):`"[Callsign] downwind [Runway] for departue to [Point/Destniation]"`
