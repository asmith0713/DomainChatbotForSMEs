# 📚 **Domain Chatbot**

This project is a **web-based chatbot application** designed to interact with users in a conversational manner. It features a dynamic UI with **theme switching capabilities** and integrates with a **backend API** for processing user messages.

---

## 🚀 **Features**

- **💬 Responsive Chat Interface:** A clean and responsive chat interface built with **HTML**, **CSS**, and **JavaScript**.
- **🎨 Theme Switching:** Users can switch between different themes (**Dark**, **Light**, **Nature**) to customize their chat experience.
- **✨ Animated Messages:** Smooth animations for message transitions using **Animate.css**.
- **🔗 Backend Integration:** Communicates with a backend **API** to process and respond to user messages.

---

## 🛠️ **Technologies Used**

- **Frontend:** HTML, CSS, JavaScript
- **Styling:** Bootstrap, Animate.css
- **Build Tool:** Vite
- **Backend API:** Integrated via a custom API endpoint

---

## Demo Video



https://github.com/user-attachments/assets/c9cb80ed-d7bd-403f-b3f8-29e0233edb33


---

## 📥 **Installation**

### **1. Clone the repository:**
```bash
git clone https://github.com/asmith0713/DomainChatbotForSMEs.git
cd project
```

### **2. Install dependencies:**
Make sure you have **Node.js** installed, then run:
```bash
npm install
```

### **3. Run the server:**
```bash
npm run dev
```

---

## 💻 **Usage**

- Open the application in your browser.
- Interact with the chatbot by typing messages in the input field and pressing the **Send** button.
- Switch themes using the **dropdown menu** in the chat header.

---
---

## 📖 **Notebook Details**

The Jupyter notebook included in this project demonstrates the following:

- **Dependencies Installation:** Installation of required libraries like PyMuPDF, faiss-gpu, transformers, pdfplumber, sentence-transformers, bitsandbytes, huggingface_hub, flask, flask-cors, and pyngrok.
- **Library Imports and Authentication:** Importing necessary libraries and authenticating with Hugging Face Hub.
- **Text Extraction from PDF:** Extracting text from a PDF document using pdfplumber.
- **Text Chunking:** Splitting extracted text into manageable chunks.
- **Embedding Generation:** Using the 'all-MiniLM-L6-v2' model from Sentence Transformers to generate embeddings for the text chunks.
- **FAISS Index Creation:** Creating and populating a FAISS index with the generated embeddings.
- **Model Loading and Quantization:** Loading and quantizing the 'Llama-3.1-8B-Instruct' model using BitsAndBytesConfig.
- **Text Generation Pipeline:** Initializing a text generation pipeline with the quantized model.

These techniques and models enable efficient processing and querying of large textual data, making the chatbot capable of handling domain-specific queries effectively. 

---

## 🤝 **Contribution**

Contributed by our Project School Team(G227) of KMIT 🎉

- [M Asmith](https://github.com/asmith0713)
- [T Venkatesh](https://github.com/venkateshtagulla)
- [S Shishir](https://github.com/Shishir2105)
- [P Arjun](https://github.com/Arjun7304)
- [B Nareen Sai](https://github.com/Nareen20)
- [C Sai Prathyun Gupta](https://github.com/Gupta-01)

---
## 🚧 **Limitations and Future Work**

Due to limited resources, we were unable to fully train the model. Instead, we utilized BitsAndBytesConfig to load and use the model directly. Consequently, the accuracy of the generated answers may not be optimal. We welcome suggestions and contributions for further development and improvements to enhance the model's performance.

Thank you for your understanding and support!
---

Happy coding! 🚀😊
