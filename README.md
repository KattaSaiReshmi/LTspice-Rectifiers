# LTspice-Rectifiers
alf-Wave Rectifier
Without Capacitor

When AC voltage is applied, the diode allows only the positive half-cycle to pass and blocks the negative half-cycle. So, current flows through the load only during the positive half-cycle. During the negative half-cycle, no current flows and the output becomes zero. Therefore, the output is a series of positive pulses and is called pulsating DC.

With Capacitor

When a capacitor is connected across the load, it stores energy during the positive half-cycle when the diode conducts. When the input voltage decreases and the diode turns OFF, the capacitor releases its stored energy to the load. Thus, the output voltage does not fall to zero immediately. The capacitor fills the gaps between the pulses, making the output smoother and reducing ripple.

Full-Wave Rectifier
Without Capacitor

In a full-wave rectifier, both positive and negative half-cycles of the AC input are converted into positive output. Current flows through the load during both half-cycles. Therefore, the output contains more pulses and is smoother than that of a half-wave rectifier, but it is still pulsating DC.

With Capacitor

The capacitor charges whenever the output voltage reaches a peak. When the voltage starts decreasing, the capacitor supplies energy to the load. Since charging occurs in every half-cycle, the capacitor does not discharge much before being recharged again. As a result, the output voltage becomes almost constant and the ripple is greatly reduced.

Conclusion

A rectifier converts AC into DC. Adding a capacitor acts as a filter that stores energy and supplies it to the load when the rectifier output decreases, producing a smoother DC output.
