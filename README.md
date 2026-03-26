# geolocation#

name = PrinceRaj
domain = python programming
student id =SGT-26C-2002
Company = SoftGrowTech

# 🌍 IP Geolocation Tracker

## 📌 Project Overview

The IP Geolocation Tracker is a Python-based application that allows users to find the approximate geographical location of any IP address. It uses free public APIs to fetch real-time location data such as city, region, country, ISP, and coordinates, and then visualizes this information on an interactive map using the Folium library. The project is designed to demonstrate API integration, data processing, and map visualization in a simple and effective way.

---

## 🎯 Objective

The main objective of this project is to:

* Track the geographical location of an IP address
* Display detailed information in the console
* Visualize the location on an interactive map
* Provide a simple and user-friendly interface

---

## 🧰 Technologies Used

* Python (Core programming language)
* Requests library (for API calls)
* Folium (for map visualization)
* Webbrowser module (to open map automatically)
* OS module (for file path handling)
* Datetime module (for timestamp display)

---

## 🌐 APIs Used

* IP-API: Used to fetch geolocation data (city, country, ISP, latitude, longitude, etc.)
* ipify API: Used to detect the user's current public IP address

---

## ⚙️ Working of the Project

1. The program starts and prompts the user to enter an IP address.
2. If the user leaves the input blank, the program automatically fetches the current public IP using the ipify API.
3. The entered or detected IP address is sent to the IP-API service.
4. The API returns location data in JSON format.
5. The program extracts useful information such as city, region, country, ISP, coordinates, and timezone.
6. The extracted data is displayed in a well-formatted output in the console.
7. Using the Folium library, an interactive map is created centered at the given latitude and longitude.
8. A marker is added to the map with a popup showing all location details.
9. The map is saved as an HTML file with a safe filename.
10. The file is automatically opened in the default web browser for visualization.

---

## 📊 Output

The program generates two types of output:

* Console Output: Displays IP address details such as location, ISP, and coordinates
* Map Output: Opens an interactive map with a marker showing the exact tracked location

---

## ⚠️ Limitations

* The location is approximate, not exact
* Results may be inaccurate if a VPN or proxy is used
* Some IPv6 addresses may not be fully supported by the API
* Internet connection is required for API calls

---

## 🔥 Features

* Automatic IP detection
* Supports both IPv4 and IPv6
* Real-time data fetching
* Interactive map visualization
* User-friendly and simple interface
* No API key required

---

## 🚀 Future Improvements

* Add GUI using Tkinter or Streamlit
* Support tracking multiple IP addresses
* Add heatmap visualization
* Store results in a database or CSV file
* Convert into a web application using Flask
* Improve accuracy using multiple APIs

---

## 🏁 Conclusion

This project is a practical implementation of API integration and data visualization using Python. It helps in understanding how real-world applications fetch and display location data. The use of an interactive map makes the project more user-friendly and visually appealing. It is suitable for beginners as well as intermediate-level learners and can be enhanced further for advanced applications.

---

## 👨‍💻 Author

Prince Raj Tiwari

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/d1330c35-f93e-4f0c-9505-93c82f07742c" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/93f461f8-9e6e-469e-8dfd-6b84740b8e18" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/cc6a6a09-b39f-4380-aa95-b66caf8523a2" />
