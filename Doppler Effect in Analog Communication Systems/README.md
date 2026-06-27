# Doppler Effect in Analog Communication Systems Using MATLAB

## 📌 Title

Doppler Effect in Analog Communication Systems Using MATLAB

A MATLAB-based simulation project that demonstrates the Doppler Effect in analog communication systems. The project analyzes how relative motion between a transmitter and receiver causes frequency shifts in received signals and studies its impact on communication systems such as mobile networks, satellite communication, radar, and aircraft communication.

---

## 🛠 Technologies

### Programming Language
- MATLAB

### MATLAB Functions & Tools
- Signal Generation
- Time Domain Analysis
- Frequency Analysis
- Plotting Functions
- Mathematical Modeling

### Concepts
- Analog Communication Systems
- Doppler Effect
- Frequency Shift
- Mobile Communication
- Satellite Communication
- Radar Systems
- Frequency Modulation (FM)
- Amplitude Modulation (AM)
- Signal Processing

---

## ✨ Features

- Simulation of Doppler frequency shift
- Visualization of original and Doppler-shifted signals
- Analysis of transmitter-receiver relative motion
- Comparison of low-speed and high-speed scenarios
- Demonstration of Doppler impact on analog communication systems
- MATLAB-based signal visualization
- Educational tool for communication engineering studies

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Function |
|----------|----------|
| Ctrl + N | Create New Script |
| Ctrl + O | Open Existing File |
| Ctrl + S | Save Script |
| F5 | Run MATLAB Script |
| Ctrl + R | Comment Selected Lines |
| Ctrl + T | Uncomment Selected Lines |
| Ctrl + C | Stop Execution |
| Ctrl + Z | Undo |
| Ctrl + Shift + S | Save As |

---

## ⚙️ The Process

### 1. Define System Parameters

The simulation initializes:

- Carrier frequency (`fc`)
- Relative velocity (`v`)
- Speed of light (`c`)
- Sampling frequency
- Simulation duration

---

### 2. Calculate Doppler Shift

The Doppler frequency shift is calculated using: :contentReference[oaicite:2]{index=2}


::contentReference[oaicite:3]{index=3}


The Doppler shift is given by:

```text
fd = (v/c) × fc
```

where:

- `fd` = Doppler frequency shift
- `v` = Relative velocity
- `c` = Speed of light
- `fc` = Carrier frequency

---

### 3. Determine Received Frequency

The received frequency is calculated as: :contentReference[oaicite:4]{index=4}

```text
fr = fc ± fd
```

- If transmitter and receiver move towards each other → Frequency increases.
- If they move away from each other → Frequency decreases.

---

### 4. Generate Communication Signals

MATLAB generates:

- Original transmitted signal
- Doppler-shifted received signal

These signals are plotted for comparison.

---

### 5. Simulate Different Motion Scenarios

Two practical cases are analyzed:

### Case 1: Car Example

A vehicle moving at low speed (20–50 m/s).

- Produces a very small Doppler shift.
- Frequency change is barely visible in plots. :contentReference[oaicite:5]{index=5}

### Case 2: Rocket/Satellite Example

A high-speed object moving at thousands of meters per second.

- Produces significant Doppler shift.
- Frequency change is clearly visible in graphs. :contentReference[oaicite:6]{index=6}

---

### 6. Analyze Communication Performance

The project studies how Doppler shift affects:

- Signal synchronization
- Frequency tracking
- Demodulation performance
- Communication reliability

---

## 📚 What I Learned

- Fundamentals of Doppler Effect
- MATLAB-based communication system simulation
- Frequency shift analysis
- Analog communication concepts
- Impact of relative motion on communication systems
- Signal generation and visualization
- Communication system impairments
- Frequency compensation techniques

---

## 📈 Overall Growth

This project improved my understanding of analog communication systems by demonstrating how relative motion affects signal transmission and reception. I gained practical experience in MATLAB simulation, frequency analysis, and communication system modeling.

The project strengthened my skills in signal processing, scientific computing, and applying theoretical communication concepts to real-world engineering scenarios.

---

## 🚀 How Can It Be Improved

- Add real-time Doppler compensation algorithms
- Implement Phase Locked Loop (PLL) compensation
- Add Automatic Frequency Control (AFC)
- Include noise analysis
- Simulate fading channels
- Extend to digital communication systems
- Develop a MATLAB GUI
- Add 3D visualization of moving transmitter and receiver
- Integrate real-world mobility datasets

---

## ▶️ Running the Project

### Requirements

- MATLAB R2020a or later

### Steps

1. Open MATLAB.
2. Create a new script.
3. Copy and paste the MATLAB code.
4. Save the file as:

```text
doppler_effect_simulation.m
```

5. Run the script by pressing:

```text
F5
```

### Expected Output

The simulation generates:

- Original transmitted signal
- Doppler-shifted received signal
- Frequency comparison plots

For low-speed motion, the shifted signal closely resembles the original signal.

For high-speed motion, a noticeable frequency increase or decrease is observed. :contentReference[oaicite:7]{index=7}

---

## 📊 Effect on Communication Systems

| Communication System | Doppler Impact |
|----------------------|---------------|
| AM Communication | Small |
| FM Communication | Large |
| Mobile Communication | Moderate |
| Satellite Communication | Very High |
| Radar Systems | Used for Speed Measurement |

The effect is more severe in FM systems because information is carried in frequency. :contentReference[oaicite:8]{index=8}

---

## 🔧 Methods to Reduce Doppler Effect

### Phase Locked Loop (PLL)

- Tracks incoming signal frequency automatically.
- Maintains synchronization with the transmitter.
- Widely used in FM, mobile, and satellite communication systems. :contentReference[oaicite:9]{index=9}

### Automatic Frequency Control (AFC)

- Corrects frequency errors automatically.
- Keeps the receiver tuned to the transmitted signal.
- Improves communication reliability. :contentReference[oaicite:10]{index=10}

---

## 🚀 Applications

- Mobile Communication
- Satellite Communication
- Aircraft Communication
- Radar Systems
- Wireless Communication
- Navigation Systems
- Space Communication
- Communication Engineering Education

---

## 👨‍💻 Author

**Santos**

---

*"Understanding motion-induced frequency shifts to build robust communication systems."*
