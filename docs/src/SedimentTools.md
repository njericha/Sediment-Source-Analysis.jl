# Sediment Analysis Tools
```@docs
SedimentSourceAnalysis.SedimentTools
```

## Types
```@docs
Grain
DensityTensor
Rock
Sink
Source
```

## Method Extentions
```@docs
getindex(::Sink, ::String)
names(::NamedArray, ::Union{String,Symbol})
heatmap(::NamedMatrix)
SedimentSourceAnalysis.SedimentTools.make_densities(::Sink)
SedimentSourceAnalysis.SedimentTools.make_densities2d(::Sink)
```

## Functions

### Importers
```@docs
read_raw_data
```

### Getters
```@docs
array
getdomain
getdomains
getmeasurements
getsourcename
getsourcenames
getstepsizes
namedarray
getsink
getsource
```

### Setters and Manipulators
```@docs
normalize_density_sums!
normalize_density_sums
setsourcename!
match_sources!
```

### Grain Labeling
```@docs
confidence_score
estimate_which_source
estimate_which_2d_source
estimate_which_nd_source
label_accuracy
```

### Iterators
```@docs
eachdensity
eachmeasurement
eachsink
eachsource
```

### Visualizers
```@docs
measurement_heatmaps
plot_densities
source_heatmaps
plot_convergence
plot_source_index
```

## Index

```@index
```
