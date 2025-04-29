# Bajaj - Lab Test OCR API
This project provides an OCR-based web API that extracts structured lab test data from images of medical lab reports. It uses FastAPI for the backend and Tesseract OCR for text recognition.

What This Project Does

- Accepts image uploads of lab reports (e.g., JPEG, PNG).
- Uses Tesseract OCR to extract text from the image.
- Parses lab test results including:
  - Test name
  - Test value
  - Reference range
  - Unit
  - Whether the result is out of range
- Returns structured JSON data from the image.
- Offers a simple web interface for uploading images.
- Also supports batch processing of multiple images from a folder.
- Automatically removes temporary uploaded files after processing.
