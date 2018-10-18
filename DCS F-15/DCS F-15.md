## DCS F-15

The DCS F-15 is an excellent air-to-air (A2A) aircraft that excels at both beyond Visual Range (BVR) combat as well as close-in dogfighting. It sports a very capable AN/APG-63(V)1 pulse-doppler radar as well as the capable AIM-120C active radar missile. Being a Flaming Cliffs 3 (FC3) aircraft, it is much simpler to operate than other high-fidelity modules such as the A-10C and lack a clickable cockpit which hampers immersion slightly. However, while it is a good starting point for beginners to the franchise, it is by no means a cakewalk to fly this machine. Good understanding of the aircraft and how to operate it will translate to airframe mastery and eventually, airspace dominance. 

### Basics

#### Cockpit and Instruments

![Cockpit](.\Assets\Cockpit.png)

The above are the notable parts of the cockpit. While the cockpit is not clickable, it does not mean that it is useless - on the contrary, much of the cockpit provides much needed information that may not be displayed in the Heads Up Display (HUD). Additionally, the cockpit also has important radar displays that allow the F-15C to possess excellent BVR capabilities like it does.

1. **Multi-Purpose Color Display (MPCD)** - sometimes may be referred to by other players as "MFCD (Multi-Function Color Display)" or just "MFD (Multi Function Display)"
2. **Indicated AirSpeed (IAS) and Mach meter** - shows airspeed as well as mach number
3. **Vertical Situation Display (VSD)** - basically the radar "screen" of the F-15C, this is where the radar cone could be manipulated and targets would be displayed or scanned
4. **Attitude Heading Director (ADI)** - displays aircraft attitude, useful for waypoint navigation
5. **Vertical Velocity Indicator (VVI)** - displays the rate of ascent or descent
6. **Altimeter** - displays current altitude
7. **Fan Turbine Inlet Temperature (FTIT) indicators** - as said on the tin, good for engine management though not the most useful gauge during normal operations
8. **Engine Tachometers** - displays engine RPM in percentage (%), useful for engine management
9. **Tactical Electronic Warfare System (TEWS) display unit** - also known as the Radar Warning Receiver (RWR), this display will inform the pilot if there are any radar sources nearby the are scanning/locking onto the aircraft
10. **Fuel Quantity Indicator** - self explanatory. 
11. **Chaff, Flare Lights** - informs the pilot that chaff and/or flares are being deployed
12. **Landing Gear Control Handle** - more for visual, but it informs the pilot if the gear is lowered or raised.
13. **Landing Gear Position Indicator** - same as (12), it is to inform the pilot if the gear is lowered or raised
14. **Angle of Attack (AoA) Indicator** - displays the units of AoA, take note that AoA units are not in degrees
15. **Accelerometer** - displays acceleration of the aircraft
16. **Horizontal Situation Indicator (HSI)** - displays the heading of the aircraft and bearing of the next waypoint
17. **Clock** - a clock, useful for synchronizing attacks or rendezvous timings
18. **Engine Fuel Flow Indicators** - displays the amount of fuel being fed to the engines, good for engine management or troubleshooting. Fuel flow is measured in pounds per hour.
19. **Engine Exhaust Nozzle Position Indicator** - displays the amount at which the engine nozzle is opened (in percent). In afterburner mode, the nozzle position will be 100%.
20. **Cabin Pressure Altimeter** - displays cabin pressure, mainly used for troubleshooting of cabin depressurization
21. **Caution Lights Panel** - panel of various lights that provides information on various errors or cautions. Used both in normal flight as well as troubleshooting.

Any other cockpit switch/instrument that is not on this list is non-essential or not implemented (most of the side switches and panels). Once again it has to be restated that even the active elements of the cockpit cannot be interacted with a mouse. The operating procedure will be centered around keyboard (or HOTAS) bindings.

##### Multi-Purpose Color Display



### Operating Procedure

These are the basic operating procedures for the DCS F-15. Following these steps should allow a beginner to get their aircraft airborne in short order. 

#### Preflight

1. `\` to access communications
2. `F8` to talk to ground crews
3. `F1` to manage stores - the stores management will pop up: the aircraft stores can now be configured to the user's liking. Once complete, wait for a moment for the stores to be loaded onto the aircraft. 
4. `F2` would bring up the external view and make it easier for this to be observed. The more stores selected to be added/swapper/removed, the longer it would take for the changes to be done by the ground crews. *Do note that you cannot change stores with the engines on and or canopy closed*

#### Startup 

1. `Lshift` + `L` : Start electrical systems
2. `Rctrl` + `C` : Lower Canopy
3. *If night-time*: `L` to start cockpit lighting
4. `Lctrl` + `Home` : Start right engine
   - Wait for engine to rest at 500 degrees, 69% RPM, check right side hydraulic gauges
5. `Lshift` + `Home` : Start left engine
   - Wait for engine to rest at 500 degrees, 69% RPM, check left side hydraulic gauges
6. `Rctrl` + `L` : Turn on wing Navigation lights
7. `Ralt` + `L` : Turn on taxi/landing lights
8. `Rctrl` + `Ralt` + `L` : Turn on anti-collision lights
9. *Brake Test*: Hold down `W` to engage wheel brakes while bringing the throttle up to around 40% - ensure that the aircraft is unable to move.
10. Release the brakes, the aircraft is now ready to taxi

#### Taxi

1. `\` to open communications menu
2. `F5`, `F1`, `F1` to request approval for taxi 
3. *On some multiplayer servers, you'll have to talk to the GCI personally to request for permissions*
4. `Numpad +` to apply throttle slightly (or use a HOTAS)
5. `Numpad -` to decrease throttle if you are moving too fast - keep the speed under 50 Knots Indicated Air Speed (KIAS) at all times
6. `Z` and `X` for left and right rudder respectively (or use rudder pedals)
7. `S` to enable nosewheel steering (allows for much faster response)
8. `W` to engage wheel-brakes - they are rather strong on the ground as long as your throttle isn't too high
9. `F10` to call up the map if you are unsure of how to get to the runway or which runway to taxi to
10. Taxi to the runway but stop short of the runway - check both sides of the runway for traffic

#### Takeoff

1. `\` to open communications menu
2. `F5`, `F1`, `F1` to request approval for takeoff
3. `F` to extend flaps - under this setting, the flaps would automatically retract when you exceed 250 KIAS and extend once the aircraft returns to below 250 KIAS
4. Turn into the runway and align with the center and come to a stop
5. `W` to engage wheel brakes
6. While holding down wheel brakes, `Numpad +` to add throttle until 80% RPM - allow the engines to spool up to 80% RPM for 2-3 seconds
7. Release the wheel brakes and add throttle to full using `Numpad +` - steer the aircraft and keep it aligned with the runway using the rudders (`Z` and `X`)
8. Once the aircraft reaches 150 KIAS, pull up on the stick to reach 11-12 degrees pitch
9. *If keyboard control is used*: Use the arrow keys to pull up. Note that keyboard control will help you hold your pitch automatically but not your roll. Take note of this to prevent crashes or excessive AoA.
10. `G` to raise the landing gear
11. You should have successfully taken off

#### Landing

1. 