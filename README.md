# Reach-Flow

**Reach-Flow** visualizes the area you can reach from your current location based on live traffic conditions.  
It uses Google Maps services to calculate and display reachable zones within a selected time frame.

---

## Features

- Real-time traffic-aware reachable area calculation
- Adjustable time, starting distance, number of attempts, and number of rays
- Visual representation on Google Maps
- Guaranteed inclusion of your starting point within the calculated area

---

## Requirements

You must create a **Google Cloud API Key** and enable the following APIs:

✅ [Maps JavaScript API](https://console.cloud.google.com/apis/library/maps-backend.googleapis.com)  
✅ [Directions API](https://console.cloud.google.com/apis/library/directions-backend.googleapis.com)

---

## How to Get a Google API Key

1. Visit [Google Cloud Console](https://console.cloud.google.com/) and create a new project (or select an existing one).
2. Navigate to **"APIs & Services" > "Library"** and enable:
   - **Maps JavaScript API**
   - **Directions API**
3. Go to **"APIs & Services" > "Credentials"**, and create a new **API Key**.
4. For security, set the following restrictions on your API Key:
   - **Application restriction:** HTTP referrer (`https://your-github-username.github.io/*`)
   - **API restrictions:** Only allow Maps JavaScript API and Directions API.

---

## Usage

1. Clone this repository or download it as a ZIP file.
2. Open the `index.html` file in your browser.
3. Enter your Google API Key when prompted.
4. Adjust the sliders to configure:
   - Travel time (minutes)
   - Starting distance (km)
   - Number of attempts
   - Number of rays
5. Click the **Reach** button to calculate and visualize your reachable area based on live traffic!

---

## Important Notes

- **Google Free Tier Limit:** 10,000 requests per month.
- Using high numbers of rays or attempts may quickly consume your quota.
- This project is intended for personal, non-commercial use. Commercial use may require additional Google Maps licensing.

---

## License

© 2024 Ayberk Karaakin  
All Rights Reserved.

Unauthorized copying, use, or distribution of this code is prohibited.
