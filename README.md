# Robot-Navigation-Simulator
A Python simulation of autonomous robot navigation using pathfinding algorithms (BFS, A*, Dijkstra) with animated visualizations.

Clone the repository:
   ```bash
   git clone https://github.com/Safhanafarha775/Robot-Navigation-Simulator.git
   cd Robot-Navigation-Simulator
   ```

2. Install required Python packages:
   ```bash
   pip install -r requirements.txt
   ```
   (Create `requirements.txt` with `numpy`, `matplotlib`, `pandas`, `heapq`, `collections`, `IPython`)

### Running the Simulator

To run the interactive Colab notebook and generate all visualizations and animations:

1. Open the `Robot_Navigation.ipynb` file in Google Colab.
2. Run all cells (`Runtime -> Run all`).

### Generated Outputs

- **`robot_navigation.gif`**: An animated GIF showing the robot's pathfinding process.
- Various static `.png` plots of algorithm comparisons and path analysis.

## 🌐 Project Structure

```
├── Robot_Navigation_Simulator.ipynb    # Main Colab notebook with all code and explanations
├── README.md                      # This file
└── robot_navigation.gif           # Generated animation output
```

## 📈 Data Science & Robotics Insights

- **Algorithm Selection**: A* provides an optimal balance of speed and efficiency for robot navigation in grid-based environments.
- **Performance**: A* consistently explores fewer nodes and performs faster than BFS on larger, more complex mazes.
- **Heuristics**: The choice of heuristic function significantly impacts A* performance.
- **Real-world Applications**: This simulation lays the foundation for understanding pathfinding in self-driving cars, warehouse robots, and game AI.

## 🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## 📜 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 📞 Contact

Connect Safhana Farhath on [LinkedIn](https://linkedin.com/in/safhanafarha786) or [GitHub](https://github.com/Safhanafarha775).
