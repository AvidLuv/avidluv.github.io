<strong>Line-Following Buggy</strong>: 
    <div style="display: flex; justify-content: space-between; align-items: center;">
        <div style="flex: 1;">
            As a programmer in the line-following robot project at the University of Manchester, I was responsible for reading data from light and speed sensors using C language, processing the sensor data, and implementing a PID algorithm to enable the robot to follow a pre-set white line both swiftly and stably. The entire system was developed on an STM32F401RE microcontroller, and our team secured second place in the final competition. <a href="https://github.com/AvidLuv/stm32-line-followed-buggy">Code</a>
        </div>
        <div style="flex: 1; text-align: right; padding-left: 20px;">
            <img src="static/assets/line_following_buggy.gif" alt="Line-Following Buggy GIF" style="width: 500px !important; max-width: 500px !important; border-radius: 5px;"/>
        </div>
    </div>

<strong>Dynamic Gesture Recognition</strong>: 
    <div style="display: flex; justify-content: space-between; align-items: center;">
        <div style="flex: 1;">
            An independent development of a dynamic gesture recognition system for an embedded system was achieved. The system utilizes the Mediapipe hand keypoints model to extract keypoints from a live video stream. Angle features between keypoint vectors are calculated and stacked to form a time series of gesture features. Fast Dynamic Time Warping (FastDTW) is then applied to measure the similarity between the live gesture's feature time series and the dataset, enabling accurate gesture recognition. <a href="https://github.com/AvidLuv/Dynamic-Gesture-Recognition-by-Using-DTW">Code</a>
        </div>
        <div style="flex: 1; text-align: right; padding-left: 20px;">
            <img src="static/assets/dynamic_gesture_recognition.gif" alt="Dynamic Gesture Recognition GIF" style="width: 500px !important; max-width: 500px !important; border-radius: 5px;"/>
        </div>
    </div>

<strong>Quadrotor UAV Controller</strong>
    <div style="display: flex; justify-content: space-between; align-items: center;">
        <div style="flex: 1;">
            An independently developed flight control program for a quadrotor UAV was implemented using Python. The controller adopts a cascaded PID architecture, enabling the UAV to navigate to predefined target points and perform attitude transitions at each location within a simulated environment built with PyBullet. I was solely responsible for the entire development process, including program implementation and PID parameter tuning. This project is currently in its final debugging stage, so the source code is not publicly available at the moment.
        </div>
        <div style="flex: 1; text-align: right; padding-left: 20px;">
            <img src="static/assets/UAV_controller.gif" alt="Quadrotor UAV Controller GIF" style="width: 500px !important; max-width: 500px !important; border-radius: 5px;"/>
        </div>
    </div>

<strong>Binary Data Decoder</strong>
    <div style="display: flex; justify-content: space-between; align-items: center;">
        <div style="flex: 1;">
            Independently developed a Python program to decode a 26-bit binary data stream originating from a thermal sensor, converting it into human-readable format. The project involved bitwise operations and custom parsing logic to interpret the data structure and extract meaningful temperature information. The 26-byte binary frames contain multiple fields, including system identifiers, sensor readings, and an 8-byte microsecond-resolution timestamp. A checksum algorithm was implemented to validate each frame's integrity, and thermal sensor values were translated into Celsius using a custom lookup table. The decoded data were then exported to CSV format for further analysis. Corrupt or invalid frames were identified based on checksum and sensor value ranges. The first valid timestamp was also used to recover the corresponding calendar date, and basic data quality statistics (e.g., number of corrupted frames) were reported at the end.
        </div>
        <div style="flex: 1; text-align: right; padding-left: 20px;">
            <img src="static/assets/decoding.png" alt="Binary Data Decoder Image" style="width: 500px !important; max-width: 500px !important; border-radius: 5px;"/>
        </div>
    </div>

