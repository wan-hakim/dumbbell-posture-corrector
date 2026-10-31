# Requirements

## Functional requirements (what the system must DO)
1. The system capture real-time video stream input of upper body dumbbell exercises (specifically Dumbbell Shoulder Press and Dumbbell Bicep Curl) using a standard RGB webcam.
2. The system extract spatial skeletal keypoint coordinates using a lightweight MobileNetV3 CNN backbone and MediaPipe Pose estimation.
3. The system compute continuous joint angles using a Dense Linear Layer regression model to continuously evaluate exercise posture correctness.
4. The system display real-time visual feedback, including a green skeletal overlay with a "CORRECT" badge for proper posture and a red skeletal overlay with an "INCORRECT" badge for posture deviations.
5. The system automatically count exercise repetitions and calculate an overall form quality performance score based on movement consistency.

## Non-functional requirements (how the system must PERFORM)
1. The system process continuous video frames at a real-time frame rate of at least 30 Frames Per Second (FPS) on standard consumer hardware.
2. The system deliver visual posture correction feedback with ultra-low processing latency to ensure immediate user notification during ongoing movement reps.
