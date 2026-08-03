## Ice Protection or Weather Avoidance? Quantifying Winter Availability for Nordic Drone Delivery
{: #project-1}

<figure style="float: right; width: 45%; margin: 0.4em 0 1em 1.5em;">
  <img src="{{ site.baseurl }}/files/graphical_abstract_P1_web.jpg" alt="Weather-aware and direct routing across a Nordic delivery area with icing regions marked" style="width: 100%;">
  <figcaption style="font-size: 0.75em; line-height: 1.3; text-align: center; margin-top: 0.4em;">Illustration generated with Google Gemini.</figcaption>
</figure>

**Abstract:** The goal of this project is to determine when an active Ice Protection System (IPS) becomes commercially justified for cargo delivery UAVs operating in Nordic winter conditions. Operators currently ground their fleets whenever icing is forecast, with the consequence that their own flight logs contain almost no icing exposure at all [1] — the hazard is invisible in operational data precisely because avoidance works. Independent meteorological analysis puts the true exposure at 5–10% of low-altitude winter hours in the Oslo area, and recommends designing national systems for up to 30% between autumn and spring [2]. The alternative to grounding, low-altitude weather-aware routing, recovers at most 13% of flight energy and typically under 5% [1] — far below the roughly 50% reported for long-range missions free to choose their altitude [3], [4]. Choosing between hardware and avoidance requires pricing an icing encounter in energy and range, which until recently rested on CFD-derived penalties never validated in flight [3], [5]. This project uses newly flight-identified clean and iced aerodynamic models [6] together with icing wind tunnel propeller data [7] to simulate a delivery fleet across a Nordic winter, comparing ground-on-forecast, continuous anti-icing, and cyclic de-icing with tolerated accretion.

**Expected background:** flight mechanics or vehicle dynamics, and MATLAB or Python proficiency.

<details markdown="1">
<summary>References</summary>

[1] T. Bakkene, "Weather-aware path planning for cargo delivery UAVs at low altitude," M.S. thesis, Dept. Eng. Cybern., Norwegian Univ. Sci. Technol., Trondheim, Norway, 2025. [Online]. Available: <https://hdl.handle.net/11250/5273739>

[2] M. Hansbø and Ø. Hoelsæter, "Icing and wind — implications and mitigations in high-intensity, safety-critical drone operations in Norway," Norwegian Defence Research Establishment (FFI), Kjeller, Norway, Rep. [FFI-RAPPORT 22/01459](https://www.ffi.no/en/publications-archive/icing-and-wind-implications-and-mitigations-in-high-intensity-safety-critical-drone-operations-in-norway), 2022.

[3] E. F. L. Narum, "Mission planning for fixed-wing UAVs in wind and icing conditions," M.S. thesis, Dept. Eng. Cybern., Norwegian Univ. Sci. Technol., Trondheim, Norway, 2020. [Online]. Available: <https://hdl.handle.net/11250/2780922>

[4] A. R. Hovenburg, F. A. de Alcantara Andrade, R. Hann, C. D. Rodin, T. A. Johansen, and R. Storvold, "Long-range path planning using an aircraft performance model for battery-powered sUAS equipped with icing protection system," *IEEE J. Miniaturization Air Space Syst.*, vol. 1, no. 2, pp. 76–89, 2020, doi: 10.1109/JMASS.2020.3003833.

[5] M. Tiller, "Path planning for fixed-wing UAVs in wind and icing conditions," M.S. thesis, Dept. Eng. Cybern., Norwegian Univ. Sci. Technol., Trondheim, Norway, 2021. [Online]. Available: <https://hdl.handle.net/11250/2786767>

[6] B. Løw-Hansen, M. Lindner, T. A. Johansen, R. Hann, and C. Deiler, "UAV icing: System identification of leading-edge rime-ice effects on a small fixed-wing drone," submitted, 2026.

[7] B. Løw-Hansen, N. C. Müller, E. M. Coates, T. A. Johansen, and R. Hann, "Identification of an electric UAV propulsion system in icing conditions," SAE Tech. Paper 2023-01-1378, 2023, doi: 10.4271/2023-01-1378.

</details>
