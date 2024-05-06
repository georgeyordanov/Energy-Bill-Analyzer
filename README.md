# Energy-Bill-Analyzer

If you've ever wanted to deeper understand your energy bill and find ways to help reduce your cost, use this analyzer to help! 

The Energy Bill Analyzer is a Python-based tool that extracts text from the uploaded file using Optical Character Recognition (OCR) to produce personalized advice to the user.

Features:
- OCR: Extracts text from digital/scanned files
- OpenAI Models: GPT-4 to help with generating a response based on the context Also, Text-to-Speech for an audible output for the initial advice.
- Streamlit App: Incorporation of a Python interface to create & display the application

How It Works:
- Required Python Packages: ('streamlit', 'openai', 'PyMuPDF', 'pytesseract')
- Upload Your Bill: Upload a digital copy of their energy bill (PDF format).
- Text Extraction: The tool extracts text from the uploaded bill using PyMuPDF & pytesseract.
- AI-Powered Analysis: The extracted text is processed by OpenAI's GPT-4 model to generate customized advice aimed at reducing energy costs.
- Results Displayed: The analyzed data is presented within the app, along with information on key points.
- Follow-Up Questions: After initial advice, one can ask follow-up questions regarding their bill, & the analyzer will provide GPT-4 model responses.
