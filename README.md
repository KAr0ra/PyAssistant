<p align="center">
  <a href="" rel="noopener">
 <img src="https://i.imgur.com/KAOnnUp.png" alt="Project logo"></a>
</p>

<div align="center">

  [![Status](https://img.shields.io/badge/status-active-success.svg)]() 
  [![GitHub Issues](https://img.shields.io/github/issues/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/issues)
  [![GitHub Pull Requests](https://img.shields.io/github/issues-pr/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/pulls)
  [![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---
## 📝 Table of Contents
- [About](#about)
- [Getting Started](#getting_started)
- [Usage](#usage)
- [Built Using](#built_using)
- [Authors](#authors)

## 🧐 About <a name = "about"></a>
PyAssistant is a vitural desktop assistant that levarges face recognition for authentication and speech recognition to interpret commands via built-in webcam/mic. PyAssistant had five functions it can perform out of box, "Play Music", "Open Website","Joke of the day","Fact of the day", and "Send Text". PyAssistant can be customized to your needs, all you need is a basic understanding of python!

## 🏁 Getting Started <a name = "getting_started"></a>

### Prerequisites
Please install all prerequisites to ensure PyAssistant will run on your system.

```
Python3
Twilio 
Speech_recognition
Requests
OpenCV
Numpy
A picture of the user face
```
Please ensure that your system has a webcam with mic built-in or by USB

### Installing

```
1. Install all Prerequisites software and hardware
2.Open PyAssistant script
3.Script is noted where the user will have to update code, the updates will be file path to users face picture(for auth), and twilio account information. 
4. Run PyAssistant
```

## 🎈 Usage <a name="usage"></a>
Once you run PyAssistant it will open a web cam stream to compare the incoming face to the stored picture, if the auth passes, PyAssistant will alert you speak a command, for example you can say " tell me a joke, " PyAssistant will then echo back the joke. 


## ⛏️ Built Using <a name = "built_using"></a>
- [Python 3](https://www.python.org/downloads/) - Python 3
- [Speech Recognition](https://pypi.org/project/SpeechRecognition/) - Speech Recognition
- [Face Recognition](https://github.com/ageitgey/face_recognition) - Face Recognition
- [Twilio](https://pypi.org/project/twilio/) - Twilio REST API (for texting)
- [HTTP Requests](https://pypi.org/project/requests/) - HTTP Requests(get requests for joke and fact api)

## ✍️ Authors <a name = "authors"></a>
- [@KAr0ra](https://github.com/KAr0ra) 



