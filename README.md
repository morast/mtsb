# mtsb

A step sequencer with individual length per step. Aswell as repetions and de/increments per step and some randomness. Inspired by the work of Mark Fell.

Patch, is intended to be used "patch-wise", but it can be transformed into an abstraction easily.
Sends (ID representing the instance of mtbs, to be found on top beneath transport):
[r mtsb-ID-duration]: Duration of current step
[r mtsb-ID-gate1]: Events via gate 1 (value-A valueB)
[r mtsb-ID-gate2]: Events via gate 2 (value-A valueB)
[r mtsb-ID-length]: TotalLength of all steps with repeats in ms
[r mtsb-ID-step]: Current step number

Vanilla flavored, no libraries needed. Tested with pd-vanilla 0.54.1


mmmorast 2024
