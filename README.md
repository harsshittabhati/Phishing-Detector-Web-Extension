# Phishing Detection Web Extension 🚨
### Preview:
- It analyzes the website that user will visit.  
- Helps you to stay away from scams and data breaches. 
- Alert if there is any possible threat.

## What’s This About?

This Phishing Detection Web Extension is your online bodyguard, keeping you safe from phishing attacks while you browse the web. It’s smart, lightweight, and always watching your back—no more worrying about clicking on suspicious links or fake login pages!

## Why You’ll Love It

- _Easy to Use:_ Simple, clean interface that anyone can navigate.
- _Fast & Lightweight:_ Doesn’t slow down your browser.
- _Multi-Browser Support:_ Works on Chrome and Firefox (with more on the way!).
- _Manual:_ scan website you visit and find vulnerable.
- Also shows the Domain name and IPv4 of the website.

## Getting Started

### Setting Backend:

1. Open the project folder in Visual studio code or any other platform.
2. In the detect_Backend folder you will find a manage.py file.
3. Open it and run it.
4. If any error occurs, it will definitely for asking for some python libraries to be installed.
5. Use the following code or just copy it:

```
> pip install numpy
> pip install pandas
> pip install matplotlib
> pip install seaborn
> pip install scikit-learn
> pip install requests
> pip install flask
> pip install django
> pip install opencv-python
> pip install opencv-contrib-python  # For extra features
> pip install tensorflow
> pip install beautifulsoup4
> pip install torch torchvision torchaudio
> pip install sqlalchemy
> pip install pytest

```
6. After this, to start the backend use the following commands:
```
> cd detector_Backend
> ls
> cd detectphising
> ls
> python manage.py runserver
```

### Setting Frontend:

_On Chrome:_

1. Download this project or clone it: git clone [https://github.com/yourusername/phishing-detection-extension.git ](url).
2. Open Chrome and go to [chrome://extensions/](url).
3. Turn on Developer Mode in the top-right corner.
4. Click Load unpacked and select the project folder.
5. Boom! The extension is now live in your toolbar.

_On Firefox:_

1. Open Firefox and go to [about:debugging#/runtime/this-firefox](url).
2. Click Load Temporary Add-on.
3. Choose the detect_Frontend file from the project folder.
4. Done! The extension is now running.

## How to Use

1. Once installed, you’ll see the extension icon in your browser’s toolbar.
 - 🟢 Green: All good! Website is safe to visit.
 - 🔴 Red: Danger! It’s a phishing site; back away.
2. Click the icon anytime for more details or to tweak settings.
