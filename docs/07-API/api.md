---
title: Module API
---

## Overview

The only API that Subsystem B2 will be handling is receiving commands concerning the steering angle. As Team 201 further develops the prototype, the rudder subsystem may incorporate another possible message that informs the controller of the steering angle the rudder has been positioned to.

Message type 1 - Set Steering Angle

||**Byte 1** |**Byte 2**|**Byte 3**|**Byte 4**|
| :-------: | :-------: | :-------: | :-------: | :-------: |
| Variable Name | Sender_ID | Reciever_ID | Message_Type | Angle |
| Variable Type | char | char | uint8_t | uint8_t |
| Min Value | A | E |1 | 0 |
| Max Value | A | E | 1| 255|
| Example | A | E |1 | 125 | 