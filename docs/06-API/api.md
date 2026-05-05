---
title: Module API
---

## Overview

Subsystem B2 will handle all messages passed along the communication daisy chain, but the only message B2 will act upon are the ones that dictate the steering angle. All other messages will simply be passed along until they reach their desired recepient. All other message types can be found on [*this*](https://egr314-s-2026-201.github.io/04-Team-Block-Diagram/Team-Diagram/) page of the team report for Team 201.

Message Type A - Set Steering Angle

||**Byte 1** |**Byte 2**|**Byte 3**|**Byte 4**|
| :-------: | :-------: | :-------: | :-------: | :-------: |
| Variable Name | Sender_ID | Reciever_ID | Message_Type | Angle |
| Variable Type | char | char | char | uint8_t |
| Min Value | A | E | A | 0 |
| Max Value | A | E | A | 255|
| Example | A | E | A | 125 |

The code for Subsystem B2 can be found [here.](actual_final_rudder_code.X.zip)