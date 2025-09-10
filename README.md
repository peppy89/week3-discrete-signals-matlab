# Discrete-Time Signals in MATLAB

This MATLAB project demonstrates the generation and visualization of common discrete-time signals using `stem()` plots. Each signal is generated over a finite range of \( n \) values from -10 to 10. The code includes comments explaining each step.

---

## Discrete-Time Signals

1. **Unit Impulse Signal (δ[n])**  
   - Definition: δ[n] = 1 at n = 0, and 0 elsewhere.  
   - Represents a single pulse at the origin.  
   - Commonly used as a building block for other signals.

2. **Unit Step Signal (u[n])**  
   - Definition: u[n] = 1 for n ≥ 0, and 0 otherwise.  
   - Represents a signal that "turns on" at n = 0.

3. **Unit Ramp Signal (r[n])**  
   - Definition: r[n] = n for n ≥ 0, and 0 otherwise.  
   - Represents a linearly increasing signal starting at n = 0.

4. **Exponential Signal (x[n] = a^n)**  
   - Definition: x[n] = a^n, where `a` is a constant.  
   - Models signals that grow or decay exponentially depending on the value of `a`.

5. **Signum Function (sgn[n])**  
   - Definition: sgn[n] = -1 for n < 0, 0 for n = 0, and 1 for n > 0.  
   - Represents the sign of a signal at each discrete time point.

6. **Sinc Function (sinc[n])**  
   - Definition: sinc[n] = sin(n)/n (normalized in MATLAB as sinc(n/π)).  
   - Commonly appears in signal processing as the idealized response of a low-pass filter.

---

## Instructions for Running the Code

1. Make sure you have **MATLAB** installed on your computer.  
2. Download or copy the MATLAB script file (e.g., `discrete_signals.m`) into a folder.  
3. Open MATLAB and navigate to the folder containing the script.  
4. In the Command Window, type the script name (without `.m`) and press **Enter**:  
   ```matlab
   discrete_signals
