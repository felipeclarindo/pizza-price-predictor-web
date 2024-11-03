🌍 [Leia em Português](README.pt-BR.md)

# Pizza Price Predictor

This project is a machine learning application that estimates the price of a pizza based on the diameter in centimeters. Using `scikit-learn` and ``Streamlit`, it offers a user-friendly and intuitive interface to view price predictions in real time.

## Features

- `Diameter input` - Allows user to insert the diameter of the pizza in centimeters.
- `Price Prediction` - Based on a linear regression model, the application estimates the price of the pizza and displays the estimated value.
- `Intuitive Interface` - Developed with `Streamlit`, the app has a simple and user-friendly interface for easy use.

## Technologies Used

- [Python](https://docs.python.org/3/) - Language used.
- [Streamlit](https://streamlit.io/) - Application interface.
- [scikit-learn](https://scikit-learn.org/stable/) - Train the linear regression model.
- [Pandas](https://pandas.pydata.org/) - Data manipulation.

## Steps to install and run

1. Clone the repository:

```bash
git clone https://github.com/felipeclarindo/pizza-price-predictor-web.git
```

2. Enter directory:

```bash
cd pizza-price-predictor-web
```

3. Create the `Virtual Environment`:

```bash
python -m venv .venv
```

4. Activate the `Virtual Environment` running file `.bat` in `.venv/Scripts/activate.bat`.

5. Install dependencies:

```bash
pip install -r requirements.txt
```

6. Run the application:

```bash
streamlit run app/main.py
```

7. The application will be available at:

- `http://localhost:8501`

8. Steps for use:

- Enter the diameter of the pizza in centimeters.
- Click Calculate price to see the prediction.

## Contribution

Contributions are welcome! If you have suggestions for improvements, feel free to open an issue or submit a pull request.

## Author

**Felipe Clarindo**

- [LinkedIn](https://www.linkedin.com/in/felipeclarindo)
- [Instagram](https://www.instagram.com/lipethecoder)
- [GitHub](https://github.com/felipeclarindo)

## License

This project is licensed under the [GNU Affero License](https://www.gnu.org/licenses/agpl-3.0.html).
