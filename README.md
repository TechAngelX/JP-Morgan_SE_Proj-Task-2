# Task 2 of the JPMorgan Chase Software Engineering program.

This task involved developing a React + TypeScript application with a Node.js backend server to visualize real-time stock data. The application features:

Real-Time Data Streaming: Continuously updates a line graph with stock data (timestamp vs. top ask price) without manual refreshes.
Duplicate Data Filtering: Removes redundant data entries for accurate representation.
Key modifications:

src/App.tsx: Adapted for continuous data fetching and dynamic graph rendering.
src/Graph.tsx: Updated to correctly handle and display real-time data.

<img src="images/screenshot1.png" style="border: 5px solid #ccc;">
<img src="images/screenshot2.png" style="border: 5px solid #ccc;">
<img src="images/screenshot3.png" style="border: 5px solid #ccc;">
