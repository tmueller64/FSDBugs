# FSDBugs

This repository provides a way to track bugs in the Tesla FSD software via the GitHub Issues feature. 

## Legal Disclaimer

The information contained in this repository is provided for informational purposes only and does not imply any suitability for use of Tesla FSD software. This repository is not affiliated with or endorsed by Tesla, Inc. Use of the information in this repository is at your own risk.

## Bug Tracking 
This repository is limited to tracking bugs; it isn't meant to record feature ideas or driving preferences. There is a fine line between the car driving wrong and 
the car not driving the way you would drive. So sometimes it is a judgement call as to whether something is a bug. 

## Bug Filing Guidelines
Here is some information to include when filing a bug:
- Description of the wrong behavior
- Expectation of what the correct behavior should be
- Where was this observed to happen
- How frequently does it happen
- What is required to avoid or correct the behavior (see labels)
- Video (if available)
- The version of FSD where this was observed
- Details about the car being used (model, FSD hardware)
- Has the issue been reported to Tesla

When an issue is fixed by Tesla, then it can be closed. 

## Labels
Here are some labels that are associated with bugs to facilitate searching.

### disengagement required
Used for a bug that requires the driver to perform a disengagement in order to correct or avoid the wrong behavior. A disengagement is achieved by pressing the 
brake pedal, moving the steering wheel, or pushing the stalk. Often this label indicates a potential safety issue. 

### intervention required
Used for a bug that may require the driver to perform an intervention in order to correct the wrong behavior. An intervention is achieved by pressing on the accelerator
pedal, moving a scroll wheel, moving the stalk up or down, or changing the driving profile. An intervention does not cause FSD to disengage. 

### legacy S/X
Used for a bug that has been observed on a legacy Model S/X vehicle. These cars were manufactured up through the first part of the 2021 model year. 

## Milestones
The GitHub milestone feature is used to identity the FSD version(s) where this bug was most recently observed. GitHub only allows a single milestone 
to be associated with an issue. Details about all of the FSD releases including release 
notes are available at [notateslaapp.com](https://www.notateslaapp.com/fsd-beta/).

