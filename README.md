**This workshop is under development.**  Please contact Michele Tobias at mmtobias@ucdavis.edu with questions.

**To Do**
1. Most of these methods focus on point data - are there methods that work for lines and polygons or is that not a thing yet?
2. Workshop data - Maybe the SF street tree dataset?
3. Workshop storyline - what will we be doing?  Is there a plausible use-case?
4. Is this really 2 or 3 workshops? Geostats can easily be it's own.



# Introduction
This is an introductory spatial stats workshop in R.

# Learning Objectives
By the end of this workshop, participants should understand
1. Why spatial data requires a different approach than non-spatial data
1. The basics of statistical data description for spatial data
1. Some uses of spatial statistics methods
1. How to use R to implement these concepts

# Set Up
For this workshop, you will need:
1. Install R and RStudio
1. Download the workshop data

# Outline

## Why Spatial Stats?
1. Assumptions - compare with traditional statistics
1. What are the key reasons to use spatial statistics?  
1. What problems does this solve?

## Descriptive Spatial Statistics
1. Summarize a dataset
1. directional trends - example: find the center of a set of points (equivalent to the mean)
1. centroid (central tendency)
1. dispersion - how far apart are the points? - present with covariance matrix?

## Point Pattern analysis
Answers questions like:
1. is there a structure to the data?
1. is the data clustered or dispersed?

Spatial regression = what factors contribute to the spatial pattern?

## Geostatistics
Predicting values using nearby data

1. Variograms
1. Model parameters
1. Interpolation methods - example: inverse distance weighted, kriging, etc.
