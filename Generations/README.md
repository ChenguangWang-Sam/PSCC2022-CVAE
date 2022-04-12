# Explanation for the names of the generated files
- filename with "σ_auto": output noise parameter is co-optimised during training (Auto σ')
- filename with "σ_"+ a "number": output noise parameter is  fixed (Manually set σ')

- filename with "mu": generated data without noise (noise free)
- filename with "noisy": generated data with noise (noisy)

- filename with "Time_all": generated data for 24 hours
- filename with "Time_"+ a "number": generated data for a specific hour of the day

- filename with "nor": generated data that are not rescaled to the original scale of historical data
- filename without "nor": generated data that are rescaled to the original scale of historical data

- filename with a β number: data generated with that specific β number
- filename without a β number: the number of β is 1 by default

- filename with "VAE" specified: it is a VAE model
- filename without "VAE" specified: it is a CVAE model by default

- filename with "35" in the end: a model for 35-dimensional input
- filename without "35" in the end: a model for 32-dimensional input by default
