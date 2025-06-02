# 📘 60 Days of Learning – Gaurav Bhattarai

Welcome to my 60 Days of Learning challenge journey, where I document daily progress on tech topics, coding, and math!

Organized by [Leapfrog Technology](https://lftechnology.com/), this challenge helps me build strong foundations and share my learning publicly.

---

## 📅 Challenge Duration

**Start Date:** June 1, 2025  
**End Date:** July 30, 2025  

## 🔖 Hashtags & Social

Please follow my journey on Twitter: [@bhattarai2727](https://twitter.com/bhattarai2727)  
Hashtags I use daily:  
`#LSPPDay1`, `#LSPPDay2`, ..., `#60DaysOfLearning2025`, `#LearningWithLeapfrog`  
Tagging: `@lftechnology`

---

## 🚀 Daily Logs

### ✅ Day 1 – Python Core Revision

📌 **Topic:** Python Fundamentals  
📚 **Summary:**  
- Data types: `int`, `float`, `str`, `list`, `dict`  
- Operators, loops, and conditions  
- Functions & common string/list methods  

🔗 **Notebook:** [Google Colab – Day 1](https://shorturl.at/CG8mo)  

🧵 **Tweet:**  
> Gaurav Bhattarai @bhattarai2727 · Jun 1  
> Day 1 – Python Core Revision  
> Revised Python fundamentals:  
> Data types (int, float, str, list, dict)  
> Operators, loops, and conditions  
> Functions & common string/list methods  
> #LSPPDay1 #60DaysOfLearning2025 #LearningWithLeapfrog @lftechnology

---

### ✅ Day 2 – Linear Algebra Basics

📌 **Topic:** Linear Algebra Foundations  
📚 **Summary:**  
- Scalars, Vectors, and Matrices  
- Operations: Dot product, Matrix multiplication, Transpose  
- Recommended book: *Introduction to Linear Algebra* by Gilbert Strang  
- Watched MIT OCW lectures to strengthen understanding  

🔗 **Notebook:** [Google Colab – Day 2](https://shorturl.at/rUUeb)  

🧵 **Tweet:** *(Update your tweet link here once tweeted)*  
📌 Hashtags: `#LSPPDay2 #60DaysOfLearning2025 #LearningWithLeapfrog`

---

## 🧑‍💻 Sample Code Snippets for Day 2

```python
# Dot product function (manual)
def dot_product(vec1, vec2):
    return sum(x * y for x, y in zip(vec1, vec2))

# Matrix multiplication function (manual)
def matrix_multiply(A, B):
    rows_A, cols_A = len(A), len(A[0])
    rows_B, cols_B = len(B), len(B[0])
    if cols_A != rows_B:
        raise ValueError("Invalid matrix dimensions")
    result = []
    for i in range(rows_A):
        row = []
        for j in range(cols_B):
            cell = sum(A[i][k] * B[k][j] for k in range(cols_A))
            row.append(cell)
        result.append(row)
    return result


---

## 📈 Goal of This Challenge

- Strengthen my foundation in **Python, Math, DS & AI**
- Build a consistent daily learning habit
- Share knowledge publicly and inspire others to learn

---

## 🙌 Shoutout

Thanks to **@lftechnology** for organizing this learning challenge and providing a great platform for tech enthusiasts in Nepal!

---

## 📄 License

This repository and its contents are shared for educational purposes.  
All notebooks, summaries, and learning materials are under the [MIT License](https://choosealicense.com/licenses/mit/).

