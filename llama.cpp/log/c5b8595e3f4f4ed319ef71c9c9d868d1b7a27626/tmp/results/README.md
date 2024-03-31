### ctest_release

Runs ctest in release mode
- status: 8
```
+ ctest --output-on-failure -L main
Test project /var/jenkins_home/workspace/llama.cpp/llama.cpp/build-ci-release
      Start  1: test-quantize-fns
 1/21 Test  #1: test-quantize-fns ...................   Passed   11.90 sec
      Start  2: test-quantize-perf
 2/21 Test  #2: test-quantize-perf ..................   Passed    4.11 sec
      Start  3: test-sampling
 3/21 Test  #3: test-sampling .......................   Passed    0.13 sec
      Start  4: test-chat-template
 4/21 Test  #4: test-chat-template ..................   Passed    0.10 sec
      Start  5: test-tokenizer-0-llama
 5/21 Test  #5: test-tokenizer-0-llama ..............   Passed    0.13 sec
      Start  6: test-tokenizer-0-falcon
 6/21 Test  #6: test-tokenizer-0-falcon .............   Passed    0.26 sec
      Start  7: test-tokenizer-1-llama
 7/21 Test  #7: test-tokenizer-1-llama ..............   Passed    0.33 sec
      Start  8: test-tokenizer-1-baichuan
 8/21 Test  #8: test-tokenizer-1-baichuan ...........   Passed    0.37 sec
      Start  9: test-tokenizer-1-falcon
 9/21 Test  #9: test-tokenizer-1-falcon .............   Passed    0.71 sec
      Start 10: test-tokenizer-1-aquila
10/21 Test #10: test-tokenizer-1-aquila .............   Passed    1.11 sec
      Start 11: test-tokenizer-1-mpt
11/21 Test #11: test-tokenizer-1-mpt ................   Passed    0.63 sec
      Start 12: test-tokenizer-1-stablelm-3b-4e1t
12/21 Test #12: test-tokenizer-1-stablelm-3b-4e1t ...   Passed    0.62 sec
      Start 13: test-tokenizer-1-gpt-neox
13/21 Test #13: test-tokenizer-1-gpt-neox ...........   Passed    0.62 sec
      Start 14: test-tokenizer-1-refact
14/21 Test #14: test-tokenizer-1-refact .............   Passed    0.60 sec
      Start 15: test-tokenizer-1-starcoder
15/21 Test #15: test-tokenizer-1-starcoder ..........   Passed    0.60 sec
      Start 16: test-tokenizer-1-gpt2
16/21 Test #16: test-tokenizer-1-gpt2 ...............   Passed    0.61 sec
      Start 17: test-grammar-parser
17/21 Test #17: test-grammar-parser .................   Passed    0.02 sec
      Start 18: test-llama-grammar
18/21 Test #18: test-llama-grammar ..................   Passed    0.09 sec
      Start 19: test-grad0
19/21 Test #19: test-grad0 ..........................   Passed    1.37 sec
      Start 20: test-backend-ops
20/21 Test #20: test-backend-ops ....................Subprocess aborted***Exception:   0.15 sec
ggml_backend_sycl_set_mul_device_mode: true
terminate called after throwing an instance of 'sycl::_V1::invalid_parameter_error'
  what():  DeviceList is empty. -30 (PI_ERROR_INVALID_VALUE)

      Start 21: test-rope
21/21 Test #21: test-rope ...........................   Passed    0.12 sec

95% tests passed, 1 tests failed out of 21

Label Time Summary:
main    =  24.57 sec*proc (21 tests)

Total Test time (real) =  24.57 sec

The following tests FAILED:
	 20 - test-backend-ops (Subprocess aborted)
Errors while running CTest

real	0m24.581s
user	0m35.240s
sys	0m2.714s
```