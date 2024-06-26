# Echarts-React

A React Components wrapper for Echarts.

## Installation

```bash
npm install echarts-react
```

## Usage

```ts
import EchartsComp form "echarts-react";

const options = {
  // Echarts options here
};

const handleChartClick = (params) => {
  console.log('Chart clicked:', params);
};

const handleChartDoubleClick = (params) => {
  console.log('Chart double-clicked:', params);
};

const handleAxisClick = (axis, params) => {
  console.log(axis + 'axis clicked:', params);
};

<EchartsComp options={options} handleChartClick={handleChartClick} handleChartDoubleClick={handleChartDoubleClick} handleAxisClick={handleAxisClick} />
```

## Version

```ts
react >= 18.0.0
react-dom >= 18.0.0
```
