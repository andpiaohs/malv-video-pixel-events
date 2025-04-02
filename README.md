# malv-pixel-video-events

As part of the Pixel Remediation work, this repository contains noteworthy Kibana logs ran from the Malv script relating to pixel firing events, video playback events, and associated VAST responses. 


## Setup
Each set of data is organized as its own directory labeled by their `action_group_id`. This identifier value is set when the Malv script initializes and represents a set of logs associated with a particular session.

Each data set will contain:
- video playback events
- pixel firing events
- VAST XML responses (if available)

## Objective
The goal of this investigation is to establish a link between pixel firing events and video playback events collected by the Malv script in order to assess whether our FS pixels are firing in the correct timing.
