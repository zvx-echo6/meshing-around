# What is this and why is it a fork?

This is the Intermountain Mesh's fork for configuration of the BBS network of devices. Using this method ensures that the primary BBS nodes have config settings that are current and functional without being subject to updates until the group as a whole is ready to update them.

## Can you tell me the specific configuration settings this has?
No messages are sent to the primary channel
Games are all turned off
Sentry is enabled and sending its alerts to Channel 2
BBS is enabled
BBS linking is set to a custom schedule that calls every 30 minutes
BBS linking calls through channel 1
This does not have LLM enabled
This will respond to cmd, but does not require the ! to preempt the command.

## Hardware Requirements
You must have a node that has compute. A femtofox, a network connected node, or a portduino node.

You must have the channels configured correctly to ensure proper BBS linking.
0 - Freq51
1 - BBS
2 - Sentry
