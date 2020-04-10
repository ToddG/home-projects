# decom chimney

# problem

chimney cap has failed, and the mortar at the top is washing out and falling down.

* ![chimney](../photos/chimney/chimney01.jpeg)
* ![loose-bricks](../photos/chimney/loose-bricks-top-left.jpeg)

## summary

* furnace and hot water heater both vent through chimney
* need to remove chimney and change the furnace and water heater

## options

* high efficiency furnace and water heater
    * use existing gas service and add side wall vent
* heat pump furnace / water heater 
    * add to electrical service and/or panels

## out of scope

* house needs insulation, it's drafty
* i'd like to add more power in the shop and garage
    * bigger lathe and mill
    * charging station for electric car

### process / stages

#### stage 0: current equipment

##### hvac


* ![hvac-01](../photos/hvac/furnace-and-water-heater-01.jpeg)
* ![hvac-02](../photos/hvac/furnace-and-water-heater-02.jpeg)
* ![hvac-03](../photos/hvac/furnace-and-water-heater-03.jpeg)
* ![furnace-01](../photos/hvac/bryant-furnace-installation-sticker.jpeg)
* ![furnace-02](../photos/hvac/bryant-furnace-internals-mfg-2006.jpeg)
* ![furnace-03](../photos/hvac/bryant-furnace-model-serial.jpeg)
* ![furnace-04](../photos/hvac/bryant-furnace-service-sticker.jpeg)


Current Venting

* ![venting-01](../photos/hvac/bryant-furnace-current-venting-to-chimney.jpeg)
* ![venting-02](../photos/hvac/side-wall-venting-opportunity.jpeg)

##### electrical

###### meter/service

* ![elec-01](../photos/electrical/electrical-service-01.jpeg)
* ![elec-02](../photos/electrical/electrical-service-02.jpeg)
* ![elec-03](../photos/electrical/electrical-service-03.jpeg)

###### panels

Main panel has a 125A breaker on the incoming line, followed by a 125A breaker on the feeder to the subpanel, and a 'spare' 20A breaker.

* ![main-panel-03](../photos/electrical/house-mainpanel-03.jpeg)

The subpanel, which powers the entire house has the following two columns:

|Amps|Amps| 
|----|----|
|40|40|
|40|40|
|20|30|
|15|30|
|30|40|
|30|40|

Totals: 375A

|Description|Breakers|
|--------|-----------|
| ![sub-panel-01](../photos/electrical/house-subpanel-01.jpeg) | ![sub-panel-02](../photos/electrical/house-subpanel-02.jpeg) |


##### gas

###### meter

* ![gas-01](../photos/gas/gas-service-01.jpeg)
* ![gas-02](../photos/gas/gas-service-02.jpeg)

#### stage 1: research and plan

* research high efficiency hvac/water heaters
* get quotes from hvac companies to replace both
* price out components
* decide on replacement components
* decide on company to do the work
* determine all external dependencies
    * Seattle City Light AM/PM
    * Lead time to order parts/components


##### Water Heaters

|Water Heater|Cost|
|------------|----|
|[50Gal Heat Pump](https://www.homedepot.com/p/Rheem-Performance-Platinum-50-gal-10-Year-Hybrid-High-Efficiency-Smart-Tank-Electric-Water-Heater-XE50T10HD50U1/303419574)|1300.00|
|[50Gal NG Power Vent](https://www.homedepot.com/p/Rheem-Performance-40-Gal-Tall-6-Year-40-000-BTU-Natural-Gas-Power-Vent-Tank-Water-Heater-XG40T06PV40U0/204318424)|800.00|
|[Tankless](https://www.homedepot.com/p/Rheem-Performance-Platinum-9-5-GPM-Natural-Gas-High-Efficiency-Indoor-Tankless-Water-Heater-ECOH200DVLN-2/304820618)|1300.00|

* Heat Pump will require a 20.83A 240V circuit (need electrician and possible service upgrade)
* NG unit can swap in and replace existing unit (need to cut hole in side wall to vent, get pro to hook up gas line)
* The power vent means it can be ducted horizontally out the wall and does not require the chimney.
* Not sure if the existing water heater can be converted to use a power vent (saw lot's of conflicting opinions on the 'tubes), but in my case, it's moot as the water heater is 13 years old at this point, and I should probably replace it rather than put more money into it.

* [x] Upgrade existing gas water heater or replace? REPLACE
* [x] Replace with 50Gal NG Power Vent $800


##### Furnace

|Component|Cost|
|---------|----|
|[Power Vent Adapter](https://www.homedepot.com/p/Field-Controls-Power-Vent-4-in-Outside-Mounted-SWG-4HD/205880995)|412.00|
|[Power Vent Controller](https://www.homedepot.com/p/Field-Controls-Control-Kit-Gas-CK-41F/203206852)|200.00|
|[Furnace Category IV Venting](https://www.homedepot.com/p/Winchester-80-000-BTU-95-Efficient-Single-Stage-Multi-Positional-Residential-Gas-Furnace-with-ECM-Blower-Motor-TM9E080B12MP12/311370770)|1800.00|

* [ ] Upgrade or replace existing gas furnace? 
* [ ] Need pros to come out and take a look and give quotes
* [ ] Have detailed plan, timeline, etc.

#### stage 2: stop using chimney

* [ ] Replace hvac systems
* [ ] Chimney is not being used


#### stage 3: job site

* make the chimney safe to work around, either
    * request a power disconnect (called an AM/PM, costs $1K)
    * hire an electrician to move the service
* buy, borrow, or rent trailer
* buy, borrow, or rent scaffolding
* buy, borrow, or rent tools (air hammer, etc.)
* erect scaffolding (attach to side of house)
* buy & deploy safety lines, harness, hardhat

* [ ] Job site is prepped and safe


#### stage 4: decom chimney
* decom
    * tear down the chimney
    * patch the siding
    * patch the roof
* take down the scaffolding

* [ ] Chimney removed

#### stage 5: wrap up
* re-connect power if disconnected
* return borrowed and/or rented equipment

* [ ] Power restored, house buttoned up, and all systems operational

### notes (most recent first)

#### Thu Apr  9 12:16:13 PDT 2020

##### Seattle City Light: 206-684-3000

Just talked to my Seattle City Light rep. Got great info:

* no crews currently operating for next 2 days, not sure when they will start back up
* governor has a stop work order in effect through the end of April
* need to consult an electrician as i'll be adding draw to my service (adding two heat pumps, doh!, and may add charging for an electric car eventually)
* current service is probably up to 200Amps, judging from the size of the wires going into the WeatherHead
* need to check the rating on the panel size *and* the meter base
* fee for an AM/PM drop/connect is $1K
* Rep suggested I consult an electrician and they could route the service to a better location farther from the chimney, and upgrade the house wiring, add the circuits for the heat pumps, etc.

* [ ] check rating on panel size
* [ ] check rating on meter base

BTW - If you look at the service photos, the electrical tape is fraying off where it enters the WeatherHead

##### Aurora Rents


    https://blog.aurorarents.com/about/
    Shoreline –  206.368.7368
    **Greenlake –  206.729.7368**
    Lake City –  206.362.7368
    25' scaffolding : $77/day
    trailer to haul scaffolding: $40/day

##### Can purchase scaffolding here

https://seattle.craigslist.org/see/for/d/seattle-tons-of-scaffolding/7104283806.html

    Call me for scaffolding questions. Dan 206-399-2936
    There are too many options to give you for dimensions without knowing exactly what you want.
    Frames 45.00 each
    X brace 17.00 each
    Plank 35.00 each
    Wheels 35.00 each
    Screw jacks 15.00 each

