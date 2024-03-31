### ctest_release

Runs ctest in release mode
- status: 8
```
+ ctest --output-on-failure -L main
Test project /var/jenkins_home/workspace/llama.cpp/llama.cpp/build-ci-release
      Start  1: test-quantize-fns
 1/22 Test  #1: test-quantize-fns ...................   Passed   14.32 sec
      Start  2: test-quantize-perf
 2/22 Test  #2: test-quantize-perf ..................   Passed    4.05 sec
      Start  3: test-sampling
 3/22 Test  #3: test-sampling .......................   Passed    0.12 sec
      Start  4: test-chat-template
 4/22 Test  #4: test-chat-template ..................   Passed    0.12 sec
      Start  5: test-tokenizer-0-llama
 5/22 Test  #5: test-tokenizer-0-llama ..............   Passed    0.11 sec
      Start  6: test-tokenizer-0-falcon
 6/22 Test  #6: test-tokenizer-0-falcon .............   Passed    0.23 sec
      Start  7: test-tokenizer-1-llama
 7/22 Test  #7: test-tokenizer-1-llama ..............   Passed    0.35 sec
      Start  8: test-tokenizer-1-baichuan
 8/22 Test  #8: test-tokenizer-1-baichuan ...........   Passed    0.36 sec
      Start  9: test-tokenizer-1-falcon
 9/22 Test  #9: test-tokenizer-1-falcon .............   Passed    0.71 sec
      Start 10: test-tokenizer-1-aquila
10/22 Test #10: test-tokenizer-1-aquila .............   Passed    1.12 sec
      Start 11: test-tokenizer-1-mpt
11/22 Test #11: test-tokenizer-1-mpt ................   Passed    0.64 sec
      Start 12: test-tokenizer-1-stablelm-3b-4e1t
12/22 Test #12: test-tokenizer-1-stablelm-3b-4e1t ...   Passed    0.62 sec
      Start 13: test-tokenizer-1-gpt-neox
13/22 Test #13: test-tokenizer-1-gpt-neox ...........   Passed    0.61 sec
      Start 14: test-tokenizer-1-refact
14/22 Test #14: test-tokenizer-1-refact .............   Passed    0.61 sec
      Start 15: test-tokenizer-1-starcoder
15/22 Test #15: test-tokenizer-1-starcoder ..........   Passed    0.59 sec
      Start 16: test-tokenizer-1-gpt2
16/22 Test #16: test-tokenizer-1-gpt2 ...............   Passed    0.61 sec
      Start 17: test-grammar-parser
17/22 Test #17: test-grammar-parser .................   Passed    0.04 sec
      Start 18: test-llama-grammar
18/22 Test #18: test-llama-grammar ..................   Passed    0.09 sec
      Start 19: test-grad0
19/22 Test #19: test-grad0 ..........................   Passed    1.30 sec
      Start 20: test-backend-ops
20/22 Test #20: test-backend-ops ....................Subprocess aborted***Exception:   0.18 sec
ggml_backend_sycl_set_mul_device_mode: true
terminate called after throwing an instance of 'sycl::_V1::invalid_parameter_error'
  what():  DeviceList is empty. -30 (PI_ERROR_INVALID_VALUE)

      Start 21: test-rope
21/22 Test #21: test-rope ...........................   Passed    0.06 sec
      Start 24: test-json-schema-to-grammar
22/22 Test #24: test-json-schema-to-grammar .........   Passed    0.02 sec

95% tests passed, 1 tests failed out of 22

Label Time Summary:
main    =  26.86 sec*proc (22 tests)

Total Test time (real) =  26.87 sec

The following tests FAILED:
	 20 - test-backend-ops (Subprocess aborted)
Errors while running CTest

real	0m26.873s
user	0m37.648s
sys	0m2.371s
```
