
# Benchmark: Response Times

The following are the response time results from AWS XRay, generated after running `npm run benchmark`.

![Average Cold/Warm Response Times](./benchmark/response-times-average.svg)

- 🔵: Average cold startup times
- 🔴: Average warm startup times

![Fastest and Slowest Response Times](./benchmark/response-times-extremes.svg)

- 🔵: Fastest warm response time
- 🔴: Slowest warm response time
- 🟡: Fastest cold response time
- 🟠: Slowest cold response time

## Results for 128 MB

| Measurement (128 MB) | Time (ms) |
|-------------|------|
| Average warm start response time | 8.1 ms |
| Average cold start response time | 96.8 ms |
| Fastest warm response time | 5 ms |
| Slowest warm response time | 88.9 ms |
| Fastest cold response time  | 6.9 ms |
| Slowest cold response time | 121.9 ms |
  

| Response time | Initialization | Invocation | Overhead | Cold/ Warm Start | Memory Size |
|---------------|----------------|------------|----------|------------------|-------------|
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 128 MB |
| 8 ms |  | 0.6 ms | 0.2 ms | 🥵 | 128 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 7.9 ms |  | 0.4 ms | 0 ms | 🥵 | 128 MB |
| 29.9 ms |  | 24.7 ms | 0.2 ms | 🥵 | 128 MB |
| 121.9 ms | 28.6 ms | 0.4 ms | 0.1 ms | 🥶 | 128 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 7.9 ms |  | 0.5 ms | 0 ms | 🥵 | 128 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 128 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 128 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 128 MB |
| 61 ms |  | 55.4 ms | 0.2 ms | 🥵 | 128 MB |
| 6.9 ms |  | 1.3 ms | 0.3 ms | 🥵 | 128 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 6.9 ms | 25.4 ms | 0.3 ms | 0.1 ms | 🥶 | 128 MB |
| 107 ms | 20.1 ms | 0.7 ms | 3.4 ms | 🥶 | 128 MB |
| 24.9 ms |  | 17.8 ms | 0.1 ms | 🥵 | 128 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 128 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 5 ms |  | 0.4 ms | 0.2 ms | 🥵 | 128 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 26 ms |  | 0.7 ms | 19.5 ms | 🥵 | 128 MB |
| 8.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 7.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 128 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 128 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 108 ms | 28.3 ms | 0.7 ms | 0.3 ms | 🥶 | 128 MB |
| 7.9 ms |  | 0.3 ms | 0 ms | 🥵 | 128 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 128 MB |
| 42 ms |  | 15.2 ms | 19.8 ms | 🥵 | 128 MB |
| 7 ms |  | 0.5 ms | 0.1 ms | 🥵 | 128 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 88.9 ms |  | 61.6 ms | 19.8 ms | 🥵 | 128 MB |
| 17.9 ms |  | 0.4 ms | 0.3 ms | 🥵 | 128 MB |
| 8 ms |  | 0.3 ms | 0.2 ms | 🥵 | 128 MB |
| 7.9 ms |  | 0.3 ms | 0 ms | 🥵 | 128 MB |
| 6 ms |  | 0.2 ms | 0.1 ms | 🥵 | 128 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 128 MB |
| 72.9 ms |  | 40.1 ms | 19.7 ms | 🥵 | 128 MB |
| 8.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 128 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |## Results for 256 MB

| Measurement (256 MB) | Time (ms) |
|-------------|------|
| Average warm start response time | 7 ms |
| Average cold start response time | 121.2 ms |
| Fastest warm response time | 4.9 ms |
| Slowest warm response time | 88.9 ms |
| Fastest cold response time  | 6.9 ms |
| Slowest cold response time | 195 ms |
  

