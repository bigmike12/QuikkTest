# QuikkTest
# AI-Powered Test Generator for JavaScript

## 🚀 Overview
An open-source AI-powered tool that helps engineers write **unit and integration tests** for JavaScript code automatically. The goal is to generate **high-quality Jest/Mocha tests** using AI, reducing the time spent on manual test writing.

## ✨ Features
- 🔹 **AI-generated Jest/Mocha tests** for JavaScript functions
- 🔹 **Supports unit and integration tests**
- 🔹 **CLI tool (`gen-tests myfile.js`)** for local test generation
- 🔹 **VS Code extension** for real-time test suggestions
- 🔹 **API service** for test generation
- 🔹 **Test coverage insights** to detect missing test cases

## 🏗️ Project Structure
```
📦 ai-test-gen  
 ┣ 📂 model-training  # AI model fine-tuning code  
 ┣ 📂 api  # Backend API for generating tests  
 ┣ 📂 cli  # CLI tool for generating tests locally  
 ┣ 📂 vscode-extension  # VS Code extension for live test suggestions  
 ┣ 📂 datasets  # JavaScript code + test dataset  
 ┣ 📜 README.md  # Project overview and setup guide  
 ┣ 📜 CONTRIBUTING.md  # How to contribute  
 ┣ 📜 LICENSE  # Open-source license  
```

## 🛠️ Installation
### 1️⃣ Clone the repository
```sh
git clone https://github.com/bigmike12/QuikkTest
cd quikktest
```
### 2️⃣ Install dependencies
```sh
npm install  # For CLI & VS Code extension
pip install -r requirements.txt  # For AI model training & API
```
### 3️⃣ Run the CLI tool
```sh
node cli/index.js myfile.js  # Generates Jest tests for myfile.js
```
### 4️⃣ Start the API
```sh
cd api
python app.py  # Runs the AI-powered test generation API
```

## 📌 Roadmap
- ✅ Train an AI model on JavaScript test generation
- ✅ Develop a CLI tool for local test generation
- 🔄 Build a VS Code extension for real-time suggestions
- 🔄 Implement API for test generation
- 🔄 Add CI/CD for automated deployments

## 🤝 Contributing
Contributions are welcome! Please check the [CONTRIBUTING.md](CONTRIBUTING.md) file for guidelines.

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
🚀 **Let's revolutionize test automation with AI!**

