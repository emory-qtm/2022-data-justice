<h2> Setup for this notebook: </h2>

<h4> Database Setup </h4>

The dataset the notebook currently uses is the aligned.tar.gz Adience dataset from (Adience Download)[http://www.cslab.openu.ac.il/download/adiencedb/AdienceBenchmarkOfUnfilteredFacesForGenderAndAgeClassification/]

If it asks: username is adiencedb and password is adience

From that link, also download the fold_frontal_0_data.txt file for metadata

<h4> Facial Attribute Analysis Model Setup </h4>

Use pip to install “deepface”. Model comes from (Deepface Github)[https://github.com/serengil/deepface]

Then, download the pre-trained weights for the gender classification part of the model from (this google drive)[https://drive.google.com/uc?id=1wUXRVlbsni2FN9-jkS_f4UTUrm1bRLyk]. 

The downloaded file must be placed in “~/.deepface/weights/gender_model_weights.h5”.

<h4> Directory Structure </h4>

Place all of the Adience database files into a directory named "aligned" in the top level directory, and everything should be good to go.

