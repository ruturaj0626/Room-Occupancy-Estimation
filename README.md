# Room Occupancy Estimation
![Room Occupancy Estimation](/Room%20Occupancy%20Estimation.png)

Welcome to the Room Occupancy Estimation repository, your comprehensive resource for exploring occupancy estimation using non-intrusive sensors in a controlled environment. Whether you're a researcher, developer, or just curious, this repository provides data, code, and insights to deepen your understanding.

## Experimental Setup

Our experiments unfolded within a precisely measured room, spanning 6 meters by 4.6 meters. We meticulously orchestrated a testbed comprising 7 sensor nodes and an edge node interconnected in a star configuration. These sensor nodes transmitted data wirelessly to the edge node at 30-second intervals. Importantly, HVAC systems remained inactive throughout the data collection phase to maintain consistent environmental conditions.

## Sensor Types

Our sensor array encompassed various non-intrusive sensors to capture multiple facets of the room environment:

1. **Temperature**: Monitoring thermal conditions within the room.
2. **Light**: Measuring ambient light levels for insights into occupancy patterns.
3. **Sound**: Employing sound sensors, essentially microphones, equipped with adjustable gain amplifiers. These sensors output data in analog format (volts).
4. **CO2 (Carbon Dioxide)**: Assessing air quality by measuring CO2 levels. Rigorous calibration ensured data accuracy.
5. **Digital Passive Infrared (PIR)**: Positioning PIR sensors on ceiling ledges for maximum motion detection coverage.

## Calibration Details

To guarantee data precision, our sensors underwent meticulous calibration:

### CO2 Sensor Calibration
Zero-point calibration was conducted before the initial use of the CO2 sensor. This involved placing the sensor in a clean environment for over 20 minutes and then performing a calibration step by pulling the calibration pin (HD pin) low for over 7 seconds.

### Sound Sensor Calibration
We calibrated sound sensors by adjusting the potentiometer linked to the amplifier's gain. This optimization ensured sensors operated at their maximum sensitivity, capturing even subtle acoustic changes.

### PIR Sensor Calibration
Our PIR sensors featured two adjustable trimpots. One trimpot fine-tuned sensitivity, while the other determined the duration of the sensor's output staying high after motion detection. Both trimpots were set to their highest values for peak performance.

## Data Collection

Data collection extended over four days, with careful monitoring of room occupancy fluctuating between 0 and 3 people. We manually recorded occupancy counts to establish ground truth, serving as vital reference data for our occupancy estimation experiment.

## Usage

This repository provides valuable resources for various purposes:

### Data Exploration
- Explore the rich dataset within the "data" folder, which includes sensor readings and corresponding occupancy labels.

### Experiment Replication
- Review the "code" directory to access scripts and code used in the experiment, enabling replication and further research.

### Sensor Calibration
- Learn from our calibration procedures in the "calibration" folder to apply similar techniques in your projects.

### License

This repository is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute the code and data while giving appropriate credit.

Should you have any questions, require assistance, or wish to collaborate, please don't hesitate to reach out by creating an issue or contacting the repository owner.

Feel free to star this repository if you find it useful!

**ChatGPT**
