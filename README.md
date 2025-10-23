## LIVE LINK https://aizasyahdesuazxr47pha2usy6hntxnorkhkoxc.streamlit.app/
## AuraTale: The Vision-to-Narrative Synthesizer
A New Dimension of Digital Storytelling
AuraTale is an innovative, AI-driven web application that bridges the gap between sight and sound by automatically transforming your visual memories into rich, narrated stories. Upload your photos, select a theme, and watch as artificial intelligence weaves a seamless, personalized narrative complete with voice narration.

## Sequential Image-to-Text Synthesis
The application accepts a sequence of 1 to 10 images (supporting PNG, JPG, and JPEG formats). It analyzes the visual data of each picture and crafts a cohesive narrative arc that links every image in the exact order you provide, ensuring a logical flow from beginning to end.

## Thematic Story Customization
Tailor the atmosphere and style of your story by choosing from a robust menu of story genres:

Comedy

Mystery

Thriller

Sci-Fi (Science Fiction)

Adventure

Fairy Tale

Morale (Inspirational)

## Culturally Grounded Content
All generated stories feature Indian names, cultural elements, characters, and settings, providing a relevant and immersive experience for users interested in South Asian context.

## Advanced Genre Conclusions
Specific genres are enhanced with unique, formatted closing statements to maximize impact:

Mystery: Concludes with a [SOLUTION]: paragraph that clearly identifies the culprit and the crucial evidence.

Thriller: Ends with a sudden, dramatic [TWIST]: revelation designed to shock the reader.

Morale: Provides a final [LESSON]: section to explicitly state the moral learned from the tale.

## Automated Narration
Once the text is generated, AuraTale employs AI-based Text-to-Speech (TTS) technology to deliver a clear English narration. Users can listen to their story directly within the interface.

## Technical Overview & Setup
-User Workflow
Input: Drag and drop your images into the designated sidebar upload area.

Selection: Choose your preferred narrative theme from the dropdown menu.

Synthesis: Click the primary action button to trigger the AI generation pipeline.

Output: Instantly receive the written text, see your images, and play the embedded audio narration.

-Prerequisites to Run Locally
AuraTale is built on Python and uses a simple Streamlit front-end.

Python Version: 3.7 or newer.

Dependencies: All required packages are listed in requirements.txt.

-Deployment Steps
1. Install Libraries: Use the command line to fetch all required libraries.

Bash

pip install -r requirements.txt
API Key Configuration: Secure your GOOGLE_API_KEY by placing it in a .env file at the project root.

2. Launch Application: Run the Streamlit server to open the app in your browser.

Bash

streamlit run app.py

## Potential Applications
Creative Writing: Use photos from events or outings to automatically draft a narrative draft.

Education: A fun and engaging tool for teachers to spark children's imagination.

Personal Keepsakes: Transform simple vacation photos or family albums into memorable, narrated "audio books."

Developed by namrausman.
