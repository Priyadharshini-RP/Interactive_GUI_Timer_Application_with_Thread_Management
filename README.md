# Interactive_GUI_Timer_Application_with_Thread_Management
This program is a multithreaded timer application developed using Java Swing. It provides a graphical user interface (GUI) to display and control a timer.

The application window contains a label to show time and three buttons: Start, Stop, and Reset. When the user clicks the Start button, a new thread is created using the Runnable interface. This thread increases the time every second and updates the label.

The Stop button is used to stop the timer by controlling the execution of the thread. The Reset button sets the timer value back to zero and updates the display.

The program uses SwingUtilities.invokeLater() to safely update the GUI from a separate thread. Event handling is implemented using ActionListener for button actions.
