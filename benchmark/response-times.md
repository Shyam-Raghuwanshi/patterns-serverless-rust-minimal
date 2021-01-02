
# Benchmark: Response Times

The following are the response time results from AWS XRay, generated after running `npm run benchmark`.

![Average Cold/Warm Response Times](./response-times-average.svg)

- 🔵: Average cold startup times
- 🔴: Average warm startup times

![Fastest and Slowest Response Times](./response-times-extremes.svg)

- 🔵: Fastest warm response time
- 🔴: Slowest warm response time
- 🟡: Fastest cold response time
- 🟠: Slowest cold response time

## Results for 128 MB

| Measurement (128 MB) | Time (ms) |
|-------------|------|
| Average warm start response time | 17.3 ms |
| Average cold start response time | 109.7 ms |
| Fastest warm response time | 4.9 ms |
| Slowest warm response time | 151.9 ms |
| Fastest cold response time  | 78.9 ms |
| Slowest cold response time | 177.9 ms |
  

| Response time | Initialization | Invocation | Overhead | Cold/ Warm Start | Memory Size |
|---------------|----------------|------------|----------|------------------|-------------|
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 91 ms | 19.9 ms | 0.4 ms | 0.1 ms | 🥶 | 128 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 128 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 128 MB |
| 4.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 128 MB |
| 43.9 ms |  | 37.4 ms | 0.1 ms | 🥵 | 128 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 128 MB |
| 123 ms | 19.5 ms | 0.6 ms | 0.1 ms | 🥶 | 128 MB |
| 96.9 ms | 20.2 ms | 0.6 ms | 0.5 ms | 🥶 | 128 MB |
| 8.9 ms |  | 0.4 ms | 0 ms | 🥵 | 128 MB |
| 36.9 ms |  | 10.8 ms | 19.9 ms | 🥵 | 128 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 9.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 128 MB |
| 6.9 ms |  |  |  | 🥵 | 128 MB |
| 101 ms |  |  |  | 🥵 | 128 MB |
| 129.9 ms | 31.8 ms | 0.4 ms | 0.2 ms | 🥶 | 128 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 128 MB |
| 95 ms | 17.3 ms | 0.4 ms | 0.3 ms | 🥶 | 128 MB |
| 13.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 128 MB |
| 92.9 ms | 26.2 ms | 0.6 ms | 3.1 ms | 🥶 | 128 MB |
| 7.9 ms |  | 1.5 ms | 0.3 ms | 🥵 | 128 MB |
| 90.9 ms | 25 ms | 0.5 ms | 0.4 ms | 🥶 | 128 MB |
| 98 ms | 18.9 ms | 0.6 ms | 0.4 ms | 🥶 | 128 MB |
| 25 ms |  | 0.7 ms | 8.7 ms | 🥵 | 128 MB |
| 26 ms |  | 18.5 ms | 0.2 ms | 🥵 | 128 MB |
| 38 ms |  | 32.8 ms | 0.3 ms | 🥵 | 128 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 128 MB |
| 105.9 ms | 20 ms | 0.5 ms | 0.1 ms | 🥶 | 128 MB |
| 68 ms |  | 60.7 ms | 0.2 ms | 🥵 | 128 MB |
| 128 ms | 25.6 ms | 0.7 ms | 0.3 ms | 🥶 | 128 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 23.9 ms |  | 18.6 ms | 0.2 ms | 🥵 | 128 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 24.9 ms |  | 18.8 ms | 0.1 ms | 🥵 | 128 MB |
| 151.9 ms |  | 80 ms | 59.9 ms | 🥵 | 128 MB |
| 6 ms |  | 0.5 ms | 0.2 ms | 🥵 | 128 MB |
| 21.9 ms |  | 15.7 ms | 0.2 ms | 🥵 | 128 MB |
| 54.9 ms |  | 48.5 ms | 0.3 ms | 🥵 | 128 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 128 MB |
| 9 ms |  | 3 ms | 0.1 ms | 🥵 | 128 MB |
| 125 ms | 26.2 ms | 0.6 ms | 0.4 ms | 🥶 | 128 MB |
| 101.9 ms | 18.5 ms | 0.5 ms | 0.3 ms | 🥶 | 128 MB |
| 8 ms |  | 0.4 ms | 0.3 ms | 🥵 | 128 MB |
| 50.9 ms |  | 0.5 ms | 39.5 ms | 🥵 | 128 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 23 ms |  | 17 ms | 0 ms | 🥵 | 128 MB |
| 60.9 ms |  | 34.5 ms | 19.7 ms | 🥵 | 128 MB |
| 4.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 128 MB |
| 10.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 6 ms |  | 0.5 ms | 0.2 ms | 🥵 | 128 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 128 MB |
| 102.9 ms | 27.1 ms | 0.5 ms | 0.5 ms | 🥶 | 128 MB |
| 24 ms |  | 16.9 ms | 0.1 ms | 🥵 | 128 MB |
| 85 ms |  | 79.8 ms | 0.7 ms | 🥵 | 128 MB |
| 93.9 ms | 25.3 ms | 0.4 ms | 0.2 ms | 🥶 | 128 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 128 MB |
| 18.9 ms |  | 12.8 ms | 0.2 ms | 🥵 | 128 MB |
| 8 ms |  | 0.5 ms | 0.4 ms | 🥵 | 128 MB |
| 23.9 ms |  | 18 ms | 0.2 ms | 🥵 | 128 MB |
| 23.9 ms |  | 0.4 ms | 18 ms | 🥵 | 128 MB |
| 24 ms |  | 19.3 ms | 0.2 ms | 🥵 | 128 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 13.9 ms |  | 7.1 ms | 0.1 ms | 🥵 | 128 MB |
| 23 ms |  | 18.4 ms | 0.2 ms | 🥵 | 128 MB |
| 101 ms | 27.5 ms | 0.6 ms | 0.3 ms | 🥶 | 128 MB |
| 33.9 ms |  | 27.7 ms | 0.2 ms | 🥵 | 128 MB |
| 78.9 ms | 17.9 ms | 0.5 ms | 0.1 ms | 🥶 | 128 MB |
| 7 ms |  | 0.3 ms | 0.2 ms | 🥵 | 128 MB |
| 111 ms | 25 ms | 0.7 ms | 0.3 ms | 🥶 | 128 MB |
| 85 ms |  | 77.7 ms | 0.2 ms | 🥵 | 128 MB |
| 98.9 ms | 25.2 ms | 0.7 ms | 0.4 ms | 🥶 | 128 MB |
| 53.9 ms |  | 39.9 ms | 0.3 ms | 🥵 | 128 MB |
| 14 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 42 ms |  | 35 ms | 0 ms | 🥵 | 128 MB |
| 25 ms |  | 18.4 ms | 0.3 ms | 🥵 | 128 MB |
| 107 ms | 26.8 ms | 0.5 ms | 0.2 ms | 🥶 | 128 MB |
| 26.9 ms |  | 21.4 ms | 0.1 ms | 🥵 | 128 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 117 ms |  | 91.5 ms | 19.7 ms | 🥵 | 128 MB |
| 98.9 ms | 25.7 ms | 0.3 ms | 0.3 ms | 🥶 | 128 MB |
| 95 ms | 25 ms | 0.4 ms | 0.1 ms | 🥶 | 128 MB |
| 29.9 ms |  | 23.1 ms | 0.1 ms | 🥵 | 128 MB |
| 23 ms |  | 18.6 ms | 0.1 ms | 🥵 | 128 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 128 MB |
| 38.9 ms |  | 11.9 ms | 20 ms | 🥵 | 128 MB |
| 88.9 ms | 23.8 ms | 0.4 ms | 0.2 ms | 🥶 | 128 MB |
| 32.9 ms |  | 25.4 ms | 0.2 ms | 🥵 | 128 MB |
| 54 ms |  | 40.3 ms | 0.2 ms | 🥵 | 128 MB |
| 67 ms |  | 20.2 ms | 39.6 ms | 🥵 | 128 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 128 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 177.9 ms | 18.6 ms | 0.5 ms | 0.3 ms | 🥶 | 128 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 121 ms | 33.5 ms | 15.7 ms | 0.5 ms | 🥶 | 128 MB |
| 95 ms | 18.9 ms | 0.5 ms | 0.4 ms | 🥶 | 128 MB |
| 100.9 ms | 30.2 ms | 0.4 ms | 0.4 ms | 🥶 | 128 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 128 MB |
| 118 ms | 28.7 ms | 0.4 ms | 0.2 ms | 🥶 | 128 MB |
| 45 ms |  | 39.7 ms | 0.1 ms | 🥵 | 128 MB |
| 23 ms |  | 0.5 ms | 17.3 ms | 🥵 | 128 MB |
| 128 ms | 22.3 ms | 0.6 ms | 0.2 ms | 🥶 | 128 MB |
| 111 ms | 23 ms | 0.4 ms | 0.2 ms | 🥶 | 128 MB |
| 91 ms | 22 ms | 0.3 ms | 0.2 ms | 🥶 | 128 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 128 MB |
| 59 ms |  | 40 ms | 0.2 ms | 🥵 | 128 MB |
| 76.9 ms |  |  |  | 🥵 | 128 MB |
| 20 ms |  | 12 ms | 0.2 ms | 🥵 | 128 MB |
| 86.9 ms |  | 81.1 ms | 0.3 ms | 🥵 | 128 MB |
| 7.9 ms |  | 3 ms | 0.1 ms | 🥵 | 128 MB |
| 105 ms | 19.3 ms | 0.7 ms | 0.2 ms | 🥶 | 128 MB |
| 26.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 88 ms |  | 81.4 ms | 0 ms | 🥵 | 128 MB |
| 59 ms |  | 40.2 ms | 0.1 ms | 🥵 | 128 MB |
| 23.9 ms |  | 18.1 ms | 0.4 ms | 🥵 | 128 MB |
| 8 ms |  | 0.6 ms | 0.2 ms | 🥵 | 128 MB |
| 112.9 ms | 25 ms | 0.8 ms | 0.2 ms | 🥶 | 128 MB |
| 13 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 6 ms |  | 1.1 ms | 0.1 ms | 🥵 | 128 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 23.9 ms |  | 18.6 ms | 0.1 ms | 🥵 | 128 MB |
| 26.9 ms |  | 19.6 ms | 0.1 ms | 🥵 | 128 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 23 ms |  | 18.3 ms | 0.1 ms | 🥵 | 128 MB |
| 115 ms | 20.6 ms | 0.9 ms | 14.6 ms | 🥶 | 128 MB |
| 23 ms |  | 16.6 ms | 0.1 ms | 🥵 | 128 MB |
| 27 ms |  | 0.6 ms | 18.8 ms | 🥵 | 128 MB |
| 92 ms |  | 84.5 ms | 0.3 ms | 🥵 | 128 MB |
| 20.9 ms |  | 13.9 ms | 0.1 ms | 🥵 | 128 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 19.9 ms |  | 13.8 ms | 0.2 ms | 🥵 | 128 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 24.9 ms |  | 19.1 ms | 0.2 ms | 🥵 | 128 MB |
| 16 ms |  | 0.5 ms | 0.2 ms | 🥵 | 128 MB |
| 104 ms | 21.5 ms | 0.6 ms | 0.2 ms | 🥶 | 128 MB |
| 64 ms |  | 17.3 ms | 39.8 ms | 🥵 | 128 MB |
| 36.9 ms |  | 28.5 ms | 0.2 ms | 🥵 | 128 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 9 ms |  | 0.3 ms | 0 ms | 🥵 | 128 MB |
| 119.9 ms | 23.2 ms | 0.6 ms | 0.3 ms | 🥶 | 128 MB |
| 10 ms |  | 3.7 ms | 0.1 ms | 🥵 | 128 MB |
| 109 ms |  | 80 ms | 19.9 ms | 🥵 | 128 MB |
| 154 ms | 25.4 ms | 0.4 ms | 0.5 ms | 🥶 | 128 MB |
| 9.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 128 MB |
| 96.9 ms | 17.9 ms | 0.5 ms | 0.3 ms | 🥶 | 128 MB |
| 80 ms |  | 73.7 ms | 0.1 ms | 🥵 | 128 MB |
| 23.9 ms |  | 17.1 ms | 0.1 ms | 🥵 | 128 MB |
| 9 ms |  | 3.4 ms | 0.1 ms | 🥵 | 128 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 128 MB |
| 5 ms |  | 0.3 ms | 0 ms | 🥵 | 128 MB |
| 115.9 ms | 18.7 ms | 0.5 ms | 0.3 ms | 🥶 | 128 MB |
| 117 ms | 25 ms | 0.4 ms | 7.1 ms | 🥶 | 128 MB |
| 6 ms |  | 0.4 ms | 0 ms | 🥵 | 128 MB |
| 85.9 ms | 18.1 ms | 0.4 ms | 0.2 ms | 🥶 | 128 MB |
| 85.9 ms | 18.4 ms | 0.6 ms | 0.4 ms | 🥶 | 128 MB |
| 25 ms |  | 19.1 ms | 0.7 ms | 🥵 | 128 MB |
| 99.9 ms | 27.3 ms | 0.4 ms | 0.1 ms | 🥶 | 128 MB |
| 39 ms |  | 32.4 ms | 0.1 ms | 🥵 | 128 MB |
| 95 ms | 18.5 ms | 0.5 ms | 0.1 ms | 🥶 | 128 MB |
| 146.9 ms | 28.7 ms | 0.4 ms | 0.2 ms | 🥶 | 128 MB |
| 59.9 ms |  | 33.6 ms | 19.9 ms | 🥵 | 128 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 36.9 ms |  | 29.6 ms | 0.2 ms | 🥵 | 128 MB |
| 23.9 ms |  | 17.1 ms | 0.2 ms | 🥵 | 128 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 98 ms | 26.9 ms | 0.8 ms | 0.2 ms | 🥶 | 128 MB |## Results for 256 MB

| Measurement (256 MB) | Time (ms) |
|-------------|------|
| Average warm start response time | 22.2 ms |
| Average cold start response time | 114.3 ms |
| Fastest warm response time | 4.9 ms |
| Slowest warm response time | 151.9 ms |
| Fastest cold response time  | 75 ms |
| Slowest cold response time | 279 ms |
  

| Response time | Initialization | Invocation | Overhead | Cold/ Warm Start | Memory Size |
|---------------|----------------|------------|----------|------------------|-------------|
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 256 MB |
| 107 ms | 28.7 ms | 0.6 ms | 0.1 ms | 🥶 | 256 MB |
| 99.9 ms | 19.8 ms | 0.5 ms | 0.2 ms | 🥶 | 256 MB |
| 8 ms |  | 0.5 ms | 0.1 ms | 🥵 | 256 MB |
| 6.9 ms |  |  |  | 🥵 | 256 MB |
| 8.9 ms |  | 0.4 ms | 0 ms | 🥵 | 256 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 19 ms |  | 0.6 ms | 0.2 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 95 ms | 17.3 ms | 0.4 ms | 0.3 ms | 🥶 | 256 MB |
| 92 ms | 22.9 ms | 0.4 ms | 0.2 ms | 🥶 | 256 MB |
| 29 ms |  | 0.4 ms | 0.2 ms | 🥵 | 256 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 129.9 ms | 31.8 ms | 0.4 ms | 0.2 ms | 🥶 | 256 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 256 MB |
| 78.9 ms | 24.9 ms | 0.5 ms | 0.3 ms | 🥶 | 256 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 256 MB |
| 98.9 ms | 18.2 ms | 0.6 ms | 0.1 ms | 🥶 | 256 MB |
| 99.9 ms | 26.2 ms | 0.3 ms | 0.3 ms | 🥶 | 256 MB |
| 98 ms | 18.9 ms | 0.6 ms | 0.4 ms | 🥶 | 256 MB |
| 99.9 ms | 31.7 ms | 0.5 ms | 0.1 ms | 🥶 | 256 MB |
| 14 ms |  | 6.2 ms | 0.1 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 256 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 4.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 25 ms |  | 18 ms | 0.1 ms | 🥵 | 256 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.4 ms | 0.4 ms | 🥵 | 256 MB |
| 19 ms |  | 12.3 ms | 0.1 ms | 🥵 | 256 MB |
| 26.9 ms |  | 20.2 ms | 0.1 ms | 🥵 | 256 MB |
| 128 ms | 25.6 ms | 0.7 ms | 0.3 ms | 🥶 | 256 MB |
| 5 ms |  | 0.4 ms | 0 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 23.9 ms |  | 18.6 ms | 0.2 ms | 🥵 | 256 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 151.9 ms |  | 80 ms | 59.9 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 256 MB |
| 54.9 ms |  | 48.5 ms | 0.3 ms | 🥵 | 256 MB |
| 20.9 ms |  | 13.3 ms | 0.2 ms | 🥵 | 256 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 13.9 ms |  | 9.4 ms | 0.1 ms | 🥵 | 256 MB |
| 9 ms |  | 3 ms | 0.1 ms | 🥵 | 256 MB |
| 101.9 ms | 18.5 ms | 0.5 ms | 0.3 ms | 🥶 | 256 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 256 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 16 ms |  | 8.9 ms | 0.2 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 4.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 50.9 ms |  | 0.5 ms | 39.5 ms | 🥵 | 256 MB |
| 11.9 ms |  | 6.6 ms | 0.1 ms | 🥵 | 256 MB |
| 7.9 ms |  | 0.7 ms | 0.2 ms | 🥵 | 256 MB |
| 98 ms | 17.2 ms | 0.4 ms | 0.1 ms | 🥶 | 256 MB |
| 85 ms |  | 79.8 ms | 0.7 ms | 🥵 | 256 MB |
| 12 ms |  | 5.1 ms | 0.1 ms | 🥵 | 256 MB |
| 44 ms |  | 36.3 ms | 0.2 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 256 MB |
| 8 ms |  | 0.5 ms | 0.4 ms | 🥵 | 256 MB |
| 18.9 ms |  | 13.8 ms | 0.1 ms | 🥵 | 256 MB |
| 23.9 ms |  | 0.4 ms | 18 ms | 🥵 | 256 MB |
| 96.9 ms | 26.2 ms | 0.6 ms | 0.1 ms | 🥶 | 256 MB |
| 13.9 ms |  | 7.1 ms | 0.1 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.4 ms | 0.5 ms | 🥵 | 256 MB |
| 23 ms |  | 18.4 ms | 0.2 ms | 🥵 | 256 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 33.9 ms |  | 27.7 ms | 0.2 ms | 🥵 | 256 MB |
| 78.9 ms | 17.9 ms | 0.5 ms | 0.1 ms | 🥶 | 256 MB |
| 85 ms |  | 77.7 ms | 0.2 ms | 🥵 | 256 MB |
| 111 ms | 25 ms | 0.7 ms | 0.3 ms | 🥶 | 256 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 100 ms | 20.3 ms | 0.5 ms | 0.2 ms | 🥶 | 256 MB |
| 14 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 16 ms |  | 10.2 ms | 0 ms | 🥵 | 256 MB |
| 12 ms |  | 5.3 ms | 0.1 ms | 🥵 | 256 MB |
| 25 ms |  | 18.4 ms | 0.3 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 256 MB |
| 53.9 ms |  | 39.9 ms | 0.3 ms | 🥵 | 256 MB |
| 117 ms |  | 91.5 ms | 19.7 ms | 🥵 | 256 MB |
| 98.9 ms | 25.7 ms | 0.3 ms | 0.3 ms | 🥶 | 256 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 256 MB |
| 95 ms | 25 ms | 0.4 ms | 0.1 ms | 🥶 | 256 MB |
| 23 ms |  | 18.6 ms | 0.1 ms | 🥵 | 256 MB |
| 99.9 ms | 29.8 ms | 0.4 ms | 0.2 ms | 🥶 | 256 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 11.9 ms |  | 4.2 ms | 0.2 ms | 🥵 | 256 MB |
| 67 ms |  | 20.2 ms | 39.6 ms | 🥵 | 256 MB |
| 23 ms |  | 0.5 ms | 17.3 ms | 🥵 | 256 MB |
| 24.9 ms |  | 18 ms | 0.2 ms | 🥵 | 256 MB |
| 22 ms |  | 15.3 ms | 0.1 ms | 🥵 | 256 MB |
| 100.9 ms | 30.2 ms | 0.4 ms | 0.4 ms | 🥶 | 256 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 118 ms | 28.7 ms | 0.4 ms | 0.2 ms | 🥶 | 256 MB |
| 45 ms |  | 39.7 ms | 0.1 ms | 🥵 | 256 MB |
| 147 ms | 18.6 ms | 0.5 ms | 0.2 ms | 🥶 | 256 MB |
| 36.9 ms |  | 30.9 ms | 0.2 ms | 🥵 | 256 MB |
| 128 ms | 22.3 ms | 0.6 ms | 0.2 ms | 🥶 | 256 MB |
| 75 ms | 22 ms | 0.4 ms | 0 ms | 🥶 | 256 MB |
| 7.9 ms |  | 1.7 ms | 0.3 ms | 🥵 | 256 MB |
| 279 ms | 27.9 ms | 0.4 ms | 0.1 ms | 🥶 | 256 MB |
| 21.9 ms |  | 10.5 ms | 0.1 ms | 🥵 | 256 MB |
| 23 ms |  | 15.8 ms | 1.4 ms | 🥵 | 256 MB |
| 26.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 256 MB |
| 76.9 ms |  |  |  | 🥵 | 256 MB |
| 101 ms | 19.2 ms | 0.7 ms | 0.4 ms | 🥶 | 256 MB |
| 105 ms | 19.3 ms | 0.7 ms | 0.2 ms | 🥶 | 256 MB |
| 13 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 23.9 ms |  | 18.1 ms | 0.4 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 256 MB |
| 95.9 ms | 25.4 ms | 0.7 ms | 0.2 ms | 🥶 | 256 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 112.9 ms | 25 ms | 0.8 ms | 0.2 ms | 🥶 | 256 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 256 MB |
| 112.9 ms | 19.2 ms | 0.5 ms | 0.2 ms | 🥶 | 256 MB |
| 23.9 ms |  | 18.6 ms | 0.1 ms | 🥵 | 256 MB |
| 26.9 ms |  | 19.6 ms | 0.1 ms | 🥵 | 256 MB |
| 38 ms |  | 32.5 ms | 0.3 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 6 ms |  | 1.1 ms | 0.1 ms | 🥵 | 256 MB |
| 20 ms |  | 12.5 ms | 0 ms | 🥵 | 256 MB |
| 13.9 ms |  | 8.6 ms | 0.1 ms | 🥵 | 256 MB |
| 27 ms |  | 20.3 ms | 0.2 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 82.9 ms | 21.9 ms | 0.6 ms | 0.4 ms | 🥶 | 256 MB |
| 23 ms |  | 16.6 ms | 0.1 ms | 🥵 | 256 MB |
| 115 ms | 20.6 ms | 0.9 ms | 14.6 ms | 🥶 | 256 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 8 ms |  | 0.5 ms | 0.1 ms | 🥵 | 256 MB |
| 36.9 ms |  | 31.9 ms | 0.2 ms | 🥵 | 256 MB |
| 104 ms | 21.5 ms | 0.6 ms | 0.2 ms | 🥶 | 256 MB |
| 19.9 ms |  | 13.8 ms | 0.2 ms | 🥵 | 256 MB |
| 24.9 ms |  | 19.1 ms | 0.2 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 256 MB |
| 9 ms |  | 0.3 ms | 0 ms | 🥵 | 256 MB |
| 23.9 ms |  | 17.1 ms | 0.1 ms | 🥵 | 256 MB |
| 36.9 ms |  | 28.5 ms | 0.2 ms | 🥵 | 256 MB |
| 115.9 ms | 18.7 ms | 0.5 ms | 0.3 ms | 🥶 | 256 MB |
| 9 ms |  | 3.4 ms | 0.1 ms | 🥵 | 256 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 256 MB |
| 16 ms |  | 0.7 ms | 0.4 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 256 MB |
| 5 ms |  | 0.3 ms | 0 ms | 🥵 | 256 MB |
| 85.9 ms | 18.1 ms | 0.4 ms | 0.2 ms | 🥶 | 256 MB |
| 85.9 ms | 18.4 ms | 0.6 ms | 0.4 ms | 🥶 | 256 MB |
| 26 ms |  | 19.9 ms | 0.2 ms | 🥵 | 256 MB |
| 7.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 256 MB |
| 85.9 ms | 21.9 ms | 0.5 ms | 0.1 ms | 🥶 | 256 MB |
| 95 ms | 18.5 ms | 0.5 ms | 0.1 ms | 🥶 | 256 MB |
| 7.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 256 MB |
| 146.9 ms | 28.7 ms | 0.4 ms | 0.2 ms | 🥶 | 256 MB |
| 99.9 ms | 27.3 ms | 0.4 ms | 0.1 ms | 🥶 | 256 MB |
| 59.9 ms |  | 33.6 ms | 19.9 ms | 🥵 | 256 MB |
| 36.9 ms |  | 29.6 ms | 0.2 ms | 🥵 | 256 MB |
| 98 ms | 26.9 ms | 0.8 ms | 0.2 ms | 🥶 | 256 MB |
| 107 ms | 20 ms | 0.8 ms | 0.1 ms | 🥶 | 256 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 105 ms | 28.8 ms | 0.4 ms | 0.3 ms | 🥶 | 256 MB |
| 6.9 ms |  | 0.4 ms | 0.3 ms | 🥵 | 256 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 30.9 ms |  | 24.4 ms | 0.3 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 91 ms | 19.9 ms | 0.4 ms | 0.1 ms | 🥶 | 256 MB |
| 88 ms | 26.4 ms | 0.5 ms | 0.2 ms | 🥶 | 256 MB |
| 42 ms |  | 15.8 ms | 19.7 ms | 🥵 | 256 MB |
| 4.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 256 MB |
| 43.9 ms |  | 37.4 ms | 0.1 ms | 🥵 | 256 MB |
| 7 ms |  | 0.4 ms | 0.2 ms | 🥵 | 256 MB |
| 123 ms | 19.5 ms | 0.6 ms | 0.1 ms | 🥶 | 256 MB |
| 96.9 ms | 20.2 ms | 0.6 ms | 0.5 ms | 🥶 | 256 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 256 MB |
| 23.9 ms |  | 16.4 ms | 0.1 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 256 MB |
| 36.9 ms |  | 10.8 ms | 19.9 ms | 🥵 | 256 MB |
| 9.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 256 MB |
| 128 ms | 20.1 ms | 0.5 ms | 0.2 ms | 🥶 | 256 MB |
| 98 ms | 18.3 ms | 0.6 ms | 0.1 ms | 🥶 | 256 MB |
| 101 ms |  |  |  | 🥵 | 256 MB |
| 4.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 13.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 256 MB |
| 92.9 ms | 26.2 ms | 0.6 ms | 3.1 ms | 🥶 | 256 MB |
| 89.9 ms | 25.1 ms | 0.3 ms | 0.1 ms | 🥶 | 256 MB |
| 7.9 ms |  | 1.5 ms | 0.3 ms | 🥵 | 256 MB |
| 25 ms |  | 0.7 ms | 8.7 ms | 🥵 | 256 MB |
| 90.9 ms | 25 ms | 0.5 ms | 0.4 ms | 🥶 | 256 MB |
| 6.9 ms |  | 0.5 ms | 0 ms | 🥵 | 256 MB |
| 105.9 ms | 20 ms | 0.5 ms | 0.1 ms | 🥶 | 256 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 68 ms |  | 60.7 ms | 0.2 ms | 🥵 | 256 MB |
| 4.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.8 ms | 0.2 ms | 🥵 | 256 MB |
| 26 ms |  | 18.5 ms | 0.2 ms | 🥵 | 256 MB |
| 38 ms |  | 32.8 ms | 0.3 ms | 🥵 | 256 MB |
| 40 ms |  | 14.7 ms | 19.8 ms | 🥵 | 256 MB |
| 5.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 256 MB |
| 6 ms |  | 0.5 ms | 0.2 ms | 🥵 | 256 MB |
| 21.9 ms |  | 15.7 ms | 0.2 ms | 🥵 | 256 MB |
| 91 ms | 23.4 ms | 0.3 ms | 0.3 ms | 🥶 | 256 MB |
| 24.9 ms |  | 18.8 ms | 0.1 ms | 🥵 | 256 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 7.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 256 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 95.9 ms | 19.7 ms | 0.5 ms | 0.2 ms | 🥶 | 256 MB |
| 125 ms | 26.2 ms | 0.6 ms | 0.4 ms | 🥶 | 256 MB |
| 90.9 ms | 25 ms | 0.6 ms | 0.3 ms | 🥶 | 256 MB |
| 92 ms | 18.1 ms | 0.6 ms | 0.2 ms | 🥶 | 256 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 23 ms |  | 17 ms | 0 ms | 🥵 | 256 MB |
| 60.9 ms |  | 34.5 ms | 19.7 ms | 🥵 | 256 MB |
| 8 ms |  | 0.4 ms | 0.3 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.6 ms | 0 ms | 🥵 | 256 MB |
| 126.9 ms | 32.4 ms | 0.5 ms | 0.2 ms | 🥶 | 256 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 102.9 ms | 27.1 ms | 0.5 ms | 0.5 ms | 🥶 | 256 MB |
| 24 ms |  | 16.9 ms | 0.1 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 256 MB |
| 10.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 6 ms |  | 0.5 ms | 0.2 ms | 🥵 | 256 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 256 MB |
| 33.9 ms |  | 28.1 ms | 0.3 ms | 🥵 | 256 MB |
| 8 ms |  | 0.3 ms | 0.2 ms | 🥵 | 256 MB |
| 18.9 ms |  | 12.8 ms | 0.2 ms | 🥵 | 256 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 256 MB |
| 23.9 ms |  | 18 ms | 0.2 ms | 🥵 | 256 MB |
| 93.9 ms | 25.3 ms | 0.4 ms | 0.2 ms | 🥶 | 256 MB |
| 5.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 256 MB |
| 88.9 ms | 25 ms | 0.6 ms | 0.4 ms | 🥶 | 256 MB |
| 8.9 ms |  | 0.6 ms | 0.2 ms | 🥵 | 256 MB |
| 24 ms |  | 19.3 ms | 0.2 ms | 🥵 | 256 MB |
| 101 ms | 27.5 ms | 0.6 ms | 0.3 ms | 🥶 | 256 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 22 ms |  | 14.9 ms | 0.2 ms | 🥵 | 256 MB |
| 7 ms |  | 0.3 ms | 0.2 ms | 🥵 | 256 MB |
| 107 ms | 26.8 ms | 0.5 ms | 0.2 ms | 🥶 | 256 MB |
| 105 ms | 28 ms | 0.5 ms | 0.3 ms | 🥶 | 256 MB |
| 98.9 ms | 25.2 ms | 0.7 ms | 0.4 ms | 🥶 | 256 MB |
| 108 ms | 17.1 ms | 0.4 ms | 0.4 ms | 🥶 | 256 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 42 ms |  | 35 ms | 0 ms | 🥵 | 256 MB |
| 5.9 ms |  | 0.2 ms | 0.4 ms | 🥵 | 256 MB |
| 92.9 ms | 19.9 ms | 0.7 ms | 0.4 ms | 🥶 | 256 MB |
| 26.9 ms |  | 21.4 ms | 0.1 ms | 🥵 | 256 MB |
| 79.9 ms | 22.3 ms | 0.4 ms | 0.4 ms | 🥶 | 256 MB |
| 5 ms |  | 0.3 ms | 0 ms | 🥵 | 256 MB |
| 100 ms | 27.2 ms | 0.6 ms | 0.2 ms | 🥶 | 256 MB |
| 38.9 ms |  | 11.9 ms | 20 ms | 🥵 | 256 MB |
| 88.9 ms | 23.8 ms | 0.4 ms | 0.2 ms | 🥶 | 256 MB |
| 29.9 ms |  | 23.1 ms | 0.1 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 256 MB |
| 5.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 256 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 256 MB |
| 177.9 ms | 18.6 ms | 0.5 ms | 0.3 ms | 🥶 | 256 MB |
| 32.9 ms |  | 25.4 ms | 0.2 ms | 🥵 | 256 MB |
| 121 ms | 33.5 ms | 15.7 ms | 0.5 ms | 🥶 | 256 MB |
| 54 ms |  | 40.3 ms | 0.2 ms | 🥵 | 256 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 256 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 95 ms | 18.9 ms | 0.5 ms | 0.4 ms | 🥶 | 256 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.6 ms | 0.3 ms | 🥵 | 256 MB |
| 8.9 ms |  | 0.4 ms | 0.4 ms | 🥵 | 256 MB |
| 9.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 256 MB |
| 111 ms | 23 ms | 0.4 ms | 0.2 ms | 🥶 | 256 MB |
| 91 ms | 22 ms | 0.3 ms | 0.2 ms | 🥶 | 256 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 20 ms |  | 12 ms | 0.2 ms | 🥵 | 256 MB |
| 8 ms |  | 0.6 ms | 0.2 ms | 🥵 | 256 MB |
| 86.9 ms |  | 81.1 ms | 0.3 ms | 🥵 | 256 MB |
| 59 ms |  | 40 ms | 0.2 ms | 🥵 | 256 MB |
| 7.9 ms |  | 3 ms | 0.1 ms | 🥵 | 256 MB |
| 88 ms |  | 81.4 ms | 0 ms | 🥵 | 256 MB |
| 59 ms |  | 40.2 ms | 0.1 ms | 🥵 | 256 MB |
| 39.9 ms |  | 13.3 ms | 19.5 ms | 🥵 | 256 MB |
| 20.9 ms |  | 14 ms | 0.1 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 16.9 ms |  | 10.9 ms | 0.2 ms | 🥵 | 256 MB |
| 23 ms |  | 18.3 ms | 0.1 ms | 🥵 | 256 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 108 ms | 18.6 ms | 0.4 ms | 0.1 ms | 🥶 | 256 MB |
| 101.9 ms | 20.3 ms | 0.6 ms | 0.4 ms | 🥶 | 256 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 27 ms |  | 0.6 ms | 18.8 ms | 🥵 | 256 MB |
| 20.9 ms |  | 13.9 ms | 0.1 ms | 🥵 | 256 MB |
| 95.9 ms | 25.2 ms | 0.5 ms | 0.4 ms | 🥶 | 256 MB |
| 105 ms | 26.8 ms | 0.6 ms | 0.2 ms | 🥶 | 256 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 256 MB |
| 92 ms |  | 84.5 ms | 0.3 ms | 🥵 | 256 MB |
| 13 ms |  | 6.1 ms | 0.1 ms | 🥵 | 256 MB |
| 16 ms |  | 0.5 ms | 0.2 ms | 🥵 | 256 MB |
| 82.9 ms | 17.1 ms | 0.3 ms | 0.1 ms | 🥶 | 256 MB |
| 8 ms |  | 0.5 ms | 0.2 ms | 🥵 | 256 MB |
| 38 ms |  | 9.9 ms | 19.8 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 256 MB |
| 13.9 ms |  | 8.2 ms | 0.2 ms | 🥵 | 256 MB |
| 64 ms |  | 17.3 ms | 39.8 ms | 🥵 | 256 MB |
| 5 ms |  | 0.3 ms | 0.2 ms | 🥵 | 256 MB |
| 52.9 ms |  | 46.6 ms | 0.6 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 41 ms |  | 33.4 ms | 0.2 ms | 🥵 | 256 MB |
| 21 ms |  | 13.2 ms | 0.1 ms | 🥵 | 256 MB |
| 119.9 ms | 23.2 ms | 0.6 ms | 0.3 ms | 🥶 | 256 MB |
| 10 ms |  | 3.7 ms | 0.1 ms | 🥵 | 256 MB |
| 109 ms |  | 80 ms | 19.9 ms | 🥵 | 256 MB |
| 88.9 ms | 23.6 ms | 0.3 ms | 0 ms | 🥶 | 256 MB |
| 106.9 ms | 27.6 ms | 0.5 ms | 0.3 ms | 🥶 | 256 MB |
| 154 ms | 25.4 ms | 0.4 ms | 0.5 ms | 🥶 | 256 MB |
| 27.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 32.9 ms |  | 8 ms | 19.9 ms | 🥵 | 256 MB |
| 95.9 ms | 30.9 ms | 0.4 ms | 0.3 ms | 🥶 | 256 MB |
| 9.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 96.9 ms | 17.9 ms | 0.5 ms | 0.3 ms | 🥶 | 256 MB |
| 91 ms | 18 ms | 0.5 ms | 0.1 ms | 🥶 | 256 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 16.9 ms |  | 10.2 ms | 0.2 ms | 🥵 | 256 MB |
| 80 ms |  | 73.7 ms | 0.1 ms | 🥵 | 256 MB |
| 92 ms | 25.9 ms | 0.5 ms | 0.6 ms | 🥶 | 256 MB |
| 9.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 117 ms | 25 ms | 0.4 ms | 7.1 ms | 🥶 | 256 MB |
| 6 ms |  | 0.4 ms | 0 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 256 MB |
| 103.9 ms | 33.1 ms | 0.7 ms | 0.2 ms | 🥶 | 256 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 25 ms |  | 19.1 ms | 0.7 ms | 🥵 | 256 MB |
| 148 ms | 28.8 ms | 0.5 ms | 0.5 ms | 🥶 | 256 MB |
| 39 ms |  | 32.4 ms | 0.1 ms | 🥵 | 256 MB |
| 111 ms | 24.3 ms | 0.7 ms | 0.3 ms | 🥶 | 256 MB |
| 18 ms |  | 11 ms | 0.1 ms | 🥵 | 256 MB |
| 109.9 ms | 26.4 ms | 0.6 ms | 0.2 ms | 🥶 | 256 MB |
| 18 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 23.9 ms |  | 17.1 ms | 0.2 ms | 🥵 | 256 MB |## Results for 512 MB

