# React Native FlatList Performance Optimization

This repository demonstrates a common performance issue in React Native's FlatList component when dealing with large datasets and complex item rendering. The `FlatListBug.js` file shows an example of how inefficient rendering can lead to poor performance, while `FlatListBugSolution.js` demonstrates optimized solutions.

**Problem:** Slow scrolling, dropped frames, or UI freezes in FlatList with large datasets and computationally expensive `renderItem` functions.

**Solution:** Implementing optimizations like `keyExtractor`, `ItemSeparatorComponent`, `getItemLayout`, and using `React.memo` or `useMemo` to prevent unnecessary re-renders.