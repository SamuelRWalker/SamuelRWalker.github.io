---
layout: page
title: ESP32 ADC Characterization
---

## Overview
This independent study focused on ADC characterization using the Adafruit QT Py ESP32-S3 and software-defined instruments. Throughout the project, I developed scripts to test the performance of ADCs and DACs and analyzed key figures of merit.

## Milestone 1 Report
In this phase, I developed a modular program to manage serial communication between the ESP32 and Python scripts. Some key components were:
- **ESP32 Controller and Serial Communication**: Implemented a robust `esp32_communicator.py` script to handle communication between ESP32 and Python.
- **AD2 Controller Integration**: Used the `ad2_controller.py` script to control voltage levels for ADC characterization.
- **Testing and Analysis Helper Functions**: Developed `testing_helper.py` and `analysis_helper.py` scripts to conduct tests and analyze the data.

You can view the full milestone 1 report [here](assets/pdf/adc/Bogatin_IndStudy_Mid.pdf).

<object data="/assets/pdf/adc/Bogatin_IndStudy_Mid.pdf" type="application/pdf" width="700px" height="700px">
    <embed src="/assets/pdf/adc/Bogatin_IndStudy_Mid.pdf">
        <p>This browser does not support PDFs. Please download the PDF to view it: <a href="/assets/pdf/adc/Bogatin_IndStudy_Mid.pdf">Download PDF</a>.</p>
    </embed>
</object>

## Final Report: Software-Defined Instruments
In the final phase, the project focused on developing software-defined instruments to characterize ADC performance:
- **Scope**: Implemented a virtual oscilloscope for capturing waveforms and storing data.
- **Strip Chart**: Developed a strip chart to record data over time and visualize slow-changing signals.
- **RMS**: Calculated the AC RMS value of signals to measure noise levels.
- **DC Calibration**: Implemented tools for precise DC signal calibration to ensure accuracy in measurements.

The report concludes with key insights into the ESP32 ADC's performance and areas for future improvement.

You can view the full final report [here](assets/pdf/adc/Bogatin_IndStudy_Final.pdf).

<object data="/assets/pdf/adc/Bogatin_IndStudy_Final.pdf" type="application/pdf" width="700px" height="700px">
    <embed src="/assets/pdf/adc/Bogatin_IndStudy_Final.pdf">
        <p>This browser does not support PDFs. Please download the PDF to view it: <a href="/assets/pdf/adc/Bogatin_IndStudy_Final.pdf">Download PDF</a>.</p>
    </embed>
</object>

## Key Contributions and Takeaways
- **Modular Scripts**: Developed scalable, modular scripts to manage ADC tests and data collection.
- **Software-Defined Instruments**: Created virtual instruments for data acquisition and analysis, including a scope, strip chart, RMS calculator, and DC calibrator.
- **Future Work**: Planned improvements for the strip chart and RMS functions and identified anomalies in the ESP32 ADC that could be addressed in future research.

This independent study deepened my understanding of ADCs, DACs, and microcontroller-based testing systems, and provided valuable experience in project management and technical development.
