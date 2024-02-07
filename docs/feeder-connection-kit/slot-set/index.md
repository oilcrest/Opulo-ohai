# Feeder Slot Set

This section will guide the reader on how to properly assemble and package a `feeder-blade-set`

## Assembly Process
* Begin by separating a `feeder-blade-panel` into its 4x separate rows
	![](img/break-slots2.jpg)
	![](img/break-slots25.jpg)
	![](img/slot-set-3.JPG)

* Install each `blade13-pcb` into a `blade13` 3D print to create `feeder-blade13-asm`
	![](img/place-slots-in-blade2.jpeg)
	![](img/place-slots-in-blade1.jpeg)

* Set `feeder-blade13-asm` into the `feeder-blade-cradle-jig`
	![](img/place-blade-in-jig.jpeg)

* Proceed to install 5x `M3x8-self-threading-screw` into the WIP `feeder-blade13-asm`
	* Use an automatic torque driver set to `6`
	
	![](img/install-m3-screws.jpeg)
	
* Use `clear loctite` to attach a `blade-pin-cover` over the 2x exposed IDC connector pins in the `feeder-blade13-asm`
	* Do not leave any excess glue be shown on the exposed PCB
	* Leave the glue to dry for 5 minutes before continuing
	![](img/install-caps.jpeg)
* Remove the blades from the `feeder-blade-cradle-jig`
* Loosely install 5x `M5-t-slot-nut` and 5x `M5x10-bolt` into each feeder blade for subsequent use in mounting onto a feeder rail
	![](img/install-t-nut1.jpeg)
	![](img/install-t-nut2.jpg)

* Repeat these above steps until you have created 2x `feeder-blade13-asm` and 2x `feeder-blade12-asm`
	* The steps to make the `feeder-blade12-asm` are the same as the 13-gang version, the only differences are that the 3D print and PCB are a 12-slot variant.

!!!success "Once all 4 assemblies have been prepared, you have finished building a `feeder-blade-set`"
	![](img/feeder-blade-set.jpeg)

#Next Steps
The next step is to proceed to either:

* `Feeder Accessory Preparation` - provided you are making a Feeder Connection Kit
* `Front-feeder-rail / Rear-feeder-rail` - provided you are making a LumenPnp V3.2.X