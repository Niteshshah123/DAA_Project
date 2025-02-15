# DAA_Project

### **Project Title: AI-Powered Sentiment-Based Travel Assistant**  

#### **Problem Statement:**  
Travelers often struggle with **trip planning, managing bookings, and resolving issues** while on the go. Customer support chatbots fail to understand user **sentiment**, leading to **frustration**, especially when users face **unexpected travel issues** (e.g., flight delays, hotel problems). A lack of **personalized recommendations** based on mood and preferences further worsens the experience.  

#### **Integrated Solution:**  
An **AI-powered travel assistant** that:  
✅ **Plans personalized trips** based on **budget, interests, weather**, and real-time discounts.  
✅ **Understands user sentiment** (positive, negative, or neutral) from chat queries and **adjusts responses accordingly**.  
✅ **Stores user preferences & trip history in a database** for better recommendations and issue resolution.  
✅ **Escalates urgent issues** (e.g., missed flights, overbooked hotels) to a **human agent** when negative sentiment is detected.  
✅ **Provides real-time updates** and offers alternatives for canceled flights, hotel issues, or transportation delays.  

#### **How It Works:**  
1️⃣ **User Inquiry:** The AI chatbot interacts with the user to plan a trip or resolve an issue.  
2️⃣ **Sentiment Analysis:** The chatbot **analyzes sentiment** from user messages using **NLP techniques** (positive, neutral, negative).  
3️⃣ **Dynamic Response:**  
   - **Positive Sentiment:** AI provides **upbeat travel tips, exclusive offers**, and joyful responses.  
   - **Neutral Sentiment:** AI gives standard responses and allows further customization.  
   - **Negative Sentiment:** AI **prioritizes issue resolution**, providing **apologies, urgent solutions, and faster support**.  
4️⃣ **Database Integration:**  
   - Stores past **trip preferences, feedback, and issues** to enhance future recommendations.  
   - Fetches available flights, hotels, and activities dynamically from **travel APIs** (e.g., MakeMyTrip, Skyscanner).  
5️⃣ **Escalation Mechanism:** If AI detects extreme **negative sentiment**, it immediately **escalates the case** to a **human agent** for personalized assistance.  

#### **Example Use Cases:**  
✔ **Scenario 1 - Planning a Trip:**  
   - User: "I want to travel to Goa for 5 days on a budget of ₹30,000."  
   - AI: (Analyzes preferences, checks database) "Here’s your best itinerary with budget stays, Weather Condition & local attractions!"  

✔ **Scenario 2 - Issue During Trip:**  
   - User: "My flight got canceled, and I don’t know what to do!"  
   - AI: (Detects negative sentiment) "I understand your frustration. Let me check alternative flights for you." (Fetches flights from the DB)  
   - If the user remains unsatisfied, AI escalates to a **human travel assistant**.  

#### **Technology Stack:**  
- **AI/NLP:** Python (NLTK, spaCy, or TensorFlow for sentiment analysis)  
- **Backend:** Node.js / Java Spring Boot (for API & DB management)  
- **Database:** MySQL/PostgreSQL (stores user preferences, trip details, issue logs)  
- **Frontend:** React Native 
- **API Integration:** Skyscanner, Google Flights, MakeMyTrip, etc.  
