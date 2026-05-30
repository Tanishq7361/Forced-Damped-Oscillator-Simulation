# Forced-Damped Oscillators, Resonance and Beats

⚡ Computational Physics project focused on studying forced oscillations, resonance phenomena, and beat formation using numerical methods in Python. The project investigates the response of damped and undamped harmonic oscillators under external periodic forcing through simulations and graphical analysis.

---

## Topics Covered

- Harmonic Oscillators
- Forced Oscillations
- Damped Oscillators
- Resonance
- Beats Phenomenon
- Frequency Response Curves
- Numerical ODE Solvers
- Scientific Visualization

---

## Problems Simulated

### 1. Forced-Damped Oscillator

The system studied is:

$$
\ddot{x} + 2\beta\dot{x} + \omega_0^2x = F_0\cos(\omega t)
$$

with:

- Driving force amplitude $F_0 = 1$
- Natural frequency $\omega_0 = 2.5$
- Damping coefficient $\beta = 0.5$

The simulation analyzes:

- Transient behavior
- Steady-state oscillations
- Resonance effects
- Amplitude variation with driving frequency

---

### 2. Resonance Analysis

The resonance frequency is given by:

$$
\omega_{res}=\sqrt{\omega_0^2-2\beta^2}
$$

The response of the oscillator is studied for frequencies below, near, and above resonance to observe maximum energy transfer.

---

### 3. Resonance Curve

The driving frequency is varied over a wide range and the steady-state amplitude is measured to generate the frequency response curve.

This demonstrates:

- Resonance peak formation
- Damping effects
- Frequency-dependent response

---

### 4. Undamped Oscillator and Beats

The system studied is:

$$
\ddot{x}+x=\cos(\omega t)
$$

The simulation explores:

- Off-resonance oscillations
- Near-resonance behavior
- Beat formation
- Growth of oscillation amplitude near resonance

---

## Technologies Used

- Python
- NumPy
- Matplotlib
- SciPy
- Jupyter Notebook

---

## Features

- Numerical solution of second-order differential equations
- Forced and damped oscillator simulation
- Resonance frequency analysis
- Beat phenomenon visualization
- Frequency response curve generation
- Interactive scientific plotting

---

## Key Observations

- Damping reduces the resonance amplitude.
- Maximum oscillation occurs near the resonance frequency.
- Transient oscillations decay with time, leaving only steady-state motion.
- Beats occur when the driving frequency is close to the natural frequency.
- As the frequencies become closer, the beat period increases significantly.

---

## Conclusion

This project demonstrates the fundamental behavior of driven harmonic oscillators, including resonance and beat phenomena. Through numerical simulations, it highlights the role of damping, driving frequency, and energy transfer in oscillatory systems.

---

## How to Run

Clone the repository:

```bash
git clone <repository-link>
```

Install dependencies:

```bash
pip install numpy matplotlib scipy jupyter
```

Run the notebook:

```bash
jupyter notebook
```