| Response time | Initialization | Invocation | Overhead | Cold/ Warm Start | Memory Size |
|---------------|----------------|------------|----------|------------------|-------------|
| 38.9 ms |  | 30 ms | 0.2 ms | 🥵 | 256 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 7.9 ms |  | 0.4 ms | 0 ms | 🥵 | 256 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 256 MB |
| 7.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 256 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 11.9 ms |  | 2.2 ms | 0.2 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 195 ms | 20.3 ms | 0.7 ms | 0.2 ms | 🥶 | 256 MB |
| 7.9 ms |  | 0.5 ms | 0 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 101.9 ms | 24.6 ms | 0.8 ms | 0.1 ms | 🥶 | 256 MB |
| 5 ms |  | 0.3 ms | 0.2 ms | 🥵 | 256 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 256 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 5 ms |  | 0.4 ms | 0.2 ms | 🥵 | 256 MB |
| 26 ms |  | 0.7 ms | 19.5 ms | 🥵 | 256 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 34 ms |  | 25.7 ms | 0.1 ms | 🥵 | 256 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 256 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 8 ms |  | 0.4 ms | 0.3 ms | 🥵 | 256 MB |
| 8.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 12 ms |  | 6.6 ms | 0 ms | 🥵 | 256 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 108 ms | 28.3 ms | 0.7 ms | 0.3 ms | 🥶 | 256 MB |
| 7.9 ms |  | 0.3 ms | 0 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 256 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 7.9 ms |  | 0.4 ms | 0 ms | 🥵 | 256 MB |
| 11 ms |  | 0.4 ms | 0.2 ms | 🥵 | 256 MB |
| 117 ms | 32.9 ms | 0.6 ms | 0.4 ms | 🥶 | 256 MB |
| 9.9 ms |  | 0.7 ms | 0.2 ms | 🥵 | 256 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 6 ms |  | 0.2 ms | 0.1 ms | 🥵 | 256 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 17.9 ms |  | 0.4 ms | 0.3 ms | 🥵 | 256 MB |
| 72.9 ms |  | 40.1 ms | 19.7 ms | 🥵 | 256 MB |
| 7.9 ms |  | 0.3 ms | 0 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 8.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 256 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 8 ms |  | 0.6 ms | 0.2 ms | 🥵 | 256 MB |
| 7.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 256 MB |
| 29.9 ms |  | 24.7 ms | 0.2 ms | 🥵 | 256 MB |
| 121.9 ms | 28.6 ms | 0.4 ms | 0.1 ms | 🥶 | 256 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 5.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 256 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 61 ms |  | 55.4 ms | 0.2 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 256 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 256 MB |
| 6.9 ms |  | 1.3 ms | 0.3 ms | 🥵 | 256 MB |
| 6.9 ms | 25.4 ms | 0.3 ms | 0.1 ms | 🥶 | 256 MB |
| 107 ms | 20.1 ms | 0.7 ms | 3.4 ms | 🥶 | 256 MB |
| 24.9 ms |  | 17.8 ms | 0.1 ms | 🥵 | 256 MB |
| 4.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 7.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 256 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 256 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 134.9 ms | 32.1 ms | 0.5 ms | 0.4 ms | 🥶 | 256 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 8 ms |  | 0.5 ms | 0 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 7.9 ms |  | 0.3 ms | 0 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 256 MB |
| 42 ms |  | 15.2 ms | 19.8 ms | 🥵 | 256 MB |
| 131.9 ms | 27.6 ms | 0.5 ms | 0.3 ms | 🥶 | 256 MB |
| 7 ms |  | 0.5 ms | 0.1 ms | 🥵 | 256 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 256 MB |
| 13.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 256 MB |
| 88.9 ms |  | 61.6 ms | 19.8 ms | 🥵 | 256 MB |
| 8 ms |  | 0.3 ms | 0.2 ms | 🥵 | 256 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 256 MB |
| 5 ms |  | 0.3 ms | 0 ms | 🥵 | 256 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |## Results for 512 MB

| Measurement (512 MB) | Time (ms) |
|-------------|------|
| Average warm start response time | 7.1 ms |
| Average cold start response time | 62.7 ms |
| Fastest warm response time | 4.9 ms |
| Slowest warm response time | 88.9 ms |
| Fastest cold response time  | 6.9 ms |
| Slowest cold response time | 195 ms |
  

