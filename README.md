<h1>Design and Implementation of a Low-Power RTK Positioning Base Station for Precise Navigation</h1>

<b>Description</b>

This thesis was developed in collaboration with a Lisbon-based company and details the development, design and testing of a low-power RTK positioning base station. The objective was to achieve, through the base station, centimeter-level precision for UAV navigation by reducing the device's power consumption while maintaining real-time GNSS corrections. The work encompasses everything from design to prototype testing, and culminated with a written report.

<h2>👨‍💻 Thesis Summary:</h2>

<b>Objectives:</b>

- Complete design-to-prototype process - including testing.

- Development of a new low-power power supply architecture with battery balancing, power selection, voltage conversion, and switching circuits.

- Integration of a Raspberry Pi Compute Module 4 for managing GNSS data, wireless communications, and remote configuration.

- Achievement of (ideally) 50% power consumption reduction compared to the previous design.

<b>Thesis Structure:</b>

- Chapter 1: Introduction – Outlines the problem and motivation.

- Chapter 2: State-of-the-Art – Reviews GNSS fundamentals, positioning methods, and RTK techniques.

- Chapter 3: Hardware Design – Power Supply – Covers detailed circuit designs for a low-power architecture.

- Chapter 4: Hardware Design – Control, Peripherals, and Communications – Describes the integration of control and communication modules.

- Chapter 5: Prototyping and Functional Evaluation – Presents PCB layout, assembly, and test results.

- Chapter 6: Conclusions and Future Work – Summarizes achievements and suggests potential improvements.

<h2>🛠️ Implementation Details:</h2>

- Low-Power Design: Utilizes battery balancing and power management circuits to reduce overall consumption.

- RTK & GNSS Integration: Employs carrier-based corrections and Differential GNSS to achieve high-precision positioning.

- System Control: Integrates a Raspberry Pi Compute Module 4 for handling GNSS data, wireless communication, and remote configuration.

<h2>📊 Prototype & Evaluation:</h2>

Extensive prototyping and testing were conducted on the prototype, which served as a foundation for future improvements and iterations.

<!-- Add your prototype images/screenshots here -->

Below are some screenshots and pictures of the schematics, layout and prototype itself:

<p align="center">
  <img src="https://github.com/danielftsilva/RTK-Base-Station/blob/main/Chapters/Figures/chapter3/Power_Supply_and_Selection_1.png" alt="Power_Supply_and_Selection_1">
  <br>
  <i>New power supply and selection.</i>
</p>

<p align="center">
  <img src="https://github.com/danielftsilva/RTK-Base-Station/blob/main/Chapters/Figures/chapter5/prototype/10_proto_HDMI_and_RPiOS_working.png" alt="10_proto_HDMI_and_RPiOS_working">
  <br>
  <i>Prototype's HDMI displaying RPiOS screen.</i>
</p>

<p align="center">
  <img src="https://github.com/danielftsilva/RTK-Base-Station/blob/main/Chapters/Figures/chapter5/placement_FULL.png" alt="placement_FULL">
  <br>
  <i>Finalized placement on top layer.</i>
</p>

<p align="center">
  <img src="https://github.com/danielftsilva/RTK-Base-Station/blob/main/Chapters/Figures/chapter5/7_routing_FULL_FCu_BCu.png" alt="7_routing_FULL_FCu_BCu">
  <br>
  <i>Finalized routing on top and bottom layers.</i>
</p>

<p align="center">
  <img src="https://github.com/danielftsilva/RTK-Base-Station/blob/main/Chapters/Figures/chapter5/prototype/5_proto_first_test_ONLY_EXT_PWR.png" alt="5_proto_first_test_ONLY_EXT_PWR">
  <br>
  <i>Prototype's first power-up.</i>
</p>

<p align="center">
  <img src="https://github.com/danielftsilva/RTK-Base-Station/blob/main/Chapters/Figures/chapter5/prototype/3_proto_ReworkStation.png" alt="3_proto_ReworkStation">
  <br>
  <i>Soldering of the USB hub IC using a rework station.</i>
</p>

<p align="center">
  <img src="https://github.com/danielftsilva/RTK-Base-Station/blob/main/Chapters/Figures/chapter5/prototype/25MHz_oscilloscope.png" alt="25MHz_oscilloscope">
  <br>
  <i>Stable USB hub's 25 MHz clock frequency.</i>
</p>

<!-- <img src="https://github.com/danielftsilva/RTK-Base-Station/blob/main/Chapters/Figures/chapter5/prototype/10_proto_HDMI_and_RPiOS_working.png" alt="10_proto_HDMI_and_RPiOS_working"/> -->
<!-- <img src="https://github.com/danielftsilva/RTK-Base-Station/blob/main/Chapters/Figures/chapter5/placement_FULL.png" alt="placement_FULL"/> -->
<!-- <img src="https://github.com/danielftsilva/RTK-Base-Station/blob/main/Chapters/Figures/chapter5/7_routing_FULL_FCu_BCu.png" alt="7_routing_FULL_FCu_BCu"/> -->
<!-- <img src="https://github.com/danielftsilva/RTK-Base-Station/blob/main/Chapters/Figures/chapter5/prototype/5_proto_first_test_ONLY_EXT_PWR.png" alt="5_proto_first_test_ONLY_EXT_PWR"/> -->
<!-- <img src="https://github.com/danielftsilva/RTK-Base-Station/blob/main/Chapters/Figures/chapter5/prototype/3_proto_ReworkStation.png" alt="3_proto_ReworkStation"/> -->
<!-- <img src="https://github.com/danielftsilva/RTK-Base-Station/blob/main/Chapters/Figures/chapter5/prototype/25MHz_oscilloscope.png" alt="25MHz_oscilloscope"/> -->

