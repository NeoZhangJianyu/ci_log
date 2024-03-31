# llama.cpp CI for SYCL Backend

|Commit ID|UT PassRate|Warn|Date|Title|Author|Log|
|-|-|-|-|-|-|-|
| 5106ef48|95.0%|-1|2024-03-28 16:01:47|[SYCL] Revisited & updated SYCL build documentation|Ouadie EL FAROUKI|[log](./log/5106ef482c65ac60ac14da9a68c7b37bca4c6993)|
| 25f4a613|95.0%|-1|2024-03-28 08:55:24|[SYCL] fix set main gpu crash|Neo Zhang Jianyu|[log](./log/25f4a613c4ed6451162a87cb90be10d610b49f0f)|
| e82f9e2b|95.0%|-1|2024-03-27 08:16:40|[SYCL] Fix batched impl for NVidia GPU|AidanBeltonS|[log](./log/e82f9e2b833d88cd2b30123ef57346c2cb8abd99)|
| a4f569e8|95.0%|-1|2024-03-27 09:47:06|[SYCL] fix no file in win rel|Neo Zhang Jianyu|[log](./log/a4f569e8a316cbd33d2b4de94b694d111507475a)|
| 557410b8|95.0%|-1|2024-03-26 10:46:41|llama : greatly reduce output buffer memory usage|compilade|[log](./log/557410b8f06380560155ac7fcb8316d71ddc9837)|
| 95ad616c|95.0%|-1|2024-03-25 15:52:41|[SYCL] fix SYCL backend build on windows is break by LOG|Neo Zhang Jianyu|[log](./log/95ad616cddda50273e955bfe192328acd9aa4896)|
| ddf65685|95.0%|-1|2024-03-24 12:04:25|[SYCL] offload op|Meng, Hengyu|[log](./log/ddf65685105a39a57b1e7f80c3aa502a6313af24)|
| 59c17f02|95.0%|-1|2024-03-22 15:19:37|add blog link|Neo Zhang Jianyu|[log](./log/59c17f02de8fdf7b084d6100b875b7e2bc07a83b)|
| f372c49c|95.0%|-1|2024-03-21 11:52:35|Corrected typo to wrong file|semidark|[log](./log/f372c49ccdc561ab96fb3c7d2b7cbc0f89a4b359)|
| c5b8595e|95.0%|-1|2024-03-21 06:10:52|Add nvidia and amd backends|AidanBeltonS|[log](./log/c5b8595e3f4f4ed319ef71c9c9d868d1b7a27626)|
| 6c0b2877|95.0%|-1|2024-03-20 11:21:41|update readme sycl for new update|Neo Zhang Jianyu|[log](./log/6c0b287748327741b113d7d6018b68c63039b1c5)|
| d26e8b66|95.0%|-1|2024-03-20 08:28:49|increase igpu cluster limit|Abhilash Majumder|[log](./log/d26e8b669dbf1f5f5a0afe4d2d885e86cf566302)|
| 2bf8d0f7|95.0%|-1|2024-03-18 11:03:04|backend : offload large batches to GPU|slaren|[log](./log/2bf8d0f7c4cc1235755ad06961ca761e458c5e55)|
| 46acb367|95.0%|-1|2024-03-15 18:53:53|fix set main gpu error|Neo Zhang Jianyu|[log](./log/46acb3676718b983157058aecf729a2064fc7d34)|
| 753e36f6|19.0%|-1|2024-03-15 09:26:20|[SYCL] Fix non-intel device selection|AidanBeltonS|[log](./log/753e36f650fa2a5869f89188d9ee745dc74cf14b)|
| f30ea47a|19.0%|-1|2024-03-13 18:54:21|llama : add pipeline parallelism support|slaren|[log](./log/f30ea47a87ed4446ad55adb265755dc9102956a2)|
| b3d97860|19.0%|-1|2024-03-13 13:17:54|Update get version|AidanBeltonS|[log](./log/b3d978600f07f22e94f2e797f18a8b5f6df23c89)|
| 8030da7a|19.0%|-1|2024-03-12 14:27:20|ggml : reuse quantum structs across backends|Georgi Gerganov|[log](./log/8030da7afea2d89f997aeadbd14183d399a017b9)|
| 48358b2e|19.0%|-1|2024-03-12 11:15:05|sycl : update IQ1_S kernels|Georgi Gerganov|[log](./log/48358b2e5b3983c41ba7e61a493e84d3901dc7b9)|
| ef3ced26|19.0%|-1|2024-03-11 10:27:56|[SYCL] Add q3_s and q1_s|Abhilash Majumder|[log](./log/ef3ced26a3817d92890b97b83acaeb018ade02d0)|
| 3814a073|19.0%|-1|2024-03-11 01:13:57|[SYCL] Add support for SYCL Nvidia target|AidanBeltonS|[log](./log/3814a07392d2bdc22911652bc7c2f9bdb0ce042e)|
| 8a3012a4|19.0%|-1|2024-03-09 12:47:57|ggml : add ggml-common.h to deduplicate shared code|Georgi Gerganov|[log](./log/8a3012a4ad08112bb3dc3f1399afec4e93780c44)|
| 89fb735f|19.0%|-1|2024-03-07 19:14:49|Revert "[SYCL] fix error when set main gpu to non-zero|Neo Zhang Jianyu|[log](./log/89fb735fcfd21781a8194b211cf32824beb3f71f)|
| ceca1aef|19.0%|-1|2024-03-07 16:34:31|[SYCL] fix error when set main gpu to non-zero|Neo Zhang Jianyu|[log](./log/ceca1aef0738b57951cd12c603c3477e75312dec)|
| 8ced9f7e|19.0%|-1|2024-03-06 12:08:32|add wait|Neo Zhang Jianyu|[log](./log/8ced9f7e3225adb8501e9821ed1bbd92e3a5c7ae)|
| 21b08674|19.0%|-1|2024-03-05 16:08:35|[SYCL] fix mul_mat fault in CI/unit-test|Neo Zhang Jianyu|[log](./log/21b08674331e1ea1b599f17c5ca91f0ed173be31)|
| 9fa26273|19.0%|-1|2024-03-04 10:05:42|ggml : introduce ggml_status|Michael Podvitskiy|[log](./log/9fa262734733573fa629ffc97dfcb971fe3f4832)|
| 71564139|19.0%|-1|2024-03-02 19:49:30|Support multiple GPUs|Neo Zhang Jianyu|[log](./log/715641391dda1ff9762dc5d99d9a30acce99f2c6)|
| 38d15216|95.0%|-1|2024-03-01 07:36:47|[SYCL] Use batched mul_mat pathway|AidanBeltonS|[log](./log/38d152160898b0173ffe4dc7df5daadcbd2eceb0)|
| 5f706718|95.0%|-1|2024-02-24 11:27:36|Introduce backend GUIDs|UEXTM.com|[log](./log/5f706718566e3a5147916dc381f3b99de0ffad47)|
| e849078c|95.0%|-1|2024-02-26 14:02:11|[SYCL] Add support for soft_max ALiBi|AidanBeltonS|[log](./log/e849078c6e09e72fdd2c95ba61f5fba9a7b2d9ef)|
| ab336a9d|95.0%|-1|2024-02-25 12:09:09|code : normalize enum names|Georgi Gerganov|[log](./log/ab336a9d5e5352ecdcdf4c12d2d54cf4ef82ce31)|
| 88c46cbd|95.0%|-1|2024-02-21 17:52:06|[SYCL] conext add name|Meng, Hengyu|[log](./log/88c46cbdac05cebd936511b1d3c74112e721615f)|
| b9111bd2|95.0%|-1|2024-02-20 07:01:25|Update ggml_sycl_op_mul_mat_vec_q|AidanBeltonS|[log](./log/b9111bd209c7b11b0592450a6ed2e0ca545b2c84)|
| 70d45af0|95.0%|-1|2024-02-19 02:37:10|readme : fix typo in README-sycl.md|valiray|[log](./log/70d45af0efce9ed360e1858b827989d971dd9caf)|
| 13e2c771|95.0%|-1|2024-02-19 14:45:18|cmake : remove obsolete sycl compile flags|Abhilash Majumder|[log](./log/13e2c771aa4212cd5405cf310203848d50f7f859)|
| 43fe07c1|95.0%|-1|2024-02-12 20:22:05|ggml-sycl: Replace 3d ops with macro|Abhilash Majumder|[log](./log/43fe07c1a4f3a58612e1d9543f7c6b556710f5d0)|
| 6e99f2a0|95.0%|-1|2024-02-08 22:39:10|Fix f16_sycl cpy call from Arc|Abhilash Majumder|[log](./log/6e99f2a04f1871d637dd77eb4d81de31a5510253)|
| 10afa6f1|Build_Err|-1|2024-02-07 18:16:55|[SYCL] update install make by w64devkit|Neo Zhang Jianyu|[log](./log/10afa6f1d11ebc9fcc1085f468170002cbf6e2b5)|
| 4833ac20|Build_Err|-1|2024-02-05 07:08:24|[SYCL] Fix cpy with dims of 3|AidanBeltonS|[log](./log/4833ac209da6a427de64f97e8f403dcdc5de6bc3)|
| a305dba8|95.0%|-1|2024-02-03 08:11:37|Fix im2col with 32fp|AidanBeltonS|[log](./log/a305dba8ff642e57f538f42010868fe0bc5262a1)|
| b05102fe|95.0%|-1|2024-02-02 08:39:48|Tidy ggml-sycl|AidanBeltonS|[log](./log/b05102fe8cfa9893851c6bf6efd15cdc20b6afa2)|
| 6b91b1e0|95.0%|-1|2024-02-02 08:56:31|docker : add build for SYCL, Vulkan + update readme|Xuan Son Nguyen|[log](./log/6b91b1e0a92ac2e4e269eec6361ca53a61ced6c6)|
| e805f0fa|95.0%|-1|2024-02-02 15:54:14|[SYCL] get MAX_MEM_ALLOC from device property|Meng, Hengyu|[log](./log/e805f0fa9951081ce0a86378a7aa52b6f636b82d)|
| af3ba5d9|95.0%|-1|2024-02-02 15:53:27|[SYCL] update guide of SYCL backend|Neo Zhang Jianyu|[log](./log/af3ba5d94627d337e32a95129e31a3064c459f6b)|
| 128dcbd3|95.0%|-1|2024-02-02 03:48:53|add --no-mmap in llama-bench|Neo Zhang Jianyu|[log](./log/128dcbd3c9c4b12f42b560a4430427d7b2828628)|
| b2b9f025|95.0%|-1|2024-01-31 21:04:46|format license text, restore apache license by legal suggestion|Neo Zhang Jianyu|[log](./log/b2b9f025e7821e78bd501d75d01838c26de07a57)|
| 01684139|95.0%|-1|2024-01-31 10:38:07|support SYCL backend windows build|Neo Zhang Jianyu|[log](./log/01684139c352561840ae55ec627ab58abc3e06ab)|
| 2307523d|95.0%|-1|2024-01-28 18:03:59|ggml : add Vulkan backend|0cc4m|[log](./log/2307523d322af762ae06648b29ec5a9eb1c73032)|
| 0f648573|95.0%|-1|2024-01-28 21:26:23|ggml : add unified SYCL backend for Intel GPUs|Abhilash Majumder|[log](./log/0f648573dde61c510560f68244f70ece7e60d8c1)|
