My code creates a system to detect fake news by extracting text from an image. The user selects an image from the desktop and I process it using OpenCV and Tesseract. First, I convert the image to grayscale, then blur it and perform edge detection. After that, I extract the text with OCR and print it on the screen.


![SAMPLE NEWS](https://github.com/user-attachments/assets/018382d5-2097-415a-9580-c8fcd963732d)


I subject the extracted text to sentiment analysis with a transformer-based model, which determines whether the text is positive or negative. I vectorize the texts with the TF-IDF method and determine the topic distribution with the LDA model. I calculate the similarity between the two texts using Cosine Similarity. I train a fake news detection model with the SGDClassifier algorithm and calculate the accuracy rate of the model as 97.76%.
