### ctest_release

Runs ctest in release mode
- status: 8
```
+ ctest --output-on-failure -L main
Test project /home/jianyuzh/ws/llama.cpp/llama.cpp_ci/llama.cpp/build-ci-release
      Start  1: test-quantize-fns
 1/22 Test  #1: test-quantize-fns ...................   Passed    8.26 sec
      Start  2: test-quantize-perf
 2/22 Test  #2: test-quantize-perf ..................   Passed    2.90 sec
      Start  3: test-sampling
 3/22 Test  #3: test-sampling .......................   Passed    0.11 sec
      Start  4: test-chat-template
 4/22 Test  #4: test-chat-template ..................   Passed    0.10 sec
      Start  5: test-tokenizer-0-llama
 5/22 Test  #5: test-tokenizer-0-llama ..............   Passed    0.12 sec
      Start  6: test-tokenizer-0-falcon
 6/22 Test  #6: test-tokenizer-0-falcon .............   Passed    0.21 sec
      Start  7: test-tokenizer-1-llama
 7/22 Test  #7: test-tokenizer-1-llama ..............   Passed    0.22 sec
      Start  8: test-tokenizer-1-baichuan
 8/22 Test  #8: test-tokenizer-1-baichuan ...........   Passed    0.24 sec
      Start  9: test-tokenizer-1-falcon
 9/22 Test  #9: test-tokenizer-1-falcon .............   Passed    0.54 sec
      Start 10: test-tokenizer-1-aquila
10/22 Test #10: test-tokenizer-1-aquila .............   Passed    0.80 sec
      Start 11: test-tokenizer-1-mpt
11/22 Test #11: test-tokenizer-1-mpt ................   Passed    0.46 sec
      Start 12: test-tokenizer-1-stablelm-3b-4e1t
12/22 Test #12: test-tokenizer-1-stablelm-3b-4e1t ...   Passed    0.45 sec
      Start 13: test-tokenizer-1-gpt-neox
13/22 Test #13: test-tokenizer-1-gpt-neox ...........   Passed    0.47 sec
      Start 14: test-tokenizer-1-refact
14/22 Test #14: test-tokenizer-1-refact .............   Passed    0.45 sec
      Start 15: test-tokenizer-1-starcoder
15/22 Test #15: test-tokenizer-1-starcoder ..........   Passed    0.43 sec
      Start 16: test-tokenizer-1-gpt2
16/22 Test #16: test-tokenizer-1-gpt2 ...............   Passed    0.43 sec
      Start 17: test-grammar-parser
17/22 Test #17: test-grammar-parser .................   Passed    0.02 sec
      Start 18: test-llama-grammar
18/22 Test #18: test-llama-grammar ..................   Passed    0.10 sec
      Start 19: test-grad0
19/22 Test #19: test-grad0 ..........................   Passed    1.01 sec
      Start 20: test-backend-ops
20/22 Test #20: test-backend-ops ....................Subprocess aborted***Exception:   9.49 sec
ggml_backend_sycl_set_mul_device_mode: true
detect 1 SYCL GPUs: [0] with top Max compute units:512
ggml_init_sycl: GGML_SYCL_DEBUG: 0
ggml_init_sycl: GGML_SYCL_F16: yes
found 6 SYCL devices:
|  |                  |                                             |Compute   |Max compute|Max work|Max sub|               |
|ID|       Device Type|                                         Name|capability|units      |group   |group  |Global mem size|
|--|------------------|---------------------------------------------|----------|-----------|--------|-------|---------------|
| 0|[level_zero:gpu:0]|               Intel(R) Arc(TM) A770 Graphics|       1.3|        512|    1024|     32|    16225243136|
| 1|[level_zero:gpu:1]|                    Intel(R) UHD Graphics 770|       1.3|         32|     512|     32|    62569066496|
| 2|    [opencl:gpu:0]|               Intel(R) Arc(TM) A770 Graphics|       3.0|        512|    1024|     32|    16225243136|
| 3|    [opencl:gpu:1]|                    Intel(R) UHD Graphics 770|       3.0|         32|     512|     32|    62569066496|
| 4|    [opencl:cpu:0]|         13th Gen Intel(R) Core(TM) i7-13700K|       3.0|         24|    8192|     64|    67064815616|
| 5|    [opencl:acc:0]|               Intel(R) FPGA Emulation Device|       1.2|         24|67108864|     64|    67064815616|
Testing 2 backends

Backend 1/2 (CPU)
  Skipping CPU backend
Backend 2/2 (SYCL0)
  Backend name: SYCL0
  ABS(type=f32,ne=[128,10,10,10]): not supported [SYCL0] 
  SGN(type=f32,ne=[128,10,10,10]): not supported [SYCL0] 
  NEG(type=f32,ne=[128,10,10,10]): not supported [SYCL0] 
  STEP(type=f32,ne=[128,10,10,10]): not supported [SYCL0] 
  TANH(type=f32,ne=[128,10,10,10]): [1;32mOK[0m
  ELU(type=f32,ne=[128,10,10,10]): not supported [SYCL0] 
  RELU(type=f32,ne=[128,10,10,10]): [1;32mOK[0m
  GELU(type=f32,ne=[128,10,10,10]): [1;32mOK[0m
  GELU_QUICK(type=f32,ne=[128,10,10,10]): [1;32mOK[0m
  SILU(type=f32,ne=[128,10,10,10]): [1;32mOK[0m
  HARDSWISH(type=f32,ne=[128,10,10,10]): [1;32mOK[0m
  HARDSIGMOID(type=f32,ne=[128,10,10,10]): [1;32mOK[0m
  GET_ROWS(type=f32,n=1,m=8,r=2,b=1,v=0): [1;32mOK[0m
  GET_ROWS(type=f32,n=256,m=5,r=4,b=1,v=0): [1;32mOK[0m
  GET_ROWS(type=f32,n=256,m=5,r=4,b=1,v=1): [1;32mOK[0m
  GET_ROWS(type=f32,n=256,m=5,r=4,b=7,v=0): [1;32mOK[0m
  GET_ROWS(type=f32,n=256,m=5,r=4,b=7,v=1): [1;32mOK[0m
  GET_ROWS(type=f16,n=256,m=5,r=4,b=1,v=0): [1;32mOK[0m
  GET_ROWS(type=f16,n=256,m=5,r=4,b=1,v=1): [1;32mOK[0m
  GET_ROWS(type=f16,n=256,m=5,r=4,b=7,v=0): [1;32mOK[0m
  GET_ROWS(type=f16,n=256,m=5,r=4,b=7,v=1): [1;32mOK[0m
  GET_ROWS(type=q4_0,n=256,m=5,r=4,b=1,v=0): [1;32mOK[0m
  GET_ROWS(type=q4_0,n=256,m=5,r=4,b=1,v=1): [1;32mOK[0m
  GET_ROWS(type=q4_0,n=256,m=5,r=4,b=7,v=0): [1;32mOK[0m
  GET_ROWS(type=q4_0,n=256,m=5,r=4,b=7,v=1): [1;32mOK[0m
  GET_ROWS(type=q4_1,n=256,m=5,r=4,b=1,v=0): [1;32mOK[0m
  GET_ROWS(type=q4_1,n=256,m=5,r=4,b=1,v=1): [1;32mOK[0m
  GET_ROWS(type=q4_1,n=256,m=5,r=4,b=7,v=0): [1;32mOK[0m
  GET_ROWS(type=q4_1,n=256,m=5,r=4,b=7,v=1): [1;32mOK[0m
  GET_ROWS(type=q5_0,n=256,m=5,r=4,b=1,v=0): [1;32mOK[0m
  GET_ROWS(type=q5_0,n=256,m=5,r=4,b=1,v=1): [1;32mOK[0m
  GET_ROWS(type=q5_0,n=256,m=5,r=4,b=7,v=0): [1;32mOK[0m
  GET_ROWS(type=q5_0,n=256,m=5,r=4,b=7,v=1): [1;32mOK[0m
  GET_ROWS(type=q5_1,n=256,m=5,r=4,b=1,v=0): [1;32mOK[0m
  GET_ROWS(type=q5_1,n=256,m=5,r=4,b=1,v=1): [1;32mOK[0m
  GET_ROWS(type=q5_1,n=256,m=5,r=4,b=7,v=0): [1;32mOK[0m
  GET_ROWS(type=q5_1,n=256,m=5,r=4,b=7,v=1): [1;32mOK[0m
  GET_ROWS(type=q8_0,n=256,m=5,r=4,b=1,v=0): [1;32mOK[0m
  GET_ROWS(type=q8_0,n=256,m=5,r=4,b=1,v=1): [1;32mOK[0m
  GET_ROWS(type=q8_0,n=256,m=5,r=4,b=7,v=0): [1;32mOK[0m
  GET_ROWS(type=q8_0,n=256,m=5,r=4,b=7,v=1): [1;32mOK[0m
  GET_ROWS(type=q2_K,n=256,m=5,r=4,b=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=q2_K,n=256,m=5,r=4,b=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=q2_K,n=256,m=5,r=4,b=7,v=0): not supported [SYCL0] 
  GET_ROWS(type=q2_K,n=256,m=5,r=4,b=7,v=1): not supported [SYCL0] 
  GET_ROWS(type=q3_K,n=256,m=5,r=4,b=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=q3_K,n=256,m=5,r=4,b=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=q3_K,n=256,m=5,r=4,b=7,v=0): not supported [SYCL0] 
  GET_ROWS(type=q3_K,n=256,m=5,r=4,b=7,v=1): not supported [SYCL0] 
  GET_ROWS(type=q4_K,n=256,m=5,r=4,b=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=q4_K,n=256,m=5,r=4,b=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=q4_K,n=256,m=5,r=4,b=7,v=0): not supported [SYCL0] 
  GET_ROWS(type=q4_K,n=256,m=5,r=4,b=7,v=1): not supported [SYCL0] 
  GET_ROWS(type=q5_K,n=256,m=5,r=4,b=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=q5_K,n=256,m=5,r=4,b=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=q5_K,n=256,m=5,r=4,b=7,v=0): not supported [SYCL0] 
  GET_ROWS(type=q5_K,n=256,m=5,r=4,b=7,v=1): not supported [SYCL0] 
  GET_ROWS(type=q6_K,n=256,m=5,r=4,b=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=q6_K,n=256,m=5,r=4,b=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=q6_K,n=256,m=5,r=4,b=7,v=0): not supported [SYCL0] 
  GET_ROWS(type=q6_K,n=256,m=5,r=4,b=7,v=1): not supported [SYCL0] 
  GET_ROWS(type=iq2_xxs,n=256,m=5,r=4,b=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=iq2_xxs,n=256,m=5,r=4,b=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=iq2_xxs,n=256,m=5,r=4,b=7,v=0): not supported [SYCL0] 
  GET_ROWS(type=iq2_xxs,n=256,m=5,r=4,b=7,v=1): not supported [SYCL0] 
  GET_ROWS(type=iq2_xs,n=256,m=5,r=4,b=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=iq2_xs,n=256,m=5,r=4,b=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=iq2_xs,n=256,m=5,r=4,b=7,v=0): not supported [SYCL0] 
  GET_ROWS(type=iq2_xs,n=256,m=5,r=4,b=7,v=1): not supported [SYCL0] 
  GET_ROWS(type=iq2_s,n=256,m=5,r=4,b=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=iq2_s,n=256,m=5,r=4,b=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=iq2_s,n=256,m=5,r=4,b=7,v=0): not supported [SYCL0] 
  GET_ROWS(type=iq2_s,n=256,m=5,r=4,b=7,v=1): not supported [SYCL0] 
  GET_ROWS(type=iq3_xxs,n=256,m=5,r=4,b=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=iq3_xxs,n=256,m=5,r=4,b=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=iq3_xxs,n=256,m=5,r=4,b=7,v=0): not supported [SYCL0] 
  GET_ROWS(type=iq3_xxs,n=256,m=5,r=4,b=7,v=1): not supported [SYCL0] 
  GET_ROWS(type=iq1_s,n=256,m=5,r=4,b=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=iq1_s,n=256,m=5,r=4,b=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=iq1_s,n=256,m=5,r=4,b=7,v=0): not supported [SYCL0] 
  GET_ROWS(type=iq1_s,n=256,m=5,r=4,b=7,v=1): not supported [SYCL0] 
  GET_ROWS(type=iq4_nl,n=256,m=5,r=4,b=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=iq4_nl,n=256,m=5,r=4,b=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=iq4_nl,n=256,m=5,r=4,b=7,v=0): not supported [SYCL0] 
  GET_ROWS(type=iq4_nl,n=256,m=5,r=4,b=7,v=1): not supported [SYCL0] 
  GET_ROWS(type=iq3_s,n=256,m=5,r=4,b=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=iq3_s,n=256,m=5,r=4,b=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=iq3_s,n=256,m=5,r=4,b=7,v=0): not supported [SYCL0] 
  GET_ROWS(type=iq3_s,n=256,m=5,r=4,b=7,v=1): not supported [SYCL0] 
  GET_ROWS(type=iq4_xs,n=256,m=5,r=4,b=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=iq4_xs,n=256,m=5,r=4,b=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=iq4_xs,n=256,m=5,r=4,b=7,v=0): not supported [SYCL0] 
  GET_ROWS(type=iq4_xs,n=256,m=5,r=4,b=7,v=1): not supported [SYCL0] 
  GET_ROWS(type=i32,n=256,m=5,r=4,b=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=i32,n=256,m=5,r=4,b=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=i32,n=256,m=5,r=4,b=7,v=0): not supported [SYCL0] 
  GET_ROWS(type=i32,n=256,m=5,r=4,b=7,v=1): not supported [SYCL0] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=1,s1=1,p0=0,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=1,s1=1,p0=0,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=1,s1=1,p0=1,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=1,s1=1,p0=1,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=1,s1=2,p0=0,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=1,s1=2,p0=0,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=1,s1=2,p0=1,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=1,s1=2,p0=1,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=2,s1=1,p0=0,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=2,s1=1,p0=0,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=2,s1=1,p0=1,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=2,s1=1,p0=1,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=2,s1=2,p0=0,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=2,s1=2,p0=0,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=2,s1=2,p0=1,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=2,s1=2,p0=1,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=1,s1=1,p0=0,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=1,s1=1,p0=0,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=1,s1=1,p0=1,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=1,s1=1,p0=1,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=1,s1=2,p0=0,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=1,s1=2,p0=0,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=1,s1=2,p0=1,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=1,s1=2,p0=1,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=2,s1=1,p0=0,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=2,s1=1,p0=0,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=2,s1=1,p0=1,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=2,s1=1,p0=1,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=2,s1=2,p0=0,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=2,s1=2,p0=0,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=2,s1=2,p0=1,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=2,s1=2,p0=1,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=1,s1=1,p0=0,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=1,s1=1,p0=0,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=1,s1=1,p0=1,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=1,s1=1,p0=1,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=1,s1=2,p0=0,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=1,s1=2,p0=0,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=1,s1=2,p0=1,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=1,s1=2,p0=1,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=2,s1=1,p0=0,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=2,s1=1,p0=0,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=2,s1=1,p0=1,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=2,s1=1,p0=1,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=2,s1=2,p0=0,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=2,s1=2,p0=0,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=2,s1=2,p0=1,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=2,s1=2,p0=1,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=1,s1=1,p0=0,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=1,s1=1,p0=0,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=1,s1=1,p0=1,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=1,s1=1,p0=1,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=1,s1=2,p0=0,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=1,s1=2,p0=0,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=1,s1=2,p0=1,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=1,s1=2,p0=1,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=2,s1=1,p0=0,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=2,s1=1,p0=0,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=2,s1=1,p0=1,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=2,s1=1,p0=1,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=2,s1=2,p0=0,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=2,s1=2,p0=0,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=2,s1=2,p0=1,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=2,s1=2,p0=1,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=1,s1=1,p0=0,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=1,s1=1,p0=0,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=1,s1=1,p0=1,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=1,s1=1,p0=1,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=1,s1=2,p0=0,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=1,s1=2,p0=0,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=1,s1=2,p0=1,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=1,s1=2,p0=1,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=2,s1=1,p0=0,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=2,s1=1,p0=0,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=2,s1=1,p0=1,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=2,s1=1,p0=1,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=2,s1=2,p0=0,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=2,s1=2,p0=0,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=2,s1=2,p0=1,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=2,s1=2,p0=1,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=1,s1=1,p0=0,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=1,s1=1,p0=0,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=1,s1=1,p0=1,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=1,s1=1,p0=1,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=1,s1=2,p0=0,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=1,s1=2,p0=0,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=1,s1=2,p0=1,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=1,s1=2,p0=1,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=2,s1=1,p0=0,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=2,s1=1,p0=0,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=2,s1=1,p0=1,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=2,s1=1,p0=1,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=2,s1=2,p0=0,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=2,s1=2,p0=0,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=2,s1=2,p0=1,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=2,s1=2,p0=1,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=1,s1=1,p0=0,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=1,s1=1,p0=0,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=1,s1=1,p0=1,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=1,s1=1,p0=1,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=1,s1=2,p0=0,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=1,s1=2,p0=0,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=1,s1=2,p0=1,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=1,s1=2,p0=1,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=2,s1=1,p0=0,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=2,s1=1,p0=0,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=2,s1=1,p0=1,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=2,s1=1,p0=1,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=2,s1=2,p0=0,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=2,s1=2,p0=0,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=2,s1=2,p0=1,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=2,s1=2,p0=1,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=1,s1=1,p0=0,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=1,s1=1,p0=0,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=1,s1=1,p0=1,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=1,s1=1,p0=1,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=1,s1=2,p0=0,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=1,s1=2,p0=0,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=1,s1=2,p0=1,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=1,s1=2,p0=1,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=2,s1=1,p0=0,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=2,s1=1,p0=0,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=2,s1=1,p0=1,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=2,s1=1,p0=1,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=2,s1=2,p0=0,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=2,s1=2,p0=0,p1=1): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=2,s1=2,p0=1,p1=0): [1;32mOK[0m
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=2,s1=2,p0=1,p1=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f16,dst_type=f32,ne_input=[10,10,3,1],ne_kernel=[3,3,3,1],s0=1,s1=1,p0=1,p1=1,d0=1,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f16,dst_type=f16,ne_input=[10,10,3,1],ne_kernel=[3,3,3,1],s0=1,s1=1,p0=1,p1=1,d0=1,d1=1,is_2D=1): [1;32mOK[0m
  REPEAT(type=f32,ne=[10,10,10,10],nr=[1,1,1,1]): [1;32mOK[0m
  REPEAT(type=f32,ne=[10,10,10,10],nr=[2,1,1,1]): [1;32mOK[0m
  REPEAT(type=f32,ne=[10,10,10,10],nr=[1,2,1,1]): [1;32mOK[0m
  REPEAT(type=f32,ne=[10,10,10,10],nr=[1,1,2,1]): [1;32mOK[0m
  REPEAT(type=f32,ne=[10,10,10,10],nr=[1,1,1,2]): [1;32mOK[0m
  REPEAT(type=i32,ne=[10,10,10,10],nr=[2,1,1,1]): [1;32mOK[0m
  REPEAT(type=i16,ne=[10,10,10,10],nr=[1,1,1,2]): [1;32mOK[0m
  DUP(type=f32,ne=[10,10,10,1]): [1;32mOK[0m
  DUP(type=f16,ne=[10,10,10,1]): [1;32mOK[0m
  DUP(type=i32,ne=[10,10,10,1]): [1;32mOK[0m
  DUP(type=i16,ne=[10,10,10,1]): [1;32mOK[0m
  DUP(type=i16,ne=[10,8,3,1],permute=[0,2,1,3]): [1;32mOK[0m
  DUP(type=i16,ne=[10,8,3,1],permute=[1,2,0,3]): [1;32mOK[0m
  CPY(type_src=f16,type_dst=f32,ne=[256,4,4,4]): [1;32mOK[0m
  CPY(type_src=f16,type_dst=f16,ne=[256,4,4,4]): [1;32mOK[0m
  CPY(type_src=f16,type_dst=q4_0,ne=[256,4,4,4]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q4_1,ne=[256,4,4,4]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q5_0,ne=[256,4,4,4]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q5_1,ne=[256,4,4,4]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q8_0,ne=[256,4,4,4]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q2_K,ne=[256,4,4,4]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q3_K,ne=[256,4,4,4]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q4_K,ne=[256,4,4,4]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q5_K,ne=[256,4,4,4]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q6_K,ne=[256,4,4,4]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq2_xxs,ne=[256,4,4,4]): not supported [SYCL0] not supported [CPU] 
  CPY(type_src=f16,type_dst=iq2_xs,ne=[256,4,4,4]): not supported [SYCL0] not supported [CPU] 
  CPY(type_src=f16,type_dst=iq2_s,ne=[256,4,4,4]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq3_xxs,ne=[256,4,4,4]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq1_s,ne=[256,4,4,4]): not supported [SYCL0] not supported [CPU] 
  CPY(type_src=f16,type_dst=iq4_nl,ne=[256,4,4,4]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq3_s,ne=[256,4,4,4]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq4_xs,ne=[256,4,4,4]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=f32,ne=[256,4,4,4]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=f16,ne=[256,4,4,4]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=q4_0,ne=[256,4,4,4]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=q4_1,ne=[256,4,4,4]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=q5_0,ne=[256,4,4,4]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=q5_1,ne=[256,4,4,4]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=q8_0,ne=[256,4,4,4]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=q2_K,ne=[256,4,4,4]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=q3_K,ne=[256,4,4,4]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=q4_K,ne=[256,4,4,4]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=q5_K,ne=[256,4,4,4]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=q6_K,ne=[256,4,4,4]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq2_xxs,ne=[256,4,4,4]): not supported [SYCL0] not supported [CPU] 
  CPY(type_src=f32,type_dst=iq2_xs,ne=[256,4,4,4]): not supported [SYCL0] not supported [CPU] 
  CPY(type_src=f32,type_dst=iq2_s,ne=[256,4,4,4]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq3_xxs,ne=[256,4,4,4]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq1_s,ne=[256,4,4,4]): not supported [SYCL0] not supported [CPU] 
  CPY(type_src=f32,type_dst=iq4_nl,ne=[256,4,4,4]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq3_s,ne=[256,4,4,4]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq4_xs,ne=[256,4,4,4]): not supported [SYCL0] 
  CONT(type=f32,ne=[10,10,10,1]): [1;32mOK[0m
  ADD(type=f32,ne=[1,1,8,1],nr=[1,1,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[1,1,8,1],nr=[1,1,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[1,1,8,1],nr=[1,1,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[1,1,1,1],nr=[32,1,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[1,1,1,1],nr=[32,1,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[1,1,1,1],nr=[32,1,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[1,1,320,320],nr=[1,1,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[1,1,320,320],nr=[1,1,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[1,1,320,320],nr=[1,1,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[16,10,1,1],nr=[1,1,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[16,10,1,1],nr=[1,1,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[16,10,1,1],nr=[1,1,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[16,10,10,1],nr=[1,1,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[16,10,10,1],nr=[1,1,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[16,10,10,1],nr=[1,1,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[16,10,10,10],nr=[1,1,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[16,10,10,10],nr=[1,1,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[16,10,10,10],nr=[1,1,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[16,10,10,10],nr=[2,1,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[16,10,10,10],nr=[2,1,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[16,10,10,10],nr=[2,1,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[16,10,10,10],nr=[1,2,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[16,10,10,10],nr=[1,2,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[16,10,10,10],nr=[1,2,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[16,10,10,10],nr=[1,1,2,1]): [1;32mOK[0m
  MUL(type=f32,ne=[16,10,10,10],nr=[1,1,2,1]): [1;32mOK[0m
  DIV(type=f32,ne=[16,10,10,10],nr=[1,1,2,1]): [1;32mOK[0m
  ADD(type=f32,ne=[16,10,10,10],nr=[1,1,1,2]): [1;32mOK[0m
  MUL(type=f32,ne=[16,10,10,10],nr=[1,1,1,2]): [1;32mOK[0m
  DIV(type=f32,ne=[16,10,10,10],nr=[1,1,1,2]): [1;32mOK[0m
  ADD(type=f32,ne=[16,10,10,10],nr=[1,1,2,2]): [1;32mOK[0m
  MUL(type=f32,ne=[16,10,10,10],nr=[1,1,2,2]): [1;32mOK[0m
  DIV(type=f32,ne=[16,10,10,10],nr=[1,1,2,2]): [1;32mOK[0m
  ADD(type=f32,ne=[16,10,10,10],nr=[1,2,2,2]): [1;32mOK[0m
  MUL(type=f32,ne=[16,10,10,10],nr=[1,2,2,2]): [1;32mOK[0m
  DIV(type=f32,ne=[16,10,10,10],nr=[1,2,2,2]): [1;32mOK[0m
  ADD(type=f32,ne=[16,10,10,10],nr=[2,2,2,2]): [1;32mOK[0m
  MUL(type=f32,ne=[16,10,10,10],nr=[2,2,2,2]): [1;32mOK[0m
  DIV(type=f32,ne=[16,10,10,10],nr=[2,2,2,2]): [1;32mOK[0m
  ADD(type=f32,ne=[1280,1,1,1],nr=[1,1,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[1280,1,1,1],nr=[1,1,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[1280,1,1,1],nr=[1,1,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[1280,1,1,1],nr=[1,16,16,1]): [1;32mOK[0m
  MUL(type=f32,ne=[1280,1,1,1],nr=[1,16,16,1]): [1;32mOK[0m
  DIV(type=f32,ne=[1280,1,1,1],nr=[1,16,16,1]): [1;32mOK[0m
  ADD(type=f32,ne=[1280,16,16,1],nr=[1,1,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[1280,16,16,1],nr=[1,1,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[1280,16,16,1],nr=[1,1,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[1280,1,1,1],nr=[1,256,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[1280,1,1,1],nr=[1,256,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[1280,1,1,1],nr=[1,256,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[1,1,1280,1],nr=[16,16,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[1,1,1280,1],nr=[16,16,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[1,1,1280,1],nr=[16,16,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[16,16,1280,1],nr=[1,1,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[16,16,1280,1],nr=[1,1,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[16,16,1280,1],nr=[1,1,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[1,1,1920,1],nr=[16,16,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[1,1,1920,1],nr=[16,16,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[1,1,1920,1],nr=[16,16,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[1,1,2560,1],nr=[16,16,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[1,1,2560,1],nr=[16,16,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[1,1,2560,1],nr=[16,16,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[1,1,1280,1],nr=[32,32,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[1,1,1280,1],nr=[32,32,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[1,1,1280,1],nr=[32,32,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[1,1,1920,1],nr=[32,32,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[1,1,1920,1],nr=[32,32,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[1,1,1920,1],nr=[32,32,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[1,1,640,1],nr=[32,32,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[1,1,640,1],nr=[32,32,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[1,1,640,1],nr=[32,32,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[5120,1,1,1],nr=[1,256,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[5120,1,1,1],nr=[1,256,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[5120,1,1,1],nr=[1,256,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[640,1,1,1],nr=[1,1,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[640,1,1,1],nr=[1,1,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[640,1,1,1],nr=[1,1,1,1]): [1;32mOK[0m
  SCALE(type=f32,ne=[10,10,10,10],scale=2.000000): [1;32mOK[0m
  NORM(type=f32,ne=[64,10,10,10],eps=0.000001): [1;32mOK[0m
  RMS_NORM(type=f32,ne=[64,10,10,10],eps=0.000001): [1;32mOK[0m
  NORM(type=f32,ne=[64,10,10,10],eps=0.000010): [1;32mOK[0m
  RMS_NORM(type=f32,ne=[64,10,10,10],eps=0.000010): [1;32mOK[0m
  NORM(type=f32,ne=[64,10,10,10],eps=0.001000): [1;32mOK[0m
  RMS_NORM(type=f32,ne=[64,10,10,10],eps=0.001000): [1;32mOK[0m
  NORM(type=f32,ne=[64,10,10,10],eps=0.100000): [1;32mOK[0m
  RMS_NORM(type=f32,ne=[64,10,10,10],eps=0.100000): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] 
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] 
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] 
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] 
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] 
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] 
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] 
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] 
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] 
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] 
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] 
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] 
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] 
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] 
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=q5_0,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_0,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_0,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_0,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_0,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_0,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] 
  MUL_MAT(type_a=q5_0,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] 
  MUL_MAT(type_a=q5_0,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_0,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_0,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_0,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_0,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_0,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] 
  MUL_MAT(type_a=q5_0,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] 
  MUL_MAT(type_a=q5_0,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q5_0,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q5_0,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=q5_0,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q5_0,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=q5_0,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=q5_0,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=q5_0,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q5_0,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q5_0,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=q5_0,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q5_0,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=q5_0,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=q5_0,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=q5_1,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_1,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_1,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_1,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_1,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_1,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] 
  MUL_MAT(type_a=q5_1,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] 
  MUL_MAT(type_a=q5_1,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_1,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_1,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_1,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_1,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_1,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] 
  MUL_MAT(type_a=q5_1,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] 
  MUL_MAT(type_a=q5_1,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q5_1,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q5_1,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=q5_1,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q5_1,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=q5_1,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=q5_1,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=q5_1,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q5_1,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q5_1,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=q5_1,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q5_1,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=q5_1,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=q5_1,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] 
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] 
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] 
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=q2_K,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q2_K,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q2_K,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q2_K,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q2_K,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q2_K,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] 
  MUL_MAT(type_a=q2_K,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] 
  MUL_MAT(type_a=q2_K,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q2_K,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q2_K,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q2_K,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q2_K,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q2_K,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] 
  MUL_MAT(type_a=q2_K,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] 
  MUL_MAT(type_a=q2_K,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q2_K,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q2_K,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=q2_K,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q2_K,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=q2_K,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=q2_K,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=q2_K,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q2_K,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q2_K,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=q2_K,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q2_K,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=q2_K,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=q2_K,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=q3_K,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q3_K,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q3_K,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q3_K,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q3_K,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q3_K,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] 
  MUL_MAT(type_a=q3_K,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] 
  MUL_MAT(type_a=q3_K,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q3_K,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q3_K,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q3_K,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q3_K,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q3_K,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] 
  MUL_MAT(type_a=q3_K,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] 
  MUL_MAT(type_a=q3_K,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q3_K,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q3_K,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=q3_K,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q3_K,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=q3_K,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=q3_K,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=q3_K,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q3_K,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q3_K,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=q3_K,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q3_K,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=q3_K,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=q3_K,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] 
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] 
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] 
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=q5_K,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_K,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_K,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_K,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_K,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_K,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] 
  MUL_MAT(type_a=q5_K,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] 
  MUL_MAT(type_a=q5_K,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_K,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_K,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_K,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_K,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_K,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] 
  MUL_MAT(type_a=q5_K,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] 
  MUL_MAT(type_a=q5_K,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q5_K,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q5_K,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=q5_K,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q5_K,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=q5_K,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=q5_K,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=q5_K,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q5_K,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q5_K,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=q5_K,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q5_K,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=q5_K,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=q5_K,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=q6_K,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q6_K,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q6_K,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q6_K,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q6_K,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q6_K,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] 
  MUL_MAT(type_a=q6_K,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] 
  MUL_MAT(type_a=q6_K,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q6_K,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q6_K,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q6_K,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q6_K,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q6_K,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] 
  MUL_MAT(type_a=q6_K,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] 
  MUL_MAT(type_a=q6_K,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q6_K,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q6_K,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=q6_K,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q6_K,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=q6_K,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=q6_K,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=q6_K,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q6_K,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q6_K,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=q6_K,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=q6_K,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=q6_K,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=q6_K,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): GGML_ASSERT: /home/jianyuzh/ws/llama.cpp/llama.cpp_ci/llama.cpp/ggml-sycl.cpp:14025: false
[New LWP 1745982]
[New LWP 1745983]
[New LWP 1745986]
[New LWP 1745987]
[New LWP 1745988]
[New LWP 1745989]
[New LWP 1745990]
[New LWP 1745991]
[New LWP 1745992]
[New LWP 1745993]
[New LWP 1745994]
[New LWP 1745995]
[New LWP 1745996]
[New LWP 1745997]
[New LWP 1745998]
[New LWP 1745999]
[New LWP 1746000]
[New LWP 1746001]
[New LWP 1746002]
[New LWP 1746003]
[New LWP 1746004]
[New LWP 1746005]
[New LWP 1746006]
[New LWP 1746007]
[New LWP 1746008]
[New LWP 1746009]
[New LWP 1746010]
[New LWP 1746011]
[New LWP 1746012]
[New LWP 1746013]
[New LWP 1746014]
[New LWP 1746015]
[New LWP 1746016]
[New LWP 1786714]
warning: File "/opt/intel/oneapi/compiler/2024.1/lib/libsycl.so.7.1.0-gdb.py" auto-loading has been declined by your `auto-load safe-path' set to "$debugdir:$datadir/auto-load".
To enable execution of this file add
	add-auto-load-safe-path /opt/intel/oneapi/compiler/2024.1/lib/libsycl.so.7.1.0-gdb.py
