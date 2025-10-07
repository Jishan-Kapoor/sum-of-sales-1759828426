# Sales Summary Test

## Summary
This static web application fetches data from `data.csv`, calculates the total sales amount, and displays it on a single-page site titled "Sales Summary Test." It utilizes Bootstrap 5 from jsDelivr for styling.

## Setup
To deploy the application on GitHub Pages, follow these steps:
1. Fork this repository.
2. Upload your `data.csv` file to the repository.
3. In the repository settings, enable GitHub Pages and set the source branch to `main`.
4. Access the deployed site at `https://your-username.github.io/your-repository`.

## Usage
- Access the page by navigating to the deployed site on GitHub Pages.
- There are no query parameters or configuration options for the page.
- Key features:
  - Fetches data from `data.csv` automatically.
  - Calculates the total sales amount.
  - Displays the total sales in the element with id `total-sales`.

## Code Explanation
The implementation involves:
- Utilizing HTML to structure the page and display the total sales.
- Using JavaScript to fetch the data, calculate the total, and update the DOM.
- Bootstrap 5 from jsDelivr is included to enhance the visual presentation.

### Libraries Used
- Bootstrap 5 from jsDelivr

### JavaScript Logic
- Fetches `data.csv` using `fetch` API.
- Parses the CSV data to calculate the sum of the sales column.
- Updates the DOM to display the total sales amount.

## License
This project is licensed under the MIT License.