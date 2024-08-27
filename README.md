HTML Structure:

An input field with an ID of "input" where users can type text.
A button that triggers the speak() function when clicked.
JavaScript Function (speak()):

The function retrieves the text value from the input field.
It creates a new SpeechSynthesisUtterance object using the retrieved text.
The speechSynthesis.speak() method then takes the utterance object and converts the text to speech.
