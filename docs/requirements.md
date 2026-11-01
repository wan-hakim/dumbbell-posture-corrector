# Requirements

## Functional requirements
- **FR1:** The system shall capture real-time video stream input of upper body dumbbell exercises standard laptop webcam.
- **FR2:** The system shall extract spatial skeletal keypoint coordinates using a lightweight CNN.
- **FR3:** The system shall compute continuous joint angles using regression model to continuously evaluate exercise posture correctness.
- **FR4:** The system shall display real-time visual feedback, including a green skeletal overlay with a "CORRECT" badge for proper posture and a red skeletal overlay with an "INCORRECT" badge for posture deviations.
- **FR5:** The system shall count the number of completed repetitions during an exercise session.
- **FR6:** The system shall calculate a form quality score for each completed set.

## Non-functional requirements
- **NFR1:** The system shall process continuous video frames at a real-time frame rate of at least 30 Frames Per Second (FPS) on standard consumer hardware.
- **NFR2:** The system shall deliver visual posture correction feedback to ensure immediate user notification during ongoing movement reps.
- **NFR3:** The system shall process all video on the user's device and shall not store or upload any video frames.
- **NFR4:** A first-time user shall be able to start an exercise session without reading instructions.
