## Autopilot Tuning That Survives Icing – Robust Control Across Clean and Iced Envelopes
{: #project-4}

<figure style="float: right; width: 45%; margin: 0.4em 0 1em 1.5em;">
  <img src="{{ site.baseurl }}/files/graphical_abstract_P4_web.jpg" alt="Fixed-wing UAV holding an approved corridor and altitude band under icing conditions" style="width: 100%;">
  <figcaption style="font-size: 0.75em; line-height: 1.3; text-align: center; margin-top: 0.4em;">Illustration generated with Google Gemini.</figcaption>
</figure>

**Abstract:** The goal of this project is to re-evaluate and optimize flight control for small fixed-wing UAVs against flight-validated iced aerodynamics, and to quantify what robustness across clean and iced envelopes costs in fair-weather performance. Control of UAVs in icing conditions has been studied extensively at NTNU through robust and gain-scheduled design [1], [2], model reference adaptive control [3] and nonlinear model predictive control [4]. All of this work necessarily relied on the icing models available at the time — an iced aerodynamic endpoint assembled in 2019 by transferring general-aviation icing behaviour onto a small UAV, with the limited validation then possible [5]. Within that model the robust and gain-scheduled designs explicitly assumed the control derivatives to be independent of icing level [1], and the later adaptive study revised this using CFD, reducing elevator pitching-moment effectiveness by 37% [3]. Flight tests with realistic leading-edge rime ice now measure a 57% reduction in that same derivative, together with a short-period frequency falling from 13.7 to 6.8 rad/s, Dutch-roll damping from 0.48 to 0.19, and pitch stiffness and pitch-rate damping reduced by roughly 83% and 80% [6]. Because cargo delivery UAVs operate within a narrow 50–120 m AGL band and inside approved corridors [7], the relevant failure modes are actuator saturation, altitude loss in banked turns under powertrain limits, and corridor violation in gusts. The student will re-anchor these controllers onto measured aerodynamics and optimize a tuning that holds across both envelopes.

**Expected background:** control engineering and MATLAB or Python proficiency.

<details markdown="1">
<summary>References</summary>

[1] R. Kleiven, "Robust and gain-scheduled flight control of fixed-wing UAVs in icing conditions," M.S. thesis, Dept. Eng. Cybern., Norwegian Univ. Sci. Technol., Trondheim, Norway, 2021. [Online]. Available: <https://hdl.handle.net/11250/2781074>

[2] R. Kleiven, K. Gryte, and T. A. Johansen, "Robust and gain-scheduled flight control of fixed-wing UAVs in wind and icing conditions," in *Proc. IEEE Aerospace Conf. (AERO)*, 2022, pp. 1–12, doi: 10.1109/AERO53065.2022.9843837.

[3] S. Högnadóttir, K. Gryte, R. Hann, and T. A. Johansen, "Inner-loop control of fixed-wing unmanned aerial vehicles in icing conditions," in *AIAA SciTech 2023 Forum*, 2023, doi: 10.2514/6.2023-1049.

[4] N. A. Ghindaoanu, K. Gryte, D. Reinhardt, and T. A. Johansen, "Control of fixed-wing UAVs in icing conditions using nonlinear model predictive control," in *Proc. European Control Conf. (ECC)*, 2024, pp. 1461–1466, doi: 10.23919/ECC64448.2024.10591240.

[5] A. Winter, R. Hann, A. Wenz, K. Gryte, and T. A. Johansen, "Stability of a flying wing UAV in icing conditions," in *Proc. 8th European Conf. Aeronautics and Space Sciences (EUCASS)*, Madrid, Spain, 2019, doi: 10.13009/EUCASS2019-906.

[6] B. Løw-Hansen, M. Lindner, T. A. Johansen, R. Hann, and C. Deiler, "UAV icing: System identification of leading-edge rime-ice effects on a small fixed-wing drone," submitted, 2026.

[7] T. Bakkene, "Weather-aware path planning for cargo delivery UAVs at low altitude," M.S. thesis, Dept. Eng. Cybern., Norwegian Univ. Sci. Technol., Trondheim, Norway, 2025. [Online]. Available: <https://hdl.handle.net/11250/5273739>

</details>
