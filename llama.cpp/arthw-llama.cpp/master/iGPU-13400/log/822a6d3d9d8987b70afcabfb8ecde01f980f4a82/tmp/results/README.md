### ctest_release

Runs ctest in release mode
- status: 8
```
+ ctest --output-on-failure -L main
Test project /home/zjy/ws/jenkins/workspace/ci-arc770/arthw-llama.cpp/build-ci-release
      Start  1: test-tokenizer-0-bert-bge
 1/29 Test  #1: test-tokenizer-0-bert-bge .........   Passed    0.14 sec
      Start  2: test-tokenizer-0-command-r
 2/29 Test  #2: test-tokenizer-0-command-r ........   Passed    0.38 sec
      Start  3: test-tokenizer-0-deepseek-coder
 3/29 Test  #3: test-tokenizer-0-deepseek-coder ...   Passed    0.13 sec
      Start  4: test-tokenizer-0-deepseek-llm
 4/29 Test  #4: test-tokenizer-0-deepseek-llm .....   Passed    0.19 sec
      Start  5: test-tokenizer-0-falcon
 5/29 Test  #5: test-tokenizer-0-falcon ...........   Passed    0.16 sec
      Start  6: test-tokenizer-0-gpt-2
 6/29 Test  #6: test-tokenizer-0-gpt-2 ............   Passed    0.15 sec
      Start  7: test-tokenizer-0-llama-bpe
 7/29 Test  #7: test-tokenizer-0-llama-bpe ........   Passed    0.28 sec
      Start  8: test-tokenizer-0-llama-spm
 8/29 Test  #8: test-tokenizer-0-llama-spm ........   Passed    0.11 sec
      Start  9: test-tokenizer-0-mpt
 9/29 Test  #9: test-tokenizer-0-mpt ..............   Passed    0.13 sec
      Start 10: test-tokenizer-0-phi-3
10/29 Test #10: test-tokenizer-0-phi-3 ............   Passed    0.10 sec
      Start 11: test-tokenizer-0-qwen2
11/29 Test #11: test-tokenizer-0-qwen2 ............   Passed    0.26 sec
      Start 12: test-tokenizer-0-refact
12/29 Test #12: test-tokenizer-0-refact ...........   Passed    0.14 sec
      Start 13: test-tokenizer-0-starcoder
13/29 Test #13: test-tokenizer-0-starcoder ........   Passed    0.14 sec
      Start 14: test-sampling
14/29 Test #14: test-sampling .....................   Passed    0.94 sec
      Start 15: test-grammar-parser
15/29 Test #15: test-grammar-parser ...............   Passed    0.03 sec
      Start 16: test-grammar-integration
16/29 Test #16: test-grammar-integration ..........   Passed    0.03 sec
      Start 17: test-llama-grammar
17/29 Test #17: test-llama-grammar ................   Passed    0.03 sec
      Start 18: test-chat
18/29 Test #18: test-chat .........................   Passed    0.37 sec
      Start 19: test-json-schema-to-grammar
19/29 Test #19: test-json-schema-to-grammar .......   Passed    1.78 sec
      Start 20: test-tokenizer-1-llama-spm
20/29 Test #20: test-tokenizer-1-llama-spm ........   Passed    0.19 sec
      Start 21: test-log
21/29 Test #21: test-log ..........................   Passed    0.04 sec
      Start 22: test-arg-parser
22/29 Test #22: test-arg-parser ...................   Passed    0.11 sec
      Start 23: test-chat-template
23/29 Test #23: test-chat-template ................   Passed    0.10 sec
      Start 24: test-gguf
24/29 Test #24: test-gguf .........................   Passed    0.25 sec
      Start 25: test-backend-ops
25/29 Test #25: test-backend-ops ..................Subprocess aborted***Exception:   1.35 sec
detect 1 SYCL devices:[0] by ONEAPI_DEVICE_SELECTOR=level_zero:1
Running with Environment Variables:
  GGML_SYCL_DEBUG: 0
  GGML_SYCL_DISABLE_OPT: 0
Build with Macros:
  GGML_SYCL_FORCE_MMQ: no
  GGML_SYCL_F16: yes
ggml_sycl_init: SYCL_USE_XMX: yes
found 1 SYCL devices:
Part1:
|ID|        Device Type|  Ver|                                   Name|Global mem size|
|--|-------------------|-----|---------------------------------------|---------------|
| 0| [level_zero:gpu:0]| 12.2|                 Intel UHD Graphics 730|         14958M|

Part2:
|ID|Max compute units|Max work group|Max subgroup|                    Driver version|
|--|-----------------|--------------|------------|----------------------------------|
| 0|               32|           512|          32|                      1.3.29735+27|
SYCL Optimization Feature:
|ID|        Device Type|Reorder|
|--|-------------------|-------|
| 0| [level_zero:gpu:0]|      N|
Testing 2 devices

Backend 1/2: SYCL0
  Device description: Intel(R) UHD Graphics 730
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
  Device memory: 14265 MB (14265 MB free)

  ABS(type=f16,ne_a=[128,2,2,2],v=0): not supported [SYCL0] 
  ABS(type=f16,ne_a=[5,7,11,13],v=0): not supported [SYCL0] 
  SGN(type=f16,ne_a=[128,2,2,2],v=0): not supported [SYCL0] 
  SGN(type=f16,ne_a=[5,7,11,13],v=0): not supported [SYCL0] 
  NEG(type=f16,ne_a=[128,2,2,2],v=0): /home/zjy/ws/jenkins/workspace/ci-arc770/arthw-llama.cpp/ggml/src/ggml-sycl/element_wise.cpp:741: GGML_ASSERT(src0->type == GGML_TYPE_F32) failed
Could not attach to process.  If your uid matches the uid of the target
process, check the setting of /proc/sys/kernel/yama/ptrace_scope, or try
again as the root user.  For more details, see /etc/sysctl.d/10-ptrace.conf
ptrace: Inappropriate ioctl for device.
No stack.
The program is not being run.

      Start 28: test-barrier
26/29 Test #28: test-barrier ......................   Passed    0.92 sec
      Start 29: test-quantize-fns
27/29 Test #29: test-quantize-fns .................   Passed   12.16 sec
      Start 30: test-quantize-perf
28/29 Test #30: test-quantize-perf ................   Passed    0.08 sec
      Start 31: test-rope
29/29 Test #31: test-rope .........................   Passed    0.08 sec

97% tests passed, 1 tests failed out of 29

Label Time Summary:
main    =  20.76 sec*proc (29 tests)

Total Test time (real) =  20.77 sec

The following tests FAILED:
	 25 - test-backend-ops (Subprocess aborted)
Errors while running CTest

real	0m20.777s
user	0m19.176s
sys	0m2.542s
```
