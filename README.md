# Audiobook-From-PDF
Fed up of being on the screen constantly. Worry not, feed in your favourite short read in  pdf format into the code and have the mp3 audiobook generated for the same under the title "ultimateaudio" in your Downloadss folder!!
You will need to install the following :

pip install pdftotext //reads the pdf and converts to text
pip install gtts //google text to speech to access the audio

Quick tip: if using google colab to use pip install packages add '!' before the command.
Example : !pip install gtts

Add the location of your pdf to the code in the line where the line
with open('frost.pdf','rb') as text:

And find the audio file downloaded by the name 'ultimateaudio.mp3'