| Measurement (512 MB) | Time (ms) |
|-------------|------|
| Average warm start response time | 10 ms |
| Average cold start response time | 116.6 ms |
| Fastest warm response time | 4.9 ms |
| Slowest warm response time | 151.9 ms |
| Fastest cold response time  | 75 ms |
| Slowest cold response time | 310 ms |
  

| Response time | Initialization | Invocation | Overhead | Cold/ Warm Start | Memory Size |
|---------------|----------------|------------|----------|------------------|-------------|
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 512 MB |
| 93.9 ms | 18 ms | 0.3 ms | 0.1 ms | 🥶 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 107 ms | 28.7 ms | 0.6 ms | 0.1 ms | 🥶 | 512 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 8 ms |  | 0.5 ms | 0.1 ms | 🥵 | 512 MB |
| 101 ms | 25.2 ms | 0.6 ms | 1.5 ms | 🥶 | 512 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 92 ms | 22.9 ms | 0.4 ms | 0.2 ms | 🥶 | 512 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 129.9 ms | 31.8 ms | 0.4 ms | 0.2 ms | 🥶 | 512 MB |
| 95 ms | 17.3 ms | 0.4 ms | 0.3 ms | 🥶 | 512 MB |
| 78.9 ms | 24.9 ms | 0.5 ms | 0.3 ms | 🥶 | 512 MB |
| 7.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 512 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 512 MB |
| 98.9 ms | 18.2 ms | 0.6 ms | 0.1 ms | 🥶 | 512 MB |
| 98 ms | 18.9 ms | 0.6 ms | 0.4 ms | 🥶 | 512 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.4 ms | 🥵 | 512 MB |
| 21.9 ms |  | 8.2 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 512 MB |
| 26.9 ms |  | 20.2 ms | 0.1 ms | 🥵 | 512 MB |
| 128 ms | 25.6 ms | 0.7 ms | 0.3 ms | 🥶 | 512 MB |
| 151.9 ms |  | 80 ms | 59.9 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 23.9 ms |  | 18.6 ms | 0.2 ms | 🥵 | 512 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 512 MB |
| 12 ms |  | 4.9 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 512 MB |
| 101.9 ms | 18.5 ms | 0.5 ms | 0.3 ms | 🥶 | 512 MB |
| 20.9 ms |  | 13.3 ms | 0.2 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 16 ms |  | 8.9 ms | 0.2 ms | 🥵 | 512 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 85 ms |  | 79.8 ms | 0.7 ms | 🥵 | 512 MB |
| 12 ms |  | 5.1 ms | 0.1 ms | 🥵 | 512 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 512 MB |
| 98 ms | 17.2 ms | 0.4 ms | 0.1 ms | 🥶 | 512 MB |
| 18.9 ms |  | 13.8 ms | 0.1 ms | 🥵 | 512 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 85 ms |  | 77.7 ms | 0.2 ms | 🥵 | 512 MB |
| 23.9 ms |  | 0.4 ms | 18 ms | 🥵 | 512 MB |
| 33.9 ms |  | 27.7 ms | 0.2 ms | 🥵 | 512 MB |
| 16 ms |  | 10.2 ms | 0 ms | 🥵 | 512 MB |
| 111 ms | 25 ms | 0.7 ms | 0.3 ms | 🥶 | 512 MB |
| 100 ms | 20.3 ms | 0.5 ms | 0.2 ms | 🥶 | 512 MB |
| 53.9 ms |  | 39.9 ms | 0.3 ms | 🥵 | 512 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 512 MB |
| 12 ms |  | 5.3 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 25 ms |  | 18.4 ms | 0.3 ms | 🥵 | 512 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.3 ms | 🥵 | 512 MB |
| 98.9 ms | 25.7 ms | 0.3 ms | 0.3 ms | 🥶 | 512 MB |
| 95 ms | 25 ms | 0.4 ms | 0.1 ms | 🥶 | 512 MB |
| 16.9 ms |  | 10.4 ms | 0.5 ms | 🥵 | 512 MB |
| 23 ms |  | 18.6 ms | 0.1 ms | 🥵 | 512 MB |
| 98 ms | 17.7 ms | 0.6 ms | 0.3 ms | 🥶 | 512 MB |
| 147 ms | 18.6 ms | 0.5 ms | 0.2 ms | 🥶 | 512 MB |
| 5 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 512 MB |
| 24.9 ms |  | 18 ms | 0.2 ms | 🥵 | 512 MB |
| 75 ms | 22 ms | 0.4 ms | 0 ms | 🥶 | 512 MB |
| 118 ms | 28.7 ms | 0.4 ms | 0.2 ms | 🥶 | 512 MB |
| 8 ms |  | 0.3 ms | 0.2 ms | 🥵 | 512 MB |
| 23 ms |  | 15.8 ms | 1.4 ms | 🥵 | 512 MB |
| 105 ms | 19.3 ms | 0.7 ms | 0.2 ms | 🥶 | 512 MB |
| 110 ms | 18.6 ms | 0.9 ms | 0.4 ms | 🥶 | 512 MB |
| 112.9 ms | 19.2 ms | 0.5 ms | 0.2 ms | 🥶 | 512 MB |
| 95.9 ms | 25.4 ms | 0.7 ms | 0.2 ms | 🥶 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 23.9 ms |  | 18.6 ms | 0.1 ms | 🥵 | 512 MB |
| 20 ms |  | 12.5 ms | 0 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 23 ms |  | 16.6 ms | 0.1 ms | 🥵 | 512 MB |
| 27 ms |  | 20.3 ms | 0.2 ms | 🥵 | 512 MB |
| 19.9 ms |  | 13.8 ms | 0.2 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 512 MB |
| 36.9 ms |  | 31.9 ms | 0.2 ms | 🥵 | 512 MB |
| 9 ms |  | 0.3 ms | 0 ms | 🥵 | 512 MB |
| 115 ms | 27.1 ms | 0.4 ms | 0.1 ms | 🥶 | 512 MB |
| 16 ms |  | 0.7 ms | 0.4 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 512 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 512 MB |
| 5 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 9.9 ms |  | 4.1 ms | 0.6 ms | 🥵 | 512 MB |
| 85.9 ms | 18.1 ms | 0.4 ms | 0.2 ms | 🥶 | 512 MB |
| 26 ms |  | 19.9 ms | 0.2 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 512 MB |
| 85.9 ms | 18.4 ms | 0.6 ms | 0.4 ms | 🥶 | 512 MB |
| 85.9 ms | 21.9 ms | 0.5 ms | 0.1 ms | 🥶 | 512 MB |
| 21 ms |  | 14.5 ms | 0.1 ms | 🥵 | 512 MB |
| 7.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 512 MB |
| 95 ms | 18.5 ms | 0.5 ms | 0.1 ms | 🥶 | 512 MB |
| 146.9 ms | 28.7 ms | 0.4 ms | 0.2 ms | 🥶 | 512 MB |
| 98 ms | 26.9 ms | 0.8 ms | 0.2 ms | 🥶 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 13.9 ms |  | 6.9 ms | 0.1 ms | 🥵 | 512 MB |
| 4.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 512 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 42 ms |  | 15.8 ms | 19.7 ms | 🥵 | 512 MB |
| 43.9 ms |  | 37.4 ms | 0.1 ms | 🥵 | 512 MB |
| 123 ms | 19.5 ms | 0.6 ms | 0.1 ms | 🥶 | 512 MB |
| 91 ms | 19.9 ms | 0.4 ms | 0.1 ms | 🥶 | 512 MB |
| 6 ms |  | 0.5 ms | 0 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 512 MB |
| 128 ms | 20.1 ms | 0.5 ms | 0.2 ms | 🥶 | 512 MB |
| 23.9 ms |  | 16.4 ms | 0.1 ms | 🥵 | 512 MB |
| 4.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 9.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 512 MB |
| 13.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 512 MB |
| 101 ms |  |  |  | 🥵 | 512 MB |
| 138 ms | 22.7 ms | 0.5 ms | 0.1 ms | 🥶 | 512 MB |
| 97 ms | 21.3 ms | 0.7 ms | 0.1 ms | 🥶 | 512 MB |
| 89.9 ms | 25.1 ms | 0.3 ms | 0.1 ms | 🥶 | 512 MB |
| 90.9 ms | 25 ms | 0.5 ms | 0.4 ms | 🥶 | 512 MB |
| 6.9 ms |  | 0.5 ms | 0 ms | 🥵 | 512 MB |
| 7.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 512 MB |
| 40 ms |  | 14.7 ms | 19.8 ms | 🥵 | 512 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 5.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 512 MB |
| 7.9 ms |  | 0.4 ms | 0 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.3 ms | 🥵 | 512 MB |
| 38 ms |  | 32.8 ms | 0.3 ms | 🥵 | 512 MB |
| 24.9 ms |  | 18.8 ms | 0.1 ms | 🥵 | 512 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 6 ms |  | 0.5 ms | 0.2 ms | 🥵 | 512 MB |
| 91 ms | 23.4 ms | 0.3 ms | 0.3 ms | 🥶 | 512 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 125 ms | 26.2 ms | 0.6 ms | 0.4 ms | 🥶 | 512 MB |
| 90.9 ms | 25 ms | 0.6 ms | 0.3 ms | 🥶 | 512 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 512 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 11 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 95.9 ms | 19.7 ms | 0.5 ms | 0.2 ms | 🥶 | 512 MB |
| 8 ms |  | 0.4 ms | 0.3 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.6 ms | 0 ms | 🥵 | 512 MB |
| 126.9 ms | 32.4 ms | 0.5 ms | 0.2 ms | 🥶 | 512 MB |
| 102.9 ms | 23.2 ms | 0.7 ms | 0.1 ms | 🥶 | 512 MB |
| 24 ms |  | 16.9 ms | 0.1 ms | 🥵 | 512 MB |
| 10.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 6 ms |  | 0.5 ms | 0.2 ms | 🥵 | 512 MB |
| 8.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 18 ms |  | 10 ms | 0.4 ms | 🥵 | 512 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 33.9 ms |  | 28.1 ms | 0.3 ms | 🥵 | 512 MB |
| 93.9 ms | 25.3 ms | 0.4 ms | 0.2 ms | 🥶 | 512 MB |
| 16 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 88.9 ms | 25 ms | 0.6 ms | 0.4 ms | 🥶 | 512 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 23.9 ms |  | 18 ms | 0.2 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 512 MB |
| 5.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 512 MB |
| 101 ms | 27.5 ms | 0.6 ms | 0.3 ms | 🥶 | 512 MB |
| 4.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 16 ms |  | 10.2 ms | 0.2 ms | 🥵 | 512 MB |
| 42 ms |  | 35 ms | 0 ms | 🥵 | 512 MB |
| 99.9 ms | 23.5 ms | 0.6 ms | 0.4 ms | 🥶 | 512 MB |
| 5.9 ms |  | 0.2 ms | 0.4 ms | 🥵 | 512 MB |
| 107 ms | 26.8 ms | 0.5 ms | 0.2 ms | 🥶 | 512 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 512 MB |
| 21.9 ms |  | 14.2 ms | 0.4 ms | 🥵 | 512 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 512 MB |
| 14 ms |  | 7.3 ms | 0.2 ms | 🥵 | 512 MB |
| 88.9 ms | 23.8 ms | 0.4 ms | 0.2 ms | 🥶 | 512 MB |
| 98 ms | 25.8 ms | 0.8 ms | 0.3 ms | 🥶 | 512 MB |
| 7.9 ms |  | 3.4 ms | 0.2 ms | 🥵 | 512 MB |
| 100 ms | 27.2 ms | 0.6 ms | 0.2 ms | 🥶 | 512 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 512 MB |
| 38.9 ms |  | 11.9 ms | 20 ms | 🥵 | 512 MB |
| 101.9 ms | 22.9 ms | 0.5 ms | 0.1 ms | 🥶 | 512 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 121 ms | 33.5 ms | 15.7 ms | 0.5 ms | 🥶 | 512 MB |
| 177.9 ms | 18.6 ms | 0.5 ms | 0.3 ms | 🥶 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 512 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 21.9 ms |  | 15.7 ms | 0.2 ms | 🥵 | 512 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.6 ms | 0.3 ms | 🥵 | 512 MB |
| 9.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 512 MB |
| 118.9 ms | 26.7 ms | 0.4 ms | 0.3 ms | 🥶 | 512 MB |
| 91 ms | 22 ms | 0.3 ms | 0.2 ms | 🥶 | 512 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 59 ms |  | 40.2 ms | 0.1 ms | 🥵 | 512 MB |
| 5.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 512 MB |
| 7 ms |  | 0.3 ms | 0 ms | 🥵 | 512 MB |
| 86.9 ms |  | 81.1 ms | 0.3 ms | 🥵 | 512 MB |
| 7.9 ms |  | 3 ms | 0.1 ms | 🥵 | 512 MB |
| 97.9 ms | 18.4 ms | 0.5 ms | 0.1 ms | 🥶 | 512 MB |
| 88 ms |  | 81.4 ms | 0 ms | 🥵 | 512 MB |
| 11.9 ms |  | 4.5 ms | 0.2 ms | 🥵 | 512 MB |
| 20.9 ms |  | 14 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 39.9 ms |  | 13.3 ms | 19.5 ms | 🥵 | 512 MB |
| 23 ms |  | 18.3 ms | 0.1 ms | 🥵 | 512 MB |
| 9.9 ms |  | 3.2 ms | 0.1 ms | 🥵 | 512 MB |
| 108 ms | 18.6 ms | 0.4 ms | 0.1 ms | 🥶 | 512 MB |
| 16 ms |  | 0.8 ms | 0.2 ms | 🥵 | 512 MB |
| 16.9 ms |  | 10.9 ms | 0.2 ms | 🥵 | 512 MB |
| 7.9 ms |  | 1.8 ms | 0.1 ms | 🥵 | 512 MB |
| 20.9 ms |  | 13.9 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 512 MB |
| 82.9 ms | 17.1 ms | 0.3 ms | 0.1 ms | 🥶 | 512 MB |
| 133 ms | 18.4 ms | 0.4 ms | 0.2 ms | 🥶 | 512 MB |
| 8 ms |  | 0.5 ms | 0.2 ms | 🥵 | 512 MB |
| 92 ms |  | 84.5 ms | 0.3 ms | 🥵 | 512 MB |
| 16 ms |  | 0.5 ms | 0.2 ms | 🥵 | 512 MB |
| 16.9 ms |  | 9.3 ms | 0.1 ms | 🥵 | 512 MB |
| 5 ms |  | 0.3 ms | 0.2 ms | 🥵 | 512 MB |
| 109 ms |  | 80 ms | 19.9 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 9 ms |  | 0.3 ms | 0 ms | 🥵 | 512 MB |
| 119.9 ms | 23.2 ms | 0.6 ms | 0.3 ms | 🥶 | 512 MB |
| 91 ms | 18 ms | 0.5 ms | 0.1 ms | 🥶 | 512 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 16.9 ms |  | 10.2 ms | 0.2 ms | 🥵 | 512 MB |
| 92 ms | 25.9 ms | 0.5 ms | 0.6 ms | 🥶 | 512 MB |
| 25 ms |  | 19.1 ms | 0.7 ms | 🥵 | 512 MB |
| 88 ms | 28.7 ms | 0.5 ms | 0.3 ms | 🥶 | 512 MB |
| 9.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 512 MB |
| 8.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 103.9 ms | 19.6 ms | 0.9 ms | 0.6 ms | 🥶 | 512 MB |
| 23.9 ms |  | 17.1 ms | 0.2 ms | 🥵 | 512 MB |
| 18 ms |  | 11 ms | 0.1 ms | 🥵 | 512 MB |
| 103.9 ms | 33.1 ms | 0.7 ms | 0.2 ms | 🥶 | 512 MB |
| 85 ms | 22.6 ms | 0.4 ms | 0.1 ms | 🥶 | 512 MB |
| 26 ms |  | 17.5 ms | 0.1 ms | 🥵 | 512 MB |
| 99.9 ms | 19.8 ms | 0.5 ms | 0.2 ms | 🥶 | 512 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 7 ms |  | 0.6 ms | 0.3 ms | 🥵 | 512 MB |
| 110.9 ms | 19.7 ms | 0.5 ms | 0.2 ms | 🥶 | 512 MB |
| 8.9 ms |  | 0.4 ms | 0 ms | 🥵 | 512 MB |
| 29 ms |  | 0.4 ms | 0.2 ms | 🥵 | 512 MB |
| 19 ms |  | 0.6 ms | 0.2 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 99.9 ms | 26.2 ms | 0.3 ms | 0.3 ms | 🥶 | 512 MB |
| 6.9 ms |  |  |  | 🥵 | 512 MB |
| 95.9 ms | 24.6 ms | 0.7 ms | 0.2 ms | 🥶 | 512 MB |
| 6 ms |  | 0.3 ms | 0.3 ms | 🥵 | 512 MB |
| 14 ms |  | 6.2 ms | 0.1 ms | 🥵 | 512 MB |
| 99.9 ms | 31.7 ms | 0.5 ms | 0.1 ms | 🥶 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 512 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 512 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 4.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 25 ms |  | 18 ms | 0.1 ms | 🥵 | 512 MB |
| 105 ms | 27.2 ms | 0.3 ms | 0.1 ms | 🥶 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 512 MB |
| 5 ms |  | 0.4 ms | 0 ms | 🥵 | 512 MB |
| 9.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 19 ms |  | 12.3 ms | 0.1 ms | 🥵 | 512 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 23 ms |  | 15.1 ms | 0 ms | 🥵 | 512 MB |
| 54.9 ms |  | 48.5 ms | 0.3 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 512 MB |
| 6.9 ms |  | 2.8 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 512 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 13.9 ms |  | 9.4 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 105 ms | 28.2 ms | 0.5 ms | 0.2 ms | 🥶 | 512 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 512 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 9 ms |  | 3 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 4.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 512 MB |
| 101 ms | 17.4 ms | 0.5 ms | 0.2 ms | 🥶 | 512 MB |
| 103 ms | 18.3 ms | 0.6 ms | 0.3 ms | 🥶 | 512 MB |
| 50.9 ms |  | 0.5 ms | 39.5 ms | 🥵 | 512 MB |
| 11.9 ms |  | 6.6 ms | 0.1 ms | 🥵 | 512 MB |
| 7.9 ms |  | 0.7 ms | 0.2 ms | 🥵 | 512 MB |
| 94 ms | 27.4 ms | 0.5 ms | 0.1 ms | 🥶 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 512 MB |
| 96.9 ms | 26.2 ms | 0.6 ms | 0.1 ms | 🥶 | 512 MB |
| 44 ms |  | 36.3 ms | 0.2 ms | 🥵 | 512 MB |
| 8 ms |  | 0.5 ms | 0.4 ms | 🥵 | 512 MB |
| 18.9 ms |  | 11.5 ms | 0.3 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 512 MB |
| 13.9 ms |  | 7.1 ms | 0.1 ms | 🥵 | 512 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.5 ms | 🥵 | 512 MB |
| 23 ms |  | 18.4 ms | 0.2 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 14 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 78.9 ms | 17.9 ms | 0.5 ms | 0.1 ms | 🥶 | 512 MB |
| 117 ms |  | 91.5 ms | 19.7 ms | 🥵 | 512 MB |
| 17.9 ms |  | 5.7 ms | 0.2 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 512 MB |
| 94 ms | 18.2 ms | 0.9 ms | 0.3 ms | 🥶 | 512 MB |
| 7.9 ms |  | 0.6 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 512 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 99.9 ms | 28.5 ms | 0.4 ms | 0.2 ms | 🥶 | 512 MB |
| 113.9 ms | 22.3 ms | 0.5 ms | 0.2 ms | 🥶 | 512 MB |
| 97 ms | 26.4 ms | 0.4 ms | 0.1 ms | 🥶 | 512 MB |
| 99.9 ms | 29.8 ms | 0.4 ms | 0.2 ms | 🥶 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 67 ms |  | 20.2 ms | 39.6 ms | 🥵 | 512 MB |
| 11.9 ms |  | 4.2 ms | 0.2 ms | 🥵 | 512 MB |
| 23 ms |  | 0.5 ms | 17.3 ms | 🥵 | 512 MB |
| 100.9 ms | 30.2 ms | 0.4 ms | 0.4 ms | 🥶 | 512 MB |
| 22 ms |  | 15.3 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 279 ms | 27.9 ms | 0.4 ms | 0.1 ms | 🥶 | 512 MB |
| 45 ms |  | 39.7 ms | 0.1 ms | 🥵 | 512 MB |
| 21.9 ms |  | 10.5 ms | 0.1 ms | 🥵 | 512 MB |
| 128 ms | 22.3 ms | 0.6 ms | 0.2 ms | 🥶 | 512 MB |
| 36.9 ms |  | 30.9 ms | 0.2 ms | 🥵 | 512 MB |
| 26.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 512 MB |
| 7.9 ms |  | 1.7 ms | 0.3 ms | 🥵 | 512 MB |
| 76.9 ms |  |  |  | 🥵 | 512 MB |
| 101 ms | 19.2 ms | 0.7 ms | 0.4 ms | 🥶 | 512 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 98 ms | 18.7 ms | 0.5 ms | 0.1 ms | 🥶 | 512 MB |
| 13 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 23.9 ms |  | 18.1 ms | 0.4 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 512 MB |
| 112.9 ms | 25 ms | 0.8 ms | 0.2 ms | 🥶 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 26.9 ms |  | 19.6 ms | 0.1 ms | 🥵 | 512 MB |
| 38 ms |  | 32.5 ms | 0.3 ms | 🥵 | 512 MB |
| 6 ms |  | 1.1 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 13.9 ms |  | 8.6 ms | 0.1 ms | 🥵 | 512 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 107 ms | 25.8 ms | 0.6 ms | 0.1 ms | 🥶 | 512 MB |
| 82.9 ms | 21.9 ms | 0.6 ms | 0.4 ms | 🥶 | 512 MB |
| 6.9 ms |  | 1.5 ms | 0 ms | 🥵 | 512 MB |
| 8 ms |  | 0.5 ms | 0.1 ms | 🥵 | 512 MB |
| 115 ms | 20.6 ms | 0.9 ms | 14.6 ms | 🥶 | 512 MB |
| 104 ms | 21.5 ms | 0.6 ms | 0.2 ms | 🥶 | 512 MB |
| 9.9 ms |  | 2.9 ms | 0.8 ms | 🥵 | 512 MB |
| 24.9 ms |  | 19.1 ms | 0.2 ms | 🥵 | 512 MB |
| 23.9 ms |  | 17.1 ms | 0.1 ms | 🥵 | 512 MB |
| 36.9 ms |  | 28.5 ms | 0.2 ms | 🥵 | 512 MB |
| 16.9 ms |  | 9.9 ms | 0.2 ms | 🥵 | 512 MB |
| 115.9 ms | 18.7 ms | 0.5 ms | 0.3 ms | 🥶 | 512 MB |
| 9 ms |  | 3.4 ms | 0.1 ms | 🥵 | 512 MB |
| 101.9 ms | 18.8 ms | 0.5 ms | 0.3 ms | 🥶 | 512 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 512 MB |
| 120 ms | 20.6 ms | 0.5 ms | 0.3 ms | 🥶 | 512 MB |
| 5 ms |  | 0.3 ms | 0 ms | 🥵 | 512 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 7.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 512 MB |
| 21 ms |  | 14.3 ms | 0.1 ms | 🥵 | 512 MB |
| 96.9 ms | 26.1 ms | 0.5 ms | 0.3 ms | 🥶 | 512 MB |
| 99.9 ms | 27.3 ms | 0.4 ms | 0.1 ms | 🥶 | 512 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 7.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 512 MB |
| 59.9 ms |  | 33.6 ms | 19.9 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 107 ms | 20 ms | 0.8 ms | 0.1 ms | 🥶 | 512 MB |
| 36.9 ms |  | 29.6 ms | 0.2 ms | 🥵 | 512 MB |
| 105 ms | 28.8 ms | 0.4 ms | 0.3 ms | 🥶 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 30.9 ms |  | 24.4 ms | 0.3 ms | 🥵 | 512 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 88 ms | 26.4 ms | 0.5 ms | 0.2 ms | 🥶 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.3 ms | 🥵 | 512 MB |
| 17.9 ms |  | 9.1 ms | 0.2 ms | 🥵 | 512 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 7 ms |  | 0.4 ms | 0.2 ms | 🥵 | 512 MB |
| 96.9 ms | 20.2 ms | 0.6 ms | 0.5 ms | 🥶 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 18 ms |  | 0.3 ms | 0.2 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 512 MB |
| 36.9 ms |  | 10.8 ms | 19.9 ms | 🥵 | 512 MB |
| 7.9 ms |  | 0.5 ms | 0.4 ms | 🥵 | 512 MB |
| 102.9 ms | 19.2 ms | 0.6 ms | 0.3 ms | 🥶 | 512 MB |
| 98 ms | 18.3 ms | 0.6 ms | 0.1 ms | 🥶 | 512 MB |
| 92.9 ms | 26.2 ms | 0.6 ms | 3.1 ms | 🥶 | 512 MB |
| 21 ms |  | 15.2 ms | 0.2 ms | 🥵 | 512 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 512 MB |
| 10.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 512 MB |
| 108.9 ms | 27.8 ms | 0.5 ms | 0.4 ms | 🥶 | 512 MB |
| 7.9 ms |  | 1.5 ms | 0.3 ms | 🥵 | 512 MB |
| 105.9 ms | 20 ms | 0.5 ms | 0.1 ms | 🥶 | 512 MB |
| 25 ms |  | 0.7 ms | 8.7 ms | 🥵 | 512 MB |
| 4.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.8 ms | 0.2 ms | 🥵 | 512 MB |
| 26 ms |  | 18.5 ms | 0.2 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 512 MB |
| 68 ms |  | 60.7 ms | 0.2 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 92 ms | 18.1 ms | 0.6 ms | 0.2 ms | 🥶 | 512 MB |
| 21.9 ms |  | 15.7 ms | 0.2 ms | 🥵 | 512 MB |
| 19.9 ms |  | 12.6 ms | 0.3 ms | 🥵 | 512 MB |
| 23 ms |  | 17 ms | 0 ms | 🥵 | 512 MB |
| 7.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 60.9 ms |  | 34.5 ms | 19.7 ms | 🥵 | 512 MB |
| 102.9 ms | 27.1 ms | 0.5 ms | 0.5 ms | 🥶 | 512 MB |
| 5.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 512 MB |
| 8 ms |  | 0.3 ms | 0.2 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 512 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 512 MB |
| 8 ms |  | 0.6 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 512 MB |
| 97.9 ms | 27.6 ms | 0.5 ms | 0.4 ms | 🥶 | 512 MB |
| 18.9 ms |  | 12.8 ms | 0.2 ms | 🥵 | 512 MB |
| 24 ms |  | 19.3 ms | 0.2 ms | 🥵 | 512 MB |
| 8.9 ms |  | 0.6 ms | 0.2 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 512 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 512 MB |
| 22 ms |  | 14.9 ms | 0.2 ms | 🥵 | 512 MB |
| 7 ms |  | 0.3 ms | 0.2 ms | 🥵 | 512 MB |
| 23 ms |  | 16.2 ms | 0.2 ms | 🥵 | 512 MB |
| 129.9 ms | 25.2 ms | 0.9 ms | 0.2 ms | 🥶 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 105 ms | 28 ms | 0.5 ms | 0.3 ms | 🥶 | 512 MB |
| 98.9 ms | 25.2 ms | 0.7 ms | 0.4 ms | 🥶 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 512 MB |
| 15 ms |  | 8.8 ms | 0.1 ms | 🥵 | 512 MB |
| 98 ms | 19.3 ms | 0.5 ms | 0.2 ms | 🥶 | 512 MB |
| 108 ms | 17.1 ms | 0.4 ms | 0.4 ms | 🥶 | 512 MB |
| 92.9 ms | 19.9 ms | 0.7 ms | 0.4 ms | 🥶 | 512 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 26.9 ms |  | 21.4 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 512 MB |
| 79.9 ms | 22.3 ms | 0.4 ms | 0.4 ms | 🥶 | 512 MB |
| 21.9 ms |  | 15.4 ms | 0.1 ms | 🥵 | 512 MB |
| 29.9 ms |  | 23.1 ms | 0.1 ms | 🥵 | 512 MB |
| 99.9 ms | 27.1 ms | 0.7 ms | 0.2 ms | 🥶 | 512 MB |
| 310 ms | 18.5 ms | 0.5 ms | 0.3 ms | 🥶 | 512 MB |
| 5 ms |  | 0.3 ms | 0 ms | 🥵 | 512 MB |
| 5.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 512 MB |
| 54 ms |  | 40.3 ms | 0.2 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 32.9 ms |  | 25.4 ms | 0.2 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 512 MB |
| 9.9 ms |  | 4 ms | 0.1 ms | 🥵 | 512 MB |
| 16.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 95 ms | 18.9 ms | 0.5 ms | 0.4 ms | 🥶 | 512 MB |
| 8.9 ms |  | 0.4 ms | 0.4 ms | 🥵 | 512 MB |
| 111 ms | 23 ms | 0.4 ms | 0.2 ms | 🥶 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 93.9 ms | 17.9 ms | 0.6 ms | 0.3 ms | 🥶 | 512 MB |
| 92.9 ms | 22.3 ms | 0.4 ms | 0.1 ms | 🥶 | 512 MB |
| 20 ms |  | 12 ms | 0.2 ms | 🥵 | 512 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 8 ms |  | 0.6 ms | 0.2 ms | 🥵 | 512 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 59 ms |  | 40 ms | 0.2 ms | 🥵 | 512 MB |
| 101.9 ms | 20.3 ms | 0.6 ms | 0.4 ms | 🥶 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 27 ms |  | 0.6 ms | 18.8 ms | 🥵 | 512 MB |
| 13 ms |  | 6.1 ms | 0.1 ms | 🥵 | 512 MB |
| 95.9 ms | 25.2 ms | 0.5 ms | 0.4 ms | 🥶 | 512 MB |
| 105 ms | 26.8 ms | 0.6 ms | 0.2 ms | 🥶 | 512 MB |
| 38 ms |  | 9.9 ms | 19.8 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 512 MB |
| 52.9 ms |  | 46.6 ms | 0.6 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 512 MB |
| 97 ms | 31.8 ms | 0.4 ms | 0.2 ms | 🥶 | 512 MB |
| 8 ms |  | 0.6 ms | 0.3 ms | 🥵 | 512 MB |
| 13.9 ms |  | 8.2 ms | 0.2 ms | 🥵 | 512 MB |
| 64 ms |  | 17.3 ms | 39.8 ms | 🥵 | 512 MB |
| 5 ms |  | 0.2 ms | 0.2 ms | 🥵 | 512 MB |
| 88.9 ms | 23.6 ms | 0.3 ms | 0 ms | 🥶 | 512 MB |
| 41 ms |  | 33.4 ms | 0.2 ms | 🥵 | 512 MB |
| 21 ms |  | 13.2 ms | 0.1 ms | 🥵 | 512 MB |
| 10 ms |  | 3.7 ms | 0.1 ms | 🥵 | 512 MB |
| 154 ms | 25.4 ms | 0.4 ms | 0.5 ms | 🥶 | 512 MB |
| 95.9 ms | 30.9 ms | 0.4 ms | 0.3 ms | 🥶 | 512 MB |
| 106.9 ms | 27.6 ms | 0.5 ms | 0.3 ms | 🥶 | 512 MB |
| 96.9 ms | 17.9 ms | 0.5 ms | 0.3 ms | 🥶 | 512 MB |
| 27.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 32.9 ms |  | 8 ms | 19.9 ms | 🥵 | 512 MB |
| 9.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 80 ms |  | 73.7 ms | 0.1 ms | 🥵 | 512 MB |
| 7.9 ms |  | 0.3 ms | 0 ms | 🥵 | 512 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 117 ms | 25 ms | 0.4 ms | 7.1 ms | 🥶 | 512 MB |
| 39 ms |  | 32.4 ms | 0.1 ms | 🥵 | 512 MB |
| 6 ms |  | 0.4 ms | 0 ms | 🥵 | 512 MB |
| 13 ms |  | 5.8 ms | 0.5 ms | 🥵 | 512 MB |
| 90 ms | 23.5 ms | 0.5 ms | 0.4 ms | 🥶 | 512 MB |
| 5 ms |  | 0.3 ms | 0 ms | 🥵 | 512 MB |
| 111 ms | 24.3 ms | 0.7 ms | 0.3 ms | 🥶 | 512 MB |
| 103 ms | 29.9 ms | 0.5 ms | 0.1 ms | 🥶 | 512 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 109.9 ms | 26.4 ms | 0.6 ms | 0.2 ms | 🥶 | 512 MB |
| 89.9 ms | 18.1 ms | 0.4 ms | 0.2 ms | 🥶 | 512 MB |
| 18 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 148 ms | 28.8 ms | 0.5 ms | 0.5 ms | 🥶 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 109.9 ms | 18.4 ms | 0.4 ms | 0.1 ms | 🥶 | 512 MB |## Results for 1024 MB

