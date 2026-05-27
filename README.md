# RF-1GHz-Hairpin-Filter-AWR
Designed λ/4 harmonic suppression stubs at 2nd and 3rd harmonics for a 1 GHz hairpin bandpass filter, reducing spurious responses and improving out-of-band rejection. Optimized stub spacing and layout to preserve passband performance and return loss using AWR Microwave Office.

# Overview

In microstrip hairpin bandpass filters, unwanted harmonic responses appear at higher frequencies (2nd, 3rd harmonics, etc.) due to the resonant behavior of transmission line structures. These spurious passbands reduce filter selectivity and can interfere with adjacent RF systems.

To address this, harmonic suppression stubs are incorporated into the design.

# Design Principle
Quarter-wavelength (λ/4) open-circuited stubs are used
Designed at:
2nd harmonic (2f₀)
3rd harmonic (3f₀)

👉 At these frequencies, the stubs behave like short circuits, effectively suppressing unwanted signals.

# Key Design Considerations
Stub lengths are calculated using guided wavelength (λg) on RO4003 substrate
Stub spacing is optimized to:
Minimize impact on passband (1 GHz)
Maintain good return loss (S11)
Stubs are folded to reduce PCB area
Requires co-optimization with the main hairpin filter
# Simulation Results (AWR Microwave Office)
Significant suppression at 2nd and 3rd harmonic frequencies
Minimal degradation in passband insertion loss (S21)
Slight shift in response corrected through optimization
# Key Outcome

The addition of harmonic stubs improved out-of-band rejection while maintaining desired bandpass characteristics, making the filter suitable for practical RF applications.

🚀 Tools Used
AWR Microwave Office
Microstrip models (MLIN, MLEF, MCROSS, MCURVE)
