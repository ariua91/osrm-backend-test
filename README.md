# osrm-backend-test
Testing OSRM backend

## Motivation

The [JSPRIT <> OSRM POC](https://github.com/ariua91/road-dist-optimiser) was successful. OSRM accessed through http was ridiculously fast (~ 1s) for a 100 by 100 matrix. There were some odd results in JSPRIT - an awkward number of cross island results for some reason, but the core principle seems sound. Odd results possibly from weird long lat or wrong null result handling.

I want to scale the OSRM past the 100 point API imposed limit, to see where this can go. Actually deploying this in production will be for real engineers, not some noob like me.

