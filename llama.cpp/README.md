# llama.cpp CI for SYCL Backend

|Commit ID|UT PassRate|Warn|Date|Title|Author|Log|
|-|-|-|-|-|-|-|
| 5106ef48|95.0%|-1|2024-03-28 16:01:47|[SYCL] Revisited & updated SYCL build documentation|Ouadie EL FAROUKI <ouadie.elfarouki@codeplay.com>|
| 25f4a613|95.0%|-1|2024-03-28 08:55:24|[SYCL] fix set main gpu crash|Neo Zhang Jianyu <jianyu.zhang@intel.com>|
| e82f9e2b|95.0%|-1|2024-03-27 08:16:40|[SYCL] Fix batched impl for NVidia GPU|AidanBeltonS <87009434+AidanBeltonS@users.noreply.github.com>|
| a4f569e8|95.0%|-1|2024-03-27 09:47:06|[SYCL] fix no file in win rel|Neo Zhang Jianyu <jianyu.zhang@intel.com>|
| 557410b8|95.0%|-1|2024-03-26 10:46:41|llama : greatly reduce output buffer memory usage|compilade <113953597+compilade@users.noreply.github.com>|
| 95ad616c|95.0%|-1|2024-03-25 15:52:41|[SYCL] fix SYCL backend build on windows is break by LOG|Neo Zhang Jianyu <jianyu.zhang@intel.com>|
| ddf65685|95.0%|-1|2024-03-24 12:04:25|[SYCL] offload op|Meng, Hengyu <hengyu.meng@intel.com>|
| 59c17f02|95.0%|-1|2024-03-22 15:19:37|add blog link|Neo Zhang Jianyu <jianyu.zhang@intel.com>|
| f372c49c|95.0%|-1|2024-03-21 11:52:35|Corrected typo to wrong file|semidark <me@semidark.net>|
| c5b8595e|95.0%|-1|2024-03-21 06:10:52|Add nvidia and amd backends|AidanBeltonS <87009434+AidanBeltonS@users.noreply.github.com>|
| 6c0b2877|95.0%|-1|2024-03-20 11:21:41|update readme sycl for new update|Neo Zhang Jianyu <jianyu.zhang@intel.com>|
| d26e8b66|95.0%|-1|2024-03-20 08:28:49|increase igpu cluster limit|Abhilash Majumder <30946547+abhilash1910@users.noreply.github.com>|
| 2bf8d0f7|95.0%|-1|2024-03-18 11:03:04|backend : offload large batches to GPU|slaren <slarengh@gmail.com>|
| 46acb367|95.0%|-1|2024-03-15 18:53:53|fix set main gpu error|Neo Zhang Jianyu <jianyu.zhang@intel.com>|
| 753e36f6|19.0%|-1|2024-03-15 09:26:20|[SYCL] Fix non-intel device selection|AidanBeltonS <87009434+AidanBeltonS@users.noreply.github.com>|
| f30ea47a|19.0%|-1|2024-03-13 18:54:21|llama : add pipeline parallelism support|slaren <slarengh@gmail.com>|
| b3d97860|19.0%|-1|2024-03-13 13:17:54|Update get version|AidanBeltonS <87009434+AidanBeltonS@users.noreply.github.com>|
| 8030da7a|19.0%|-1|2024-03-12 14:27:20|ggml : reuse quantum structs across backends|Georgi Gerganov <ggerganov@gmail.com>|
| 48358b2e|19.0%|-1|2024-03-12 11:15:05|sycl : update IQ1_S kernels|Georgi Gerganov <ggerganov@gmail.com>|
| ef3ced26|19.0%|-1|2024-03-11 10:27:56|[SYCL] Add q3_s and q1_s|Abhilash Majumder <30946547+abhilash1910@users.noreply.github.com>|
| 3814a073|19.0%|-1|2024-03-11 01:13:57|[SYCL] Add support for SYCL Nvidia target|AidanBeltonS <87009434+AidanBeltonS@users.noreply.github.com>|
| 8a3012a4|19.0%|-1|2024-03-09 12:47:57|ggml : add ggml-common.h to deduplicate shared code|Georgi Gerganov <ggerganov@gmail.com>|
| 89fb735f|19.0%|-1|2024-03-07 19:14:49|Revert "[SYCL] fix error when set main gpu to non-zero|Neo Zhang Jianyu <jianyu.zhang@intel.com>|
| ceca1aef|19.0%|-1|2024-03-07 16:34:31|[SYCL] fix error when set main gpu to non-zero|Neo Zhang Jianyu <jianyu.zhang@intel.com>|
| 8ced9f7e|19.0%|-1|2024-03-06 12:08:32|add wait|Neo Zhang Jianyu <jianyu.zhang@intel.com>|
| 21b08674|19.0%|-1|2024-03-05 16:08:35|[SYCL] fix mul_mat fault in CI/unit-test|Neo Zhang Jianyu <jianyu.zhang@intel.com>|
| 9fa26273|19.0%|-1|2024-03-04 10:05:42|ggml : introduce ggml_status|Michael Podvitskiy <podvitskiymichael@gmail.com>|
| 71564139|19.0%|-1|2024-03-02 19:49:30|Support multiple GPUs|Neo Zhang Jianyu <jianyu.zhang@intel.com>|
| 38d15216|95.0%|-1|2024-03-01 07:36:47|[SYCL] Use batched mul_mat pathway|AidanBeltonS <87009434+AidanBeltonS@users.noreply.github.com>|
| 5f706718|95.0%|-1|2024-02-24 11:27:36|Introduce backend GUIDs|UEXTM.com <84163508+uextm@users.noreply.github.com>|
| e849078c|95.0%|-1|2024-02-26 14:02:11|[SYCL] Add support for soft_max ALiBi|AidanBeltonS <87009434+AidanBeltonS@users.noreply.github.com>|
| ab336a9d|95.0%|-1|2024-02-25 12:09:09|code : normalize enum names|Georgi Gerganov <ggerganov@gmail.com>|
| 88c46cbd|95.0%|-1|2024-02-21 17:52:06|[SYCL] conext add name|Meng, Hengyu <hengyu.meng@intel.com>|
| b9111bd2|95.0%|-1|2024-02-20 07:01:25|Update ggml_sycl_op_mul_mat_vec_q|AidanBeltonS <87009434+AidanBeltonS@users.noreply.github.com>|
| 70d45af0|95.0%|-1|2024-02-19 02:37:10|readme : fix typo in README-sycl.md|valiray <133289098+valiray@users.noreply.github.com>|
| 13e2c771|95.0%|-1|2024-02-19 14:45:18|cmake : remove obsolete sycl compile flags|Abhilash Majumder <30946547+abhilash1910@users.noreply.github.com>|
| 43fe07c1|95.0%|-1|2024-02-12 20:22:05|ggml-sycl: Replace 3d ops with macro|Abhilash Majumder <30946547+abhilash1910@users.noreply.github.com>|
| 6e99f2a0|95.0%|-1|2024-02-08 22:39:10|Fix f16_sycl cpy call from Arc|Abhilash Majumder <30946547+abhilash1910@users.noreply.github.com>|
| 10afa6f1|Build_Err|-1|2024-02-07 18:16:55|[SYCL] update install make by w64devkit|Neo Zhang Jianyu <jianyu.zhang@intel.com>|
| 4833ac20|Build_Err|-1|2024-02-05 07:08:24|[SYCL] Fix cpy with dims of 3|AidanBeltonS <87009434+AidanBeltonS@users.noreply.github.com>|
| a305dba8|95.0%|-1|2024-02-03 08:11:37|Fix im2col with 32fp|AidanBeltonS <87009434+AidanBeltonS@users.noreply.github.com>|
| b05102fe|95.0%|-1|2024-02-02 08:39:48|Tidy ggml-sycl|AidanBeltonS <87009434+AidanBeltonS@users.noreply.github.com>|
| 6b91b1e0|95.0%|-1|2024-02-02 08:56:31|docker : add build for SYCL, Vulkan + update readme|Xuan Son Nguyen <thichthat@gmail.com>|
| e805f0fa|95.0%|-1|2024-02-02 15:54:14|[SYCL] get MAX_MEM_ALLOC from device property|Meng, Hengyu <hengyu.meng@intel.com>|
| af3ba5d9|95.0%|-1|2024-02-02 15:53:27|[SYCL] update guide of SYCL backend|Neo Zhang Jianyu <jianyu.zhang@intel.com>|
| 128dcbd3|95.0%|-1|2024-02-02 03:48:53|add --no-mmap in llama-bench|Neo Zhang Jianyu <jianyu.zhang@intel.com>|
| b2b9f025|95.0%|-1|2024-01-31 21:04:46|format license text, restore apache license by legal suggestion|Neo Zhang Jianyu <jianyu.zhang@intel.com>|
| 01684139|95.0%|-1|2024-01-31 10:38:07|support SYCL backend windows build|Neo Zhang Jianyu <jianyu.zhang@intel.com>|
| 2307523d|95.0%|-1|2024-01-28 18:03:59|ggml : add Vulkan backend|0cc4m <picard12@live.de>|
| 0f648573|95.0%|-1|2024-01-28 21:26:23|ggml : add unified SYCL backend for Intel GPUs|Abhilash Majumder <30946547+abhilash1910@users.noreply.github.com>|
