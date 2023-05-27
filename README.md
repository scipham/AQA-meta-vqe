# AQA-meta-vqe

 **!! NOTE: The python + cirq notebook is legacy code for reference. It should work fine but the Julia + Yao Edition is much more up-to-date and tested. !!**
 
The Julia Edition notebook requires Julia v1.7+. However, v1.9 is highly recommended and tested. 
Required Julia packages: StatsBase.jl, Distributions.jl, StatsPlots.jl, Plots.jl, Yao.jl, YaoPlots.jl, Optimization.jl, JLD.jl and ProgressMeter.jl

But you may need additional packages, depending on your needs. By default we also try to import Zygote.jl, OptimizationOptimisers.jl, OptimizationNLopt.jl, OptimizationMultistartOptimization.jl

For performance acceleration on either CPUs or GPUs we also recommend to install MKL.jl, CUDA.jl and CuYao.jl
