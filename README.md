# TuniHack

# Building The Dataset
 In this phase, we attempt to build a dictionary for the tunisian sign language and gather datasets for our models.
  ## Context
  Because deaf people have few options for communicating with hearing people, and all of the alternatives have major flaws (interpreters aren't always available and can be expensive; you can't have an interpreter anywhere you go...), we devised an easy-to-use, innovative mobile application that works by placing a smartphone in front of the user while the app on the one hand translates gestures or sign language into text and on the other hand records doctor instructions and translates them into TSL videos. The app can interpret Tunisian sign language as fast as the user talks. We will detect a Tunisian sign language speaker's video using neural networks and computer vision, and then smart algorithms will convert it into text. By speech recognition, we will match different words recorded by several people to translate the doctor's words.
  Moreover, via this application, we will enable deaf people from different backgrounds to communicate, chat, and share their expertise with each other.
  As a first step, we have decided to limit ourselves to the context of a medical consultation. We've worked with a general practitioner that described the medical consultation. And using that description, we've extracted a list of words that we will use for our dictionary. 
   ## Building from Scratch
   We were able to find <strong>"Medical Dictionary in Tunisian Sign Languages"</strong> a dictionnary created by the IFT making the translation from french to Tunisian Sign Language
   ## Already Available Ressources
   This booklet contains 160 words used in the context of a medical consultation with their respective signs. By asking a doctor, we've sampled 16 relevant words as a starting size for our vocabulary.
   
   ## Mobile app description
   Implementation of  a mobile application so that our solution will reach a bigger number of people.
   ### - <strong>First interface</strong>
   The first Interface is the main page where the user chooses his role,whether he is a patient or a doctor.      
  ###  - <strong>Second interface</strong>
    If the user chose the doctor role he will be directed to an interface where he must enter a code  in order to open a temporary session to facilitate the communication with his patient 
   ###  - <strong>Third interface</strong>
     If the code written by the doctor is the same as the one the patient have , then he will be redirected to the third interface, where he can do both talking and understanding of the patient.
     
   #### Understanding the patient 
     This is when the doctor chooses to capture the patient's movements and there will be real time pattern recognition translating the movements into a text.
   ## Used model
     We needed to use a trained model like I3D because our dataset was still so small.
     I3D was trained on the American Sign Language dataset, and it is based on 3D convolutional layers, which will enable us to capture the temporary change of the different fixed points on our extracted frames.
     I3D needed to get tuned so he could adapt to our data filmed at a different resolution.
   #### Talking to the patient 
     In this part the doctor will record his voice and with real time speech recognition his voice would be intrepreted at the same time into a sign language video so the patient would understand what the doctor is saying.
   ###  - <strong>Fourth interface</strong>
     This when the user chose the patient role , he will be directed to an interface , where : 
      A live video interpreting the docotr's voice into sign language.
      A random code that is only available for an hour.
      An info sign so he will be directed to the Fifth Interface.
   ###   - <strong>Fifth interface</strong>
      We will provide users with more ressources on sign language qnd on how to use the application.
## Video shooting guidlines
These are the rules we imposed when we shot the videos:
- FPS (frames per second): 30
- Min/Max quality: 720p
- Framing: follow "Medical Dictionary in Tunisian Sign Languages" picture framing
- Sign speed: calibrate to one of the interpreters' signing speed
- Orientation: vertical

## Contacts
These are the various individuals and entities that may help us go further in this project by providinng us with other recorded videos
- Association Voix du Sourd de Tunisie
- Association Tunisienne des Interprètes en Langues des Signes
- IFT
