# Homemade Protein Powder: A Research-Backed Infographic & AI Nutrition Tool


## 1. Introduction

This project is a single-page web application designed for Indian vegetarians who are serious about their fitness but face challenges with the high cost and questionable quality of commercial whey protein supplements.

It began as a personal research project to find an affordable, safe, and effective post-workout protein source. The result is a data-driven infographic that not only presents a cost-effective homemade solution but also educates users on the hidden drawbacks of commercial supplements, backed by scientific research.

This application has been enhanced with the **Google Gemini API** to provide dynamic, AI-powered nutritional tools, transforming it from a static report into a personalized health assistant.

## 2. Key Features

This application is structured into several key sections:

* **Market Case Study:** A financial and compositional analysis of the homemade protein blend versus commercial alternatives.
* **Hidden Drawbacks:** An infographic page detailing 10 research-backed drawbacks of commercial whey protein, from nutritional damage to heavy metal contamination.
* **Myth Busters:** A direct, evidence-based comparison that debunks the myth that "commercial is always better."
* **✨ AI-Powered Tools:**
    * **AI Recipe Generator:** Creates custom homemade protein powder recipes based on user's dietary needs (e.g., allergies, flavor preferences).
    * **AI Post-Workout Meal Planner:** Suggests simple, affordable, and nutritious vegetarian meals to complement the protein shake after a specific workout.

## 3. Technology Stack

* **Frontend:** HTML5, Tailwind CSS, JavaScript
* **Data Visualization:** Chart.js
* **Artificial Intelligence:** Google Gemini API

---

## 4. How to Set Up and Run This App Locally (Step-by-Step)

This application is a single, self-contained HTML file. To run it on your local machine and enable the AI features, please follow these steps carefully.

### **Step 1: Get the Project Files**

You need to download the code from this GitHub repository.

* Click the green **`< > Code`** button on the main repository page.
* Select **"Download ZIP"**.
* Find the downloaded `.zip` file on your computer and extract it. You will now have a folder containing the `index.html` file.

### **Step 2: Get Your Free Google Gemini API Key**

The AI features (Recipe Generator and Meal Planner) require an API key from Google. This is a free and simple process.

* Go to the Google AI Studio website: **[https://aistudio.google.com/app/apikey](https://aistudio.google.com/app/apikey)**
* If prompted, sign in with your Google account.
* Click the **"Create API key"** button.
* A new key will be generated for you. Click the copy icon next to it to copy your key to the clipboard.

> **Note:** Treat your API key like a password. Do not share it publicly.

### **Step 3: Add Your API Key to the Application**

Now, you need to tell the application what your API key is.

* Open the `index.html` file using a simple text editor (like **Notepad** on Windows or **TextEdit** on Mac).
* Scroll down to the very bottom of the file to find the `<script>` section.
* Look for the following line of code:

    ```javascript
    const apiKey = ""; 
    ```

* Paste the API key you copied from Google AI Studio directly between the double quotes (`""`).

    **Before:**
    ```javascript
    const apiKey = ""; 
    ```

    **After (Example):**
    ```javascript
    const apiKey = "AIzaSyB...your...unique...key...goes...here...xyz"; 
    ```
* Save the changes to your `index.html` file.

### **Step 4: Run the Application**

You're all set!

* Find the `index.html` file in the folder you extracted.
* **Double-click the file.**
* It will open directly in your default web browser (like Chrome, Firefox, or Safari).

The application is now running on your local machine, and all features, including the AI Tools, are fully functional.

## 5. Research & Data Sources

The information and data presented in this infographic are based on analysis of the following scientific papers:

1.  Sánchez-Oliver, A. J., Contreras-Calderón, J., Puya-Braz, J. M., & Guerra-Hernández, E. (2018). Quality analysis of commercial protein powder supplements and relation to characteristics declared by manufacturer. *LWT - Food Science and Technology, 97*, 100-108.
2.  Saxton, R., & McDougal, O. M. (2021). Whey Protein Powder Analysis by Mid-Infrared Spectroscopy. *Foods, 10*(5), 1033.
3.  Bandara, S. B., Towle, K. M., & Monnot, A. D. (2020). A human health risk assessment of heavy metal ingestion among consumers of protein powder supplements. *Toxicology Reports, 7*, 1255–1262.
4.  Ingle, P. D., Christian, R., Purohit, P., Zarraga, V., Handley, E., Freel, K., & Abdo, S. (2016). Determination of Protein Content by NIR Spectroscopy in Protein Powder Mix Products. *Journal of AOAC International, 99*(2), 360–363.

