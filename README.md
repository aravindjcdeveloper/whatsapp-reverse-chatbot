# whatsapp-reverse-chatbot
REPO UNDER CONSTRUCTION 

A Hobby Project - This CLI Application will automatically send whatever someone sends back to them in a reversed order. Example: If they send you "Hai", it will reply them with "iaH". This can be used as a Base to develop some intellignet Chatbots. Project is made with Python, OpenCV, pytesser-ocr, pyautogui. 

NOTES:      
1. As far as I know, Python modules to interact with WhatsApp became obsolete due to updated security features of WhatsApp.     2. Here, I used Image Processing techniques to use WhatsApp.
3. On a computer, go to web.whatsapp.com on any browser and sync your WhatsApp accuont.
4. Run the CLI application (main.py) 

THEORY USED:
1. The WhatsApp Web Inteface has a Smiley Button on the left side of the Texting Area and a Microphone or a Send Button on the right side of the Texting Area.
2. We first detect the center of the Texting Area by detecting the side Button's locations. We then move the mouse pointer to the place and click it.
3. We have got the focus of the Texting Area.

DOCUMENTATION UNDER CONSTRUCTION
