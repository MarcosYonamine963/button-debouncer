# Four Debounced Buttons

The designed board has four debounced tactile buttons.

The board has an 6-pin socket header, containing the VCC, GND and the four output signals (Q1 to Q4).

Also, there are two auxiliary 2-pin header with VCC and GND, as you can see on the figure below.

![3D_View](https://user-images.githubusercontent.com/92953755/230695475-ed796c1f-5f6f-4482-bb55-99061953925d.png)
![3D_View2](https://user-images.githubusercontent.com/92953755/230695478-88e811cc-5dcd-489e-815e-65b65dac8ed7.png)



The logic output of the Buttons 1 and 2 (Q1 and Q2) are NL (normally LOW). For the Buttons 3 and 4, user can configure to NL or NH by the sliding switch (SW5 and SW6).

## Schematics

It was used an quad OR gate to buffer the signal to the LED indicators.


![Schematics-1](https://user-images.githubusercontent.com/92953755/230695895-8f7ec9d7-00e0-43d3-b283-f73b039b4c73.png)