| Response time | Initialization | Invocation | Overhead | Cold/ Warm Start | Memory Size |
|---------------|----------------|------------|----------|------------------|-------------|
| 7.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 512 MB |
| 39 ms |  | 0.4 ms | 0.2 ms | 🥵 | 512 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 7.9 ms |  | 0.4 ms | 0 ms | 🥵 | 512 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 512 MB |
| 11.9 ms |  | 2.2 ms | 0.2 ms | 🥵 | 512 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 38.9 ms |  | 30 ms | 0.2 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 7.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 512 MB |
| 9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 105 ms | 31.4 ms | 0.4 ms | 0.4 ms | 🥶 | 512 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 512 MB |
| 195 ms | 20.3 ms | 0.7 ms | 0.2 ms | 🥶 | 512 MB |
| 7.9 ms |  | 0.5 ms | 0 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.5 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 101.9 ms | 24.6 ms | 0.8 ms | 0.1 ms | 🥶 | 512 MB |
| 5 ms |  | 0.3 ms | 0.2 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 512 MB |
| 105.9 ms | 24.6 ms | 0.6 ms | 0.4 ms | 🥶 | 512 MB |
| 23 ms |  | 14.9 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 512 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 512 MB |
| 17.9 ms |  | 12.1 ms | 0.1 ms | 🥵 | 512 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 5 ms |  | 0.4 ms | 0.2 ms | 🥵 | 512 MB |
| 26 ms |  | 0.7 ms | 19.5 ms | 🥵 | 512 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 34 ms |  | 25.7 ms | 0.1 ms | 🥵 | 512 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 512 MB |
| 7.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 8.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 512 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 8 ms |  | 0.4 ms | 0.3 ms | 🥵 | 512 MB |
| 108 ms | 28.3 ms | 0.7 ms | 0.3 ms | 🥶 | 512 MB |
| 7 ms |  | 0.5 ms | 0 ms | 🥵 | 512 MB |
| 12 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 12 ms |  | 6.6 ms | 0 ms | 🥵 | 512 MB |
| 7.9 ms |  | 0.3 ms | 0 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 121.9 ms | 17.9 ms | 0.6 ms | 0.3 ms | 🥶 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 512 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 4.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 7.9 ms |  | 0.4 ms | 0 ms | 🥵 | 512 MB |
| 7.9 ms |  | 0.3 ms | 0 ms | 🥵 | 512 MB |
| 9.9 ms |  | 0.7 ms | 0.2 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 512 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 11 ms |  | 0.4 ms | 0.2 ms | 🥵 | 512 MB |
| 117 ms | 32.9 ms | 0.6 ms | 0.4 ms | 🥶 | 512 MB |
| 17.9 ms |  | 0.4 ms | 0.3 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 6 ms |  | 0.2 ms | 0.1 ms | 🥵 | 512 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 72.9 ms |  | 40.1 ms | 19.7 ms | 🥵 | 512 MB |
| 7.9 ms |  | 0.3 ms | 0 ms | 🥵 | 512 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 512 MB |
| 8.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 512 MB |
| 8 ms |  | 0.6 ms | 0.2 ms | 🥵 | 512 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 29.9 ms |  | 24.7 ms | 0.2 ms | 🥵 | 512 MB |
| 7.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 512 MB |
| 121.9 ms | 28.6 ms | 0.4 ms | 0.1 ms | 🥶 | 512 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 7 ms |  | 0.4 ms | 0.2 ms | 🥵 | 512 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 5.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 512 MB |
| 8 ms |  | 0.3 ms | 0 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 512 MB |
| 7.9 ms |  | 0.4 ms | 0 ms | 🥵 | 512 MB |
| 7.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 512 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 61 ms |  | 55.4 ms | 0.2 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 512 MB |
| 9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 1.3 ms | 0.3 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms | 25.4 ms | 0.3 ms | 0.1 ms | 🥶 | 512 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 24.9 ms |  | 17.8 ms | 0.1 ms | 🥵 | 512 MB |
| 4.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 107 ms | 20.1 ms | 0.7 ms | 3.4 ms | 🥶 | 512 MB |
| 13 ms |  | 6 ms | 0.1 ms | 🥵 | 512 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 8 ms |  | 0.4 ms | 0 ms | 🥵 | 512 MB |
| 7.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 512 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 512 MB |
| 9 ms |  | 0.3 ms | 0 ms | 🥵 | 512 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 8 ms |  | 0.4 ms | 0.3 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 512 MB |
| 134.9 ms | 32.1 ms | 0.5 ms | 0.4 ms | 🥶 | 512 MB |
| 8 ms |  | 0.5 ms | 0 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 512 MB |
| 24.9 ms |  | 16.5 ms | 0.1 ms | 🥵 | 512 MB |
| 7.9 ms |  | 0.3 ms | 0 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 42 ms |  | 15.2 ms | 19.8 ms | 🥵 | 512 MB |
| 7.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 512 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 7 ms |  | 0.5 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 512 MB |
| 95.9 ms | 29 ms | 0.9 ms | 0.6 ms | 🥶 | 512 MB |
| 131.9 ms | 27.6 ms | 0.5 ms | 0.3 ms | 🥶 | 512 MB |
| 8 ms |  | 0.3 ms | 0.2 ms | 🥵 | 512 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 512 MB |
| 13.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 512 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 88.9 ms |  | 61.6 ms | 19.8 ms | 🥵 | 512 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 8 ms | 27.4 ms | 0.6 ms | 0.1 ms | 🥶 | 512 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 512 MB |
| 5 ms |  | 0.3 ms | 0 ms | 🥵 | 512 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |## Results for 1024 MB

