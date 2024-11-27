# OneClick - Install tools instantly with a one click
[![Version](https://img.shields.io/badge/Version-1.0.0-blue.svg)](https://github.com/hackinter/Archer/releases)
[![GitHub](https://img.shields.io/badge/GITHUB-HACKINTER-red.svg)](https://github.com/hackinter)

OneClick is a command-line tool designed to simplify the installation of various security tools. It automates the process of installing multiple tools from a JSON configuration file, ensuring you have all the essential tools required for bug hunting and other security tasks. 🔧🛠️

## Features 🌟

- **Install Top 20 Tools**: Installs the most recommended and frequently used tools for security professionals. 🏆
- **Install All Tools**: Installs all tools listed in the JSON configuration file, including top tools and additional utilities. 📥
- **Install Selected Tools**: Installs specific tools by name, either from the top 20 or from the complete list. 🔍
- **List All Available Tools**: Displays all available tools that can be installed, from both the top 20 and the full list. 📋
- **Custom Banner**: A custom banner is displayed when the script is run to provide user feedback. 🎨

## Usage 📝

### Basic Commands
![OneClick](https://github.com/hackinter/Template/blob/main/Screenshot%20from%202024-11-27%2017-55-33.png)

1. **Install Top 20 Bug Hunting Tools**  
   Run the following command to install the top 20 bug hunting tools:

 

   ```bash
   ./oneclick -i top-bughunt-tools
   ```

3. **Install a Single Tool**  
   To install a specific tool, run the following command:
   ```bash
   ./oneclick -i <toolname>
   ```
   Example:
   ```bash
   ./oneclick -i sublist3r
   ```

4. **Install All Tools**  
   To install all available tools listed in the JSON file:
   ```bash
   ./oneclick -i all
   ```

5. **List All Tools**  
   To view the list of all available tools:
   ```bash
   ./oneclick -i list
   ```

6. **Install Multiple Tools**  
   To install multiple tools at once, use the following syntax:
   ```bash
   ./oneclick -b <toolname1>,<toolname2>,<toolname3>
   ```
   Example:
   ```bash
   ./oneclick -b sublist3r,nuclei,httpx
   ```

### Script Options ⚙️

- `-i <argument>`  
  Installs the specified tools:
  - `top-bughunt-tools`: Install top 20 bug hunting tools. 🏆
  - `all`: Install all tools. 📥
  - `list`: List all available tools. 📋
  - `<toolname>`: Install a specific tool by name. 🔍
  
- `-b <toolnames>`  
  Installs multiple tools separated by commas. 🔄

- `-l`  
  Lists all available tools. 📜

### Example Output 💬

When you run the script with the `-i` option, it will show output like:
```
[+] Installing Top 20 Tools...
Cloning into 'sublist3r'...
Cloning into 'nuclei'...
...
[+] All Top 20 Tools Installed Successfully! ✅
```

### Banner 🎉

The script displays a banner to the user upon execution:

```

╔═╗╔╗╔╔═╗  ╔═╗╦  ╦╔═╗╦╔═
║ ║║║║║╣───║  ║  ║║  ╠╩╗
╚═╝╝╚╝╚═╝  ╚═╝╩═╝╩╚═╝╩ ╩
..................[V1.0][@hackinter] 🎨
```

### Installation Instructions ⚡

1. **Clone the Repository**  
   Clone the repository to your local machine:
   ```bash
   git clone https://github.com/hackinter/oneclick.git
   ```

2. **Make the Script Executable**  
   Grant execution permissions to the script:
   ```bash
   chmod +x oneclick
   ```

3. **Run the Script**  
   Now you can use the script to install tools as per your requirements:
   ```bash
   ./oneclick -i <argument>
   ```

### Dependencies 🛠️

- `jq`: A lightweight and flexible command-line JSON processor. 💻
- `git`: For cloning the repositories. 🧑‍💻

Here is the updated section for the `README.md` with similar formatting and tone for **OneClick**:

---

## License 📜
This project is licensed under the MIT License. See the [LICENSE](https://github.com/hackinter/oneclick/blob/main/LICENSE) file for more details.

## Contributing 🤝
We welcome contributions! If you would like to contribute, feel free to fork the repository and submit a pull request. If you encounter any bugs or have suggestions, please open an issue.

## Contact 📧
For any queries or issues, feel free to reach out to us:

[![Email](https://img.shields.io/badge/HACKINTER-MAIL-red.svg)](mailto:ceh.ec.counselor147@gmail.com)  
[![Telegram](https://img.shields.io/badge/HACKINTER-T.ME-blue.svg)](https://t.me/chat_with_hackinter_bot)  
[![Twitter](https://img.shields.io/badge/HACKINTER-TWITTER-black.svg)](https://x.com/_anonix_z)


---
> "Automation makes it easy, but ethical practice makes it meaningful!" - Hackinter

## Disclaimer ⚠️

The tool **OneClick** is designed for educational purposes and legitimate security testing only. **This tool is strictly prohibited for illegal activities, unauthorized access, or malicious intent.**

By using this tool, you agree to comply with all local laws and regulations regarding cybersecurity, and you are solely responsible for your actions. The creators of this tool do not take any responsibility for any misuse or damage caused by the tool.

