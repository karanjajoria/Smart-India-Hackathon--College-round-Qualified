# 🌿 Smart India Hackathon 2024 - Real-Time AQI Monitoring System

**Problem Statement ID**: SIH1616  
**Problem Statement Title**: Technological solutions for capturing AQI values through mobile and other forms of stations  
**Theme**: Clean & Green Technology  
**Category**: Software  
**Team Name**: Glitch1.0  

---

## 💡 Project Overview

This project provides a **real-time Air Quality Index (AQI) monitoring solution** that captures AQI data from mobile devices and sensor-equipped drones. It integrates APIs, geolocation, and machine learning to provide accurate and user-friendly AQI readings across multiple platforms.

---

## 🧠 Proposed Solution

- **Real-Time Monitoring** via mobile and station-based sensors.
- **API Integration** from multiple sources to ensure reliable AQI data.
- **GPS-Based AQI Reporting** for location precision.
- **Drone-Based Industrial Monitoring** for high-pollution zones.

---

## 🛠️ Technologies Used

### Frontend
- `NextJS`
- `Tailwind CSS`
- `Shadeshine UI`

### Backend
- REST APIs for real-time weather and AQI data.

### APIs Used
- **OpenWeatherMap API**: Weather + AQI data
- **AQICN / AirVisual API**: Global AQI data
- **Ambee API**: Real-time AQI
- **WeatherAPI**: Weather details (paid plans)
- **Geo-Location API**: For accurate user-specific data
- **OpenAQ + Scraping**: For historical data collection

---

## 🧩 System Framework

- **LSTM Network**: Predicts AQI from PM2.5 & PM10 data.
- **Drones**: Measure pollutants like CO2, CO, NO₂, SO₂, O₃ and record temp & humidity.
- **Real-Time Processing**: APIs + ML pipeline for instant feedback.
- **Architecture Flow**:
  1. Data Collection
  2. Data Preprocessing
  3. Model Designing (LSTM)
  4. Model Training (MSE Loss)
  5. Prediction & Evaluation

---

## 🔍 Features

- **Location-Based Search**: Enter city or use GPS.
- **Custom Dashboard**: Theme toggle + multi-language support.
- **Real-Time Data**: Weather, temperature, humidity, wind speed.
- **Forecast Graphs**: Hourly & weekly trends.
- **Pollutant Breakdown**: PM2.5, PM10, NO₂, SO₂, O₃, CO.
- **Interactive Charts**: Hover-enabled insights for users.

---

## ✅ Feasibility & Viability

### Technology Readiness
- Mobile sensor and app compatibility validated.

### Market Demand
- Appeals to individuals, enterprises, and government bodies.

### Integration Capability
- Seamless with existing environmental systems.

### Cost & Resources
- Efficient deployment via AWS/GCP using Flask or Django.

---

## ⚠️ Challenges & Mitigation

| Challenge | Solution |
|----------|----------|
| **Data Accuracy** | Use high-quality sensors + validation algorithms |
| **Device Calibration** | Implement scheduled calibration protocols |
| **Data Privacy** | Apply robust encryption, follow GDPR & other norms |

---

## 🚀 Deployment

- Can be deployed on **AWS** or **Google Cloud**.
- Backend APIs can be hosted using **Flask** or **Django**.
- Real-time data processing & display enabled through REST APIs.

---

## 📊 Benefits

- 📈 Higher Accuracy  
- 🔁 Dynamic Learning  
- ⚙️ Automated Monitoring  
- 🧠 Intelligent Insights  
- 📍 Location Precision  

---
## 📸 Screenshots

[![Weather Dashboard]([assets/dashboard_sample.png](http://smart-india-hackthon-project.vercel.app/)) ](http://smart-india-hackthon-project.vercel.app/)]
*Live Demo*

---

> Built with 💚 by Glitch1.0 for Smart India Hackathon 2024
===
This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
