# SnapStory

**A universe of stories from vision**

---

SnapStory is an AI-powered application that transforms your images into engaging stories and narrates them for you! Upload up to 10 images, pick your favorite genre, and let the AI generate and narrate a unique story inspired by your visuals.

## Features

- **Image-to-Story Generation:**  
  Upload 1 to 10 images (PNG, JPG, JPEG), and SnapStory will analyze them to create a coherent narrative connecting all images in the order provided.

- **Genre Selection:**  
  Choose from multiple storytelling styles, including:
  - Comedy
  - Thriller
  - Fairy Tale
  - Sci-Fi
  - Mystery
  - Adventure
  - Morale

- **Indian Context:**  
  All stories are written with Indian names, characters, places, and cultural context.

- **Special Genre Sections:**  
  Some genres include unique conclusions:
    - **Morale:** A `[MORAL]:` section at the end of the story delivering the lesson.
    - **Mystery:** A `[SOLUTION]:` section that reveals the culprit and the key clue.
    - **Thriller:** A `[TWIST]:` section with a final, shocking twist.

- **AI Narration:**  
  After generating the story, SnapStory uses AI-based text-to-speech to narrate the story in English. Listen to your story directly in the app.

- **Interactive & Easy to Use:**  
  - Simple Streamlit web interface.
  - Real-time feedback and error handling for uploads and API issues.

## How It Works

1. **Upload Images:**  
   Use the sidebar to upload between 1 and 10 images.

2. **Choose a Style:**  
   Select your desired story genre from the dropdown.

3. **Generate Story:**  
   Click the "Generate Story and Narration" button. The AI will:
   - Interpret each image for key details.
   - Create a single, connected story with a beginning, middle, and end.
   - Write the story in simple, modern English.
   - For special genres, add a unique section (moral, solution, or twist).

4. **View and Listen:**  
   - See your images and the generated story on the main page.
   - Listen to the AI narration of your story.

## Example Use Cases

- Make bedtime stories from your family photos.
- Turn your vacation pictures into a fun adventure tale.
- Generate creative stories for children’s activities.
- Use as a storytelling tool in classrooms.

## Requirements

- Python 3.7+
- Streamlit
- Pillow
- google-generativeai
- gTTS
- python-dotenv

## How to Run

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. Set your `GOOGLE_API_KEY` in a `.env` file.

3. Run the app:
   ```bash
   streamlit run app.py
   ```

## Credits

Developed by [imswatisinha](https://github.com/imswatisinha).

---

## Link
https://swati-snapstory.streamlit.app/

Enjoy creating stories from your images with SnapStory!
