# [arthw/llama.cpp](https://github.com/arthw/llama.cpp) CI for arc770 by SYCL Backend

## Summary

Figure

![Performance](ci_log/llama.cpp/arthw-llama.cpp/arc770/perf.png)
## Detail

**GGUF res** is verified by script ./example/sycl/run.sh with llama2-7b-Q4 for correction

**Perf** is the performance data by script ./example/sycl/run.sh with llama2-7b-Q4

|Commit ID|UT PassRate|Fault Detail|<div style="width:100px">GGUF res</div>|Perf|Warn/Err|Date|Title|Author|Log|
|-|-|-|-|-|-|-|-|-|-|
|[fdef7d606ef4864ceb5f51a576c0ecddec2cce2a](https://github.com/arthw/llama.cpp/commit/fdef7d606ef4864ceb5f51a576c0ecddec2cce2a)|91.0%|NA|('ok', 'pass')|40.12|0/0|2024-07-04 11:55:23|replace get_work_group_size|Neo Zhang|[log](./log/fdef7d606ef4864ceb5f51a576c0ecddec2cce2a)|
|[249347995825713ad03b9cda3a036851f2e95033](https://github.com/arthw/llama.cpp/commit/249347995825713ad03b9cda3a036851f2e95033)|91.0%|NA|('ok', 'pass')|40.05|0/0|2024-07-04 08:28:58|skip UT for BF16|Neo Zhang|[log](./log/249347995825713ad03b9cda3a036851f2e95033)|
|[51be86243892833c9779ae903d5b54241ec2507a](https://github.com/arthw/llama.cpp/commit/51be86243892833c9779ae903d5b54241ec2507a)|91.0%|NA|('ok', 'pass')|40.06|577/0|2024-07-03 02:55:34|Dequant improvements rebase|AidanBeltonS|[log](./log/51be86243892833c9779ae903d5b54241ec2507a)|
|[044995e2d1fbc21ca275be66a9cb580034124502](https://github.com/arthw/llama.cpp/commit/044995e2d1fbc21ca275be66a9cb580034124502)|91.0%|NA|('ok', 'pass')|40.06|571/0|2024-07-02 12:18:10|Removes multiple newlines at the end of files that is breaking the editorconfig step of CI.|Clint Herron|[log](./log/044995e2d1fbc21ca275be66a9cb580034124502)|
|[9c593619f363fda422375b386674d558fa48d437](https://github.com/arthw/llama.cpp/commit/9c593619f363fda422375b386674d558fa48d437)|91.0%|NA|('ok', 'pass')|40.05|571/0|2024-07-03 11:20:54|fix multiple gpu, add device choose mode, update the guide for usages|Neo Zhang|[log](./log/9c593619f363fda422375b386674d558fa48d437)|
|[de2763118fd5b6ea89702cc9981349e0556b0c3d](https://github.com/arthw/llama.cpp/commit/de2763118fd5b6ea89702cc9981349e0556b0c3d)|Build Err|NA|('err', 'diff in line 0:<br>exp=Step 1: Get to know the basics of web design<br>out=./examples/sycl/run-llama2.sh: line 29: ./build/bin/llama-cli: No such file or d')|NA|13/6|2024-06-19 22:54:15|fix to support multiple GPUs, fix set single device, unify id/device_id/device_index|Jianyu Zhang|[log](./log/de2763118fd5b6ea89702cc9981349e0556b0c3d)|
|[d08c20eddedb24515a3212e2de66bdff41a26b8c](https://github.com/arthw/llama.cpp/commit/d08c20eddedb24515a3212e2de66bdff41a26b8c)|91.0%|NA|('err', 'diff in line 0:<br>exp=Step 1: Get to know the basics of web design<br>out=Step 1: The original copy text needed should describe the products/ services.')|43.39|599/0|2024-07-02 02:16:00|[SYCL] Fix the sub group size of Intel|luoyu-intel|[log](./log/d08c20eddedb24515a3212e2de66bdff41a26b8c)|
|[cb5fad4c6c2cbef92e9b8b63449e1cb7664e4846](https://github.com/arthw/llama.cpp/commit/cb5fad4c6c2cbef92e9b8b63449e1cb7664e4846)|91.0%|NA|('ok', 'pass')|40.09|543/0|2024-07-01 20:39:06|CUDA: refactor and optimize IQ MMVQ|Johannes Gäßler|[log](./log/cb5fad4c6c2cbef92e9b8b63449e1cb7664e4846)|
|[197fe6c1d7bec6718ce901f0141b2725240f298c](https://github.com/arthw/llama.cpp/commit/197fe6c1d7bec6718ce901f0141b2725240f298c)|91.0%|NA|('ok', 'pass')|40.08|543/0|2024-07-01 19:39:06|[SYCL] Update SYCL-Rope op and Refactor|zhentaoyu|[log](./log/197fe6c1d7bec6718ce901f0141b2725240f298c)|
|[f3f65429c44bb195a9195bfdc19a30a79709db7b](https://github.com/arthw/llama.cpp/commit/f3f65429c44bb195a9195bfdc19a30a79709db7b)|95.0%|NA|('ok', 'pass')|40.09|533/0|2024-06-26 18:33:02|llama : reorganize source code + improve CMake|Georgi Gerganov|[log](./log/f3f65429c44bb195a9195bfdc19a30a79709db7b)|
|[083bacce14c1aaf9976aa40e8266cdc25ac749d3](https://github.com/arthw/llama.cpp/commit/083bacce14c1aaf9976aa40e8266cdc25ac749d3)|91.0%|NA|('ok', 'pass')|40.17|554/0|2024-06-25 10:19:20|[SYCL] Re-enabled mul_mat_batched_sycl|Meng, Hengyu|[log](./log/083bacce14c1aaf9976aa40e8266cdc25ac749d3)|
|[de391e4c803383bbea054b6edd016e78c024a74d](https://github.com/arthw/llama.cpp/commit/de391e4c803383bbea054b6edd016e78c024a74d)|91.0%|NA|('ok', 'pass')|40.09|554/0|2024-06-20 13:19:05|[SYCL] Fix windows build and inference|luoyu-intel|[log](./log/de391e4c803383bbea054b6edd016e78c024a74d)|
|[623494a478134432fd2d7ee40135770a3340674f](https://github.com/arthw/llama.cpp/commit/623494a478134432fd2d7ee40135770a3340674f)|91.0%|NA|('ok', 'pass')|40.09|542/0|2024-06-19 09:11:51|[SYCL] refactor|Meng, Hengyu|[log](./log/623494a478134432fd2d7ee40135770a3340674f)|
|[df68d4fa5dc929217d3e64d673e099d7a417b206](https://github.com/arthw/llama.cpp/commit/df68d4fa5dc929217d3e64d673e099d7a417b206)|91.0%|NA|('ok', 'pass')|40.08|480/0|2024-06-17 11:17:07|[SYCL] Update README-sycl.md for Chapter "Recommended release" and "News"|Neo Zhang|[log](./log/df68d4fa5dc929217d3e64d673e099d7a417b206)|
|[7b2f4a7d193ef2475259bbe7656fcccfab4b1217](https://github.com/arthw/llama.cpp/commit/7b2f4a7d193ef2475259bbe7656fcccfab4b1217)|91.0%|NA|('ok', 'pass')|40.09|480/0|2024-06-15 14:05:10|[SYCL] remove global variables|Meng, Hengyu|[log](./log/7b2f4a7d193ef2475259bbe7656fcccfab4b1217)|
|[f578b86b2123d0f92afbaa98a031df4d4464e582](https://github.com/arthw/llama.cpp/commit/f578b86b2123d0f92afbaa98a031df4d4464e582)|91.0%|NA|('err', 'diff in line 6:<br>exp=Step 7: Make the site responsive<br>out=Step 7: Make,orsz onседа atir Byett, 1./doV’3ar/F(, knowledgejyl onop5all')|29.65|493/0|2024-06-13 03:11:35|move BLAS to a separate backend|slaren|[log](./log/f578b86b2123d0f92afbaa98a031df4d4464e582)|
|[1c641e6aac5c18b964e7b32d9dbbb4bf5301d0d7](https://github.com/arthw/llama.cpp/commit/1c641e6aac5c18b964e7b32d9dbbb4bf5301d0d7)|91.0%|NA|('err', 'diff in line 6:<br>exp=Step 7: Make the site responsive<br>out=Step 7: Make,orsz onседа atir Byett, 1./doV’3ar/F(, knowledgejyl onop5all')|29.73|493/0|2024-06-13 00:41:52|`build`: rename main → llama-cli, server → llama-server, llava-cli → llama-llava-cli, etc...|Olivier Chafik|[log](./log/1c641e6aac5c18b964e7b32d9dbbb4bf5301d0d7)|
|[a9cae48003dfc4fe95b8f5c81682fc6e63425235](https://github.com/arthw/llama.cpp/commit/a9cae48003dfc4fe95b8f5c81682fc6e63425235)|91.0%|NA|('err', 'diff in line 6:<br>exp=Step 7: Make the site responsive<br>out=Step 7: Make,orsz onседа atir Byett, 1./doV’3ar/F(, knowledgejyl onop5all')|29.69|493/0|2024-06-12 16:00:22|tests : add non-cont unary tests|Georgi Gerganov|[log](./log/a9cae48003dfc4fe95b8f5c81682fc6e63425235)|
|[af4ae502ddaeb03cd5861273ca2e9a5ae4551db7](https://github.com/arthw/llama.cpp/commit/af4ae502ddaeb03cd5861273ca2e9a5ae4551db7)|91.0%|NA|('err', 'diff in line 6:<br>exp=Step 7: Make the site responsive<br>out=Step 7: Make,orsz onседа atir Byett, 1./doV’3ar/F(, knowledgejyl onop5all')|29.7|493/0|2024-06-10 02:21:31|use the correct SYCL context for host USM allocations|Ben Ashbaugh|[log](./log/af4ae502ddaeb03cd5861273ca2e9a5ae4551db7)|
|[d5c938cd7716b9a2ace49a43a469dfbffcff4d28](https://github.com/arthw/llama.cpp/commit/d5c938cd7716b9a2ace49a43a469dfbffcff4d28)|91.0%|NA|('err', 'diff in line 6:<br>exp=Step 7: Make the site responsive<br>out=Step 7: Make,orsz onседа atir Byett, 1./doV’3ar/F(, knowledgejyl onop5all')|29.64|493/0|2024-06-07 14:28:26|[SYCL] fix softmax r2r result wrong issue|pengxin99|[log](./log/d5c938cd7716b9a2ace49a43a469dfbffcff4d28)|
|[2b3389677a833cee0880226533a1768b1a9508d2](https://github.com/arthw/llama.cpp/commit/2b3389677a833cee0880226533a1768b1a9508d2)|91.0%|NA|('err', 'diff in line 6:<br>exp=Step 7: Make the site responsive<br>out=Step 7: Make,orsz onседа atir Byett, 1./doV’3ar/F(, knowledgejyl onop5all')|29.73|493/0|2024-06-05 11:29:20|ggml : refactor rope norm/neox|Georgi Gerganov|[log](./log/2b3389677a833cee0880226533a1768b1a9508d2)|
|[554c247caffed64465f372661f2826640cb10430](https://github.com/arthw/llama.cpp/commit/554c247caffed64465f372661f2826640cb10430)|91.0%|NA|('err', 'diff in line 6:<br>exp=Step 7: Make the site responsive<br>out=Step 7: Make report (v has have has got (pay( Big and (c gu in to The(Col U2 R,2')|29.97|487/0|2024-06-04 21:23:20|ggml : remove OpenCL|Georgi Gerganov|[log](./log/554c247caffed64465f372661f2826640cb10430)|