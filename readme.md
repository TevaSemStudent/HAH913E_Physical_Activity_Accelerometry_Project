# Physical Activity - Accelerometry Project : Kinovea Video Analysis 

## Tools : 

Jump height is assessed from a video recording, an-
alyzed using Kinovea software. Kinovea is a free and open-
source two-dimensional motion analysis software specifically
designed for video analysis in sports contexts. A video cam-
era (4k/60FPS) is positioned in profile, at a sufficient distance
to capture the entire body during the jump. The camera frame
rate is chosen to allow for precise identification of the takeoff, jump, and landing phases.

## Method : 

A comparative biomechanical analysis was performed using the Kinovea video processing software to quantify the influence of the arm swing on vertical jump performance. The protocol began by setting up a dual-screen display allowing for the simultaneous visualization of the jump without arm swing and the jump with arm swing. 

The first processing step involved temporally synchronizing both sequences. The synchronization point was set at the precise takeoff frame, defined as the last moment of foot contact with the ground, in order to observe the temporal difference during the flight phase and upon landing. Spatial calibration was then performed on each video using the subject's height as a metric reference, thereby allowing the software to convert pixels into centimeters.
Performance measurement was carried out using two complementary methods. A temporal method was first employed using the stopwatch tool to measure the flight phase duration between takeoff and landing, which allowed for the calculation of the theoretical jump height. A direct spatial method was subsequently applied by freezing the video at the jump apex to measure the vertical distance between the ground and the subject's heels using the line tool. 

Finally, the analysis focused on the horizontal components of the movement. The use of visual markers and distance measurement tools allowed for the quantification of the subject's forward horizontal displacement, highlighting the modification of the center of mass trajectory induced by the momentum transfer from the upper limbs. 

## Results :

<p align="center">
  <img src="https://github.com/user-attachments/assets/62b97d88-13e6-4a7c-883f-7b2f1c447b40).gif" alt="Description du saut" width="700">
  <br>
  <em>Figure 2 : Vertical jump with active arm swing only vs with arm swing and a preparatory run-up</em>
</p>

<p align="center">
  <video src="no_arm_vs_arms.mp4" controls width="700"></video>
  <br>
no_arm_vs_arms
  <em>Figure 4 : Slow motion capture of the jump phase</em>
</p>


<p align="center">
  <img src="https://github.com/user-attachments/assets/f362f09c-6b40-48ae-9c6d-546c21ea1abb" alt="Description" width="700">
  <br>
  <em>Figure 1 : Vertical jump without arm swing</em>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/dee6cb07-62cb-4b45-8f1c-8b67fef9e956" alt="Description" width="700">
  <br>
  <em>Figure 2 : Vertical jump with active arm swing</em>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/24204007-9b19-48ff-b316-07a422746580" alt="Description" width="700">
  <br>
  <em>Figure 3 : Vertical jump with arm swing and a preparatory run-up</em>
</p>

## Interpretation : 

For the baseline jump without arms, a flight time of 0.57 seconds was recorded. Applying the gravitational equation of motion h = 1/8 * g * t², this duration yields a theoretical height of 39.8 cm. Similarly, the jump with arm swing recorded a flight time of 0.65 seconds, corresponding to a theoretical height of 51.8 cm. Finally, the jump with run-up recorded a flight time of 0.70 seconds, corresponding to a theoretical height of 60.1 cm. 

| Jump Type | Time ($t$) <br> (s) | Calc. Height <br> (cm) | Meas. Height <br> (cm) | Diff. <br> (%) |
| :--- | :---: | :---: | :---: | :---: |
| No Arms | 0.57 | 39.80 | 44.78 | 11.1 |
| Arms (Static) | 0.65 | 51.80 | 58.76 | 11.8 |
| Arms + Run-Up | 0.70 | 60.10 | 63.32 | 5.1 |

*Table 1 : Validation of Calculation Methods: Comparison between Temporal (Stopwatch) and Spatial (Kinovea) measurements.*

Although minor discrepancies exist due to the precise identification of takeoff frames, the convergence of results between these spatial and temporal methods validates the accuracy of the video analysis. 

| Comparison Factor | Progression <br> (cm) | Abs. Gain <br> (cm) | Rel. Gain <br> (%) |
| :--- | :---: | :---: | :---: |
| Arm Swing Effect | $44.78 \to 58.76$ | $+13.98$ | $+31.2$ |
| Run-Up Effect | $58.76 \to 63.32$ | $+4.56$ | $+7.8$ |
| **Total Gain** | $\mathbf{44.78 \to 63.32}$ | $\mathbf{+18.54}$ | $\mathbf{+41.4}$ |

*Table 2 : Analysis of Performance Progression and Relative Gains.*

The video analysis demonstrates a clear hierarchical progression in performance based on the spatial measurements. The baseline countermovement jump without arm swing resulted in a height of 44.78 cm. The introduction of an active arm swing from a static start significantly increased this height to 58.76 cm, representing a gain of +13.98 cm (+31.2\%). Finally, the inclusion of a run-up optimized the movement further, reaching a peak height of 63.32 cm. This final step contributed an additional +4.56 cm (+7.8\%), culminating in a total performance gain of +18.54 cm (+41.4\%) over the baseline. This progression highlights that the mechanical energy contribution from the upper limbs and approach velocity accounts for a substantial portion of the total vertical displacement.

Cross-referencing these kinematic results with kinetic data from the accelerometer provides a mechanical explanation for the observed performance gains. The accelerometer recorded a drastic increase in horizontal acceleration forces along the X-axis, rising from a baseline of 1.47 g without arms to 10.25 g with arms, and peaking at 12.88 g with the run-up. This nine-fold increase in horizontal force illustrates the massive momentum transfer required to elevate the center of mass. However, this force generation induces a significant horizontal displacement, observed in the video as a forward drift of 35.61 centimeters for the static arm swing and 57.20 centimeters for the run-up jump. 

