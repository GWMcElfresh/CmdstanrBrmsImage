# genie-in-a-model
A docker image for running general statistical extensions on exacloud.

Features tidyverse, brms, and cmdstanr backend on top of cellmembrane. 

Hacks: There's an hpp file issue with the current version of cmdstanr, so this is pegged to 2.2.0 until something like: https://github.com/stan-dev/cmdstanr/pull/863 is implemented.
