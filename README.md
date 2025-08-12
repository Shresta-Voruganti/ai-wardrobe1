# AI Wardrobe
This project aims to provide an intelligent solution for managing your wardrobe and generating outfits based on the clothes you own. By leveraging computer vision and machine learning, the AI Wardrobe system can analyze uploaded clothing items, identify their characteristics, and store them in a digital wardrobe. It also utilizes an AI model to generate fashionable outfits using the available clothes.

## Features
* **Clothing Detection**: The AI Wardrobe system uses computer vision techniques to identify various types of clothing items from images or uploaded photos.
* **Digital Wardrobe**: Once a clothing item is detected, it is saved in the digital wardrobe, which serves as a centralized inventory of your clothes.
* **Outfit Generation**: By leveraging an AI model, the AI Wardrobe system can generate stylish outfits based on the available clothes in your digital wardrobe.

## Jupyter notebooks
* **Item classification**: [Link](https://colab.research.google.com/drive/1scuubYOVsM3UjpQZmqFQbjK7sYx0bpd9?usp=sharing)
*  **Siamese network data preparation**: [Link](https://colab.research.google.com/drive/1Nza8JqagDwdiwqufdjeJyX9SbbnQIzlD?usp=sharing)
*  **Siamese network**: [Link](https://colab.research.google.com/drive/1t1djpwPXnADrj-8Mw20ZonJELQSC5qYq?usp=sharing)

## Usage

To set up the AI Wardrobe system locally, follow these steps:

1. Download the [models](https://drive.google.com/file/d/1iR8BF3As2roXZdprnVHAXmc3TuRHzq18/view?usp=share_link) and move to the root directory

2. Clone the repository:
```
git clone https://github.com/your-username/ai-wardrobe1.git
```
3. Install the required dependencies. You may use a virtual environment to keep your dependencies isolated:
```
cd ai-wardrobe1
npm i
cd ./server
pip install -r requirements.txt
```
4. Launch the application:
```
python server.py
cd ..
npm start
```
5. Access the AI Wardrobe system by visiting http://localhost:3000 in your web browser.

## Demo

![ai-wardrobe-demo](https://github.com/user-attachments/assets/89679dca-fb7e-42f7-b54f-28d0a2baac1f)



## Contributing
Contributions to the AI Wardrobe project are welcome! If you have any ideas, improvements, or bug fixes, feel free to submit a pull request. Please ensure that your contributions adhere to the project's coding standards and guidelines.
