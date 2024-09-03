# Speech-to-sign
Initialization

Start the program and initialize the necessary components.
Capturing Speech

Ambient Noise Calibration: Listen for 1 second to calibrate the energy threshold based on ambient noise levels, ensuring accurate speech detection.
Speech Capture: Capture the speech input from the microphone using the calibrated energy threshold for reliable detection.
Speech Recognition

Convert the captured audio to text using a speech recognition engine.
Text Processing

Text Normalization: Convert the recognized text to lowercase to standardize it for further processing.
Text Analysis and Translation

Exit Condition: If the detected text is "goodbye," terminate the program.
Dictionary Lookup: If the detected text matches a phrase in the predefined dictionary, display the corresponding GIFs representing the sign language translation.
Character Count & Visualization:
If the phrase is not in the dictionary, count the letters in the word or phrase.
Display the sign language visualization of the phrase, with appropriate delays between actions to ensure clarity.
Looping: Continue processing new speech input from step 3, looping through the steps until speech input ends.
Error Handling

If no speech is detected during the capture phase (Step 2), display an error message, such as "Could not detect speech," and prompt the user to try again.

IMPORTANT Note:
Inside the ISL_GIFS folder, there is another folder named ISL_GIFS.

Copy all the GIFs from the second ISL_GIFS folder (the inner folder) into the first ISL_GIFS folder (the outer folder).
After copying, delete the second ISL_GIFS folder (the inner folder).
