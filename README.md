# F1 Tire Degradation & Lap Time Prediction Model 🏎️🏁

An end-to-end Machine Learning pipeline predicting Formula 1 lap times based on tire life, compound selection, and stint parameters using ensemble techniques.

## Features & Methodology
- **Data Pipeline:** Telemetry modeling of real-world F1 tire wear dynamics across Soft, Medium, and Hard compounds.
- **Modeling:** Trained a Random Forest Regressor to capture non-linear degradation trends.
- **Evaluation:** Evaluated performance using Mean Absolute Error (MAE) and feature importance analysis.

## Results
- Feature Analysis identified **TyreLife** (~85%) as the primary driver of performance degradation.
- Achieved minimal prediction error across multi-stint race simulations.

## Tech Stack
- **Language:** Python
- **Libraries:** Pandas, Scikit-Learn, Matplotlib, NumPy
- **Environment:** Google Colab
