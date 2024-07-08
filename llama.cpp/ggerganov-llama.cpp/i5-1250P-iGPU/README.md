# [ggerganov/llama.cpp](https://github.com/ggerganov/llama.cpp) CI for i5-1250P-iGPU by SYCL Backend

## Summary

Figure

![Performance](./perf.png)
## Detail

**GGUF res** is verified by script ./example/sycl/run.sh with llama2-7b-Q4 for correction

**Perf** is the performance data by script ./example/sycl/run.sh with llama2-7b-Q4

|Commit Info|UT PassRate|Fault Detail|<div style="width:100px">GGUF res</div>|Perf|Warn/Err|
|-|-|-|-|-|-|
|[3f2d538b817112ad8429341c7e8657dcd660f4d3](https://github.com/ggerganov/llama.cpp/commit/3f2d538b817112ad8429341c7e8657dcd660f4d3)<br>2024-07-08 13:51:31<br>scripts : fix sync for sycl<br>Georgi Gerganov  Log: [log](./log/3f2d538b817112ad8429341c7e8657dcd660f4d3)|95.0%|NA|('ok', 'pass')|4.94|705/0|
|[be20e7f49d9e5c6d9e8d9b4871eeba3df7a1639d](https://github.com/ggerganov/llama.cpp/commit/be20e7f49d9e5c6d9e8d9b4871eeba3df7a1639d)<br>2024-07-05 18:08:32<br>Reorganize documentation pages<br>Xuan Son Nguyen  Log: [log](./log/be20e7f49d9e5c6d9e8d9b4871eeba3df7a1639d)|95.0%|NA|('err', 'diff in line 0:<br>exp=Step 1: Get to know the basics of web design<br>out=main: error: unable to load model')|NA|705/0|
|[1f3e1b66e21310ed78b964f72f19766549633f0e](https://github.com/ggerganov/llama.cpp/commit/1f3e1b66e21310ed78b964f72f19766549633f0e)<br>2024-07-05 13:23:25<br>Enabled more data types for oneMKL gemm_batch<br>Ouadie EL FAROUKI  Log: [log](./log/1f3e1b66e21310ed78b964f72f19766549633f0e)|95.0%|NA|('err', 'diff in line 0:<br>exp=Step 1: Get to know the basics of web design<br>out=main: error: unable to load model')|NA|705/0|