| Measurement (1024 MB) | Time (ms) |
|-------------|------|
| Average warm start response time | 14.4 ms |
| Average cold start response time | 114.3 ms |
| Fastest warm response time | 4.9 ms |
| Slowest warm response time | 151.9 ms |
| Fastest cold response time  | 75 ms |
| Slowest cold response time | 310 ms |
  

| Response time | Initialization | Invocation | Overhead | Cold/ Warm Start | Memory Size |
|---------------|----------------|------------|----------|------------------|-------------|
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 93.9 ms | 18 ms | 0.3 ms | 0.1 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 94.9 ms | 31.5 ms | 0.7 ms | 0.2 ms | 🥶 | 1024 MB |
| 107 ms | 28.7 ms | 0.6 ms | 0.1 ms | 🥶 | 1024 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.5 ms | 0.1 ms | 🥵 | 1024 MB |
| 7 ms |  | 0.4 ms | 0 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 101 ms | 25.2 ms | 0.6 ms | 1.5 ms | 🥶 | 1024 MB |
| 6 ms |  | 0.5 ms | 0 ms | 🥵 | 1024 MB |
| 92 ms | 22.9 ms | 0.4 ms | 0.2 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 1024 MB |
| 129.9 ms | 31.8 ms | 0.4 ms | 0.2 ms | 🥶 | 1024 MB |
| 95 ms | 17.3 ms | 0.4 ms | 0.3 ms | 🥶 | 1024 MB |
| 78.9 ms | 24.9 ms | 0.5 ms | 0.3 ms | 🥶 | 1024 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 1024 MB |
| 98 ms | 18.9 ms | 0.6 ms | 0.4 ms | 🥶 | 1024 MB |
| 7.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 1024 MB |
| 98.9 ms | 18.2 ms | 0.6 ms | 0.1 ms | 🥶 | 1024 MB |
| 91 ms | 26.9 ms | 0.6 ms | 0.4 ms | 🥶 | 1024 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 1024 MB |
| 21.9 ms |  | 8.2 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.4 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 1024 MB |
| 26.9 ms |  | 20.2 ms | 0.1 ms | 🥵 | 1024 MB |
| 128 ms | 25.6 ms | 0.7 ms | 0.3 ms | 🥶 | 1024 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 23.9 ms |  | 18.6 ms | 0.2 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 151.9 ms |  | 80 ms | 59.9 ms | 🥵 | 1024 MB |
| 12 ms |  | 4.9 ms | 0.1 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 1024 MB |
| 20.9 ms |  | 13.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 97 ms | 32 ms | 0.4 ms | 0.7 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 101.9 ms | 18.5 ms | 0.5 ms | 0.3 ms | 🥶 | 1024 MB |
| 6 ms |  | 0.5 ms | 0.2 ms | 🥵 | 1024 MB |
| 16 ms |  | 8.9 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 1024 MB |
| 98 ms | 17.2 ms | 0.4 ms | 0.1 ms | 🥶 | 1024 MB |
| 88 ms | 22.5 ms | 0.6 ms | 0.1 ms | 🥶 | 1024 MB |
| 85 ms |  | 79.8 ms | 0.7 ms | 🥵 | 1024 MB |
| 18.9 ms |  | 13.8 ms | 0.1 ms | 🥵 | 1024 MB |
| 23.9 ms |  | 0.4 ms | 18 ms | 🥵 | 1024 MB |
| 12 ms |  | 5.1 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 1024 MB |
| 108 ms | 24.5 ms | 0.5 ms | 0.1 ms | 🥶 | 1024 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 85 ms |  | 77.7 ms | 0.2 ms | 🥵 | 1024 MB |
| 33.9 ms |  | 27.7 ms | 0.2 ms | 🥵 | 1024 MB |
| 89.9 ms | 21.6 ms | 0.6 ms | 0.1 ms | 🥶 | 1024 MB |
| 16 ms |  | 10.2 ms | 0 ms | 🥵 | 1024 MB |
| 111 ms | 25 ms | 0.7 ms | 0.3 ms | 🥶 | 1024 MB |
| 100 ms | 20.3 ms | 0.5 ms | 0.2 ms | 🥶 | 1024 MB |
| 53.9 ms |  | 39.9 ms | 0.3 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 12 ms |  | 5.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 25 ms |  | 18.4 ms | 0.3 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 1024 MB |
| 98.9 ms | 25.7 ms | 0.3 ms | 0.3 ms | 🥶 | 1024 MB |
| 95 ms | 25 ms | 0.4 ms | 0.1 ms | 🥶 | 1024 MB |
| 5.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 23 ms |  | 18.6 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.3 ms | 🥵 | 1024 MB |
| 98 ms | 17.7 ms | 0.6 ms | 0.3 ms | 🥶 | 1024 MB |
| 116.9 ms | 18.7 ms | 0.5 ms | 0 ms | 🥶 | 1024 MB |
| 16.9 ms |  | 10.4 ms | 0.5 ms | 🥵 | 1024 MB |
| 108 ms | 32.5 ms | 0.5 ms | 0.5 ms | 🥶 | 1024 MB |
| 96 ms | 29.8 ms | 0.5 ms | 0.4 ms | 🥶 | 1024 MB |
| 84 ms | 18.7 ms | 0.4 ms | 0.2 ms | 🥶 | 1024 MB |
| 97 ms | 27.4 ms | 0.4 ms | 0.3 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 1024 MB |
| 105.9 ms | 30.4 ms | 0.7 ms | 0.2 ms | 🥶 | 1024 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 5 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 108.9 ms | 24.5 ms | 0.7 ms | 0.2 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.4 ms | 0.3 ms | 🥵 | 1024 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 118 ms | 28.7 ms | 0.4 ms | 0.2 ms | 🥶 | 1024 MB |
| 147 ms | 18.6 ms | 0.5 ms | 0.2 ms | 🥶 | 1024 MB |
| 8 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 24.9 ms |  | 18 ms | 0.2 ms | 🥵 | 1024 MB |
| 75 ms | 22 ms | 0.4 ms | 0 ms | 🥶 | 1024 MB |
| 23 ms |  | 15.8 ms | 1.4 ms | 🥵 | 1024 MB |
| 108 ms | 30.5 ms | 0.4 ms | 0.2 ms | 🥶 | 1024 MB |
| 105 ms | 19.3 ms | 0.7 ms | 0.2 ms | 🥶 | 1024 MB |
| 97 ms | 27.9 ms | 0.5 ms | 0.2 ms | 🥶 | 1024 MB |
| 110 ms | 18.6 ms | 0.9 ms | 0.4 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 112.9 ms | 19.2 ms | 0.5 ms | 0.2 ms | 🥶 | 1024 MB |
| 95.9 ms | 25.4 ms | 0.7 ms | 0.2 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.6 ms | 0.2 ms | 🥵 | 1024 MB |
| 23.9 ms |  | 18.6 ms | 0.1 ms | 🥵 | 1024 MB |
| 20 ms |  | 12.5 ms | 0 ms | 🥵 | 1024 MB |
| 23 ms |  | 16.6 ms | 0.1 ms | 🥵 | 1024 MB |
| 27 ms |  | 20.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 1024 MB |
| 36.9 ms |  | 31.9 ms | 0.2 ms | 🥵 | 1024 MB |
| 19.9 ms |  | 13.8 ms | 0.2 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 115 ms | 27.1 ms | 0.4 ms | 0.1 ms | 🥶 | 1024 MB |
| 9 ms |  | 0.3 ms | 0 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 9.9 ms |  | 4.1 ms | 0.6 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 1024 MB |
| 16 ms |  | 0.7 ms | 0.4 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 85.9 ms | 18.4 ms | 0.6 ms | 0.4 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 85.9 ms | 18.1 ms | 0.4 ms | 0.2 ms | 🥶 | 1024 MB |
| 9 ms |  | 0.3 ms | 0.3 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 5 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 85.9 ms | 21.9 ms | 0.5 ms | 0.1 ms | 🥶 | 1024 MB |
| 7.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 1024 MB |
| 95 ms | 18.5 ms | 0.5 ms | 0.1 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 1024 MB |
| 26 ms |  | 19.9 ms | 0.2 ms | 🥵 | 1024 MB |
| 146.9 ms | 28.7 ms | 0.4 ms | 0.2 ms | 🥶 | 1024 MB |
| 21 ms |  | 14.5 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 13.9 ms |  | 6.9 ms | 0.1 ms | 🥵 | 1024 MB |
| 98 ms | 26.9 ms | 0.8 ms | 0.2 ms | 🥶 | 1024 MB |
| 91 ms | 19.9 ms | 0.4 ms | 0.1 ms | 🥶 | 1024 MB |
| 83 ms | 20 ms | 0.7 ms | 0.4 ms | 🥶 | 1024 MB |
| 4.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 42 ms |  | 15.8 ms | 19.7 ms | 🥵 | 1024 MB |
| 43.9 ms |  | 37.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 123 ms | 19.5 ms | 0.6 ms | 0.1 ms | 🥶 | 1024 MB |
| 6 ms |  | 0.5 ms | 0.1 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.5 ms | 0 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 23.9 ms |  | 16.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 4.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 1024 MB |
| 9.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 128 ms | 20.1 ms | 0.5 ms | 0.2 ms | 🥶 | 1024 MB |
| 101 ms |  |  |  | 🥵 | 1024 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 13.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 1024 MB |
| 100.9 ms | 29.9 ms | 0.6 ms | 0.3 ms | 🥶 | 1024 MB |
| 97 ms | 21.3 ms | 0.7 ms | 0.1 ms | 🥶 | 1024 MB |
| 95.9 ms | 22.2 ms | 0.8 ms | 0.2 ms | 🥶 | 1024 MB |
| 89.9 ms | 25.1 ms | 0.3 ms | 0.1 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.5 ms | 0 ms | 🥵 | 1024 MB |
| 138 ms | 22.7 ms | 0.5 ms | 0.1 ms | 🥶 | 1024 MB |
| 101.9 ms | 25 ms | 0.5 ms | 0.1 ms | 🥶 | 1024 MB |
| 90.9 ms | 25 ms | 0.5 ms | 0.4 ms | 🥶 | 1024 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.4 ms | 0 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.4 ms | 0 ms | 🥵 | 1024 MB |
| 5.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.3 ms | 🥵 | 1024 MB |
| 38 ms |  | 32.8 ms | 0.3 ms | 🥵 | 1024 MB |
| 40 ms |  | 14.7 ms | 19.8 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.5 ms | 0.2 ms | 🥵 | 1024 MB |
| 91 ms | 23.4 ms | 0.3 ms | 0.3 ms | 🥶 | 1024 MB |
| 24.9 ms |  | 18.8 ms | 0.1 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 119 ms | 20.2 ms | 0.5 ms | 0.2 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 95.9 ms | 19.7 ms | 0.5 ms | 0.2 ms | 🥶 | 1024 MB |
| 90.9 ms | 25 ms | 0.6 ms | 0.3 ms | 🥶 | 1024 MB |
| 125 ms | 26.2 ms | 0.6 ms | 0.4 ms | 🥶 | 1024 MB |
| 94 ms | 18.6 ms | 0.6 ms | 0 ms | 🥶 | 1024 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 13.9 ms |  | 0.8 ms | 0.5 ms | 🥵 | 1024 MB |
| 11 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.4 ms | 0.3 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.6 ms | 0 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 126.9 ms | 32.4 ms | 0.5 ms | 0.2 ms | 🥶 | 1024 MB |
| 102.9 ms | 23.2 ms | 0.7 ms | 0.1 ms | 🥶 | 1024 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 1024 MB |
| 10.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.5 ms | 0.2 ms | 🥵 | 1024 MB |
| 18 ms |  | 10 ms | 0.4 ms | 🥵 | 1024 MB |
| 11 ms |  | 5.5 ms | 0.2 ms | 🥵 | 1024 MB |
| 24 ms |  | 16.9 ms | 0.1 ms | 🥵 | 1024 MB |
| 33.9 ms |  | 28.1 ms | 0.3 ms | 🥵 | 1024 MB |
| 93.9 ms | 25.3 ms | 0.4 ms | 0.2 ms | 🥶 | 1024 MB |
| 16 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 8.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 23.9 ms |  | 18 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 5.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 1024 MB |
| 88.9 ms | 25 ms | 0.6 ms | 0.4 ms | 🥶 | 1024 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 16 ms |  | 10.2 ms | 0.2 ms | 🥵 | 1024 MB |
| 107 ms | 26.8 ms | 0.5 ms | 0.2 ms | 🥶 | 1024 MB |
| 101 ms | 27.5 ms | 0.6 ms | 0.3 ms | 🥶 | 1024 MB |
| 4.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 42 ms |  | 35 ms | 0 ms | 🥵 | 1024 MB |
| 99.9 ms | 23.5 ms | 0.6 ms | 0.4 ms | 🥶 | 1024 MB |
| 5.9 ms |  | 0.2 ms | 0.4 ms | 🥵 | 1024 MB |
| 11 ms |  | 3.5 ms | 0.1 ms | 🥵 | 1024 MB |
| 21.9 ms |  | 14.2 ms | 0.4 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 97 ms | 30.8 ms | 0.8 ms | 0.5 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 1024 MB |
| 14 ms |  | 7.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 100 ms | 27.2 ms | 0.6 ms | 0.2 ms | 🥶 | 1024 MB |
| 38.9 ms |  | 11.9 ms | 20 ms | 🥵 | 1024 MB |
| 88.9 ms | 23.8 ms | 0.4 ms | 0.2 ms | 🥶 | 1024 MB |
| 98 ms | 25.8 ms | 0.8 ms | 0.3 ms | 🥶 | 1024 MB |
| 7.9 ms |  | 3.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 1024 MB |
| 177.9 ms | 18.6 ms | 0.5 ms | 0.3 ms | 🥶 | 1024 MB |
| 101.9 ms | 22.9 ms | 0.5 ms | 0.1 ms | 🥶 | 1024 MB |
| 121 ms | 33.5 ms | 15.7 ms | 0.5 ms | 🥶 | 1024 MB |
| 21.9 ms |  | 15.7 ms | 0.2 ms | 🥵 | 1024 MB |
| 119.9 ms | 35 ms | 0.4 ms | 0.7 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.6 ms | 0.3 ms | 🥵 | 1024 MB |
| 9.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 1024 MB |
| 118.9 ms | 26.7 ms | 0.4 ms | 0.3 ms | 🥶 | 1024 MB |
| 91 ms | 22 ms | 0.3 ms | 0.2 ms | 🥶 | 1024 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 59 ms |  | 40.2 ms | 0.1 ms | 🥵 | 1024 MB |
| 5.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 86.9 ms |  | 81.1 ms | 0.3 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 3 ms | 0.1 ms | 🥵 | 1024 MB |
| 88 ms |  | 81.4 ms | 0 ms | 🥵 | 1024 MB |
| 11.9 ms |  | 4.5 ms | 0.2 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 7 ms |  | 0.3 ms | 0 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 82 ms | 25.3 ms | 0.4 ms | 0.1 ms | 🥶 | 1024 MB |
| 97.9 ms | 18.4 ms | 0.5 ms | 0.1 ms | 🥶 | 1024 MB |
| 39.9 ms |  | 13.3 ms | 19.5 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 20.9 ms |  | 14 ms | 0.1 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.3 ms | 0.3 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 23 ms |  | 18.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 108 ms | 18.6 ms | 0.4 ms | 0.1 ms | 🥶 | 1024 MB |
| 9.9 ms |  | 3.2 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 16.9 ms |  | 10.9 ms | 0.2 ms | 🥵 | 1024 MB |
| 20.9 ms |  | 13.9 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 15 ms |  | 8.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 16 ms |  | 0.8 ms | 0.2 ms | 🥵 | 1024 MB |
| 92 ms |  | 84.5 ms | 0.3 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 1.8 ms | 0.1 ms | 🥵 | 1024 MB |
| 16 ms |  | 0.5 ms | 0.2 ms | 🥵 | 1024 MB |
| 87 ms | 18.2 ms | 0.8 ms | 0.4 ms | 🥶 | 1024 MB |
| 133 ms | 18.4 ms | 0.4 ms | 0.2 ms | 🥶 | 1024 MB |
| 8 ms |  | 0.5 ms | 0.2 ms | 🥵 | 1024 MB |
| 100.9 ms | 23 ms | 0.5 ms | 0.2 ms | 🥶 | 1024 MB |
| 82.9 ms | 17.1 ms | 0.3 ms | 0.1 ms | 🥶 | 1024 MB |
| 5 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 5 ms |  | 0.3 ms | 0 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 16.9 ms |  | 9.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 119.9 ms | 23.2 ms | 0.6 ms | 0.3 ms | 🥶 | 1024 MB |
| 109 ms |  | 80 ms | 19.9 ms | 🥵 | 1024 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 9 ms |  | 0.3 ms | 0 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 91 ms | 18 ms | 0.5 ms | 0.1 ms | 🥶 | 1024 MB |
| 92 ms | 25.9 ms | 0.5 ms | 0.6 ms | 🥶 | 1024 MB |
| 16.9 ms |  | 10.2 ms | 0.2 ms | 🥵 | 1024 MB |
| 9.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 88 ms | 28.7 ms | 0.5 ms | 0.3 ms | 🥶 | 1024 MB |
| 25 ms |  | 19.1 ms | 0.7 ms | 🥵 | 1024 MB |
| 8.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 1024 MB |
| 42 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 103.9 ms | 19.6 ms | 0.9 ms | 0.6 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 1024 MB |
| 103.9 ms | 33.1 ms | 0.7 ms | 0.2 ms | 🥶 | 1024 MB |
| 85 ms | 22.6 ms | 0.4 ms | 0.1 ms | 🥶 | 1024 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 18 ms |  | 11 ms | 0.1 ms | 🥵 | 1024 MB |
| 23.9 ms |  | 17.1 ms | 0.2 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.3 ms | 0 ms | 🥵 | 1024 MB |
| 26 ms |  | 17.5 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 1024 MB |
| 99.9 ms | 19.8 ms | 0.5 ms | 0.2 ms | 🥶 | 1024 MB |
| 7 ms |  | 0.6 ms | 0.3 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 110.9 ms | 19.7 ms | 0.5 ms | 0.2 ms | 🥶 | 1024 MB |
| 19 ms |  | 0.6 ms | 0.2 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.5 ms | 0.2 ms | 🥵 | 1024 MB |
| 9 ms |  | 2.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  |  |  | 🥵 | 1024 MB |
| 8.9 ms |  | 0.4 ms | 0 ms | 🥵 | 1024 MB |
| 95.9 ms | 24.6 ms | 0.7 ms | 0.2 ms | 🥶 | 1024 MB |
| 29 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 109 ms | 18.3 ms | 0.6 ms | 0.4 ms | 🥶 | 1024 MB |
| 10.9 ms |  | 4.9 ms | 0.2 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.3 ms | 0.3 ms | 🥵 | 1024 MB |
| 99.9 ms | 31.7 ms | 0.5 ms | 0.1 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 1024 MB |
| 99.9 ms | 26.2 ms | 0.3 ms | 0.3 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 14 ms |  | 6.2 ms | 0.1 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 4.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 25 ms |  | 18 ms | 0.1 ms | 🥵 | 1024 MB |
| 105 ms | 27.2 ms | 0.3 ms | 0.1 ms | 🥶 | 1024 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 19 ms |  | 12.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.4 ms | 0.3 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 5 ms |  | 0.4 ms | 0 ms | 🥵 | 1024 MB |
| 9.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 1024 MB |
| 23 ms |  | 15.1 ms | 0 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 1024 MB |
| 54.9 ms |  | 48.5 ms | 0.3 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 2.8 ms | 0.1 ms | 🥵 | 1024 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 13.9 ms |  | 9.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 105 ms | 28.2 ms | 0.5 ms | 0.2 ms | 🥶 | 1024 MB |
| 9 ms |  | 3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 1024 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 50.9 ms |  | 0.5 ms | 39.5 ms | 🥵 | 1024 MB |
| 4.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 118.9 ms | 41.8 ms | 0.4 ms | 0.4 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 11.9 ms |  | 6.6 ms | 0.1 ms | 🥵 | 1024 MB |
| 87.9 ms | 22.3 ms | 0.5 ms | 0.2 ms | 🥶 | 1024 MB |
| 101 ms | 17.4 ms | 0.5 ms | 0.2 ms | 🥶 | 1024 MB |
| 103 ms | 18.3 ms | 0.6 ms | 0.3 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.7 ms | 0.2 ms | 🥵 | 1024 MB |
| 105 ms | 26.8 ms | 0.7 ms | 0.6 ms | 🥶 | 1024 MB |
| 44 ms |  | 36.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 92.9 ms | 25.7 ms | 0.4 ms | 0.1 ms | 🥶 | 1024 MB |
| 18.9 ms |  | 11.5 ms | 0.3 ms | 🥵 | 1024 MB |
| 96.9 ms | 26.2 ms | 0.6 ms | 0.1 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.5 ms | 0.4 ms | 🥵 | 1024 MB |
| 94 ms | 27.4 ms | 0.5 ms | 0.1 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 1024 MB |
| 13.9 ms |  | 7.1 ms | 0.1 ms | 🥵 | 1024 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.5 ms | 🥵 | 1024 MB |
| 23 ms |  | 18.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 114 ms | 19 ms | 0.7 ms | 0.1 ms | 🥶 | 1024 MB |
| 78.9 ms | 17.9 ms | 0.5 ms | 0.1 ms | 🥶 | 1024 MB |
| 17.9 ms |  | 5.7 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 94 ms | 18.2 ms | 0.9 ms | 0.3 ms | 🥶 | 1024 MB |
| 7.9 ms |  | 0.6 ms | 0.1 ms | 🥵 | 1024 MB |
| 14 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 117 ms |  | 91.5 ms | 19.7 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 113.9 ms | 22.3 ms | 0.5 ms | 0.2 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 67 ms |  | 20.2 ms | 39.6 ms | 🥵 | 1024 MB |
| 99.9 ms | 28.5 ms | 0.4 ms | 0.2 ms | 🥶 | 1024 MB |
| 97 ms | 26.4 ms | 0.4 ms | 0.1 ms | 🥶 | 1024 MB |
| 99.9 ms | 29.8 ms | 0.4 ms | 0.2 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 11.9 ms |  | 4.2 ms | 0.2 ms | 🥵 | 1024 MB |
| 100.9 ms | 30.2 ms | 0.4 ms | 0.4 ms | 🥶 | 1024 MB |
| 23 ms |  | 0.5 ms | 17.3 ms | 🥵 | 1024 MB |
| 128 ms | 22.3 ms | 0.6 ms | 0.2 ms | 🥶 | 1024 MB |
| 22 ms |  | 15.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 36.9 ms |  | 30.9 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 9 ms |  | 3.8 ms | 0.1 ms | 🥵 | 1024 MB |
| 279 ms | 27.9 ms | 0.4 ms | 0.1 ms | 🥶 | 1024 MB |
| 45 ms |  | 39.7 ms | 0.1 ms | 🥵 | 1024 MB |
| 21.9 ms |  | 10.5 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 76.9 ms |  |  |  | 🥵 | 1024 MB |
| 7.9 ms |  | 1.7 ms | 0.3 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 1024 MB |
| 101 ms | 19.2 ms | 0.7 ms | 0.4 ms | 🥶 | 1024 MB |
| 26.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 148 ms | 17.6 ms | 0.3 ms | 0.3 ms | 🥶 | 1024 MB |
| 98 ms | 18.7 ms | 0.5 ms | 0.1 ms | 🥶 | 1024 MB |
| 23.9 ms |  | 18.1 ms | 0.4 ms | 🥵 | 1024 MB |
| 112.9 ms | 25 ms | 0.8 ms | 0.2 ms | 🥶 | 1024 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 13 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.6 ms | 0.1 ms | 🥵 | 1024 MB |
| 26.9 ms |  | 19.6 ms | 0.1 ms | 🥵 | 1024 MB |
| 38 ms |  | 32.5 ms | 0.3 ms | 🥵 | 1024 MB |
| 6 ms |  | 1.1 ms | 0.1 ms | 🥵 | 1024 MB |
| 15 ms |  | 8.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 13.9 ms |  | 8.6 ms | 0.1 ms | 🥵 | 1024 MB |
| 115 ms | 20.6 ms | 0.9 ms | 14.6 ms | 🥶 | 1024 MB |
| 107 ms | 25.8 ms | 0.6 ms | 0.1 ms | 🥶 | 1024 MB |
| 82.9 ms | 21.9 ms | 0.6 ms | 0.4 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 1.5 ms | 0 ms | 🥵 | 1024 MB |
| 104 ms | 21.5 ms | 0.6 ms | 0.2 ms | 🥶 | 1024 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 9.9 ms |  | 2.9 ms | 0.8 ms | 🥵 | 1024 MB |
| 24.9 ms |  | 19.1 ms | 0.2 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.5 ms | 0.1 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.7 ms | 0.1 ms | 🥵 | 1024 MB |
| 36.9 ms |  | 28.5 ms | 0.2 ms | 🥵 | 1024 MB |
| 16.9 ms |  | 9.9 ms | 0.2 ms | 🥵 | 1024 MB |
| 120 ms | 20.6 ms | 0.5 ms | 0.3 ms | 🥶 | 1024 MB |
| 23.9 ms |  | 17.1 ms | 0.1 ms | 🥵 | 1024 MB |
| 115.9 ms | 18.7 ms | 0.5 ms | 0.3 ms | 🥶 | 1024 MB |
| 24.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 9 ms |  | 3.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 101.9 ms | 18.8 ms | 0.5 ms | 0.3 ms | 🥶 | 1024 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 5 ms |  | 0.3 ms | 0 ms | 🥵 | 1024 MB |
| 21 ms |  | 14.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 98.9 ms | 22 ms | 0.5 ms | 0.1 ms | 🥶 | 1024 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 1024 MB |
| 96.9 ms | 26.1 ms | 0.5 ms | 0.3 ms | 🥶 | 1024 MB |
| 99.9 ms | 27.3 ms | 0.4 ms | 0.1 ms | 🥶 | 1024 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.7 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 59.9 ms |  | 33.6 ms | 19.9 ms | 🥵 | 1024 MB |
| 36.9 ms |  | 29.6 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 30.9 ms |  | 24.4 ms | 0.3 ms | 🥵 | 1024 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 107 ms | 20 ms | 0.8 ms | 0.1 ms | 🥶 | 1024 MB |
| 113 ms | 31.6 ms | 0.6 ms | 0.5 ms | 🥶 | 1024 MB |
| 105 ms | 28.8 ms | 0.4 ms | 0.3 ms | 🥶 | 1024 MB |
| 88 ms | 26.4 ms | 0.5 ms | 0.2 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.3 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 1.2 ms | 0.1 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 17.9 ms |  | 9.1 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 7 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 96.9 ms | 20.2 ms | 0.6 ms | 0.5 ms | 🥶 | 1024 MB |
| 18 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.5 ms | 0.4 ms | 🥵 | 1024 MB |
| 36.9 ms |  | 10.8 ms | 19.9 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.3 ms | 0 ms | 🥵 | 1024 MB |
| 102.9 ms | 19.2 ms | 0.6 ms | 0.3 ms | 🥶 | 1024 MB |
| 98 ms | 18.3 ms | 0.6 ms | 0.1 ms | 🥶 | 1024 MB |
| 7 ms |  | 0.5 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 1024 MB |
| 21 ms |  | 15.2 ms | 0.2 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 92.9 ms | 26.2 ms | 0.6 ms | 3.1 ms | 🥶 | 1024 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 1.5 ms | 0.3 ms | 🥵 | 1024 MB |
| 10.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 108.9 ms | 27.8 ms | 0.5 ms | 0.4 ms | 🥶 | 1024 MB |
| 105.9 ms | 20 ms | 0.5 ms | 0.1 ms | 🥶 | 1024 MB |
| 25 ms |  | 0.7 ms | 8.7 ms | 🥵 | 1024 MB |
| 4.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 4.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.8 ms | 0.2 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.6 ms | 0.1 ms | 🥵 | 1024 MB |
| 26 ms |  | 18.5 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 68 ms |  | 60.7 ms | 0.2 ms | 🥵 | 1024 MB |
| 9 ms |  | 2.2 ms | 0.7 ms | 🥵 | 1024 MB |
| 21.9 ms |  | 15.7 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 92 ms | 18.1 ms | 0.6 ms | 0.2 ms | 🥶 | 1024 MB |
| 19.9 ms |  | 12.6 ms | 0.3 ms | 🥵 | 1024 MB |
| 60.9 ms |  | 34.5 ms | 19.7 ms | 🥵 | 1024 MB |
| 23 ms |  | 17 ms | 0 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 5.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.4 ms | 0 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.6 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 1024 MB |
| 102.9 ms | 27.1 ms | 0.5 ms | 0.5 ms | 🥶 | 1024 MB |
| 8 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 98.9 ms | 28.1 ms | 0.4 ms | 0.3 ms | 🥶 | 1024 MB |
| 97.9 ms | 27.6 ms | 0.5 ms | 0.4 ms | 🥶 | 1024 MB |
| 24 ms |  | 19.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 18.9 ms |  | 12.8 ms | 0.2 ms | 🥵 | 1024 MB |
| 8.9 ms |  | 0.6 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 22 ms |  | 14.9 ms | 0.2 ms | 🥵 | 1024 MB |
| 23 ms |  | 16.2 ms | 0.2 ms | 🥵 | 1024 MB |
| 7 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 129.9 ms | 25.2 ms | 0.9 ms | 0.2 ms | 🥶 | 1024 MB |
| 5.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 105 ms | 28 ms | 0.5 ms | 0.3 ms | 🥶 | 1024 MB |
| 98.9 ms | 25.2 ms | 0.7 ms | 0.4 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 1024 MB |
| 15 ms |  | 8.8 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 108 ms | 17.1 ms | 0.4 ms | 0.4 ms | 🥶 | 1024 MB |
| 92.9 ms | 19.9 ms | 0.7 ms | 0.4 ms | 🥶 | 1024 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 98 ms | 19.3 ms | 0.5 ms | 0.2 ms | 🥶 | 1024 MB |
| 26.9 ms |  | 21.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 1024 MB |
| 79.9 ms | 22.3 ms | 0.4 ms | 0.4 ms | 🥶 | 1024 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 99.9 ms | 27.1 ms | 0.7 ms | 0.2 ms | 🥶 | 1024 MB |
| 5 ms |  | 0.3 ms | 0 ms | 🥵 | 1024 MB |
| 21.9 ms |  | 15.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 29.9 ms |  | 23.1 ms | 0.1 ms | 🥵 | 1024 MB |
| 5.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 310 ms | 18.5 ms | 0.5 ms | 0.3 ms | 🥶 | 1024 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 54 ms |  | 40.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 32.9 ms |  | 25.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.5 ms | 0.1 ms | 🥵 | 1024 MB |
| 9.9 ms |  | 4 ms | 0.1 ms | 🥵 | 1024 MB |
| 16.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 95 ms | 18.9 ms | 0.5 ms | 0.4 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 92.9 ms | 22.3 ms | 0.4 ms | 0.1 ms | 🥶 | 1024 MB |
| 8.9 ms |  | 0.4 ms | 0.4 ms | 🥵 | 1024 MB |
| 111 ms | 23 ms | 0.4 ms | 0.2 ms | 🥶 | 1024 MB |
| 20 ms |  | 12 ms | 0.2 ms | 🥵 | 1024 MB |
| 93.9 ms | 17.9 ms | 0.6 ms | 0.3 ms | 🥶 | 1024 MB |
| 59 ms |  | 40 ms | 0.2 ms | 🥵 | 1024 MB |
| 95 ms | 27.3 ms | 0.6 ms | 0.3 ms | 🥶 | 1024 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 85 ms | 24.5 ms | 0.4 ms | 0.1 ms | 🥶 | 1024 MB |
| 8 ms |  | 0.6 ms | 0.2 ms | 🥵 | 1024 MB |
| 127.9 ms | 21.7 ms | 0.6 ms | 0.1 ms | 🥶 | 1024 MB |
| 13.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.7 ms | 0.2 ms | 🥵 | 1024 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 17.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 1024 MB |
| 101.9 ms | 20.3 ms | 0.6 ms | 0.4 ms | 🥶 | 1024 MB |
| 91 ms | 18.5 ms | 0.5 ms | 0.2 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 95.9 ms | 25.2 ms | 0.5 ms | 0.4 ms | 🥶 | 1024 MB |
| 27 ms |  | 0.6 ms | 18.8 ms | 🥵 | 1024 MB |
| 105 ms | 26.8 ms | 0.6 ms | 0.2 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 1024 MB |
| 13 ms |  | 6.1 ms | 0.1 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 64 ms |  | 17.3 ms | 39.8 ms | 🥵 | 1024 MB |
| 38 ms |  | 9.9 ms | 19.8 ms | 🥵 | 1024 MB |
| 108 ms | 28.9 ms | 0.8 ms | 0.1 ms | 🥶 | 1024 MB |
| 52.9 ms |  | 46.6 ms | 0.6 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.6 ms | 0.3 ms | 🥵 | 1024 MB |
| 13.9 ms |  | 8.2 ms | 0.2 ms | 🥵 | 1024 MB |
| 5 ms |  | 0.2 ms | 0.2 ms | 🥵 | 1024 MB |
| 10 ms |  | 3.7 ms | 0.1 ms | 🥵 | 1024 MB |
| 88.9 ms | 23.6 ms | 0.3 ms | 0 ms | 🥶 | 1024 MB |
| 41 ms |  | 33.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 21 ms |  | 13.2 ms | 0.1 ms | 🥵 | 1024 MB |
| 97 ms | 31.8 ms | 0.4 ms | 0.2 ms | 🥶 | 1024 MB |
| 154 ms | 25.4 ms | 0.4 ms | 0.5 ms | 🥶 | 1024 MB |
| 95.9 ms | 30.9 ms | 0.4 ms | 0.3 ms | 🥶 | 1024 MB |
| 106.9 ms | 27.6 ms | 0.5 ms | 0.3 ms | 🥶 | 1024 MB |
| 96.9 ms | 17.9 ms | 0.5 ms | 0.3 ms | 🥶 | 1024 MB |
| 27.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 32.9 ms |  | 8 ms | 19.9 ms | 🥵 | 1024 MB |
| 9.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 80 ms |  | 73.7 ms | 0.1 ms | 🥵 | 1024 MB |
| 11.9 ms |  | 4.9 ms | 0.1 ms | 🥵 | 1024 MB |
| 117 ms | 25 ms | 0.4 ms | 7.1 ms | 🥶 | 1024 MB |
| 5 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 13 ms |  | 5.8 ms | 0.5 ms | 🥵 | 1024 MB |
| 106 ms | 23.6 ms | 0.5 ms | 0.3 ms | 🥶 | 1024 MB |
| 7.9 ms |  | 0.3 ms | 0 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.4 ms | 0 ms | 🥵 | 1024 MB |
| 7 ms |  | 0.5 ms | 0.1 ms | 🥵 | 1024 MB |
| 90 ms | 23.5 ms | 0.5 ms | 0.4 ms | 🥶 | 1024 MB |
| 5 ms |  | 0.3 ms | 0 ms | 🥵 | 1024 MB |
| 13.9 ms |  | 8.6 ms | 0.3 ms | 🥵 | 1024 MB |
| 39 ms |  | 32.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 103 ms | 29.9 ms | 0.5 ms | 0.1 ms | 🥶 | 1024 MB |
| 111 ms | 24.3 ms | 0.7 ms | 0.3 ms | 🥶 | 1024 MB |
| 109.9 ms | 26.4 ms | 0.6 ms | 0.2 ms | 🥶 | 1024 MB |
| 89.9 ms | 18.1 ms | 0.4 ms | 0.2 ms | 🥶 | 1024 MB |
| 148 ms | 28.8 ms | 0.5 ms | 0.5 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 114 ms | 28.5 ms | 0.6 ms | 0.1 ms | 🥶 | 1024 MB |
| 109.9 ms | 18.4 ms | 0.4 ms | 0.1 ms | 🥶 | 1024 MB |
| 18 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |## Results for 2048 MB

