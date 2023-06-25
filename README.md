**Customizable EMAs Indicator**

This indicator for Pine Script allows you to customize and plot Exponential Moving Averages (EMAs) on your trading charts. With adjustable periods for 5 EMAs (5, 13, 26, 50, and 200), you have control over which EMAs to display. By toggling the visibility of each EMA line, you can focus on specific moving averages relevant to your trading strategy.

**Features:**
- Adjustable periods for 5 EMAs (5, 13, 26, 50, 200)
- Boolean inputs to control the visibility of each EMA line
- Calculates EMAs using the `ta.ema` function
- Customizable color and line width for each EMA
- Overlay indicator on the chart for easy analysis

**Usage:**
1. Set the desired EMA periods in the input section.
2. Choose which EMAs to display by toggling the boolean inputs.
3. Observe the plotted EMAs on your trading chart.

**Example:**
```pinescript
//@version=5
indicator(title="Customizable EMAs", overlay=true)

// Set the desired EMA periods and visibility
// ...

// Calculate EMAs and plot them
// ...

// Customize colors and line widths
// ...

// Additional code and strategy integration
// ...
```

Feel free to customize the indicator based on your requirements and integrate it with your trading strategies. Happy trading!
