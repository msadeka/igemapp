# igemapp
iGEM - International Genetically Engineered Machine - competition is organised by the MIT each year to promote research in Synthetic Biology. For more details about iGEM, please refer to this link: https://igem.org/About.
In 2018, my team and I represented Carnegie Mellon University Qatar and worked on a project that has ensured faster diagnosis of genetic diseases, Sickle Cell Anemia in particular. Partnering with the software team, I assisted in the backend coding of our own iGEM website (http://2018.igem.org/Team:CMUQ). Additionally, I collaborated with the hardware subteam to develop an application that synchronises with a detection device and translates data to be easily understood by everyone. Later that year, we presented our project at the Giant Jamboree in Boston, Massachussets, USA.


Purpose of the Application
The main goal of the Android application is to reach a wide range of users - general practitioners, NGOs, healthcare in rural areas and even individuals who do not have prior knowledge of Sickle Cell Anemia. The app will help them with genetic counseling based on an individual’s diagnosis or risk of being diagnosed with Sickle Cell Anemia (SCA). 


The application serves three main purposes:
1. raises awareness about Sickle Cell Anemia
2. provides genetic counseling through accessible and known family history
3. displays the diagnosis results and a follow-up advising in an engaging manner 


Currently the two main features are:

# Counseling by pedigree
Individuals will fill up the details about themselves, their partner (if applicable), their parents, their paternal and maternal grandparents where applicable. The algorithm at the backend will compute the family pedigree and analyze the risk accordingly. So they can check if their children are at a risk of being diagnosed with Sickle Cell Anemia, carrier or are unaffected. The different percentages will also have specific interpretations regarding their family planning.

# Counseling by diagnosis
Individuals can take the test using our device. The application will display the results from the device and provide family planning advice accordingly.


Software specifications:
The application is built using Cordova framework in Android Studio. The backend algorithm is designed in Javascript and the device connection is established over Bluetooth using Bluetooth API provided by Android.
