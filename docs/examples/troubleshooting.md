# **Troubleshooting Common Oscilloscope Issues**  

## **1. Using Demo Mode for Testing and Practice**  
The DSOX1204G includes a **Demo Mode**, which generates built-in example waveforms. This is useful for:  
- Learning how to operate the oscilloscope without external signals.  
- Testing measurement functions (e.g., cursors, FFT, math operations).  
- Verifying that the oscilloscope is functioning properly.  

### **How to Enable Demo Mode:**  
1. **Open the Utility or System Menu**  
   - Press the **"Utility"** or **"System"** button (varies by model).  
   - Look for an option labeled **Demo Mode** or **Self-Test Mode**.  

2. **Select a Demo Waveform**  
   - Some oscilloscopes provide predefined signals, such as sine waves, square waves, or modulated signals.  
   - Choose a waveform and observe how it behaves on-screen.  

3. **Use Demo Mode to Practice Functions**  
   - Adjust time and voltage scales to see how they affect the display.  
   - Test **measurement tools**, **math functions**, and **triggers** using a stable demo signal.  
   - Experiment with **cursors** and **FFT analysis**.  

4. **Exit Demo Mode When Finished**  
   - Return to the **Utility/System menu** and disable Demo Mode.  
   - Connect an actual probe to start measuring real signals.  

---

## **2. Ensuring Proper Probe Attenuation Settings**  
Incorrect probe settings can lead to inaccurate voltage readings.  

### **Checking and Adjusting Probe Attenuation:**  
1. **Identify Your Probe’s Attenuation Setting**  
   - Many probes have a **switch near the BNC connector** with **1X, 10X, or 100X** settings.  

2. **Verify the Oscilloscope’s Probe Setting**  
   - Open the **Channel Menu (CH1, CH2, etc.)**.  
   - Find the **Probe Attenuation** setting and ensure it matches the actual probe setting.  
   - Example: If using a **10X probe**, set the oscilloscope to **10X mode**.  

3. **Use the Probe Compensation Signal**  
   - Most oscilloscopes have a built-in **probe compensation output** (often labeled "1 kHz, 1V").  
   - Connect the probe tip to this signal and adjust the compensation screw on the probe if the waveform is distorted.  

---

## **3. No Signal Displayed**  
### **Possible Causes & Fixes:**  
- **Check if the Input Channel is Enabled** → Press the corresponding **CH1/CH2/CH3/CH4** button.  
- **Verify the Time/Div Setting** → If set too high, the signal may appear flat. Adjust to a lower value.  
- **Ensure the Trigger Level is Set Correctly** → If the trigger level is outside the signal range, the waveform won’t appear. Try setting it to **Auto Mode**.  
- **Confirm the Probe is Properly Connected** → Ensure it’s securely attached to both the oscilloscope and the test point.  

---

## **4. Waveform Looks Distorted or Clipped**  
### **Possible Causes & Fixes:**  
- **Check the Vertical Scale (Volts/Div)** → If the signal is too large for the current setting, lower the voltage per division.  
- **Verify AC/DC Coupling** → Use **DC coupling** to see both AC and DC components, or **AC coupling** to remove DC offsets.  
- **Check Bandwidth Limit Settings** → Some oscilloscopes have a **bandwidth limit** that filters high frequencies. Disable it if necessary.  

---

## **5. Timebase or Waveform Appears Unstable**  
### **Possible Causes & Fixes:**  
- **Use a Proper Trigger Setting** → Set the trigger source to the correct channel and adjust trigger level.  
- **Increase the Acquisition Time** → A very fast timebase can make signals appear erratic. Try slowing it down.  
- **Enable Averaging Mode** → If noise is affecting the signal, using averaging can help stabilize the display.  