| Measurement (2048 MB) | Time (ms) |
|-------------|------|
| Average warm start response time | 7.5 ms |
| Average cold start response time | 111.8 ms |
| Fastest warm response time | 4.9 ms |
| Slowest warm response time | 151.9 ms |
| Fastest cold response time  | 75 ms |
| Slowest cold response time | 310 ms |
  

| Response time | Initialization | Invocation | Overhead | Cold/ Warm Start | Memory Size |
|---------------|----------------|------------|----------|------------------|-------------|
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 107 ms | 28.7 ms | 0.6 ms | 0.1 ms | 🥶 | 2048 MB |
| 8 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 93.9 ms | 18 ms | 0.3 ms | 0.1 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 129.9 ms | 31.8 ms | 0.4 ms | 0.2 ms | 🥶 | 2048 MB |
| 7 ms |  | 0.4 ms | 0 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 98.9 ms | 27.2 ms | 0.4 ms | 0.2 ms | 🥶 | 2048 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 5 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 91 ms | 26.9 ms | 0.6 ms | 0.4 ms | 🥶 | 2048 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.4 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.5 ms | 0.2 ms | 🥵 | 2048 MB |
| 16 ms |  | 8.9 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 101.9 ms | 18.5 ms | 0.5 ms | 0.3 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 5 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 98 ms | 17.2 ms | 0.4 ms | 0.1 ms | 🥶 | 2048 MB |
| 88 ms | 22.5 ms | 0.6 ms | 0.1 ms | 🥶 | 2048 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 91 ms | 23.2 ms | 0.5 ms | 0.2 ms | 🥶 | 2048 MB |
| 23.9 ms |  | 0.4 ms | 18 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 2048 MB |
| 89.9 ms | 21.6 ms | 0.6 ms | 0.1 ms | 🥶 | 2048 MB |
| 100 ms | 20.3 ms | 0.5 ms | 0.2 ms | 🥶 | 2048 MB |
| 7 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 33.9 ms |  | 27.7 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 25 ms |  | 18.4 ms | 0.3 ms | 🥵 | 2048 MB |
| 19.9 ms |  | 0.6 ms | 0.3 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.7 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.3 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 98 ms | 17.7 ms | 0.6 ms | 0.3 ms | 🥶 | 2048 MB |
| 5.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 84 ms | 18.7 ms | 0.4 ms | 0.2 ms | 🥶 | 2048 MB |
| 5 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 108.9 ms | 24.5 ms | 0.7 ms | 0.2 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 101.9 ms | 21.1 ms | 0.6 ms | 0.2 ms | 🥶 | 2048 MB |
| 147 ms | 18.6 ms | 0.5 ms | 0.2 ms | 🥶 | 2048 MB |
| 8 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 97 ms | 27.9 ms | 0.5 ms | 0.2 ms | 🥶 | 2048 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 108 ms | 30.5 ms | 0.4 ms | 0.2 ms | 🥶 | 2048 MB |
| 134 ms | 19.4 ms | 0.7 ms | 0.2 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 105 ms | 19.3 ms | 0.7 ms | 0.2 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 95.9 ms | 25.4 ms | 0.7 ms | 0.2 ms | 🥶 | 2048 MB |
| 5 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 23.9 ms |  | 18.6 ms | 0.1 ms | 🥵 | 2048 MB |
| 27 ms |  | 20.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 95.9 ms | 29.7 ms | 0.5 ms | 0.1 ms | 🥶 | 2048 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 36.9 ms |  | 31.9 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 9.9 ms |  | 4.1 ms | 0.6 ms | 🥵 | 2048 MB |
| 16 ms |  | 0.7 ms | 0.4 ms | 🥵 | 2048 MB |
| 85.9 ms | 18.4 ms | 0.6 ms | 0.4 ms | 🥶 | 2048 MB |
| 6 ms |  | 0.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 5 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 2048 MB |
| 85.9 ms | 18.1 ms | 0.4 ms | 0.2 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 2048 MB |
| 85.9 ms | 21.9 ms | 0.5 ms | 0.1 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 95 ms | 18.5 ms | 0.5 ms | 0.1 ms | 🥶 | 2048 MB |
| 98.9 ms | 27.6 ms | 0.5 ms | 0.2 ms | 🥶 | 2048 MB |
| 98 ms | 26.9 ms | 0.8 ms | 0.2 ms | 🥶 | 2048 MB |
| 89.9 ms | 23.1 ms | 0.5 ms | 0.1 ms | 🥶 | 2048 MB |
| 21 ms |  | 14.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 13.9 ms |  | 6.9 ms | 0.1 ms | 🥵 | 2048 MB |
| 93.9 ms | 18.7 ms | 0.6 ms | 0.2 ms | 🥶 | 2048 MB |
| 4.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 91 ms | 19.9 ms | 0.4 ms | 0.1 ms | 🥶 | 2048 MB |
| 83 ms | 20 ms | 0.7 ms | 0.4 ms | 🥶 | 2048 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 43.9 ms |  | 37.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 23.9 ms |  | 16.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 123 ms | 19.5 ms | 0.6 ms | 0.1 ms | 🥶 | 2048 MB |
| 6 ms |  | 0.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.5 ms | 0 ms | 🥵 | 2048 MB |
| 4.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 9.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 13.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 100.9 ms | 29.9 ms | 0.6 ms | 0.3 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 90.9 ms | 25 ms | 0.5 ms | 0.4 ms | 🥶 | 2048 MB |
| 8 ms |  | 0.3 ms | 0.3 ms | 🥵 | 2048 MB |
| 4.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.5 ms | 0 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.4 ms | 0 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 38 ms |  | 32.8 ms | 0.3 ms | 🥵 | 2048 MB |
| 40 ms |  | 14.7 ms | 19.8 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.5 ms | 0.2 ms | 🥵 | 2048 MB |
| 91 ms | 23.4 ms | 0.3 ms | 0.3 ms | 🥶 | 2048 MB |
| 11 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 24.9 ms |  | 18.8 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 102.9 ms | 23.2 ms | 0.7 ms | 0.1 ms | 🥶 | 2048 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 85.9 ms | 26 ms | 0.4 ms | 0.2 ms | 🥶 | 2048 MB |
| 126.9 ms | 32.4 ms | 0.5 ms | 0.2 ms | 🥶 | 2048 MB |
| 10.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 18 ms |  | 10 ms | 0.4 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 24 ms |  | 16.9 ms | 0.1 ms | 🥵 | 2048 MB |
| 33.9 ms |  | 28.1 ms | 0.3 ms | 🥵 | 2048 MB |
| 93.9 ms | 25.3 ms | 0.4 ms | 0.2 ms | 🥶 | 2048 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 16 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 5.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 4.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 95 ms | 20.3 ms | 0.7 ms | 0.3 ms | 🥶 | 2048 MB |
| 16 ms |  | 10.2 ms | 0.2 ms | 🥵 | 2048 MB |
| 107 ms | 26.8 ms | 0.5 ms | 0.2 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 11 ms |  | 3.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 2048 MB |
| 103 ms | 24.5 ms | 0.4 ms | 0.4 ms | 🥶 | 2048 MB |
| 14 ms |  | 7.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 88.9 ms | 23.8 ms | 0.4 ms | 0.2 ms | 🥶 | 2048 MB |
| 177.9 ms | 18.6 ms | 0.5 ms | 0.3 ms | 🥶 | 2048 MB |
| 101.9 ms | 22.9 ms | 0.5 ms | 0.1 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.6 ms | 0.3 ms | 🥵 | 2048 MB |
| 9.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 2048 MB |
| 118.9 ms | 26.7 ms | 0.4 ms | 0.3 ms | 🥶 | 2048 MB |
| 91 ms | 22 ms | 0.3 ms | 0.2 ms | 🥶 | 2048 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 59 ms |  | 40.2 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 5.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 88 ms |  | 81.4 ms | 0 ms | 🥵 | 2048 MB |
| 11.9 ms |  | 4.5 ms | 0.2 ms | 🥵 | 2048 MB |
| 89.9 ms | 24.7 ms | 0.6 ms | 0.2 ms | 🥶 | 2048 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 7 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 97.9 ms | 18.4 ms | 0.5 ms | 0.1 ms | 🥶 | 2048 MB |
| 82 ms | 25.3 ms | 0.4 ms | 0.1 ms | 🥶 | 2048 MB |
| 7.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 20.9 ms |  | 14 ms | 0.1 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.3 ms | 0.3 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 23 ms |  | 18.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 108 ms | 18.6 ms | 0.4 ms | 0.1 ms | 🥶 | 2048 MB |
| 9.9 ms |  | 3.2 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 16.9 ms |  | 10.9 ms | 0.2 ms | 🥵 | 2048 MB |
| 105 ms | 19.4 ms | 0.6 ms | 0.4 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.5 ms | 0.4 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 15 ms |  | 8.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 133 ms | 18.4 ms | 0.4 ms | 0.2 ms | 🥶 | 2048 MB |
| 5 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 92 ms |  | 84.5 ms | 0.3 ms | 🥵 | 2048 MB |
| 20.9 ms |  | 13.9 ms | 0.1 ms | 🥵 | 2048 MB |
| 82.9 ms | 17.1 ms | 0.3 ms | 0.1 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 119.9 ms | 23.2 ms | 0.6 ms | 0.3 ms | 🥶 | 2048 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 16.9 ms |  | 10.2 ms | 0.2 ms | 🥵 | 2048 MB |
| 91 ms | 18 ms | 0.5 ms | 0.1 ms | 🥶 | 2048 MB |
| 92 ms | 25.9 ms | 0.5 ms | 0.6 ms | 🥶 | 2048 MB |
| 9.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 101 ms | 23.2 ms | 0.5 ms | 0.6 ms | 🥶 | 2048 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 26 ms |  | 17.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.5 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 110.9 ms | 19.7 ms | 0.5 ms | 0.2 ms | 🥶 | 2048 MB |
| 6.9 ms |  |  |  | 🥵 | 2048 MB |
| 95.9 ms | 24.6 ms | 0.7 ms | 0.2 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 99.9 ms | 31.7 ms | 0.5 ms | 0.1 ms | 🥶 | 2048 MB |
| 9 ms |  | 2.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 98 ms | 29 ms | 0.5 ms | 0.4 ms | 🥶 | 2048 MB |
| 4.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 25 ms |  | 18 ms | 0.1 ms | 🥵 | 2048 MB |
| 105 ms | 27.2 ms | 0.3 ms | 0.1 ms | 🥶 | 2048 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 9.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 23 ms |  | 15.1 ms | 0 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 54.9 ms |  | 48.5 ms | 0.3 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 2.8 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 2048 MB |
| 50.9 ms |  | 0.5 ms | 39.5 ms | 🥵 | 2048 MB |
| 13.9 ms |  | 9.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 105 ms | 28.2 ms | 0.5 ms | 0.2 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 103 ms | 18.3 ms | 0.6 ms | 0.3 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 101.9 ms | 24 ms | 0.7 ms | 0.4 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 105 ms | 26.8 ms | 0.7 ms | 0.6 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 44 ms |  | 36.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 92.9 ms | 25.7 ms | 0.4 ms | 0.1 ms | 🥶 | 2048 MB |
| 8 ms |  | 0.5 ms | 0.4 ms | 🥵 | 2048 MB |
| 18.9 ms |  | 11.5 ms | 0.3 ms | 🥵 | 2048 MB |
| 94 ms | 27.4 ms | 0.5 ms | 0.1 ms | 🥶 | 2048 MB |
| 96.9 ms | 26.2 ms | 0.6 ms | 0.1 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 17.9 ms |  | 5.7 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 94 ms | 18.2 ms | 0.9 ms | 0.3 ms | 🥶 | 2048 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 92 ms | 22.4 ms | 0.6 ms | 0.2 ms | 🥶 | 2048 MB |
| 113.9 ms | 22.3 ms | 0.5 ms | 0.2 ms | 🥶 | 2048 MB |
| 90.9 ms | 25.3 ms | 0.5 ms | 0.2 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 100.9 ms | 30.2 ms | 0.4 ms | 0.4 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 2048 MB |
| 279 ms | 27.9 ms | 0.4 ms | 0.1 ms | 🥶 | 2048 MB |
| 45 ms |  | 39.7 ms | 0.1 ms | 🥵 | 2048 MB |
| 36.9 ms |  | 30.9 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 1.7 ms | 0.3 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 101 ms | 19.2 ms | 0.7 ms | 0.4 ms | 🥶 | 2048 MB |
| 5.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 112.9 ms | 25 ms | 0.8 ms | 0.2 ms | 🥶 | 2048 MB |
| 76.9 ms |  |  |  | 🥵 | 2048 MB |
| 98 ms | 18.7 ms | 0.5 ms | 0.1 ms | 🥶 | 2048 MB |
| 13 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 38 ms |  | 32.5 ms | 0.3 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6 ms |  | 1.1 ms | 0.1 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 26.9 ms |  | 19.6 ms | 0.1 ms | 🥵 | 2048 MB |
| 4.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 107 ms | 25.8 ms | 0.6 ms | 0.1 ms | 🥶 | 2048 MB |
| 82.9 ms | 21.9 ms | 0.6 ms | 0.4 ms | 🥶 | 2048 MB |
| 15 ms |  | 8.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 13.9 ms |  | 8.6 ms | 0.1 ms | 🥵 | 2048 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 89.9 ms | 26.2 ms | 0.6 ms | 0.3 ms | 🥶 | 2048 MB |
| 24.9 ms |  | 19.1 ms | 0.2 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.7 ms | 0.1 ms | 🥵 | 2048 MB |
| 96.9 ms | 24.2 ms | 0.7 ms | 0.2 ms | 🥶 | 2048 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 16.9 ms |  | 9.9 ms | 0.2 ms | 🥵 | 2048 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 23.9 ms |  | 17.1 ms | 0.1 ms | 🥵 | 2048 MB |
| 7 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 115.9 ms | 18.7 ms | 0.5 ms | 0.3 ms | 🥶 | 2048 MB |
| 101.9 ms | 18.8 ms | 0.5 ms | 0.3 ms | 🥶 | 2048 MB |
| 98.9 ms | 22 ms | 0.5 ms | 0.1 ms | 🥶 | 2048 MB |
| 98.9 ms | 25.9 ms | 0.6 ms | 0.2 ms | 🥶 | 2048 MB |
| 5 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 21 ms |  | 14.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.5 ms | 0.2 ms | 🥵 | 2048 MB |
| 107 ms | 20 ms | 0.8 ms | 0.1 ms | 🥶 | 2048 MB |
| 59.9 ms |  | 33.6 ms | 19.9 ms | 🥵 | 2048 MB |
| 99.9 ms | 25.3 ms | 0.5 ms | 0.5 ms | 🥶 | 2048 MB |
| 88 ms | 26.4 ms | 0.5 ms | 0.2 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.3 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 7 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 1.2 ms | 0.1 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 21 ms |  | 15.2 ms | 0.2 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.5 ms | 0.4 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 1.5 ms | 0.3 ms | 🥵 | 2048 MB |
| 10.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 105.9 ms | 20 ms | 0.5 ms | 0.1 ms | 🥶 | 2048 MB |
| 4.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 4.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.6 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.8 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 19.9 ms |  | 12.6 ms | 0.3 ms | 🥵 | 2048 MB |
| 23 ms |  | 17 ms | 0 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 2048 MB |
| 102.9 ms | 27.1 ms | 0.5 ms | 0.5 ms | 🥶 | 2048 MB |
| 5.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.4 ms | 0 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 97.9 ms | 27.6 ms | 0.5 ms | 0.4 ms | 🥶 | 2048 MB |
| 18.9 ms |  | 12.8 ms | 0.2 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 8.9 ms |  | 0.6 ms | 0.2 ms | 🥵 | 2048 MB |
| 7 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 23 ms |  | 16.2 ms | 0.2 ms | 🥵 | 2048 MB |
| 5.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 98 ms | 19.3 ms | 0.5 ms | 0.2 ms | 🥶 | 2048 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 105 ms | 28 ms | 0.5 ms | 0.3 ms | 🥶 | 2048 MB |
| 99.9 ms | 27.1 ms | 0.7 ms | 0.2 ms | 🥶 | 2048 MB |
| 21.9 ms |  | 15.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 29.9 ms |  | 23.1 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 5.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 310 ms | 18.5 ms | 0.5 ms | 0.3 ms | 🥶 | 2048 MB |
| 95 ms | 23 ms | 0.5 ms | 0.3 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 54 ms |  | 40.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 16.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 32.9 ms |  | 25.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 111 ms | 23 ms | 0.4 ms | 0.2 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 20 ms |  | 12 ms | 0.2 ms | 🥵 | 2048 MB |
| 13.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.7 ms | 0.2 ms | 🥵 | 2048 MB |
| 17.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 2048 MB |
| 127.9 ms | 21.7 ms | 0.6 ms | 0.1 ms | 🥶 | 2048 MB |
| 91 ms | 18.5 ms | 0.5 ms | 0.2 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 119 ms | 27.9 ms | 0.4 ms | 0.2 ms | 🥶 | 2048 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.6 ms | 0.3 ms | 🥵 | 2048 MB |
| 13.9 ms |  | 8.2 ms | 0.2 ms | 🥵 | 2048 MB |
| 38 ms |  | 9.9 ms | 19.8 ms | 🥵 | 2048 MB |
| 64 ms |  | 17.3 ms | 39.8 ms | 🥵 | 2048 MB |
| 13 ms |  | 6.1 ms | 0.1 ms | 🥵 | 2048 MB |
| 88.9 ms | 23.6 ms | 0.3 ms | 0 ms | 🥶 | 2048 MB |
| 41 ms |  | 33.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 97 ms | 31.8 ms | 0.4 ms | 0.2 ms | 🥶 | 2048 MB |
| 154 ms | 25.4 ms | 0.4 ms | 0.5 ms | 🥶 | 2048 MB |
| 27.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 9.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 96.9 ms | 17.9 ms | 0.5 ms | 0.3 ms | 🥶 | 2048 MB |
| 80 ms |  | 73.7 ms | 0.1 ms | 🥵 | 2048 MB |
| 11.9 ms |  | 4.9 ms | 0.1 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.4 ms | 0 ms | 🥵 | 2048 MB |
| 106 ms | 23.6 ms | 0.5 ms | 0.3 ms | 🥶 | 2048 MB |
| 88.9 ms | 19.4 ms | 0.4 ms | 0.1 ms | 🥶 | 2048 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 5 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 39 ms |  | 32.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 5.9 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 103 ms | 29.9 ms | 0.5 ms | 0.1 ms | 🥶 | 2048 MB |
| 111 ms | 24.3 ms | 0.7 ms | 0.3 ms | 🥶 | 2048 MB |
| 13.9 ms |  | 8.6 ms | 0.3 ms | 🥵 | 2048 MB |
| 18 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 94.9 ms | 31.5 ms | 0.7 ms | 0.2 ms | 🥶 | 2048 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.6 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 101 ms | 25.2 ms | 0.6 ms | 1.5 ms | 🥶 | 2048 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.5 ms | 0 ms | 🥵 | 2048 MB |
| 95 ms | 17.3 ms | 0.4 ms | 0.3 ms | 🥶 | 2048 MB |
| 92 ms | 22.9 ms | 0.4 ms | 0.2 ms | 🥶 | 2048 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 78.9 ms | 24.9 ms | 0.5 ms | 0.3 ms | 🥶 | 2048 MB |
| 98 ms | 18.9 ms | 0.6 ms | 0.4 ms | 🥶 | 2048 MB |
| 7.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 21.9 ms |  | 8.2 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 98.9 ms | 18.2 ms | 0.6 ms | 0.1 ms | 🥶 | 2048 MB |
| 128 ms | 25.6 ms | 0.7 ms | 0.3 ms | 🥶 | 2048 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 2048 MB |
| 23.9 ms |  | 18.6 ms | 0.2 ms | 🥵 | 2048 MB |
| 26.9 ms |  | 20.2 ms | 0.1 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 151.9 ms |  | 80 ms | 59.9 ms | 🥵 | 2048 MB |
| 12 ms |  | 4.9 ms | 0.1 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 20.9 ms |  | 13.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 97 ms | 32 ms | 0.4 ms | 0.7 ms | 🥶 | 2048 MB |
| 7 ms |  | 0.5 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 18.9 ms |  | 13.8 ms | 0.1 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 85 ms |  | 79.8 ms | 0.7 ms | 🥵 | 2048 MB |
| 12 ms |  | 5.1 ms | 0.1 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 108 ms | 24.5 ms | 0.5 ms | 0.1 ms | 🥶 | 2048 MB |
| 85 ms |  | 77.7 ms | 0.2 ms | 🥵 | 2048 MB |
| 111 ms | 25 ms | 0.7 ms | 0.3 ms | 🥶 | 2048 MB |
| 6 ms |  | 0.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 53.9 ms |  | 39.9 ms | 0.3 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 16 ms |  | 10.2 ms | 0 ms | 🥵 | 2048 MB |
| 12 ms |  | 5.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 95 ms | 25 ms | 0.4 ms | 0.1 ms | 🥶 | 2048 MB |
| 98.9 ms | 25.7 ms | 0.3 ms | 0.3 ms | 🥶 | 2048 MB |
| 92 ms | 23.8 ms | 0.4 ms | 0.3 ms | 🥶 | 2048 MB |
| 16.9 ms |  | 10.4 ms | 0.5 ms | 🥵 | 2048 MB |
| 108 ms | 32.5 ms | 0.5 ms | 0.5 ms | 🥶 | 2048 MB |
| 23 ms |  | 18.6 ms | 0.1 ms | 🥵 | 2048 MB |
| 96 ms | 29.8 ms | 0.5 ms | 0.4 ms | 🥶 | 2048 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 116.9 ms | 18.7 ms | 0.5 ms | 0 ms | 🥶 | 2048 MB |
| 9 ms |  | 0.6 ms | 0.2 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 13 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 97 ms | 27.4 ms | 0.4 ms | 0.3 ms | 🥶 | 2048 MB |
| 8 ms |  | 0.4 ms | 0.3 ms | 🥵 | 2048 MB |
| 105.9 ms | 30.4 ms | 0.7 ms | 0.2 ms | 🥶 | 2048 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 7 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 24.9 ms |  | 18 ms | 0.2 ms | 🥵 | 2048 MB |
| 75 ms | 22 ms | 0.4 ms | 0 ms | 🥶 | 2048 MB |
| 118 ms | 28.7 ms | 0.4 ms | 0.2 ms | 🥶 | 2048 MB |
| 23 ms |  | 15.8 ms | 1.4 ms | 🥵 | 2048 MB |
| 94 ms | 22.9 ms | 0.7 ms | 0.3 ms | 🥶 | 2048 MB |
| 110 ms | 18.6 ms | 0.9 ms | 0.4 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 112.9 ms | 19.2 ms | 0.5 ms | 0.2 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 20 ms |  | 12.5 ms | 0 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.6 ms | 0.2 ms | 🥵 | 2048 MB |
| 97 ms | 22.2 ms | 0.4 ms | 0.2 ms | 🥶 | 2048 MB |
| 11.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 23 ms |  | 16.6 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 19.9 ms |  | 13.8 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 9 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 115 ms | 27.1 ms | 0.4 ms | 0.1 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 9 ms |  | 0.3 ms | 0.3 ms | 🥵 | 2048 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 26 ms |  | 19.9 ms | 0.2 ms | 🥵 | 2048 MB |
| 146.9 ms | 28.7 ms | 0.4 ms | 0.2 ms | 🥶 | 2048 MB |
| 42 ms |  | 15.8 ms | 19.7 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 4.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 90 ms | 25.8 ms | 0.6 ms | 0.1 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 128 ms | 20.1 ms | 0.5 ms | 0.2 ms | 🥶 | 2048 MB |
| 101 ms |  |  |  | 🥵 | 2048 MB |
| 97 ms | 21.3 ms | 0.7 ms | 0.1 ms | 🥶 | 2048 MB |
| 95.9 ms | 22.2 ms | 0.8 ms | 0.2 ms | 🥶 | 2048 MB |
| 89.9 ms | 25.1 ms | 0.3 ms | 0.1 ms | 🥶 | 2048 MB |
| 138 ms | 22.7 ms | 0.5 ms | 0.1 ms | 🥶 | 2048 MB |
| 101.9 ms | 25 ms | 0.5 ms | 0.1 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 5.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.4 ms | 0 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.3 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 95.9 ms | 19.7 ms | 0.5 ms | 0.2 ms | 🥶 | 2048 MB |
| 119 ms | 20.2 ms | 0.5 ms | 0.2 ms | 🥶 | 2048 MB |
| 90.9 ms | 25 ms | 0.6 ms | 0.3 ms | 🥶 | 2048 MB |
| 94 ms | 18.6 ms | 0.6 ms | 0 ms | 🥶 | 2048 MB |
| 13.9 ms |  | 0.8 ms | 0.5 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 125 ms | 26.2 ms | 0.6 ms | 0.4 ms | 🥶 | 2048 MB |
| 8 ms |  | 0.4 ms | 0.3 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.6 ms | 0 ms | 🥵 | 2048 MB |
| 102.9 ms | 18.9 ms | 0.5 ms | 0.3 ms | 🥶 | 2048 MB |
| 6 ms |  | 0.5 ms | 0.2 ms | 🥵 | 2048 MB |
| 98 ms | 17.7 ms | 0.6 ms | 0.3 ms | 🥶 | 2048 MB |
| 11 ms |  | 5.5 ms | 0.2 ms | 🥵 | 2048 MB |
| 88.9 ms | 25 ms | 0.6 ms | 0.4 ms | 🥶 | 2048 MB |
| 8.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 103.9 ms | 23.8 ms | 0.7 ms | 0.3 ms | 🥶 | 2048 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 23.9 ms |  | 18 ms | 0.2 ms | 🥵 | 2048 MB |
| 93.9 ms | 28 ms | 0.4 ms | 0.3 ms | 🥶 | 2048 MB |
| 15 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 101 ms | 27.5 ms | 0.6 ms | 0.3 ms | 🥶 | 2048 MB |
| 99.9 ms | 23.5 ms | 0.6 ms | 0.4 ms | 🥶 | 2048 MB |
| 42 ms |  | 35 ms | 0 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 5.9 ms |  | 0.2 ms | 0.4 ms | 🥵 | 2048 MB |
| 96.9 ms | 22.1 ms | 0.5 ms | 0.2 ms | 🥶 | 2048 MB |
| 7.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 21.9 ms |  | 14.2 ms | 0.4 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 98 ms | 25.8 ms | 0.8 ms | 0.3 ms | 🥶 | 2048 MB |
| 100 ms | 27.2 ms | 0.6 ms | 0.2 ms | 🥶 | 2048 MB |
| 97 ms | 30.8 ms | 0.8 ms | 0.5 ms | 🥶 | 2048 MB |
| 38.9 ms |  | 11.9 ms | 20 ms | 🥵 | 2048 MB |
| 135.9 ms | 20 ms | 0.6 ms | 0.1 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 3.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 119.9 ms | 35 ms | 0.4 ms | 0.7 ms | 🥶 | 2048 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 121 ms | 33.5 ms | 15.7 ms | 0.5 ms | 🥶 | 2048 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 21.9 ms |  | 15.7 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 93 ms | 26.2 ms | 1 ms | 0.4 ms | 🥶 | 2048 MB |
| 86.9 ms |  | 81.1 ms | 0.3 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 39.9 ms |  | 13.3 ms | 19.5 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 1.8 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.5 ms | 0.2 ms | 🥵 | 2048 MB |
| 16 ms |  | 0.8 ms | 0.2 ms | 🥵 | 2048 MB |
| 100.9 ms | 23 ms | 0.5 ms | 0.2 ms | 🥶 | 2048 MB |
| 16 ms |  | 0.5 ms | 0.2 ms | 🥵 | 2048 MB |
| 87 ms | 18.2 ms | 0.8 ms | 0.4 ms | 🥶 | 2048 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 109 ms |  | 80 ms | 19.9 ms | 🥵 | 2048 MB |
| 5 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.4 ms | 0 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 16.9 ms |  | 9.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 9 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 94 ms | 28.4 ms | 0.9 ms | 0.2 ms | 🥶 | 2048 MB |
| 25 ms |  | 19.1 ms | 0.7 ms | 🥵 | 2048 MB |
| 88 ms | 28.7 ms | 0.5 ms | 0.3 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 42 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 8.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 103.9 ms | 19.6 ms | 0.9 ms | 0.6 ms | 🥶 | 2048 MB |
| 18 ms |  | 11 ms | 0.1 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 103.9 ms | 33.1 ms | 0.7 ms | 0.2 ms | 🥶 | 2048 MB |
| 85 ms | 22.6 ms | 0.4 ms | 0.1 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 23.9 ms |  | 17.1 ms | 0.2 ms | 🥵 | 2048 MB |
| 7 ms |  | 0.6 ms | 0.3 ms | 🥵 | 2048 MB |
| 7 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 7 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 99.9 ms | 19.8 ms | 0.5 ms | 0.2 ms | 🥶 | 2048 MB |
| 19 ms |  | 0.6 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 8.9 ms |  | 0.4 ms | 0 ms | 🥵 | 2048 MB |
| 29 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 5 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 99.9 ms | 26.2 ms | 0.3 ms | 0.3 ms | 🥶 | 2048 MB |
| 109 ms | 18.3 ms | 0.6 ms | 0.4 ms | 🥶 | 2048 MB |
| 10.9 ms |  | 4.9 ms | 0.2 ms | 🥵 | 2048 MB |
| 204.9 ms | 30.2 ms | 0.5 ms | 0.1 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 15 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 87.9 ms | 23.6 ms | 0.5 ms | 0.4 ms | 🥶 | 2048 MB |
| 7.9 ms |  | 0.6 ms | 0.1 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.3 ms | 0.3 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 14 ms |  | 6.2 ms | 0.1 ms | 🥵 | 2048 MB |
| 79.9 ms | 23.4 ms | 0.4 ms | 0.4 ms | 🥶 | 2048 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.4 ms | 0.3 ms | 🥵 | 2048 MB |
| 5 ms |  | 0.4 ms | 0 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 19 ms |  | 12.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 9 ms |  | 3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 118.9 ms | 41.8 ms | 0.4 ms | 0.4 ms | 🥶 | 2048 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 11.9 ms |  | 6.6 ms | 0.1 ms | 🥵 | 2048 MB |
| 87.9 ms | 22.3 ms | 0.5 ms | 0.2 ms | 🥶 | 2048 MB |
| 4.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 101 ms | 17.4 ms | 0.5 ms | 0.2 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.7 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 23 ms |  | 18.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 13.9 ms |  | 7.1 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.5 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 114 ms | 19 ms | 0.7 ms | 0.1 ms | 🥶 | 2048 MB |
| 78.9 ms | 17.9 ms | 0.5 ms | 0.1 ms | 🥶 | 2048 MB |
| 117 ms |  | 91.5 ms | 19.7 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 14 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.6 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 97 ms | 26.4 ms | 0.4 ms | 0.1 ms | 🥶 | 2048 MB |
| 99.9 ms | 29.8 ms | 0.4 ms | 0.2 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 67 ms |  | 20.2 ms | 39.6 ms | 🥵 | 2048 MB |
| 99.9 ms | 28.5 ms | 0.4 ms | 0.2 ms | 🥶 | 2048 MB |
| 11.9 ms |  | 4.2 ms | 0.2 ms | 🥵 | 2048 MB |
| 23 ms |  | 0.5 ms | 17.3 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 22 ms |  | 15.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 128 ms | 22.3 ms | 0.6 ms | 0.2 ms | 🥶 | 2048 MB |
| 26.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 9 ms |  | 3.8 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.4 ms | 0 ms | 🥵 | 2048 MB |
| 21.9 ms |  | 10.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 148 ms | 17.6 ms | 0.3 ms | 0.3 ms | 🥶 | 2048 MB |
| 23.9 ms |  | 18.1 ms | 0.4 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 101.9 ms | 22.4 ms | 0.6 ms | 0.2 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.6 ms | 0.1 ms | 🥵 | 2048 MB |
| 115 ms | 20.6 ms | 0.9 ms | 14.6 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 1.5 ms | 0 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 2048 MB |
| 104 ms | 21.5 ms | 0.6 ms | 0.2 ms | 🥶 | 2048 MB |
| 9.9 ms |  | 2.9 ms | 0.8 ms | 🥵 | 2048 MB |
| 104 ms | 23.9 ms | 0.5 ms | 0.2 ms | 🥶 | 2048 MB |
| 36.9 ms |  | 28.5 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 9 ms |  | 3.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 120 ms | 20.6 ms | 0.5 ms | 0.3 ms | 🥶 | 2048 MB |
| 7.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 2048 MB |
| 24.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 101.9 ms | 18.8 ms | 0.5 ms | 0.2 ms | 🥶 | 2048 MB |
| 96.9 ms | 26.1 ms | 0.5 ms | 0.3 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.7 ms | 0.2 ms | 🥵 | 2048 MB |
| 99.9 ms | 27.3 ms | 0.4 ms | 0.1 ms | 🥶 | 2048 MB |
| 36.9 ms |  | 29.6 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 30.9 ms |  | 24.4 ms | 0.3 ms | 🥵 | 2048 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 4.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 113 ms | 31.6 ms | 0.6 ms | 0.5 ms | 🥶 | 2048 MB |
| 105 ms | 28.8 ms | 0.4 ms | 0.3 ms | 🥶 | 2048 MB |
| 17.9 ms |  | 9.1 ms | 0.2 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 96.9 ms | 20.2 ms | 0.6 ms | 0.5 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 18 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 98 ms | 18.3 ms | 0.6 ms | 0.1 ms | 🥶 | 2048 MB |
| 7 ms |  | 0.5 ms | 0.2 ms | 🥵 | 2048 MB |
| 36.9 ms |  | 10.8 ms | 19.9 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 102.9 ms | 19.2 ms | 0.6 ms | 0.3 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 92.9 ms | 26.2 ms | 0.6 ms | 3.1 ms | 🥶 | 2048 MB |
| 108.9 ms | 27.8 ms | 0.5 ms | 0.4 ms | 🥶 | 2048 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 25 ms |  | 0.7 ms | 8.7 ms | 🥵 | 2048 MB |
| 26 ms |  | 18.5 ms | 0.2 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 68 ms |  | 60.7 ms | 0.2 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.6 ms | 0.2 ms | 🥵 | 2048 MB |
| 9 ms |  | 2.2 ms | 0.7 ms | 🥵 | 2048 MB |
| 92 ms | 18.1 ms | 0.6 ms | 0.2 ms | 🥶 | 2048 MB |
| 21.9 ms |  | 15.7 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 60.9 ms |  | 34.5 ms | 19.7 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 4.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.6 ms | 0.1 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 2048 MB |
| 24 ms |  | 19.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 98.9 ms | 28.1 ms | 0.4 ms | 0.3 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.3 ms | 🥵 | 2048 MB |
| 15 ms |  | 8.8 ms | 0.1 ms | 🥵 | 2048 MB |
| 129.9 ms | 25.2 ms | 0.9 ms | 0.2 ms | 🥶 | 2048 MB |
| 98.9 ms | 25.2 ms | 0.7 ms | 0.4 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 2048 MB |
| 22 ms |  | 14.9 ms | 0.2 ms | 🥵 | 2048 MB |
| 88 ms | 25.2 ms | 0.4 ms | 0.1 ms | 🥶 | 2048 MB |
| 108 ms | 17.1 ms | 0.4 ms | 0.4 ms | 🥶 | 2048 MB |
| 92.9 ms | 19.9 ms | 0.7 ms | 0.4 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 2048 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 5 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 4.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 26.9 ms |  | 21.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 79.9 ms | 22.3 ms | 0.4 ms | 0.4 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 96.9 ms | 28.7 ms | 0.5 ms | 0.2 ms | 🥶 | 2048 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 9.9 ms |  | 4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 95 ms | 18.9 ms | 0.5 ms | 0.4 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 8.9 ms |  | 0.4 ms | 0.4 ms | 🥵 | 2048 MB |
| 93.9 ms | 17.9 ms | 0.6 ms | 0.3 ms | 🥶 | 2048 MB |
| 59 ms |  | 40 ms | 0.2 ms | 🥵 | 2048 MB |
| 101 ms | 26.8 ms | 0.6 ms | 0.3 ms | 🥶 | 2048 MB |
| 92.9 ms | 22.3 ms | 0.4 ms | 0.1 ms | 🥶 | 2048 MB |
| 95 ms | 27.3 ms | 0.6 ms | 0.3 ms | 🥶 | 2048 MB |
| 85 ms | 24.5 ms | 0.4 ms | 0.1 ms | 🥶 | 2048 MB |
| 8 ms |  | 0.6 ms | 0.2 ms | 🥵 | 2048 MB |
| 102.9 ms | 24.3 ms | 0.6 ms | 0.2 ms | 🥶 | 2048 MB |
| 4.9 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 101.9 ms | 20.3 ms | 0.6 ms | 0.4 ms | 🥶 | 2048 MB |
| 27 ms |  | 0.6 ms | 18.8 ms | 🥵 | 2048 MB |
| 105 ms | 26.8 ms | 0.6 ms | 0.2 ms | 🥶 | 2048 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 95.9 ms | 25.2 ms | 0.5 ms | 0.4 ms | 🥶 | 2048 MB |
| 7 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 108 ms | 28.9 ms | 0.8 ms | 0.1 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 5 ms |  | 0.2 ms | 0.2 ms | 🥵 | 2048 MB |
| 10 ms |  | 3.7 ms | 0.1 ms | 🥵 | 2048 MB |
| 52.9 ms |  | 46.6 ms | 0.6 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 95.9 ms | 30.9 ms | 0.4 ms | 0.3 ms | 🥶 | 2048 MB |
| 106.9 ms | 27.6 ms | 0.5 ms | 0.3 ms | 🥶 | 2048 MB |
| 21 ms |  | 13.2 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 32.9 ms |  | 8 ms | 19.9 ms | 🥵 | 2048 MB |
| 5 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 92.9 ms | 18.2 ms | 0.5 ms | 0.4 ms | 🥶 | 2048 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 117 ms | 25 ms | 0.4 ms | 7.1 ms | 🥶 | 2048 MB |
| 13 ms |  | 5.8 ms | 0.5 ms | 🥵 | 2048 MB |
| 4.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 7 ms |  | 0.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 90 ms | 23.5 ms | 0.5 ms | 0.4 ms | 🥶 | 2048 MB |
| 89.9 ms | 18.1 ms | 0.4 ms | 0.2 ms | 🥶 | 2048 MB |
| 148 ms | 28.8 ms | 0.5 ms | 0.5 ms | 🥶 | 2048 MB |
| 114 ms | 28.5 ms | 0.6 ms | 0.1 ms | 🥶 | 2048 MB |
| 109.9 ms | 26.4 ms | 0.6 ms | 0.2 ms | 🥶 | 2048 MB |
| 109.9 ms | 18.4 ms | 0.4 ms | 0.1 ms | 🥶 | 2048 MB |## Results for 3072 MB

