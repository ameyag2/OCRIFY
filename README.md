# **OCRify - Extract Text from Images and PDFs Seamlessly 📝🚀**  
OCRify is an intuitive application designed to extract text from images and PDF files, leveraging the power of **Azure OCR** and **EasyOCR**. Whether you're a casual user or a premium subscriber, OCRify offers a range of features to simplify your text extraction tasks, from single-image uploads to advanced batch processing and text conversion to .docx format.

## **🔧 Key Features**  

1. **Login:** 
2. **Signup:**  
3. **Pdf reader:** 
4. **Image:**  
5. **Save to word document:**  
5. **Multiple Models Like Easy OCR, Azure AI:**  

### 🆓 **For Free Users:**  
- **Image Upload & Text Extraction:** Process individual images with Azure OCR or EasyOCR.  
- **Entity Recognition:** Identify key information from extracted text for structured insights.  
- **Basic PDF Processing:** Extract text from PDF files with ease.

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

### **Screenshots**  



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