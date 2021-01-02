
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



## Overview

  
- [Results for 128 MB](#results-for-128-mb)
- [Results for 256 MB](#results-for-256-mb)
- [Results for 512 MB](#results-for-512-mb)
- [Results for 1024 MB](#results-for-1024-mb)
- [Results for 2048 MB](#results-for-2048-mb)
- [Results for 3072 MB](#results-for-3072-mb)
- [Results for 4096 MB](#results-for-4096-mb)


## Results for 128 MB

| Measurement (128 MB) | Time (ms) |
|-------------|------|
| Average warm start response time | 70 ms |
| Average cold start response time | 98 ms |
| Fastest warm response time | 4.9 ms |
| Slowest warm response time | 352.9 ms |
| Fastest cold response time  | 95.9 ms |
| Slowest cold response time | 100 ms |
  

| Response time | Initialization | Invocation | Overhead | Cold/ Warm Start | Memory Size |
|---------------|----------------|------------|----------|------------------|-------------|
| 85 ms |  |  |  | 🥵 | 128 MB |
| 89.9 ms |  |  |  | 🥵 | 128 MB |
| 98 ms |  |  |  | 🥵 | 128 MB |
| 7.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 128 MB |
| 115 ms |  |  |  | 🥵 | 128 MB |
| 99.9 ms |  |  |  | 🥵 | 128 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 5 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 19 ms |  | 12.7 ms | 0 ms | 🥵 | 128 MB |
| 88.9 ms |  |  |  | 🥵 | 128 MB |
| 95.9 ms |  |  |  | 🥵 | 128 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 115.9 ms |  |  |  | 🥵 | 128 MB |
| 4.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 128 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 108.9 ms |  |  |  | 🥵 | 128 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 128 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 101.9 ms |  |  |  | 🥵 | 128 MB |
| 114 ms |  |  |  | 🥵 | 128 MB |
| 8 ms |  | 0.3 ms | 0.2 ms | 🥵 | 128 MB |
| 7 ms |  | 0.5 ms | 0.2 ms | 🥵 | 128 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 128 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 5 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 7 ms |  | 0.3 ms | 0 ms | 🥵 | 128 MB |
| 105.9 ms |  |  |  | 🥵 | 128 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 98 ms |  |  |  | 🥵 | 128 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 4.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 95.9 ms |  |  |  | 🥵 | 128 MB |
| 6 ms |  | 0.6 ms | 0.1 ms | 🥵 | 128 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 6.9 ms |  | 0.3 ms | 0.3 ms | 🥵 | 128 MB |
| 95.9 ms |  |  |  | 🥵 | 128 MB |
| 11 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 5.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 128 MB |
| 8 ms |  | 0.4 ms | 0 ms | 🥵 | 128 MB |
| 95.9 ms | 25.1 ms | 0.4 ms | 0.2 ms | 🥶 | 128 MB |
| 4.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 128 MB |
| 95 ms |  |  |  | 🥵 | 128 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 131.9 ms |  |  |  | 🥵 | 128 MB |
| 92.9 ms |  |  |  | 🥵 | 128 MB |
| 7 ms |  | 0.4 ms | 0.2 ms | 🥵 | 128 MB |
| 135.9 ms |  |  |  | 🥵 | 128 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 92.9 ms |  |  |  | 🥵 | 128 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 104.9 ms |  |  |  | 🥵 | 128 MB |
| 102.9 ms |  |  |  | 🥵 | 128 MB |
| 98.9 ms |  |  |  | 🥵 | 128 MB |
| 97 ms |  |  |  | 🥵 | 128 MB |
| 114 ms |  |  |  | 🥵 | 128 MB |
| 93.9 ms |  |  |  | 🥵 | 128 MB |
| 88.9 ms |  |  |  | 🥵 | 128 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 101.9 ms |  |  |  | 🥵 | 128 MB |
| 92 ms |  |  |  | 🥵 | 128 MB |
| 9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 128 MB |
| 100 ms | 18.5 ms | 0.6 ms | 0.3 ms | 🥶 | 128 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 129.9 ms |  |  |  | 🥵 | 128 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 98 ms |  |  |  | 🥵 | 128 MB |
| 84 ms |  |  |  | 🥵 | 128 MB |
| 8.9 ms |  | 0.8 ms | 0.1 ms | 🥵 | 128 MB |
| 88 ms |  |  |  | 🥵 | 128 MB |
| 128 ms |  |  |  | 🥵 | 128 MB |
| 108.9 ms |  |  |  | 🥵 | 128 MB |
| 5 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 93.9 ms |  |  |  | 🥵 | 128 MB |
| 5 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 114 ms |  |  |  | 🥵 | 128 MB |
| 89.9 ms |  |  |  | 🥵 | 128 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 128 MB |
| 98.9 ms |  |  |  | 🥵 | 128 MB |
| 83.9 ms |  |  |  | 🥵 | 128 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 100.9 ms |  |  |  | 🥵 | 128 MB |
| 91 ms |  |  |  | 🥵 | 128 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 101.9 ms |  |  |  | 🥵 | 128 MB |
| 101.9 ms |  |  |  | 🥵 | 128 MB |
| 100.9 ms |  |  |  | 🥵 | 128 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 6 ms |  | 0.7 ms | 0.1 ms | 🥵 | 128 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 90.9 ms |  |  |  | 🥵 | 128 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 128 MB |
| 103.9 ms |  |  |  | 🥵 | 128 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 108.9 ms |  |  |  | 🥵 | 128 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 128 MB |
| 121.9 ms |  |  |  | 🥵 | 128 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 100.9 ms |  |  |  | 🥵 | 128 MB |
| 132.9 ms |  |  |  | 🥵 | 128 MB |
| 137 ms |  |  |  | 🥵 | 128 MB |
| 91 ms |  |  |  | 🥵 | 128 MB |
| 124 ms |  |  |  | 🥵 | 128 MB |
| 139.9 ms |  |  |  | 🥵 | 128 MB |
| 4.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 152.9 ms |  |  |  | 🥵 | 128 MB |
| 105 ms |  |  |  | 🥵 | 128 MB |
| 85.9 ms |  |  |  | 🥵 | 128 MB |
| 97 ms |  |  |  | 🥵 | 128 MB |
| 92.9 ms |  |  |  | 🥵 | 128 MB |
| 45 ms |  | 0.3 ms | 39.2 ms | 🥵 | 128 MB |
| 111 ms |  |  |  | 🥵 | 128 MB |
| 5 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 4.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 128 MB |
| 6 ms |  | 0.5 ms | 0.1 ms | 🥵 | 128 MB |
| 105 ms |  |  |  | 🥵 | 128 MB |
| 97.9 ms |  |  |  | 🥵 | 128 MB |
| 101.9 ms |  |  |  | 🥵 | 128 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 93.9 ms |  |  |  | 🥵 | 128 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 128 MB |
| 9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 128 MB |
| 157.9 ms |  |  |  | 🥵 | 128 MB |
| 8 ms |  | 0.5 ms | 0.1 ms | 🥵 | 128 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 96.9 ms |  |  |  | 🥵 | 128 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 99.9 ms |  |  |  | 🥵 | 128 MB |
| 78.9 ms |  |  |  | 🥵 | 128 MB |
| 92.9 ms |  |  |  | 🥵 | 128 MB |
| 6.9 ms |  | 0.6 ms | 0.1 ms | 🥵 | 128 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 105 ms |  |  |  | 🥵 | 128 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 110.9 ms |  |  |  | 🥵 | 128 MB |
| 100.9 ms |  |  |  | 🥵 | 128 MB |
| 84 ms |  |  |  | 🥵 | 128 MB |
| 121.9 ms |  |  |  | 🥵 | 128 MB |
| 89.9 ms |  |  |  | 🥵 | 128 MB |
| 90 ms |  |  |  | 🥵 | 128 MB |
| 194 ms |  |  |  | 🥵 | 128 MB |
| 5 ms |  | 0.3 ms | 0 ms | 🥵 | 128 MB |
| 98.9 ms |  |  |  | 🥵 | 128 MB |
| 8.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 128 MB |
| 352.9 ms |  |  |  | 🥵 | 128 MB |
| 115 ms |  |  |  | 🥵 | 128 MB |
| 7.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 128 MB |
| 96 ms |  |  |  | 🥵 | 128 MB |
| 106.9 ms |  |  |  | 🥵 | 128 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 128 MB |
| 125 ms |  |  |  | 🥵 | 128 MB |
| 6 ms |  | 0.4 ms | 0 ms | 🥵 | 128 MB |
| 86 ms |  |  |  | 🥵 | 128 MB |
| 7.9 ms |  | 0.4 ms | 0.3 ms | 🥵 | 128 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 150 ms |  |  |  | 🥵 | 128 MB |
| 111.9 ms |  |  |  | 🥵 | 128 MB |
| 101.9 ms |  |  |  | 🥵 | 128 MB |
| 5 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 129.9 ms |  |  |  | 🥵 | 128 MB |
| 4.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 128 MB |
| 120 ms |  |  |  | 🥵 | 128 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 128 MB |
| 101.9 ms |  |  |  | 🥵 | 128 MB |
| 92.9 ms |  |  |  | 🥵 | 128 MB |
| 87 ms |  |  |  | 🥵 | 128 MB |
| 138 ms |  |  |  | 🥵 | 128 MB |
| 9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 128 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 128 MB |
| 105.9 ms |  |  |  | 🥵 | 128 MB |

## Results for 256 MB

| Measurement (256 MB) | Time (ms) |
|-------------|------|
| Average warm start response time | 7.6 ms |
| Average cold start response time | 94.4 ms |
| Fastest warm response time | 4.9 ms |
| Slowest warm response time | 135.9 ms |
| Fastest cold response time  | 77 ms |
| Slowest cold response time | 161.9 ms |
  

| Response time | Initialization | Invocation | Overhead | Cold/ Warm Start | Memory Size |
|---------------|----------------|------------|----------|------------------|-------------|
| 98 ms | 26.7 ms | 0.6 ms | 0.3 ms | 🥶 | 256 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 112.9 ms | 18.3 ms | 0.8 ms | 0 ms | 🥶 | 256 MB |
| 5 ms |  | 0.3 ms | 0 ms | 🥵 | 256 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 7 ms |  | 0.3 ms | 0 ms | 🥵 | 256 MB |
| 111 ms | 28.9 ms | 0.5 ms | 0.4 ms | 🥶 | 256 MB |
| 95.9 ms | 17.9 ms | 0.6 ms | 0.1 ms | 🥶 | 256 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 256 MB |
| 7.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 256 MB |
| 88 ms | 23.4 ms | 0.6 ms | 0.2 ms | 🥶 | 256 MB |
| 94 ms | 18.8 ms | 0.6 ms | 0.4 ms | 🥶 | 256 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 256 MB |
| 4.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 256 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 256 MB |
| 101.9 ms | 30.4 ms | 0.6 ms | 0.5 ms | 🥶 | 256 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 256 MB |
| 4.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 256 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 90.9 ms | 22.9 ms | 0.5 ms | 0.1 ms | 🥶 | 256 MB |
| 9.9 ms |  | 4 ms | 0.1 ms | 🥵 | 256 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 5 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 95 ms | 19.4 ms | 0.6 ms | 0.4 ms | 🥶 | 256 MB |
| 77 ms | 18.8 ms | 0.5 ms | 0.3 ms | 🥶 | 256 MB |
| 115.9 ms | 31.4 ms | 0.4 ms | 0.2 ms | 🥶 | 256 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 96.9 ms | 24.4 ms | 0.5 ms | 0.2 ms | 🥶 | 256 MB |
| 102.9 ms | 30.7 ms | 0.5 ms | 0.2 ms | 🥶 | 256 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 99.9 ms | 30.1 ms | 0.6 ms | 0.3 ms | 🥶 | 256 MB |
| 6 ms |  | 0.3 ms | 0.4 ms | 🥵 | 256 MB |
| 89.9 ms | 25.4 ms | 0.6 ms | 0.3 ms | 🥶 | 256 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 5 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 4.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 6 ms |  | 0.3 ms | 0.3 ms | 🥵 | 256 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 105.9 ms | 21.9 ms | 0.4 ms | 0.1 ms | 🥶 | 256 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 5.9 ms |  | 0.3 ms | 0 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 94.9 ms | 19.1 ms | 0.4 ms | 0.1 ms | 🥶 | 256 MB |
| 98.9 ms | 27.1 ms | 0.5 ms | 0.2 ms | 🥶 | 256 MB |
| 123.9 ms | 18.8 ms | 0.6 ms | 0.4 ms | 🥶 | 256 MB |
| 101.9 ms | 18.7 ms | 0.5 ms | 0.6 ms | 🥶 | 256 MB |
| 97 ms | 25.8 ms | 0.5 ms | 0.2 ms | 🥶 | 256 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 256 MB |
| 105 ms | 29.2 ms | 0.5 ms | 0.1 ms | 🥶 | 256 MB |
| 92.9 ms | 18.1 ms | 0.6 ms | 0.4 ms | 🥶 | 256 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 83.9 ms | 21.5 ms | 0.6 ms | 0.3 ms | 🥶 | 256 MB |
| 103.9 ms | 24.9 ms | 0.6 ms | 0.1 ms | 🥶 | 256 MB |
| 103.9 ms | 23.8 ms | 0.5 ms | 0.2 ms | 🥶 | 256 MB |
| 18 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 5 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 118.9 ms | 29.2 ms | 0.6 ms | 0.1 ms | 🥶 | 256 MB |
| 93.9 ms | 26.4 ms | 0.5 ms | 0.2 ms | 🥶 | 256 MB |
| 102.9 ms | 28.5 ms | 0.6 ms | 0.4 ms | 🥶 | 256 MB |
| 83.9 ms | 17.6 ms | 0.6 ms | 0.4 ms | 🥶 | 256 MB |
| 104 ms | 27.8 ms | 0.7 ms | 0.3 ms | 🥶 | 256 MB |
| 83.9 ms | 22.7 ms | 0.4 ms | 0.1 ms | 🥶 | 256 MB |
| 9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 6 ms |  | 1.1 ms | 0 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 101 ms | 29.1 ms | 0.8 ms | 0.2 ms | 🥶 | 256 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 7.9 ms |  | 0.6 ms | 0.1 ms | 🥵 | 256 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 103 ms | 23 ms | 0.6 ms | 0.1 ms | 🥶 | 256 MB |
| 110 ms | 24 ms | 0.4 ms | 0.1 ms | 🥶 | 256 MB |
| 78.9 ms | 24.3 ms | 0.4 ms | 0.2 ms | 🥶 | 256 MB |
| 101 ms | 21.9 ms | 0.5 ms | 0.3 ms | 🥶 | 256 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 256 MB |
| 101.9 ms | 24.5 ms | 0.6 ms | 0.3 ms | 🥶 | 256 MB |
| 98 ms | 18.4 ms | 0.5 ms | 0.2 ms | 🥶 | 256 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 5 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 256 MB |
| 81 ms | 16.6 ms | 0.5 ms | 0.1 ms | 🥶 | 256 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 103.9 ms | 27 ms | 0.4 ms | 0.3 ms | 🥶 | 256 MB |
| 102.9 ms | 19.1 ms | 0.4 ms | 0.1 ms | 🥶 | 256 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 93.9 ms | 31.2 ms | 0.4 ms | 0.4 ms | 🥶 | 256 MB |
| 7.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 256 MB |
| 88.9 ms | 25.3 ms | 0.5 ms | 0.4 ms | 🥶 | 256 MB |
| 98.9 ms | 31.1 ms | 0.6 ms | 0.5 ms | 🥶 | 256 MB |
| 106.9 ms | 21.6 ms | 0.6 ms | 0.3 ms | 🥶 | 256 MB |
| 98 ms | 25.8 ms | 0.5 ms | 0.5 ms | 🥶 | 256 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 4.9 ms |  | 0.3 ms | 0 ms | 🥵 | 256 MB |
| 87 ms | 17.5 ms | 0.5 ms | 0.4 ms | 🥶 | 256 MB |
| 106.9 ms | 28 ms | 0.4 ms | 0.4 ms | 🥶 | 256 MB |
| 5 ms |  | 0.5 ms | 0.1 ms | 🥵 | 256 MB |
| 5.9 ms |  | 0.3 ms | 0 ms | 🥵 | 256 MB |
| 6 ms |  | 0.4 ms | 0 ms | 🥵 | 256 MB |
| 93.9 ms | 17.8 ms | 0.5 ms | 0.3 ms | 🥶 | 256 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 89.9 ms | 25.9 ms | 0.5 ms | 0.1 ms | 🥶 | 256 MB |
| 108 ms | 18.3 ms | 0.5 ms | 0.5 ms | 🥶 | 256 MB |
| 95 ms | 25.5 ms | 0.4 ms | 0.3 ms | 🥶 | 256 MB |
| 98 ms | 19 ms | 0.6 ms | 0.2 ms | 🥶 | 256 MB |
| 135.9 ms |  |  |  | 🥵 | 256 MB |
| 104 ms | 24.6 ms | 0.7 ms | 0.2 ms | 🥶 | 256 MB |
| 23 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 7.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 256 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 113.9 ms | 24.4 ms | 0.6 ms | 0.2 ms | 🥶 | 256 MB |
| 92.9 ms | 33 ms | 0.8 ms | 0.2 ms | 🥶 | 256 MB |
| 103 ms | 24.4 ms | 0.6 ms | 0.3 ms | 🥶 | 256 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 256 MB |
| 105.9 ms | 23.6 ms | 0.6 ms | 0.5 ms | 🥶 | 256 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 101 ms | 20.7 ms | 0.4 ms | 0.3 ms | 🥶 | 256 MB |
| 89.9 ms | 27.7 ms | 0.4 ms | 0.2 ms | 🥶 | 256 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 256 MB |
| 90.9 ms | 16.7 ms | 0.3 ms | 0.1 ms | 🥶 | 256 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 5 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 14.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 4.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 88.9 ms | 22 ms | 0.5 ms | 0.1 ms | 🥶 | 256 MB |
| 101 ms | 17.4 ms | 0.6 ms | 0.4 ms | 🥶 | 256 MB |
| 99.9 ms | 20.7 ms | 0.7 ms | 0.2 ms | 🥶 | 256 MB |
| 13 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 5 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 101.9 ms | 27.3 ms | 0.5 ms | 0.4 ms | 🥶 | 256 MB |
| 93 ms | 16.7 ms | 0.6 ms | 0.1 ms | 🥶 | 256 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 4.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 256 MB |
| 107 ms | 31.7 ms | 0.4 ms | 0.7 ms | 🥶 | 256 MB |
| 125 ms | 29.3 ms | 0.6 ms | 0.1 ms | 🥶 | 256 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 256 MB |
| 98 ms | 23.4 ms | 0.7 ms | 0.5 ms | 🥶 | 256 MB |
| 108.9 ms | 25.2 ms | 0.5 ms | 0.5 ms | 🥶 | 256 MB |
| 84 ms | 21.6 ms | 0.3 ms | 0.3 ms | 🥶 | 256 MB |
| 82 ms | 21 ms | 0.4 ms | 0.3 ms | 🥶 | 256 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 4.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 99.9 ms | 19.4 ms | 0.4 ms | 0.4 ms | 🥶 | 256 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 256 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 81 ms | 22.5 ms | 0.6 ms | 0.2 ms | 🥶 | 256 MB |
| 161.9 ms | 26 ms | 0.6 ms | 0.2 ms | 🥶 | 256 MB |
| 107 ms | 28.5 ms | 0.5 ms | 0.4 ms | 🥶 | 256 MB |
| 97.9 ms | 25.5 ms | 0.5 ms | 0.2 ms | 🥶 | 256 MB |
| 82 ms | 18 ms | 0.3 ms | 0.1 ms | 🥶 | 256 MB |
| 99.9 ms | 27.8 ms | 0.5 ms | 0.2 ms | 🥶 | 256 MB |
| 94 ms | 30.6 ms | 0.7 ms | 0.1 ms | 🥶 | 256 MB |
| 100.9 ms | 19.4 ms | 0.5 ms | 0.1 ms | 🥶 | 256 MB |
| 19.9 ms |  | 0.6 ms | 0.1 ms | 🥵 | 256 MB |
| 6 ms |  | 0.5 ms | 0 ms | 🥵 | 256 MB |
| 111 ms | 25.8 ms | 0.7 ms | 0.5 ms | 🥶 | 256 MB |
| 5 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 91 ms | 24 ms | 0.6 ms | 0.1 ms | 🥶 | 256 MB |
| 99.9 ms | 29.3 ms | 0.6 ms | 0.2 ms | 🥶 | 256 MB |
| 7.9 ms |  | 0.6 ms | 0.2 ms | 🥵 | 256 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 79.9 ms | 20.5 ms | 0.4 ms | 0.2 ms | 🥶 | 256 MB |
| 100 ms | 24.2 ms | 0.3 ms | 0.2 ms | 🥶 | 256 MB |
| 101.9 ms | 25.4 ms | 0.4 ms | 0.4 ms | 🥶 | 256 MB |
| 118.9 ms | 32.2 ms | 1.2 ms | 18.7 ms | 🥶 | 256 MB |
| 123.9 ms | 29.6 ms | 0.6 ms | 0.4 ms | 🥶 | 256 MB |
| 87.9 ms | 17.1 ms | 0.5 ms | 0.1 ms | 🥶 | 256 MB |
| 5 ms |  | 0.4 ms | 0.1 ms | 🥵 | 256 MB |
| 106.9 ms | 19.1 ms | 0.4 ms | 0.2 ms | 🥶 | 256 MB |
| 125 ms | 35.2 ms | 1.6 ms | 0.5 ms | 🥶 | 256 MB |
| 10.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 256 MB |
| 7.9 ms |  | 0.3 ms | 0.3 ms | 🥵 | 256 MB |
| 108 ms | 17.2 ms | 0.7 ms | 0.2 ms | 🥶 | 256 MB |
| 90 ms | 17 ms | 0.5 ms | 0.5 ms | 🥶 | 256 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 256 MB |
| 83 ms | 18.7 ms | 0.5 ms | 0.3 ms | 🥶 | 256 MB |
| 96.9 ms | 21.8 ms | 0.6 ms | 0.2 ms | 🥶 | 256 MB |

## Results for 512 MB

| Measurement (512 MB) | Time (ms) |
|-------------|------|
| Average warm start response time | 6.6 ms |
| Average cold start response time | 220.7 ms |
| Fastest warm response time | 5.9 ms |
| Slowest warm response time | 16.9 ms |
| Fastest cold response time  | 78.9 ms |
| Slowest cold response time | 333.9 ms |
  

| Response time | Initialization | Invocation | Overhead | Cold/ Warm Start | Memory Size |
|---------------|----------------|------------|----------|------------------|-------------|
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 100 ms | 23.4 ms | 0.3 ms | 0.1 ms | 🥶 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 512 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 512 MB |
| 101 ms | 18 ms | 0.7 ms | 0.2 ms | 🥶 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 108 ms | 20.1 ms | 0.7 ms | 0.3 ms | 🥶 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 105 ms | 26.7 ms | 0.5 ms | 0.2 ms | 🥶 | 512 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.7 ms | 0.1 ms | 🥵 | 512 MB |
| 99.9 ms | 28.3 ms | 0.6 ms | 0.6 ms | 🥶 | 512 MB |
| 116 ms | 31.4 ms | 0.6 ms | 0.4 ms | 🥶 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 203.9 ms | 19.7 ms | 0.7 ms | 0.2 ms | 🥶 | 512 MB |
| 96.9 ms | 25.8 ms | 0.4 ms | 0.4 ms | 🥶 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 512 MB |
| 100.9 ms | 26.5 ms | 0.4 ms | 0.6 ms | 🥶 | 512 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 89.9 ms | 20.7 ms | 0.4 ms | 0.1 ms | 🥶 | 512 MB |
| 119.9 ms | 20.8 ms | 0.4 ms | 0.2 ms | 🥶 | 512 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 105 ms | 20.3 ms | 0.4 ms | 0.1 ms | 🥶 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 94 ms | 18.4 ms | 0.6 ms | 0.4 ms | 🥶 | 512 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 90.9 ms | 26.5 ms | 0.6 ms | 0.2 ms | 🥶 | 512 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 8 ms |  | 0.3 ms | 0.2 ms | 🥵 | 512 MB |
| 8 ms |  | 0.3 ms | 0.2 ms | 🥵 | 512 MB |
| 87 ms | 23.3 ms | 0.5 ms | 0.4 ms | 🥶 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 92 ms | 20.3 ms | 0.6 ms | 0.3 ms | 🥶 | 512 MB |
| 99.9 ms | 28.3 ms | 0.6 ms | 0.2 ms | 🥶 | 512 MB |
| 108 ms | 16.7 ms | 0.8 ms | 0.5 ms | 🥶 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 512 MB |
| 85.9 ms | 24.2 ms | 0.4 ms | 0.4 ms | 🥶 | 512 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 7.9 ms |  | 1.1 ms | 0.2 ms | 🥵 | 512 MB |
| 7 ms |  | 0.4 ms | 0 ms | 🥵 | 512 MB |
| 85.9 ms | 23.3 ms | 0.6 ms | 0.1 ms | 🥶 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 100.9 ms | 28 ms | 0.4 ms | 0.1 ms | 🥶 | 512 MB |
| 16.9 ms |  | 9.1 ms | 0.2 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 78.9 ms | 22.2 ms | 0.4 ms | 0.1 ms | 🥶 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 512 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 512 MB |
| 157 ms | 29 ms | 0.8 ms | 1.6 ms | 🥶 | 512 MB |
| 16 ms |  | 0.6 ms | 0.2 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.6 ms | 0.2 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 101 ms | 26.3 ms | 0.7 ms | 0.6 ms | 🥶 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 8 ms |  | 0.3 ms | 0 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 512 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 512 MB |
| 105.9 ms | 21.8 ms | 0.5 ms | 0.1 ms | 🥶 | 512 MB |
| 6 ms |  | 0.5 ms | 0 ms | 🥵 | 512 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 85.9 ms | 18.5 ms | 0.4 ms | 0.2 ms | 🥶 | 512 MB |
| 106 ms | 27.5 ms | 0.4 ms | 0.2 ms | 🥶 | 512 MB |
| 115.9 ms | 17.5 ms | 0.7 ms | 0 ms | 🥶 | 512 MB |
| 108.9 ms | 29.2 ms | 0.5 ms | 0.5 ms | 🥶 | 512 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 512 MB |
| 10.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 106 ms | 18.5 ms | 0.4 ms | 0 ms | 🥶 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 512 MB |
| 92 ms | 26.9 ms | 0.5 ms | 0.4 ms | 🥶 | 512 MB |
| 100.9 ms | 26.7 ms | 0.5 ms | 0.6 ms | 🥶 | 512 MB |
| 95 ms | 18.1 ms | 0.4 ms | 0.1 ms | 🥶 | 512 MB |
| 131 ms | 17.2 ms | 0.6 ms | 0.3 ms | 🥶 | 512 MB |
| 88 ms | 22.9 ms | 0.7 ms | 0.2 ms | 🥶 | 512 MB |
| 88.9 ms | 17.8 ms | 0.6 ms | 0.1 ms | 🥶 | 512 MB |
| 160 ms | 19.4 ms | 0.6 ms | 0.2 ms | 🥶 | 512 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 105 ms | 32.9 ms | 0.6 ms | 0.3 ms | 🥶 | 512 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 103 ms | 30.4 ms | 0.5 ms | 0.4 ms | 🥶 | 512 MB |
| 101 ms | 32.7 ms | 0.5 ms | 0.4 ms | 🥶 | 512 MB |
| 102.9 ms | 18.3 ms | 0.7 ms | 0.2 ms | 🥶 | 512 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 92 ms | 18.1 ms | 0.4 ms | 0.1 ms | 🥶 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 133.9 ms | 20.2 ms | 0.7 ms | 0.7 ms | 🥶 | 512 MB |
| 6 ms |  | 0.5 ms | 0 ms | 🥵 | 512 MB |
| 95 ms | 25.2 ms | 0.7 ms | 0.2 ms | 🥶 | 512 MB |
| 8.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 6 ms |  | 0.9 ms | 0.1 ms | 🥵 | 512 MB |
| 95.9 ms | 24.3 ms | 0.5 ms | 0.2 ms | 🥶 | 512 MB |
| 6 ms |  | 0.5 ms | 0.1 ms | 🥵 | 512 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 512 MB |
| 91 ms | 17.8 ms | 0.4 ms | 0.2 ms | 🥶 | 512 MB |
| 115.9 ms | 27.1 ms | 0.4 ms | 0.5 ms | 🥶 | 512 MB |
| 8 ms |  | 0.5 ms | 0.2 ms | 🥵 | 512 MB |
| 127 ms | 27.7 ms | 0.4 ms | 0.2 ms | 🥶 | 512 MB |
| 102.9 ms | 18.5 ms | 0.5 ms | 0.4 ms | 🥶 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 88 ms | 19.3 ms | 0.4 ms | 0.1 ms | 🥶 | 512 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 154 ms | 28.9 ms | 0.5 ms | 0.2 ms | 🥶 | 512 MB |
| 6.9 ms |  | 0.5 ms | 0.3 ms | 🥵 | 512 MB |
| 99.9 ms | 18.6 ms | 0.6 ms | 0.2 ms | 🥶 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 93 ms | 17 ms | 0.3 ms | 0.3 ms | 🥶 | 512 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 101 ms | 16.6 ms | 0.7 ms | 0.4 ms | 🥶 | 512 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 112.9 ms | 28.5 ms | 0.5 ms | 0.3 ms | 🥶 | 512 MB |
| 93 ms | 24.7 ms | 0.5 ms | 0.1 ms | 🥶 | 512 MB |
| 108.9 ms | 31.6 ms | 0.6 ms | 0.4 ms | 🥶 | 512 MB |
| 8 ms |  | 0.4 ms | 0.3 ms | 🥵 | 512 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 512 MB |
| 111.9 ms | 28.8 ms | 1.3 ms | 0.3 ms | 🥶 | 512 MB |
| 114 ms | 17.7 ms | 0.6 ms | 0.4 ms | 🥶 | 512 MB |
| 85.9 ms | 22.7 ms | 0.5 ms | 0.1 ms | 🥶 | 512 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 512 MB |
| 115.9 ms | 31.1 ms | 0.6 ms | 0.1 ms | 🥶 | 512 MB |
| 97 ms | 24.8 ms | 0.6 ms | 0.5 ms | 🥶 | 512 MB |
| 112.9 ms | 28.7 ms | 0.4 ms | 0.1 ms | 🥶 | 512 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |
| 333.9 ms | 19.9 ms | 0.8 ms | 0.5 ms | 🥶 | 512 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 512 MB |

## Results for 1024 MB

| Measurement (1024 MB) | Time (ms) |
|-------------|------|
| Average warm start response time | 7 ms |
| Average cold start response time | 96.6 ms |
| Fastest warm response time | 5.9 ms |
| Slowest warm response time | 29 ms |
| Fastest cold response time  | 80.9 ms |
| Slowest cold response time | 144 ms |
  

| Response time | Initialization | Invocation | Overhead | Cold/ Warm Start | Memory Size |
|---------------|----------------|------------|----------|------------------|-------------|
| 93.9 ms | 23 ms | 0.3 ms | 0.1 ms | 🥶 | 1024 MB |
| 107 ms | 27.6 ms | 0.6 ms | 0.7 ms | 🥶 | 1024 MB |
| 88 ms | 18.2 ms | 0.3 ms | 0.1 ms | 🥶 | 1024 MB |
| 8 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 120.9 ms | 18 ms | 0.4 ms | 0.3 ms | 🥶 | 1024 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 116.9 ms | 26.5 ms | 0.8 ms | 0.1 ms | 🥶 | 1024 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 100 ms | 24.4 ms | 0.5 ms | 0.1 ms | 🥶 | 1024 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 103.9 ms | 19.4 ms | 0.8 ms | 0.3 ms | 🥶 | 1024 MB |
| 91 ms | 21.5 ms | 0.6 ms | 0.3 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 110.9 ms | 17.9 ms | 0.5 ms | 0.3 ms | 🥶 | 1024 MB |
| 95.9 ms | 33 ms | 0.7 ms | 0.5 ms | 🥶 | 1024 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 102.9 ms | 29.6 ms | 0.6 ms | 0.2 ms | 🥶 | 1024 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 96.9 ms | 21.5 ms | 0.5 ms | 0.2 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.3 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 92 ms | 24.8 ms | 0.6 ms | 0.2 ms | 🥶 | 1024 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 89.9 ms | 25 ms | 0.5 ms | 0.2 ms | 🥶 | 1024 MB |
| 29 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 101.9 ms | 28.6 ms | 0.6 ms | 0.4 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 108 ms | 22.2 ms | 0.7 ms | 0.2 ms | 🥶 | 1024 MB |
| 9.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 8 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 108.9 ms | 18.6 ms | 0.6 ms | 0.2 ms | 🥶 | 1024 MB |
| 95 ms | 18.9 ms | 0.4 ms | 0.1 ms | 🥶 | 1024 MB |
| 103 ms | 31.4 ms | 0.6 ms | 0.2 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.6 ms | 0 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 88.9 ms | 23.2 ms | 0.4 ms | 0.2 ms | 🥶 | 1024 MB |
| 88.9 ms | 25.9 ms | 0.6 ms | 0.3 ms | 🥶 | 1024 MB |
| 102.9 ms | 28.6 ms | 0.6 ms | 0.4 ms | 🥶 | 1024 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 115.9 ms | 29.3 ms | 0.4 ms | 0.3 ms | 🥶 | 1024 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 1024 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 115.9 ms | 30.5 ms | 0.5 ms | 0.3 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 108.9 ms | 22.3 ms | 0.5 ms | 0.2 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 102 ms | 27.2 ms | 0.6 ms | 0.2 ms | 🥶 | 1024 MB |
| 10.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 98 ms | 30.7 ms | 0.6 ms | 0.4 ms | 🥶 | 1024 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.6 ms | 0.1 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 92.9 ms | 19.8 ms | 0.5 ms | 0.2 ms | 🥶 | 1024 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 101 ms | 34.3 ms | 0.6 ms | 0.3 ms | 🥶 | 1024 MB |
| 92 ms | 19.3 ms | 0.7 ms | 0.2 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 94 ms | 26.9 ms | 0.6 ms | 0.4 ms | 🥶 | 1024 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 90.9 ms | 24.9 ms | 0.4 ms | 0.2 ms | 🥶 | 1024 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 112.9 ms | 19.6 ms | 0.6 ms | 0.2 ms | 🥶 | 1024 MB |
| 102.9 ms | 19.7 ms | 0.6 ms | 0.2 ms | 🥶 | 1024 MB |
| 128.9 ms | 19.5 ms | 0.7 ms | 0.5 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 97 ms | 29.1 ms | 0.5 ms | 0.3 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 88.9 ms | 21.3 ms | 0.3 ms | 0.1 ms | 🥶 | 1024 MB |
| 104 ms | 17.4 ms | 0.4 ms | 0.2 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 97.9 ms | 18.5 ms | 0.7 ms | 0.2 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 92 ms | 26.2 ms | 0.6 ms | 0.3 ms | 🥶 | 1024 MB |
| 8 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 113.9 ms | 32.1 ms | 0.5 ms | 0.2 ms | 🥶 | 1024 MB |
| 13.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 99.9 ms | 26.3 ms | 0.5 ms | 0.3 ms | 🥶 | 1024 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 117 ms | 18.1 ms | 0.4 ms | 0.1 ms | 🥶 | 1024 MB |
| 97 ms | 24.4 ms | 0.6 ms | 0.2 ms | 🥶 | 1024 MB |
| 97 ms | 29.7 ms | 0.6 ms | 0.4 ms | 🥶 | 1024 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 108.9 ms | 22.3 ms | 0.8 ms | 0.4 ms | 🥶 | 1024 MB |
| 100 ms | 28.1 ms | 0.6 ms | 0.3 ms | 🥶 | 1024 MB |
| 93 ms | 20 ms | 0.5 ms | 0.1 ms | 🥶 | 1024 MB |
| 98 ms | 27.2 ms | 0.7 ms | 0.5 ms | 🥶 | 1024 MB |
| 114 ms | 26.8 ms | 0.5 ms | 0.1 ms | 🥶 | 1024 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 139 ms | 26.1 ms | 0.8 ms | 0.2 ms | 🥶 | 1024 MB |
| 88 ms | 21 ms | 0.5 ms | 0.1 ms | 🥶 | 1024 MB |
| 113.9 ms | 29.5 ms | 0.6 ms | 0.3 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 82.9 ms | 26 ms | 0.3 ms | 0.1 ms | 🥶 | 1024 MB |
| 95 ms | 30 ms | 0.7 ms | 0.4 ms | 🥶 | 1024 MB |
| 95.9 ms | 29.8 ms | 0.4 ms | 0.4 ms | 🥶 | 1024 MB |
| 91 ms | 29 ms | 0.4 ms | 0.1 ms | 🥶 | 1024 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 107 ms | 32.1 ms | 0.4 ms | 0.1 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 144 ms | 17.8 ms | 0.4 ms | 0.2 ms | 🥶 | 1024 MB |
| 6 ms |  | 0.4 ms | 0 ms | 🥵 | 1024 MB |
| 92.9 ms | 27.7 ms | 0.8 ms | 0.2 ms | 🥶 | 1024 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 92 ms | 17.2 ms | 0.6 ms | 0.2 ms | 🥶 | 1024 MB |
| 8 ms |  | 0.9 ms | 0 ms | 🥵 | 1024 MB |
| 101.9 ms | 20.4 ms | 0.4 ms | 0.1 ms | 🥶 | 1024 MB |
| 103.9 ms | 25.5 ms | 0.7 ms | 0.2 ms | 🥶 | 1024 MB |
| 96.9 ms | 27.4 ms | 0.8 ms | 0.2 ms | 🥶 | 1024 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 1024 MB |
| 113.9 ms | 17.4 ms | 0.4 ms | 0.1 ms | 🥶 | 1024 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 95.9 ms | 17.5 ms | 0.4 ms | 0.2 ms | 🥶 | 1024 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 88 ms | 21.3 ms | 0.5 ms | 0.1 ms | 🥶 | 1024 MB |
| 7.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 93.9 ms | 22.5 ms | 0.5 ms | 0 ms | 🥶 | 1024 MB |
| 92.9 ms | 20.8 ms | 0.4 ms | 0 ms | 🥶 | 1024 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 7.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 86.9 ms | 23.2 ms | 0.3 ms | 0.1 ms | 🥶 | 1024 MB |
| 138.9 ms | 18.4 ms | 0.4 ms | 0.1 ms | 🥶 | 1024 MB |
| 95 ms | 29.8 ms | 0.7 ms | 0.2 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 11.9 ms |  | 4.2 ms | 0.2 ms | 🥵 | 1024 MB |
| 26.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 88.9 ms | 22.1 ms | 0.6 ms | 0.1 ms | 🥶 | 1024 MB |
| 7 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 97.9 ms | 28.9 ms | 0.4 ms | 0.1 ms | 🥶 | 1024 MB |
| 94.9 ms | 28.2 ms | 0.5 ms | 0.2 ms | 🥶 | 1024 MB |
| 108.9 ms | 30.6 ms | 0.5 ms | 0.4 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 83.9 ms | 24.1 ms | 0.4 ms | 0.1 ms | 🥶 | 1024 MB |
| 97.9 ms | 26.6 ms | 0.6 ms | 0.3 ms | 🥶 | 1024 MB |
| 99.9 ms | 22.8 ms | 0.5 ms | 0.1 ms | 🥶 | 1024 MB |
| 7 ms |  | 0.4 ms | 0.3 ms | 🥵 | 1024 MB |
| 91 ms | 27 ms | 0.5 ms | 0.3 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 95.9 ms | 17.7 ms | 0.7 ms | 0.3 ms | 🥶 | 1024 MB |
| 98 ms | 23.8 ms | 0.6 ms | 0.2 ms | 🥶 | 1024 MB |
| 102.9 ms | 28.3 ms | 0.8 ms | 0.3 ms | 🥶 | 1024 MB |
| 108 ms | 18.8 ms | 0.6 ms | 0.6 ms | 🥶 | 1024 MB |
| 88.9 ms | 20.2 ms | 0.4 ms | 0.1 ms | 🥶 | 1024 MB |
| 95 ms | 26.2 ms | 0.5 ms | 0.4 ms | 🥶 | 1024 MB |
| 8 ms |  | 0.6 ms | 0.2 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 103.9 ms | 17.9 ms | 0.6 ms | 0.2 ms | 🥶 | 1024 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 87 ms | 22.2 ms | 0.4 ms | 0.1 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 1024 MB |
| 5.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |
| 80.9 ms | 24.9 ms | 0.4 ms | 0.4 ms | 🥶 | 1024 MB |
| 8 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 1024 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 1024 MB |
| 105.9 ms | 20.4 ms | 0.5 ms | 0.1 ms | 🥶 | 1024 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 1024 MB |

## Results for 2048 MB

| Measurement (2048 MB) | Time (ms) |
|-------------|------|
| Average warm start response time | 7.3 ms |
| Average cold start response time | 92.9 ms |
| Fastest warm response time | 6 ms |
| Slowest warm response time | 13 ms |
| Fastest cold response time  | 75 ms |
| Slowest cold response time | 182.9 ms |
  

| Response time | Initialization | Invocation | Overhead | Cold/ Warm Start | Memory Size |
|---------------|----------------|------------|----------|------------------|-------------|
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 95.9 ms | 25.3 ms | 0.4 ms | 0.3 ms | 🥶 | 2048 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 98.9 ms | 24.3 ms | 0.6 ms | 0.2 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 81 ms | 19.2 ms | 0.4 ms | 0.1 ms | 🥶 | 2048 MB |
| 98 ms | 25.6 ms | 0.5 ms | 0.2 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 2048 MB |
| 88 ms | 22.5 ms | 0.5 ms | 0.2 ms | 🥶 | 2048 MB |
| 82 ms | 21.4 ms | 0.4 ms | 0.1 ms | 🥶 | 2048 MB |
| 95 ms | 28.2 ms | 0.5 ms | 0.2 ms | 🥶 | 2048 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 104 ms | 29.8 ms | 0.5 ms | 0.3 ms | 🥶 | 2048 MB |
| 94 ms | 24.6 ms | 0.5 ms | 0.2 ms | 🥶 | 2048 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 91 ms | 25.3 ms | 0.4 ms | 0.1 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 88 ms | 22.3 ms | 0.6 ms | 0.1 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 94 ms | 20.8 ms | 0.5 ms | 0.2 ms | 🥶 | 2048 MB |
| 94 ms | 25.4 ms | 0.4 ms | 0.2 ms | 🥶 | 2048 MB |
| 88 ms | 20.8 ms | 0.6 ms | 0.2 ms | 🥶 | 2048 MB |
| 97 ms | 30.3 ms | 0.6 ms | 0.3 ms | 🥶 | 2048 MB |
| 98 ms | 18.1 ms | 0.4 ms | 0 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 92 ms | 24.9 ms | 0.5 ms | 0.2 ms | 🥶 | 2048 MB |
| 95.9 ms | 21.5 ms | 0.8 ms | 0.1 ms | 🥶 | 2048 MB |
| 118.9 ms | 21.5 ms | 0.5 ms | 0.2 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 148 ms | 17.2 ms | 0.6 ms | 0.4 ms | 🥶 | 2048 MB |
| 96.9 ms | 18 ms | 0.6 ms | 0.3 ms | 🥶 | 2048 MB |
| 105.9 ms | 26.3 ms | 0.6 ms | 0.2 ms | 🥶 | 2048 MB |
| 92 ms | 25.5 ms | 0.6 ms | 0.2 ms | 🥶 | 2048 MB |
| 100 ms | 20 ms | 0.5 ms | 0.3 ms | 🥶 | 2048 MB |
| 83.9 ms | 18.3 ms | 0.4 ms | 0.2 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 84 ms | 19.1 ms | 0.4 ms | 0.2 ms | 🥶 | 2048 MB |
| 95 ms | 17.9 ms | 0.4 ms | 0.3 ms | 🥶 | 2048 MB |
| 89.9 ms | 20.8 ms | 0.3 ms | 0.1 ms | 🥶 | 2048 MB |
| 6 ms |  | 0.2 ms | 0.3 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 93.9 ms | 22.2 ms | 0.5 ms | 0.2 ms | 🥶 | 2048 MB |
| 96 ms | 26.6 ms | 0.6 ms | 0.5 ms | 🥶 | 2048 MB |
| 99.9 ms | 23.9 ms | 0.7 ms | 0.2 ms | 🥶 | 2048 MB |
| 91 ms | 20.3 ms | 0.5 ms | 0.2 ms | 🥶 | 2048 MB |
| 8 ms |  | 0.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 102 ms | 17.9 ms | 0.4 ms | 0.1 ms | 🥶 | 2048 MB |
| 89.9 ms | 27.2 ms | 0.6 ms | 0.1 ms | 🥶 | 2048 MB |
| 8 ms |  | 0.4 ms | 0.3 ms | 🥵 | 2048 MB |
| 88.9 ms | 26.4 ms | 0.6 ms | 0.3 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 8.9 ms |  | 0.7 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 91 ms | 21.9 ms | 0.4 ms | 0.1 ms | 🥶 | 2048 MB |
| 98 ms | 20.5 ms | 0.5 ms | 0.1 ms | 🥶 | 2048 MB |
| 77.9 ms | 19.8 ms | 0.5 ms | 0 ms | 🥶 | 2048 MB |
| 111.9 ms | 27.1 ms | 0.8 ms | 0.1 ms | 🥶 | 2048 MB |
| 7 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 84 ms | 18 ms | 0.6 ms | 0.4 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 94 ms | 26.3 ms | 0.7 ms | 0.1 ms | 🥶 | 2048 MB |
| 97.9 ms | 19 ms | 0.4 ms | 0.3 ms | 🥶 | 2048 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 98.9 ms | 27 ms | 0.7 ms | 0.4 ms | 🥶 | 2048 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 93.9 ms | 23.6 ms | 0.7 ms | 0.2 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 90.9 ms | 21 ms | 0.7 ms | 0.2 ms | 🥶 | 2048 MB |
| 115 ms | 19.4 ms | 0.7 ms | 0.7 ms | 🥶 | 2048 MB |
| 98.9 ms | 28.6 ms | 0.6 ms | 0.3 ms | 🥶 | 2048 MB |
| 103.9 ms | 26.4 ms | 0.4 ms | 0 ms | 🥶 | 2048 MB |
| 101.9 ms | 23.1 ms | 0.5 ms | 0.3 ms | 🥶 | 2048 MB |
| 102.9 ms | 20.3 ms | 0.3 ms | 0.3 ms | 🥶 | 2048 MB |
| 97 ms | 31.3 ms | 0.7 ms | 0.6 ms | 🥶 | 2048 MB |
| 89.9 ms | 19.4 ms | 0.6 ms | 0 ms | 🥶 | 2048 MB |
| 100.9 ms | 23.8 ms | 0.5 ms | 0.3 ms | 🥶 | 2048 MB |
| 101.9 ms | 20.4 ms | 0.4 ms | 0.2 ms | 🥶 | 2048 MB |
| 11.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 88 ms | 22.4 ms | 0.5 ms | 0 ms | 🥶 | 2048 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 97.9 ms | 28.2 ms | 0.7 ms | 0.2 ms | 🥶 | 2048 MB |
| 90.9 ms | 25.7 ms | 0.5 ms | 0.4 ms | 🥶 | 2048 MB |
| 114 ms | 28.5 ms | 0.4 ms | 0.1 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 153 ms | 20.2 ms | 0.5 ms | 0.3 ms | 🥶 | 2048 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 98 ms | 21.5 ms | 0.4 ms | 0 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 85 ms | 25.9 ms | 0.5 ms | 0.1 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 95.9 ms | 19.8 ms | 0.6 ms | 0.1 ms | 🥶 | 2048 MB |
| 92.9 ms | 21 ms | 0.3 ms | 0 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 95.9 ms | 19.5 ms | 1 ms | 0.2 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 100 ms | 30.8 ms | 0.5 ms | 0.3 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 13 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 88.9 ms | 25 ms | 0.4 ms | 0.1 ms | 🥶 | 2048 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 94 ms | 25.3 ms | 0.6 ms | 0.2 ms | 🥶 | 2048 MB |
| 7.9 ms |  | 0.4 ms | 0 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 93 ms | 26.5 ms | 0.6 ms | 0.9 ms | 🥶 | 2048 MB |
| 78.9 ms | 19.5 ms | 0.5 ms | 0.1 ms | 🥶 | 2048 MB |
| 9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 105 ms | 25.5 ms | 0.6 ms | 0.4 ms | 🥶 | 2048 MB |
| 8 ms |  | 0.4 ms | 0 ms | 🥵 | 2048 MB |
| 182.9 ms | 18.6 ms | 0.7 ms | 0.5 ms | 🥶 | 2048 MB |
| 8 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 86.9 ms | 18.5 ms | 0.5 ms | 0.1 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 95.9 ms | 29.1 ms | 0.5 ms | 0.1 ms | 🥶 | 2048 MB |
| 106 ms | 28.2 ms | 0.4 ms | 0.3 ms | 🥶 | 2048 MB |
| 96 ms | 18 ms | 0.4 ms | 0 ms | 🥶 | 2048 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 2048 MB |
| 85.9 ms | 22.2 ms | 0.4 ms | 0.2 ms | 🥶 | 2048 MB |
| 95 ms | 28.3 ms | 0.4 ms | 0.2 ms | 🥶 | 2048 MB |
| 107 ms | 30.7 ms | 0.4 ms | 0.2 ms | 🥶 | 2048 MB |
| 95 ms | 20.7 ms | 0.6 ms | 0.1 ms | 🥶 | 2048 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 98.9 ms | 18.9 ms | 0.7 ms | 0.2 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 75 ms | 22.2 ms | 0.4 ms | 0.1 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 97.9 ms | 20.4 ms | 0.7 ms | 0.2 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 101.9 ms | 26.5 ms | 0.9 ms | 0.2 ms | 🥶 | 2048 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 111 ms | 17.9 ms | 0.5 ms | 0.2 ms | 🥶 | 2048 MB |
| 92.9 ms | 24.4 ms | 0.6 ms | 0.3 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 2048 MB |
| 98 ms | 16.9 ms | 0.5 ms | 0.1 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 98.9 ms | 27.2 ms | 0.4 ms | 0.1 ms | 🥶 | 2048 MB |
| 7.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 103 ms | 17.2 ms | 0.4 ms | 0.1 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 2048 MB |
| 13 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 95.9 ms | 19.4 ms | 0.6 ms | 0.1 ms | 🥶 | 2048 MB |
| 7.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 8 ms |  | 0.6 ms | 0.1 ms | 🥵 | 2048 MB |
| 101.9 ms | 27.5 ms | 0.6 ms | 0.6 ms | 🥶 | 2048 MB |
| 101 ms | 20.4 ms | 0.7 ms | 0.1 ms | 🥶 | 2048 MB |
| 104 ms | 26.3 ms | 0.6 ms | 0.3 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.3 ms | 🥵 | 2048 MB |
| 7.9 ms |  | 0.4 ms | 0.4 ms | 🥵 | 2048 MB |
| 88.9 ms | 24.1 ms | 0.5 ms | 0.4 ms | 🥶 | 2048 MB |
| 118 ms | 20.8 ms | 0.5 ms | 0.2 ms | 🥶 | 2048 MB |
| 88.9 ms | 29.8 ms | 0.5 ms | 0.2 ms | 🥶 | 2048 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 2048 MB |
| 87.9 ms | 17 ms | 0.4 ms | 0.1 ms | 🥶 | 2048 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 2048 MB |

## Results for 3072 MB

| Measurement (3072 MB) | Time (ms) |
|-------------|------|
| Average warm start response time | 6.7 ms |
| Average cold start response time | 91.8 ms |
| Fastest warm response time | 5.9 ms |
| Slowest warm response time | 15 ms |
| Fastest cold response time  | 76.9 ms |
| Slowest cold response time | 250.9 ms |
  

| Response time | Initialization | Invocation | Overhead | Cold/ Warm Start | Memory Size |
|---------------|----------------|------------|----------|------------------|-------------|
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 92 ms | 19.3 ms | 0.6 ms | 0.3 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 103 ms | 20.8 ms | 0.7 ms | 0.4 ms | 🥶 | 3072 MB |
| 92 ms | 17.8 ms | 0.4 ms | 0 ms | 🥶 | 3072 MB |
| 88 ms | 21.6 ms | 0.5 ms | 0.3 ms | 🥶 | 3072 MB |
| 114.9 ms | 19.7 ms | 0.6 ms | 0.2 ms | 🥶 | 3072 MB |
| 88.9 ms | 20.8 ms | 0.7 ms | 0.4 ms | 🥶 | 3072 MB |
| 118 ms | 17.8 ms | 0.5 ms | 0.3 ms | 🥶 | 3072 MB |
| 85 ms | 17.5 ms | 0.4 ms | 0.1 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 15 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 88 ms | 17.6 ms | 0.6 ms | 0.4 ms | 🥶 | 3072 MB |
| 105.9 ms | 18.8 ms | 0.3 ms | 0.1 ms | 🥶 | 3072 MB |
| 105 ms | 21.4 ms | 0.5 ms | 0.6 ms | 🥶 | 3072 MB |
| 85 ms | 22.3 ms | 0.6 ms | 0.3 ms | 🥶 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 110 ms | 17.8 ms | 0.7 ms | 0.3 ms | 🥶 | 3072 MB |
| 82.9 ms | 20.6 ms | 0.6 ms | 0.1 ms | 🥶 | 3072 MB |
| 96 ms | 18.1 ms | 0.6 ms | 0.3 ms | 🥶 | 3072 MB |
| 76.9 ms | 18.1 ms | 0.5 ms | 0.1 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 7 ms |  | 0.3 ms | 0.3 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 88.9 ms | 19 ms | 0.6 ms | 0.3 ms | 🥶 | 3072 MB |
| 6 ms |  | 0.5 ms | 0.2 ms | 🥵 | 3072 MB |
| 117 ms | 17.7 ms | 0.5 ms | 0.1 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 95.9 ms | 17.9 ms | 0.4 ms | 0.2 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 88 ms | 19.4 ms | 0.6 ms | 0.6 ms | 🥶 | 3072 MB |
| 83.9 ms | 21.5 ms | 0.5 ms | 0.2 ms | 🥶 | 3072 MB |
| 103 ms | 19.3 ms | 0.7 ms | 0.4 ms | 🥶 | 3072 MB |
| 89.9 ms | 21 ms | 0.7 ms | 0.4 ms | 🥶 | 3072 MB |
| 98.9 ms | 23.7 ms | 0.5 ms | 0.6 ms | 🥶 | 3072 MB |
| 88.9 ms | 18.3 ms | 0.5 ms | 0.1 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 88.9 ms | 19.7 ms | 0.8 ms | 0.2 ms | 🥶 | 3072 MB |
| 87.9 ms | 21.2 ms | 0.5 ms | 0.3 ms | 🥶 | 3072 MB |
| 129 ms | 19 ms | 0.7 ms | 0.3 ms | 🥶 | 3072 MB |
| 103 ms | 20.9 ms | 0.4 ms | 0.1 ms | 🥶 | 3072 MB |
| 88.9 ms | 22.1 ms | 0.5 ms | 0.4 ms | 🥶 | 3072 MB |
| 88.9 ms | 19.2 ms | 0.8 ms | 0.1 ms | 🥶 | 3072 MB |
| 101 ms | 19.2 ms | 0.5 ms | 0.3 ms | 🥶 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 105.9 ms | 21.4 ms | 0.6 ms | 0.5 ms | 🥶 | 3072 MB |
| 92.9 ms | 20 ms | 0.6 ms | 0.4 ms | 🥶 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 101 ms | 19.5 ms | 0.6 ms | 0.4 ms | 🥶 | 3072 MB |
| 88.9 ms | 22.4 ms | 0.5 ms | 0.5 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 87 ms | 19.4 ms | 0.8 ms | 0.4 ms | 🥶 | 3072 MB |
| 108.9 ms | 21.3 ms | 0.6 ms | 0.4 ms | 🥶 | 3072 MB |
| 98 ms | 19.7 ms | 0.7 ms | 0.2 ms | 🥶 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 92.9 ms | 21.4 ms | 0.8 ms | 0.4 ms | 🥶 | 3072 MB |
| 101 ms | 19.4 ms | 0.6 ms | 0.6 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 92.9 ms | 21 ms | 0.6 ms | 0.4 ms | 🥶 | 3072 MB |
| 85 ms | 18.4 ms | 0.6 ms | 0.4 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 100 ms | 18.4 ms | 0.4 ms | 0.1 ms | 🥶 | 3072 MB |
| 92 ms | 20.9 ms | 0.5 ms | 0.3 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 1.1 ms | 0.1 ms | 🥵 | 3072 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 80 ms | 19.6 ms | 0.4 ms | 0.1 ms | 🥶 | 3072 MB |
| 8 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 100 ms | 18.4 ms | 0.4 ms | 0.2 ms | 🥶 | 3072 MB |
| 101 ms | 17.4 ms | 0.4 ms | 0 ms | 🥶 | 3072 MB |
| 108.9 ms | 20.9 ms | 0.4 ms | 0.3 ms | 🥶 | 3072 MB |
| 9 ms |  | 0.9 ms | 0.1 ms | 🥵 | 3072 MB |
| 93.9 ms | 18.6 ms | 0.7 ms | 0.2 ms | 🥶 | 3072 MB |
| 111.9 ms | 18.3 ms | 0.4 ms | 0.1 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 102.9 ms | 20.1 ms | 0.6 ms | 0 ms | 🥶 | 3072 MB |
| 81.9 ms | 18.3 ms | 0.6 ms | 0.3 ms | 🥶 | 3072 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 84.9 ms | 17.3 ms | 0.4 ms | 0.1 ms | 🥶 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 119.9 ms | 17.7 ms | 0.5 ms | 0.3 ms | 🥶 | 3072 MB |
| 88.9 ms | 17.1 ms | 0.6 ms | 0 ms | 🥶 | 3072 MB |
| 105 ms | 18.3 ms | 0.5 ms | 0.2 ms | 🥶 | 3072 MB |
| 101.9 ms | 31.2 ms | 0.4 ms | 0.2 ms | 🥶 | 3072 MB |
| 6 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 79.9 ms | 19.9 ms | 0.8 ms | 0.4 ms | 🥶 | 3072 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 8 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 82 ms | 18 ms | 0.5 ms | 0.4 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 82.9 ms | 19.5 ms | 0.8 ms | 0.3 ms | 🥶 | 3072 MB |
| 125.9 ms | 17.5 ms | 0.5 ms | 0.1 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 106 ms | 20.5 ms | 0.4 ms | 0.3 ms | 🥶 | 3072 MB |
| 7 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 9.9 ms |  | 0.6 ms | 0.1 ms | 🥵 | 3072 MB |
| 85.9 ms | 17.6 ms | 0.4 ms | 0.2 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.5 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 10.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 97 ms | 18.3 ms | 0.5 ms | 0.3 ms | 🥶 | 3072 MB |
| 96.9 ms | 19.4 ms | 0.7 ms | 0.7 ms | 🥶 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 250.9 ms | 20.8 ms | 0.5 ms | 0.2 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.7 ms | 0.1 ms | 🥵 | 3072 MB |
| 96.9 ms | 22 ms | 0.5 ms | 0.2 ms | 🥶 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 116 ms | 19.5 ms | 0.6 ms | 0.2 ms | 🥶 | 3072 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 88.9 ms | 19.4 ms | 0.4 ms | 0.1 ms | 🥶 | 3072 MB |
| 108.9 ms | 20.3 ms | 0.6 ms | 0.3 ms | 🥶 | 3072 MB |
| 77 ms | 19.4 ms | 0.4 ms | 0.3 ms | 🥶 | 3072 MB |
| 142 ms | 19.6 ms | 0.4 ms | 0.6 ms | 🥶 | 3072 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 114 ms | 19.5 ms | 0.8 ms | 0.2 ms | 🥶 | 3072 MB |
| 118.9 ms | 22.6 ms | 0.6 ms | 1 ms | 🥶 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 82 ms | 17.7 ms | 0.6 ms | 0.6 ms | 🥶 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.2 ms | 🥵 | 3072 MB |
| 102.9 ms | 19.7 ms | 0.6 ms | 0.2 ms | 🥶 | 3072 MB |
| 77 ms | 18.5 ms | 0.8 ms | 0.5 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 108.9 ms | 21 ms | 15.8 ms | 0.2 ms | 🥶 | 3072 MB |
| 97 ms | 20 ms | 0.6 ms | 0.4 ms | 🥶 | 3072 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 95 ms | 17.8 ms | 0.6 ms | 0.3 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 105.9 ms | 17.9 ms | 0.7 ms | 0.2 ms | 🥶 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 90 ms | 19.8 ms | 0.5 ms | 0 ms | 🥶 | 3072 MB |
| 95.9 ms | 19.2 ms | 0.5 ms | 0.5 ms | 🥶 | 3072 MB |
| 92 ms | 20.3 ms | 0.5 ms | 0.1 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 88.9 ms | 22.3 ms | 0.5 ms | 0.2 ms | 🥶 | 3072 MB |
| 101.9 ms | 20 ms | 0.4 ms | 0 ms | 🥶 | 3072 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 96.9 ms | 19.3 ms | 0.4 ms | 0.1 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 92.9 ms | 18 ms | 0.4 ms | 0.1 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 3072 MB |
| 6.9 ms |  | 0.4 ms | 0 ms | 🥵 | 3072 MB |
| 100.9 ms | 18.4 ms | 0.5 ms | 0.3 ms | 🥶 | 3072 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 85 ms | 19.2 ms | 0.5 ms | 0 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.5 ms | 0 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 106.9 ms | 22.9 ms | 0.5 ms | 0.1 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 86.9 ms | 17.1 ms | 0.6 ms | 0.3 ms | 🥶 | 3072 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 3072 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 3072 MB |
| 101.9 ms | 20.6 ms | 0.5 ms | 0.3 ms | 🥶 | 3072 MB |
| 103.9 ms | 17.4 ms | 0.5 ms | 0.2 ms | 🥶 | 3072 MB |
| 82.9 ms | 18.8 ms | 0.7 ms | 0.3 ms | 🥶 | 3072 MB |
| 7 ms |  | 0.4 ms | 0 ms | 🥵 | 3072 MB |

## Results for 4096 MB

| Measurement (4096 MB) | Time (ms) |
|-------------|------|
| Average warm start response time | 6.8 ms |
| Average cold start response time | 89.2 ms |
| Fastest warm response time | 5.9 ms |
| Slowest warm response time | 23.9 ms |
| Fastest cold response time  | 79.9 ms |
| Slowest cold response time | 257 ms |
  

| Response time | Initialization | Invocation | Overhead | Cold/ Warm Start | Memory Size |
|---------------|----------------|------------|----------|------------------|-------------|
| 88.9 ms | 18.6 ms | 0.5 ms | 0.1 ms | 🥶 | 4096 MB |
| 87 ms | 20.1 ms | 1 ms | 0.5 ms | 🥶 | 4096 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 83.9 ms | 19.4 ms | 0.6 ms | 0.3 ms | 🥶 | 4096 MB |
| 257 ms | 17.6 ms | 0.4 ms | 0.2 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.7 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 93 ms | 19.6 ms | 0.7 ms | 0.4 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 104 ms | 20.4 ms | 0.6 ms | 0.5 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 85.9 ms | 17.4 ms | 0.7 ms | 0.4 ms | 🥶 | 4096 MB |
| 92.9 ms | 19.3 ms | 0.6 ms | 0.4 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 80 ms | 17.6 ms | 0.4 ms | 0.2 ms | 🥶 | 4096 MB |
| 95.9 ms | 19.5 ms | 0.6 ms | 0.3 ms | 🥶 | 4096 MB |
| 94 ms | 25.7 ms | 0.6 ms | 0.4 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 98 ms | 20.4 ms | 0.6 ms | 0.4 ms | 🥶 | 4096 MB |
| 80 ms | 17.9 ms | 0.4 ms | 0.1 ms | 🥶 | 4096 MB |
| 101.9 ms | 20.7 ms | 0.5 ms | 0.4 ms | 🥶 | 4096 MB |
| 101.9 ms | 23.5 ms | 0.9 ms | 0.5 ms | 🥶 | 4096 MB |
| 10.9 ms |  | 0.3 ms | 3.1 ms | 🥵 | 4096 MB |
| 88 ms | 19.9 ms | 0.7 ms | 0.2 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.5 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 88.9 ms | 19.7 ms | 0.6 ms | 0.2 ms | 🥶 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 93 ms | 18.2 ms | 0.4 ms | 0.2 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 111 ms | 17.9 ms | 0.6 ms | 0.2 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 91 ms | 19.1 ms | 0.6 ms | 0.1 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 94 ms | 19.9 ms | 0.4 ms | 0 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.5 ms | 0.2 ms | 🥵 | 4096 MB |
| 92 ms | 18.9 ms | 0.5 ms | 0.1 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.5 ms | 0.2 ms | 🥵 | 4096 MB |
| 97.9 ms | 19.9 ms | 0.5 ms | 0.1 ms | 🥶 | 4096 MB |
| 7.9 ms |  | 0.5 ms | 0 ms | 🥵 | 4096 MB |
| 92.9 ms | 18.5 ms | 0.5 ms | 0.3 ms | 🥶 | 4096 MB |
| 104 ms | 19.8 ms | 0.6 ms | 0.3 ms | 🥶 | 4096 MB |
| 84 ms | 19.6 ms | 0.6 ms | 0.5 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 80 ms | 17.3 ms | 0.3 ms | 0.1 ms | 🥶 | 4096 MB |
| 98.9 ms | 19.5 ms | 0.6 ms | 0.3 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 115 ms | 19.3 ms | 0.4 ms | 0.3 ms | 🥶 | 4096 MB |
| 118 ms | 18.1 ms | 0.5 ms | 0.3 ms | 🥶 | 4096 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 103.9 ms | 18.7 ms | 0.4 ms | 0.2 ms | 🥶 | 4096 MB |
| 137 ms | 19.8 ms | 0.7 ms | 0.2 ms | 🥶 | 4096 MB |
| 88.9 ms | 17 ms | 0.5 ms | 0.3 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 109.9 ms | 19.3 ms | 0.9 ms | 0.5 ms | 🥶 | 4096 MB |
| 122.9 ms | 17.7 ms | 0.4 ms | 0.2 ms | 🥶 | 4096 MB |
| 91 ms | 20.6 ms | 0.5 ms | 0.2 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.4 ms | 0 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 134.9 ms | 19.7 ms | 0.4 ms | 0.2 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 114 ms | 19.9 ms | 0.6 ms | 0.3 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 101.9 ms | 19.8 ms | 0.7 ms | 0 ms | 🥶 | 4096 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 84 ms | 18.1 ms | 0.6 ms | 0 ms | 🥶 | 4096 MB |
| 13.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 131.9 ms | 16.7 ms | 0.6 ms | 0.2 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 124 ms | 29.8 ms | 0.5 ms | 1.1 ms | 🥶 | 4096 MB |
| 79.9 ms | 17.9 ms | 0.4 ms | 0.3 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 98 ms | 17.7 ms | 0.6 ms | 0.3 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 96.9 ms | 19.4 ms | 0.4 ms | 0.1 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 88 ms | 20.6 ms | 0.4 ms | 0 ms | 🥶 | 4096 MB |
| 92.9 ms | 20.6 ms | 0.9 ms | 0.4 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 105.9 ms | 19.4 ms | 0.7 ms | 0.4 ms | 🥶 | 4096 MB |
| 19.9 ms |  | 0.8 ms | 0.3 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 100 ms | 19.9 ms | 0.9 ms | 0 ms | 🥶 | 4096 MB |
| 115 ms | 28.9 ms | 0.4 ms | 0.1 ms | 🥶 | 4096 MB |
| 95 ms | 19.6 ms | 0.6 ms | 0.5 ms | 🥶 | 4096 MB |
| 86 ms | 18.3 ms | 0.5 ms | 0.1 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 103.9 ms | 27.6 ms | 0.4 ms | 0.4 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 8 ms |  | 0.7 ms | 0.1 ms | 🥵 | 4096 MB |
| 91 ms | 19.4 ms | 0.5 ms | 0.5 ms | 🥶 | 4096 MB |
| 5.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 110.9 ms | 19.6 ms | 0.7 ms | 0.2 ms | 🥶 | 4096 MB |
| 87 ms | 19.1 ms | 0.4 ms | 0.2 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.6 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 107.9 ms | 24.9 ms | 0.6 ms | 0 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 161 ms | 19.1 ms | 0.6 ms | 0.4 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 105.9 ms | 17.5 ms | 0.6 ms | 0.2 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.2 ms | 🥵 | 4096 MB |
| 92 ms | 20.7 ms | 0.6 ms | 0.3 ms | 🥶 | 4096 MB |
| 7.9 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 92 ms | 17.9 ms | 0.5 ms | 0.3 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.7 ms | 0.1 ms | 🥵 | 4096 MB |
| 89 ms | 20.5 ms | 0.4 ms | 0.1 ms | 🥶 | 4096 MB |
| 82.9 ms | 17.5 ms | 0.4 ms | 0.3 ms | 🥶 | 4096 MB |
| 88 ms | 21.5 ms | 0.4 ms | 0.3 ms | 🥶 | 4096 MB |
| 93.9 ms | 21.2 ms | 0.4 ms | 0.3 ms | 🥶 | 4096 MB |
| 108 ms | 19.9 ms | 0.7 ms | 0.3 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 23.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 104 ms | 20.5 ms | 0.5 ms | 0 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 85 ms | 19.7 ms | 0.7 ms | 0.3 ms | 🥶 | 4096 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 83.9 ms | 20.1 ms | 0.4 ms | 0.2 ms | 🥶 | 4096 MB |
| 98.9 ms | 20.5 ms | 0.6 ms | 0.2 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 129.9 ms | 18.2 ms | 0.6 ms | 0.1 ms | 🥶 | 4096 MB |
| 101.9 ms | 20.1 ms | 0.4 ms | 0 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 85.9 ms | 19.6 ms | 0.6 ms | 0.2 ms | 🥶 | 4096 MB |
| 83.9 ms | 19.3 ms | 0.8 ms | 1 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 91 ms | 19.8 ms | 0.5 ms | 0.7 ms | 🥶 | 4096 MB |
| 92.9 ms | 17.2 ms | 0.6 ms | 0.5 ms | 🥶 | 4096 MB |
| 106.9 ms | 19.7 ms | 0.6 ms | 0 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 138 ms | 18.5 ms | 0.4 ms | 0.1 ms | 🥶 | 4096 MB |
| 97 ms | 17.9 ms | 0.5 ms | 0.2 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 111.9 ms | 21 ms | 0.7 ms | 0.6 ms | 🥶 | 4096 MB |
| 85.9 ms | 17.9 ms | 0.4 ms | 0.3 ms | 🥶 | 4096 MB |
| 99.9 ms | 21.9 ms | 0.6 ms | 0 ms | 🥶 | 4096 MB |
| 101 ms | 17.8 ms | 0.5 ms | 0.2 ms | 🥶 | 4096 MB |
| 108 ms | 19.3 ms | 0.5 ms | 0.3 ms | 🥶 | 4096 MB |
| 108.9 ms | 19.4 ms | 0.8 ms | 0.4 ms | 🥶 | 4096 MB |
| 81 ms | 18.2 ms | 0.6 ms | 0.5 ms | 🥶 | 4096 MB |
| 125 ms | 17.4 ms | 0.5 ms | 0.5 ms | 🥶 | 4096 MB |
| 97.9 ms | 21.1 ms | 0.6 ms | 0.5 ms | 🥶 | 4096 MB |
| 91 ms | 22.6 ms | 0.5 ms | 0.2 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0 ms | 🥵 | 4096 MB |
| 6 ms |  | 0.3 ms | 0.2 ms | 🥵 | 4096 MB |
| 106.9 ms | 18.2 ms | 0.6 ms | 0.4 ms | 🥶 | 4096 MB |
| 92 ms | 17.7 ms | 0.6 ms | 0.3 ms | 🥶 | 4096 MB |
| 98.9 ms | 19.9 ms | 0.6 ms | 0.4 ms | 🥶 | 4096 MB |
| 7.9 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 5.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |
| 89.9 ms | 19.8 ms | 0.7 ms | 0.2 ms | 🥶 | 4096 MB |
| 92.9 ms | 19.9 ms | 0.6 ms | 0.3 ms | 🥶 | 4096 MB |
| 6 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 7 ms |  | 0.4 ms | 0.1 ms | 🥵 | 4096 MB |
| 85 ms | 18.1 ms | 0.4 ms | 0.1 ms | 🥶 | 4096 MB |
| 6.9 ms |  | 0.3 ms | 0.1 ms | 🥵 | 4096 MB |


## XRay Example of a Cold Start

<img width="1476" alt="Screenshot 2020-10-07 at 23 01 40" src="https://user-images.githubusercontent.com/1189998/95387505-178a1d00-08f1-11eb-83a7-7bc32eee48e2.png">

## XRay Example of a Warm Start

<img width="1479" alt="Screenshot 2020-10-07 at 23 01 23" src="https://user-images.githubusercontent.com/1189998/95387509-1953e080-08f1-11eb-8d46-ac25efa235e4.png">
