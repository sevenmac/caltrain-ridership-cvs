# caltrain-ridership-cvs
This repo contains the cvs format of a part of the ridership information Caltrain shared publicly


## Caltrain Ridership Information

Caltrain Shares the Ridership information publicly in their web page, the shared formats were not ın formats that I can consume with my limited Python and Data Science experience. So, I decided to translate some of the data into cvs format. Caltrain is the owner of the data and it is subject to the licence thay enforce.

The CVS file only contains the 2019 Ridership data, excluded the riders with Bike data. 

[Caltrain Ridership Web Page](https://www.caltrain.com/about/statsandreports/Ridership.html)

## Information About the CVS content

- Station    >> Caltrain Station
- On         >> How many new passengers get into the train
- Off        >> How many passangers get out of the train
- Onboard    >> Total number of the passangers in the train
- Direction  >> N, Northbound / S, Southbound 
- Train Code >> I assumed internal code of the scheduled train ride