| Measurement (3072 MB) | Time (ms) |
|-------------|------|
| Average warm start response time | 6.9 ms |
| Average cold start response time | 114 ms |
| Fastest warm response time | 4.9 ms |
| Slowest warm response time | 151.9 ms |
| Fastest cold response time  | 75 ms |
| Slowest cold response time | 310 ms |
  

| Response time | Initialization | Invocation | Overhead | Cold/ Warm Start | Memory Size |
|---------------|----------------|------------|----------|------------------|-------------|
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 88.9 ms | 18.8 ms | 0.4 ms | 0.4 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 107 ms | 28.7 ms | 0.6 ms | 0.1 ms | 🥶 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 93.9 ms | 18 ms | 0.3 ms | 0.1 ms | 🥶 | 3072 MB |
| 92 ms | 20.9 ms | 0.6 ms | 0.1 ms | 🥶 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 129.9 ms | 31.8 ms | 0.4 ms | 0.2 ms | 🥶 | 3072 MB |
| 7 ms |  | 0.4 ms | 0 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 98.9 ms | 27.2 ms | 0.4 ms | 0.2 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.4 ms | 🥵 | 3072 MB |
| 5 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 91 ms | 26.9 ms | 0.6 ms | 0.4 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 101.9 ms | 18.5 ms | 0.5 ms | 0.3 ms | 🥶 | 3072 MB |
| 6 ms |  | 0.5 ms | 0.2 ms | 🥵 | 3072 MB |
| 16 ms |  | 8.9 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 91 ms | 23.2 ms | 0.5 ms | 0.2 ms | 🥶 | 3072 MB |
| 5 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 98 ms | 17.2 ms | 0.4 ms | 0.1 ms | 🥶 | 3072 MB |
| 88 ms | 22.5 ms | 0.6 ms | 0.1 ms | 🥶 | 3072 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 23.9 ms |  | 0.4 ms | 18 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 3072 MB |
| 33.9 ms |  | 27.7 ms | 0.2 ms | 🥵 | 3072 MB |
| 89.9 ms | 21.6 ms | 0.6 ms | 0.1 ms | 🥶 | 3072 MB |
| 100 ms | 20.3 ms | 0.5 ms | 0.2 ms | 🥶 | 3072 MB |
| 7 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 25 ms |  | 18.4 ms | 0.3 ms | 🥵 | 3072 MB |
| 19.9 ms |  | 0.6 ms | 0.3 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.7 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.3 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 5.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 84 ms | 18.7 ms | 0.4 ms | 0.2 ms | 🥶 | 3072 MB |
| 98 ms | 17.7 ms | 0.6 ms | 0.3 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 101.9 ms | 21.1 ms | 0.6 ms | 0.2 ms | 🥶 | 3072 MB |
| 147 ms | 18.6 ms | 0.5 ms | 0.2 ms | 🥶 | 3072 MB |
| 5 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 108.9 ms | 24.5 ms | 0.7 ms | 0.2 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 97 ms | 27.9 ms | 0.5 ms | 0.2 ms | 🥶 | 3072 MB |
| 115.9 ms | 19.2 ms | 0.5 ms | 0.3 ms | 🥶 | 3072 MB |
| 90.9 ms | 19.8 ms | 0.6 ms | 0.5 ms | 🥶 | 3072 MB |
| 102.9 ms | 20.2 ms | 0.5 ms | 0.3 ms | 🥶 | 3072 MB |
| 108 ms | 30.5 ms | 0.4 ms | 0.2 ms | 🥶 | 3072 MB |
| 134 ms | 19.4 ms | 0.7 ms | 0.2 ms | 🥶 | 3072 MB |
| 89 ms | 19.6 ms | 0.5 ms | 0.3 ms | 🥶 | 3072 MB |
| 95.9 ms | 25.4 ms | 0.7 ms | 0.2 ms | 🥶 | 3072 MB |
| 6 ms |  | 0.5 ms | 0 ms | 🥵 | 3072 MB |
| 23.9 ms |  | 18.6 ms | 0.1 ms | 🥵 | 3072 MB |
| 105 ms | 19.3 ms | 0.7 ms | 0.2 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 5 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 27 ms |  | 20.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 95.9 ms | 29.7 ms | 0.5 ms | 0.1 ms | 🥶 | 3072 MB |
| 36.9 ms |  | 31.9 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 9.9 ms |  | 4.1 ms | 0.6 ms | 🥵 | 3072 MB |
| 16 ms |  | 0.7 ms | 0.4 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 85.9 ms | 18.4 ms | 0.6 ms | 0.4 ms | 🥶 | 3072 MB |
| 6 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 85.9 ms | 18.1 ms | 0.4 ms | 0.2 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 3072 MB |
| 5 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 85.9 ms | 21.9 ms | 0.5 ms | 0.1 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 3072 MB |
| 95 ms | 18.5 ms | 0.5 ms | 0.1 ms | 🥶 | 3072 MB |
| 98.9 ms | 27.6 ms | 0.5 ms | 0.2 ms | 🥶 | 3072 MB |
| 4.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 21 ms |  | 14.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 13.9 ms |  | 6.9 ms | 0.1 ms | 🥵 | 3072 MB |
| 93.9 ms | 18.7 ms | 0.6 ms | 0.2 ms | 🥶 | 3072 MB |
| 98 ms | 26.9 ms | 0.8 ms | 0.2 ms | 🥶 | 3072 MB |
| 89.9 ms | 23.1 ms | 0.5 ms | 0.1 ms | 🥶 | 3072 MB |
| 102.9 ms | 20.1 ms | 0.5 ms | 0.3 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 83 ms | 20 ms | 0.7 ms | 0.4 ms | 🥶 | 3072 MB |
| 4.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 43.9 ms |  | 37.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 91 ms | 19.9 ms | 0.4 ms | 0.1 ms | 🥶 | 3072 MB |
| 6 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 23.9 ms |  | 16.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 123 ms | 19.5 ms | 0.6 ms | 0.1 ms | 🥶 | 3072 MB |
| 9.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.5 ms | 0 ms | 🥵 | 3072 MB |
| 7 ms |  | 0.4 ms | 0 ms | 🥵 | 3072 MB |
| 90 ms | 20.7 ms | 0.5 ms | 0.1 ms | 🥶 | 3072 MB |
| 4.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 13.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 100.9 ms | 29.9 ms | 0.6 ms | 0.3 ms | 🥶 | 3072 MB |
| 90.9 ms | 25 ms | 0.5 ms | 0.4 ms | 🥶 | 3072 MB |
| 4.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 82.9 ms | 18.4 ms | 0.6 ms | 0.4 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.5 ms | 0 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.5 ms | 0 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.3 ms | 0.3 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 38 ms |  | 32.8 ms | 0.3 ms | 🥵 | 3072 MB |
| 40 ms |  | 14.7 ms | 19.8 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.4 ms | 0 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.5 ms | 0.2 ms | 🥵 | 3072 MB |
| 91 ms | 23.4 ms | 0.3 ms | 0.3 ms | 🥶 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 24.9 ms |  | 18.8 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 11 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 85.9 ms | 26 ms | 0.4 ms | 0.2 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 126.9 ms | 32.4 ms | 0.5 ms | 0.2 ms | 🥶 | 3072 MB |
| 102.9 ms | 23.2 ms | 0.7 ms | 0.1 ms | 🥶 | 3072 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 10.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 18 ms |  | 10 ms | 0.4 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 24 ms |  | 16.9 ms | 0.1 ms | 🥵 | 3072 MB |
| 33.9 ms |  | 28.1 ms | 0.3 ms | 🥵 | 3072 MB |
| 93.9 ms | 25.3 ms | 0.4 ms | 0.2 ms | 🥶 | 3072 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 16 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 5.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 95 ms | 20.3 ms | 0.7 ms | 0.3 ms | 🥶 | 3072 MB |
| 16 ms |  | 10.2 ms | 0.2 ms | 🥵 | 3072 MB |
| 107 ms | 26.8 ms | 0.5 ms | 0.2 ms | 🥶 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.3 ms | 🥵 | 3072 MB |
| 4.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 11 ms |  | 3.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 14 ms |  | 7.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 95 ms | 20.6 ms | 1 ms | 0.6 ms | 🥶 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 88.9 ms | 23.8 ms | 0.4 ms | 0.2 ms | 🥶 | 3072 MB |
| 103 ms | 24.5 ms | 0.4 ms | 0.4 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 177.9 ms | 18.6 ms | 0.5 ms | 0.3 ms | 🥶 | 3072 MB |
| 107 ms | 18.9 ms | 0.6 ms | 0.3 ms | 🥶 | 3072 MB |
| 101.9 ms | 22.9 ms | 0.5 ms | 0.1 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.6 ms | 0.3 ms | 🥵 | 3072 MB |
| 9.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 3072 MB |
| 118.9 ms | 26.7 ms | 0.4 ms | 0.3 ms | 🥶 | 3072 MB |
| 91 ms | 22 ms | 0.3 ms | 0.2 ms | 🥶 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 59 ms |  | 40.2 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 5.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 88 ms |  | 81.4 ms | 0 ms | 🥵 | 3072 MB |
| 89.9 ms | 24.7 ms | 0.6 ms | 0.2 ms | 🥶 | 3072 MB |
| 11.9 ms |  | 4.5 ms | 0.2 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 7 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 82 ms | 25.3 ms | 0.4 ms | 0.1 ms | 🥶 | 3072 MB |
| 97.9 ms | 18.4 ms | 0.5 ms | 0.1 ms | 🥶 | 3072 MB |
| 7.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 20.9 ms |  | 14 ms | 0.1 ms | 🥵 | 3072 MB |
| 105 ms | 20.7 ms | 0.8 ms | 0.4 ms | 🥶 | 3072 MB |
| 7.9 ms |  | 0.3 ms | 0.3 ms | 🥵 | 3072 MB |
| 9.9 ms |  | 3.2 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 108 ms | 18.6 ms | 0.4 ms | 0.1 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 23 ms |  | 18.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 5 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 105 ms | 19.4 ms | 0.6 ms | 0.4 ms | 🥶 | 3072 MB |
| 8 ms |  | 0.6 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 16.9 ms |  | 10.9 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.5 ms | 0.4 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 15 ms |  | 8.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 92 ms |  | 84.5 ms | 0.3 ms | 🥵 | 3072 MB |
| 20.9 ms |  | 13.9 ms | 0.1 ms | 🥵 | 3072 MB |
| 80.9 ms | 18.3 ms | 0.7 ms | 0.1 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 95 ms | 20.5 ms | 0.6 ms | 0.2 ms | 🥶 | 3072 MB |
| 82.9 ms | 17.1 ms | 0.3 ms | 0.1 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 133 ms | 18.4 ms | 0.4 ms | 0.2 ms | 🥶 | 3072 MB |
| 5 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 119.9 ms | 23.2 ms | 0.6 ms | 0.3 ms | 🥶 | 3072 MB |
| 105 ms | 22.3 ms | 0.6 ms | 0.3 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 90 ms | 20 ms | 0.5 ms | 0.1 ms | 🥶 | 3072 MB |
| 16.9 ms |  | 10.2 ms | 0.2 ms | 🥵 | 3072 MB |
| 91 ms | 18 ms | 0.5 ms | 0.1 ms | 🥶 | 3072 MB |
| 92 ms | 25.9 ms | 0.5 ms | 0.6 ms | 🥶 | 3072 MB |
| 9.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 101 ms | 23.2 ms | 0.5 ms | 0.6 ms | 🥶 | 3072 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 26 ms |  | 17.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 110.9 ms | 19.7 ms | 0.5 ms | 0.2 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.5 ms | 0.2 ms | 🥵 | 3072 MB |
| 9 ms |  | 2.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  |  |  | 🥵 | 3072 MB |
| 95.9 ms | 24.6 ms | 0.7 ms | 0.2 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 99.9 ms | 31.7 ms | 0.5 ms | 0.1 ms | 🥶 | 3072 MB |
| 8 ms |  | 0.4 ms | 0 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 98 ms | 29 ms | 0.5 ms | 0.4 ms | 🥶 | 3072 MB |
| 4.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 25 ms |  | 18 ms | 0.1 ms | 🥵 | 3072 MB |
| 105 ms | 27.2 ms | 0.3 ms | 0.1 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 23 ms |  | 15.1 ms | 0 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 54.9 ms |  | 48.5 ms | 0.3 ms | 🥵 | 3072 MB |
| 9.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 3072 MB |
| 13.9 ms |  | 9.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 105 ms | 28.2 ms | 0.5 ms | 0.2 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 2.8 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 50.9 ms |  | 0.5 ms | 39.5 ms | 🥵 | 3072 MB |
| 99.9 ms | 19.4 ms | 0.5 ms | 0.1 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 101.9 ms | 24 ms | 0.7 ms | 0.4 ms | 🥶 | 3072 MB |
| 94 ms | 19.6 ms | 0.5 ms | 0.5 ms | 🥶 | 3072 MB |
| 103 ms | 18.3 ms | 0.6 ms | 0.3 ms | 🥶 | 3072 MB |
| 105 ms | 26.8 ms | 0.7 ms | 0.6 ms | 🥶 | 3072 MB |
| 44 ms |  | 36.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 92.9 ms | 25.7 ms | 0.4 ms | 0.1 ms | 🥶 | 3072 MB |
| 8 ms |  | 0.5 ms | 0.4 ms | 🥵 | 3072 MB |
| 18.9 ms |  | 11.5 ms | 0.3 ms | 🥵 | 3072 MB |
| 94 ms | 27.4 ms | 0.5 ms | 0.1 ms | 🥶 | 3072 MB |
| 96.9 ms | 26.2 ms | 0.6 ms | 0.1 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 17.9 ms |  | 5.7 ms | 0.2 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 94 ms | 18.2 ms | 0.9 ms | 0.3 ms | 🥶 | 3072 MB |
| 115.9 ms | 19.9 ms | 0.6 ms | 0.4 ms | 🥶 | 3072 MB |
| 92 ms | 22.4 ms | 0.6 ms | 0.2 ms | 🥶 | 3072 MB |
| 113.9 ms | 22.3 ms | 0.5 ms | 0.2 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 88 ms | 18.7 ms | 0.4 ms | 0.1 ms | 🥶 | 3072 MB |
| 90.9 ms | 25.3 ms | 0.5 ms | 0.2 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 92.9 ms | 18.1 ms | 0.4 ms | 0.2 ms | 🥶 | 3072 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 100.9 ms | 30.2 ms | 0.4 ms | 0.4 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 3072 MB |
| 279 ms | 27.9 ms | 0.4 ms | 0.1 ms | 🥶 | 3072 MB |
| 45 ms |  | 39.7 ms | 0.1 ms | 🥵 | 3072 MB |
| 36.9 ms |  | 30.9 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 1.7 ms | 0.3 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 101 ms | 19.2 ms | 0.7 ms | 0.4 ms | 🥶 | 3072 MB |
| 5.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 112.9 ms | 25 ms | 0.8 ms | 0.2 ms | 🥶 | 3072 MB |
| 76.9 ms |  |  |  | 🥵 | 3072 MB |
| 98 ms | 18.7 ms | 0.5 ms | 0.1 ms | 🥶 | 3072 MB |
| 13 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 38 ms |  | 32.5 ms | 0.3 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 1.1 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 26.9 ms |  | 19.6 ms | 0.1 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 10.9 ms |  | 0.5 ms | 4.1 ms | 🥵 | 3072 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 15 ms |  | 8.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 13.9 ms |  | 8.6 ms | 0.1 ms | 🥵 | 3072 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 4.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 107 ms | 25.8 ms | 0.6 ms | 0.1 ms | 🥶 | 3072 MB |
| 82.9 ms | 21.9 ms | 0.6 ms | 0.4 ms | 🥶 | 3072 MB |
| 8 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 16.9 ms |  | 9.9 ms | 0.2 ms | 🥵 | 3072 MB |
| 24.9 ms |  | 19.1 ms | 0.2 ms | 🥵 | 3072 MB |
| 89.9 ms | 26.2 ms | 0.6 ms | 0.3 ms | 🥶 | 3072 MB |
| 7.9 ms |  | 0.4 ms | 0.3 ms | 🥵 | 3072 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.7 ms | 0.1 ms | 🥵 | 3072 MB |
| 96.9 ms | 24.2 ms | 0.7 ms | 0.2 ms | 🥶 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 23.9 ms |  | 17.1 ms | 0.1 ms | 🥵 | 3072 MB |
| 7 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 115.9 ms | 18.7 ms | 0.5 ms | 0.3 ms | 🥶 | 3072 MB |
| 101.9 ms | 18.8 ms | 0.5 ms | 0.3 ms | 🥶 | 3072 MB |
| 5 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 98.9 ms | 25.9 ms | 0.6 ms | 0.2 ms | 🥶 | 3072 MB |
| 21 ms |  | 14.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 98.9 ms | 22 ms | 0.5 ms | 0.1 ms | 🥶 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 3072 MB |
| 59.9 ms |  | 33.6 ms | 19.9 ms | 🥵 | 3072 MB |
| 99.9 ms | 25.3 ms | 0.5 ms | 0.5 ms | 🥶 | 3072 MB |
| 8 ms |  | 0.5 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.3 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 107 ms | 20 ms | 0.8 ms | 0.1 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 1.2 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 88 ms | 26.4 ms | 0.5 ms | 0.2 ms | 🥶 | 3072 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 7 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.5 ms | 0.4 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 21 ms |  | 15.2 ms | 0.2 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 10.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 1.5 ms | 0.3 ms | 🥵 | 3072 MB |
| 105.9 ms | 20 ms | 0.5 ms | 0.1 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.6 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 4.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 4.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.8 ms | 0.2 ms | 🥵 | 3072 MB |
| 19.9 ms |  | 12.6 ms | 0.3 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 84 ms | 20.6 ms | 0.4 ms | 0.2 ms | 🥶 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 23 ms |  | 17 ms | 0 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 3072 MB |
| 102.9 ms | 27.1 ms | 0.5 ms | 0.5 ms | 🥶 | 3072 MB |
| 5.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 18.9 ms |  | 12.8 ms | 0.2 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.4 ms | 0 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 97.9 ms | 27.6 ms | 0.5 ms | 0.4 ms | 🥶 | 3072 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 8.9 ms |  | 0.6 ms | 0.2 ms | 🥵 | 3072 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 7 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 23 ms |  | 16.2 ms | 0.2 ms | 🥵 | 3072 MB |
| 5.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 91 ms | 20.2 ms | 0.5 ms | 0.3 ms | 🥶 | 3072 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 105 ms | 28 ms | 0.5 ms | 0.3 ms | 🥶 | 3072 MB |
| 98 ms | 19.3 ms | 0.5 ms | 0.2 ms | 🥶 | 3072 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 21.9 ms |  | 15.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 29.9 ms |  | 23.1 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 99.9 ms | 27.1 ms | 0.7 ms | 0.2 ms | 🥶 | 3072 MB |
| 310 ms | 18.5 ms | 0.5 ms | 0.3 ms | 🥶 | 3072 MB |
| 95 ms | 23 ms | 0.5 ms | 0.3 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 5.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 54 ms |  | 40.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.5 ms | 0 ms | 🥵 | 3072 MB |
| 32.9 ms |  | 25.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 16.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 111 ms | 23 ms | 0.4 ms | 0.2 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 5 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 20 ms |  | 12 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 17.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 3072 MB |
| 127.9 ms | 21.7 ms | 0.6 ms | 0.1 ms | 🥶 | 3072 MB |
| 91 ms | 18.5 ms | 0.5 ms | 0.2 ms | 🥶 | 3072 MB |
| 13.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 119 ms | 27.9 ms | 0.4 ms | 0.2 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.7 ms | 0.2 ms | 🥵 | 3072 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 64 ms |  | 17.3 ms | 39.8 ms | 🥵 | 3072 MB |
| 38 ms |  | 9.9 ms | 19.8 ms | 🥵 | 3072 MB |
| 13 ms |  | 6.1 ms | 0.1 ms | 🥵 | 3072 MB |
| 88.9 ms | 23.6 ms | 0.3 ms | 0 ms | 🥶 | 3072 MB |
| 41 ms |  | 33.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 97 ms | 31.8 ms | 0.4 ms | 0.2 ms | 🥶 | 3072 MB |
| 8 ms |  | 0.6 ms | 0.3 ms | 🥵 | 3072 MB |
| 13.9 ms |  | 8.2 ms | 0.2 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 96.9 ms | 17.9 ms | 0.5 ms | 0.3 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 154 ms | 25.4 ms | 0.4 ms | 0.5 ms | 🥶 | 3072 MB |
| 27.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 87.9 ms | 19 ms | 0.6 ms | 0.5 ms | 🥶 | 3072 MB |
| 9.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 80 ms |  | 73.7 ms | 0.1 ms | 🥵 | 3072 MB |
| 11.9 ms |  | 4.9 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0 ms | 🥵 | 3072 MB |
| 106 ms | 23.6 ms | 0.5 ms | 0.3 ms | 🥶 | 3072 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 88.9 ms | 19.4 ms | 0.4 ms | 0.1 ms | 🥶 | 3072 MB |
| 5 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 39 ms |  | 32.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 103 ms | 29.9 ms | 0.5 ms | 0.1 ms | 🥶 | 3072 MB |
| 111 ms | 24.3 ms | 0.7 ms | 0.3 ms | 🥶 | 3072 MB |
| 7 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 13.9 ms |  | 8.6 ms | 0.3 ms | 🥵 | 3072 MB |
| 18 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 5.9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 94.9 ms | 31.5 ms | 0.7 ms | 0.2 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.6 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 92 ms | 22.9 ms | 0.4 ms | 0.2 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 101 ms | 25.2 ms | 0.6 ms | 1.5 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.5 ms | 0 ms | 🥵 | 3072 MB |
| 95 ms | 17.3 ms | 0.4 ms | 0.3 ms | 🥶 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 118.9 ms | 20 ms | 0.5 ms | 0.4 ms | 🥶 | 3072 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 78.9 ms | 24.9 ms | 0.5 ms | 0.3 ms | 🥶 | 3072 MB |
| 7.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 96.9 ms | 20.8 ms | 0.7 ms | 0.3 ms | 🥶 | 3072 MB |
| 9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 98.9 ms | 18.2 ms | 0.6 ms | 0.1 ms | 🥶 | 3072 MB |
| 98 ms | 18.9 ms | 0.6 ms | 0.4 ms | 🥶 | 3072 MB |
| 21.9 ms |  | 8.2 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 26.9 ms |  | 20.2 ms | 0.1 ms | 🥵 | 3072 MB |
| 128 ms | 25.6 ms | 0.7 ms | 0.3 ms | 🥶 | 3072 MB |
| 151.9 ms |  | 80 ms | 59.9 ms | 🥵 | 3072 MB |
| 23.9 ms |  | 18.6 ms | 0.2 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 20.9 ms |  | 13.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 97 ms | 32 ms | 0.4 ms | 0.7 ms | 🥶 | 3072 MB |
| 12 ms |  | 4.9 ms | 0.1 ms | 🥵 | 3072 MB |
| 100.9 ms | 19.8 ms | 0.6 ms | 0 ms | 🥶 | 3072 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.7 ms | 0.1 ms | 🥵 | 3072 MB |
| 7 ms |  | 0.5 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 85 ms |  | 79.8 ms | 0.7 ms | 🥵 | 3072 MB |
| 12 ms |  | 5.1 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 108.9 ms | 19.6 ms | 0.5 ms | 0.4 ms | 🥶 | 3072 MB |
| 18.9 ms |  | 13.8 ms | 0.1 ms | 🥵 | 3072 MB |
| 85 ms |  | 77.7 ms | 0.2 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 16 ms |  | 10.2 ms | 0 ms | 🥵 | 3072 MB |
| 108 ms | 24.5 ms | 0.5 ms | 0.1 ms | 🥶 | 3072 MB |
| 111 ms | 25 ms | 0.7 ms | 0.3 ms | 🥶 | 3072 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 53.9 ms |  | 39.9 ms | 0.3 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 12 ms |  | 5.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 98.9 ms | 25.7 ms | 0.3 ms | 0.3 ms | 🥶 | 3072 MB |
| 95 ms | 25 ms | 0.4 ms | 0.1 ms | 🥶 | 3072 MB |
| 125.9 ms | 26 ms | 0.7 ms | 0.1 ms | 🥶 | 3072 MB |
| 92 ms | 23.8 ms | 0.4 ms | 0.3 ms | 🥶 | 3072 MB |
| 116.9 ms | 18.7 ms | 0.5 ms | 0 ms | 🥶 | 3072 MB |
| 16.9 ms |  | 10.4 ms | 0.5 ms | 🥵 | 3072 MB |
| 108 ms | 32.5 ms | 0.5 ms | 0.5 ms | 🥶 | 3072 MB |
| 23 ms |  | 18.6 ms | 0.1 ms | 🥵 | 3072 MB |
| 96 ms | 29.8 ms | 0.5 ms | 0.4 ms | 🥶 | 3072 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 9 ms |  | 0.6 ms | 0.2 ms | 🥵 | 3072 MB |
| 13 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 97 ms | 27.4 ms | 0.4 ms | 0.3 ms | 🥶 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.4 ms | 0.3 ms | 🥵 | 3072 MB |
| 105.9 ms | 30.4 ms | 0.7 ms | 0.2 ms | 🥶 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 7 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 24.9 ms |  | 18 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 118 ms | 28.7 ms | 0.4 ms | 0.2 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 105.9 ms | 22.1 ms | 0.7 ms | 0.5 ms | 🥶 | 3072 MB |
| 110 ms | 18.6 ms | 0.9 ms | 0.4 ms | 🥶 | 3072 MB |
| 75 ms | 22 ms | 0.4 ms | 0 ms | 🥶 | 3072 MB |
| 112.9 ms | 19.2 ms | 0.5 ms | 0.2 ms | 🥶 | 3072 MB |
| 23 ms |  | 15.8 ms | 1.4 ms | 🥵 | 3072 MB |
| 94 ms | 22.9 ms | 0.7 ms | 0.3 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.6 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 20 ms |  | 12.5 ms | 0 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.6 ms | 0.3 ms | 🥵 | 3072 MB |
| 97 ms | 22.2 ms | 0.4 ms | 0.2 ms | 🥶 | 3072 MB |
| 11.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 23 ms |  | 16.6 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 19.9 ms |  | 13.8 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 115 ms | 27.1 ms | 0.4 ms | 0.1 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 5 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 5 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 26 ms |  | 19.9 ms | 0.2 ms | 🥵 | 3072 MB |
| 9 ms |  | 0.3 ms | 0.3 ms | 🥵 | 3072 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.5 ms | 0.3 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 146.9 ms | 28.7 ms | 0.4 ms | 0.2 ms | 🥶 | 3072 MB |
| 42 ms |  | 15.8 ms | 19.7 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 93.9 ms | 19.9 ms | 0.6 ms | 0 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 90 ms | 25.8 ms | 0.6 ms | 0.1 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 12 ms |  | 0.4 ms | 0 ms | 🥵 | 3072 MB |
| 128 ms | 20.1 ms | 0.5 ms | 0.2 ms | 🥶 | 3072 MB |
| 101 ms |  |  |  | 🥵 | 3072 MB |
| 4.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 97 ms | 21.3 ms | 0.7 ms | 0.1 ms | 🥶 | 3072 MB |
| 138 ms | 22.7 ms | 0.5 ms | 0.1 ms | 🥶 | 3072 MB |
| 101.9 ms | 25 ms | 0.5 ms | 0.1 ms | 🥶 | 3072 MB |
| 95.9 ms | 22.2 ms | 0.8 ms | 0.2 ms | 🥶 | 3072 MB |
| 89.9 ms | 25.1 ms | 0.3 ms | 0.1 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 105.9 ms | 20.7 ms | 0.4 ms | 0.3 ms | 🥶 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 5.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.4 ms | 0 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.3 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 119 ms | 20.2 ms | 0.5 ms | 0.2 ms | 🥶 | 3072 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 90.9 ms | 25 ms | 0.6 ms | 0.3 ms | 🥶 | 3072 MB |
| 94 ms | 18.6 ms | 0.6 ms | 0 ms | 🥶 | 3072 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 125 ms | 26.2 ms | 0.6 ms | 0.4 ms | 🥶 | 3072 MB |
| 95.9 ms | 19.7 ms | 0.5 ms | 0.2 ms | 🥶 | 3072 MB |
| 102.9 ms | 18.9 ms | 0.5 ms | 0.3 ms | 🥶 | 3072 MB |
| 13.9 ms |  | 0.8 ms | 0.5 ms | 🥵 | 3072 MB |
| 98 ms | 17.7 ms | 0.6 ms | 0.3 ms | 🥶 | 3072 MB |
| 8 ms |  | 0.4 ms | 0.3 ms | 🥵 | 3072 MB |
| 91 ms | 21.6 ms | 0.7 ms | 0.2 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.6 ms | 0 ms | 🥵 | 3072 MB |
| 82 ms | 17.9 ms | 0.3 ms | 0.1 ms | 🥶 | 3072 MB |
| 6 ms |  | 0.5 ms | 0.2 ms | 🥵 | 3072 MB |
| 8.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 11 ms |  | 5.5 ms | 0.2 ms | 🥵 | 3072 MB |
| 88.9 ms | 25 ms | 0.6 ms | 0.4 ms | 🥶 | 3072 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 103.9 ms | 23.8 ms | 0.7 ms | 0.3 ms | 🥶 | 3072 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 15 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 23.9 ms |  | 18 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.6 ms | 0.1 ms | 🥵 | 3072 MB |
| 101 ms | 27.5 ms | 0.6 ms | 0.3 ms | 🥶 | 3072 MB |
| 8 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 99.9 ms | 23.5 ms | 0.6 ms | 0.4 ms | 🥶 | 3072 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.4 ms | 0 ms | 🥵 | 3072 MB |
| 93.9 ms | 28 ms | 0.4 ms | 0.3 ms | 🥶 | 3072 MB |
| 96.9 ms | 22.1 ms | 0.5 ms | 0.2 ms | 🥶 | 3072 MB |
| 21.9 ms |  | 14.2 ms | 0.4 ms | 🥵 | 3072 MB |
| 42 ms |  | 35 ms | 0 ms | 🥵 | 3072 MB |
| 5.9 ms |  | 0.2 ms | 0.4 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 125.9 ms | 19.8 ms | 0.8 ms | 0.4 ms | 🥶 | 3072 MB |
| 7.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 97 ms | 30.8 ms | 0.8 ms | 0.5 ms | 🥶 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 135.9 ms | 20 ms | 0.6 ms | 0.1 ms | 🥶 | 3072 MB |
| 98 ms | 25.8 ms | 0.8 ms | 0.3 ms | 🥶 | 3072 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 100 ms | 27.2 ms | 0.6 ms | 0.2 ms | 🥶 | 3072 MB |
| 38.9 ms |  | 11.9 ms | 20 ms | 🥵 | 3072 MB |
| 95 ms | 20.4 ms | 0.8 ms | 0.3 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 3.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 119.9 ms | 35 ms | 0.4 ms | 0.7 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.3 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 121 ms | 33.5 ms | 15.7 ms | 0.5 ms | 🥶 | 3072 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 21.9 ms |  | 15.7 ms | 0.2 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 86.9 ms |  | 81.1 ms | 0.3 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 93 ms | 26.2 ms | 1 ms | 0.4 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 39.9 ms |  | 13.3 ms | 19.5 ms | 🥵 | 3072 MB |
| 16 ms |  | 0.8 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 1.8 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 87 ms | 18.2 ms | 0.8 ms | 0.4 ms | 🥶 | 3072 MB |
| 8 ms |  | 0.5 ms | 0.2 ms | 🥵 | 3072 MB |
| 100.9 ms | 23 ms | 0.5 ms | 0.2 ms | 🥶 | 3072 MB |
| 16 ms |  | 0.5 ms | 0.2 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 5 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 16.9 ms |  | 9.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 109 ms |  | 80 ms | 19.9 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 94 ms | 28.4 ms | 0.9 ms | 0.2 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 25 ms |  | 19.1 ms | 0.7 ms | 🥵 | 3072 MB |
| 88 ms | 28.7 ms | 0.5 ms | 0.3 ms | 🥶 | 3072 MB |
| 8.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 103.9 ms | 33.1 ms | 0.7 ms | 0.2 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 42 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 103.9 ms | 19.6 ms | 0.9 ms | 0.6 ms | 🥶 | 3072 MB |
| 18 ms |  | 11 ms | 0.1 ms | 🥵 | 3072 MB |
| 23.9 ms |  | 17.1 ms | 0.2 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 85 ms | 22.6 ms | 0.4 ms | 0.1 ms | 🥶 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 7 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 7 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 99.9 ms | 19.8 ms | 0.5 ms | 0.2 ms | 🥶 | 3072 MB |
| 19 ms |  | 0.6 ms | 0.2 ms | 🥵 | 3072 MB |
| 7 ms |  | 0.6 ms | 0.3 ms | 🥵 | 3072 MB |
| 95 ms | 18.6 ms | 0.5 ms | 0.1 ms | 🥶 | 3072 MB |
| 8.9 ms |  | 0.4 ms | 0 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 29 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 109 ms | 18.3 ms | 0.6 ms | 0.4 ms | 🥶 | 3072 MB |
| 98.9 ms | 19.4 ms | 0.4 ms | 0 ms | 🥶 | 3072 MB |
| 88 ms | 19.8 ms | 0.6 ms | 0.5 ms | 🥶 | 3072 MB |
| 5 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 99.9 ms | 26.2 ms | 0.3 ms | 0.3 ms | 🥶 | 3072 MB |
| 10.9 ms |  | 4.9 ms | 0.2 ms | 🥵 | 3072 MB |
| 204.9 ms | 30.2 ms | 0.5 ms | 0.1 ms | 🥶 | 3072 MB |
| 15 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 87.9 ms | 23.6 ms | 0.5 ms | 0.4 ms | 🥶 | 3072 MB |
| 7.9 ms |  | 0.6 ms | 0.1 ms | 🥵 | 3072 MB |
| 98.9 ms | 18.4 ms | 0.5 ms | 0.3 ms | 🥶 | 3072 MB |
| 14 ms |  | 6.2 ms | 0.1 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.3 ms | 🥵 | 3072 MB |
| 79.9 ms | 23.4 ms | 0.4 ms | 0.4 ms | 🥶 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 5 ms |  | 0.4 ms | 0 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 19 ms |  | 12.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.3 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.3 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.5 ms | 0 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 94 ms | 23.3 ms | 0.6 ms | 0.3 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.4 ms | 0 ms | 🥵 | 3072 MB |
| 97 ms | 20.1 ms | 0.7 ms | 0.3 ms | 🥶 | 3072 MB |
| 9 ms |  | 3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 87.9 ms | 22.3 ms | 0.5 ms | 0.2 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 4.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 118.9 ms | 41.8 ms | 0.4 ms | 0.4 ms | 🥶 | 3072 MB |
| 101 ms | 17.4 ms | 0.5 ms | 0.2 ms | 🥶 | 3072 MB |
| 11.9 ms |  | 6.6 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.7 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 7 ms |  | 0.4 ms | 0 ms | 🥵 | 3072 MB |
| 112.9 ms | 17.8 ms | 0.6 ms | 0.1 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 13.9 ms |  | 7.1 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.5 ms | 🥵 | 3072 MB |
| 23 ms |  | 18.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 78.9 ms | 17.9 ms | 0.5 ms | 0.1 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.6 ms | 0.1 ms | 🥵 | 3072 MB |
| 14 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 114 ms | 19 ms | 0.7 ms | 0.1 ms | 🥶 | 3072 MB |
| 117 ms |  | 91.5 ms | 19.7 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 99.9 ms | 28.5 ms | 0.4 ms | 0.2 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 99.9 ms | 29.8 ms | 0.4 ms | 0.2 ms | 🥶 | 3072 MB |
| 97 ms | 26.4 ms | 0.4 ms | 0.1 ms | 🥶 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 11.9 ms |  | 4.2 ms | 0.2 ms | 🥵 | 3072 MB |
| 67 ms |  | 20.2 ms | 39.6 ms | 🥵 | 3072 MB |
| 23 ms |  | 0.5 ms | 17.3 ms | 🥵 | 3072 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 128 ms | 22.3 ms | 0.6 ms | 0.2 ms | 🥶 | 3072 MB |
| 22 ms |  | 15.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 9 ms |  | 3.8 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0 ms | 🥵 | 3072 MB |
| 21.9 ms |  | 10.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 4.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 26.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 148 ms | 17.6 ms | 0.3 ms | 0.3 ms | 🥶 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 23.9 ms |  | 18.1 ms | 0.4 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.6 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 1.5 ms | 0 ms | 🥵 | 3072 MB |
| 101.9 ms | 22.4 ms | 0.6 ms | 0.2 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 89.9 ms | 19.4 ms | 0.4 ms | 0.4 ms | 🥶 | 3072 MB |
| 115 ms | 20.6 ms | 0.9 ms | 14.6 ms | 🥶 | 3072 MB |
| 104 ms | 21.5 ms | 0.6 ms | 0.2 ms | 🥶 | 3072 MB |
| 104 ms | 23.9 ms | 0.5 ms | 0.2 ms | 🥶 | 3072 MB |
| 9.9 ms |  | 2.9 ms | 0.8 ms | 🥵 | 3072 MB |
| 36.9 ms |  | 28.5 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 24.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 9 ms |  | 3.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 120 ms | 20.6 ms | 0.5 ms | 0.3 ms | 🥶 | 3072 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 3072 MB |
| 101.9 ms | 18.8 ms | 0.5 ms | 0.2 ms | 🥶 | 3072 MB |
| 96.9 ms | 26.1 ms | 0.5 ms | 0.3 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.7 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 99.9 ms | 27.3 ms | 0.4 ms | 0.1 ms | 🥶 | 3072 MB |
| 36.9 ms |  | 29.6 ms | 0.2 ms | 🥵 | 3072 MB |
| 113 ms | 31.6 ms | 0.6 ms | 0.5 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 30.9 ms |  | 24.4 ms | 0.3 ms | 🥵 | 3072 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 4.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 105 ms | 28.8 ms | 0.4 ms | 0.3 ms | 🥶 | 3072 MB |
| 17.9 ms |  | 9.1 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 96.9 ms | 20.2 ms | 0.6 ms | 0.5 ms | 🥶 | 3072 MB |
| 102.9 ms | 19.2 ms | 0.6 ms | 0.3 ms | 🥶 | 3072 MB |
| 18 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 98 ms | 18.3 ms | 0.6 ms | 0.1 ms | 🥶 | 3072 MB |
| 7 ms |  | 0.5 ms | 0.2 ms | 🥵 | 3072 MB |
| 36.9 ms |  | 10.8 ms | 19.9 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 92.9 ms | 26.2 ms | 0.6 ms | 3.1 ms | 🥶 | 3072 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 108.9 ms | 27.8 ms | 0.5 ms | 0.4 ms | 🥶 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 7 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 25 ms |  | 0.7 ms | 8.7 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.6 ms | 0.2 ms | 🥵 | 3072 MB |
| 13 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 26 ms |  | 18.5 ms | 0.2 ms | 🥵 | 3072 MB |
| 90.9 ms | 22.9 ms | 0.4 ms | 0.3 ms | 🥶 | 3072 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 68 ms |  | 60.7 ms | 0.2 ms | 🥵 | 3072 MB |
| 123.9 ms | 18.6 ms | 0.5 ms | 0.4 ms | 🥶 | 3072 MB |
| 21.9 ms |  | 15.7 ms | 0.2 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 9 ms |  | 2.2 ms | 0.7 ms | 🥵 | 3072 MB |
| 92 ms | 18.1 ms | 0.6 ms | 0.2 ms | 🥶 | 3072 MB |
| 9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 60.9 ms |  | 34.5 ms | 19.7 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 4.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 92 ms | 17.8 ms | 0.6 ms | 0.3 ms | 🥶 | 3072 MB |
| 8 ms |  | 0.6 ms | 0.1 ms | 🥵 | 3072 MB |
| 98.9 ms | 28.1 ms | 0.4 ms | 0.3 ms | 🥶 | 3072 MB |
| 7.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.3 ms | 🥵 | 3072 MB |
| 9.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 24 ms |  | 19.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.6 ms | 0.1 ms | 🥵 | 3072 MB |
| 22 ms |  | 14.9 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 129.9 ms | 25.2 ms | 0.9 ms | 0.2 ms | 🥶 | 3072 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 98.9 ms | 25.2 ms | 0.7 ms | 0.4 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 3072 MB |
| 15 ms |  | 8.8 ms | 0.1 ms | 🥵 | 3072 MB |
| 88 ms | 25.2 ms | 0.4 ms | 0.1 ms | 🥶 | 3072 MB |
| 108 ms | 17.1 ms | 0.4 ms | 0.4 ms | 🥶 | 3072 MB |
| 92.9 ms | 19.9 ms | 0.7 ms | 0.4 ms | 🥶 | 3072 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 4.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 79.9 ms | 22.3 ms | 0.4 ms | 0.4 ms | 🥶 | 3072 MB |
| 26.9 ms |  | 21.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 5 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 96.9 ms | 28.7 ms | 0.5 ms | 0.2 ms | 🥶 | 3072 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 9.9 ms |  | 4 ms | 0.1 ms | 🥵 | 3072 MB |
| 95 ms | 18.9 ms | 0.5 ms | 0.4 ms | 🥶 | 3072 MB |
| 92.9 ms | 22.3 ms | 0.4 ms | 0.1 ms | 🥶 | 3072 MB |
| 101 ms | 26.8 ms | 0.6 ms | 0.3 ms | 🥶 | 3072 MB |
| 8.9 ms |  | 0.4 ms | 0.4 ms | 🥵 | 3072 MB |
| 85 ms | 24.5 ms | 0.4 ms | 0.1 ms | 🥶 | 3072 MB |
| 8 ms |  | 0.6 ms | 0.2 ms | 🥵 | 3072 MB |
| 93.9 ms | 17.9 ms | 0.6 ms | 0.3 ms | 🥶 | 3072 MB |
| 59 ms |  | 40 ms | 0.2 ms | 🥵 | 3072 MB |
| 95 ms | 27.3 ms | 0.6 ms | 0.3 ms | 🥶 | 3072 MB |
| 87.9 ms | 21.4 ms | 0.6 ms | 0.5 ms | 🥶 | 3072 MB |
| 4.9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 102.9 ms | 24.3 ms | 0.6 ms | 0.2 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.3 ms | 🥵 | 3072 MB |
| 101.9 ms | 20.3 ms | 0.6 ms | 0.4 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 27 ms |  | 0.6 ms | 18.8 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 95.9 ms | 25.2 ms | 0.5 ms | 0.4 ms | 🥶 | 3072 MB |
| 105 ms | 26.8 ms | 0.6 ms | 0.2 ms | 🥶 | 3072 MB |
| 7 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.4 ms | 0 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 5 ms |  | 0.2 ms | 0.2 ms | 🥵 | 3072 MB |
| 108 ms | 28.9 ms | 0.8 ms | 0.1 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 52.9 ms |  | 46.6 ms | 0.6 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 106.9 ms | 27.6 ms | 0.5 ms | 0.3 ms | 🥶 | 3072 MB |
| 21 ms |  | 13.2 ms | 0.1 ms | 🥵 | 3072 MB |
| 10 ms |  | 3.7 ms | 0.1 ms | 🥵 | 3072 MB |
| 32.9 ms |  | 8 ms | 19.9 ms | 🥵 | 3072 MB |
| 95.9 ms | 30.9 ms | 0.4 ms | 0.3 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 117 ms | 25 ms | 0.4 ms | 7.1 ms | 🥶 | 3072 MB |
| 5 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 13 ms |  | 5.8 ms | 0.5 ms | 🥵 | 3072 MB |
| 4.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 92.9 ms | 18.2 ms | 0.5 ms | 0.4 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 7 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 90 ms | 23.5 ms | 0.5 ms | 0.4 ms | 🥶 | 3072 MB |
| 109.9 ms | 26.4 ms | 0.6 ms | 0.2 ms | 🥶 | 3072 MB |
| 89.9 ms | 18.1 ms | 0.4 ms | 0.2 ms | 🥶 | 3072 MB |
| 148 ms | 28.8 ms | 0.5 ms | 0.5 ms | 🥶 | 3072 MB |
| 114 ms | 28.5 ms | 0.6 ms | 0.1 ms | 🥶 | 3072 MB |
| 109.9 ms | 18.4 ms | 0.4 ms | 0.1 ms | 🥶 | 3072 MB |## Results for 4096 MB

