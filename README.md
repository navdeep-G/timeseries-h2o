## Exponential Smoothing & Moving Average Models Implemented in Java & H2O-3

An implementation of exponential smoothing and moving averages in pure Java and [H2O-3](https://github.com/h2oai/h2o-3)

## Java Implementation:
### Statistical Calculations:
- [Stats.java](https://github.com/navdeep-G/timeseries-java/blob/master/src/main/java/util/Stats.java)

### Transformation Algorithms:
- [BoxCox.java](https://github.com/navdeep-G/timeseries-java/blob/master/src/main/java/transform/BoxCox.java)
- [Transform.java](https://github.com/navdeep-G/timeseries-java/blob/master/src/main/java/transform/Transform.java)

### Moving Average Algorithms:
- [SimpleMovingAverage.java](https://github.com/navdeep-G/timeseries-java/blob/master/src/main/java/movingaverage/SimpleMovingAverage.java)
- [CumulativeMovingAverage.java](https://github.com/navdeep-G/timeseries-java/blob/master/src/main/java/movingaverage/CumulativeMovingAverage.java)
- [ExponentialMovingAverage.java](https://github.com/navdeep-G/timeseries-java/blob/master/src/main/java/movingaverage/ExponentialMovingAverage.java)

### Stationarity Tests:
- [AugmentedDickeyFuller.java](https://github.com/navdeep-G/timeseries-java/blob/master/src/main/java/tests/AugmentedDickeyFuller.java) 

### Forecasting Algorithms:
- [TripleExponentialSmoothing.java](https://github.com/navdeep-G/timeseries-java/tree/master/src/main/java/algos/expsmoothing/TripleExpSmoothing.java)
- [DoubleExponentialSmoothing.java](https://github.com/navdeep-G/timeseries-java/blob/master/src/main/java/algos/expsmoothing/DoubleExpSmoothing.java)
- [SingleExponentialSmoothing.java](https://github.com/navdeep-G/timeseries-java/blob/master/src/main/java/algos/expsmoothing/SingleExpSmoothing.java)

## H2O-3 Implementation::
### Statistical Calculations:
- [StatsFrame.java](https://github.com/navdeep-G/timeseries-java/blob/master/src/main/java/util/h2oframe/StatsFrame.java)

### Transformations: 
- [BoxCoxFrame.java](https://github.com/navdeep-G/timeseries-java/blob/master/src/main/java/transform/h2oframe/BoxCoxFrame.java)
- [TransformFrame.java](https://github.com/navdeep-G/timeseries-java/blob/master/src/main/java/transform/h2oframe/TransformFuncsFrame.java)

### Moving Averages:
- [SimpleMovingAverageFrame.java](https://github.com/navdeep-G/timeseries-java/blob/master/src/main/java/movingaverage/h2oframe/SimpleMovingAverageFrame.java)
- [CumulativeMovingAverageFrame.java](https://github.com/navdeep-G/timeseries-java/blob/master/src/main/java/movingaverage/h2oframe/CumulativeMovingAverageFrame.java)
- [ExponentialMovingAverageFrame .java](https://github.com/navdeep-G/timeseries-java/blob/master/src/main/java/movingaverage/h2oframe/ExponentialMovingAverageFrame.java)

### Stationarity Tests:
- WIP

### Forecasting Algorithms:
- [TripleExpSmoothingFrame.java](https://github.com/navdeep-G/timeseries-java/blob/master/src/main/java/algos/h2oframe/TripleExpSmoothingFrame.java)
- [DoubleExpSmoothingFrame.java](https://github.com/navdeep-G/timeseries-java/blob/master/src/main/java/algos/h2oframe/DoubleExpSmoothingFrame.java)
- [SingleExpSmoothingFrame.java](https://github.com/navdeep-G/timeseries-java/blob/master/src/main/java/algos/h2oframe/SingleExpSmoothingFrame.java)
