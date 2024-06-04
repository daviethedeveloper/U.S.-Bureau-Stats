# Data Science Labor of Statistic

Brief description of what your project does and what it's used for.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What things you need to install the software and how to install them.



## Using the Public API from the U.S. Bureau of Labor Statistics

This section guides you through obtaining an API key necessary to fetch data for this project.

### Step 1: Register for an API Key

To access the U.S. Bureau of Labor Statistics Public API, you need to register for an API key. Here is a brief guide on how to do it:

1. Go to [BLS Public Data API](https://www.bls.gov/developers/) website.
2. Follow the registration process to obtain your API key.

![API Registration Step](path/to/your/screenshot1.png)

For a detailed guide, you can watch this helpful video:

[![How to get BLS API Key](https://img.youtube.com/vi/118FyvU6OSc/0.jpg)](https://www.youtube.com/watch?v=118FyvU6OSc)

### Step 2: Using the API Key

Once you have your API key, you can use it to make requests to the API as shown in the example codes in the repository.

## Understanding the Code

This section explains the purpose and function of the code in the Quarto (.qmd) file included in this repository.

### Overview

The code fetches employment data by state from the U.S. Bureau of Labor Statistics and visualizes this data using `ggplot2` and `plotly` in R.

### Key Functions

- `get_state_data()`: This function retrieves data for a specific state using the BLS API.
- Visualization: The code generates bar graphs representing employment data, which are interactive and can be used for detailed analysis.

![Visualization Example](path/to/your/screenshot2.png)

## Results

When you run the `.qmd` file with your API key, you will generate visualizations similar to the ones shown below:

![Generated Graph](path/to/your/screenshot3.png)

## Contributing

Please read [CONTRIBUTING.md](path/to/CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

- Hat tip to anyone whose code was used
- Inspiration
- etc


