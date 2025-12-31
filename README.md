# Structural Breakout Matrix

**Professional Structural Market Analysis System for MetaTrader 5**

![MT5 Indicator](https://img.shields.io/badge/Platform-MetaTrader%205-blue)  
![Language](https://img.shields.io/badge/Language-MQL5-orange)  
![Version](https://img.shields.io/badge/Version-1.00-green)  
![License](https://img.shields.io/badge/License-Free%20for%20personal%20use-lightgrey)

## Overview

**Structural Breakout Matrix** is an advanced custom indicator for MetaTrader 5 that combines multiple smart money concepts (SMC/ICT) into a comprehensive breakout detection system.

It identifies high-probability breakout setups by analyzing:

- Market structure (HH/HL/LH/LL)
- Supply & Demand zones
- Order blocks (bullish/bearish)
- Volume confirmation & spikes
- False breakout filtering
- Multi-layer signal quality scoring

The indicator displays visual signals on the chart, draws key zones/levels, and includes a detailed real-time dashboard with trade parameters.

## Features

- **Structural Breakout Detection** (Bullish & Bearish) with 3-tier signal levels
- **Swing High/Low** marking
- **Order Block Detection** (validated by subsequent price movement)
- **Supply & Demand Zones** with strength scoring and transparency
- **Volume Spike** visualization
- **False Breakout** detection and alerts
- **Comprehensive Dashboard** showing:
  - Current market structure
  - Active zones & order blocks
  - Signal quality breakdown
  - Suggested entry, targets, stop loss, and risk/reward
- **Customizable Alerts** (popup, sound, push notification)
- **Non-repainting** logic (signals only on closed bars)

## Visual Elements

| Element                | Symbol/Color                          | Meaning                                      |
|------------------------|---------------------------------------|----------------------------------------------|
| Bullish Breakout       | Green upward arrow (↑)                 | High-probability long setup                  |
| Bearish Breakout       | Red downward arrow (↓)                | High-probability short setup                 |
| Level 2 Signal         | Yellow star                           | Strong confirmation                          |
| Level 3 Signal         | Cyan diamond                          | Highest quality signal                       |
| Swing High             | Orange-red marker                     | Potential resistance                         |
| Swing Low              | Blue marker                           | Potential support                            |
| Volume Spike           | Gold marker                           | Significant volume increase                  |
| Bullish Order Block    | Blue rectangle + marker               | Institutional buying area                    |
| Bearish Order Block    | Purple rectangle + marker             | Institutional selling area                   |
| False Breakout         | Gray X                                | Failed breakout detected                     |
| Supply Zone            | Red transparent rectangle             | Potential reversal/selling zone              |
| Demand Zone            | Green transparent rectangle           | Potential reversal/buying zone               |

## Installation

1. Download the file `StructuralBreakoutMatrix.mq5`
2. Open MetaTrader 5 → File → Open Data Folder
3. Navigate to `MQL5/Indicators/`
4. Copy the `.mq5` file into this folder
5. Restart MT5 or right-click in Navigator → Refresh
6. Drag the indicator onto any chart

## Input Parameters

The indicator is highly configurable with grouped settings:

### Structural Detection Settings
- Swing Detection Period
- Structure Threshold
- Multi-Timeframe Analysis
- Lookback periods

### Volume Confirmation
- Volume spike ratio
- SMA period
- Require increasing volume

### Supply-Demand Zones
- Zone strength filter
- Max zones displayed
- Zone range multiplier (ATR-based)
- Extend zones to current bar

### Order Block Detection
- Minimum body/range ratio
- Minimum volume ratio
- Validation bars forward
- Max order blocks shown

### Breakout Validation
- Follow-through bars
- Max pullback ratio
- False breakout window
- Session time filter (GMT)

### Signal Generation
- Minimum score thresholds for Level 1/2/3 signals
- Require volume confirmation
- Show all signal levels

### Visual & Dashboard Settings
- Colors for zones, levels, order blocks
- Zone transparency
- Dashboard position and appearance
- Enable/disable dashboard

### Alert Settings
- Enable alerts
- Alert on specific signal levels
- Alert on false breakouts
- Push notifications

## Usage Tips

- Best used on major forex pairs and indices
- Higher timeframes (H1, H4, Daily) produce more reliable signals
- Combine with price action confirmation
- Pay attention to Level 3 signals — highest historical probability
- Watch the dashboard for real-time context and trade parameters

## Author

© Copyright by **M4DI~UciH4**  
GitHub: https://github.com/RizkyEvory

## Disclaimer

This indicator is provided for educational and personal use only.  
No guarantee of profitability is made. Trading involves risk.  
Use at your own discretion and risk.

---

**Happy trading!** 🚀
