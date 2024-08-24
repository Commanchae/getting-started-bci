# Getting Started with Brain-Computer Interfaces
## Preface
I'm a university student who's interested in the field of brain-computer interfaces. I was motivated to write this repository to serve as my personal Wiki or documentation that I can refer to for my learnings and understandings. As such, the content may not be fully accurate, but I will aim to put citations or sources for information!

As of now, I think the best way to break down the topics is the following. (The organization will change as I learn more)

## What are Brain-Computer Interfaces (BCIs)?
### Definition of BCI
### Applications of BCIs

## Understanding of Brain Signals as Data (BSaD)
In BCI applications, the main source of input is from electroencephalogram (EEG) tests, which measure electrical activity in the brain via electrodes placed on the scalp. Note that the measurements are done relative to a reference electrode. (https://www.hopkinsmedicine.org/health/treatment-tests-and-therapies/electroencephalogram-eeg). Each hardware used in collecting EEG data may have different sampling rates, which tell us how many data points can be collected within a second. The Muse 2, for example, has a sampling rate of 256 Hz, meaning that the device will record 256 data points every second.

The collected EEG data will often have the dimensions [C, T] or [T, C], where C refers to the number of channels (number of electrodes used) and T refers to the timesteps. A 1-second recording by the Muse 2 would have dimensions [5, ~256]. The reason a tilde (~) was used there is because there may be delays or errors within the recording method that may result in timesteps unequal to the sampling rate.

### Considerations for BSaD
#### Noise
#### Artifacts
### Processing Techniques

## How I Got Started

