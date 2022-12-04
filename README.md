# TuniHack

# Building The Dataset
 In this phase, we attempt to build a dictionary for the tunisian sign language and gather datasets for our models.
  ## Context
  Because deaf people have few options for communicating with hearing people, and all of the alternatives have major flaws (interpreters aren't always available and can be expensive; you can't have an interpreter anywhere you go...), we devised an easy-to-use, innovative mobile application that works by placing a smartphone in front of the user while the app on the one hand translates gestures or sign language into text and on the other hand records doctor instructions and translates them into TSL videos. The app can interpret Tunisian sign language as fast as the user talks. We will detect a Tunisian sign language speaker's video using neural networks and computer vision, and then smart algorithms will convert it into text. By speech recognition, we will match different words recorded by several people to translate the doctor's words.
As a first step, we have decided to limit ourselves to the context of a medical consultation. We've worked with a general practitioner that described the medical consultation. And using that description, we've extracted a list of words that we will use for our dictionary. 
   ## Building from Scratch
   We were able to find <strong>"Medical Dictionary in Tunisian Sign Languages"</strong> a dictionnary created by the IFT making the translation from french to Tunisian Sign Language
   ## Already Available Ressources
   This booklet contains 160 words used in the context of a medical consultation with their respective signs. By asking a doctor, we've sampled 16 relevant words as a starting size for our vocabulary.


## Video shooting guidlines
These are the rules we imposed when we shot the videos:
- FPS (frames per second): 30
- Min/Max quality: 720p
- Framing: follow "Medical Dictionary in Tunisian Sign Languages" picture framing
- Sign speed: calibrate to one of the interpreters' signing speed
- Orientation: vertical

## Contacts
These are the various individuals and entities that may help us go further in this project by providinng us with other recorded videos
- Association Voix du Sourd de Tunisie.
- Association Tunisienne des Interprètes en Langues des Signes.
