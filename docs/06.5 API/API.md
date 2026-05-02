## Overview

My board sends my personal data from my temperature sensor and passes along packet data from previous sensors in the daisy chain, it also receives a "Rollcall" message. Below are all possible messages I will be sending or receiving.

## Messages

**Send Temperature**
||**Byte 1** |**Byte 2**|**Byte 3**|**Byte 4**|
| :-------: | :-------: | :-------: | :-------: | :-------: |
| Variable Name | Sender_ID | Reciever_ID | Message_Type | Temperature |
| Variable Type | char | char | uint8_t | uint8_t |
| Min Value | I | A | 7 | 0 |
| Max Value | I | A | 7 | 255 |
| Example | I | A | 7 | 125 | 

**Send Distance**
||**Byte 1** |**Byte 2**|**Byte 3**|**Byte 4**|
| :-------: | :-------: | :-------: | :-------: | :-------: |
| Variable Name | Sender_ID | Reciever_ID | Message_Type | Distance |
| Variable Type | char | char | uint8_t | uint8_t |
| Min Value | J | A | 6 | 0 |
| Max Value | J | A | 6 | 255 |
| Example | J | A | 6 | 125 | 

**Send Speed data**
||**Byte 1** |**Byte 2**|**Byte 3**|**Byte 4**|
| :-------: | :-------: | :-------: | :-------: | :-------: |
| Variable Name | Sender_ID | Reciever_ID | Message_Type | Speed |
| Variable Type | char | char | uint8_t | uint8_t |
| Min Value | H | A | 5 | 0 |
| Max Value | H | A | 5 | 255 |
| Example | H | A | 5 | 125 | 

**Rollcall**
||**Byte 1** |**Byte 2**|**Byte 3**|
| :-------: | :-------: | :-------: | :-------: |
| Variable Name | Sender_ID | Reciever_ID | Message_Type |
| Variable Type | char | char | uint8_t |
| Min Value | A | X | 12 |
| Max Value | J | X | 12 |
| Example | A | J | 12 | 
