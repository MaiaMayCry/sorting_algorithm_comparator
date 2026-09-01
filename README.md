# Sorting Algorithm Comparator

A performance benchmarking application that compares three sorting algorithms—Bubble Sort, Gnome Sort, and Cocktail Sort—using a dataset of 11,446 entries to analyze execution efficiency and performance characteristics.

The application is designed to:

- Implement Bubble Sort, Gnome Sort, and Cocktail Sort algorithms
- Measure and compare execution time for each sorting algorithm
- Benchmark performance on realistic dataset sizes
- Display performance metrics and comparisons
- Provide educational insights into algorithm efficiency
- Analyze time complexity in practical scenarios

## Features

- Three different sorting algorithm implementations
- Real-time performance measurement and timing
- Benchmark testing with 11,446 dataset entries
- Side-by-side performance comparison
- Detailed execution time metrics
- Visual results table for easy comparison
- Educational analysis of algorithm behavior

## Requirements

- .NET Framework (for Windows applications) or equivalent runtime
- Visual Studio or compatible C# compiler
- 2+ GB RAM for dataset processing

## Getting Started

1. **Clone or download the project**
```text
git clone https://github.com/MaiaMayCry/sorting\_algorithm\_comparator.git
```

2. **Open the project**
- Navigate to the `workspace` folder
- Open the project file in Visual Studio

3. **Build the project**
- Build the solution in Visual Studio

4. **Run the application**
- Execute the compiled application or run directly from Visual Studio

## Usage

1. **Load the dataset**
- The application uses a predefined dataset of 11,446 entries

2. **Run the benchmark**
- Click the execute button to run all three sorting algorithms

3. **View results**
- Compare execution times across Bubble Sort, Gnome Sort, and Cocktail Sort
- Analyze performance differences and efficiency metrics

4. **Interpret the data**
- Observe how algorithm choice impacts execution speed
- Understand practical implications of time complexity

## Algorithm Details

### Bubble Sort
- Time Complexity: O(n²)
- Simplest sorting algorithm
- Repeatedly compares adjacent elements

### Gnome Sort
- Time Complexity: O(n²)
- Similar to bubble sort with simpler logic
- Moves elements backwards when out of order

### Cocktail Sort
- Time Complexity: O(n²)
- Variation of bubble sort
- Sorts in both directions alternately

## Results

Results are displayed in a comparison table showing execution time (in milliseconds) for each algorithm on the same 11,446-entry dataset. This allows for empirical observation of how these algorithms perform in practice.

## Notes

- Execution times may vary depending on system hardware
- All algorithms are tested on identical data
- Results demonstrate the importance of algorithm selection for large datasets
- Run multiple times for average performance metrics
