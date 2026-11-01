# Problem Statement

## Who is affected?
Beginners, home fitness enthusiasts, students, and casual gym-goers who perform resistance training and dumbbell exercises without professional trainer supervision.

## What exactly is going wrong?
Individuals frequently perform dumbbell movements with improper form, joint misalignment, and spinal hyperextension due to a lack of immediate expert feedback and kinesthetic awareness. Furthermore, existing AI posture solutions rely on heavy models that cause high latency on standard consumer devices or use basic classification models that fail to capture continuous physical movements.

## Why does it matter?
Exercising with incorrect biomechanics reduces target muscle engagement and significantly increases the risk of severe musculoskeletal injuries, such as rotator cuff and spinal strain. Additionally, high-end monitoring software requires expensive hardware or sensors, making safe home exercise inaccessible to many users.

## Problem statement (3 to 5 sentences)
Beginners and home fitness enthusiasts often perform dumbbell exercises with improper posture due to a lack of immediate expert feedback and kinesthetic awareness. Performing these exercises with incorrect form reduces muscle engagement and significantly increases the risk of serious musculoskeletal injuries to the spine and shoulder joints. Hiring personal trainers is expensive, while existing computer vision systems are either too computationally heavy for standard webcams or rely on discrete classification that cannot evaluate continuous physical movement.

## Evidence
Unsupervised weightlifting frequently leads to joint strain and injuries due to poor kinesthetic awareness (Fierro et al., 2022; Williams & Taylor, 2023). Additionally, standard deep CNN models cause significant processing latency and frame-rate drops on everyday consumer hardware, making them impractical for live posture feedback (Wang et al., 2023).

## Users and Stakeholders
* **Primary Users:** Beginners, home fitness enthusiasts, and students who engage in dumbbell resistance training without access to personal trainers.
* **Secondary Stakeholders:** Personal trainers, physical therapists, and fitness app developers interested in automated posture correction and lightweight biomechanical analysis tools.

## Scope

### In Scope
* Upper-body dumbbell exercises.
* Real-time video stream capture using standard laptop webcams
* Skeletal keypoint extraction using MediaPipe Pose and a lightweight CNN backbone.
* Continuous joint angle evaluation using regression.
* Visual real-time feedback.
  
### Out of Scope
* Lower-body or compound resistance exercises.
* Requirement of specialized depth-sensing hardware.
* Advanced posture tracking.
