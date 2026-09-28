# Reflection: sebmart_taxisimulation

TaxiSimulation's pattern is declining in the most extreme way of any project here: a burst
of activity right at the start of its recorded history, then a very long quiet period, with
four gaps of three or more months.

The longest gap (2018-02 to 2024-10, 81 months, by far the longest of any of the ten
projects) took more digging to pin down fully. The pre-gap  commits (2016-2018) are from 
original author Sebastien Martin, tied to an Operations Research paper on online vehicle 
routing, and research code built for a specific paper commonly goes quiet once that work 
concludes. The repo's own README now references a fork, `RoutingNetworksPotato`, and the 
post-gap merge commit explicitly names `OwOIamNoob/TaxiSimulationPotato`. The 81-month gap 
ended because an outside team ported the code from an outdated Julia/graphics stack (SFML 
to CSFML, old JuMP syntax) to run on modern Julia, likely because they wanted to reuse the 
simulator for their own purposes.

Sebastien Martin, the original author, does not appear anywhere in the post-gap commits 
and this recovery was driven entirely by new people (OwOIamNoob, hoangvanphi).

**Current status:** Inactive (last GitHub commit 2024-11-14).
