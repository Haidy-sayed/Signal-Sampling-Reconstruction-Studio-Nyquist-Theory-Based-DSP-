Signal Sampling & Reconstruction Studio Nyquist Theory Based [DSP]


**Digital Signal Processing · Python · PyQt5**

A desktop application demonstrating the **Nyquist-Shannon Sampling Theorem** through interactive visualization. Users compose signals from sinusoidal components, sample them at configurable multiples of the Nyquist rate, and reconstruct them using **Whittaker-Shannon sinc interpolation** — directly observing aliasing and reconstruction fidelity in real time.

---

## Key Features

- **Signal Composer** — synthesize custom signals by superimposing sinusoids with independent frequency, magnitude, and phase; export as `.csv`
- **Nyquist-Aware Sampling** — FFT-based $F_{max}$ detection drives a live Nyquist rate calculation; a slider sweeps from $0.5\times$ (aliasing) to $4\times$ (oversampled)
- **Sinc Reconstruction** — vectorised Whittaker-Shannon interpolation via NumPy matrix multiplication for real-time performance


---

## Stack

`Python 3` · `PyQt5` · `pyqtgraph` · `NumPy` · `SciPy` · `pandas`

```bash
pip install PyQt5 pyqtgraph numpy scipy pandas
python Task2GUI_mainFinal.py
```

---

## Skills Demonstrated
Nyquist-Shannon theorem · FFT analysis · Sinc interpolation · Vectorised numerical computing · PyQt5 GUI architecture