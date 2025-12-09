# flights-price-analysis
This project analyses 300,000+ flight records from Indian airlines to uncover pricing trends. Using Python, pandas, NumPy, seaborn, and matplotlib, it explores how departure time, arrival time, cities, class, duration, and days left affect fares, revealing insights for smarter travel cost optimization.
## 📌 Project Overview
This project explores a dataset of **300,000+ flight records** from multiple Indian airlines.  
The goal is to analyze how flight prices vary with factors such as:
- Departure and arrival times  
- Source and destination cities  
- Number of stops  
- Travel class (Economy/Business)  
- Flight duration  
- Days left before departure  

By combining **Python, pandas, NumPy, seaborn, and matplotlib** in Google Colab, the analysis uncovers meaningful insights into airline pricing strategies and traveler cost optimization.

---

## 📊 Key Insights
- **Departure Time vs Price**  
  - Night flights are the most expensive.  
  - Late-night flights are the cheapest.  
  - 👉 Booking in the afternoon saves ~20% compared to night flights.

- **Days Left vs Price**  
  - Prices are highest close to departure (0–5 days left).  
  - Prices gradually decrease and stabilize after ~20 days.

- **Airline Frequencies**  
  - Vistara operates the most flights, followed by Air India and Indigo.  
  - SpiceJet has the fewest flights in the dataset.

- **Extreme Cases**  
  - Maximum price: ₹123,071 (Business class, Vistara).  
  - Minimum price: ₹1,105 (Economy class, AirAsia/GO_FIRST).

---

## 🛠 Tools & Libraries
- **Python 3**  
- **pandas** – data cleaning and transformation  
- **NumPy** – numerical operations  
- **seaborn & matplotlib** – data visualization  
- **Google Colab** – interactive analysis environment  

---

## 📂 Dataset
- File: `airlines_flights_data.csv`  
- Size: 300,153 rows × 12 columns  
- Features include: airline, flight, source city, departure/arrival time, stops, destination city, class, duration, days_left, price.

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/flights-price-analysis.git
