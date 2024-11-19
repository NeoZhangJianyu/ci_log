### ctest_release

Runs ctest in release mode
- status: 8
```
+ ctest --output-on-failure -L main
Test project /home/jianyuzh/ws/llama.cpp/llama.cpp_ci/arthw-llama.cpp/build-ci-release
      Start  1: test-tokenizer-0-bert-bge
 1/26 Test  #1: test-tokenizer-0-bert-bge .........   Passed    0.04 sec
      Start  2: test-tokenizer-0-command-r
 2/26 Test  #2: test-tokenizer-0-command-r ........   Passed    0.35 sec
      Start  3: test-tokenizer-0-deepseek-coder
 3/26 Test  #3: test-tokenizer-0-deepseek-coder ...   Passed    0.07 sec
      Start  4: test-tokenizer-0-deepseek-llm
 4/26 Test  #4: test-tokenizer-0-deepseek-llm .....   Passed    0.15 sec
      Start  5: test-tokenizer-0-falcon
 5/26 Test  #5: test-tokenizer-0-falcon ...........   Passed    0.09 sec
      Start  6: test-tokenizer-0-gpt-2
 6/26 Test  #6: test-tokenizer-0-gpt-2 ............   Passed    0.07 sec
      Start  7: test-tokenizer-0-llama-bpe
 7/26 Test  #7: test-tokenizer-0-llama-bpe ........   Passed    0.26 sec
      Start  8: test-tokenizer-0-llama-spm
 8/26 Test  #8: test-tokenizer-0-llama-spm ........   Passed    0.04 sec
      Start  9: test-tokenizer-0-mpt
 9/26 Test  #9: test-tokenizer-0-mpt ..............   Passed    0.08 sec
      Start 10: test-tokenizer-0-phi-3
10/26 Test #10: test-tokenizer-0-phi-3 ............   Passed    0.04 sec
      Start 11: test-tokenizer-0-qwen2
11/26 Test #11: test-tokenizer-0-qwen2 ............   Passed    0.20 sec
      Start 12: test-tokenizer-0-refact
12/26 Test #12: test-tokenizer-0-refact ...........   Passed    0.07 sec
      Start 13: test-tokenizer-0-starcoder
13/26 Test #13: test-tokenizer-0-starcoder ........   Passed    0.08 sec
      Start 14: test-tokenizer-1-llama-spm
14/26 Test #14: test-tokenizer-1-llama-spm ........   Passed    0.11 sec
      Start 15: test-arg-parser
15/26 Test #15: test-arg-parser ...................   Passed    0.03 sec
      Start 16: test-quantize-fns
16/26 Test #16: test-quantize-fns .................   Passed   10.19 sec
      Start 17: test-quantize-perf
17/26 Test #17: test-quantize-perf ................   Passed    2.86 sec
      Start 18: test-sampling
18/26 Test #18: test-sampling .....................   Passed    0.03 sec
      Start 19: test-chat-template
19/26 Test #19: test-chat-template ................   Passed    0.03 sec
      Start 20: test-grammar-parser
20/26 Test #20: test-grammar-parser ...............   Passed    0.03 sec
      Start 21: test-llama-grammar
21/26 Test #21: test-llama-grammar ................   Passed    0.03 sec
      Start 22: test-grammar-integration
22/26 Test #22: test-grammar-integration ..........   Passed    0.04 sec
      Start 23: test-grad0
23/26 Test #23: test-grad0 ........................   Passed    0.22 sec
      Start 24: test-backend-ops
24/26 Test #24: test-backend-ops ..................***Failed   20.78 sec
[SYCL] call ggml_init_sycl
ggml_sycl_init: GGML_SYCL_DEBUG: 0
ggml_sycl_init: GGML_SYCL_F16: yes
ggml_sycl_init: GGML_SYCL_FORCE_MMQ:   no
ggml_sycl_init: SYCL_USE_XMX: yes
found 1 SYCL devices:
Part1:
|ID|        Device Type| Ver|                                   Name|Global mem size|
|--|-------------------|----|---------------------------------------|---------------|
| 0| [level_zero:gpu:0]|12.55|                Intel Arc A770 Graphics|         16225M|

Part2:
|ID|Max compute units|Max work group|Max subgroup|                    Driver version|
|--|-----------------|--------------|------------|----------------------------------|
| 0|              512|          1024|          32|                      1.3.29735+27|
detect 1 SYCL devices:[0] by ONEAPI_DEVICE_SELECTOR=level_zero:0
Testing 2 backends

Backend 1/2 (CPU)
  Skipping CPU backend
Backend 2/2 (SYCL0)
  Backend name: SYCL0
  ABS(type=f32,ne_a=[128,2,2,2],v=0): not supported [SYCL0] 
  ABS(type=f32,ne_a=[5,7,11,13],v=0): not supported [SYCL0] 
  SGN(type=f32,ne_a=[128,2,2,2],v=0): not supported [SYCL0] 
  SGN(type=f32,ne_a=[5,7,11,13],v=0): not supported [SYCL0] 
  NEG(type=f32,ne_a=[128,2,2,2],v=0): not supported [SYCL0] 
  NEG(type=f32,ne_a=[5,7,11,13],v=0): not supported [SYCL0] 
  STEP(type=f32,ne_a=[128,2,2,2],v=0): not supported [SYCL0] 
  STEP(type=f32,ne_a=[5,7,11,13],v=0): not supported [SYCL0] 
  TANH(type=f32,ne_a=[128,2,2,2],v=0): [1;32mOK[0m
  TANH(type=f32,ne_a=[5,7,11,13],v=0): [1;32mOK[0m
  ELU(type=f32,ne_a=[128,2,2,2],v=0): not supported [SYCL0] 
  ELU(type=f32,ne_a=[5,7,11,13],v=0): not supported [SYCL0] 
  RELU(type=f32,ne_a=[128,2,2,2],v=0): [1;32mOK[0m
  RELU(type=f32,ne_a=[5,7,11,13],v=0): [1;32mOK[0m
  SIGMOID(type=f32,ne_a=[128,2,2,2],v=0): not supported [SYCL0] 
  SIGMOID(type=f32,ne_a=[5,7,11,13],v=0): not supported [SYCL0] 
  GELU(type=f32,ne_a=[128,2,2,2],v=0): [1;32mOK[0m
  GELU(type=f32,ne_a=[5,7,11,13],v=0): [1;32mOK[0m
  GELU_QUICK(type=f32,ne_a=[128,2,2,2],v=0): [1;32mOK[0m
  GELU_QUICK(type=f32,ne_a=[5,7,11,13],v=0): [1;32mOK[0m
  SILU(type=f32,ne_a=[128,2,2,2],v=0): [1;32mOK[0m
  SILU(type=f32,ne_a=[5,7,11,13],v=0): [1;32mOK[0m
  HARDSWISH(type=f32,ne_a=[128,2,2,2],v=0): [1;32mOK[0m
  HARDSWISH(type=f32,ne_a=[5,7,11,13],v=0): [1;32mOK[0m
  HARDSIGMOID(type=f32,ne_a=[128,2,2,2],v=0): [1;32mOK[0m
  HARDSIGMOID(type=f32,ne_a=[5,7,11,13],v=0): [1;32mOK[0m
  EXP(type=f32,ne_a=[128,2,2,2],v=0): not supported [SYCL0] 
  EXP(type=f32,ne_a=[5,7,11,13],v=0): not supported [SYCL0] 
  ABS(type=f32,ne_a=[128,2,2,2],v=1): not supported [SYCL0] 
  ABS(type=f32,ne_a=[5,7,11,13],v=1): not supported [SYCL0] 
  SGN(type=f32,ne_a=[128,2,2,2],v=1): not supported [SYCL0] 
  SGN(type=f32,ne_a=[5,7,11,13],v=1): not supported [SYCL0] 
  NEG(type=f32,ne_a=[128,2,2,2],v=1): not supported [SYCL0] 
  NEG(type=f32,ne_a=[5,7,11,13],v=1): not supported [SYCL0] 
  STEP(type=f32,ne_a=[128,2,2,2],v=1): not supported [SYCL0] 
  STEP(type=f32,ne_a=[5,7,11,13],v=1): not supported [SYCL0] 
  TANH(type=f32,ne_a=[128,2,2,2],v=1): not supported [SYCL0] 
  TANH(type=f32,ne_a=[5,7,11,13],v=1): not supported [SYCL0] 
  ELU(type=f32,ne_a=[128,2,2,2],v=1): not supported [SYCL0] 
  ELU(type=f32,ne_a=[5,7,11,13],v=1): not supported [SYCL0] 
  RELU(type=f32,ne_a=[128,2,2,2],v=1): not supported [SYCL0] 
  RELU(type=f32,ne_a=[5,7,11,13],v=1): not supported [SYCL0] 
  SIGMOID(type=f32,ne_a=[128,2,2,2],v=1): not supported [SYCL0] 
  SIGMOID(type=f32,ne_a=[5,7,11,13],v=1): not supported [SYCL0] 
  GELU(type=f32,ne_a=[128,2,2,2],v=1): not supported [SYCL0] 
  GELU(type=f32,ne_a=[5,7,11,13],v=1): not supported [SYCL0] 
  GELU_QUICK(type=f32,ne_a=[128,2,2,2],v=1): not supported [SYCL0] 
  GELU_QUICK(type=f32,ne_a=[5,7,11,13],v=1): not supported [SYCL0] 
  SILU(type=f32,ne_a=[128,2,2,2],v=1): not supported [SYCL0] 
  SILU(type=f32,ne_a=[5,7,11,13],v=1): not supported [SYCL0] 
  HARDSWISH(type=f32,ne_a=[128,2,2,2],v=1): not supported [SYCL0] 
  HARDSWISH(type=f32,ne_a=[5,7,11,13],v=1): not supported [SYCL0] 
  HARDSIGMOID(type=f32,ne_a=[128,2,2,2],v=1): not supported [SYCL0] 
  HARDSIGMOID(type=f32,ne_a=[5,7,11,13],v=1): not supported [SYCL0] 
  EXP(type=f32,ne_a=[128,2,2,2],v=1): not supported [SYCL0] 
  EXP(type=f32,ne_a=[5,7,11,13],v=1): not supported [SYCL0] 
  GET_ROWS(type=f32,n=1,m=8,r=2,b=1,v=0): [1;32mOK[0m
  GET_ROWS(type=f32,n=256,m=5,r=4,b=1,v=0): [1;32mOK[0m
  GET_ROWS(type=f32,n=256,m=5,r=4,b=1,v=1): [1;32mOK[0m
  GET_ROWS(type=f32,n=256,m=5,r=4,b=7,v=0): [1;32mOK[0m
  GET_ROWS(type=f32,n=256,m=5,r=4,b=7,v=1): [1;32mOK[0m
  GET_ROWS(type=f16,n=256,m=5,r=4,b=1,v=0): [1;32mOK[0m
  GET_ROWS(type=f16,n=256,m=5,r=4,b=1,v=1): [1;32mOK[0m
  GET_ROWS(type=f16,n=256,m=5,r=4,b=7,v=0): [1;32mOK[0m
  GET_ROWS(type=f16,n=256,m=5,r=4,b=7,v=1): [1;32mOK[0m
  GET_ROWS(type=bf16,n=256,m=5,r=4,b=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=bf16,n=256,m=5,r=4,b=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=bf16,n=256,m=5,r=4,b=7,v=0): not supported [SYCL0] 
  GET_ROWS(type=bf16,n=256,m=5,r=4,b=7,v=1): not supported [SYCL0] 
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
  GET_ROWS(type=iq1_m,n=256,m=5,r=4,b=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=iq1_m,n=256,m=5,r=4,b=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=iq1_m,n=256,m=5,r=4,b=7,v=0): not supported [SYCL0] 
  GET_ROWS(type=iq1_m,n=256,m=5,r=4,b=7,v=1): not supported [SYCL0] 
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
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[10,10,3,1],ne_kernel=[3,3,3,1],s0=1,s1=1,p0=1,p1=1,d0=1,d1=1,is_2D=1): not supported [SYCL0] 
  IM2COL(type_input=f32,type_kernel=f16,dst_type=f32,ne_input=[10,10,3,1],ne_kernel=[3,3,3,1],s0=1,s1=1,p0=1,p1=1,d0=1,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f16,dst_type=f16,ne_input=[10,10,3,1],ne_kernel=[3,3,3,1],s0=1,s1=1,p0=1,p1=1,d0=1,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[3000,128,1,1],ne_kernel=[3,128,1280,1],s0=1,s1=0,p0=1,p1=0,d0=1,d1=0,is_2D=0): not supported [SYCL0] 
  IM2COL(type_input=f32,type_kernel=f16,dst_type=f32,ne_input=[3000,128,1,1],ne_kernel=[3,128,1280,1],s0=1,s1=0,p0=1,p1=0,d0=1,d1=0,is_2D=0): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f16,dst_type=f16,ne_input=[3000,128,1,1],ne_kernel=[3,128,1280,1],s0=1,s1=0,p0=1,p1=0,d0=1,d1=0,is_2D=0): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[197,32,1,1],ne_kernel=[16,32,32,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[3,2,1,1],ne_kernel=[2,3,2,1],s0=3,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[3,2,1,1],ne_kernel=[2,3,2,1],s0=2,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[3,2,1,1],ne_kernel=[2,3,2,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[3,2,1,1],ne_kernel=[3,2,2,1],s0=2,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[3,2,1,1],ne_kernel=[3,2,2,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[3,2,1,1],ne_kernel=[3,1,2,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[2,1,1,1],ne_kernel=[3,1,1,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  REPEAT(type=f32,ne=[10,5,4,3],nr=[1,1,1,1]): [1;32mOK[0m
  REPEAT(type=f32,ne=[10,5,4,3],nr=[2,1,1,1]): [1;32mOK[0m
  REPEAT(type=f32,ne=[10,5,4,3],nr=[1,2,1,1]): [1;32mOK[0m
  REPEAT(type=f32,ne=[10,5,4,3],nr=[1,1,2,1]): [1;32mOK[0m
  REPEAT(type=f32,ne=[10,5,4,3],nr=[1,1,1,2]): [1;32mOK[0m
  REPEAT(type=i32,ne=[10,5,4,3],nr=[2,1,1,1]): [1;32mOK[0m
  REPEAT(type=i16,ne=[10,5,4,3],nr=[1,1,1,2]): [1;32mOK[0m
  DUP(type=f32,ne=[10,10,20,1]): [1;32mOK[0m
  DUP(type=f16,ne=[10,10,20,1]): [1;32mOK[0m
  DUP(type=i32,ne=[10,10,20,1]): [1;32mOK[0m
  DUP(type=i16,ne=[10,10,20,1]): [1;32mOK[0m
  DUP(type=f32,ne=[10,10,5,1],permute=[0,2,1,3]): [1;32mOK[0m
  DUP(type=f16,ne=[10,10,5,1],permute=[0,2,1,3]): [1;32mOK[0m
  DUP(type=f32,ne=[10,10,5,1],permute=[1,0,2,3]): [1;32mOK[0m
  DUP(type=f16,ne=[10,10,5,1],permute=[1,0,2,3]): [1;32mOK[0m
  DUP(type=i16,ne=[10,8,3,1],permute=[0,2,1,3]): [1;32mOK[0m
  DUP(type=i16,ne=[10,8,3,1],permute=[1,2,0,3]): [1;32mOK[0m
  SET(type_src=f32,type_dst=f32,ne=[6,5,4,3],dim=1): not supported [SYCL0] 
  SET(type_src=f32,type_dst=f32,ne=[6,5,4,3],dim=2): not supported [SYCL0] 
  SET(type_src=f32,type_dst=f32,ne=[6,5,4,3],dim=3): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=f32,ne=[256,4,4,4],permute=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=f16,type_dst=f32,ne=[256,2,3,4],permute=[0,2,1,3]): [1;32mOK[0m
  CPY(type_src=f16,type_dst=f16,ne=[256,4,4,4],permute=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=f16,type_dst=f16,ne=[256,2,3,4],permute=[0,2,1,3]): [1;32mOK[0m
  CPY(type_src=f16,type_dst=bf16,ne=[256,4,4,4],permute=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=bf16,ne=[256,2,3,4],permute=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q4_0,ne=[256,4,4,4],permute=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q4_0,ne=[256,2,3,4],permute=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q4_1,ne=[256,4,4,4],permute=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q4_1,ne=[256,2,3,4],permute=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q5_0,ne=[256,4,4,4],permute=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q5_0,ne=[256,2,3,4],permute=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q5_1,ne=[256,4,4,4],permute=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q5_1,ne=[256,2,3,4],permute=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q8_0,ne=[256,4,4,4],permute=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q8_0,ne=[256,2,3,4],permute=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q2_K,ne=[256,4,4,4],permute=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q2_K,ne=[256,2,3,4],permute=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q3_K,ne=[256,4,4,4],permute=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q3_K,ne=[256,2,3,4],permute=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q4_K,ne=[256,4,4,4],permute=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q4_K,ne=[256,2,3,4],permute=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q5_K,ne=[256,4,4,4],permute=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q5_K,ne=[256,2,3,4],permute=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q6_K,ne=[256,4,4,4],permute=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q6_K,ne=[256,2,3,4],permute=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq2_xxs,ne=[256,4,4,4],permute=[0,0,0,0]): not supported [SYCL0] not supported [CPU] 
  CPY(type_src=f16,type_dst=iq2_xxs,ne=[256,2,3,4],permute=[0,2,1,3]): not supported [SYCL0] not supported [CPU] 
  CPY(type_src=f16,type_dst=iq2_xs,ne=[256,4,4,4],permute=[0,0,0,0]): not supported [SYCL0] not supported [CPU] 
  CPY(type_src=f16,type_dst=iq2_xs,ne=[256,2,3,4],permute=[0,2,1,3]): not supported [SYCL0] not supported [CPU] 
  CPY(type_src=f16,type_dst=iq2_s,ne=[256,4,4,4],permute=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq2_s,ne=[256,2,3,4],permute=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq3_xxs,ne=[256,4,4,4],permute=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq3_xxs,ne=[256,2,3,4],permute=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq1_s,ne=[256,4,4,4],permute=[0,0,0,0]): not supported [SYCL0] not supported [CPU] 
  CPY(type_src=f16,type_dst=iq1_s,ne=[256,2,3,4],permute=[0,2,1,3]): not supported [SYCL0] not supported [CPU] 
  CPY(type_src=f16,type_dst=iq1_m,ne=[256,4,4,4],permute=[0,0,0,0]): not supported [SYCL0] not supported [CPU] 
  CPY(type_src=f16,type_dst=iq1_m,ne=[256,2,3,4],permute=[0,2,1,3]): not supported [SYCL0] not supported [CPU] 
  CPY(type_src=f16,type_dst=iq4_nl,ne=[256,4,4,4],permute=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq4_nl,ne=[256,2,3,4],permute=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq3_s,ne=[256,4,4,4],permute=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq3_s,ne=[256,2,3,4],permute=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq4_xs,ne=[256,4,4,4],permute=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq4_xs,ne=[256,2,3,4],permute=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=f32,ne=[256,4,4,4],permute=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=f32,ne=[256,2,3,4],permute=[0,2,1,3]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=f16,ne=[256,4,4,4],permute=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=f16,ne=[256,2,3,4],permute=[0,2,1,3]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=bf16,ne=[256,4,4,4],permute=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=bf16,ne=[256,2,3,4],permute=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=q4_0,ne=[256,4,4,4],permute=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=q4_0,ne=[256,2,3,4],permute=[0,2,1,3]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=q4_1,ne=[256,4,4,4],permute=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=q4_1,ne=[256,2,3,4],permute=[0,2,1,3]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=q5_0,ne=[256,4,4,4],permute=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=q5_0,ne=[256,2,3,4],permute=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=q5_1,ne=[256,4,4,4],permute=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=q5_1,ne=[256,2,3,4],permute=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=q8_0,ne=[256,4,4,4],permute=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=q8_0,ne=[256,2,3,4],permute=[0,2,1,3]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=q2_K,ne=[256,4,4,4],permute=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=q2_K,ne=[256,2,3,4],permute=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=q3_K,ne=[256,4,4,4],permute=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=q3_K,ne=[256,2,3,4],permute=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=q4_K,ne=[256,4,4,4],permute=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=q4_K,ne=[256,2,3,4],permute=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=q5_K,ne=[256,4,4,4],permute=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=q5_K,ne=[256,2,3,4],permute=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=q6_K,ne=[256,4,4,4],permute=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=q6_K,ne=[256,2,3,4],permute=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq2_xxs,ne=[256,4,4,4],permute=[0,0,0,0]): not supported [SYCL0] not supported [CPU] 
  CPY(type_src=f32,type_dst=iq2_xxs,ne=[256,2,3,4],permute=[0,2,1,3]): not supported [SYCL0] not supported [CPU] 
  CPY(type_src=f32,type_dst=iq2_xs,ne=[256,4,4,4],permute=[0,0,0,0]): not supported [SYCL0] not supported [CPU] 
  CPY(type_src=f32,type_dst=iq2_xs,ne=[256,2,3,4],permute=[0,2,1,3]): not supported [SYCL0] not supported [CPU] 
  CPY(type_src=f32,type_dst=iq2_s,ne=[256,4,4,4],permute=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq2_s,ne=[256,2,3,4],permute=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq3_xxs,ne=[256,4,4,4],permute=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq3_xxs,ne=[256,2,3,4],permute=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq1_s,ne=[256,4,4,4],permute=[0,0,0,0]): not supported [SYCL0] not supported [CPU] 
  CPY(type_src=f32,type_dst=iq1_s,ne=[256,2,3,4],permute=[0,2,1,3]): not supported [SYCL0] not supported [CPU] 
  CPY(type_src=f32,type_dst=iq1_m,ne=[256,4,4,4],permute=[0,0,0,0]): not supported [SYCL0] not supported [CPU] 
  CPY(type_src=f32,type_dst=iq1_m,ne=[256,2,3,4],permute=[0,2,1,3]): not supported [SYCL0] not supported [CPU] 
  CPY(type_src=f32,type_dst=iq4_nl,ne=[256,4,4,4],permute=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq4_nl,ne=[256,2,3,4],permute=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq3_s,ne=[256,4,4,4],permute=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq3_s,ne=[256,2,3,4],permute=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq4_xs,ne=[256,4,4,4],permute=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq4_xs,ne=[256,2,3,4],permute=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=f16,ne=[256,2,3,4],permute=[1,0,2,3]): [1;32mOK[0m
  CPY(type_src=f16,type_dst=f32,ne=[256,2,3,4],permute=[1,0,2,3]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=f16,ne=[256,2,3,4],permute=[1,0,2,3]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=f32,ne=[256,2,3,4],permute=[1,0,2,3]): [1;32mOK[0m
  CONT(type=f32,ne=[10,10,10,1]): [1;32mOK[0m
  CONT(type=f32,ne=[2,1,1,1]): [1;32mOK[0m
  CONT(type=f32,ne=[2,1,3,5]): [1;32mOK[0m
  CONT(type=f32,ne=[2,3,5,7]): [1;32mOK[0m
  CONT(type=f16,ne=[2,1,1,1]): [1;32mOK[0m
  CONT(type=f16,ne=[2,1,3,5]): [1;32mOK[0m
  CONT(type=f16,ne=[2,3,5,7]): [1;32mOK[0m
  CONT(type=bf16,ne=[2,1,1,1]): not supported [SYCL0] 
  CONT(type=bf16,ne=[2,1,3,5]): not supported [SYCL0] 
  CONT(type=bf16,ne=[2,3,5,7]): not supported [SYCL0] 
  ADD(type=f32,ne=[1,1,8,1],nr=[1,1,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[1,1,8,1],nr=[1,1,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[1,1,8,1],nr=[1,1,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[1,1,1,1],nr=[32,1,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[1,1,1,1],nr=[32,1,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[1,1,1,1],nr=[32,1,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[1,1,320,320],nr=[1,1,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[1,1,320,320],nr=[1,1,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[1,1,320,320],nr=[1,1,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[10,5,1,1],nr=[1,1,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[10,5,1,1],nr=[1,1,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[10,5,1,1],nr=[1,1,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[10,5,4,1],nr=[1,1,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[10,5,4,1],nr=[1,1,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[10,5,4,1],nr=[1,1,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[10,5,4,3],nr=[1,1,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[10,5,4,3],nr=[1,1,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[10,5,4,3],nr=[1,1,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[10,5,4,3],nr=[2,1,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[10,5,4,3],nr=[2,1,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[10,5,4,3],nr=[2,1,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[10,5,4,3],nr=[1,2,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[10,5,4,3],nr=[1,2,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[10,5,4,3],nr=[1,2,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[10,5,4,3],nr=[1,1,2,1]): [1;32mOK[0m
  MUL(type=f32,ne=[10,5,4,3],nr=[1,1,2,1]): [1;32mOK[0m
  DIV(type=f32,ne=[10,5,4,3],nr=[1,1,2,1]): [1;32mOK[0m
  ADD(type=f32,ne=[10,5,4,3],nr=[1,1,1,2]): [1;32mOK[0m
  MUL(type=f32,ne=[10,5,4,3],nr=[1,1,1,2]): [1;32mOK[0m
  DIV(type=f32,ne=[10,5,4,3],nr=[1,1,1,2]): [1;32mOK[0m
  ADD(type=f32,ne=[10,5,4,3],nr=[1,1,2,2]): [1;32mOK[0m
  MUL(type=f32,ne=[10,5,4,3],nr=[1,1,2,2]): [1;32mOK[0m
  DIV(type=f32,ne=[10,5,4,3],nr=[1,1,2,2]): [1;32mOK[0m
  ADD(type=f32,ne=[10,5,4,3],nr=[1,2,2,2]): [1;32mOK[0m
  MUL(type=f32,ne=[10,5,4,3],nr=[1,2,2,2]): [1;32mOK[0m
  DIV(type=f32,ne=[10,5,4,3],nr=[1,2,2,2]): [1;32mOK[0m
  ADD(type=f32,ne=[10,5,4,3],nr=[2,2,2,2]): [1;32mOK[0m
  MUL(type=f32,ne=[10,5,4,3],nr=[2,2,2,2]): [1;32mOK[0m
  DIV(type=f32,ne=[10,5,4,3],nr=[2,2,2,2]): [1;32mOK[0m
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
  ADD1(type=f32,ne=[10,5,4,3]): not supported [SYCL0] 
  SCALE(type=f32,ne=[10,10,10,10],scale=2.000000): [1;32mOK[0m
  NORM(type=f32,ne=[64,5,4,3],eps=0.000001): [1;32mOK[0m
  RMS_NORM(type=f32,ne=[64,5,4,3],eps=0.000001): [1;32mOK[0m
  NORM(type=f32,ne=[64,5,4,3],eps=0.000010): [1;32mOK[0m
  RMS_NORM(type=f32,ne=[64,5,4,3],eps=0.000010): [1;32mOK[0m
  NORM(type=f32,ne=[64,5,4,3],eps=0.001000): [1;32mOK[0m
  RMS_NORM(type=f32,ne=[64,5,4,3],eps=0.001000): [1;32mOK[0m
  NORM(type=f32,ne=[64,5,4,3],eps=0.100000): [1;32mOK[0m
  RMS_NORM(type=f32,ne=[64,5,4,3],eps=0.100000): [1;32mOK[0m
  SSM_CONV(type=f32,ne_a=[4,1536,1,1],ne_b=[4,1536,1,1]): not supported [SYCL0] 
  SSM_CONV(type=f32,ne_a=[8,1536,1,1],ne_b=[4,1536,1,1]): not supported [SYCL0] 
  SSM_CONV(type=f32,ne_a=[4,1536,4,1],ne_b=[4,1536,1,1]): not supported [SYCL0] 
  SSM_SCAN(type=f32,d_state=16,d_inner=1024,n_seq_tokens=32,n_seqs=4): not supported [SYCL0] 
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
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): not supported [SYCL0] not supported [CPU] 
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=1,k=32,bs=[1,1],nr=[1,1]): [MUL_MAT] NMSE = 0.926813441 > 0.000500000 [1;31mFAIL[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_0,type_b=f32,m=16,n=1,k=32,bs=[1,1],nr=[1,1]): [MUL_MAT] NMSE = 0.351352522 > 0.000500000 [1;31mFAIL[0m
  MUL_MAT(type_a=q5_0,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_1,type_b=f32,m=16,n=1,k=32,bs=[1,1],nr=[1,1]): [MUL_MAT] NMSE = 0.645704928 > 0.000500000 [1;31mFAIL[0m
  MUL_MAT(type_a=q5_1,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=1,k=32,bs=[1,1],nr=[1,1]): [MUL_MAT] NMSE = 0.518161512 > 0.000500000 [1;31mFAIL[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q2_K,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q3_K,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_K,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q6_K,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xs,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_s,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq3_xxs,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq1_s,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq1_m,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq4_nl,type_b=f32,m=16,n=1,k=32,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq4_nl,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq3_s,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq4_xs,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=bf16,type_b=f32,m=16,n=1,k=1,bs=[1,1],nr=[1,1]): not supported [SYCL0] 
  MUL_MAT(type_a=bf16,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): not supported [SYCL0] 
  MUL_MAT(type_a=f16,type_b=f32,m=64,n=2,k=128,bs=[8,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=83,n=2,k=128,bs=[8,1],nr=[4,1]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=64,n=2,k=64,bs=[8,1],nr=[4,1]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=83,n=2,k=64,bs=[8,1],nr=[4,1]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=64,n=45,k=128,bs=[8,1],nr=[4,1]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=128,n=45,k=64,bs=[8,1],nr=[4,1]): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=4,n_used=1,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=4,n_used=1,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=4,n_used=1,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=4,n_used=1,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=4,n_used=2,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=4,n_used=2,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=4,n_used=4,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=4,n_used=4,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=4,n_used=4,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=4,n_used=4,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,n_used=1,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,n_used=1,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,n_used=1,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,n_used=1,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,n_used=2,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,n_used=2,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,n_used=2,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,n_used=4,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,n_used=4,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,n_used=4,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,n_used=4,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=4,n_used=1,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=4,n_used=1,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=4,n_used=1,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=4,n_used=1,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=4,n_used=2,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=4,n_used=2,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=4,n_used=4,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=4,n_used=4,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=4,n_used=4,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=4,n_used=4,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,n_used=1,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,n_used=1,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,n_used=1,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,n_used=1,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,n_used=2,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,n_used=2,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,n_used=2,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,n_used=4,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,n_used=4,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,n_used=4,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,n_used=4,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=4,n_used=1,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=4,n_used=1,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=4,n_used=1,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=4,n_used=1,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=4,n_used=2,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=4,n_used=2,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=4,n_used=4,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=4,n_used=4,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=4,n_used=4,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=4,n_used=4,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,n_used=1,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,n_used=1,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,n_used=1,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,n_used=1,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,n_used=2,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,n_used=2,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,n_used=2,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,n_used=4,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,n_used=4,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,n_used=4,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,n_used=4,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=4,n_used=1,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=4,n_used=1,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=4,n_used=1,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=4,n_used=1,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=4,n_used=2,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=4,n_used=2,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=4,n_used=4,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=4,n_used=4,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=4,n_used=4,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=4,n_used=4,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,n_used=1,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,n_used=1,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,n_used=1,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,n_used=1,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,n_used=2,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,n_used=2,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,n_used=2,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,n_used=4,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,n_used=4,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,n_used=4,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,n_used=4,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=4,n_used=1,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=4,n_used=1,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=4,n_used=1,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=4,n_used=1,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=4,n_used=2,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=4,n_used=2,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=4,n_used=4,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=4,n_used=4,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=4,n_used=4,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=4,n_used=4,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,n_used=1,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,n_used=1,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,n_used=1,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,n_used=1,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,n_used=2,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,n_used=2,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,n_used=2,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,n_used=4,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,n_used=4,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,n_used=4,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,n_used=4,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_0,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_1,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q2_K,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q3_K,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_K,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q6_K,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xs,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_s,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_xxs,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq1_s,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq1_m,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_nl,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_s,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_xs,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=bf16,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): not supported [SYCL0] 
  SQR(type=f32,ne=[10,5,4,3]): [1;32mOK[0m
  SQRT(type=f32,ne=[10,3,3,2]): not supported [SYCL0] 
  LOG(type=f32,ne=[10,5,4,3]): not supported [SYCL0] 
  SIN(type=f32,ne=[10,2,2,2]): not supported [SYCL0] 
  COS(type=f32,ne=[10,2,2,2]): not supported [SYCL0] 
  CLAMP(type=f32,ne=[10,5,4,3],min=-0.500000,max=0.500000): [1;32mOK[0m
  DIAG_MASK_INF(type=f32,ne=[10,10,1,1],n_past=5): [1;32mOK[0m
  DIAG_MASK_INF(type=f32,ne=[10,10,3,1],n_past=5): [1;32mOK[0m
  DIAG_MASK_INF(type=f32,ne=[10,10,3,2],n_past=5): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[16,16,1,1],mask=0,scale=1.000000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[15,15,1,1],mask=0,scale=1.000000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[16,1024,1,1],mask=0,scale=1.000000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[15,1023,1,1],mask=0,scale=1.000000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1024,16,1,1],mask=0,scale=1.000000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1023,15,1,1],mask=0,scale=1.000000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1024,1024,1,1],mask=0,scale=1.000000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1023,1023,1,1],mask=0,scale=1.000000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[16,16,1,1],mask=0,scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[15,15,1,1],mask=0,scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[16,1024,1,1],mask=0,scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[15,1023,1,1],mask=0,scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1024,16,1,1],mask=0,scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1023,15,1,1],mask=0,scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1024,1024,1,1],mask=0,scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1023,1023,1,1],mask=0,scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[16,16,1,1],mask=1,scale=1.000000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[15,15,1,1],mask=1,scale=1.000000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[16,1024,1,1],mask=1,scale=1.000000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[15,1023,1,1],mask=1,scale=1.000000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1024,16,1,1],mask=1,scale=1.000000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1023,15,1,1],mask=1,scale=1.000000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1024,1024,1,1],mask=1,scale=1.000000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1023,1023,1,1],mask=1,scale=1.000000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[16,16,1,1],mask=1,scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[15,15,1,1],mask=1,scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[16,1024,1,1],mask=1,scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[15,1023,1,1],mask=1,scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1024,16,1,1],mask=1,scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1023,15,1,1],mask=1,scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1024,1024,1,1],mask=1,scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1023,1023,1,1],mask=1,scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[16,16,1,1],mask=1,scale=1.000000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[15,15,1,1],mask=1,scale=1.000000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[16,1024,1,1],mask=1,scale=1.000000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[15,1023,1,1],mask=1,scale=1.000000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1024,16,1,1],mask=1,scale=1.000000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1023,15,1,1],mask=1,scale=1.000000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1024,1024,1,1],mask=1,scale=1.000000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1023,1023,1,1],mask=1,scale=1.000000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[16,16,1,1],mask=1,scale=0.100000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[15,15,1,1],mask=1,scale=0.100000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[16,1024,1,1],mask=1,scale=0.100000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[15,1023,1,1],mask=1,scale=0.100000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1024,16,1,1],mask=1,scale=0.100000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1023,15,1,1],mask=1,scale=0.100000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1024,1024,1,1],mask=1,scale=0.100000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1023,1023,1,1],mask=1,scale=0.100000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[16,2,32,1],mask=1,scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[16,2,32,1],mask=0,scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[32,2,32,1],mask=1,scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[32,2,32,1],mask=1,scale=0.100000,max_bias=8.000000): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,40,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,52,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,64,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,1,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,71,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,8,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[80,32,2,1],n_dims=20,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[80,32,2,1],n_dims=32,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,40,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,52,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,64,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,1,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,71,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,8,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[80,32,2,1],n_dims=20,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[80,32,2,1],n_dims=32,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,40,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,52,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,64,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,1,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,71,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,8,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[80,32,2,1],n_dims=20,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[80,32,2,1],n_dims=32,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,40,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,52,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,64,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,1,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,71,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,8,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[80,32,2,1],n_dims=20,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[80,32,2,1],n_dims=32,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=0,v=1): not supported [SYCL0] 
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=0,v=1): not supported [SYCL0] 
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=1,v=1): not supported [SYCL0] 
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=1,v=1): not supported [SYCL0] 
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=0,v=1): not supported [SYCL0] 
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=0,v=1): not supported [SYCL0] 
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=1,v=1): not supported [SYCL0] 
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=1,v=1): not supported [SYCL0] 
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=0,v=1): not supported [SYCL0] 
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=0,v=1): not supported [SYCL0] 
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=1,v=1): not supported [SYCL0] 
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=1,v=1): not supported [SYCL0] 
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=0,v=1): not supported [SYCL0] 
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=0,v=1): not supported [SYCL0] 
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=1,v=1): not supported [SYCL0] 
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=1,v=1): not supported [SYCL0] 
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=0,v=1): not supported [SYCL0] 
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=0,v=1): not supported [SYCL0] 
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=1,v=1): not supported [SYCL0] 
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=1,v=1): not supported [SYCL0] 
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=0,v=1): not supported [SYCL0] 
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=0,v=1): not supported [SYCL0] 
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=1,v=1): not supported [SYCL0] 
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=1,v=1): not supported [SYCL0] 
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=0,v=1): not supported [SYCL0] 
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=0,v=1): not supported [SYCL0] 
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=1,v=1): not supported [SYCL0] 
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=1,v=1): not supported [SYCL0] 
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=0,v=1): not supported [SYCL0] 
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=0,v=1): not supported [SYCL0] 
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=1,v=1): not supported [SYCL0] 
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=1,v=1): not supported [SYCL0] 
  CONCAT(type=f32,ne_a=[11,12,13,14],ne_b_d=7,dim=0,v=0): not supported [SYCL0] 
  CONCAT(type=i32,ne_a=[11,12,13,14],ne_b_d=7,dim=0,v=0): not supported [SYCL0] 
  CONCAT(type=f32,ne_a=[11,12,13,14],ne_b_d=7,dim=1,v=0): not supported [SYCL0] 
  CONCAT(type=i32,ne_a=[11,12,13,14],ne_b_d=7,dim=1,v=0): not supported [SYCL0] 
  CONCAT(type=f32,ne_a=[11,12,13,14],ne_b_d=7,dim=2,v=0): [1;32mOK[0m
  CONCAT(type=i32,ne_a=[11,12,13,14],ne_b_d=7,dim=2,v=0): not supported [SYCL0] 
  CONCAT(type=f32,ne_a=[11,12,13,14],ne_b_d=7,dim=3,v=0): not supported [SYCL0] 
  CONCAT(type=i32,ne_a=[11,12,13,14],ne_b_d=7,dim=3,v=0): not supported [SYCL0] 
  CONCAT(type=f32,ne_a=[11,12,13,14],ne_b_d=7,dim=0,v=1): not supported [SYCL0] 
  CONCAT(type=i32,ne_a=[11,12,13,14],ne_b_d=7,dim=0,v=1): not supported [SYCL0] 
  CONCAT(type=f32,ne_a=[11,12,13,14],ne_b_d=7,dim=1,v=1): not supported [SYCL0] 
  CONCAT(type=i32,ne_a=[11,12,13,14],ne_b_d=7,dim=1,v=1): not supported [SYCL0] 
  CONCAT(type=f32,ne_a=[11,12,13,14],ne_b_d=7,dim=2,v=1): not supported [SYCL0] 
  CONCAT(type=i32,ne_a=[11,12,13,14],ne_b_d=7,dim=2,v=1): not supported [SYCL0] 
  CONCAT(type=f32,ne_a=[11,12,13,14],ne_b_d=7,dim=3,v=1): not supported [SYCL0] 
  CONCAT(type=i32,ne_a=[11,12,13,14],ne_b_d=7,dim=3,v=1): not supported [SYCL0] 
  CONCAT(type=f32,ne_a=[11,12,13,14],ne_b_d=7,dim=0,v=2): not supported [SYCL0] 
  CONCAT(type=i32,ne_a=[11,12,13,14],ne_b_d=7,dim=0,v=2): not supported [SYCL0] 
  CONCAT(type=f32,ne_a=[11,12,13,14],ne_b_d=7,dim=1,v=2): not supported [SYCL0] 
  CONCAT(type=i32,ne_a=[11,12,13,14],ne_b_d=7,dim=1,v=2): not supported [SYCL0] 
  CONCAT(type=f32,ne_a=[11,12,13,14],ne_b_d=7,dim=2,v=2): not supported [SYCL0] 
  CONCAT(type=i32,ne_a=[11,12,13,14],ne_b_d=7,dim=2,v=2): not supported [SYCL0] 
  CONCAT(type=f32,ne_a=[11,12,13,14],ne_b_d=7,dim=3,v=2): not supported [SYCL0] 
  CONCAT(type=i32,ne_a=[11,12,13,14],ne_b_d=7,dim=3,v=2): not supported [SYCL0] 
  CONCAT(type=f32,ne_a=[11,12,13,14],ne_b_d=7,dim=0,v=3): not supported [SYCL0] 
  CONCAT(type=i32,ne_a=[11,12,13,14],ne_b_d=7,dim=0,v=3): not supported [SYCL0] 
  CONCAT(type=f32,ne_a=[11,12,13,14],ne_b_d=7,dim=1,v=3): not supported [SYCL0] 
  CONCAT(type=i32,ne_a=[11,12,13,14],ne_b_d=7,dim=1,v=3): not supported [SYCL0] 
  CONCAT(type=f32,ne_a=[11,12,13,14],ne_b_d=7,dim=2,v=3): not supported [SYCL0] 
  CONCAT(type=i32,ne_a=[11,12,13,14],ne_b_d=7,dim=2,v=3): not supported [SYCL0] 
  CONCAT(type=f32,ne_a=[11,12,13,14],ne_b_d=7,dim=3,v=3): not supported [SYCL0] 
  CONCAT(type=i32,ne_a=[11,12,13,14],ne_b_d=7,dim=3,v=3): not supported [SYCL0] 
  ARGSORT(type=f32,ne=[8,1,1,1],order=0): [1;32mOK[0m
  ARGSORT(type=f32,ne=[16,10,10,10],order=0): [1;32mOK[0m
  ARGSORT(type=f32,ne=[60,10,10,10],order=0): [1;32mOK[0m
  ARGSORT(type=f32,ne=[8,1,1,1],order=1): [1;32mOK[0m
  ARGSORT(type=f32,ne=[16,10,10,10],order=1): [1;32mOK[0m
  ARGSORT(type=f32,ne=[60,10,10,10],order=1): [1;32mOK[0m
  SUM(type=f32,ne=[10,5,4,3]): not supported [SYCL0] 
  SUM_ROWS(type=f32,ne=[10,5,4,3]): [1;32mOK[0m
  UPSCALE(type=f32,ne=[512,512,3,1],scale_factor=2,transpose=0): [1;32mOK[0m
  UPSCALE(type=f32,ne=[512,512,3,1],scale_factor=2,transpose=1): [1;32mOK[0m
  UPSCALE(type=f32,ne=[2,5,7,11],ne_tgt=[5,7,11,13]): [1;32mOK[0m
  GROUP_NORM(type=f32,ne=[64,64,320,1],num_groups=32): [1;32mOK[0m
  ACC(type=f32,ne_a=[256,17,1,1],ne_b=[256,16,1,1]): [1;32mOK[0m
  PAD(type=f32,ne_a=[512,512,1,1],pad_0=1,pad_1=1): [1;32mOK[0m
  ARANGE(type=f32,start=0.000000,stop=10.000000,step=1.000000): not supported [SYCL0] 
  TIMESTEP_EMBEDDING(type=f32,ne_a=[2,1,1,1],dim=320,max_period=10000): [1;32mOK[0m
  LEAKY_RELU(type=f32,ne_a=[10,5,4,3],negative_slope=0.100000): [1;32mOK[0m
  FLASH_ATTN_EXT(hs=64,nh=32,kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=512,nb=2,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=512,nb=2,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=512,nb=2,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=512,nb=4,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=512,nb=4,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=512,nb=4,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=512,nb=8,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=512,nb=8,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=512,nb=8,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=1024,nb=2,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=1024,nb=2,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=1024,nb=2,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=1024,nb=4,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=1024,nb=4,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=1024,nb=4,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=1024,nb=8,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=1024,nb=8,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=1024,nb=8,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=512,nb=2,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=512,nb=2,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=512,nb=2,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=512,nb=4,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=512,nb=4,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=512,nb=4,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=512,nb=8,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=512,nb=8,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=512,nb=8,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=1024,nb=2,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=1024,nb=2,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=1024,nb=2,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=1024,nb=4,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=1024,nb=4,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=1024,nb=4,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=1024,nb=8,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=1024,nb=8,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=1024,nb=8,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=512,nb=2,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=512,nb=2,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=512,nb=2,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=512,nb=4,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=512,nb=4,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=512,nb=4,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=512,nb=8,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=512,nb=8,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=512,nb=8,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=1024,nb=2,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=1024,nb=2,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=1024,nb=2,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=1024,nb=4,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=1024,nb=4,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=1024,nb=4,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=1024,nb=8,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=1024,nb=8,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=64,nh=32,kv=1024,nb=8,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=512,nb=2,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=512,nb=2,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=512,nb=2,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=512,nb=4,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=512,nb=4,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=512,nb=4,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=512,nb=8,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=512,nb=8,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=512,nb=8,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=1024,nb=2,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=1024,nb=2,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=1024,nb=2,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=1024,nb=4,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=1024,nb=4,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=1024,nb=4,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=1024,nb=8,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=1024,nb=8,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=1024,nb=8,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=512,nb=2,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=512,nb=2,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=512,nb=2,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=512,nb=4,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=512,nb=4,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=512,nb=4,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=512,nb=8,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=512,nb=8,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=512,nb=8,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=1024,nb=2,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=1024,nb=2,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=1024,nb=2,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=1024,nb=4,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=1024,nb=4,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=1024,nb=4,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=1024,nb=8,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=1024,nb=8,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=1024,nb=8,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=512,nb=2,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=512,nb=2,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=512,nb=2,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=512,nb=4,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=512,nb=4,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=512,nb=4,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=512,nb=8,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=512,nb=8,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=512,nb=8,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=1024,nb=2,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=1024,nb=2,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=1024,nb=2,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=1024,nb=4,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=1024,nb=4,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=1024,nb=4,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=1024,nb=8,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=1024,nb=8,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=80,nh=32,kv=1024,nb=8,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=2,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=2,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=2,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=4,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=4,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=4,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=8,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=8,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=8,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=2,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=2,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=2,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=4,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=4,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=4,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=8,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=8,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=8,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=10.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=10.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=10.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=2,mask=1,max_bias=0.000000,logit_softcap=10.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=2,mask=1,max_bias=0.000000,logit_softcap=10.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=2,mask=1,max_bias=0.000000,logit_softcap=10.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=4,mask=1,max_bias=0.000000,logit_softcap=10.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=4,mask=1,max_bias=0.000000,logit_softcap=10.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=4,mask=1,max_bias=0.000000,logit_softcap=10.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=8,mask=1,max_bias=0.000000,logit_softcap=10.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=8,mask=1,max_bias=0.000000,logit_softcap=10.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=8,mask=1,max_bias=0.000000,logit_softcap=10.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=10.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=10.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=10.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=2,mask=1,max_bias=0.000000,logit_softcap=10.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=2,mask=1,max_bias=0.000000,logit_softcap=10.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=2,mask=1,max_bias=0.000000,logit_softcap=10.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=4,mask=1,max_bias=0.000000,logit_softcap=10.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=4,mask=1,max_bias=0.000000,logit_softcap=10.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=4,mask=1,max_bias=0.000000,logit_softcap=10.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=8,mask=1,max_bias=0.000000,logit_softcap=10.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=8,mask=1,max_bias=0.000000,logit_softcap=10.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=8,mask=1,max_bias=0.000000,logit_softcap=10.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=2,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=2,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=2,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=4,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=4,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=4,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=8,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=8,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=8,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=2,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=2,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=2,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=4,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=4,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=4,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=8,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=8,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=8,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=10.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=10.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=10.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=2,mask=1,max_bias=8.000000,logit_softcap=10.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=2,mask=1,max_bias=8.000000,logit_softcap=10.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=2,mask=1,max_bias=8.000000,logit_softcap=10.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=4,mask=1,max_bias=8.000000,logit_softcap=10.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=4,mask=1,max_bias=8.000000,logit_softcap=10.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=4,mask=1,max_bias=8.000000,logit_softcap=10.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=8,mask=1,max_bias=8.000000,logit_softcap=10.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=8,mask=1,max_bias=8.000000,logit_softcap=10.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=8,mask=1,max_bias=8.000000,logit_softcap=10.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=10.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=10.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=10.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=2,mask=1,max_bias=8.000000,logit_softcap=10.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=2,mask=1,max_bias=8.000000,logit_softcap=10.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=2,mask=1,max_bias=8.000000,logit_softcap=10.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=4,mask=1,max_bias=8.000000,logit_softcap=10.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=4,mask=1,max_bias=8.000000,logit_softcap=10.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=4,mask=1,max_bias=8.000000,logit_softcap=10.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=8,mask=1,max_bias=8.000000,logit_softcap=10.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=8,mask=1,max_bias=8.000000,logit_softcap=10.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=8,mask=1,max_bias=8.000000,logit_softcap=10.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=2,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=2,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=2,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=4,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=4,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=4,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=8,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=8,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=8,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=2,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=2,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=2,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=4,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=4,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=4,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=8,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=8,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=8,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=10.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=10.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=10.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=2,mask=0,max_bias=0.000000,logit_softcap=10.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=2,mask=0,max_bias=0.000000,logit_softcap=10.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=2,mask=0,max_bias=0.000000,logit_softcap=10.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=4,mask=0,max_bias=0.000000,logit_softcap=10.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=4,mask=0,max_bias=0.000000,logit_softcap=10.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=4,mask=0,max_bias=0.000000,logit_softcap=10.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=8,mask=0,max_bias=0.000000,logit_softcap=10.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=8,mask=0,max_bias=0.000000,logit_softcap=10.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=512,nb=8,mask=0,max_bias=0.000000,logit_softcap=10.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=10.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=10.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=10.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=2,mask=0,max_bias=0.000000,logit_softcap=10.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=2,mask=0,max_bias=0.000000,logit_softcap=10.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=2,mask=0,max_bias=0.000000,logit_softcap=10.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=4,mask=0,max_bias=0.000000,logit_softcap=10.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=4,mask=0,max_bias=0.000000,logit_softcap=10.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=4,mask=0,max_bias=0.000000,logit_softcap=10.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=8,mask=0,max_bias=0.000000,logit_softcap=10.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=8,mask=0,max_bias=0.000000,logit_softcap=10.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=128,nh=32,kv=1024,nb=8,mask=0,max_bias=0.000000,logit_softcap=10.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=512,nb=2,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=512,nb=2,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=512,nb=2,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=512,nb=4,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=512,nb=4,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=512,nb=4,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=512,nb=8,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=512,nb=8,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=512,nb=8,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=1024,nb=2,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=1024,nb=2,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=1024,nb=2,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=1024,nb=4,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=1024,nb=4,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=1024,nb=4,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=1024,nb=8,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=1024,nb=8,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=1024,nb=8,mask=1,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=512,nb=2,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=512,nb=2,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=512,nb=2,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=512,nb=4,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=512,nb=4,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=512,nb=4,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=512,nb=8,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=512,nb=8,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=512,nb=8,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=1024,nb=2,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=1024,nb=2,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=1024,nb=2,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=1024,nb=4,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=1024,nb=4,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=1024,nb=4,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=1024,nb=8,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=1024,nb=8,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=1024,nb=8,mask=1,max_bias=8.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=512,nb=2,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=512,nb=2,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=512,nb=2,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=512,nb=4,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=512,nb=4,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=512,nb=4,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=512,nb=8,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=512,nb=8,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=512,nb=8,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=1024,nb=2,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=1024,nb=2,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=1024,nb=2,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=1024,nb=4,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=1024,nb=4,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=1024,nb=4,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=1024,nb=8,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=f16): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=1024,nb=8,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q8_0): not supported [SYCL0] 
  FLASH_ATTN_EXT(hs=256,nh=32,kv=1024,nb=8,mask=0,max_bias=0.000000,logit_softcap=0.000000,type_KV=q4_0): not supported [SYCL0] 
  CROSS_ENTROPY_LOSS(type=f32,ne=[10,5,4,3]): not supported [SYCL0] 
  1438/1442 tests passed
  Backend SYCL0: [1;31mFAIL[0m

1/2 backends passed
[1;31mFAIL[0m

      Start 25: test-rope
25/26 Test #25: test-rope .........................   Passed    0.06 sec
      Start 28: test-json-schema-to-grammar
26/26 Test #28: test-json-schema-to-grammar .......Subprocess aborted***Exception:   1.58 sec
LLAMA_NODE_AVAILABLE = false
LLAMA_PYTHON_AVAILABLE = false
#
# Testing JSON schema conversion (C++)
#
- min 0
- min 1
- min 3
- min 9
- min 10
- min 25
- max 30
- min -5
- min -123
- max -5
- max 1
- max 100
- min 0 max 23
- min 15 max 300
- min 5 max 30
- min -123 max 42
- min -10 max 10
- unknown type (failure expected)
Error: JSON schema conversion failed:
Unrecognized schema: {"type":"kaboom"}
- invalid type (failure expected)
Error: JSON schema conversion failed:
Unrecognized schema: {"type":123}
- empty schema (object)
- exotic formats
- string
- string w/ min length 1
- string w/ min length 3
- string w/ max length
- string w/ min & max length
- boolean
- integer
- string const
- non-string const
- non-string enum
- string array
- nullable string array
- tuple1
- tuple2
- number
- minItems
- maxItems 1
- maxItems 2
- min + maxItems
- min + max items with min + max values across zero
- min + max items with min + max values
- simple regexp
- regexp escapes
- regexp quote
- regexp
- required props in original order
- 1 optional prop
- N optional props
- required + optional props each in original order
- additional props
- additional props (true)
- additional props (implicit)
- empty w/o additional props
- required + additional props
- optional + additional props
- required + optional + additional props
- optional props with empty name
- optional props with nested names
- optional props with common prefix
- top-level $ref
- anyOf
- mix of allOf, anyOf and $ref (similar to https://json.schemastore.org/tsconfig.json)
- conflicting names
Python version is sufficient
#
# Testing JSON schema conversion (Python)
#
- min 0
- min 1
- min 3
- min 9
- min 10
- min 25
- max 30
- min -5
- min -123
- max -5
- max 1
- max 100
- min 0 max 23
- min 15 max 300
- min 5 max 30
- min -123 max 42
- min -10 max 10
- unknown type (failure expected)
Traceback (most recent call last):
  File "/home/jianyuzh/ws/llama.cpp/llama.cpp_ci/arthw-llama.cpp/./examples/json_schema_to_grammar.py", line 811, in <module>
    main()
  File "/home/jianyuzh/ws/llama.cpp/llama.cpp_ci/arthw-llama.cpp/./examples/json_schema_to_grammar.py", line 806, in main
    converter.visit(schema, '')
  File "/home/jianyuzh/ws/llama.cpp/llama.cpp_ci/arthw-llama.cpp/./examples/json_schema_to_grammar.py", line 667, in visit
    assert schema_type in PRIMITIVE_RULES, f'Unrecognized schema: {schema}'
AssertionError: Unrecognized schema: {'type': 'kaboom'}
- invalid type (failure expected)
Traceback (most recent call last):
  File "/home/jianyuzh/ws/llama.cpp/llama.cpp_ci/arthw-llama.cpp/./examples/json_schema_to_grammar.py", line 811, in <module>
    main()
  File "/home/jianyuzh/ws/llama.cpp/llama.cpp_ci/arthw-llama.cpp/./examples/json_schema_to_grammar.py", line 806, in main
    converter.visit(schema, '')
  File "/home/jianyuzh/ws/llama.cpp/llama.cpp_ci/arthw-llama.cpp/./examples/json_schema_to_grammar.py", line 667, in visit
    assert schema_type in PRIMITIVE_RULES, f'Unrecognized schema: {schema}'
AssertionError: Unrecognized schema: {'type': 123}
- empty schema (object)
- exotic formats
- string
- string w/ min length 1
- string w/ min length 3
- string w/ max length
- string w/ min & max length
- boolean
- integer
- string const
- non-string const
- non-string enum
- string array
- nullable string array
- tuple1
- tuple2
- number
- minItems
- maxItems 1
- maxItems 2
- min + maxItems
- min + max items with min + max values across zero
- min + max items with min + max values
- simple regexp
- regexp escapes
- regexp quote
- regexp
- required props in original order
- 1 optional prop
- N optional props
- required + optional props each in original order
- additional props
- additional props (true)
- additional props (implicit)
- empty w/o additional props
- required + additional props
- optional + additional props
- required + optional + additional props
- optional props with empty name
- optional props with nested names
- optional props with common prefix
- top-level $ref
- anyOf
- mix of allOf, anyOf and $ref (similar to https://json.schemastore.org/tsconfig.json)
- conflicting names
v12.22.9
#
# Testing JSON schema conversion (JavaScript)
#
- min 0
file:///home/jianyuzh/ws/llama.cpp/llama.cpp_ci/arthw-llama.cpp/tests/run-json-schema-to-grammar.mjs:8
schema = await converter.resolveRefs(schema, url)
         ^^^^^

SyntaxError: Unexpected reserved word
    at Loader.moduleStrategy (internal/modules/esm/translators.js:133:18)
    at async link (internal/modules/esm/module_job.js:42:21)
#
# Test 'min 0' failed.
#
{
            "type": "integer",
            "minimum": 0
        }
# EXPECTED STATUS: SUCCESS
# ACTUAL STATUS: FAILURE
test-json-schema-to-grammar: /home/jianyuzh/ws/llama.cpp/llama.cpp_ci/arthw-llama.cpp/tests/test-json-schema-to-grammar.cpp:60: void TestCase::verify_status(TestCaseStatus) const: Assertion `false' failed.


92% tests passed, 2 tests failed out of 26

Label Time Summary:
main    =  37.53 sec*proc (26 tests)

Total Test time (real) =  37.54 sec

The following tests FAILED:
	 24 - test-backend-ops (Failed)
	 28 - test-json-schema-to-grammar (Subprocess aborted)
Errors while running CTest

real	0m37.541s
user	0m45.580s
sys	0m4.383s
```
