# CSS for Kaggle Notebook
This repository is used for customizing Kaggle Notebook.

Original CSS code was Created By:
<br>
[![kaggle_acc](https://img.shields.io/badge/Sergey%20Saharovskiy-0057e7?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/sergiosaharovskiy)

ChatGPT Color Scheme Reference:
<br>
[![medium](https://img.shields.io/badge/Transforming_My_VSCode_with_a_ChatGPT_Inspired_Theme-by_Sohyun_Park-000000?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@sohyuniverse/transforming-my-vscode-with-a-chatgpt-inspired-theme-8a9fa8f8d8b4)

# How to Use
```python
!wget https://raw.githubusercontent.com/drmwnrafi/kaggle_css_styling/main/CSS.css -q -O CSS.css  

from IPython.core.display import HTML
with open('./CSS.css', 'r') as file:
  custom_css = file.read()

HTML(custom_css)
```
Copy the code snippet to a Kaggle Notebook cell.
