# openintro (development version)

* Added new datasets:
  * `earthquakes`, `mcu_films`, `salinity`, `snowfall`, `ssd_speed` by [@npaterno](https://github.com/npaterno)
* Added new datasets: 
  * `fact_opinion`, `flow_rates`, `race_justice` by [@npaterno](https://github.com/npaterno)
  * `exam_grades`
* Updated `email` and `email50` datasets to make indicator variables factors, remove variables that don't exist in the data from the documentation, and update the documentation for `email50` to match the randomly sampled data

# openintro 2.0.0

* Added a `NEWS.md` file to track changes to the package.
* Consolidated openintro, oilabs, and oidata packages.
* Updated all dataframe and variable names to use snake_case.
* Turned data.frames into tibbles.
* Simplified code in most examples to make it more accessible for the student audience for the package.
* Added new datasets used in OpenIntro Statistics, 4th Edition.
* Added new datasets used in new OpenIntro labs.
* Removed package startup message.
* Added dependency on the following packages: [airports](https://openintrostat.github.io/airports/), [cherryblossom](https://openintrostat.github.io/cherryblossom/), and [usdata](https://openintrostat.github.io/usdata/).
* Moved `run09`, `run12`, and `run19` datasets to the cherryblossom package.
* Moved `usairports` to the airports packages.
* Moved `county_complete`, `county`, `govrace10`, `houserace10`, `prrace08`, `senaterace10`, `state_stats`, `urban_owner`, `urban_rural_pop`, `vote_nsa` datasets and `state2abbr` and `abbr2state` functions to the usdata package.
