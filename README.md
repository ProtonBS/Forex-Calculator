# Trade Calculator

A web-based tool that calculates the number of trades required to reach a desired amount from an initial capital. The calculator takes into account the risk-to-reward ratio, win rate, and risk per trade, and provides a detailed breakdown of trades with an option to exclude NFP Fridays.

## Features

- Calculate the number of trades needed to reach the desired amount.
- Displays the estimated date to reach the desired amount.
- Provides a detailed breakdown of each trade.
- Option to exclude NFP Fridays from the trading days.
- Automatically updates results when toggling the NFP exclusion option.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/trade-calculator.git
    ```

2. Navigate to the project directory:

    ```bash
    cd trade-calculator
    ```

3. Open the `index.html` file in your preferred web browser to use the tool.

## Usage

1. Open the `index.html` file in your web browser.

2. Fill in the following parameters in the form:
    - **Initial Capital Amount**: The starting capital amount.
    - **Desired Amount**: The target amount you want to reach.
    - **Risk to Reward Ratio**: The risk-to-reward ratio for each trade (e.g., `1:3`).
    - **Win Rate (%)**: The win rate percentage (e.g., `30` for 30%).
    - **Risk per Trade (%)**: The percentage of capital you are willing to risk on each trade (e.g., `3` for 3%).

3. Click the **Calculate** button to see the results.

4. Optionally, toggle the **Exclude NFP Fridays** switch to exclude the first Friday of each month from the trading days. The results will update automatically.

## Example

If you want to flip an initial capital of `$30` to `$100` with a risk-to-reward ratio of `1:3`, a win rate of `30%`, and risking `3%` per trade, the tool will show:

