# BizCardX-Extracting-Business-Card-Data-with-OCR  ![MIT LICENSE](https://badgen.net//badge/license/MIT/green)   ![MAINTAINED BADGE](https://img.shields.io/badge/Maintained%3F-yes-green.svg)

`Application Link:` https://shamhiruthik-bizcardx-extracting-business-ca-bizcard-app-xlx2u8.streamlit.app/

 `Demo Link:` 

This code is an OCR application that extracts text from images uploaded by users, using the EasyOCR library. 
The extracted text is then processed to extract information such as email, phone number, pin code, address, 
and website URL, and displayed on a Streamlit web app interface. User will be able to upload this information into 
database and can delete at anytime

## Skills required:
    
    Python, AWS-RDS-MYSQL, Streamlit, Regular Expressions, OCR, CSS, HTML 

## Features:

    Extracts Website URL, Email, Pin Code, Phone Number(s), and Address from the uploaded image.
    Displays the uploaded image along with the extracted text.
    
## Installation:

  open cmd:
1. > C:\Users\shamhiruthik> pip install virtualenv 
2. > C:\Users\shamhiruthik> virtualenv my_bizcards_env
3. > C:\Users\shamhiruthik> cd my_bizcards_env
4. > C:\Users\shamhiruthik\my_bizcards_env> cd Scripts
5. > C:\Users\shamhiruthik\my_bizcards_env\Scripts>activate                    # It will activate the virtual environment
6. > (my_bizcards_env)  C:\Users\shamhiruthik\> mkdir bizcards           #create a folder 
7. > (my_bizcards_env)  C:\Users\shamhiruthik\> cd bizcards              # download the above files from this repository and place inside this folder
8. > (my_bizcards_env)  C:\Users\shamhiruthik\bizcards> pip install -r requirements.txt       # it will install all the required modules in the environment
9. > (my_bizcards_env)  C:\Users\shamhiruthik\phonepe> streamlit run Bizcard_App.py  # Now run the app using streamlit
10. > You can now view your Streamlit app in your browser.


## Usage
   *  Once the application is running, upload an image using the “Upload Image” button
   * The application will extract the text from the image and display it in the “Extracted Text” section.
   * The extracted text will include the Website URL, Email, Pin Code, Phone Number(s), and Address.

    
## Advantages:
   * Time-saving: OCR technology enables the automated extraction of data from business cards, saving time and effort 
    that would otherwise be spent on manual data entry.
   * Increased accuracy: OCR technology has the potential to reduce errors and improve accuracy compared to manual data entry.
   * Scalability: OCR technology can handle large volumes of business cards, making it an ideal solution for businesses 
    with high volumes of contacts.
   * Easy integration: OCR technology can be easily integrated into existing systems and applications, making it a seamless 
    addition to existing workflows.
   * Cost-effective: OCR technology can be a cost-effective solution compared to hiring additional staff to handle manual 
    data entry tasks.
    
## Limitations:
   * While the app has been designed to make accurate predictions, occasional incorrect outputs may occur.
   * This can happen due to various factors such as low-quality input data or unexpected changes in the input data.
    
## Note:
    * The application can extract text in English language only.  
    * It will extract information only from BUSINESS CARDS 
