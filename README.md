# 🥗🤖 Smart Diet Planner Bot – Dual-Mode Automation with UiPath 💻🧠

🚀 **Season 2: Empowering Automation for Everyone**  
🎓 Hosted by [UiPath Student Community KIIT (USC.KIIT)](https://community.uipath.com/)

A mini-project that blends **RPA** with **personal wellness** – this bot calculates your BMI and generates a tailored diet plan using two automation paths:  
1️⃣ Automated Mode (Message Box logic)  
2️⃣ Web Scraping Mode (Eat This Much integration)

---

## 🍽️ What It Does

🔸 Takes user inputs – Name, Height (cm), Weight (kg)  
🔸 Calculates BMI using `Assign` activity  
🔸 Offers two automation modes:

### ⚡ Automated Mode
- Displays calorie info & diet tips via Message Boxes  
- Uses flowchart logic based on BMI category  
- Includes custom Message Box buttons for restart/exit

### 🌐 Web Scraping Mode
- Opens [Eat This Much](https://www.eatthismuch.com/) via browser  
- Inputs calorie targets based on BMI  
- Navigates using dynamic selectors  
- Extracts meal plans for:
  - Underweight: 3000 cal  
  - Normal: 2500 cal  
  - Overweight: 1800 cal  
  - Obese: 1500 cal

---

## 🎥 Demo

The demo showcases the “Normal” BMI category — a perfect weight scenario with a 2500-calorie plan.  
The bot is built to dynamically handle all four BMI categories.

---

## 🛠️ Tech Stack

🔹 `Flowchart`, `Assign`, `Input Dialog`, `Message Box`  
🔹 `Use Application/Browser`, `Click`, `Type Into`, `Scroll`, `Get Text`  
🔹 `If-Else`, `Flow Decision`  

---

## 📚 What I Learned

✔️ Dual-path automation design  
✔️ Real-time scraping logic  
✔️ UI-focused branching  
✔️ Health-tech meets RPA


