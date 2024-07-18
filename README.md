# Space_Problem_NEO: Predicting Sentry Objects

This project involves predicting whether a near-Earth object (NEO) is a "sentry object" (an object with a risk of impact) using machine learning models. The models use various features of the NEOs to make these predictions.

## Dataset Description

The dataset used in this project contains information about various near-Earth objects. The relevant columns are:

- `absolute_magnitude_h`: The absolute magnitude of the NEO
- `kilometers_estimated_diameter_min`: The minimum estimated diameter in kilometers
- `kilometers_estimated_diameter_max`: The maximum estimated diameter in kilometers
- `perihelion_distance`: The perihelion distance of the NEO
- `aphelion_distance`: The aphelion distance of the NEO
- `orbit_class_type`: The class of the NEO's orbit
- `is_sentry_object`: A boolean indicating if the NEO is a sentry object (1: Yes, 0: No)

## Dependencies

To run this project, you need the following Python packages:
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## Installation

Install the required packages using pip:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