| Measurement (1024 MB) | Time (ms) |
|-------------|------|
| Average warm start response time | 7.5 ms |
| Average cold start response time | 59.5 ms |
| Fastest warm response time | 4.9 ms |
| Slowest warm response time | 88.9 ms |
| Fastest cold response time  | 6.9 ms |
| Slowest cold response time | 195 ms |
  

| Response time | Initialization | Invocation | Overhead | Cold/ Warm Start | Memory Size |
|---------------|----------------|------------|----------|------------------|-------------|
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 11.9 ms |  | 2.2 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.4 ms | 0 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 13.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.5 ms | 0 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 1024 MB |
| 5 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 105.9 ms | 24.6 ms | 0.6 ms | 0.4 ms | 🥶 | 1024 MB |
| 101.9 ms | 24.6 ms | 0.8 ms | 0.1 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 102.9 ms | 26.7 ms | 0.7 ms | 0.3 ms | 🥶 | 1024 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.3 ms | 0 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 7 ms |  | 0.5 ms | 0 ms | 🥵 | 1024 MB |
| 117 ms | 32.9 ms | 0.6 ms | 0.4 ms | 🥶 | 1024 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 17.9 ms |  | 0.4 ms | 0.3 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 8.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.3 ms | 0 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.5 ms | 0.1 ms | 🥵 | 1024 MB |
| 7 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 121.9 ms | 28.6 ms | 0.4 ms | 0.1 ms | 🥶 | 1024 MB |
| 8 ms |  | 0.6 ms | 0.2 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.4 ms | 0 ms | 🥵 | 1024 MB |
| 7 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.4 ms | 0.3 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 61 ms |  | 55.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 24.9 ms |  | 17.8 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 1.3 ms | 0.3 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 5.9 ms |  | 0.3 ms | 0 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.4 ms | 0 ms | 🥵 | 1024 MB |
| 9 ms |  | 0.3 ms | 0 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.4 ms | 0.3 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.5 ms | 0 ms | 🥵 | 1024 MB |
| 9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 1024 MB |
| 134.9 ms | 32.1 ms | 0.5 ms | 0.4 ms | 🥶 | 1024 MB |
| 13.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.3 ms | 0 ms | 🥵 | 1024 MB |
| 24.9 ms |  | 16.5 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 88.9 ms |  | 61.6 ms | 19.8 ms | 🥵 | 1024 MB |
| 9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 5.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.3 ms | 0 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.6 ms | 0.2 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 134 ms | 20.1 ms | 0.5 ms | 0.4 ms | 🥶 | 1024 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 39 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 1024 MB |
| 38.9 ms |  | 30 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 108 ms | 24.5 ms | 0.4 ms | 0.3 ms | 🥶 | 1024 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 105 ms | 31.4 ms | 0.4 ms | 0.4 ms | 🥶 | 1024 MB |
| 9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 195 ms | 20.3 ms | 0.7 ms | 0.2 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.5 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 1024 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 23 ms |  | 14.9 ms | 0.1 ms | 🥵 | 1024 MB |
| 106.9 ms | 28 ms | 0.4 ms | 0.2 ms | 🥶 | 1024 MB |
| 17.9 ms |  | 12.1 ms | 0.1 ms | 🥵 | 1024 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 5 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 26 ms |  | 0.7 ms | 19.5 ms | 🥵 | 1024 MB |
| 34 ms |  | 25.7 ms | 0.1 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 8.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 95.9 ms | 26.5 ms | 0.4 ms | 0.1 ms | 🥶 | 1024 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 7 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.4 ms | 0.3 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 1024 MB |
| 12 ms |  | 6.6 ms | 0 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.3 ms | 0 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 108 ms | 28.3 ms | 0.7 ms | 0.3 ms | 🥶 | 1024 MB |
| 12 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 4.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 12 ms |  | 0.5 ms | 0.1 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.4 ms | 0 ms | 🥵 | 1024 MB |
| 121.9 ms | 17.9 ms | 0.6 ms | 0.3 ms | 🥶 | 1024 MB |
| 9.9 ms |  | 0.7 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 11 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 72.9 ms |  | 40.1 ms | 19.7 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.2 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 9.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 29.9 ms |  | 24.7 ms | 0.2 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.9 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 1024 MB |
| 5.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.3 ms | 0 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms | 25.4 ms | 0.3 ms | 0.1 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 1024 MB |
| 9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 107 ms | 20.1 ms | 0.7 ms | 3.4 ms | 🥶 | 1024 MB |
| 9 ms |  | 0.4 ms | 0 ms | 🥵 | 1024 MB |
| 4.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 13 ms |  | 6 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 42 ms |  | 15.2 ms | 19.8 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 7 ms |  | 0.5 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 95.9 ms | 29 ms | 0.9 ms | 0.6 ms | 🥶 | 1024 MB |
| 4.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 131.9 ms | 27.6 ms | 0.5 ms | 0.3 ms | 🥶 | 1024 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 13.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 1024 MB |
| 8.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 5 ms |  | 0.3 ms | 0 ms | 🥵 | 1024 MB |
| 8 ms | 27.4 ms | 0.6 ms | 0.1 ms | 🥶 | 1024 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |## Results for 2048 MB

