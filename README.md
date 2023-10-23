# Music and Movement Correlation Experiment

## Overview
This experiment explores the correlation between music and movement by analyzing various metrics extracted from audio and movement data. The analysis is performed on data collected from subjects as they move to the rhythm of the music. The code provided processes the movement data, extracts relevant audio features, and performs correlation analysis to find any coinciding peaks and troughs between the music and movement data.

## Dependencies
- Python 3.x
- NumPy
- Pandas
- Matplotlib
- SciPy

## Setup
1. Ensure you have Python 3.x installed on your machine. You can download Python from [here](https://www.python.org/downloads/).
2. Install the required libraries using pip:
```bash
pip install numpy pandas matplotlib scipy
```
3. Clone this repository to your local machine or download the code files.
```bash
git clone <repository-url>
```
4. Place your data files in the `data` directory.

## Data Structure
Ensure your data is structured as follows:
- Audio data should be placed in a CSV file with columns for time, and various audio features such as RMS, spectral flux, brightness, etc.
- Movement data should be placed in a separate CSV file with columns for time, and various movement metrics.

## Code Structure
- `experiment_notebook.ipynb`: This Jupyter Notebook contains all the code required to run the experiment. It includes data processing, audio analysis, movement analysis, and correlation analysis sections.

## Running the Experiment
1. Navigate to the root directory of the code.
2. Open the `ExaminingCorrelationMusicMovement.ipynb` notebook using Jupyter Notebook:
```bash
jupyter notebook ExaminingCorrelationMusicMovement.ipynb
```
3. Run the notebook cells in sequence to execute the experiment.

## Output
The output of the experiment will include:
- Plots showing the audio features over time.
- Plots showing the movement data over time.
- Plots showing the correlation between audio features and movement data.
- Console output showing any significant findings, such as coinciding peaks and troughs.

## Understanding the Output
- The code calculates and prints the number of coinciding peaks and troughs between audio features and movement data.
- The percentage of coinciding peaks and troughs is also calculated and printed.
- The plots generated provide a visual representation of how the audio features and movement data correlate with each other.

## Customization
- You can customize the analysis by modifying the parameters defined within the relevant cells in the `ExaminingCorrelationMusicMovement.ipynb` notebook.

## Contributing
If you find any bugs or have suggestions for improvements, feel free to open an issue or create a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
