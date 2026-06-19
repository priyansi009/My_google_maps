# My_google_maps

# 🌍 My Google Maps Project

A simple web application built using the **Google Maps JavaScript API** that displays an interactive map centered on **Bhubaneswar, Odisha, India** with a custom marker.

## 🚀 Features
* Interactive Google Map
* Centered on Bhubaneswar
* Custom location marker
* Responsive map container
* Built with HTML, CSS, and JavaScript

## 📸 Preview

The map opens in the browser and displays:
* Bhubaneswar as the center location
* A marker titled **"Bhubaneswar!!!"**
* Zoom level set to 12
![Google Map Preview](myMap.png)

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript
* Google Maps JavaScript API

## 📂 Project Structure

```text
My_google_maps/
│
├── index.html
├── README.md
└── myMap.png
```

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/My_google_maps.git
cd My_google_maps
```

### 2. Get a Google Maps API Key

1. Create a project in Google Cloud Console.
2. Enable the Google Maps JavaScript API.
3. Generate an API key.
4. Replace the API key in `index.html`.

```html
<script async defer src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY&callback=initMap"></script>
```

### 3. Run the Project

Using serve:

```bash
npx serve -l 8080
```

Open:

```text
http://localhost:8080
```

## 📍 Location Used

**Bhubaneswar, Odisha, India**

Coordinates:

```javascript
{
  lat: 20.296059,
  lng: 85.824539
}
```

## 🎯 Future Improvements

* Multiple location markers
* Custom marker icons
* Route and direction support
* User location detection
* Search functionality

## 👩‍💻 Author

Priyansi Purohit

Built as a learning project using the Google Maps JavaScript API.


