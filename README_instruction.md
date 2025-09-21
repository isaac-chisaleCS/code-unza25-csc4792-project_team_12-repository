 # Unza Faculty Publication Classification Project – README
 ## Overview
 
This project builds an Author Classification System that predicts whether a research publication is authored by UNZA (University of Zambia) researchers or non-UNZA authors.
The notebook follows a full machine learning pipeline:

    1.	Data Loading & Cleaning
    2.	Feature Engineering
    3.	Model Training & Evaluation
    4.	Real-World Testing
    
 The system supports interactive testing where you can:
* Select from preloaded publications using a dropdown.
* Upload your own files (.pdf, .txt, .json, .csv) to test predictions.
________________________________________

 # NOTE: You Must Run All Cells Before Testing
 
Google Colab does not keep memory when the runtime disconnects. This means:
*	Models are not pre-saved.
*	If you only run the test code (Part 5), there will be no trained models in memory.
*	Therefore, you must execute the entire pipeline (Parts 1–4) first.
Here’s what happens in each part:

    1.	Part 1–2: Data Loading & Cleaning → Loads the dataset and cleans text.
    2.	Part 3: Feature Engineering → Converts text and authors into numeric features.
    3.	Part 4: Model Training → Trains Random Forest, Logistic Regression, and Naive Bayes.
     
             *	Saves the best models in memory (best_author_model, best_combined_model, etc.).
      
  5.	Part 5: Testing → Uses those trained models to classify new publications.
 If you skip Parts 1–4, Part 5 will fail because the models don’t exist.

# Steps to Run the Project

 # 1. Install Dependencies
    
    •	Ensure you’re connected to a runtime.
    •	Run the first cell to install required packages.
    
 # 3. Run All Cells (Parts 1–4)
    •	Run each cell from the top until Part 4 finishes.
    •	This will:
    
          o	Load and clean data
          o	Engineer features
          o	Train and evaluate models
          
 # 3.Test Publications (Part 5)
Now you can use the interactive testing section:

  # Option A: Dropdown Menu
  
        o	Choose from built-in test publications (e.g., UNZA_Publication, Non_UNZA_Paper).
        o	Results will show predicted class (UNZA / Non-UNZA) and confidence scores.
    
  # Option B: Upload Your Own File
    
    o	Upload .pdf, .txt, .json, or .csv.
    o	The system extracts title, authors, abstract, and keywords.
    o	Runs classification and displays results.

