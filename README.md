# Tabular-OCR

JPG and PDF files containing tabulated handwritten data were processed with Python’s OpenCV library using various preprocessing techniques such as Gaussian smoothing and threshing methods. Using Google’s Vision API individual cell values are then passed to a pre-trained machine learning model that returns the closest word match and an accompanying accuracy rating. Finally, each result is stored in a dataframe matching the table structure from the JPG/PDF.
