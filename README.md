# Project-Portfolio

🚀 **My Developer Portfolio** – A collection of my software, AI, and web development projects.  

📌 **Featured Projects:**  
- **Akebulan AI – Indigenous Language AI Model** *(2024–Present)*  
- **React Bible App** – A self-hosted scripture archive with REST API and AWS deployment.  
- **Balanced Life NGO Website** – A no-code website builder template for NGOs.  
- **Samalie Bot** – AI-powered coding assistant with code generation and debugging.  
- **Walkie-Talkie App** – A real-time voice communication platform.  

🔹 **Tech Stack:** Python, Java, C++, JavaScript, React, React Native, Node.js, Firebase, Cordova, Vite.  

🌍 **Connect:** [LinkedIn Profile](https://linkedin.com/in/sekanjako-mathew)  

---

## **Akebulan AI – Indigenous Language AI Development**

Developing **Akebulan AI**, an open-language model trained to understand and generate text in **Luganda**, with long-term plans to support other Bantu and African languages.

- Fine-tuned **Mistral-7B** with **QLoRA** for efficient training on **RunPod RTX A6000** and **Google Cloud T4/A100** GPUs.  
- Engineered a **custom SentencePiece tokenizer** (ABLT) using a linguistically-aware corpus of 100K+ Luganda sentences.  
- Performed **morphological analysis, syllable distribution**, and **OOV rate optimization** to build a tokenizer tailored for agglutinative Bantu syntax.  
- Enabled **token-level importance tracking** and **translation alignment** using `HF Transformers`, `Datasets`, `PEFT`, and `bitsandbytes`.  

### **Screenshots and Sample Output**

- **Model Training Interface**  
  ![Training](https://github.com/Psalms23Wave/Akebulan-Ai/blob/main/models/Screenshot%202025-04-14%20at%202.38.22%20PM.png)

- **Tokenizer Breakdown and Token IDs**  
  ![Token IDs](https://github.com/Psalms23Wave/Akebulan-Ai/blob/main/models/Screenshot%202025-04-14%20at%202.39.10%20PM.png)

- **Multilingual Tokenization Preview**  
  ![Tokenizer Compare](https://github.com/Psalms23Wave/Akebulan-Ai/blob/main/models/Screenshot%202025-04-14%20at%202.39.45%20PM.png)

- **Corpus Sample and Alignment**  
  ![Corpus Preview](https://github.com/Psalms23Wave/Akebulan-Ai/blob/main/models/Screenshot%202025-04-14%20at%202.46.00%20PM.png)

- **GitHub Upload Preview**  
  ![Upload](https://github.com/Psalms23Wave/Akebulan-Ai/blob/main/models/Screenshot%202025-04-14%20at%202.47.47%20PM.png)

> Project is ongoing. This model is expected to support translation, summarization, and even coding explanations in Luganda using inherited capabilities of pretrained LLMs.

---

## **React Bible App Development**  

Developed a **self-hosted Bible Archive web app** using **React.js (JSX), JavaScript, and CSS**, enabling seamless scripture search from a **JSON database**.  
- Built a **RESTful API with Node.js and Express**, improving query performance and reducing load times by **40%**.  
- Designed a **2-4 side-by-side grid UI** for scripture, commentary, and dictionary display.  
- Created a **Python 3 script** to preprocess and structure the JSON Bible database, ensuring smooth AWS deployment.  

### **UI Previews**  
- **Single Grid Display (Local Scripture Rendering)**  
  ![Single Grid UI](https://github.com/mathewisrich/Project-Portfolio/blob/main/Show%20no%20grid.png)  

- **Terminal View (Local JSON Database Server with Node.js & Express)**  
  ![Terminal Server Output](https://github.com/mathewisrich/Project-Portfolio/blob/main/Testing%20for%20local%20databasenusing%20node%3Aexpress.png)  

- **Web App UI**  
  ![UI Overview](https://github.com/mathewisrich/Project-Portfolio/blob/main/Ui%20show.png)  

- **Two-Grid UI (Scripture + Commentary + Dictionary)**  
  ![Two Grid UI](https://github.com/mathewisrich/Project-Portfolio/blob/main/Grid%20show.png)  

### **Tech Stack**  
- **Languages:** JavaScript, Python, CSS  
- **Frameworks & Tools:** React.js, Node.js, Express, AWS EC2  
- **Database:** JSON-based scripture and dictionary storage  

---

## **Balanced Life NGO Website Template**  

Developed a **full-stack web app template** using **JavaScript, HTML, and CSS** to help NGOs create and manage their websites effortlessly.  
- Integrated **Firebase for real-time data storage, authentication, and cloud notifications**.  
- Built with **Apache Cordova** for cross-platform development.  
- Developing a **no-code platform for NGOs** using **Webflow Multisite, React.js, and Node.js**.  

### **UI Previews**  
- **Who We Are Section**  
  ![Who We Are UI](https://github.com/mathewisrich/Project-Portfolio/blob/main/Ui%20sample%20who%20we%20are.png)  

- **Login Options (Google, Facebook, Email)**  
  ![Login UI](https://github.com/mathewisrich/Project-Portfolio/blob/main/login%20using%20google%20and%20emal.png)  

- **Firebase Authentication Testing**  
  ![Firebase Authentication](https://github.com/mathewisrich/Project-Portfolio/blob/main/firebase%20authentication.png)  

- **Donation Integration (Mobile Money & PayPal)**  
  ![Donation UI](https://github.com/mathewisrich/Project-Portfolio/blob/main/donateui.png)  
  ![Donation UI 2](https://github.com/mathewisrich/Project-Portfolio/blob/main/donate%20ui.png)  

### **Tech Stack**  
- **Languages:** JavaScript, HTML, CSS  
- **Frameworks & Tools:** React.js, Node.js, Webflow Multisite, Apache Cordova  
- **Database & Authentication:** Firebase  
- **Payment Integration:** Mobile Money, PayPal  

---

## **Samalie Bot – AI Coding Assistant**  

Designed and launched **Samalie Bot**, a generative AI tool that develops software using **connected generative AI models**, including **DALL·E 2, GPT-3, and Whisper v2**.  
- Provides **coding explanations, pseudocode, and UML diagrams** across multiple languages like **Python, JavaScript, and C++**.  
- Built using **Brancher AI** to connect multiple AI models for seamless software development.  
- Currently used by **10+ users** for coding assistance.  

### **UI Previews**  
- **Samalie Bot Interface**  
  ![Samalie Bot UI](https://github.com/mathewisrich/Project-Portfolio/blob/main/Samalie%20tes.png)  

- **User Query Input**  
  ![User Query](https://github.com/mathewisrich/Project-Portfolio/blob/main/samalie%20bot.png)  

- **Generated Code Output**  
  ![Generated Code](https://github.com/mathewisrich/Project-Portfolio/blob/main/samalie%20test.png)  

- **Pseudocode Output**  
  ![Pseudocode Output](https://github.com/mathewisrich/Project-Portfolio/blob/main/samalie%20test%20pusedo.png)  

### **Tech Stack**  
- **AI Models:** DALL·E 2, GPT-3, Whisper v2  
- **Languages:** Python, JavaScript, C++, Rust, Ruby, Go, Kotlin, Java, TypeScript, Swift  
- **Tools:** Brancher AI  

---

### **Connect & Explore**  
📌 **LinkedIn:** [linkedin.com/in/sekanjako-mathew](https://linkedin.com/in/sekanjako-mathew)  
📌 **GitHub Portfolio:** [github.com/mathewisrich/Project-Portfolio](https://github.com/mathewisrich/Project-Portfolio)
