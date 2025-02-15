# 🚀 AI-Powered Automation Assistant

Welcome to the **AI-Powered Automation Assistant**! This intelligent system utilizes cutting-edge language models to execute a range of automation tasks efficiently.

---

## 🌟 Key Features
- 🤖 **Smart Task Interpretation**: Uses advanced NLP for precise command execution.
- 🔒 **Secure Data Handling**: Ensures safe file operations and sensitive data protection.
- ⚡ **Multi-Task Execution**: Seamlessly handles multiple automation requests.
- 🌐 **API Integration**: Enables robust task execution through external API support.

---

## 📋 Requirements
Ensure you have the following installed before running the application:
- **Docker**: Required for containerized deployment.
- **AI Proxy Authentication Token**: Needed to access LLM functionalities.

---

## ⚙️ Installation & Usage

### 1. Clone the Repository
```sh
git clone https://github.com/S41lesh/LLM_TASK_TDS.git
cd LLM_TASK_TDS
```

### 2. Install Dependencies
```sh
pip install -r requirements.txt
```

### 3. Configure Environment Variables
Create a `.env` file in the project's root directory:
```sh
echo "AIPROXY_TOKEN=your_token_here" > .env
```

### 4. Run the Application Locally
```sh
python run.py
```

### 5. Deploy Using Docker

#### Build the Docker Image
```sh
docker build -t "Your_Image_Name" .
```

#### Run the Container
```sh
docker run --env-file .env -p 8000:8000 "Your_Image_Name"
```

---

Enjoy automating your tasks with ease! 🚀

