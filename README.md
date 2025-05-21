# 📈 Simple Linear Regression in Python (from Scratch) 

This is a simple implementation of **Linear Regression** in Python using **NumPy** and **Matplotlib** without relying on libraries like `scikit-learn`. It demonstrates how to estimate the coefficients for a simple linear regression model and visualize the results.

---

## 📋 Features

* Compute regression coefficients (slope and intercept) using the **Least Squares Method**.
* Plot the data points along with the fitted regression line.
* Clean, beginner-friendly implementation with comments for easy understanding.

---

## 🛠️ Requirements

* Python 3.x
* NumPy
* Matplotlib

You can install the dependencies using:

```bash
pip install numpy matplotlib
```

---

## 📌 How It Works

1. **Estimate Coefficients:**
   Calculates the slope (`b_1`) and intercept (`b_0`) using the formula:

   * ![equations](https://latex.codecogs.com/png.latex?b_1%20%3D%20%5Cfrac%7B%5CSum%20%28x_i-y_i%29%28x_i-%5Cbar%7Bx%7D%29%7D%7B%5CSum%20%28x_i-%5Cbar%7Bx%7D%29%5E2%7D)
   * ![equations](https://latex.codecogs.com/png.latex?b_0%20%3D%20%5Cbar%7By%7D%20-%20b_1%20%5Cbar%7Bx%7D)

2. **Plot the Regression Line:**
   Visualizes the original data points and the regression line for a clear understanding of the model fit.

---

## 🚀 How to Run

Clone or download this repository and run:

```bash
python linear_regression.py
```

You’ll see:

* The estimated coefficients printed to the console.
* A scatter plot of the data points with the fitted regression line.

---

## 📊 Example Output

```text
Estimated coefficients:
b_0 = 1.48 
b_1 = 1.17
```

![sample plot](https://via.placeholder.com/500x300?text=Regression+Plot)
*(You can replace this with your actual plot if sharing online)*

---

## 📚 Concepts Covered

* Simple Linear Regression
* Least Squares Estimation
* Data Visualization using Matplotlib
* NumPy for numerical operations

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
