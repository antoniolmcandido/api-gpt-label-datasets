# api-gpt-label-datasets

🚀 **Automatically Label Datasets with OpenAI GPT API** 🚀

Welcome to the **api-gpt-label-datasets** repository! Here, you will find an amazing project that uses the powerful OpenAI GPT API to automatically label datasets. This project is perfect for those who want to automate sentiment analysis and other text labeling tasks.

## 📚 Overview

This project was developed to facilitate the labeling of large volumes of text data, using OpenAI's artificial intelligence. With it, you can:

-   📊 **Analyze Sentiments**: Classify texts based on sentiment, from very negative (1) to very positive (7).
-   ⚡ **Automate Processes**: Save time and effort by automating data labeling.

-   🌐 **Integrate with Ease**: Use the OpenAI API in a simple and efficient way.

## 🛠️ Project Structure

```plaintext
data/
  your_dataset.z
.env
.env.example
.gitignore
LICENSE
notebook.ipynb
README.md
requirements.txt
```

-   **.env**: Configuration file with API keys and dataset URLs.
-   **.gitignore**: File to ignore sensitive and data files.
-   **data/**: Directory where labeled datasets are stored.
-   **notebook.ipynb**: Jupyter Notebook with the code for labeling and analyzing data.
-   **README.md**: This file you are reading now!

## 🚀 How to Get Started

1. **Clone the Repository**:

```
git clone https://github.com/antoniolmcandido/api-gpt-label-datasets.git
cd api-gpt-label-datasets
```

2. **Install Dependencies**:

```
pip install -r requirements.txt
```

3. **Set Up the Environment**:

Rename the `.env.example` file to `.env` and add your OpenAI API keys and dataset URL.

4. **Run the Notebook**:

Open the `notebook.ipynb` in Jupyter Notebook or JupyterLab and run the cells to automatically label your data.

## 📊 Example Output

Here's an example of how the data is labeled:

| Index | Text                                                                                                             | Sentiment |
| ----- | ---------------------------------------------------------------------------------------------------------------- | --------- |
| 0     | Interesting! How often we say those things to others without really understanding what we are saying. Excellent! | 6.5       |
| 1     | What is "Algebra as a Math Game" or are you just saying you create games that incorporate algebra?               | 4.0       |
| 2     | I like the idea of ​​my kids principal who says "Smart doesn't mean easy, smart means working hard".             | 5.5       |

## 🌟 Highlights

-   **Accuracy**: Uses advanced OpenAI models to ensure high accuracy in labeling.
-   **Ease of Use**: Intuitive interface and easy to set up.
-   **Scalability**: Capable of handling large volumes of data.

## 🤝 Contributions

Contributions are welcome! Feel free to open issues and pull requests.

## 📄 License

This project is licensed under the MIT license. See the LICENSE file for more details.

---

💡 **Tip**: Don't forget to review and adjust the .env settings to make sure everything works perfectly!

Enjoy the project and happy tagging! 🎉