line to your configuration file "/home/jianyuzh/.config/gdb/gdbinit".
To completely disable this security protection add
	set auto-load safe-path /
line to your configuration file "/home/jianyuzh/.config/gdb/gdbinit".
For more information about this security protection see the
"Auto-loading safe path" section in the GDB manual.  E.g., run from the shell:
	info "(gdb)Auto-loading safe path"
[Thread debugging using libthread_db enabled]
Using host libthread_db library "/lib/x86_64-linux-gnu/libthread_db.so.1".
0x00007f900b8ea42f in __GI___wait4 (pid=1806896, stat_loc=0x0, options=0, usage=0x0) at ../sysdeps/unix/sysv/linux/wait4.c:30
30	../sysdeps/unix/sysv/linux/wait4.c: No such file or directory.
#0  0x00007f900b8ea42f in __GI___wait4 (pid=1806896, stat_loc=0x0, options=0, usage=0x0) at ../sysdeps/unix/sysv/linux/wait4.c:30
30	in ../sysdeps/unix/sysv/linux/wait4.c
#1  0x000000000046a5db in ggml_print_backtrace ()
#2  0x00000000005c35b9 in ggml_sycl_op_dequantize_mul_mat_vec(ggml_tensor const*, ggml_tensor const*, ggml_tensor*, char const*, float const*, char const*, float*, long, long, long, long, sycl::_V1::queue* const&) ()
#3  0x00000000005305de in ggml_sycl_op_mul_mat(ggml_tensor const*, ggml_tensor const*, ggml_tensor*, void (*)(ggml_tensor const*, ggml_tensor const*, ggml_tensor*, char const*, float const*, char const*, float*, long, long, long, long, sycl::_V1::queue* const&), bool) ()
#4  0x00000000004f4ffd in ggml_sycl_compute_forward ()
#5  0x00000000005b26be in ggml_backend_sycl_graph_compute(ggml_backend*, ggml_cgraph*) ()
#6  0x00000000004bbcb2 in ggml_backend_compare_graph_backend ()
#7  0x000000000041cd1f in test_case::eval(ggml_backend*, ggml_backend*, char const*) ()
#8  0x000000000041895d in test_backend(ggml_backend*, test_mode, char const*) ()
#9  0x000000000040dc86 in main ()
[Inferior 1 (process 1745981) detached]

      Start 21: test-rope
21/22 Test #21: test-rope ...........................   Passed    0.14 sec
      Start 24: test-json-schema-to-grammar
22/22 Test #24: test-json-schema-to-grammar .........   Passed    0.03 sec

95% tests passed, 1 tests failed out of 22

Label Time Summary:
main    =  26.95 sec*proc (22 tests)

Total Test time (real) =  26.96 sec

The following tests FAILED:
	 20 - test-backend-ops (Subprocess aborted)
Errors while running CTest

real	0m26.958s
user	0m31.804s
sys	0m3.660s
```