| Measurement (2048 MB) | Time (ms) |
|-------------|------|
| Average warm start response time | 7.6 ms |
| Average cold start response time | 59.2 ms |
| Fastest warm response time | 4.9 ms |
| Slowest warm response time | 88.9 ms |
| Fastest cold response time  | 6.9 ms |
| Slowest cold response time | 203.9 ms |
  

| Response time | Initialization | Invocation | Overhead | Cold/ Warm Start | Memory Size |
|---------------|----------------|------------|----------|------------------|-------------|
| 11.9 ms |  | 2.2 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.4 ms | 0 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 13.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 7 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.5 ms | 0 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.4 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 101.9 ms | 24.6 ms | 0.8 ms | 0.1 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 5 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 105.9 ms | 24.6 ms | 0.6 ms | 0.4 ms | 🥶 | 2048 MB |
| 7.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 102.9 ms | 26.7 ms | 0.7 ms | 0.3 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 7 ms |  | 0.5 ms | 0 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 105 ms | 24 ms | 0.4 ms | 0.3 ms | 🥶 | 2048 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 117 ms | 32.9 ms | 0.6 ms | 0.4 ms | 🥶 | 2048 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 17.9 ms |  | 0.4 ms | 0.3 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 2048 MB |
| 8.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 7 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 121.9 ms | 28.6 ms | 0.4 ms | 0.1 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.6 ms | 0.2 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.4 ms | 0 ms | 🥵 | 2048 MB |
| 7 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.3 ms | 🥵 | 2048 MB |
| 61 ms |  | 55.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 24.9 ms |  | 17.8 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 1.3 ms | 0.3 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.4 ms | 0.3 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 5 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 4.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 5.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.4 ms | 0 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 5.9 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 134.9 ms | 32.1 ms | 0.5 ms | 0.4 ms | 🥶 | 2048 MB |
| 9 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.4 ms | 0.3 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.5 ms | 0 ms | 🥵 | 2048 MB |
| 9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 2048 MB |
| 13.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 24.9 ms |  | 16.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 88.9 ms |  | 61.6 ms | 19.8 ms | 🥵 | 2048 MB |
| 9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 7 ms |  | 0.4 ms | 0 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 39 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 5.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.6 ms | 0.2 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 134 ms | 20.1 ms | 0.5 ms | 0.4 ms | 🥶 | 2048 MB |
| 38.9 ms |  | 30 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 108 ms | 24.5 ms | 0.4 ms | 0.3 ms | 🥶 | 2048 MB |
| 7.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 105 ms | 31.4 ms | 0.4 ms | 0.4 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.5 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 13 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 195 ms | 20.3 ms | 0.7 ms | 0.2 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 106.9 ms | 28 ms | 0.4 ms | 0.2 ms | 🥶 | 2048 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 23 ms |  | 14.9 ms | 0.1 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 17.9 ms |  | 12.1 ms | 0.1 ms | 🥵 | 2048 MB |
| 34 ms |  | 25.7 ms | 0.1 ms | 🥵 | 2048 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 5 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 26 ms |  | 0.7 ms | 19.5 ms | 🥵 | 2048 MB |
| 8.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 95.9 ms | 26.5 ms | 0.4 ms | 0.1 ms | 🥶 | 2048 MB |
| 7.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 2048 MB |
| 7 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.4 ms | 0.3 ms | 🥵 | 2048 MB |
| 12 ms |  | 6.6 ms | 0 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 108 ms | 28.3 ms | 0.7 ms | 0.3 ms | 🥶 | 2048 MB |
| 12 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.6 ms | 0.2 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 12 ms |  | 0.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.4 ms | 0 ms | 🥵 | 2048 MB |
| 121.9 ms | 17.9 ms | 0.6 ms | 0.3 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 4.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 11 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 9.9 ms |  | 0.7 ms | 0.2 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.2 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 72.9 ms |  | 40.1 ms | 19.7 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 40.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 9.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 7 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.4 ms | 0.3 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 29.9 ms |  | 24.7 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 203.9 ms | 28.2 ms | 0.9 ms | 0.5 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 5.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.9 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms | 25.4 ms | 0.3 ms | 0.1 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 107 ms | 20.1 ms | 0.7 ms | 3.4 ms | 🥶 | 2048 MB |
| 4.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 105 ms | 18.7 ms | 0.4 ms | 0.2 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 9 ms |  | 0.4 ms | 0 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 13 ms |  | 6 ms | 0.1 ms | 🥵 | 2048 MB |
| 42 ms |  | 15.2 ms | 19.8 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.4 ms | 0 ms | 🥵 | 2048 MB |
| 7 ms |  | 0.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 95.9 ms | 29 ms | 0.9 ms | 0.6 ms | 🥶 | 2048 MB |
| 131.9 ms | 27.6 ms | 0.5 ms | 0.3 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 4.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 13.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 8.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 115 ms | 28.2 ms | 0.5 ms | 0.3 ms | 🥶 | 2048 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 5 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 105.9 ms | 19.3 ms | 0.7 ms | 0.7 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 8 ms | 27.4 ms | 0.6 ms | 0.1 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |## Results for 3072 MB

