🌱 CarbonForge - Personal Impact Simulator

CarbonForge is a consumer-facing application that models the "Decay of Impact" for personal carbon footprints. It moves beyond simple static calculators by modeling how lifestyle interventions (EVs, Solar, Diet) compound over time to accelerate an individual's path to Net Zero.

It serves as a demonstration of Behavioral Modeling, showing how user choices can alter the exponential decay curve of their environmental impact.
✨ Key Features

    Lifestyle Modeling: precise inputs for Transport (Mileage/Vehicle Type), Home Energy (Heating Source), and Diet (Meat vs. Vegan).

    Intervention Engine: A gamified interface where users select "Power-ups" (e.g., Switch to EV, Install Solar) to instantly visualize the impact on their 10-year trajectory.

    Economic Analysis: Calculates not just carbon saved, but financial savings (e.g., fuel/energy costs) to align economic incentives with environmental ones.

    Social Benchmarking: Compares user data against National (UK) and Global averages in real-time.

    Platform Showcase: Includes a visualization of the wider "Forge Theory" ecosystem, demonstrating how the math applies to other verticals (Health, Materials, Psychology).

🚀 Quick Start

    Run: Open index.html in any modern browser. No server required.

    Input Profile: Adjust the "Example Carbon Profile" inputs to match a specific persona (e.g., a commuter in a detached house).

    Apply Interventions: Click the cards in the "Example Interventions" section to simulate lifestyle changes.

    Observe Decay: Watch the chart update to show how the "Time to Significant Reduction" shortens based on the selected interventions.

🧮 The Math: Lifestyle Decay

CarbonForge uses Exponential Decay to model the adoption and impact of sustainability technology.
C(t)=Ctarget​+(Cinitial​−Ctarget​)×e−k⋅t

    C(t): Carbon footprint at time t.

    Ctarget​: The minimum viable footprint (the floor).

    k (Adoption Rate): Represents the speed of transition.

        Low k: Passive reduction (grid gets greener).

        High k: Active reduction (User buys an EV).

⚙️ Configuration

The simulation logic is data-driven. You can adjust the EXAMPLE_FACTORS object to localize the tool for different regions (e.g., changing US vs EU grid factors).
JavaScript
