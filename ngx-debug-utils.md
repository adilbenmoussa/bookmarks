
### Element debugging information
`ng.probe($0)`

### Triggering digest cycle manually
`ng.profiler.timeChangeDetection();`

or

`ng.probe($0).injector.get(ng.coreTokens.ApplicationRef).tick();`
