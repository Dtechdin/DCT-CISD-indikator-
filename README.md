# DCT-CISD-indikator-
Open Source Trading Library for Market Structure and CISD Analysis.
DC TRADERS {DCT} Framework - Open Source Trading Library
DC TRADERS {DCT} is an advanced, open-source technical analysis framework written in Pine Script® v6. This tool is designed to assist the trading community in identifying institutional order flow, market structure shifts
🚀 Key Features
1. Change In State of Delivery (CISD) Detection
Automatically identifies and tracks CISD levels. Unlike standard indicators, DCT uses a dynamic array system to store and manage historical levels, allowing traders to see where price delivery has shifted from bullish to bearish and vice versa.

It detects divergences between correlated assets to confirm institutional accumulation or distribution.
2. Automated Market Structure Tracking
Uses custom type definitions to track topPrice and bottomPrice dynamically, providing a clean visual representation of current market states (Bullish/Bearish).
3. Interactive Statistics Table
A real-time dashboard on the chart that displays the current market state and active ticker info, optimized for educational live-streaming and fast research.
🛠 Technical Implementation
This framework is built using the latest Pine Script® v6 standards:
Custom Object Types: Utilizes type MarketStructure and type cisd for memory-efficient data handling.
Array Management: Implements array.push and array.shift for real-time level management.
Multi-Symbol Security: Uses request.security with optimized 360-minute timeframe analysis for macro correlation.
📖 Educational Mission
This project is part of the DC Traders Education Community. Our mission is to provide high-quality, transparent, and open-source analytical tools to help retail traders understand institutional price action without the need for expensive proprietary software.
We believe that financial literacy should be accessible to everyone, and this repository serves as a foundation for algorithmic research and backtesting.
⚙️ Installation
Open TradingView.
Go to Pine Editor.
Create a New Indicator.
Paste the code from dct_indicator.pine in this repository.
Click Add to Chart.
📄 License
This project is licensed under the Mozilla Public License 2.0 - see the LICENSE file for details.
🤝 Contribution
Contributions are welcome! If you have ideas for new correlation pairs or structural logic, feel free to:
Fork the project.
Create your Feature Branch.
Submit a Pull Request.
Developed with ❤️ by Iamdinda and the DCT Community.
