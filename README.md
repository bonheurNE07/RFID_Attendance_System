# Attendance System Based on RFID Technology 📚🎓

A student attendance management system based on RFID technology using a Raspberry Pi.

## Project Overview 🛠️

This project is an attendance management system designed for universities but adaptable to other institutions. The system uses RFID technology to track attendance for both students and employees. The user interface is built with PySide, providing an intuitive and user-friendly experience. The hardware setup includes an RFID reader, a Raspberry Pi, and RFID cards and bracelets as user input.

## Features 🌟

- **RFID-Based Identification:** Utilizes RFID cards and bracelets for quick and reliable identification of students and employees.
- **User-Friendly Interface:** Built with PySide to ensure ease of use for administrators and users.
- **Real-Time Attendance Tracking:** Captures and records attendance data in real-time.
- **Data Management:** Stores attendance records in a database for easy retrieval and analysis.
- **Adaptable to Various Institutions:** While designed for university use, the system can be customized for other types of institutions.

## Hardware Requirements 🖥️🔧

- Raspberry Pi (any model with sufficient GPIO pins)
- RFID Reader
- RFID Cards and Bracelets
- Power Supply for Raspberry Pi
- MicroSD Card with Raspbian OS installed

## Software Requirements 💻📦

- Python 3.x
- PyQt6 or PySide6
- GPIO Library for Raspberry Pi
- SQLite3 (or any other database system of your choice)

## Installation and Setup ⚙️📋

### 1. Setting Up the Raspberry Pi

1. Install Raspbian OS on the Raspberry Pi.
2. Connect the RFID reader to the Raspberry Pi USB Port.
3. Ensure the Raspberry Pi has internet access for installing necessary packages.

### 2. Installing Required Software

```bash
sudo apt-get update
sudo apt-get install python3-PySide6 python3-rpi.gpio sqlite3
```

### 3. Cloning the Repository

```bash
git clone https://github.com/bonheurNE07/RFID_Attendance_System.git
cd RFID_Attendance_System
```

### 4. Running the Application

```bash
python3 main.py
```

## Usage 🚀

1. **Administrator Setup:** Administrators can add, update, and remove users (students and employees) from the system using the PyQt interface.
2. **RFID Registration:** Register RFID cards and bracelets to individual users through the registration interface.
3. **Attendance Tracking:** Users simply scan their RFID cards or bracelets at the RFID reader to log their attendance.
4. **Data Management:** View and export attendance records from the database for analysis and reporting.

## Contributing 🤝

Contributions are welcome! Please fork this repository and submit a pull request for any enhancements or bug fixes.

## License 📜

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements 🙏

- Thanks to the open-source community for providing the tools and libraries that made this project possible.

---

Feel free to reach out with any questions or feedback regarding the project. Happy coding!

---

## Contact 📧

- **GitHub:** [bonheurNE07](https://github.com/bonheurNE07)
- **Email:** bonheurndezenc@gmail.com
