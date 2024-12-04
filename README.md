# LLM-Observability-LLM-Regression-Detailed-Testing-Scenario

Regression testing is a quality assurance technique used in software development. It ensures that changes to code don't mess things up.
How does this translate to LLM applications? When you change prompts, models, or retrieval strategies, you still need to test your software: nothing new here. But you also must test the generative part – the one that produces text, code, or content in response to user input. 

# Different Test Scenarios between target_response and new_response : 

## 1. Semantic similarity between target and new reponse
## 2. Classification quality
        a. Accuracy score
        b. Precision score
        c. Recall score
        d. F1 score

## 3. Text length
## 4. Competitor mentions
## 5. Toxicity
## 6. Sentiment
## 7. Neutrality


# Steps of Implementation : 

## Step 1. Define the dataset

![image](https://github.com/user-attachments/assets/65d802c2-90f5-4fd2-8bf0-4ed49d55c5d1)

## Step 2 : Define the test scenarios 

## Step 3 : Execute the test scenarios and generate the output , please find below updated dataframes post all the test scenarios are executed

![image](https://github.com/user-attachments/assets/25fbc6b3-518c-4ef9-b820-3f2ff59886b5)

![image](https://github.com/user-attachments/assets/73607217-fa2f-4b06-9679-f1f5d60785f6)

![image](https://github.com/user-attachments/assets/c0098946-cb9b-44cf-9797-ba5bc2f93c78)

![image](https://github.com/user-attachments/assets/e3a25a77-08d6-429a-a56d-3b6ec3cb1879)

![image](https://github.com/user-attachments/assets/5765044f-b6e7-4b5a-b425-cf3e9f7c1d78)

![image](https://github.com/user-attachments/assets/8eab9010-2ad9-4def-bf4b-1a06e8a4f5be)

![image](https://github.com/user-attachments/assets/74a65224-433d-4dc6-929d-63de1c167657)

![image](https://github.com/user-attachments/assets/abe3c86d-345e-46c5-a543-b582f95ac73d)

![image](https://github.com/user-attachments/assets/8bb02d52-fde9-4c9e-b925-1dfe9f2637e4)

![image](https://github.com/user-attachments/assets/c217067c-7981-4b2c-9c18-670cb8f9a8bd)

![image](https://github.com/user-attachments/assets/857cf311-77e9-4c63-9e66-1b03126da3ab)

## Step 4 : Combining tests ( leveraging Hugging face model for emotion classification )

![image](https://github.com/user-attachments/assets/03bbfb73-1948-465b-8d02-8a599fb45010)

## Step 5 : Set auto test condition

Happy coding :)














   


