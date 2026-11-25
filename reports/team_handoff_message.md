# Team handoff — Members 2 & 3

Members 2 and 3 have completed dataset understanding, data-quality checks, essential EDA, and reproducible train/validation/test preparation. The notebook is `notebooks/01_Data_Understanding_and_EDA.ipynb`.

**Members 4 (MLP) and 5 (Baseline):** Both use the same prepared files:

- `Data/processed/train_scaled.csv`
- `Data/processed/validation_scaled.csv`
- `Data/processed/test_scaled.csv`

Use `Diabetes_binary` as the target and exclude `source_row_index` from model inputs. The features are already scaled by a `StandardScaler` fitted on the training data. Do not refit preprocessing using validation or test data, and do not recreate or change the splits.

**Next:** Develop and train your respective models using the shared training split. Use validation for model choices, then evaluate on the test split only after those choices are finalized. This keeps both experiments comparable and avoids test-data leakage.
