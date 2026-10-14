# Leaf-level model and augmentation configurations for Leaf-EFEH electrical response prediction

Workbook of the leaf-level model and data-augmentation configurations used to predict open-circuit voltage (V<sub>OC</sub>) and short-circuit current (I<sub>SC</sub>) of leaf-based electric field energy harvesters during controlled dehydration.

The file is `leaf_level_model_and_augmentation_configurations.xlsx`. The multilayer perceptron is labeled ANN in the workbook.

## Sheets

- **Table7_selection.** Best and worst augmented configuration for each species, response, and model, ranked by mean test R² across 20 repetitions. It reports the real-data baseline, the augmented MAE, RMSE, and R², the change in R², the augmentation settings, and the model hyperparameters.
- **Brassica_fixed.** Augmentation settings and model hyperparameters for *Brassica rapa pekinensis*. These settings were held fixed across the 20 repetitions.
- **Spinacia_ranges.** Numerical ranges and the most frequent categorical choices of the augmentation and model hyperparameters for *Spinacia oleracea*, summarized over the 20 repetitions.
- **Spinacia_full.** Complete repetition-specific record for *Spinacia oleracea*: 1,200 rows (20 repetitions, two responses, five models, and six training conditions). Each row gives the repetition, the seed, the training and test leaves, R², RMSE, MAE, the augmentation parameters, and the selected hyperparameters.

## Authors

- Alexis Chugá-Portilla, Universidad Católica del Norte — [ORCID 0009-0001-8384-2347](https://orcid.org/0009-0001-8384-2347)
- Oswaldo Menéndez-Granizo, Universidad Católica del Norte — [ORCID 0000-0001-7101-0319](https://orcid.org/0000-0001-7101-0319)

## License

This work is licensed under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

