# mock-gw-skyportal
Mock data for GW follow-up using the Skyportal instance 

The flow of the project:

order |Task | comments | tools | difficulty | who | when 
--|--|--|--|--|--|--
1|make a map folder | take them from [Petrov et al.](https://zenodo.org/record/5206853) or [LIGO]()| 
2|select a cadence for upload maps | select under size and distance
3|creation of events and inject them | need to check what needs to be changed event by event
4|stream the maps | |
5|create observing plans on Skyportal |trigger the automated creation of observing plans to understand whether they complete and whether the plans make sense
6|metrics to assess the quality of the plans previous the triggering| a few different ones to cross check | [gwemopt summary](https://github.com/mcoughlin/gwemopt)
7|simulate transients | KN and contaminants| [nmma](https://nuclear-multimessenger-astronomy.github.io/nmma/) 
8|check if filtering works | metrics? different filters? |[Skyportal](https://skyportal.io/)
9|metrics to assess the quality of the plans after triggering| a few different ones to cross check | [simsurvey](https://github.com/ZwickyTransientFacility/simsurvey)
