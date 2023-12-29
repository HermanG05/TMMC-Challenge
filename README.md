# TMMC-Design-Challenge

# Purpose
The goal of this deisgn challenge was to develop and train a machine learning model that would detect black-sealing stickers on toyota car parts. The model would have to pass various tests, including those on different coloured surfaces.

# Approach
Our team captured 800 photographs showcasing black-sealing stickers on various Toyota car parts, ensuring diverse angles and lighting conditions. These images were then annotated using ROBOFLOW, a software that categorized each picture into one of six groups. Before incorporating them into our retraining dataset, we allowed the model to annotate the images. This resulted in us achieving over a 95% accuracy in identifying holes against different background colors like red, white, and aluminum. However, discerning stickers on a black background posed challenges. To address this, we aimed to rectify the issue by comparing the hue of the sticker with that of the background.

