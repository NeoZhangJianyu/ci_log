### ctest_release

Runs ctest in release mode
- status: 8
```
+ ctest --output-on-failure -L main
Test project /var/jenkins_home/workspace/llama.cpp/llama.cpp/build-ci-release
      Start  1: test-quantize-fns
 1/21 Test  #1: test-quantize-fns ...................***Failed    0.11 sec
ggml_init_sycl: GGML_SYCL_DEBUG: 0
ggml_init_sycl: GGML_SYCL_F16: yes
found 2 SYCL devices:
|ID| Name                                        |compute capability|Max compute units|Max work group|Max sub group|Global mem size|
|--|---------------------------------------------|------------------|-----------------|--------------|-------------|---------------|
| 0|          12th Gen Intel(R) Core(TM) i5-1250P|               3.0|               16|          8192|           64|    33381060608|
| 1|               Intel(R) FPGA Emulation Device|               1.2|               16|      67108864|           64|    33381060608|
DeviceList is empty. -30 (PI_ERROR_INVALID_VALUE)Exception caught at file:/var/jenkins_home/workspace/llama.cpp/llama.cpp/ggml-sycl.cpp, line:13341

      Start  2: test-quantize-perf
 2/21 Test  #2: test-quantize-perf ..................***Failed    0.09 sec
ggml_init_sycl: GGML_SYCL_DEBUG: 0
ggml_init_sycl: GGML_SYCL_F16: yes
found 2 SYCL devices:
|ID| Name                                        |compute capability|Max compute units|Max work group|Max sub group|Global mem size|
|--|---------------------------------------------|------------------|-----------------|--------------|-------------|---------------|
| 0|          12th Gen Intel(R) Core(TM) i5-1250P|               3.0|               16|          8192|           64|    33381060608|
| 1|               Intel(R) FPGA Emulation Device|               1.2|               16|      67108864|           64|    33381060608|
DeviceList is empty. -30 (PI_ERROR_INVALID_VALUE)Exception caught at file:/var/jenkins_home/workspace/llama.cpp/llama.cpp/ggml-sycl.cpp, line:13341

      Start  3: test-sampling
 3/21 Test  #3: test-sampling .......................   Passed    0.09 sec
      Start  4: test-chat-template
 4/21 Test  #4: test-chat-template ..................   Passed    0.07 sec
      Start  5: test-tokenizer-0-llama
 5/21 Test  #5: test-tokenizer-0-llama ..............***Failed    0.07 sec
main : reading vocab from: '/var/jenkins_home/workspace/llama.cpp/llama.cpp/tests/../models/ggml-vocab-llama.gguf'
ggml_init_sycl: GGML_SYCL_DEBUG: 0
ggml_init_sycl: GGML_SYCL_F16: yes
found 2 SYCL devices:
|ID| Name                                        |compute capability|Max compute units|Max work group|Max sub group|Global mem size|
|--|---------------------------------------------|------------------|-----------------|--------------|-------------|---------------|
| 0|          12th Gen Intel(R) Core(TM) i5-1250P|               3.0|               16|          8192|           64|    33381060608|
| 1|               Intel(R) FPGA Emulation Device|               1.2|               16|      67108864|           64|    33381060608|
DeviceList is empty. -30 (PI_ERROR_INVALID_VALUE)Exception caught at file:/var/jenkins_home/workspace/llama.cpp/llama.cpp/ggml-sycl.cpp, line:13341

      Start  6: test-tokenizer-0-falcon
 6/21 Test  #6: test-tokenizer-0-falcon .............***Failed    0.07 sec
main : reading vocab from: '/var/jenkins_home/workspace/llama.cpp/llama.cpp/tests/../models/ggml-vocab-falcon.gguf'
ggml_init_sycl: GGML_SYCL_DEBUG: 0
ggml_init_sycl: GGML_SYCL_F16: yes
found 2 SYCL devices:
|ID| Name                                        |compute capability|Max compute units|Max work group|Max sub group|Global mem size|
|--|---------------------------------------------|------------------|-----------------|--------------|-------------|---------------|
| 0|          12th Gen Intel(R) Core(TM) i5-1250P|               3.0|               16|          8192|           64|    33381060608|
| 1|               Intel(R) FPGA Emulation Device|               1.2|               16|      67108864|           64|    33381060608|
DeviceList is empty. -30 (PI_ERROR_INVALID_VALUE)Exception caught at file:/var/jenkins_home/workspace/llama.cpp/llama.cpp/ggml-sycl.cpp, line:13341

      Start  7: test-tokenizer-1-llama
 7/21 Test  #7: test-tokenizer-1-llama ..............***Failed    0.07 sec
main : reading vocab from: '/var/jenkins_home/workspace/llama.cpp/llama.cpp/tests/../models/ggml-vocab-llama.gguf'
ggml_init_sycl: GGML_SYCL_DEBUG: 0
ggml_init_sycl: GGML_SYCL_F16: yes
found 2 SYCL devices:
|ID| Name                                        |compute capability|Max compute units|Max work group|Max sub group|Global mem size|
|--|---------------------------------------------|------------------|-----------------|--------------|-------------|---------------|
| 0|          12th Gen Intel(R) Core(TM) i5-1250P|               3.0|               16|          8192|           64|    33381060608|
| 1|               Intel(R) FPGA Emulation Device|               1.2|               16|      67108864|           64|    33381060608|
DeviceList is empty. -30 (PI_ERROR_INVALID_VALUE)Exception caught at file:/var/jenkins_home/workspace/llama.cpp/llama.cpp/ggml-sycl.cpp, line:13341

      Start  8: test-tokenizer-1-baichuan
 8/21 Test  #8: test-tokenizer-1-baichuan ...........***Failed    0.07 sec
main : reading vocab from: '/var/jenkins_home/workspace/llama.cpp/llama.cpp/tests/../models/ggml-vocab-baichuan.gguf'
ggml_init_sycl: GGML_SYCL_DEBUG: 0
ggml_init_sycl: GGML_SYCL_F16: yes
found 2 SYCL devices:
|ID| Name                                        |compute capability|Max compute units|Max work group|Max sub group|Global mem size|
|--|---------------------------------------------|------------------|-----------------|--------------|-------------|---------------|
| 0|          12th Gen Intel(R) Core(TM) i5-1250P|               3.0|               16|          8192|           64|    33381060608|
| 1|               Intel(R) FPGA Emulation Device|               1.2|               16|      67108864|           64|    33381060608|
DeviceList is empty. -30 (PI_ERROR_INVALID_VALUE)Exception caught at file:/var/jenkins_home/workspace/llama.cpp/llama.cpp/ggml-sycl.cpp, line:13341

      Start  9: test-tokenizer-1-falcon
 9/21 Test  #9: test-tokenizer-1-falcon .............***Failed    0.09 sec
main : reading vocab from: '/var/jenkins_home/workspace/llama.cpp/llama.cpp/tests/../models/ggml-vocab-falcon.gguf'
ggml_init_sycl: GGML_SYCL_DEBUG: 0
ggml_init_sycl: GGML_SYCL_F16: yes
found 2 SYCL devices:
|ID| Name                                        |compute capability|Max compute units|Max work group|Max sub group|Global mem size|
|--|---------------------------------------------|------------------|-----------------|--------------|-------------|---------------|
| 0|          12th Gen Intel(R) Core(TM) i5-1250P|               3.0|               16|          8192|           64|    33381060608|
| 1|               Intel(R) FPGA Emulation Device|               1.2|               16|      67108864|           64|    33381060608|
DeviceList is empty. -30 (PI_ERROR_INVALID_VALUE)Exception caught at file:/var/jenkins_home/workspace/llama.cpp/llama.cpp/ggml-sycl.cpp, line:13341

      Start 10: test-tokenizer-1-aquila
10/21 Test #10: test-tokenizer-1-aquila .............***Failed    0.08 sec
main : reading vocab from: '/var/jenkins_home/workspace/llama.cpp/llama.cpp/tests/../models/ggml-vocab-aquila.gguf'
ggml_init_sycl: GGML_SYCL_DEBUG: 0
ggml_init_sycl: GGML_SYCL_F16: yes
found 2 SYCL devices:
|ID| Name                                        |compute capability|Max compute units|Max work group|Max sub group|Global mem size|
|--|---------------------------------------------|------------------|-----------------|--------------|-------------|---------------|
| 0|          12th Gen Intel(R) Core(TM) i5-1250P|               3.0|               16|          8192|           64|    33381060608|
| 1|               Intel(R) FPGA Emulation Device|               1.2|               16|      67108864|           64|    33381060608|
DeviceList is empty. -30 (PI_ERROR_INVALID_VALUE)Exception caught at file:/var/jenkins_home/workspace/llama.cpp/llama.cpp/ggml-sycl.cpp, line:13341

      Start 11: test-tokenizer-1-mpt
11/21 Test #11: test-tokenizer-1-mpt ................***Failed    0.07 sec
main : reading vocab from: '/var/jenkins_home/workspace/llama.cpp/llama.cpp/tests/../models/ggml-vocab-mpt.gguf'
ggml_init_sycl: GGML_SYCL_DEBUG: 0
ggml_init_sycl: GGML_SYCL_F16: yes
found 2 SYCL devices:
|ID| Name                                        |compute capability|Max compute units|Max work group|Max sub group|Global mem size|
|--|---------------------------------------------|------------------|-----------------|--------------|-------------|---------------|
| 0|          12th Gen Intel(R) Core(TM) i5-1250P|               3.0|               16|          8192|           64|    33381060608|
| 1|               Intel(R) FPGA Emulation Device|               1.2|               16|      67108864|           64|    33381060608|
DeviceList is empty. -30 (PI_ERROR_INVALID_VALUE)Exception caught at file:/var/jenkins_home/workspace/llama.cpp/llama.cpp/ggml-sycl.cpp, line:13341

      Start 12: test-tokenizer-1-stablelm-3b-4e1t
12/21 Test #12: test-tokenizer-1-stablelm-3b-4e1t ...***Failed    0.07 sec
main : reading vocab from: '/var/jenkins_home/workspace/llama.cpp/llama.cpp/tests/../models/ggml-vocab-stablelm-3b-4e1t.gguf'
ggml_init_sycl: GGML_SYCL_DEBUG: 0
ggml_init_sycl: GGML_SYCL_F16: yes
found 2 SYCL devices:
|ID| Name                                        |compute capability|Max compute units|Max work group|Max sub group|Global mem size|
|--|---------------------------------------------|------------------|-----------------|--------------|-------------|---------------|
| 0|          12th Gen Intel(R) Core(TM) i5-1250P|               3.0|               16|          8192|           64|    33381060608|
| 1|               Intel(R) FPGA Emulation Device|               1.2|               16|      67108864|           64|    33381060608|
DeviceList is empty. -30 (PI_ERROR_INVALID_VALUE)Exception caught at file:/var/jenkins_home/workspace/llama.cpp/llama.cpp/ggml-sycl.cpp, line:13341

      Start 13: test-tokenizer-1-gpt-neox
13/21 Test #13: test-tokenizer-1-gpt-neox ...........***Failed    0.07 sec
main : reading vocab from: '/var/jenkins_home/workspace/llama.cpp/llama.cpp/tests/../models/ggml-vocab-gpt-neox.gguf'
ggml_init_sycl: GGML_SYCL_DEBUG: 0
ggml_init_sycl: GGML_SYCL_F16: yes
found 2 SYCL devices:
|ID| Name                                        |compute capability|Max compute units|Max work group|Max sub group|Global mem size|
|--|---------------------------------------------|------------------|-----------------|--------------|-------------|---------------|
| 0|          12th Gen Intel(R) Core(TM) i5-1250P|               3.0|               16|          8192|           64|    33381060608|
| 1|               Intel(R) FPGA Emulation Device|               1.2|               16|      67108864|           64|    33381060608|
DeviceList is empty. -30 (PI_ERROR_INVALID_VALUE)Exception caught at file:/var/jenkins_home/workspace/llama.cpp/llama.cpp/ggml-sycl.cpp, line:13341

      Start 14: test-tokenizer-1-refact
14/21 Test #14: test-tokenizer-1-refact .............***Failed    0.08 sec
main : reading vocab from: '/var/jenkins_home/workspace/llama.cpp/llama.cpp/tests/../models/ggml-vocab-refact.gguf'
ggml_init_sycl: GGML_SYCL_DEBUG: 0
ggml_init_sycl: GGML_SYCL_F16: yes
found 2 SYCL devices:
|ID| Name                                        |compute capability|Max compute units|Max work group|Max sub group|Global mem size|
|--|---------------------------------------------|------------------|-----------------|--------------|-------------|---------------|
| 0|          12th Gen Intel(R) Core(TM) i5-1250P|               3.0|               16|          8192|           64|    33381060608|
| 1|               Intel(R) FPGA Emulation Device|               1.2|               16|      67108864|           64|    33381060608|
DeviceList is empty. -30 (PI_ERROR_INVALID_VALUE)Exception caught at file:/var/jenkins_home/workspace/llama.cpp/llama.cpp/ggml-sycl.cpp, line:13341

      Start 15: test-tokenizer-1-starcoder
15/21 Test #15: test-tokenizer-1-starcoder ..........***Failed    0.07 sec
main : reading vocab from: '/var/jenkins_home/workspace/llama.cpp/llama.cpp/tests/../models/ggml-vocab-starcoder.gguf'
ggml_init_sycl: GGML_SYCL_DEBUG: 0
ggml_init_sycl: GGML_SYCL_F16: yes
found 2 SYCL devices:
|ID| Name                                        |compute capability|Max compute units|Max work group|Max sub group|Global mem size|
|--|---------------------------------------------|------------------|-----------------|--------------|-------------|---------------|
| 0|          12th Gen Intel(R) Core(TM) i5-1250P|               3.0|               16|          8192|           64|    33381060608|
| 1|               Intel(R) FPGA Emulation Device|               1.2|               16|      67108864|           64|    33381060608|
DeviceList is empty. -30 (PI_ERROR_INVALID_VALUE)Exception caught at file:/var/jenkins_home/workspace/llama.cpp/llama.cpp/ggml-sycl.cpp, line:13341

      Start 16: test-tokenizer-1-gpt2
16/21 Test #16: test-tokenizer-1-gpt2 ...............***Failed    0.07 sec
main : reading vocab from: '/var/jenkins_home/workspace/llama.cpp/llama.cpp/tests/../models/ggml-vocab-gpt2.gguf'
ggml_init_sycl: GGML_SYCL_DEBUG: 0
ggml_init_sycl: GGML_SYCL_F16: yes
found 2 SYCL devices:
|ID| Name                                        |compute capability|Max compute units|Max work group|Max sub group|Global mem size|
|--|---------------------------------------------|------------------|-----------------|--------------|-------------|---------------|
| 0|          12th Gen Intel(R) Core(TM) i5-1250P|               3.0|               16|          8192|           64|    33381060608|
| 1|               Intel(R) FPGA Emulation Device|               1.2|               16|      67108864|           64|    33381060608|
DeviceList is empty. -30 (PI_ERROR_INVALID_VALUE)Exception caught at file:/var/jenkins_home/workspace/llama.cpp/llama.cpp/ggml-sycl.cpp, line:13341

      Start 17: test-grammar-parser
17/21 Test #17: test-grammar-parser .................   Passed    0.02 sec
      Start 18: test-llama-grammar
18/21 Test #18: test-llama-grammar ..................   Passed    0.07 sec
      Start 19: test-grad0
19/21 Test #19: test-grad0 ..........................***Failed    0.08 sec
ggml_init_sycl: GGML_SYCL_DEBUG: 0
ggml_init_sycl: GGML_SYCL_F16: yes
found 2 SYCL devices:
|ID| Name                                        |compute capability|Max compute units|Max work group|Max sub group|Global mem size|
|--|---------------------------------------------|------------------|-----------------|--------------|-------------|---------------|
| 0|          12th Gen Intel(R) Core(TM) i5-1250P|               3.0|               16|          8192|           64|    33381060608|
| 1|               Intel(R) FPGA Emulation Device|               1.2|               16|      67108864|           64|    33381060608|
test-grad0: iter:0/4
DeviceList is empty. -30 (PI_ERROR_INVALID_VALUE)Exception caught at file:/var/jenkins_home/workspace/llama.cpp/llama.cpp/ggml-sycl.cpp, line:13341

      Start 20: test-backend-ops
20/21 Test #20: test-backend-ops ....................Subprocess aborted***Exception:   0.12 sec
terminate called after throwing an instance of 'sycl::_V1::invalid_parameter_error'
  what():  DeviceList is empty. -30 (PI_ERROR_INVALID_VALUE)

      Start 21: test-rope
21/21 Test #21: test-rope ...........................***Failed    0.07 sec
ggml_init_sycl: GGML_SYCL_DEBUG: 0
ggml_init_sycl: GGML_SYCL_F16: yes
found 2 SYCL devices:
|ID| Name                                        |compute capability|Max compute units|Max work group|Max sub group|Global mem size|
|--|---------------------------------------------|------------------|-----------------|--------------|-------------|---------------|
| 0|          12th Gen Intel(R) Core(TM) i5-1250P|               3.0|               16|          8192|           64|    33381060608|
| 1|               Intel(R) FPGA Emulation Device|               1.2|               16|      67108864|           64|    33381060608|
DeviceList is empty. -30 (PI_ERROR_INVALID_VALUE)Exception caught at file:/var/jenkins_home/workspace/llama.cpp/llama.cpp/ggml-sycl.cpp, line:13341


19% tests passed, 17 tests failed out of 21

Label Time Summary:
main    =   1.57 sec*proc (21 tests)

Total Test time (real) =   1.57 sec

The following tests FAILED:
	  1 - test-quantize-fns (Failed)
	  2 - test-quantize-perf (Failed)
	  5 - test-tokenizer-0-llama (Failed)
	  6 - test-tokenizer-0-falcon (Failed)
	  7 - test-tokenizer-1-llama (Failed)
	  8 - test-tokenizer-1-baichuan (Failed)
	  9 - test-tokenizer-1-falcon (Failed)
	 10 - test-tokenizer-1-aquila (Failed)
	 11 - test-tokenizer-1-mpt (Failed)
	 12 - test-tokenizer-1-stablelm-3b-4e1t (Failed)
	 13 - test-tokenizer-1-gpt-neox (Failed)
	 14 - test-tokenizer-1-refact (Failed)
	 15 - test-tokenizer-1-starcoder (Failed)
	 16 - test-tokenizer-1-gpt2 (Failed)
	 19 - test-grad0 (Failed)
	 20 - test-backend-ops (Subprocess aborted)
	 21 - test-rope (Failed)
Errors while running CTest

real	0m1.580s
user	0m1.012s
sys	0m0.850s
```