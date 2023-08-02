# MemorialHall

This is a Pure Data "Interactive Dialogue" project where there is a virtual memorial hall - as you move through the space, the background sound changes in pitch. Different music excerpts are floating around this hall. This was simulated using four actual speakers and two phantom speakers. Within this seemingly infinite memorial hall, the audience can explore excerpts from different pieces. The user is exploring the virtual sound space using a game controller. This project is intended to be a form of liminal soundscape/space.


The player moves through this space with a PS4 controller connected to a Pure Data patch that sends signals to the Max patch, which creates the sounds. The sounds are then relayed to a special room with four speakers in the corners.


Materials


● Input: PlayStation 4 Game Controller, connected to a laptop by a long USB cable.

● Output: Four-speaker set-up along the room. (Snellius room 413 was used for this.)


Software:

○ Pure Data and externals: else and hidio

○ Max 8.2.2 and externals: Spat 5.2.7

○ NI Kontakt 6.7.1 (We used this to load VSTs to create a richer sound; however, any audio source that
supports MIDI input can also be used.)
