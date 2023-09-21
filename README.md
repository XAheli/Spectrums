# Spectrums - Color Palette Generator

## Introduction
Spectrums is a Python utility that allows you to create beautiful color palettes based on an input image. This project was created as a practice exercise to gain a deeper understanding of Gaussian Mixture Models (GMMs) and color analysis. It uses GMMs to cluster colors from an image and presents them in a visually appealing palette.

![Spectrums Palette Example](https://github.com/XAheli/Spectrums/blob/main/Spectrums%20photo-to-palette.png)

## Features
- Generate color palettes from input images.
- Utilizes Gaussian Mixture Models (GMMs) for color clustering.
- Sorts colors based on a custom ranking that considers hue, saturation, and perceived brightness.
- Provides a graphical representation of the generated color palette.

![K Means vs GMMs]([https://github.com/XAheli/Spectrums/blob/main/Spectrums%20photo-to-palette.png](https://github.com/XAheli/Spectrums/blob/main/k-means%2Band%2BGaussian%2BMixture%2BModel%2B(GMM)..jpg))

## Prerequisites
- Python 3.9
- Required Python libraries: `numpy`, `scikit-learn`, `Pillow`, `matplotlib`

## Installation
1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/XAheli/spectrums.git
   cd spectrums

## Usage
- Ensure you have an image (e.g., IMG_1969 copy.jpg) that you want to create a color palette from. You can replace this file with your own image.
- Open the spectrums.py script in a text editor and modify the image_path variable to specify the path to your image.
- Adjust the num_colors variable to set the number of colors you want in the palette.
- Run the script:
  
  ```bash
   python spectrums.py

- The script will generate a graphical representation of the color palette and display it using Matplotlib. You can adjust the figure size and layout in the script as needed.
- The script will also print the color labels and their RGB values to the console.

## Customization
- You can customize the script further by adjusting the coefficients in the perceived_brightness function to change how brightness is calculated.
- Modify the ranking in the hsp_rank function to influence the sorting of colors based on your preferences.

## License
This project is licensed under the [Apache License 2.0](LICENSE) - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- The custom color ranking algorithm in this project is inspired by the work of Darel Rex Finley ([source](http://alienryderflex.com/hsp.html)).

Enjoy creating beautiful color palettes with Spectrums! If you find this project useful, don't forget to give it a star ⭐!
