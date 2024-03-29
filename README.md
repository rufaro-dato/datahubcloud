# datahubcloud

My dataset page website

## Data presented as a table

<FlatUiTable url="https://raw.githubusercontent.com/rufaro-dato/datahubcloud/main/BTC-USD.csv" />

## Data as a line chart
<LineChart
  data="https://raw.githubusercontent.com/rufaro-dato/datahubcloud/main/BTC-USD.csv"
  title="High x Year"
  xAxis={{
    dataKey: 'Date', // Specify the key for the x-axis data
    type: 'category' // Assuming Date values are discrete categories
  }}
  yAxis="High"
/>
