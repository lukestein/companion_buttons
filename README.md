# Luke's Companion buttons
Several custom Bitfocus Companion buttons

For control of an ATEM Mini and H2R graphics. Original versions were for Companion v2.1.2 (which had some complications, especially the inability to change the text on "this" button rather than give an absolute button reference), with updated versions for Companion v2.2.0.

![image](https://user-images.githubusercontent.com/44452336/111806955-e0109b00-88a8-11eb-8df3-85653604fd31.png)

| Button   | Description |
| -------- | ----------- |
| 5.2      | Turn on an H2R Graphics countdown of the indicated time. Hold the button to set/reset the amount of time (currently 1/2/5/10/15 mins). This only works for me if the H2R Graphics timer transition is set to "None." Note that in the v2.1.2 version, if you move the button you'll have to edit the "Internal: Button Text" commands to refer to the correct button. |
| 5.3      | Set the output for the ATEM Mini HDMI output (aux 1). A quick press sets to Program; holding cycles through inputs 1–4 and then preview. Note that in the v2.1.2 version, if you move the button you'll have to edit the "Internal: Button Text" commands to refer to the correct button. Also, I found that in v2.1.2, the `$(atem:aux1_input)` macro didn't update reliably, so I had coded things in a more complex way—this seems fixed in v2.2.0. |
| 5.4      | Press to toggle the upstream keyer (M/E 1) on and off. Hold to cycle the upstream keyer fill source through inputs 1–4. |
| 5.10     | Toggle Mic 1 on and off. |
