psychogenicFever R Package

Detecting and Analyzing Psychogenic Fever Patterns

The psychogenicFever R package provides tools for detecting, analyzing, and visualizing patterns of psychogenic fever in medical data. This package is designed to assist researchers and medical professionals in identifying potential episodes of psychogenic fever and exploring their relationship with psychological factors.

Features
Preprocess Temperature Data: Clean and format temperature data for further analysis.
Detect Fever Episodes: Identify potential episodes of psychogenic fever based on temperature patterns and accompanying psychological factors.
Visualize Temperature Patterns: Generate visualizations to explore temperature patterns over time and their relationship with psychological factors.
Statistical Analysis: Conduct statistical analyses to explore associations between psychogenic fever episodes and psychological factors.

Installation
You can install the psychogenicFever package from CRAN using:
install.packages("psychogenicFever") 

Alternatively, you can install the development version directly from GitHub:
remotes::install_github("your_username/psychogenicFever")
Getting Started
Check out the vignettes and examples provided in the package to get started with analyzing psychogenic fever patterns in your data.

Usage

# Example usage of functions in the psychogenicFever package
library(psychogenicFever)

# Preprocess temperature data
cleaned_data <- preprocess_temperature_data(temperature_data)

# Detect fever episodes
fever_episodes <- detect_fever_episodes(temperature_data = cleaned_data, psychological_factors)

# Visualize temperature patterns
visualize_temperature_patterns(fever_episodes, psychological_factors, plot_type = "line")

# Conduct statistical analysis
stat_results <- statistical_analysis(fever_episodes, psychological_factors)

License
This package is licensed under the GNU General Public License v3.0. See the LICENSE file for details.
