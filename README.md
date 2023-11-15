# Wave Trend MT4

This is a code example of the Wave Trend MT4 trading robot developed by Forex Robot Easy Team. Please note that this code is not an exact copy of the original product and is only an approximate description of the necessary parameters for the operation of this product.

For detailed reviews and trading results of the Wave Trend MT4 trading robot, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/review-wave-trend-mt4-accurate-forex-software-for-identifying-market-reversals/).

## Description

The Wave Trend MT4 trading robot is a software designed to identify market reversals. It makes use of two moving averages, a fast moving average and a slow moving average, to generate buy and sell signals. It also checks for divergences between the two moving averages.

### Input Parameters

- FastMaPeriod: The period for the fast moving average.
- SlowMaPeriod: The period for the slow moving average.
- OverboughtLevel: The overbought level for the oscillator.
- OversoldLevel: The oversold level for the oscillator.

### Global Variables

- fastMaBuffer: Buffer to store fast moving average values.
- slowMaBuffer: Buffer to store slow moving average values.

### Initialization Function (OnInit)

- Allocates memory for the buffers.
- Sets the indicator labels.
- Sets the overbought and oversold levels.

### Deinitialization Function (OnDeinit)

- Frees the memory used by the buffers.

### Custom Function to Calculate Moving Average (MovingAverage)

- Calculates the moving average based on the specified period and shift.

### Custom Function to Check for Crossover (CrossOver)

- Checks if there is a crossover between two values.

### Custom Function to Check for Divergence (Divergence)

- Checks if there is a divergence between two values.

### Entry Point Function (OnTick)

- Calculates the fast and slow moving averages.
- Stores the moving average values in the buffers.
- Checks for a crossover, crossunder, or divergence.
- Generates appropriate signals and performs the necessary actions.

## Product Description

The Wave Trend MT4 trading robot is an accurate forex software developed by Forex Robot Easy Team. It is designed to identify market reversals using two moving averages and can generate buy and sell signals based on these indicators. Additionally, it can detect divergences between the moving averages, providing valuable insights for traders.

This trading robot is developed and published on the MQL5 website by forexroboteasy.com. The provided code serves as an example of how the product works and the necessary parameters for its operation. For detailed reviews and trading results of the Wave Trend MT4 trading robot, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/review-wave-trend-mt4-accurate-forex-software-for-identifying-market-reversals/).
