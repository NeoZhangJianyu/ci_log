# [](https://github.com//master) CI for iGPU-13400 by SYCL Backend

## Summary

Figure

![Performance](./perf.png)
## Detail

**GGUF res** is verified by script ./example/sycl/run.sh with llama2-7b-Q4 for correction

**Perf** is the performance data by script ./example/sycl/run.sh with llama2-7b-Q4

|Commit Info|UT PassRate|Fault Detail|<div style="width:100px">GGUF res</div>|Perf(token/s)|Warn/Err|
|-|-|-|-|-|-|
|[9422c5e34bbd302493b77a8f6d546154a1f4fe82](https://github.com//commit/9422c5e34bbd302493b77a8f6d546154a1f4fe82)<br>2024-06-02 19:13:54<br>[SYCL] Update rpc-server.cpp to include <br>SYCL backend<br>nickp27  Log: [log](./log/9422c5e34bbd302493b77a8f6d546154a1f4fe82)|95.0%|NA|('ok', 'pass', 0)|3.03|453/0|
