# lab02

## TITLE:
Faraday's Law

## INSTRUCTIONS:
1. The students *should work in group of two* and *submit one lab report per group*.
2. The students will get back their marked lab reports from the TA in the lab/tutorial sessions one week after report submission. Any requests for re-grading of the lab reports must be forwarded to the TA.


## INTRODUCTION:
Faraday’s Law states that a time-varying magnetic flux, $$\Psi$$, creates current flow in a closed circuit. This is another method of producing electric current in a circuit in addition to using a battery or other voltage/current supply sources. The time varying magnetic flux creates an induced voltage called Electromotive force or EMF, $$V_\text{emf}$$, in the closed circuit.
$$
V_\text{emf}=-N\frac{d\Psi}{dt}
$$

$$N$$ is the number of turns in the circuit and $$\Psi$$ is the magnetic flux through each turn. The negative sign indicates that the induced EMF opposes the time rate change of original magnetic flux (Lenz’s Law). This means the direction of induced current in the circuit should be such that the magnetic field produced by it should oppose the original $$\text{B}$$ created induced EMF.

The key concept in generation of is having a time-varying magnetic flux which can be created by
1. Having a time-varying loop area in a static $$\text{B}$$ field (Motional EMF)
2. Having a stationary loop in a time-varying $$\text{B}$$ field (Transformer EMF)
3. Having a time-varying loop area in in a time-varying $$\text{B}$$ field

The set-up in this lab provides a means for observation of transformer and motional EMF. The set-up has two large coils (Helmholtz coils) fixed on a base and a secondary small coil which can be rotated.


## OBJECTIVE:
In this experiment, we are investigating three methods for inducing electromotive force in a circuit;
- **A moving magnet,**
- **A moving coil,**
- **A time-varying field**


## EQUIPMENTS:
- Function Generator and a Power supply
- Helmholtz Coils
- Magnet
- Oscilloscope
- Banana Cables and Adaptors
- Multimeter


## 1. A MOVING PERMANENT MAGNET
1. Orient the secondary coil (small coil) such that it is parallel to the Helmholtz coils and connect it to Channel 1 of oscilloscope. Adjust the scope so that the time/division is quite slow (0.5 or 1 S) and use Auto triggering.
Hold a magnet so that one of its poles faces the secondary coil and quickly move the magnet towards the secondary coil.
2. Stop and without changing its orientation reverse the motion and move magnet away.
3. Flip the magnet so that the other pole faces the coil repeat the procedure.
    - **Q.** Describe the qualitative difference between the signals you observe on the oscilloscope display in the following four cases?
        - stationary magnet,
        - moving magnet toward the coil,
        - moving the magnet away from the coil and
        - flipping the magnet and moving toward the coi


## 2. MOVING COIL
1. Connect your multimeter in series with Helmholtz coil and adjust it to $$10\:\text{A}$$ setting. Turn on the power supply and put $$2\:\text{A}$$ through the Helmholtz coil.
2. Rotate the secondary coil.
	- **Q.** Describe what you observe on the oscilloscope. How large in amplitude is the induced $$V_\text{emf}$$? Include an approximate sketch of the signal or take a picture of the signal on oscilloscope display and include it in your report.
3. Orient the secondary coil so that it is parallel to Helmholtz coil. Wiggle it back and forth a little and observe the signal on the oscilloscope. Now, orient the secondary coil so that it is perpendicular to Helmholtz coils and wiggle it up and down a little.
	- **Q.** In which case do you see a larger EMF voltage?


## 3. A TIME-VARYING FIELD.
1. Connect a function generator to the Helmholtz coil and supply a sinusoid voltage with the RMS current of $$10\:\text{A}$$ reading on the multimeter (that is in series with the Helmholtz coil).
	- **Q** Determine which orientation of the secondary coil results in the maximum Vemf. Why?
	- **Q** Describe what you observe on the oscilloscope. How large in amplitude is the induced $$V_\text{emf}$$? Include an approximate sketch of the signal or take a picture of the signal on oscilloscope display and include it in your report.
