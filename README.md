# 👉 [简体中文文档](README-zh_CN.md)
With Quick Actions, you can send the screenshot image to Tencent Yiting's API or the text extracted from the screenshot to Tencent Yiting's API or ChatGPT's API, enabling AI to understand and read the content on the screen or in the picture. 

Steps for Operation:
1. https://bailian.console.aliyun.com/?apiKey=1#/api-key (Aliyun Bailian API key retrieval address using Tongyi Qianwen) https://bigmodel.cn/usercenter/proj-mgmt/apikeys
(Here is the link to obtain the API key for ChatGLM.)
After obtaining the key, fill it into the list in the order it was given, otherwise the program will not run properly.
 
2. Select the model to be called, default is 3, if you want to use image recognition function, please select 2 (using two models from Alibaba, qwen-vl-plus-latest and qwen-plus-1127, mainly with free token quota, which can be replaced with other models from Alibaba (with vl for image understanding model, without vl for general large model)).

3. The model call for option 1 or 3 can also use image recognition functions, but since it is by extracting text from the screenshot and sending it to the large model, it cannot recognize pure images.

4. Display the output results page, with the cancel button for closing the shortcut instruction and the complete button for continuing the chat. You can also ask more detailed questions about the picture (and the model will be automatically connected to the internet by default, if needed, you can turn it off manually)

5. You can add shortcuts to the Control Center, and add a shortcut button for Shortcuts in the Control Center. Choose Smart Scan, and you can perform image recognition on the current page by clicking the button in the Control Center.

6. Type any text that starts with "Recognize" or "New Chat" to restart the chat. Type "Exit Chat" to exit the chat.

7. Other parameters can be set as desired.

8. During the development process, it was realized that the image recognition function of the large model could help visually impaired individuals see the media and picture content on their phones, so a switch for the visually impaired mode was added. The model will provide a more detailed description of the picture content and give a vibration prompt before outputting the result, which can be turned on if needed.

This shortcut is based on the project by @YueYangLeyang, which has been improved from the original project. The original project address is https://github.com/Yue-Yang/ChatGPT-Siri. Please support the original project author.
