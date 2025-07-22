# Structural transformation: Analysis of historical data

## Repository Link

[https://github.com/kielbjoern/structural_transformation](https://github.com/kielbjoern/structural_transformation)

## Description

Many years ago, I analyzed historical data on the structural transformation of employment in Schleswig-Holstein based on cohorts (birth years). The data comes from the official statistics (1882–1939). The focus was, how the shift from an agricultural to a service-based society took place. During which periods, and for which cohorts, was the employment transformation in Schleswig-Holstein (SH) particularly pronounced? Conversely, when was this transformation relatively weak? Due to the uniqueness of this historical event, establishing a benchmark is challenging. I therefore propose using the employment trends from the German Empire (Deutsches Reich) as a comparative template for Schleswig-Holstein.

### Results Summary

- **Best Model: is the Baseline model ;-(**
- **Evaluation Metric: MSE Loss and MAE**
- **Result: It was possible to use the model to create a comparative model for the strength of sectoral transformation in Schleswig-Holstein. And it was possible to determine the difference between the historical and the expected development for the individual datasets (cohort and census year). This enables statements about the transformation in Schleswig-Holstein: where it was particularly strong, where rather weak (see presentation for details).**

## Documentation

1. **[Literature Review](0_LiteratureReview/README.md)**
2. **[Dataset Characteristics](1_DatasetCharacteristics/03_exploratory_data_analysis.ipynb)**
3. **[Baseline Model](2_BaselineModel/baseline_model.ipynb)**
4. **[Model Definition and Evaluation](3_Model/model_definition_evaluation)**
5. **[Presentation](4_Presentation/Historical_Employment_Transformation.pptx)**

## Cover Image

![Project Cover Image](CoverImage/cover_image.png)
