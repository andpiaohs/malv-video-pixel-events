# malv-pixel-video-events

As part of the Pixel Remediation work, this repository contains noteworthy Kibana logs ran from the Malv script relating to pixel firing events, video playback events, and associated VAST responses. 

## Objective
The goal of this investigation is to establish a link between pixel firing events and video playback events collected by the Malv script in order to assess whether our FS pixels are firing in the correct timing.

## Setup
Each set of data is organized by action_group_ids representing a session that for a set of logs that is set when the Malv script initializes. 

Each set of data contains:
- video playback event
- pixel firing event
- VAST XML response (if available)
