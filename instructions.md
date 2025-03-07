# Overview

This project is designed to give you hands-on experience working with an image classifier and enhancing your programming skills using AI assistance. The project has three parts, each focused on different aspects of image classification and processing. By the end, you'll have explored fundamental concepts like Grad-CAM, image occlusion, and creative image filtering.

## Part 1: Using the Basic Classifier and Implementing Grad-CAM

1. **Find an Image:**
- Choose an image you'd like to classify. This can be a personal photo or one from a free image repository (e.g., Unsplash).

2. **Run the Basic Classifier:**
- Use the provided base_classifier.py program to classify the image. This version of the program does not include comments or explanations.

- Prompt the AI to explain what each line of code in the program does. Example Prompt:
> "Explain what each line of this Python program does."

- If you do not have previous experience with Python, comment on whether the AI's explanations make sense to you. If you do have Python experience, comment on whether the AI's explanation agrees with your interpretation.
- Record the top-3 predictions and their confidence scores.
- Use the base_classifier.py program to classify the image.
- Record the top-3 predictions and their confidence scores.

3. **Implement Grad-CAM:**
- Prompt an AI to help you generate code to implement the Grad-CAM heatmap overlay. Example Prompt:
> "How can I add Grad-CAM to my image classifier to visualize the areas of the image the model focuses on?"

- Add the Grad-CAM functionality to the base_classifier.py program.

4. **Understand Grad-CAM:**
- Prompt the AI to explain what Grad-CAM is and how it works. Example Prompt:
> "Can you explain the Grad-CAM algorithm and how it highlights important areas of an image?"

5. **Analyze the Heatmap:**
- Run the updated classifier with Grad-CAM on your image.
- Identify which parts of the image the classifier focuses on most heavily.
- Record your observations.

## Part 2: Experimenting with Image Occlusion

1. **Generate Occlusion Ideas:**
- Prompt the AI to suggest three ways to occlude an image to obscure the areas identified in the Grad-CAM heatmap. Example Prompt:
> "What are three ways to occlude an image, such as adding a black box or blurring parts of it?"

2. **Implement Occlusions:**
- Modify the base_classifier.py program to implement the three occlusions suggested by the AI.
- Each occlusion should target the area highlighted by the Grad-CAM heatmap.

3. **Test the Occlusions:**
- Run the classifier on each occluded image.
- Record the top-3 predictions and confidence scores for each occlusion.

4. **Analyze the Results:**
- Compare the classifier's performance on the original image vs. the occluded versions.
- Answer the following questions:
    - Did the classifier struggle to classify the occluded images?
    - Which occlusion had the greatest impact on performance?

## Part 3: Creating and Experimenting with Image Filters

1. **Explore Filter Ideas:**
- Start with the provided basic_filter.py program, which applies a simple blur to an image. This version of the program does not include comments or explanations.
- Prompt the AI to explain what each line of code in the program does. Example Prompt:
> "Explain what each line of this Python program does."

- If you do not have previous experience with Python, comment on whether the AI's explanations make sense to you. If you do have Python experience, comment on whether the AI's explanation agrees with your interpretation.
- Prompt the AI to suggest three alternative filters to apply. Example Prompt:
> "What are three different filters I can apply to an image, such as edge detection or sharpening?"

- Start with the provided basic_filter.py program, which applies a simple blur to an image.
- Prompt the AI to suggest three alternative filters to apply. Example Prompt:
> "What are three different filters I can apply to an image, such as edge detection or sharpening?"

2. **Implement Filters:**
- Modify the basic_filter.py program to implement the three new filters suggested by the AI.

3. **Design Your Own Artistic Filter:**
- Use creative prompts to direct the AI to develop an artistic filter. Example Prompt:
> "Modify the program to create a filter that makes the image look 'deep fried,' with exaggerated colors and noise."

- Experiment with different ideas and iterate on the filter until you're satisfied with the result.

Deliverables

Final Report:
Summarize your findings from each part of the project.
Highlight what you learned about the classifier's behavior from the heatmap and how it is impacted by occlusions.
Describe the filter you developed. What kind of effect does it have on your image?
Reflect on your experience working with the AI to explain and write Python code.