| Measurement (3072 MB) | Time (ms) |
|-------------|------|
| Average warm start response time | 6.2 ms |
| Average cold start response time | 83.8 ms |
| Fastest warm response time | 4.9 ms |
| Slowest warm response time | 88.9 ms |
| Fastest cold response time  | 6.9 ms |
| Slowest cold response time | 203.9 ms |
  

| Response time | Initialization | Invocation | Overhead | Cold/ Warm Start | Memory Size |
|---------------|----------------|------------|----------|------------------|-------------|
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.4 ms | 0 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 11.9 ms |  | 2.2 ms | 0.2 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 105 ms | 21.4 ms | 0.4 ms | 0.1 ms | 🥶 | 3072 MB |
| 9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 13.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 7 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.5 ms | 0 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 101.9 ms | 24.6 ms | 0.8 ms | 0.1 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.4 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 5 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 5.9 ms |  | 0.4 ms | 0 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 108.9 ms | 17.5 ms | 0.6 ms | 0.7 ms | 🥶 | 3072 MB |
| 105.9 ms | 24.6 ms | 0.6 ms | 0.4 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 102.9 ms | 26.7 ms | 0.7 ms | 0.3 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 7 ms |  | 0.5 ms | 0 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 105 ms | 24 ms | 0.4 ms | 0.3 ms | 🥶 | 3072 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 117 ms | 32.9 ms | 0.6 ms | 0.4 ms | 🥶 | 3072 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 5 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 17.9 ms |  | 0.4 ms | 0.3 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 8.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 7 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 121.9 ms | 28.6 ms | 0.4 ms | 0.1 ms | 🥶 | 3072 MB |
| 8 ms |  | 0.6 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.4 ms | 0 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 7 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 118.9 ms | 21.1 ms | 0.7 ms | 0.7 ms | 🥶 | 3072 MB |
| 7.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.3 ms | 🥵 | 3072 MB |
| 61 ms |  | 55.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 1.3 ms | 0.3 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.4 ms | 0.3 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 24.9 ms |  | 17.8 ms | 0.1 ms | 🥵 | 3072 MB |
| 9.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 3072 MB |
| 5 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 5.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 4.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.4 ms | 0 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 5.9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.4 ms | 0.3 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.6 ms | 0.1 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.5 ms | 0 ms | 🥵 | 3072 MB |
| 9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 3072 MB |
| 134.9 ms | 32.1 ms | 0.5 ms | 0.4 ms | 🥶 | 3072 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 24.9 ms |  | 16.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 13.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 88.9 ms |  | 61.6 ms | 19.8 ms | 🥵 | 3072 MB |
| 9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.6 ms | 0.2 ms | 🥵 | 3072 MB |
| 7 ms |  | 0.4 ms | 0 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 39 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 5.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 5 ms |  | 0.4 ms | 0 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 3072 MB |
| 134 ms | 20.1 ms | 0.5 ms | 0.4 ms | 🥶 | 3072 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 38.9 ms |  | 30 ms | 0.2 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 5.9 ms |  | 0.4 ms | 0 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 108 ms | 24.5 ms | 0.4 ms | 0.3 ms | 🥶 | 3072 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 105 ms | 31.4 ms | 0.4 ms | 0.4 ms | 🥶 | 3072 MB |
| 9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.5 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 195 ms | 20.3 ms | 0.7 ms | 0.2 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 13 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 13 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 23 ms |  | 14.9 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 106.9 ms | 28 ms | 0.4 ms | 0.2 ms | 🥶 | 3072 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 5 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 17.9 ms |  | 12.1 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 34 ms |  | 25.7 ms | 0.1 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 26 ms |  | 0.7 ms | 19.5 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 8.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 95.9 ms | 26.5 ms | 0.4 ms | 0.1 ms | 🥶 | 3072 MB |
| 7 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.4 ms | 0.3 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 3072 MB |
| 12 ms |  | 6.6 ms | 0 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 108 ms | 28.3 ms | 0.7 ms | 0.3 ms | 🥶 | 3072 MB |
| 6 ms |  | 0.6 ms | 0.2 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 3072 MB |
| 12 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 12 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 4.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.4 ms | 0 ms | 🥵 | 3072 MB |
| 121.9 ms | 17.9 ms | 0.6 ms | 0.3 ms | 🥶 | 3072 MB |
| 9.9 ms |  | 0.7 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 11 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.3 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.2 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 72.9 ms |  | 40.1 ms | 19.7 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 40.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 9.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.4 ms | 0.3 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 7 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 3072 MB |
| 203.9 ms | 28.2 ms | 0.9 ms | 0.5 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 29.9 ms |  | 24.7 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 5.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.9 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 114 ms | 21.3 ms | 0.5 ms | 0.2 ms | 🥶 | 3072 MB |
| 9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms | 25.4 ms | 0.3 ms | 0.1 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 107 ms | 20.1 ms | 0.7 ms | 3.4 ms | 🥶 | 3072 MB |
| 4.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 9 ms |  | 0.4 ms | 0 ms | 🥵 | 3072 MB |
| 105 ms | 18.7 ms | 0.4 ms | 0.2 ms | 🥶 | 3072 MB |
| 13 ms |  | 6 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.4 ms | 0 ms | 🥵 | 3072 MB |
| 42 ms |  | 15.2 ms | 19.8 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 7 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 4.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 107 ms | 20.1 ms | 0.6 ms | 0.2 ms | 🥶 | 3072 MB |
| 8.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 95.9 ms | 29 ms | 0.9 ms | 0.6 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 131.9 ms | 27.6 ms | 0.5 ms | 0.3 ms | 🥶 | 3072 MB |
| 13.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 115 ms | 28.2 ms | 0.5 ms | 0.3 ms | 🥶 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 5 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 8 ms | 27.4 ms | 0.6 ms | 0.1 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 105.9 ms | 19.3 ms | 0.7 ms | 0.7 ms | 🥶 | 3072 MB |
| 8 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 5 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |## Results for 4096 MB

