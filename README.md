# Simple-Battery-Charge-Level-Indicator-
Simple Battery Charge Level Indicator – Green for >10V (Charged), Red for ≤10V (Low)

How It Works

This is a low-component battery voltage level indicator circuit that visually shows whether a battery is adequately charged or running low.
When the battery voltage is above ~10 V the 10 V zener diode breaks down in reverse and supplies base current to transistor Q1.
→ Q1 turns on, pulling current through the green LED (D1) → green light indicates "battery is good / sufficiently charged".
When the battery voltage drops below ~10 V, the zener no longer conducts significantly → Q1 turns off.
→ The base of transistor Q2 now receives current through R2 (and the path involving the green LED), turning Q2 on.
→ Current flows through the red LED (D2) and R3 → red light indicates "battery low / needs recharging".

The circuit uses a clever transistor inverter configuration so that only one LED is clearly lit at a time (the other is either off or light a bit). It draws very little current and works well for monitoring 9–12 V battery systems.

<img width="950" height="730" alt="image" src="https://github.com/user-attachments/assets/5d42d1bf-ffde-4872-a041-661a459342e6" />
<img width="1090" height="828" alt="image" src="https://github.com/user-attachments/assets/0f097de6-3d34-48f5-8a48-62c18b92a1bf" />
<img width="579" height="1027" alt="image" src="https://github.com/user-attachments/assets/0788435e-1acb-4880-8273-1562cbfe7b6b" />
<img width="579" height="1027" alt="image" src="https://github.com/user-attachments/assets/3ba9d20c-bbcb-467b-a973-fb07c6ac81cb" />
