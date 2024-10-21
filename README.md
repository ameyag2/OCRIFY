# **OCRify - Extract Text from Images and PDFs Seamlessly 📝🚀**  
OCRify is an intuitive application designed to extract text from images and PDF files, leveraging the power of **Azure OCR** and **EasyOCR**. Whether you're a casual user or a premium subscriber, OCRify offers a range of features to simplify your text extraction tasks, from single-image uploads to advanced batch processing and text conversion to .docx format.


### **Screenshots**  
![ezgif com-animated-gif-maker](https://github.com/user-attachments/assets/19369425-0e60-4324-926e-ffba68cd5051)

<img width="1496" alt="Screenshot 2024-10-20 at 9 30 51 PM" src="https://github.com/user-attachments/assets/560f515a-d1d8-48fd-ba41-444d0eac3514">

<img width="1496" alt="Screenshot 2024-10-20 at 9 31 18 PM" src="https://github.com/user-attachments/assets/bafa30f9-2c0b-4a76-80bf-e962dc8d82dd">

<img width="1451" alt="Screenshot 2024-10-20 at 10 25 17 PM" src="https://github.com/user-attachments/assets/e9faeead-7e26-482e-b8b5-3bfcf899b6cb">

<img width="1444" alt="Screenshot 2024-10-20 at 10 25 30 PM" src="https://github.com/user-attachments/assets/1933144e-c3a4-425e-ac45-09332c43682b">

<img width="1448" alt="Screenshot 2024-10-20 at 10 25 44 PM" src="https://github.com/user-attachments/assets/afe879bb-78df-4304-ba9d-8aeb575a6097">

<img width="1496" alt="Screenshot 2024-10-20 at 10 26 20 PM" src="https://github.com/user-attachments/assets/ed5d803a-09aa-4360-8b9c-0540f4660333">

<img width="1452" alt="Screenshot 2024-10-20 at 10 26 37 PM" src="https://github.com/user-attachments/assets/ba8dbe96-4290-4d03-b42c-c1fbb7d89483">

<img width="1445" alt="Screenshot 2024-10-20 at 10 27 05 PM" src="https://github.com/user-attachments/assets/49729da6-c48b-4f0a-a156-eb4e498cc78d">


## **🔧 Key Features**  

1. **Login:** 
2. **Signup:**  
3. **Pdf reader:** 
4. **Image:**  
5. **Save to word document:**  
5. **Multiple Models Like Easy OCR, Azure AI:**  

## **🚀 How OCRify Works**  
1. **Upload Your Files:** Select images or PDFs from your computer.  
2. **Choose Your OCR Engine:** Pick between **Azure OCR** and **EasyOCR**.  
3. **Process & Display:** Extracted text is displayed directly on the results page.  
4. **Download Options:**  
   - **Free Users:** View or copy the extracted text.  
   - **Premium Users:** Download the results as .docx files or process multiple images at once.

---

## **🎨 User Interface Overview**  
OCRify offers a modern and responsive design, optimized for desktop and mobile devices. With clear navigation and intuitive workflows, users can smoothly switch between free and premium features.

## **💻 Technology Stack**  
### **Backend Technologies:**  
- **Python:** Core programming language for the app logic.  
- **Azure OCR & EasyOCR:** Engines for accurate text extraction.  
- **Streamlit:** Framework for building interactive user interfaces.  
- **Pillow:** For image handling and processing.  

### **Frontend Technologies:**  
- **HTML/CSS:** Styling and layout for a smooth user experience.

### **Database:**  
- **JSON:** For managing user data and subscription statuses.

---

## **📥 Installation Guide**  
### **System Requirements:**  
- **Python 3.7+**  
- **Azure OCR API Key** (Required for Azure OCR functionality)  

### **Setup Instructions:**  
1. **Clone the Repository:**  
   ```bash
   git clone <repository_url>
   cd OCRify
   ```

2. **Install Dependencies:**  
   ```bash
   pip install -r requirements.txt
   ```

3. **Configure Azure OCR:**  
   Set the environment variables for Azure API access:  
   ```bash
   export AZURE_OCR_KEY=your_key_here
   export AZURE_OCR_ENDPOINT=your_endpoint_here
   ```

4. **Run the Application:**  
   Start the Streamlit app:  
   ```bash
   python -m streamlit run textex_app.py
   ```  
   Open the app in your browser at: [http://localhost:8501](http://localhost:8501)

---

## **🔑 User Roles & Access**  
- **Free Users:**  
  - Access basic text extraction tools for single images and PDFs.  
  - View, copy, or edit extracted text directly on the app.

- **Premium Users:**  
  - Unlock advanced batch processing and downloadable .docx files.  
  - Get access to faster performance and exclusive updates.

---

## **🌐 Roadmap for Future Development**  
- **AI-based Translation:** Automate translation of extracted text into multiple languages.  
- **Optimized Performance:** Improve batch processing speed for large files.  
- **New File Format Support:** Add compatibility for Word and Excel document processing.

---

## **🤝 How to Contribute**  
We welcome contributions to improve OCRify!  

1. **Fork the Repository:**  
   ```bash
   git checkout -b feature/your-feature
   ```  

2. **Make Changes:**  
   Commit your updates:  
   ```bash
   git commit -m "Add your feature"
   ```

3. **Push and Open a Pull Request:**  
   ```bash
   git push origin feature/your-feature
   ```  
   Submit a pull request to the main branch.

---

## **🙏 Acknowledgements**  
- **Azure OCR:** For providing robust API services.  
- **EasyOCR:** For an open-source OCR solution.  
- **Streamlit:** For making UI development simple and fast.

---

OCRify offers powerful, flexible, and user-friendly OCR capabilities, whether you need to extract text from an image, convert a PDF to Word, or handle batch processing.
