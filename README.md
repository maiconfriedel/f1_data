# Formula 1 Races Data

This repository contains structured data for Formula 1 races in JSON format. The data is organized by year and race name, with detailed session information for each event.

## 📂 Repository Structure

```
/repository-root
│
├── 2025/
│   ├── chinese-grand-prix/
│   │   ├── free_practice_1.json
│   │   ├── free_practice_2.json (if applicable)
│   │   ├── free_practice_3.json (if applicable)
│   │   ├── qualifying.json
│   │   ├── sprint_qualifying.json (if applicable)
│   │   ├── sprint.json (if applicable)
│   │   ├── race.json
│   ├── another-grand-prix/
│   │   ├── free_practice_1.json
│   │   ├── qualifying.json
│   │   ├── race.json
│
└── ...
```

## 📌 Data Details
Each JSON file contains structured information regarding the specific session. The typical data structure includes:

- **Free Practice Sessions**:
  - `Position`: Final ranking in the session.
  - `DriverNumber`: The number assigned to the driver.
  - `Driver`: The name of the driver.
  - `Constructor`: The team the driver represents.
  - `Time`: Best lap time recorded.
  - `Gap`: Time difference to the leader (empty for the first position).
  - `Laps`: Total number of laps completed.

- **Qualifying Sessions (including Sprint Qualifying)**:
  - `Position`: Final ranking in the session.
  - `DriverNumber`: The number assigned to the driver.
  - `Driver`: The name of the driver.
  - `Constructor`: The team the driver represents.
  - `Q1`, `Q2`, `Q3`: Best lap times in each qualifying segment.
  - `Gap`: Time difference to the leader (empty for the first position).
  - `Laps`: Total number of laps completed.

- **Race Sessions (including Sprint Races)**:
  - `Position`: Final ranking in the race.
  - `DriverNumber`: The number assigned to the driver.
  - `Driver`: The name of the driver.
  - `Constructor`: The team the driver represents.
  - `TimeOrRetired`: Total race time or reason for retirement.
  - `Grid`: Starting position on the grid.
  - `Laps`: Total number of laps completed.
  - `Points`: Points awarded based on finishing position.

## 🔄 Data Updates
Race data is updated every **Monday** after the race weekend, ensuring all session results and statistics have been computed and finalized.

## 🚀 Usage
You can use this dataset for:
- Data analysis and visualization.
- Machine learning models related to motorsports.
- API development for F1-related applications.
- Historical race comparisons and trend analysis.

## 📥 Contribution
Feel free to contribute by submitting pull requests with:
- New race data.
- Data corrections and improvements.
- Additional details or enrichments.

## 📜 License
This repository is open-source and available under the [MIT License](LICENSE).

---

For any questions or suggestions, feel free to open an issue. Enjoy exploring the data! 🏎️💨

