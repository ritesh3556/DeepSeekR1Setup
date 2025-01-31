# DeepSeekR1Setup
# 🧠 **Ollama & DeepSeek Setup Guide**  

## 🚀 <span style="color:blue">**Setup Guide**</span>  

### 🖥 <span style="color:green">**Windows Installation**</span>  

1. **Download & Install Ollama** from [Ollama Official Site](https://ollama.com/)  
2. **Download & Install Python** from [Python Official Site](https://www.python.org/downloads/)  
3. **QuickStart**: To run Ollama and pull the given model `deepseek-r1:"ModelVersion"`, use the following command:
   ```
   ollama run "deepseek-r1:1.5b" 
   ```
4. **Check if Python is Installed**  
   ```
   Windows
   python --version

   Mac/Linux
   python3 --version
   ```   
### 🌍 <span style="color:teal">Virtual Environment Setup</span>
#### To create a virtual environment, run:
   ```
   python -m venv ollama_env
   or
   python3 -m venv ollama_env
   ```
### 🌍 <span style="color:teal">Activate the Virtual Environment</span>
#### Windows (Command Prompt):
   ```
ollama_env\Scripts\activate
   ```
#### Windows (PowerShell):
   ``` 
.\ollama_env\Scripts\Activate
   ```
#### Mac/Linux:
```
source ollama_env/bin/activate 
```    
### 📦 <span style="color:purple">Install Ollama Python Package</span>
   ```
   pip install ollama
   or
   pip3 install ollama
   ```

### 📝 <span style="color:purple">**Code Example (Use Any IDE)**</span>  
   ```  
   import ollama

# Specify the model name
model_name = "deepseek-r1:1.5b"

# Example conversation
response = ollama.chat(model=model_name, messages=[
    {
        "role": "user",
        "content": "Hello, write message"
    }
])

# Output the response
print(response["message"]["content"])

  ```
### 🖥 <span style="color:purple">**macOS/Linux Installation**</span>
The installation process for macOS/Linux is similar to Windows, with the only difference being the commands to check Python version and virtual environment activation.
### **Key Features of This README:**  
✅ **Virtual Environment Setup** (For isolated package management)  
✅ **Step-by-Step Instructions** (For both Windows & Mac/Linux)  
✅ **Command-line Installation Commands** (`pip install`, `venv activation`)  
✅ **Python Code Example** (To use Ollama & DeepSeek) 

### 📜 <span style="color:purple">**Disclaimer**</span>
This guide is provided for educational and learning purposes only. It is intended to help users set up and use Ollama and DeepSeek as part of their development journey. Please refer to the official documentation of [Ollama](https://ollama.com/)   and [DeepSeek](https://deepseek.com/) for up-to-date and official support.


## 🙌 **Contributors**
- **Ritesh** - Created the guide
- ----



