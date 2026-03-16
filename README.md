# SolidWorks Piston Macro Generator

## Vision and Architecture
The **SolidWorks Piston Macro Generator** is a lightweight, web-based automation tool designed to bridge the gap between parametric web interfaces and SolidWorks API. It translates user-defined geometric parameters into ready-to-execute Visual Basic for Applications (VBA) macro code. This approach transforms the repetitive task of 3D piston modeling into a seamless, deterministic, and instantaneous process.

By leveraging HTML and JavaScript, this tool acts as a pre-processor, calculating and embedding dimensions directly into a robust SolidWorks API script. It is built for engineers and researchers who require rapid prototyping and automated drafting.

## Core Capabilities
* **Parametric Automation:** Dynamically generates VBA code based on precise user inputs.
* **Complex Feature Generation:** Automates base extrusions, inner cuts, pinhole boss creation, ring land cuts, and precise dome feature insertions.
* **Web-Native Interface:** Zero installation required for the generator. Runs entirely locally in any modern web browser.
* **One-Click Execution:** Instantly copies the generated macro to the clipboard for direct execution within the SolidWorks environment.

## Parametric Dimensions Handled
The logic controls the full spatial geometry of a standard combustion engine piston.
* `H`: Total Piston Height
* `a`: Top Land Clearance
* `b`: Ring Groove Width / Ring Land Depth
* `c`: Ring Land Spacing
* `d`: Pin Hole Diameter
* `h`: Pin Hole Center Distance
* `i`: Dome Height
* `O`: Outer Diameter (Piston Bore)
* `G`: Inner Diameter
* `F`: Distance Between Pin Bosses
* `E`: Pin Boss Outer Diameter

## Execution Workflow
1. **Launch the Interface:** Open `index.html` in any web browser.
2. **Define Parameters:** Input the exact dimensional values (in mm) according to your mechanical design requirements.
3. **Generate Code:** Click "Generate SolidWorks Macro". The JavaScript engine will compile the parameters into the macro template.
4. **Copy & Paste:** Click "Copy Code". Open SolidWorks, navigate to `Tools > Macro > New`, paste the code into the VBA editor, and hit Run (F5).
5. **Observation:** Watch the API autonomously sketch, extrude, and cut the complete 3D piston model in real-time.

## Technology Stack
* **Frontend UI:** HTML5, CSS3 (for structured layout and input validation)
* **Logic Engine:** Vanilla JavaScript (for DOM manipulation and template literal string generation)
* **CAD Execution:** SolidWorks API (VBA)

---

## ✍️ Author
**Arafat Hossain**
*Mechanical Engineering Student*
Focusing on deep learning, research, and innovative CAD automation in engineering fields.
