## 🧥 Invisibility Cloak using OpenCV (Harry Potter Style)  
This project creates a magical invisibility cloak effect using Python and OpenCV — inspired by Harry Potter! When you wear a cloak of a specific color (like yellow), the program detects that color and replaces it with the background, making you appear invisible on screen.

### 🚀 How It Works  
- The program first captures a still frame of the background (without you in it).  
- Then, it uses color detection in HSV color space to identify the cloak.  
- The pixels of the cloak are replaced by the saved background, creating the illusion of invisibility.

### 🎮 How to Use  
- Wear a cloak of the target color (e.g., yellow).

- Run the script:  
```python invisibilityClock.py```

- Quickly step out of the webcam view for the first 5 seconds — the program will capture the empty background.  
- Step back in wearing the cloak — only the cloak will disappear!  

### 🧩 Requirements  
Python 3  
OpenCV (opencv-python)  
NumPy

Install dependencies with:  
```pip install opencv-python numpy```
