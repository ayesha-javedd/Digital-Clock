# Digital-Clock

This Python script creates a real-time digital clock using the **Tkinter GUI** library. The clock displays the current time (HH:MM:SS AM/PM) and the current date (MM/DD/YY), updating every second.

**Features**

✅ Displays time in 12-hour format with AM/PM

✅ Shows the current date below the time

✅ Uses strftime() from the time module for accurate time formatting

✅ Automatically updates every 1 second using after(1000, time

✅ Customizable font, size, and colors

**How It Works**

1.Tkinter creates the GUI window (root).

2.The time() function gets the current time and date using strftime().

3.The Tkinter Label (label) is updated every second using .after(1000, time).

4.The script runs an infinite loop (root.mainloop()) to keep the clock running
