# Week 7
## Last Weeks Goals
- Determine exactly what questions will be asked in the tests

This has been completed, and we are hoping to have our questions approved and ethics submitted within the week.

- Develop a method to record signs with the leap motion

This turned out to not be too difficult, as we had already discovered how to access the hand data used by the leap motion a while ago. It was simply a case of saving this data to a file, and then later loading it. Recording a movement was also fairly simple, saving an array of hand datas instead of just a single copy.

- Start working on algorithm to determine distance between hand and required position.

This was unfortunately not started this week due to most of our time being taken up developing the recording technique and recording.

## Sign Recording
We were lucky to have Ramas, a native signer, in recording signs with us on thursday. We unfortunately didn't manage to get an interpreter for the meeting, but text turned out to be sufficient for communication. Apart from a few minor mishaps with the system recording went smoothly and we managed to get almost all the data we needed, excluding the signs that involve movement (there was a problem with our movement recording system at the time, it is now fixed).

## Mapping leap motion hand data onto a hand model
The leap motion stores its hand as a set of points and rotations. While this is fantastic from a computer scientists perspective, as these points and rotations can easily be accessed and manipulated, from a users point of view it would be much better to have the hands as models of an actual hand. The leap motion system can already natively handle this for tracking the users hands, however support for manipulating the hand data with saving and loading is not as present.

## Next Weeks Goals
- Figure out how to map our saved hand data onto a hand model
- Start working on algorithm to determine distance between hand and required position.
