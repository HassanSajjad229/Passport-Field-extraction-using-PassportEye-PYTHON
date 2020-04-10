# Passport-Field-extraction-using-MRZ-Scanner | PassportEye
Passports have some fields with credentials that are of utmost importance.These fields can be used to verify the document to enhance security measures.So, fields are extracted using python instead of traditional OCR method. 

Passport was used to extract the data fields of the passport.

Following steps are done to extract the data from the passport
1.Image was read using  the MRZ read class.
2.It would than extract the fields in format of JSON key-pair value
3.Each extracted key-pair value was than stored to a csv file for further processing.
