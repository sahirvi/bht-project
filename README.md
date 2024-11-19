<img width="200" alt="logo" src="https://github.com/user-attachments/assets/928759f8-7d38-4f60-a644-7c869699c883">  

# Bloom: Automatisiertes Bewässerungssystem
**Übungsprojekt im Wintersemester 2021/2022 (5. Studienplansemester)**

_Berliner Hochschule für Technik_  
_Betreuer: Dipl.-Ing. Erhard Buchberger_

*In diesem Repository befindet sich der von mir erstellte Quellcode für das Frontend und Backend des Projekts Bloom. Dieses Projekt wurde als Übungsprojekt im Rahmen des Moduls Projekt entwickelt.*

### Team  
Albert Kaminski – Projektleitung, Webserver-Programmierung  
Dominik Domonell – Hardwarekonstruktion und -design, App-Programmierung  
Jelena Mirceta – Webserver- und App-Programmierung, UI-Design  
Sahiram Ravikumar – Webserver- und App-Programmierung, Systemarchitektur  
Simon Núñez Aschenbrenner – MCU-Programmierung, Design, Systemarchitektur  

### Projektbeschreibung  
Bloom ist ein automatisiertes Bewässerungssystem, das Pflanzenbesitzern hilft, ihre Pflanzen effizient zu bewässern, sei es im Garten, auf dem Balkon oder in größeren Anwendungen wie Gewächshäusern und Farmen. Unser Ziel war es, ein benutzerfreundliches, skalierbares und ressourcenschonendes System zu entwickeln.  

### Features  
- **Backend:** Server mit MERN-Stack (Node.js, Express, MongoDB) und Sicherheitsfunktionen (SHA-256-Verschlüsselung, Token-basierte Sitzungen).  
- **Frontend:** Android-App mit intuitiver Benutzeroberfläche und MVVM-Architektur zur Steuerung und Überwachung der Bewässerung.  
- **Hardware:**  
  - **Bloom Box:** Steuerung von Magnetventilen, Pumpen und Sensoren über Microcontroller mit LoRa-Kommunikation.  
  - **Bloom Sensor:** Kabellose Feuchtigkeitssensoren mit langer Akkulaufzeit und spritzwassergeschütztem Gehäuse.  
- **Energieeffizienz:** Einsatz von energiesparenden Komponenten und Technologien wie LoRa.

### Technologien  
- **Backend:** Ubuntu, Node.js, MongoDB, Nginx, Docker Compose  
- **Frontend:** Android, Retrofit, MVVM-Design  
- **Hardware:** Microcontroller mit Micropython und C++, 3D-Druck für Prototypen  
- **Kommunikation:** LoRa für effizienten Datenaustausch über große Distanzen  

---

### English
# Bloom: Automated Irrigation System
**Exercise project of winter semester 2021/2022 (5th study plan semester)**

_Berlin University of Applied Sciences and Technology_  
_Project advisor: Prof. Dr. Sebastian von Klinski_

### Team  
Albert Kaminski – Project Lead, Webserver Development  
Dominik Domonell – Hardware Construction and Design, App Development  
Jelena Mirceta – Webserver and App Development, UI Design  
Sahiram Ravikumar – Webserver and App Development, System Architecture  
Simon Núñez Aschenbrenner – MCU Development, Design, System Architecture  

This repository contains the source code for the frontend and backend of the Bloom project that I developed. This project was created as a practice project within the Project module.  

### Project Overview  
Bloom is an automated irrigation system designed to assist plant owners in efficiently watering their plants, whether on balconies, in gardens, greenhouses, or even farms. Our goal was to create a user-friendly, scalable, and resource-efficient system.

### Features  
- **Backend:** MERN stack-based server (Node.js, Express, MongoDB) with robust security features (SHA-256 encryption, token-based sessions).  
- **Frontend:** Android app with an intuitive UI, MVVM architecture for monitoring and controlling irrigation.  
- **Hardware:**  
  - **Bloom Box:** Controls valves, pumps, and sensors via a microcontroller with LoRa communication.  
  - **Bloom Sensor:** Wireless soil moisture sensors with long battery life and splash-proof casing.  
- **Energy Efficiency:** Utilizes energy-saving components and technologies like LoRa.

### Technologies  
- **Backend:** Ubuntu, Node.js, MongoDB, Nginx, Docker Compose  
- **Frontend:** Android, Retrofit, MVVM design  
- **Hardware:** Microcontrollers with Micropython and C++, 3D printing for prototypes  
- **Communication:** LoRa for efficient long-range data exchange  
