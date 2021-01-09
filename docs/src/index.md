# Covid.jl

#Documentation for Covid.jl
<!-- Aqui podemos poner la informacion general-->
## Functions Documentation
| Column 1       | Column 2     | Column 3     |
| :------------- | :----------: | -----------: |
|  Cell Contents | More Stuff   | And Again    |
| You Can Also   | Put Pipes In | Like this \| |

```@autodocs
Modules=[Covid]
```

```@eval
using CSV
using Latexify
using DataFrames
df = CSV.read("cities.csv",DataFrame)
mdtable(df,latex=false)
```