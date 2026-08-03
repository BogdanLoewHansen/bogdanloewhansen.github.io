## Qualifying a Virtual Ice Sensor – Detection Strategy Selection and Model Fidelity Requirements
{: #project-3}

<figure style="float: right; width: 45%; margin: 0.4em 0 1em 1.5em;">
  <img src="{{ site.baseurl }}/files/graphical_abstract_P2_and_P3_web.jpg" alt="Model-based propeller ice detection from standard onboard telemetry" style="width: 100%;">
  <figcaption style="font-size: 0.75em; line-height: 1.3; text-align: center; margin-top: 0.4em;">Illustration generated with Google Gemini.</figcaption>
</figure>

**Abstract:** The goal of this project is to determine which detection strategy is best suited to model-based propeller ice detection, and what a manufacturer must know about their own propulsion system before deploying it. Detecting propeller icing from standard telemetry — motor power, motor speed and airspeed — has been demonstrated and validated in an icing wind tunnel using a generalized likelihood ratio test, with mean detection times of 20–40 s below −5 °C and 60–80 s in mild −2 °C conditions across two 14-inch propellers [1]. That result establishes feasibility, but leaves two questions open. The detector was derived assuming a step change in mean within white Gaussian noise, whereas ice accretion is a gradual drift and the residuals were shown to violate the independence assumption the test rests on [1]; other change-detection formulations may therefore suit the physics better. Separately, performance depends on how well the underlying models represent the actual hardware — the same 33% power loss produced residuals of 0.035 Nm on one propeller and 0.056 Nm on another, moving the achievable false-alarm probability from 0.075 to 0.005 [1]. The student will benchmark alternative detection strategies against the same experimental data and the same operational threshold criterion, and quantify how much model fidelity each one demands.

**Expected background:** statistical signal processing or estimation and detection theory, and MATLAB or Python proficiency.

**In collaboration with** [Ubiq Aerospace](https://www.ubiqaerospace.com/).

<details markdown="1">
<summary>References</summary>

[1] B. Løw-Hansen, R. Hann, T. A. Johansen, and R. Galeazzi, "Real-time detection of propeller icing for electric fixed-wing UAVs using estimated propeller torque," to be submitted, 2026.

</details>
