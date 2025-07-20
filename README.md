# Smart-Diet-Recommendation-System

Project Overview:

The Smart Diet Recommendation System is designed to provide personalized diet plans based on user-specific health conditions, allergies, age, gender, and lifestyle preferences. It integrates user inputs with a curated nutrition database to generate optimal food recommendations, aiming to promote a healthy lifestyle, manage chronic conditions like diabetes and hypertension, and accommodate dietary restrictions such as lactose or gluten intolerance.
This system supports both vegetarian and non-vegetarian diets and includes a recipe generator for ease of implementation in daily meals.

Technologies Used:

Programming Language: Python
Frontend: Tkinter (GUI-based interface)
Backend: Rule-based logic integrated with user input filters
Dataset: Custom food-nutrient database (CSV format)
Tools: Pandas, Numpy, FPDF (for report generation), PIL (for image rendering), Tkinter
Development Environment: Local Machine (Windows/Linux)


Objectives:

Recommend diet plans tailored to user-specific health concerns and preferences
Accommodate dietary restrictions including lactose intolerance, gluten-free, diabetic-friendly, low blood pressure, and high blood pressure needs
Provide meal suggestions categorized by breakfast, lunch, and dinner
Generate downloadable PDF reports of personalized diet plans
Encourage healthy food choices and lifestyle improvement through digital intervention


User Inputs:

Name

Age

Gender


Health Issues (Multiple selections supported):

    Diabetes
    
    High Blood Pressure
    
    Low Blood Pressure
    
    Lactose Intolerance
    
    Gluten Allergy


Dietary Preference:

     Vegetarian
     
     Non-Vegetarian





Functional Workflow:

      User Data Collection: Input through Tkinter GUI
      
      Preference Filtering: Matches user profile with dietary rules
      
      Nutrient Mapping: Filters foods based on required nutrient levels and restrictions
      
      Meal Planning: Suggests ingredients and meals (breakfast, lunch, dinner)
      
      Recipe Suggestion: Descriptions and image links provided where available
      
      Report Generation: Final recommendations exported as a downloadable PDF


Health Considerations:

    Diabetes: Recommends low-GI, low-sugar, high-fiber foods
    
    High Blood Pressure: Suggests low-sodium, potassium-rich foods
    
    Low Blood Pressure: Recommends salt-containing and iron-rich foods
    
    Lactose Intolerance: Filters out all dairy-based items
    
    Gluten Allergy: Removes wheat, barley, and rye products


Features:



Easy-to-use GUI with form-based interaction
Intelligent filtering based on multiple health constraints
Personalization across multiple dimensions (age, gender, diet type)
Recipe insights to encourage healthy cooking
PDF export for offline use or consultation with dieticians


Sample Output (Example)

Input By user
     User Profile:

     Name: Arjun
     
     Age: 25
     
     Gender: Male
     
     Health Issues: Diabetes, Lactose Intolerance
     
     Diet Type: Vegetarian


Output By ML Model:

     Suggested Breakfast:
     Vegetable Upma with rolled oats
     Sprouted Moong Salad

     Suggested Lunch:
     Bajra Roti with Mixed Vegetable Curry
     Cucumber Raita (lactose-free)

     Suggested Dinner:
     Quinoa Khichdi
     Steamed Broccoli and Tofu




Future Enhancements:

     Integrate BMI calculator and calorie estimator
  
     Add machine learning-based optimization for food recommendations
  
     Support multi-language interface for wider accessibility
  
     Enable mobile application version with cloud-based diet history tracking
  
     API integration with wearable fitness devices (e.g., Fitbit)

