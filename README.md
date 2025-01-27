# kittec-eco55
Discount Thor Kiln kittec eco 55 - 1300°c

PhotoAlbum: [Google Photos Album](https://photos.app.goo.gl/oatt2EmMtDsDjP2o6)

### How to use the kiln video playlist
[Youtbe Playlist](https://www.youtube.com/watch?v=xoc6Wg6GqKU&list=PLEvmlp-nq1Q4yKHdWhCgacgY_uAayaDIU)

(KILN controller user manual (Kudos Kittec))[https://github.com/opensourcemanufacturing/kittec-eco55/blob/main/BedienungsanleitungTC405englisch.pdf]


## Color tempering tests

### Stainless Steel 316 temper colors (tested)

During the testing, I used a large mass and a smaller one to see if the metal mass would influence the color achieved and the short results shown that with the tested curve the color difference betweeen objects was not noticible, meaning that in theory we can use small test stripts to validate future curves.

Below is the table of the validated curve temps for specific colors.

|                      | T0 | c/h | tmp1 / t1 | c/h | tmp2 / t2 | c/h |
|:---                  |:---:|:---:|:---:|:---:|:---:|:---:|
|Bronze like (260º)    |0'|700º|300º / 15'|700º|460º / 45'|700º|

![image](https://github.com/user-attachments/assets/ab1f27eb-4f0e-4b40-a2e1-f6bdf6b8db37)

### External color/temperature references
![image](https://github.com/user-attachments/assets/37454b16-c11e-43bc-b734-f0cdc38b481a)

## Replacement parts

## How to use the controller (By ChatGPT)

Here’s a basic guide to operating and configuring the Kittec Micro Timer MT 4 controller:

### Key Elements of the Controller:
1. **Display**: Shows the current temperature or programming settings.
2. **Yellow Buttons**: These are for setting temperature points (e.g., `tmp1`, `tmp2`) and ramp rates (e.g., "Auf °C/h" for heating and "Ab °C/h" for cooling).
3. **Blue Number Buttons**: For entering numerical values like temperatures or ramp rates.
4. **Red Buttons**:
   - **Total kWh**: Displays the total energy consumption.
   - **Start/Stop**: Begins or halts the programmed cycle.
5. **Yellow Key Button**: Used to save or confirm settings.
6. **Preset Programs** (`Fest-Prog.`): Predefined firing programs.
7. **Custom Programs** (`Wahl-Prog.`): For setting user-defined firing profiles.

---

![image](https://github.com/user-attachments/assets/ab1f27eb-4f0e-4b40-a2e1-f6bdf6b8db37)

---

### Steps to Program the Controller:

#### 1. **Set Initial Parameters**:
   - Press the yellow button corresponding to `t0` (starting point) and use the blue number buttons to input the initial hold time (e.g., how long to maintain the temperature before starting the ramp).
   - Confirm with the yellow key button.

#### 2. **Set Temperature Points**:
   - Press the yellow `tmp1` button to input the first target temperature. Enter the value with the blue number buttons (e.g., `800°C`), then confirm.
   - Repeat for `tmp2` if a second temperature step is needed.

#### 3. **Set Ramp Rates**:
   - Use the "Auf °C/h" buttons to define the heating rate (degrees Celsius per hour) to reach each temperature target.
   - Use "Ab °C/h" to define the cooling rate.

#### 4. **Set Hold Times**:
   - Press `t1` to set the hold time (e.g., how long to hold at `tmp1`).
   - Repeat for `t2` if necessary.

#### 5. **Save the Program**:
   - Use the yellow `Speichern` (Save) button to save the settings.
   - If you want to select a predefined or custom program, use the `Fest-Prog.` or `Wahl-Prog.` buttons.

#### 6. **Start the Cycle**:
   - Press the red `Start/Stop` button to begin the firing cycle.
   - The display will update as the program progresses.

---

### Tips:
- **Predefined Programs**: If you’re not setting custom parameters, select `Fest-Prog.` and use the numbers to pick a preset firing program (e.g., `7`, `8`, `9` for higher temperatures).
- **Energy Monitoring**: Check `Total kWh` after the firing cycle to monitor power usage.
- **Error Handling**: If the controller shows an error or behaves unexpectedly, refer to the manual or reset the controller by turning it off and on.

If you’re working with a specific material (e.g., ceramics or glass), let me know, and I can help tailor the programming for it.