| Measurement (4096 MB) | Time (ms) |
|-------------|------|
| Average warm start response time | 7.1 ms |
| Average cold start response time | 123.7 ms |
| Fastest warm response time | 4.9 ms |
| Slowest warm response time | 151.9 ms |
| Fastest cold response time  | 75 ms |
| Slowest cold response time | 310 ms |
  

| Response time | Initialization | Invocation | Overhead | Cold/ Warm Start | Memory Size |
|---------------|----------------|------------|----------|------------------|-------------|
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 88.9 ms | 18.8 ms | 0.4 ms | 0.4 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 93.9 ms | 18 ms | 0.3 ms | 0.1 ms | 🥶 | 4096 MB |
| 92 ms | 20.9 ms | 0.6 ms | 0.1 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 107 ms | 28.7 ms | 0.6 ms | 0.1 ms | 🥶 | 4096 MB |
| 7 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 4.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 129.9 ms | 31.8 ms | 0.4 ms | 0.2 ms | 🥶 | 4096 MB |
| 98.9 ms | 27.2 ms | 0.4 ms | 0.2 ms | 🥶 | 4096 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 91 ms | 26.9 ms | 0.6 ms | 0.4 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 5 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.4 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.5 ms | 0.2 ms | 🥵 | 4096 MB |
| 16 ms |  | 8.9 ms | 0.2 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 101.9 ms | 18.5 ms | 0.5 ms | 0.3 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 5 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 98 ms | 17.2 ms | 0.4 ms | 0.1 ms | 🥶 | 4096 MB |
| 97 ms | 17.8 ms | 0.5 ms | 0.3 ms | 🥶 | 4096 MB |
| 88 ms | 22.5 ms | 0.6 ms | 0.1 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.5 ms | 0.2 ms | 🥵 | 4096 MB |
| 23.9 ms |  | 0.4 ms | 18 ms | 🥵 | 4096 MB |
| 91 ms | 23.2 ms | 0.5 ms | 0.2 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 111.9 ms | 21.9 ms | 0.7 ms | 0.7 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 33.9 ms |  | 27.7 ms | 0.2 ms | 🥵 | 4096 MB |
| 89.9 ms | 21.6 ms | 0.6 ms | 0.1 ms | 🥶 | 4096 MB |
| 100 ms | 20.3 ms | 0.5 ms | 0.2 ms | 🥶 | 4096 MB |
| 7 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 25 ms |  | 18.4 ms | 0.3 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.7 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.3 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 19.9 ms |  | 0.6 ms | 0.3 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 5.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 98 ms | 17.7 ms | 0.6 ms | 0.3 ms | 🥶 | 4096 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 82 ms | 17.8 ms | 0.5 ms | 0.3 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 84 ms | 18.7 ms | 0.4 ms | 0.2 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 108.9 ms | 24.5 ms | 0.7 ms | 0.2 ms | 🥶 | 4096 MB |
| 5 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 101.9 ms | 21.1 ms | 0.6 ms | 0.2 ms | 🥶 | 4096 MB |
| 147 ms | 18.6 ms | 0.5 ms | 0.2 ms | 🥶 | 4096 MB |
| 8 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 97 ms | 27.9 ms | 0.5 ms | 0.2 ms | 🥶 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 134 ms | 19.4 ms | 0.7 ms | 0.2 ms | 🥶 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 115.9 ms | 19.2 ms | 0.5 ms | 0.3 ms | 🥶 | 4096 MB |
| 90.9 ms | 19.8 ms | 0.6 ms | 0.5 ms | 🥶 | 4096 MB |
| 102.9 ms | 20.2 ms | 0.5 ms | 0.3 ms | 🥶 | 4096 MB |
| 108 ms | 30.5 ms | 0.4 ms | 0.2 ms | 🥶 | 4096 MB |
| 89 ms | 19.6 ms | 0.5 ms | 0.3 ms | 🥶 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 95.9 ms | 25.4 ms | 0.7 ms | 0.2 ms | 🥶 | 4096 MB |
| 105 ms | 19.3 ms | 0.7 ms | 0.2 ms | 🥶 | 4096 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.5 ms | 0 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 23.9 ms |  | 18.6 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 78.9 ms | 18.3 ms | 0.6 ms | 0.1 ms | 🥶 | 4096 MB |
| 5 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 4.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 95.9 ms | 29.7 ms | 0.5 ms | 0.1 ms | 🥶 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 27 ms |  | 20.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 103 ms | 20.3 ms | 0.6 ms | 0.4 ms | 🥶 | 4096 MB |
| 36.9 ms |  | 31.9 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 9.9 ms |  | 4.1 ms | 0.6 ms | 🥵 | 4096 MB |
| 16 ms |  | 0.7 ms | 0.4 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 85.9 ms | 18.4 ms | 0.6 ms | 0.4 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 85.9 ms | 18.1 ms | 0.4 ms | 0.2 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 5 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 85.9 ms | 21.9 ms | 0.5 ms | 0.1 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 4096 MB |
| 12 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 95 ms | 18.5 ms | 0.5 ms | 0.1 ms | 🥶 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 4.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 98.9 ms | 27.6 ms | 0.5 ms | 0.2 ms | 🥶 | 4096 MB |
| 89.9 ms | 23.1 ms | 0.5 ms | 0.1 ms | 🥶 | 4096 MB |
| 98 ms | 26.9 ms | 0.8 ms | 0.2 ms | 🥶 | 4096 MB |
| 88.9 ms | 22.5 ms | 0.5 ms | 0.2 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 21 ms |  | 14.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 102.9 ms | 20.1 ms | 0.5 ms | 0.3 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 13.9 ms |  | 6.9 ms | 0.1 ms | 🥵 | 4096 MB |
| 93.9 ms | 18.7 ms | 0.6 ms | 0.2 ms | 🥶 | 4096 MB |
| 91 ms | 19.9 ms | 0.4 ms | 0.1 ms | 🥶 | 4096 MB |
| 83 ms | 20 ms | 0.7 ms | 0.4 ms | 🥶 | 4096 MB |
| 4.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 43.9 ms |  | 37.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.5 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 23.9 ms |  | 16.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 4.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 123 ms | 19.5 ms | 0.6 ms | 0.1 ms | 🥶 | 4096 MB |
| 9.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 90 ms | 20.7 ms | 0.5 ms | 0.1 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 13.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 4.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 100.9 ms | 29.9 ms | 0.6 ms | 0.3 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 90.9 ms | 25 ms | 0.5 ms | 0.4 ms | 🥶 | 4096 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.5 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 82.9 ms | 18.4 ms | 0.6 ms | 0.4 ms | 🥶 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.5 ms | 0 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.3 ms | 0.3 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 40 ms |  | 14.7 ms | 19.8 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 38 ms |  | 32.8 ms | 0.3 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 24.9 ms |  | 18.8 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.5 ms | 0.2 ms | 🥵 | 4096 MB |
| 91 ms | 23.4 ms | 0.3 ms | 0.3 ms | 🥶 | 4096 MB |
| 11 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 102.9 ms | 23.2 ms | 0.7 ms | 0.1 ms | 🥶 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 85.9 ms | 26 ms | 0.4 ms | 0.2 ms | 🥶 | 4096 MB |
| 126.9 ms | 32.4 ms | 0.5 ms | 0.2 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 8.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 10.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 18 ms |  | 10 ms | 0.4 ms | 🥵 | 4096 MB |
| 24 ms |  | 16.9 ms | 0.1 ms | 🥵 | 4096 MB |
| 33.9 ms |  | 28.1 ms | 0.3 ms | 🥵 | 4096 MB |
| 93.9 ms | 25.3 ms | 0.4 ms | 0.2 ms | 🥶 | 4096 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 16 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 5.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 4096 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 4.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 95 ms | 20.3 ms | 0.7 ms | 0.3 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 16 ms |  | 10.2 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 107 ms | 26.8 ms | 0.5 ms | 0.2 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.3 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 14 ms |  | 7.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 88.9 ms | 23.8 ms | 0.4 ms | 0.2 ms | 🥶 | 4096 MB |
| 11 ms |  | 3.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 95 ms | 20.6 ms | 1 ms | 0.6 ms | 🥶 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 103 ms | 24.5 ms | 0.4 ms | 0.4 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 89.9 ms | 20.7 ms | 0.4 ms | 0.1 ms | 🥶 | 4096 MB |
| 177.9 ms | 18.6 ms | 0.5 ms | 0.3 ms | 🥶 | 4096 MB |
| 107 ms | 18.9 ms | 0.6 ms | 0.3 ms | 🥶 | 4096 MB |
| 101.9 ms | 22.9 ms | 0.5 ms | 0.1 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.6 ms | 0.3 ms | 🥵 | 4096 MB |
| 9.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 4096 MB |
| 118.9 ms | 26.7 ms | 0.4 ms | 0.3 ms | 🥶 | 4096 MB |
| 91 ms | 22 ms | 0.3 ms | 0.2 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 59 ms |  | 40.2 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 5.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 89.9 ms | 24.7 ms | 0.6 ms | 0.2 ms | 🥶 | 4096 MB |
| 11.9 ms |  | 4.5 ms | 0.2 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 95 ms | 19 ms | 0.5 ms | 0.2 ms | 🥶 | 4096 MB |
| 5.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 88 ms |  | 81.4 ms | 0 ms | 🥵 | 4096 MB |
| 82 ms | 25.3 ms | 0.4 ms | 0.1 ms | 🥶 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 97.9 ms | 18.4 ms | 0.5 ms | 0.1 ms | 🥶 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0.3 ms | 🥵 | 4096 MB |
| 20.9 ms |  | 14 ms | 0.1 ms | 🥵 | 4096 MB |
| 9.9 ms |  | 3.2 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 105 ms | 20.7 ms | 0.8 ms | 0.4 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 23 ms |  | 18.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 105 ms | 19.4 ms | 0.6 ms | 0.4 ms | 🥶 | 4096 MB |
| 108 ms | 18.6 ms | 0.4 ms | 0.1 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.6 ms | 0.1 ms | 🥵 | 4096 MB |
| 16.9 ms |  | 10.9 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 5 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 20.9 ms |  | 13.9 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.5 ms | 0.4 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 15 ms |  | 8.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 92 ms |  | 84.5 ms | 0.3 ms | 🥵 | 4096 MB |
| 80.9 ms | 18.3 ms | 0.7 ms | 0.1 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 95 ms | 20.5 ms | 0.6 ms | 0.2 ms | 🥶 | 4096 MB |
| 82.9 ms | 17.1 ms | 0.3 ms | 0.1 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 133 ms | 18.4 ms | 0.4 ms | 0.2 ms | 🥶 | 4096 MB |
| 5 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 92 ms | 19.2 ms | 0.6 ms | 0.3 ms | 🥶 | 4096 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 105 ms | 22.3 ms | 0.6 ms | 0.3 ms | 🥶 | 4096 MB |
| 90 ms | 20 ms | 0.5 ms | 0.1 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 119.9 ms | 23.2 ms | 0.6 ms | 0.3 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 91 ms | 18 ms | 0.5 ms | 0.1 ms | 🥶 | 4096 MB |
| 92 ms | 25.9 ms | 0.5 ms | 0.6 ms | 🥶 | 4096 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 16.9 ms |  | 10.2 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 101 ms | 23.2 ms | 0.5 ms | 0.6 ms | 🥶 | 4096 MB |
| 9.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 26 ms |  | 17.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 118 ms | 19.1 ms | 0.4 ms | 0.2 ms | 🥶 | 4096 MB |
| 110.9 ms | 19.7 ms | 0.5 ms | 0.2 ms | 🥶 | 4096 MB |
| 6.9 ms |  |  |  | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 11.9 ms |  | 0.8 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.5 ms | 0.2 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 9 ms |  | 2.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 95.9 ms | 24.6 ms | 0.7 ms | 0.2 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 99.9 ms | 31.7 ms | 0.5 ms | 0.1 ms | 🥶 | 4096 MB |
| 98 ms | 29 ms | 0.5 ms | 0.4 ms | 🥶 | 4096 MB |
| 8 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 25 ms |  | 18 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 4.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 105 ms | 27.2 ms | 0.3 ms | 0.1 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 9.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 23 ms |  | 15.1 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 54.9 ms |  | 48.5 ms | 0.3 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 2.8 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 99.9 ms | 19.4 ms | 0.5 ms | 0.1 ms | 🥶 | 4096 MB |
| 13.9 ms |  | 9.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 105 ms | 28.2 ms | 0.5 ms | 0.2 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 50.9 ms |  | 0.5 ms | 39.5 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 103 ms | 18.3 ms | 0.6 ms | 0.3 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 101.9 ms | 24 ms | 0.7 ms | 0.4 ms | 🥶 | 4096 MB |
| 94 ms | 19.6 ms | 0.5 ms | 0.5 ms | 🥶 | 4096 MB |
| 105 ms | 26.8 ms | 0.7 ms | 0.6 ms | 🥶 | 4096 MB |
| 44 ms |  | 36.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 92.9 ms | 25.7 ms | 0.4 ms | 0.1 ms | 🥶 | 4096 MB |
| 8 ms |  | 0.5 ms | 0.4 ms | 🥵 | 4096 MB |
| 18.9 ms |  | 11.5 ms | 0.3 ms | 🥵 | 4096 MB |
| 94 ms | 27.4 ms | 0.5 ms | 0.1 ms | 🥶 | 4096 MB |
| 96.9 ms | 26.2 ms | 0.6 ms | 0.1 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 105.9 ms | 20.6 ms | 0.6 ms | 0.1 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 17.9 ms |  | 5.7 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 94 ms | 18.2 ms | 0.9 ms | 0.3 ms | 🥶 | 4096 MB |
| 115.9 ms | 19.9 ms | 0.6 ms | 0.4 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 92 ms | 22.4 ms | 0.6 ms | 0.2 ms | 🥶 | 4096 MB |
| 88 ms | 18.7 ms | 0.4 ms | 0.1 ms | 🥶 | 4096 MB |
| 113.9 ms | 22.3 ms | 0.5 ms | 0.2 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 4096 MB |
| 85.9 ms | 17.9 ms | 0.5 ms | 0.2 ms | 🥶 | 4096 MB |
| 92.9 ms | 18.1 ms | 0.4 ms | 0.2 ms | 🥶 | 4096 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 90.9 ms | 25.3 ms | 0.5 ms | 0.2 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 45 ms |  | 39.7 ms | 0.1 ms | 🥵 | 4096 MB |
| 100.9 ms | 30.2 ms | 0.4 ms | 0.4 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 279 ms | 27.9 ms | 0.4 ms | 0.1 ms | 🥶 | 4096 MB |
| 82 ms | 20.1 ms | 0.7 ms | 0.4 ms | 🥶 | 4096 MB |
| 36.9 ms |  | 30.9 ms | 0.2 ms | 🥵 | 4096 MB |
| 5.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 4.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 1.7 ms | 0.3 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 101 ms | 19.2 ms | 0.7 ms | 0.4 ms | 🥶 | 4096 MB |
| 112.9 ms | 25 ms | 0.8 ms | 0.2 ms | 🥶 | 4096 MB |
| 76.9 ms |  |  |  | 🥵 | 4096 MB |
| 98 ms | 18.7 ms | 0.5 ms | 0.1 ms | 🥶 | 4096 MB |
| 13 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 5 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 26.9 ms |  | 19.6 ms | 0.1 ms | 🥵 | 4096 MB |
| 38 ms |  | 32.5 ms | 0.3 ms | 🥵 | 4096 MB |
| 6 ms |  | 1.1 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 13.9 ms |  | 8.6 ms | 0.1 ms | 🥵 | 4096 MB |
| 107 ms | 25.8 ms | 0.6 ms | 0.1 ms | 🥶 | 4096 MB |
| 10.9 ms |  | 0.5 ms | 4.1 ms | 🥵 | 4096 MB |
| 82.9 ms | 21.9 ms | 0.6 ms | 0.4 ms | 🥶 | 4096 MB |
| 15 ms |  | 8.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 4.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 24.9 ms |  | 19.1 ms | 0.2 ms | 🥵 | 4096 MB |
| 89.9 ms | 26.2 ms | 0.6 ms | 0.3 ms | 🥶 | 4096 MB |
| 8 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0.3 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.7 ms | 0.1 ms | 🥵 | 4096 MB |
| 96.9 ms | 24.2 ms | 0.7 ms | 0.2 ms | 🥶 | 4096 MB |
| 16.9 ms |  | 9.9 ms | 0.2 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 23.9 ms |  | 17.1 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 101.9 ms | 18.8 ms | 0.5 ms | 0.3 ms | 🥶 | 4096 MB |
| 7 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 115.9 ms | 18.7 ms | 0.5 ms | 0.3 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 98.9 ms | 22 ms | 0.5 ms | 0.1 ms | 🥶 | 4096 MB |
| 5 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 98.9 ms | 25.9 ms | 0.6 ms | 0.2 ms | 🥶 | 4096 MB |
| 7.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 4096 MB |
| 21 ms |  | 14.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 59.9 ms |  | 33.6 ms | 19.9 ms | 🥵 | 4096 MB |
| 107 ms | 20 ms | 0.8 ms | 0.1 ms | 🥶 | 4096 MB |
| 99.9 ms | 25.3 ms | 0.5 ms | 0.5 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.3 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.5 ms | 0.2 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 4.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 88 ms | 26.4 ms | 0.5 ms | 0.2 ms | 🥶 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 1.2 ms | 0.1 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.5 ms | 0.4 ms | 🥵 | 4096 MB |
| 92 ms | 22.4 ms | 0.4 ms | 0.2 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 21 ms |  | 15.2 ms | 0.2 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 1.5 ms | 0.3 ms | 🥵 | 4096 MB |
| 10.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 105.9 ms | 20 ms | 0.5 ms | 0.1 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 4.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.8 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.6 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 4.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 84 ms | 20.6 ms | 0.4 ms | 0.2 ms | 🥶 | 4096 MB |
| 8 ms |  | 0.5 ms | 0 ms | 🥵 | 4096 MB |
| 19.9 ms |  | 12.6 ms | 0.3 ms | 🥵 | 4096 MB |
| 23 ms |  | 17 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 4096 MB |
| 5.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 102.9 ms | 27.1 ms | 0.5 ms | 0.5 ms | 🥶 | 4096 MB |
| 97.9 ms | 27.6 ms | 0.5 ms | 0.4 ms | 🥶 | 4096 MB |
| 8 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 18.9 ms |  | 12.8 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 8.9 ms |  | 0.6 ms | 0.2 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 5.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 23 ms |  | 16.2 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 98 ms | 19.3 ms | 0.5 ms | 0.2 ms | 🥶 | 4096 MB |
| 91 ms | 20.2 ms | 0.5 ms | 0.3 ms | 🥶 | 4096 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 105 ms | 28 ms | 0.5 ms | 0.3 ms | 🥶 | 4096 MB |
| 88.9 ms | 22 ms | 0.5 ms | 0.1 ms | 🥶 | 4096 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 97 ms | 21.2 ms | 0.5 ms | 0.2 ms | 🥶 | 4096 MB |
| 21.9 ms |  | 15.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 99.9 ms | 27.1 ms | 0.7 ms | 0.2 ms | 🥶 | 4096 MB |
| 95 ms | 23 ms | 0.5 ms | 0.3 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 29.9 ms |  | 23.1 ms | 0.1 ms | 🥵 | 4096 MB |
| 5.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 310 ms | 18.5 ms | 0.5 ms | 0.3 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 32.9 ms |  | 25.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 101.9 ms | 20.5 ms | 0.5 ms | 0.1 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 54 ms |  | 40.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 16.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.5 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 5 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 96.9 ms | 18.1 ms | 0.5 ms | 0.2 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 85.9 ms | 19.5 ms | 0.6 ms | 0.3 ms | 🥶 | 4096 MB |
| 111 ms | 23 ms | 0.4 ms | 0.2 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 5.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 20 ms |  | 12 ms | 0.2 ms | 🥵 | 4096 MB |
| 127.9 ms | 21.7 ms | 0.6 ms | 0.1 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 13.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 17.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 4096 MB |
| 98.9 ms | 27.6 ms | 0.3 ms | 0.2 ms | 🥶 | 4096 MB |
| 91 ms | 18.5 ms | 0.5 ms | 0.2 ms | 🥶 | 4096 MB |
| 119 ms | 27.9 ms | 0.4 ms | 0.2 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.7 ms | 0.2 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 38 ms |  | 9.9 ms | 19.8 ms | 🥵 | 4096 MB |
| 13 ms |  | 6.1 ms | 0.1 ms | 🥵 | 4096 MB |
| 5 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 88.9 ms | 23.6 ms | 0.3 ms | 0 ms | 🥶 | 4096 MB |
| 97 ms | 31.8 ms | 0.4 ms | 0.2 ms | 🥶 | 4096 MB |
| 8 ms |  | 0.6 ms | 0.3 ms | 🥵 | 4096 MB |
| 13.9 ms |  | 8.2 ms | 0.2 ms | 🥵 | 4096 MB |
| 64 ms |  | 17.3 ms | 39.8 ms | 🥵 | 4096 MB |
| 41 ms |  | 33.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 154 ms | 25.4 ms | 0.4 ms | 0.5 ms | 🥶 | 4096 MB |
| 27.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 9.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 96.9 ms | 17.9 ms | 0.5 ms | 0.3 ms | 🥶 | 4096 MB |
| 80 ms |  | 73.7 ms | 0.1 ms | 🥵 | 4096 MB |
| 100 ms | 18.5 ms | 0.5 ms | 0.2 ms | 🥶 | 4096 MB |
| 87.9 ms | 19 ms | 0.6 ms | 0.5 ms | 🥶 | 4096 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 106 ms | 23.6 ms | 0.5 ms | 0.3 ms | 🥶 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 11.9 ms |  | 4.9 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 5 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 88.9 ms | 19.4 ms | 0.4 ms | 0.1 ms | 🥶 | 4096 MB |
| 13.9 ms |  | 8.6 ms | 0.3 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 39 ms |  | 32.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 103 ms | 29.9 ms | 0.5 ms | 0.1 ms | 🥶 | 4096 MB |
| 111 ms | 24.3 ms | 0.7 ms | 0.3 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 18 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 5.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 94.9 ms | 31.5 ms | 0.7 ms | 0.2 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 12 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.6 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 101 ms | 25.2 ms | 0.6 ms | 1.5 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.5 ms | 0 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 92 ms | 22.9 ms | 0.4 ms | 0.2 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 118.9 ms | 20 ms | 0.5 ms | 0.4 ms | 🥶 | 4096 MB |
| 95 ms | 17.3 ms | 0.4 ms | 0.3 ms | 🥶 | 4096 MB |
| 78.9 ms | 24.9 ms | 0.5 ms | 0.3 ms | 🥶 | 4096 MB |
| 96.9 ms | 20.8 ms | 0.7 ms | 0.3 ms | 🥶 | 4096 MB |
| 9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 98.9 ms | 18.2 ms | 0.6 ms | 0.1 ms | 🥶 | 4096 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 98 ms | 18.9 ms | 0.6 ms | 0.4 ms | 🥶 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 21.9 ms |  | 8.2 ms | 0.1 ms | 🥵 | 4096 MB |
| 125.9 ms | 17.7 ms | 0.5 ms | 0.1 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.3 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 26.9 ms |  | 20.2 ms | 0.1 ms | 🥵 | 4096 MB |
| 128 ms | 25.6 ms | 0.7 ms | 0.3 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 23.9 ms |  | 18.6 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 151.9 ms |  | 80 ms | 59.9 ms | 🥵 | 4096 MB |
| 12 ms |  | 4.9 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 100.9 ms | 19.8 ms | 0.6 ms | 0 ms | 🥶 | 4096 MB |
| 20.9 ms |  | 13.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 97 ms | 32 ms | 0.4 ms | 0.7 ms | 🥶 | 4096 MB |
| 7 ms |  | 0.5 ms | 0.2 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.7 ms | 0.1 ms | 🥵 | 4096 MB |
| 85 ms |  | 79.8 ms | 0.7 ms | 🥵 | 4096 MB |
| 18.9 ms |  | 13.8 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 12 ms |  | 5.1 ms | 0.1 ms | 🥵 | 4096 MB |
| 5 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 108 ms | 24.5 ms | 0.5 ms | 0.1 ms | 🥶 | 4096 MB |
| 108.9 ms | 19.6 ms | 0.5 ms | 0.4 ms | 🥶 | 4096 MB |
| 85 ms |  | 77.7 ms | 0.2 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 16 ms |  | 10.2 ms | 0 ms | 🥵 | 4096 MB |
| 111 ms | 25 ms | 0.7 ms | 0.3 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 53.9 ms |  | 39.9 ms | 0.3 ms | 🥵 | 4096 MB |
| 125.9 ms | 26 ms | 0.7 ms | 0.1 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 12 ms |  | 5.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 98.9 ms | 25.7 ms | 0.3 ms | 0.3 ms | 🥶 | 4096 MB |
| 95 ms | 25 ms | 0.4 ms | 0.1 ms | 🥶 | 4096 MB |
| 23 ms |  | 18.6 ms | 0.1 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 92 ms | 23.8 ms | 0.4 ms | 0.3 ms | 🥶 | 4096 MB |
| 116.9 ms | 18.7 ms | 0.5 ms | 0 ms | 🥶 | 4096 MB |
| 16.9 ms |  | 10.4 ms | 0.5 ms | 🥵 | 4096 MB |
| 108 ms | 32.5 ms | 0.5 ms | 0.5 ms | 🥶 | 4096 MB |
| 96 ms | 29.8 ms | 0.5 ms | 0.4 ms | 🥶 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 92.9 ms | 20.4 ms | 0.6 ms | 0.2 ms | 🥶 | 4096 MB |
| 9 ms |  | 0.6 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 97 ms | 27.4 ms | 0.4 ms | 0.3 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 105.9 ms | 30.4 ms | 0.7 ms | 0.2 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 13 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 24.9 ms |  | 18 ms | 0.2 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.3 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 118 ms | 28.7 ms | 0.4 ms | 0.2 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 23 ms |  | 15.8 ms | 1.4 ms | 🥵 | 4096 MB |
| 94 ms | 22.9 ms | 0.7 ms | 0.3 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 105.9 ms | 22.1 ms | 0.7 ms | 0.5 ms | 🥶 | 4096 MB |
| 110 ms | 18.6 ms | 0.9 ms | 0.4 ms | 🥶 | 4096 MB |
| 75 ms | 22 ms | 0.4 ms | 0 ms | 🥶 | 4096 MB |
| 89.9 ms | 20.9 ms | 0.4 ms | 0 ms | 🥶 | 4096 MB |
| 112.9 ms | 19.2 ms | 0.5 ms | 0.2 ms | 🥶 | 4096 MB |
| 108 ms | 20.7 ms | 0.6 ms | 0.1 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.6 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 20 ms |  | 12.5 ms | 0 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 97 ms | 22.2 ms | 0.4 ms | 0.2 ms | 🥶 | 4096 MB |
| 11.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 23 ms |  | 16.6 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.6 ms | 0.3 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 115 ms | 27.1 ms | 0.4 ms | 0.1 ms | 🥶 | 4096 MB |
| 92.9 ms | 18.8 ms | 0.6 ms | 0.2 ms | 🥶 | 4096 MB |
| 19.9 ms |  | 13.8 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 5 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 9 ms |  | 0.3 ms | 0.3 ms | 🥵 | 4096 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 5 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 26 ms |  | 19.9 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 146.9 ms | 28.7 ms | 0.4 ms | 0.2 ms | 🥶 | 4096 MB |
| 8 ms |  | 0.5 ms | 0.3 ms | 🥵 | 4096 MB |
| 90 ms | 25.8 ms | 0.6 ms | 0.1 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 42 ms |  | 15.8 ms | 19.7 ms | 🥵 | 4096 MB |
| 4.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 93.9 ms | 19.9 ms | 0.6 ms | 0 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 12 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 128 ms | 20.1 ms | 0.5 ms | 0.2 ms | 🥶 | 4096 MB |
| 101 ms |  |  |  | 🥵 | 4096 MB |
| 97 ms | 21.3 ms | 0.7 ms | 0.1 ms | 🥶 | 4096 MB |
| 95.9 ms | 22.2 ms | 0.8 ms | 0.2 ms | 🥶 | 4096 MB |
| 89.9 ms | 25.1 ms | 0.3 ms | 0.1 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 101.9 ms | 25 ms | 0.5 ms | 0.1 ms | 🥶 | 4096 MB |
| 138 ms | 22.7 ms | 0.5 ms | 0.1 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 105.9 ms | 20.7 ms | 0.4 ms | 0.3 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 5.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.3 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 90.9 ms | 25 ms | 0.6 ms | 0.3 ms | 🥶 | 4096 MB |
| 119 ms | 20.2 ms | 0.5 ms | 0.2 ms | 🥶 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 95.9 ms | 19.7 ms | 0.5 ms | 0.2 ms | 🥶 | 4096 MB |
| 125 ms | 26.2 ms | 0.6 ms | 0.4 ms | 🥶 | 4096 MB |
| 94 ms | 18.6 ms | 0.6 ms | 0 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 101.9 ms | 21.5 ms | 0.8 ms | 0.3 ms | 🥶 | 4096 MB |
| 102.9 ms | 18.9 ms | 0.5 ms | 0.3 ms | 🥶 | 4096 MB |
| 13.9 ms |  | 0.8 ms | 0.5 ms | 🥵 | 4096 MB |
| 98 ms | 17.7 ms | 0.6 ms | 0.3 ms | 🥶 | 4096 MB |
| 91 ms | 21.6 ms | 0.7 ms | 0.2 ms | 🥶 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.3 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.6 ms | 0 ms | 🥵 | 4096 MB |
| 82 ms | 17.9 ms | 0.3 ms | 0.1 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.5 ms | 0.2 ms | 🥵 | 4096 MB |
| 5.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 11 ms |  | 5.5 ms | 0.2 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.5 ms | 0 ms | 🥵 | 4096 MB |
| 8.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 103.9 ms | 23.8 ms | 0.7 ms | 0.3 ms | 🥶 | 4096 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 88 ms | 18.9 ms | 0.4 ms | 0.2 ms | 🥶 | 4096 MB |
| 23.9 ms |  | 18 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 88.9 ms | 25 ms | 0.6 ms | 0.4 ms | 🥶 | 4096 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 15 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.6 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 101 ms | 27.5 ms | 0.6 ms | 0.3 ms | 🥶 | 4096 MB |
| 93.9 ms | 28 ms | 0.4 ms | 0.3 ms | 🥶 | 4096 MB |
| 8 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 90 ms | 18.7 ms | 0.5 ms | 0.4 ms | 🥶 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 96.9 ms | 22.1 ms | 0.5 ms | 0.2 ms | 🥶 | 4096 MB |
| 42 ms |  | 35 ms | 0 ms | 🥵 | 4096 MB |
| 21.9 ms |  | 14.2 ms | 0.4 ms | 🥵 | 4096 MB |
| 99.9 ms | 23.5 ms | 0.6 ms | 0.4 ms | 🥶 | 4096 MB |
| 5.9 ms |  | 0.2 ms | 0.4 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 125.9 ms | 19.8 ms | 0.8 ms | 0.4 ms | 🥶 | 4096 MB |
| 97 ms | 30.8 ms | 0.8 ms | 0.5 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 100 ms | 27.2 ms | 0.6 ms | 0.2 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 95 ms | 20.4 ms | 0.8 ms | 0.3 ms | 🥶 | 4096 MB |
| 135.9 ms | 20 ms | 0.6 ms | 0.1 ms | 🥶 | 4096 MB |
| 75 ms | 20.5 ms | 0.5 ms | 0.2 ms | 🥶 | 4096 MB |
| 98 ms | 25.8 ms | 0.8 ms | 0.3 ms | 🥶 | 4096 MB |
| 7.9 ms |  | 3.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 38.9 ms |  | 11.9 ms | 20 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 121 ms | 33.5 ms | 15.7 ms | 0.5 ms | 🥶 | 4096 MB |
| 119.9 ms | 35 ms | 0.4 ms | 0.7 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.3 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 21.9 ms |  | 15.7 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 93 ms | 26.2 ms | 1 ms | 0.4 ms | 🥶 | 4096 MB |
| 86.9 ms |  | 81.1 ms | 0.3 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 39.9 ms |  | 13.3 ms | 19.5 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 100.9 ms | 23 ms | 0.5 ms | 0.2 ms | 🥶 | 4096 MB |
| 16 ms |  | 0.8 ms | 0.2 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 1.8 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 16 ms |  | 0.5 ms | 0.2 ms | 🥵 | 4096 MB |
| 87 ms | 18.2 ms | 0.8 ms | 0.4 ms | 🥶 | 4096 MB |
| 88.9 ms | 18.3 ms | 0.6 ms | 0.4 ms | 🥶 | 4096 MB |
| 8 ms |  | 0.5 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 109 ms |  | 80 ms | 19.9 ms | 🥵 | 4096 MB |
| 5 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 16.9 ms |  | 9.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.7 ms | 0 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 94 ms | 28.4 ms | 0.9 ms | 0.2 ms | 🥶 | 4096 MB |
| 25 ms |  | 19.1 ms | 0.7 ms | 🥵 | 4096 MB |
| 88 ms | 28.7 ms | 0.5 ms | 0.3 ms | 🥶 | 4096 MB |
| 8.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 42 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 103.9 ms | 19.6 ms | 0.9 ms | 0.6 ms | 🥶 | 4096 MB |
| 18 ms |  | 11 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 103.9 ms | 33.1 ms | 0.7 ms | 0.2 ms | 🥶 | 4096 MB |
| 85 ms | 22.6 ms | 0.4 ms | 0.1 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 23.9 ms |  | 17.1 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 88 ms | 19.6 ms | 0.6 ms | 0.2 ms | 🥶 | 4096 MB |
| 7 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 95 ms | 18.6 ms | 0.5 ms | 0.1 ms | 🥶 | 4096 MB |
| 99.9 ms | 19.8 ms | 0.5 ms | 0.2 ms | 🥶 | 4096 MB |
| 19 ms |  | 0.6 ms | 0.2 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.6 ms | 0.3 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 8.9 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 91 ms | 19.1 ms | 0.5 ms | 0.3 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 109 ms | 18.3 ms | 0.6 ms | 0.4 ms | 🥶 | 4096 MB |
| 98.9 ms | 19.4 ms | 0.4 ms | 0 ms | 🥶 | 4096 MB |
| 29 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 5 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 99.9 ms | 26.2 ms | 0.3 ms | 0.3 ms | 🥶 | 4096 MB |
| 10.9 ms |  | 4.9 ms | 0.2 ms | 🥵 | 4096 MB |
| 88 ms | 19.8 ms | 0.6 ms | 0.5 ms | 🥶 | 4096 MB |
| 204.9 ms | 30.2 ms | 0.5 ms | 0.1 ms | 🥶 | 4096 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 15 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 87.9 ms | 23.6 ms | 0.5 ms | 0.4 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.3 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.6 ms | 0.1 ms | 🥵 | 4096 MB |
| 98.9 ms | 18.4 ms | 0.5 ms | 0.3 ms | 🥶 | 4096 MB |
| 227.9 ms | 17.7 ms | 0.4 ms | 0.4 ms | 🥶 | 4096 MB |
| 14 ms |  | 6.2 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 79.9 ms | 23.4 ms | 0.4 ms | 0.4 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.3 ms | 🥵 | 4096 MB |
| 5 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 96.9 ms | 21.1 ms | 0.5 ms | 0.3 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 19 ms |  | 12.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 84 ms | 21 ms | 0.6 ms | 0.3 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 114 ms | 17.8 ms | 0.4 ms | 0.1 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.3 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.5 ms | 0 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 94 ms | 23.3 ms | 0.6 ms | 0.3 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 9 ms |  | 3 ms | 0.1 ms | 🥵 | 4096 MB |
| 87.9 ms | 22.3 ms | 0.5 ms | 0.2 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 97 ms | 20.1 ms | 0.7 ms | 0.3 ms | 🥶 | 4096 MB |
| 4.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 118.9 ms | 41.8 ms | 0.4 ms | 0.4 ms | 🥶 | 4096 MB |
| 101 ms | 17.4 ms | 0.5 ms | 0.2 ms | 🥶 | 4096 MB |
| 11.9 ms |  | 6.6 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.7 ms | 0.2 ms | 🥵 | 4096 MB |
| 155.9 ms | 20.4 ms | 0.6 ms | 0.2 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 112.9 ms | 17.8 ms | 0.6 ms | 0.1 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.5 ms | 🥵 | 4096 MB |
| 23 ms |  | 18.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 13.9 ms |  | 7.1 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 14 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 114 ms | 19 ms | 0.7 ms | 0.1 ms | 🥶 | 4096 MB |
| 78.9 ms | 17.9 ms | 0.5 ms | 0.1 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 5 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.6 ms | 0.1 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 117 ms |  | 91.5 ms | 19.7 ms | 🥵 | 4096 MB |
| 4.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 99.9 ms | 29.8 ms | 0.4 ms | 0.2 ms | 🥶 | 4096 MB |
| 97 ms | 26.4 ms | 0.4 ms | 0.1 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 67 ms |  | 20.2 ms | 39.6 ms | 🥵 | 4096 MB |
| 99.9 ms | 28.5 ms | 0.4 ms | 0.2 ms | 🥶 | 4096 MB |
| 11.9 ms |  | 4.2 ms | 0.2 ms | 🥵 | 4096 MB |
| 23 ms |  | 0.5 ms | 17.3 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 128 ms | 22.3 ms | 0.6 ms | 0.2 ms | 🥶 | 4096 MB |
| 22 ms |  | 15.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 5.9 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 9 ms |  | 3.8 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 21.9 ms |  | 10.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 4.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 26.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 148 ms | 17.6 ms | 0.3 ms | 0.3 ms | 🥶 | 4096 MB |
| 23.9 ms |  | 18.1 ms | 0.4 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 101.9 ms | 22.4 ms | 0.6 ms | 0.2 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.6 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.3 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 1.5 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 89.9 ms | 19.4 ms | 0.4 ms | 0.4 ms | 🥶 | 4096 MB |
| 115 ms | 20.6 ms | 0.9 ms | 14.6 ms | 🥶 | 4096 MB |
| 104 ms | 21.5 ms | 0.6 ms | 0.2 ms | 🥶 | 4096 MB |
| 104 ms | 23.9 ms | 0.5 ms | 0.2 ms | 🥶 | 4096 MB |
| 9.9 ms |  | 2.9 ms | 0.8 ms | 🥵 | 4096 MB |
| 36.9 ms |  | 28.5 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 24.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 9 ms |  | 3.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 120 ms | 20.6 ms | 0.5 ms | 0.3 ms | 🥶 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 4096 MB |
| 96.9 ms | 26.1 ms | 0.5 ms | 0.3 ms | 🥶 | 4096 MB |
| 99.9 ms | 27.3 ms | 0.4 ms | 0.1 ms | 🥶 | 4096 MB |
| 36.9 ms |  | 29.6 ms | 0.2 ms | 🥵 | 4096 MB |
| 101.9 ms | 18.8 ms | 0.5 ms | 0.2 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.7 ms | 0.2 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 113 ms | 31.6 ms | 0.6 ms | 0.5 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 105 ms | 28.8 ms | 0.4 ms | 0.3 ms | 🥶 | 4096 MB |
| 30.9 ms |  | 24.4 ms | 0.3 ms | 🥵 | 4096 MB |
| 98.9 ms | 19.9 ms | 0.5 ms | 0.4 ms | 🥶 | 4096 MB |
| 4.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.5 ms | 0.3 ms | 🥵 | 4096 MB |
| 17.9 ms |  | 9.1 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 96.9 ms | 20.2 ms | 0.6 ms | 0.5 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 87 ms | 20.7 ms | 0.5 ms | 0.2 ms | 🥶 | 4096 MB |
| 18 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 98 ms | 18.3 ms | 0.6 ms | 0.1 ms | 🥶 | 4096 MB |
| 36.9 ms |  | 10.8 ms | 19.9 ms | 🥵 | 4096 MB |
| 102.9 ms | 19.2 ms | 0.6 ms | 0.3 ms | 🥶 | 4096 MB |
| 8 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.5 ms | 0.2 ms | 🥵 | 4096 MB |
| 97 ms | 19.1 ms | 0.4 ms | 0.2 ms | 🥶 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 92.9 ms | 26.2 ms | 0.6 ms | 3.1 ms | 🥶 | 4096 MB |
| 108.9 ms | 27.8 ms | 0.5 ms | 0.4 ms | 🥶 | 4096 MB |
| 80.9 ms | 18.7 ms | 0.6 ms | 0.3 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 115.9 ms | 20 ms | 0.6 ms | 0.5 ms | 🥶 | 4096 MB |
| 7 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 13 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 25 ms |  | 0.7 ms | 8.7 ms | 🥵 | 4096 MB |
| 87 ms | 18.4 ms | 0.5 ms | 0.3 ms | 🥶 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 98 ms | 18.3 ms | 0.7 ms | 0.2 ms | 🥶 | 4096 MB |
| 7.9 ms |  | 0.6 ms | 0.2 ms | 🥵 | 4096 MB |
| 68 ms |  | 60.7 ms | 0.2 ms | 🥵 | 4096 MB |
| 26 ms |  | 18.5 ms | 0.2 ms | 🥵 | 4096 MB |
| 90.9 ms | 22.9 ms | 0.4 ms | 0.3 ms | 🥶 | 4096 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 4096 MB |
| 21.9 ms |  | 15.7 ms | 0.2 ms | 🥵 | 4096 MB |
| 123.9 ms | 18.6 ms | 0.5 ms | 0.4 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 9 ms |  | 2.2 ms | 0.7 ms | 🥵 | 4096 MB |
| 92.9 ms | 18.5 ms | 0.5 ms | 0.3 ms | 🥶 | 4096 MB |
| 92 ms | 18.1 ms | 0.6 ms | 0.2 ms | 🥶 | 4096 MB |
| 9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 60.9 ms |  | 34.5 ms | 19.7 ms | 🥵 | 4096 MB |
| 4.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 92 ms | 17.8 ms | 0.6 ms | 0.3 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.6 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 98.9 ms | 28.1 ms | 0.4 ms | 0.3 ms | 🥶 | 4096 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 9.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.6 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.3 ms | 🥵 | 4096 MB |
| 129.9 ms | 25.2 ms | 0.9 ms | 0.2 ms | 🥶 | 4096 MB |
| 24 ms |  | 19.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 22 ms |  | 14.9 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 98.9 ms | 25.2 ms | 0.7 ms | 0.4 ms | 🥶 | 4096 MB |
| 8.9 ms |  | 0.4 ms | 0.3 ms | 🥵 | 4096 MB |
| 15 ms |  | 8.8 ms | 0.1 ms | 🥵 | 4096 MB |
| 88 ms | 25.2 ms | 0.4 ms | 0.1 ms | 🥶 | 4096 MB |
| 92.9 ms | 19.9 ms | 0.7 ms | 0.4 ms | 🥶 | 4096 MB |
| 108 ms | 17.1 ms | 0.4 ms | 0.4 ms | 🥶 | 4096 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 4.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 4096 MB |
| 26.9 ms |  | 21.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 79.9 ms | 22.3 ms | 0.4 ms | 0.4 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 5 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 96.9 ms | 28.7 ms | 0.5 ms | 0.2 ms | 🥶 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 92.9 ms | 17.2 ms | 0.6 ms | 0.4 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 9.9 ms |  | 4 ms | 0.1 ms | 🥵 | 4096 MB |
| 95 ms | 18.9 ms | 0.5 ms | 0.4 ms | 🥶 | 4096 MB |
| 8.9 ms |  | 0.4 ms | 0.4 ms | 🥵 | 4096 MB |
| 93.9 ms | 17.9 ms | 0.6 ms | 0.3 ms | 🥶 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 92.9 ms | 22.3 ms | 0.4 ms | 0.1 ms | 🥶 | 4096 MB |
| 101 ms | 26.8 ms | 0.6 ms | 0.3 ms | 🥶 | 4096 MB |
| 95 ms | 27.3 ms | 0.6 ms | 0.3 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 85 ms | 24.5 ms | 0.4 ms | 0.1 ms | 🥶 | 4096 MB |
| 8 ms |  | 0.6 ms | 0.2 ms | 🥵 | 4096 MB |
| 59 ms |  | 40 ms | 0.2 ms | 🥵 | 4096 MB |
| 87.9 ms | 21.4 ms | 0.6 ms | 0.5 ms | 🥶 | 4096 MB |
| 97.9 ms | 20.1 ms | 0.3 ms | 0.2 ms | 🥶 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 102.9 ms | 24.3 ms | 0.6 ms | 0.2 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.3 ms | 🥵 | 4096 MB |
| 101.9 ms | 20.3 ms | 0.6 ms | 0.4 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 95.9 ms | 25.2 ms | 0.5 ms | 0.4 ms | 🥶 | 4096 MB |
| 4.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 27 ms |  | 0.6 ms | 18.8 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 105 ms | 26.8 ms | 0.6 ms | 0.2 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 5 ms |  | 0.2 ms | 0.2 ms | 🥵 | 4096 MB |
| 108 ms | 28.9 ms | 0.8 ms | 0.1 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 52.9 ms |  | 46.6 ms | 0.6 ms | 🥵 | 4096 MB |
| 106.9 ms | 27.6 ms | 0.5 ms | 0.3 ms | 🥶 | 4096 MB |
| 21 ms |  | 13.2 ms | 0.1 ms | 🥵 | 4096 MB |
| 10 ms |  | 3.7 ms | 0.1 ms | 🥵 | 4096 MB |
| 32.9 ms |  | 8 ms | 19.9 ms | 🥵 | 4096 MB |
| 95.9 ms | 30.9 ms | 0.4 ms | 0.3 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 108 ms | 21 ms | 0.3 ms | 0.1 ms | 🥶 | 4096 MB |
| 5 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 92.9 ms | 18.2 ms | 0.5 ms | 0.4 ms | 🥶 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 117 ms | 25 ms | 0.4 ms | 7.1 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 13 ms |  | 5.8 ms | 0.5 ms | 🥵 | 4096 MB |
| 4.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 90 ms | 23.5 ms | 0.5 ms | 0.4 ms | 🥶 | 4096 MB |
| 114 ms | 28.5 ms | 0.6 ms | 0.1 ms | 🥶 | 4096 MB |
| 109.9 ms | 26.4 ms | 0.6 ms | 0.2 ms | 🥶 | 4096 MB |
| 109.9 ms | 18.4 ms | 0.4 ms | 0.1 ms | 🥶 | 4096 MB |
| 89.9 ms | 18.1 ms | 0.4 ms | 0.2 ms | 🥶 | 4096 MB |
| 148 ms | 28.8 ms | 0.5 ms | 0.5 ms | 🥶 | 4096 MB |

## XRay Example of a Cold Start

<img width="1476" alt="Screenshot 2020-10-07 at 23 01 40" src="https://user-images.githubusercontent.com/1189998/95387505-178a1d00-08f1-11eb-83a7-7bc32eee48e2.png">

## XRay Example of a Warm Start

<img width="1479" alt="Screenshot 2020-10-07 at 23 01 23" src="https://user-images.githubusercontent.com/1189998/95387509-1953e080-08f1-11eb-8d46-ac25efa235e4.png">
