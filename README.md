# OCR
To run this file you need to have the following python libraries
1. pytesseract (pip install pytesseract)
2. PIL (pip install pillow)
3. os (pip install os-sys)
4. pdf2image (pip install pdf2image)
5. docs (pip install python-docx)
6. Flask (pip install flask}
You also have to download poppler and add the bin folder in the path of system variables and pc variables via environment variables.
You can download poppler from the following link ( https://poppler.freedesktop.org/ )

You also need to have reactjs on your system.

Once you have downloaded all these libraries
1. Run the server.py file in Flask folder first(this will run in local host 5000 by default). To do this simply nevegate to the flask folder and write python server.py in the terminal
2. Navigate to ocr folder via the terminal or open the terminal in that folder and simply write npm install. Once it is installed you will see a folder called node-modules in the ocr folder. Then write npm run start in the terminal and the website will open in local host 3000 on the web browser.