| Measurement (4096 MB) | Time (ms) |
|-------------|------|
| Average warm start response time | 6 ms |
| Average cold start response time | 83.2 ms |
| Fastest warm response time | 4.9 ms |
| Slowest warm response time | 88.9 ms |
| Fastest cold response time  | 6.9 ms |
| Slowest cold response time | 203.9 ms |
  

| Response time | Initialization | Invocation | Overhead | Cold/ Warm Start | Memory Size |
|---------------|----------------|------------|----------|------------------|-------------|
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 11.9 ms |  | 2.2 ms | 0.2 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 105 ms | 21.4 ms | 0.4 ms | 0.1 ms | 🥶 | 4096 MB |
| 13.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.5 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.4 ms | 🥵 | 4096 MB |
| 102.9 ms | 18.6 ms | 0.6 ms | 0.3 ms | 🥶 | 4096 MB |
| 101.9 ms | 24.6 ms | 0.8 ms | 0.1 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 5 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 108.9 ms | 17.5 ms | 0.6 ms | 0.7 ms | 🥶 | 4096 MB |
| 5.9 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 105.9 ms | 24.6 ms | 0.6 ms | 0.4 ms | 🥶 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 102.9 ms | 26.7 ms | 0.7 ms | 0.3 ms | 🥶 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.5 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 105 ms | 24 ms | 0.4 ms | 0.3 ms | 🥶 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 117 ms | 32.9 ms | 0.6 ms | 0.4 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 5 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 17.9 ms |  | 0.4 ms | 0.3 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 8.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 125 ms | 21.3 ms | 0.5 ms | 0.1 ms | 🥶 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 121.9 ms | 28.6 ms | 0.4 ms | 0.1 ms | 🥶 | 4096 MB |
| 8 ms |  | 0.6 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 118.9 ms | 21.1 ms | 0.7 ms | 0.7 ms | 🥶 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.3 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.3 ms | 🥵 | 4096 MB |
| 61 ms |  | 55.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 24.9 ms |  | 17.8 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 1.3 ms | 0.3 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 13 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 9.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 4096 MB |
| 5 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 4.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 126 ms | 38.9 ms | 0.9 ms | 0.1 ms | 🥶 | 4096 MB |
| 5.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 8.9 ms | 21 ms | 0.4 ms | 0.1 ms | 🥶 | 4096 MB |
| 5.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.3 ms | 🥵 | 4096 MB |
| 9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 4096 MB |
| 134.9 ms | 32.1 ms | 0.5 ms | 0.4 ms | 🥶 | 4096 MB |
| 9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.6 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.3 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.5 ms | 0 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 24.9 ms |  | 16.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 13.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 88.9 ms |  | 61.6 ms | 19.8 ms | 🥵 | 4096 MB |
| 9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.6 ms | 0.2 ms | 🥵 | 4096 MB |
| 94.9 ms | 19.6 ms | 0.7 ms | 0.1 ms | 🥶 | 4096 MB |
| 5 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 134 ms | 20.1 ms | 0.5 ms | 0.4 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 39 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 5.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 38.9 ms |  | 30 ms | 0.2 ms | 🥵 | 4096 MB |
| 5.9 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 108 ms | 24.5 ms | 0.4 ms | 0.3 ms | 🥶 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 105 ms | 31.4 ms | 0.4 ms | 0.4 ms | 🥶 | 4096 MB |
| 9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.5 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 195 ms | 20.3 ms | 0.7 ms | 0.2 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 13 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 13 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 23 ms |  | 14.9 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 106.9 ms | 28 ms | 0.4 ms | 0.2 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 34 ms |  | 25.7 ms | 0.1 ms | 🥵 | 4096 MB |
| 17.9 ms |  | 12.1 ms | 0.1 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 5 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 26 ms |  | 0.7 ms | 19.5 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 8.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 95.9 ms | 26.5 ms | 0.4 ms | 0.1 ms | 🥶 | 4096 MB |
| 7 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.3 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 108 ms | 28.3 ms | 0.7 ms | 0.3 ms | 🥶 | 4096 MB |
| 12 ms |  | 6.6 ms | 0 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.6 ms | 0.2 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 4096 MB |
| 12 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 4.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 12 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 121.9 ms | 17.9 ms | 0.6 ms | 0.3 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 9.9 ms |  | 0.7 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.2 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 11 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.3 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 72.9 ms |  | 40.1 ms | 19.7 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 40.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 9.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.5 ms | 0 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0.3 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 29.9 ms |  | 24.7 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 203.9 ms | 28.2 ms | 0.9 ms | 0.5 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 114 ms | 21.3 ms | 0.5 ms | 0.2 ms | 🥶 | 4096 MB |
| 5.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.9 ms | 0.2 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms | 25.4 ms | 0.3 ms | 0.1 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 107 ms | 20.1 ms | 0.7 ms | 3.4 ms | 🥶 | 4096 MB |
| 4.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 9 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 105 ms | 18.7 ms | 0.4 ms | 0.2 ms | 🥶 | 4096 MB |
| 13 ms |  | 6 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 42 ms |  | 15.2 ms | 19.8 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 95.9 ms | 29 ms | 0.9 ms | 0.6 ms | 🥶 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 4.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 131.9 ms | 27.6 ms | 0.5 ms | 0.3 ms | 🥶 | 4096 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 107 ms | 20.1 ms | 0.6 ms | 0.2 ms | 🥶 | 4096 MB |
| 8.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 13.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.4 ms | 0.3 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 115 ms | 28.2 ms | 0.5 ms | 0.3 ms | 🥶 | 4096 MB |
| 5 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms | 27.4 ms | 0.6 ms | 0.1 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 105.9 ms | 19.3 ms | 0.7 ms | 0.7 ms | 🥶 | 4096 MB |
| 8 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 5 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |

## XRay Example of a Cold Start

<img width="1476" alt="Screenshot 2020-10-07 at 23 01 40" src="https://user-images.githubusercontent.com/1189998/95387505-178a1d00-08f1-11eb-83a7-7bc32eee48e2.png">

## XRay Example of a Warm Start

<img width="1479" alt="Screenshot 2020-10-07 at 23 01 23" src="https://user-images.githubusercontent.com/1189998/95387509-1953e080-08f1-11eb-8d46-ac25efa235e4.png">
