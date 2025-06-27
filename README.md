# cnn-penguin-classifier
# 🐧 Penguin Species Classification using CNN

This project uses a Convolutional Neural Network (CNN) to classify different species of penguins based on physical characteristics like bill length, depth, flipper length, body mass, island, and sex. It is inspired by the classic Iris dataset problem and is built using the [Palmer Penguins dataset](https://github.com/allisonhorst/palmerpenguins).

## 📊 Dataset

- **Source**: Seaborn’s built-in version of the [Palmer Penguins dataset](https://github.com/mwaskom/seaborn-data/blob/master/penguins.csv)
- **Features Used**:
  - Bill Length (mm)
  - Bill Depth (mm)
  - Flipper Length (mm)
  - Body Mass (g)
  - Sex (encoded)
  - Island (encoded)
- **Target**: Penguin Species (`Adelie`, `Chinstrap`, `Gentoo`)

## 🧠 Model Architecture

The input features were reshaped into a `2x3x1` format to simulate an image input for CNN. Here's the architecture:

