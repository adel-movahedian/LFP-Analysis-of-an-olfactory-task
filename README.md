# Analysis of LFP Signals during Olfactory Task

## Introduction
Welcome to the Neuroscience project! This project involves the analysis of Local Field Potential (LFP) signals derived from the brain of an anesthetized rat during an olfactory task. The LFP signal comprises three distinct channels:

1. Hippocampus (HPC)
2. Olfactory Tubercle (OT)
3. Medial Prefrontal Cortex (mPFC)

Throughout the task, the rat was exposed to two different odorants:

1. Banana (tag = "20")
2. Lime (tag = "40")

Each odorant was presented with an equal probability of 50%. This implies that 50% of the time, the rat was exposed to the banana odor, and the remaining 50% to the lime odor. Upon cessation of odorant release, the resting state (tag = "10") commenced, devoid of any odor stimuli.

**Note:** The 4th channel is digitalByte, which contains the event tags [10, 20, 40] in time.

## Analysis Steps
This project includes the following analysis steps:

1. **Data Loading and Exploration**:
   - Load the LFP data file.
   - Print information about the channels and event tags.
   
2. **Preprocessing**:
   - Apply preprocessing techniques such as filtering, artifact removal, and baseline correction to the LFP signals.
   
3. **Power Spectral Density (PSD) Analysis**:
   - Compute the PSD of each channel to analyze the frequency content of the LFP signals.
   
4. **Event-Related Potentials (ERPs)**:
   - Compute the ERP for each event type (banana, lime, resting state) to analyze the evoked responses.
   
5. **Phase-Locking Value (PLV)**:
   - Calculate the PLV to measure phase synchronization between different brain regions.
   
6. **Phase-Amplitude Coupling (PAC)**:
   - Compute PAC to analyze the coupling between the phase of low-frequency oscillations and the amplitude of high-frequency oscillations.
   
7. **Time-Varying Phase-Amplitude Coupling (tv-PAC)**:
   - Calculate tv-PAC to investigate dynamic changes in PAC over time.

## Usage
To use this project:

1. **Data Preparation**:
   - Ensure the LFP data file is available in the project directory.

2. **Running the Code**:
   - Run the Python scripts corresponding to each step in the analysis process.

## Dependencies
This project requires Python 3.x and the following libraries:
- numpy
- scipy
- matplotlib
- mne (for EEG/MEG data analysis)
- scikit-learn
- neurodsp

You can install these dependencies using pip:
```
pip install numpy scipy matplotlib mne scikit-learn neurodsp
```

## Contributing
Contributions are welcome! If you'd like to contribute to this project, please fork the repository, make your changes, and submit a pull request.

## Contact
For any questions or feedback, feel free to reach out to [adel.mov1382@gmail.com](adel.mov1382@gmail.com).

