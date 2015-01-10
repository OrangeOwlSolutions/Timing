# Timing
Timing classes for CPU and GPU / Windows and Linux

Usage - CPU:
```
  TimingCPU timerCPU;
  timerCPU.StartCounter();
  [CPU instructions to time]
  printf("Timing = %f\n", timerCPU.GetCounter());
```

Usage - GPU:
```
  TimingGPU timerGPU;
  timerGPU.StartCounter();
  [GPU instructions to time]
  printf("Timing = %f\n", timerGPU.GetCounter());
```
