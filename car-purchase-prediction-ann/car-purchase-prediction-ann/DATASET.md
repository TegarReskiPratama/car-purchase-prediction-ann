# Dataset setup

The CSV is not bundled. Use the `MODULE 1_CODELAB.csv` supplied with the original CODELAB Modul 1 and put it beside `car_purchase_prediction.ipynb`. The notebook reads it with `encoding="cp1252"`.

The original dataset URL and redistribution license have not been established from the attached notebook. Request the CSV from the original course/module provider. Add its original source and license before redistributing it publicly. Do not substitute a different dataset and present the saved metrics as its results.

## Expected columns

| Exact column | Role |
| --- | --- |
| `customer name` | Removed before modeling |
| `customer e-mail` | Removed before modeling |
| `country` | Removed before modeling |
| `gender` | Removed to match the four-feature codelab design |
| `age` | Numeric input |
| `annual Salary` | Numeric input |
| `credit card debt` | Numeric input |
| `net worth` | Numeric input |
| `car purchase amount` | Numeric regression target |

The saved notebook output reports 500 rows. The input features and target must not contain missing values for the existing pipeline to run. Identity columns are excluded from the portfolio preview. CSV files are excluded from Git by `.gitignore`; this does not prevent manual browser uploads.
