<div align='center'><h2><a href='https://overextended.github.io/docs/ox_target/'>Documentation</a></h2></div>

## Note
This is a RedM version of ox_target modified by [Rexshack](https://github.com/Rexshack-RedM). I just removed the function that use rsg-core to make this standalone and changed the version check to default ox_lib version check. All the credit goes to Overexteded and Rexshack for make it work in RedM.

## ox_target
A performant and flexible standalone "third-eye" targeting resource.

ox_target is the successor to qtarget, which was a mostly-compatible fork of bt-target.
To improve many design flaws, ox_target has been written from scratch and drops support for bt-target/qtarget standards, though partial compatibility is being implemented where possible.

- Performance increased ~4x compared to qtarget.
- Improved error handling protects against soft-locking.
- Improved entity and world collision detection.
- Options now stack, rather than overriding.