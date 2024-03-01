# LeaderConfidence

## oTree: Main experiment
1. X Trials of simplified version of Iowa Gambling Task (IGT)
2. followed by group and leader assignment based on outcomes
3. These groups perform X trials of Random Dot Motion (RDM) Task

### Gambling Task
Current Status: IGT task is functional in oTree without costs. Which is appropriate for the adapted version we proposed
(Publically available full IGT: https://s3.amazonaws.com/otreehub/browsable_source/25299275-4a15-433a-adb1-17a7a48b134a/iowa_gambling/index.html)
To-do:
+ Adapt decks and their compostion (Three decks with equal expected outcome and same degree of randomization i.e. variance)

### Group Composition / Assignment
To-Do:
+ Assign Leaders based on performance

### Random Dots
Current Status: Python script for the stimulus is functional, but NOT inside of otree
(https://github.com/arminbahl/random_dot_motion)

To-do:
Stimulus:
+ display stimulus inside of oTree App at all
+ display it for set amount of time only

Group Decision Making:
+ All Players Report LEFT or RIGHT
+ Leader chosses whether or not to see the groups' reports
+ Leader makes decision
