## The Aircraft as Its Own Virtual Ice Sensor – Indirect Detection and Monitoring
{: #project-2}

<figure style="float: right; width: 45%; margin: 0.4em 0 1em 1.5em;">
  <img src="{{ site.baseurl }}/files/graphical_abstract_P2_and_P3_web.jpg" alt="Model-based ice detection from onboard telemetry on a small fixed-wing UAV" style="width: 100%;">
  <figcaption style="font-size: 0.75em; line-height: 1.3; text-align: center; margin-top: 0.4em;">Illustration generated with Google Gemini.</figcaption>
</figure>

**Abstract:** The goal of this project is to develop an indirect ice detection system that uses a UAV's own flight performance as its only sensor, and that reports icing severity rather than a binary alarm. Small cargo UAVs cannot accommodate dedicated ice detection hardware [1], making performance-based detection the only scalable option. Detection from in-flight aerodynamic coefficient estimation was demonstrated in principle as early as 2019 [2], but had to assume the degradation it was looking for. A recently validated propeller torque method achieves mean detection times of 20–40 s below −5 °C and 60–80 s in mild −2 °C icing using only motor power, motor speed and airspeed [3] – but monitors the propulsion system, which ceases to be a usable icing proxy the moment a propeller de-icing system is activated. Flight tests have now quantified the airframe signature directly: a 50% increase in zero-lift drag, a 23% reduction in lift slope, a short-period frequency drop from 13.7 to 6.8 rad/s, and a 57% loss of elevator effectiveness [4]. Working in an existing 6-DOF simulation environment containing flight-identified clean and iced models, the student will design a model-based residual generator, select observables on robustness grounds, and map residuals onto a continuous severity index defined against computable envelope margins. Emphasis is placed on false-alarm resilience under turbulence, wind-estimation error and manoeuvring, which remains the principal barrier to operational adoption.

**Expected background:** estimation and detection theory, and MATLAB or Python proficiency.

<details markdown="1">
<summary>References</summary>

[1] B. Løw-Hansen, R. Hann, B. N. Stovner, and T. A. Johansen, "UAV icing: A survey of recent developments in ice detection methods," *IFAC-PapersOnLine*, vol. 56, no. 2, pp. 10727–10739, 2023, doi: 10.1016/j.ifacol.2023.10.733.

[2] A. Wenz and T. A. Johansen, "Icing detection for small fixed-wing UAVs using inflight aerodynamic coefficient estimation," in *Proc. IEEE Aerospace Conf.*, 2019, pp. 1–9, doi: 10.1109/AERO.2019.8742134.

[3] B. Løw-Hansen, R. Hann, T. A. Johansen, and R. Galeazzi, "Real-time detection of propeller icing for electric fixed-wing UAVs using estimated propeller torque," to be submitted, 2026.

[4] B. Løw-Hansen, M. Lindner, T. A. Johansen, R. Hann, and C. Deiler, "UAV icing: System identification of leading-edge rime-ice effects on a small fixed-wing drone," submitted, 2026.

</details>
