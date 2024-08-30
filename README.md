# image_to_music
Generate music inspired by an image.

This project enables the creation of music based on the inspiration drawn from an image, leveraging multiple AI technologies.

## How It Works

1. **Image to Text Description**
   - Use PaliGemma, a multi-modal AI, to convert the image into a textual description.
   
2. **Text Description to Music Prompt**
   - Use Llama 8B, a large language model (LLM), to transform the image description into a music generation prompt.
   
3. **Music Prompt to Music**
   - Use Facebook MusicGen to generate music from the music generation prompt.

## Steps

1. **Image -> [ PaliGemma, Multi-modal AI ] -> Text (Image Description)**
2. **Text (Image Description) -> [ Llama 8B, LLM ] -> Text (Music Generation Prompt)**
3. **Text (Music Generation Prompt) -> [ Facebook MusicGen ] -> Music**

Let's turn your visual inspirations into beautiful melodies!

### HuggingFace Spaces
* https://huggingface.co/spaces/beingcognitive/Image_to_Music
