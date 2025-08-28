# Tkinter-Alarm-Clock

<img width="1920" height="1080" alt="Screenshot 2025-08-29 003902" src="https://github.com/user-attachments/assets/8d94a4de-2b51-43a9-9fd7-5385379e9a99" />

📖 Overview  

This is a GUI-based Alarm Clock application created using Python and Tkinter. It lets users set alarms with AM/PM format, snooze them, and repeat them daily. The app also displays a real-time digital clock and provides cross-platform sound alerts, making it simple yet effective for everyday use.

🚀 Features

🕒 Live Digital Clock with continuous updates

⏰ Set alarms with AM/PM format

🔁 Daily repeat option for recurring alarms

🔕 Stop alarm functionality

😴 Snooze option (+5 minutes)

🎶 Sound notifications:

Windows → winsound.Beep() multi-tone alerts

Other OS → Tkinter bell()

🖼️ Clean and simple GUI built with Tkinter

📂 Project Structure
alarm_clock.py   # Main script with GUI and alarm logic

▶️ How to Run

1️⃣ Install dependencies (Tkinter comes pre-installed)

For Windows beep support:

pip install pywin32

(Tkinter and datetime are included in Python’s standard library.)

2️⃣ Run the app:

python alarm_clock.py

⚙️ How It Works

Launch the app → A live digital clock is displayed

Set alarm time (e.g., 07:30 AM)

Click Set Alarm → Alarm is scheduled

At the set time → A popup with sound alert appears

👉 Options:

Stop → Dismiss alarm

Snooze → Adds +5 minutes

Repeat Daily → Auto-schedules alarm for the next day

🖼️ GUI Preview

Main Window → Digital clock + input fields for alarm time

Popup Alert → “⏰ Time’s up!” with sound notification

🔮 Future Enhancements

🎵 Add support for custom alarm tones (MP3/WAV)

🌓 Toggle between Dark/Light themes

📱 Export as a standalone desktop app (.exe / .dmg)

⏳ Add a Countdown Timer feature
