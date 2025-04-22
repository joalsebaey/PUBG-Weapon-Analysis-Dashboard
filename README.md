# 🔫 Weapon Data Analysis

## Overview
A comprehensive data analysis project focused on weapon statistics from PUBG (PlayerUnknown's Battlegrounds). This project explores various weapon attributes including damage, fire rate, bullet caliber, and more to provide insights for gamers, game designers, and balance enthusiasts.

## 📊 Project Features

### Data Exploration
- Distribution analysis of weapons by type (Assault Rifles, SMGs, Shotguns, etc.)
- Analysis of bullet caliber usage across different weapon categories
- Performance metrics visualization including damage, fire rate, and DPS

### Key Visualizations
- **Weapon Distribution:** Count of weapons by type and bullet caliber
- **Performance Metrics:** Damage vs. Fire Rate scatter plots
- **Statistical Analysis:** Box plots of DPS by weapon and bullet type
- **Correlation Analysis:** Matrix of numeric weapon attributes
- **Performance Comparison:** Radar charts comparing top weapons across multiple metrics
- **Combat Effectiveness:** Shots to kill (chest vs. head) by weapon category

### Insights Available
- Identify the most powerful weapons based on various performance metrics
- Understand the tradeoffs between damage, fire rate, and magazine capacity
- Compare effectiveness of different bullet types
- Analyze the balance between weapon categories

## 🛠️ Technical Implementation

### Dependencies
```
pandas
matplotlib
numpy
```

### Project Structure
```
weapon-data-analysis/
├── data/
│   └── pubg-weapon-stats.csv    # Weapon statistics dataset
├── python_analysis.py           # Main analysis script
└── README.md                    # Project documentation
```

### Getting Started

1. Clone the repository
```bash
git clone https://github.com/yourusername/weapon-data-analysis.git
cd weapon-data-analysis
```

2. Install required packages
```bash
pip install pandas matplotlib numpy
```

3. Run the analysis script
```bash
python python_analysis.py
```

## 📸 Sample Visualizations

The analysis generates several visualizations including:

- Heat maps showing correlations between weapon attributes
- Bar charts displaying weapon type distributions
- Scatter plots showing the relationship between damage and fire rate
- Box plots comparing damage statistics across weapon types
- Radar charts highlighting top performers in each category

## 🎯 Applications

This analysis is useful for:
- Game designers balancing weapon systems
- Players looking to optimize their loadout choices
- Esports analysts studying weapon meta
- Game guide creators developing reference materials

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Add new analysis metrics
- Improve visualizations
- Update the dataset with new weapons
- Suggest balance improvements based on findings

## 📜 License

This project is available under the MIT License.
