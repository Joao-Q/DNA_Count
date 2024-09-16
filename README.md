# 🧬 DNA Nucleotide Count Web App

This project is a web application built with **Streamlit** that counts the nucleotide composition of a given DNA sequence. You can input any DNA sequence, and the app will output the counts of each nucleotide (A, T, G, C) in the sequence. This project is inspired by a tutorial from **Data Professor**.

## 🌟 Features

- Input DNA sequence via a text box.
- The app processes the DNA sequence to count each nucleotide (Adenine, Thymine, Guanine, Cytosine).
- Outputs include:
  - A dictionary of nucleotide counts.
  - A detailed breakdown in text format.
  - A **pandas DataFrame** displaying the nucleotide counts.
  - A bar chart visualizing the nucleotide distribution using **Altair**.

## 📋 Project Structure
.
  - dna-logo.jpg           # Logo displayed on the app
  - dna_nucleotide_count.py # Main Streamlit app script
  -  README.md              # This README file

## 🛠️ Technologies Used

- **Streamlit**: A Python framework for creating interactive web applications.
- **Pandas**: For handling and manipulating the data.
- **Altair**: A declarative statistical visualization library for Python.
- **Pillow (PIL)**: Used to handle the display of images (e.g., the logo).

## 🔗 Inspiration

This app is based on a tutorial by **Data Professor**, who provides excellent tutorials for building web apps and data science projects. Huge thanks to Data Professor for the guidance and inspiration!

You can explore more of his work on [GitHub](https://github.com/dataprofessor) and [YouTube](https://www.youtube.com/@DataProfessor).

## 🔧 How It Works

The user inputs a DNA sequence into a text area.
The app processes the sequence and counts the occurrences of each nucleotide (A, T, G, C).
Outputs:
The input DNA sequence is displayed.
A dictionary and DataFrame of nucleotide counts are shown.
The nucleotide distribution is visualized in a bar chart using **Altair**.
## 📊 Example of the App in Action

## 📝 Future Enhancements

Add the ability to input multiple sequences and compare the nucleotide counts.
Include additional analysis features, such as calculating GC content or sequence length.
Deploy the app using Streamlit Cloud for easy sharing and access.

## 🤝 Acknowledgments

Special thanks to Data Professor for the original tutorial that inspired this project. If you’re interested in data science tutorials and app development, check out [Data Professor - GitHub](https://github.com/dataprofessor) and [Data Professor YouTube Channel](https://www.youtube.com/@DataProfessor)..
