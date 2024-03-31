### ctest_release

Runs ctest in release mode
- status: 8
```
+ ctest --output-on-failure -L main
Test project /var/jenkins_home/workspace/llama.cpp/llama.cpp/build-ci-release
      Start  1: test-quantize-fns
 1/21 Test  #1: test-quantize-fns ...................   Passed    5.88 sec
      Start  2: test-quantize-perf
 2/21 Test  #2: test-quantize-perf ..................   Passed    4.11 sec
      Start  3: test-sampling
 3/21 Test  #3: test-sampling .......................   Passed    0.05 sec
      Start  4: test-chat-template
 4/21 Test  #4: test-chat-template ..................   Passed    0.02 sec
      Start  5: test-tokenizer-0-llama
 5/21 Test  #5: test-tokenizer-0-llama ..............   Passed    0.10 sec
      Start  6: test-tokenizer-0-falcon
 6/21 Test  #6: test-tokenizer-0-falcon .............   Passed    0.25 sec
      Start  7: test-tokenizer-1-llama
 7/21 Test  #7: test-tokenizer-1-llama ..............   Passed    0.33 sec
      Start  8: test-tokenizer-1-baichuan
 8/21 Test  #8: test-tokenizer-1-baichuan ...........   Passed    0.36 sec
      Start  9: test-tokenizer-1-falcon
 9/21 Test  #9: test-tokenizer-1-falcon .............   Passed    0.75 sec
      Start 10: test-tokenizer-1-aquila
10/21 Test #10: test-tokenizer-1-aquila .............   Passed    1.11 sec
      Start 11: test-tokenizer-1-mpt
11/21 Test #11: test-tokenizer-1-mpt ................   Passed    0.65 sec
      Start 12: test-tokenizer-1-stablelm-3b-4e1t
12/21 Test #12: test-tokenizer-1-stablelm-3b-4e1t ...   Passed    0.61 sec
      Start 13: test-tokenizer-1-gpt-neox
13/21 Test #13: test-tokenizer-1-gpt-neox ...........   Passed    0.61 sec
      Start 14: test-tokenizer-1-refact
14/21 Test #14: test-tokenizer-1-refact .............   Passed    0.61 sec
      Start 15: test-tokenizer-1-starcoder
15/21 Test #15: test-tokenizer-1-starcoder ..........   Passed    0.62 sec
      Start 16: test-tokenizer-1-gpt2
16/21 Test #16: test-tokenizer-1-gpt2 ...............   Passed    0.64 sec
      Start 17: test-grammar-parser
17/21 Test #17: test-grammar-parser .................   Passed    0.02 sec
      Start 18: test-llama-grammar
18/21 Test #18: test-llama-grammar ..................   Passed    0.04 sec
      Start 19: test-grad0
19/21 Test #19: test-grad0 ..........................   Passed    1.36 sec
      Start 20: test-backend-ops
20/21 Test #20: test-backend-ops ....................***Failed   33.14 sec
ggml_init_sycl: GGML_SYCL_F16:   yes
ggml_init_sycl: SYCL_USE_XMX: yes
found 2 SYCL devices:
  Device 0: 12th Gen Intel(R) Core(TM) i5-1250P,	compute capability 3.0,
	max compute_units 16,	max work group size 8192,	max sub group size 64,	global mem size 33381060608
  Device 1: Intel(R) FPGA Emulation Device,	compute capability 1.2,
	max compute_units 16,	max work group size 67108864,	max sub group size 64,	global mem size 33381060608
Using device 0 (12th Gen Intel(R) Core(TM) i5-1250P) as main device
Testing 3 backends

Backend 1/3 (CPU)
  Backend name: CPU
GGML_SYCL_DEBUG=0
  ABS(type=f32,ne=[128,10,10,10]): [1;32mOK[0m
  SGN(type=f32,ne=[128,10,10,10]): [1;32mOK[0m
  NEG(type=f32,ne=[128,10,10,10]): [1;32mOK[0m
  STEP(type=f32,ne=[128,10,10,10]): [1;32mOK[0m
  TANH(type=f32,ne=[128,10,10,10]): [1;32mOK[0m
  ELU(type=f32,ne=[128,10,10,10]): [1;32mOK[0m
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
  GET_ROWS(type=q2_K,n=256,m=5,r=4,b=1,v=0): [1;32mOK[0m
  GET_ROWS(type=q2_K,n=256,m=5,r=4,b=1,v=1): [1;32mOK[0m
  GET_ROWS(type=q2_K,n=256,m=5,r=4,b=7,v=0): [1;32mOK[0m
  GET_ROWS(type=q2_K,n=256,m=5,r=4,b=7,v=1): [1;32mOK[0m
  GET_ROWS(type=q3_K,n=256,m=5,r=4,b=1,v=0): [1;32mOK[0m
  GET_ROWS(type=q3_K,n=256,m=5,r=4,b=1,v=1): [1;32mOK[0m
  GET_ROWS(type=q3_K,n=256,m=5,r=4,b=7,v=0): [1;32mOK[0m
  GET_ROWS(type=q3_K,n=256,m=5,r=4,b=7,v=1): [1;32mOK[0m
  GET_ROWS(type=q4_K,n=256,m=5,r=4,b=1,v=0): [1;32mOK[0m
  GET_ROWS(type=q4_K,n=256,m=5,r=4,b=1,v=1): [1;32mOK[0m
  GET_ROWS(type=q4_K,n=256,m=5,r=4,b=7,v=0): [1;32mOK[0m
  GET_ROWS(type=q4_K,n=256,m=5,r=4,b=7,v=1): [1;32mOK[0m
  GET_ROWS(type=q5_K,n=256,m=5,r=4,b=1,v=0): [1;32mOK[0m
  GET_ROWS(type=q5_K,n=256,m=5,r=4,b=1,v=1): [1;32mOK[0m
  GET_ROWS(type=q5_K,n=256,m=5,r=4,b=7,v=0): [1;32mOK[0m
  GET_ROWS(type=q5_K,n=256,m=5,r=4,b=7,v=1): [1;32mOK[0m
  GET_ROWS(type=q6_K,n=256,m=5,r=4,b=1,v=0): [1;32mOK[0m
  GET_ROWS(type=q6_K,n=256,m=5,r=4,b=1,v=1): [1;32mOK[0m
  GET_ROWS(type=q6_K,n=256,m=5,r=4,b=7,v=0): [1;32mOK[0m
  GET_ROWS(type=q6_K,n=256,m=5,r=4,b=7,v=1): [1;32mOK[0m
  GET_ROWS(type=iq2_xxs,n=256,m=5,r=4,b=1,v=0): ================================================================= iq2xs_init_impl(grid_size = 256)
iq2xs_init_impl: 373964 neighbours in total
[1;32mOK[0m
  GET_ROWS(type=iq2_xxs,n=256,m=5,r=4,b=1,v=1): [1;32mOK[0m
  GET_ROWS(type=iq2_xxs,n=256,m=5,r=4,b=7,v=0): [1;32mOK[0m
  GET_ROWS(type=iq2_xxs,n=256,m=5,r=4,b=7,v=1): [1;32mOK[0m
  GET_ROWS(type=iq2_xs,n=256,m=5,r=4,b=1,v=0): ================================================================= iq2xs_init_impl(grid_size = 512)
iq2xs_init_impl: 508542 neighbours in total
[1;32mOK[0m
  GET_ROWS(type=iq2_xs,n=256,m=5,r=4,b=1,v=1): [1;32mOK[0m
  GET_ROWS(type=iq2_xs,n=256,m=5,r=4,b=7,v=0): [1;32mOK[0m
  GET_ROWS(type=iq2_xs,n=256,m=5,r=4,b=7,v=1): [1;32mOK[0m
  GET_ROWS(type=iq2_s,n=256,m=5,r=4,b=1,v=0): ================================================================= iq2xs_init_impl(grid_size = 1024)
iq2xs_init_impl: 166432 neighbours in total
[1;32mOK[0m
  GET_ROWS(type=iq2_s,n=256,m=5,r=4,b=1,v=1): [1;32mOK[0m
  GET_ROWS(type=iq2_s,n=256,m=5,r=4,b=7,v=0): [1;32mOK[0m
  GET_ROWS(type=iq2_s,n=256,m=5,r=4,b=7,v=1): [1;32mOK[0m
  GET_ROWS(type=iq3_xxs,n=256,m=5,r=4,b=1,v=0): ================================================================= iq3xs_init_impl(grid_size = 256)
iq3xs_init_impl: 18985 neighbours in total
[1;32mOK[0m
  GET_ROWS(type=iq3_xxs,n=256,m=5,r=4,b=1,v=1): [1;32mOK[0m
  GET_ROWS(type=iq3_xxs,n=256,m=5,r=4,b=7,v=0): [1;32mOK[0m
  GET_ROWS(type=iq3_xxs,n=256,m=5,r=4,b=7,v=1): [1;32mOK[0m
  GET_ROWS(type=iq1_s,n=256,m=5,r=4,b=1,v=0): ================================================================= iq2xs_init_impl(grid_size = 512)
iq2xs_init_impl: 534045 neighbours in total
[1;32mOK[0m
  GET_ROWS(type=iq1_s,n=256,m=5,r=4,b=1,v=1): [1;32mOK[0m
  GET_ROWS(type=iq1_s,n=256,m=5,r=4,b=7,v=0): [1;32mOK[0m
  GET_ROWS(type=iq1_s,n=256,m=5,r=4,b=7,v=1): [1;32mOK[0m
  GET_ROWS(type=iq4_nl,n=256,m=5,r=4,b=1,v=0): [1;32mOK[0m
  GET_ROWS(type=iq4_nl,n=256,m=5,r=4,b=1,v=1): [1;32mOK[0m
  GET_ROWS(type=iq4_nl,n=256,m=5,r=4,b=7,v=0): [1;32mOK[0m
  GET_ROWS(type=iq4_nl,n=256,m=5,r=4,b=7,v=1): [1;32mOK[0m
  GET_ROWS(type=iq3_s,n=256,m=5,r=4,b=1,v=0): ================================================================= iq3xs_init_impl(grid_size = 512)
iq3xs_init_impl: 24733 neighbours in total
[1;32mOK[0m
  GET_ROWS(type=iq3_s,n=256,m=5,r=4,b=1,v=1): [1;32mOK[0m
  GET_ROWS(type=iq3_s,n=256,m=5,r=4,b=7,v=0): [1;32mOK[0m
  GET_ROWS(type=iq3_s,n=256,m=5,r=4,b=7,v=1): [1;32mOK[0m
  GET_ROWS(type=iq4_xs,n=256,m=5,r=4,b=1,v=0): [1;32mOK[0m
  GET_ROWS(type=iq4_xs,n=256,m=5,r=4,b=1,v=1): [1;32mOK[0m
  GET_ROWS(type=iq4_xs,n=256,m=5,r=4,b=7,v=0): [1;32mOK[0m
  GET_ROWS(type=iq4_xs,n=256,m=5,r=4,b=7,v=1): [1;32mOK[0m
  GET_ROWS(type=i32,n=256,m=5,r=4,b=1,v=0): [1;32mOK[0m
  GET_ROWS(type=i32,n=256,m=5,r=4,b=1,v=1): [1;32mOK[0m
  GET_ROWS(type=i32,n=256,m=5,r=4,b=7,v=0): [1;32mOK[0m
  GET_ROWS(type=i32,n=256,m=5,r=4,b=7,v=1): [1;32mOK[0m
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
  CPY(type_src=f16,type_dst=q4_0,ne=[256,4,4,4]): [1;32mOK[0m
  CPY(type_src=f16,type_dst=q4_1,ne=[256,4,4,4]): [1;32mOK[0m
  CPY(type_src=f16,type_dst=q5_0,ne=[256,4,4,4]): [1;32mOK[0m
  CPY(type_src=f16,type_dst=q5_1,ne=[256,4,4,4]): [1;32mOK[0m
  CPY(type_src=f16,type_dst=q8_0,ne=[256,4,4,4]): [1;32mOK[0m
  CPY(type_src=f16,type_dst=q2_K,ne=[256,4,4,4]): [1;32mOK[0m
  CPY(type_src=f16,type_dst=q3_K,ne=[256,4,4,4]): [1;32mOK[0m
  CPY(type_src=f16,type_dst=q4_K,ne=[256,4,4,4]): [1;32mOK[0m
  CPY(type_src=f16,type_dst=q5_K,ne=[256,4,4,4]): [1;32mOK[0m
  CPY(type_src=f16,type_dst=q6_K,ne=[256,4,4,4]): [1;32mOK[0m
  CPY(type_src=f16,type_dst=iq2_xxs,ne=[256,4,4,4]): not supported [CPU] not supported [CPU] 
  CPY(type_src=f16,type_dst=iq2_xs,ne=[256,4,4,4]): not supported [CPU] not supported [CPU] 
  CPY(type_src=f16,type_dst=iq2_s,ne=[256,4,4,4]): [1;32mOK[0m
  CPY(type_src=f16,type_dst=iq3_xxs,ne=[256,4,4,4]): [1;32mOK[0m
  CPY(type_src=f16,type_dst=iq1_s,ne=[256,4,4,4]): not supported [CPU] not supported [CPU] 
  CPY(type_src=f16,type_dst=iq4_nl,ne=[256,4,4,4]): [1;32mOK[0m
  CPY(type_src=f16,type_dst=iq3_s,ne=[256,4,4,4]): [1;32mOK[0m
  CPY(type_src=f16,type_dst=iq4_xs,ne=[256,4,4,4]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=f32,ne=[256,4,4,4]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=f16,ne=[256,4,4,4]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=q4_0,ne=[256,4,4,4]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=q4_1,ne=[256,4,4,4]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=q5_0,ne=[256,4,4,4]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=q5_1,ne=[256,4,4,4]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=q8_0,ne=[256,4,4,4]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=q2_K,ne=[256,4,4,4]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=q3_K,ne=[256,4,4,4]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=q4_K,ne=[256,4,4,4]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=q5_K,ne=[256,4,4,4]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=q6_K,ne=[256,4,4,4]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=iq2_xxs,ne=[256,4,4,4]): not supported [CPU] not supported [CPU] 
  CPY(type_src=f32,type_dst=iq2_xs,ne=[256,4,4,4]): not supported [CPU] not supported [CPU] 
  CPY(type_src=f32,type_dst=iq2_s,ne=[256,4,4,4]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=iq3_xxs,ne=[256,4,4,4]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=iq1_s,ne=[256,4,4,4]): not supported [CPU] not supported [CPU] 
  CPY(type_src=f32,type_dst=iq4_nl,ne=[256,4,4,4]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=iq3_s,ne=[256,4,4,4]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=iq4_xs,ne=[256,4,4,4]): [1;32mOK[0m
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
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q5_0,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_0,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_0,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_0,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_0,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_0,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): [1;32mOK[0m
  MUL_MAT(type_a=q5_0,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): [1;32mOK[0m
  MUL_MAT(type_a=q5_0,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_0,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_0,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_0,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_0,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_0,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): [1;32mOK[0m
  MUL_MAT(type_a=q5_0,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): [1;32mOK[0m
  MUL_MAT(type_a=q5_0,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q5_0,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q5_0,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q5_0,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q5_0,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q5_0,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q5_0,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q5_0,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q5_0,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q5_0,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q5_0,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q5_0,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q5_0,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q5_0,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q5_1,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_1,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_1,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_1,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_1,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_1,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): [1;32mOK[0m
  MUL_MAT(type_a=q5_1,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): [1;32mOK[0m
  MUL_MAT(type_a=q5_1,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_1,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_1,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_1,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_1,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_1,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): [1;32mOK[0m
  MUL_MAT(type_a=q5_1,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): [1;32mOK[0m
  MUL_MAT(type_a=q5_1,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q5_1,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q5_1,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q5_1,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q5_1,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q5_1,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q5_1,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q5_1,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q5_1,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q5_1,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q5_1,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q5_1,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q5_1,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q5_1,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q2_K,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q2_K,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q2_K,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q2_K,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q2_K,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q2_K,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): [1;32mOK[0m
  MUL_MAT(type_a=q2_K,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): [1;32mOK[0m
  MUL_MAT(type_a=q2_K,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q2_K,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q2_K,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q2_K,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q2_K,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q2_K,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): [1;32mOK[0m
  MUL_MAT(type_a=q2_K,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): [1;32mOK[0m
  MUL_MAT(type_a=q2_K,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q2_K,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q2_K,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q2_K,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q2_K,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q2_K,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q2_K,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q2_K,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q2_K,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q2_K,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q2_K,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q2_K,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q2_K,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q2_K,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q3_K,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q3_K,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q3_K,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q3_K,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q3_K,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q3_K,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): [1;32mOK[0m
  MUL_MAT(type_a=q3_K,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): [1;32mOK[0m
  MUL_MAT(type_a=q3_K,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q3_K,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q3_K,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q3_K,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q3_K,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q3_K,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): [1;32mOK[0m
  MUL_MAT(type_a=q3_K,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): [1;32mOK[0m
  MUL_MAT(type_a=q3_K,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q3_K,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q3_K,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q3_K,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q3_K,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q3_K,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q3_K,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q3_K,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q3_K,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q3_K,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q3_K,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q3_K,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q3_K,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q3_K,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q5_K,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_K,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_K,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_K,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_K,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_K,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): [1;32mOK[0m
  MUL_MAT(type_a=q5_K,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): [1;32mOK[0m
  MUL_MAT(type_a=q5_K,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_K,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_K,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_K,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_K,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q5_K,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): [1;32mOK[0m
  MUL_MAT(type_a=q5_K,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): [1;32mOK[0m
  MUL_MAT(type_a=q5_K,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q5_K,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q5_K,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q5_K,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q5_K,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q5_K,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q5_K,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q5_K,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q5_K,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q5_K,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q5_K,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q5_K,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q5_K,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q5_K,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q6_K,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q6_K,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q6_K,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q6_K,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q6_K,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q6_K,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): [1;32mOK[0m
  MUL_MAT(type_a=q6_K,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): [1;32mOK[0m
  MUL_MAT(type_a=q6_K,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q6_K,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q6_K,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q6_K,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=q6_K,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=q6_K,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): [1;32mOK[0m
  MUL_MAT(type_a=q6_K,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): [1;32mOK[0m
  MUL_MAT(type_a=q6_K,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q6_K,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q6_K,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q6_K,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q6_K,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q6_K,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q6_K,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q6_K,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q6_K,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q6_K,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q6_K,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q6_K,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q6_K,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=q6_K,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq2_xs,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xs,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xs,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xs,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xs,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xs,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xs,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xs,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xs,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xs,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xs,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xs,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xs,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xs,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xs,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq2_xs,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq2_xs,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq2_xs,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq2_xs,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq2_xs,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq2_xs,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq2_xs,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq2_xs,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq2_xs,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq2_xs,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq2_xs,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq2_xs,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq2_xs,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq2_s,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_s,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_s,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_s,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_s,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_s,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_s,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_s,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_s,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_s,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_s,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_s,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_s,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_s,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): [1;32mOK[0m
  MUL_MAT(type_a=iq2_s,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq2_s,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq2_s,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq2_s,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq2_s,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq2_s,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq2_s,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq2_s,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq2_s,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq2_s,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq2_s,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq2_s,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq2_s,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq2_s,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq3_xxs,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq3_xxs,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq3_xxs,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq3_xxs,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq3_xxs,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq3_xxs,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): [1;32mOK[0m
  MUL_MAT(type_a=iq3_xxs,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): [1;32mOK[0m
  MUL_MAT(type_a=iq3_xxs,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq3_xxs,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq3_xxs,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq3_xxs,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq3_xxs,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq3_xxs,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): [1;32mOK[0m
  MUL_MAT(type_a=iq3_xxs,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): [1;32mOK[0m
  MUL_MAT(type_a=iq3_xxs,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq3_xxs,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq3_xxs,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq3_xxs,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq3_xxs,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq3_xxs,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq3_xxs,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq3_xxs,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq3_xxs,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq3_xxs,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq3_xxs,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq3_xxs,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq3_xxs,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq3_xxs,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq1_s,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq1_s,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq1_s,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq1_s,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq1_s,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq1_s,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): [1;32mOK[0m
  MUL_MAT(type_a=iq1_s,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): [1;32mOK[0m
  MUL_MAT(type_a=iq1_s,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq1_s,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq1_s,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq1_s,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq1_s,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq1_s,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): [1;32mOK[0m
  MUL_MAT(type_a=iq1_s,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): [1;32mOK[0m
  MUL_MAT(type_a=iq1_s,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq1_s,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq1_s,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq1_s,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq1_s,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq1_s,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq1_s,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq1_s,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq1_s,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq1_s,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq1_s,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq1_s,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq1_s,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq1_s,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq4_nl,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq4_nl,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq4_nl,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq4_nl,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq4_nl,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq4_nl,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): [1;32mOK[0m
  MUL_MAT(type_a=iq4_nl,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): [1;32mOK[0m
  MUL_MAT(type_a=iq4_nl,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq4_nl,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq4_nl,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq4_nl,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq4_nl,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq4_nl,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): [1;32mOK[0m
  MUL_MAT(type_a=iq4_nl,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): [1;32mOK[0m
  MUL_MAT(type_a=iq4_nl,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq4_nl,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq4_nl,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq4_nl,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq4_nl,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq4_nl,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq4_nl,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq4_nl,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq4_nl,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq4_nl,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq4_nl,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq4_nl,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq4_nl,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq4_nl,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq3_s,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq3_s,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq3_s,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq3_s,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq3_s,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq3_s,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): [1;32mOK[0m
  MUL_MAT(type_a=iq3_s,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): [1;32mOK[0m
  MUL_MAT(type_a=iq3_s,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq3_s,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq3_s,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq3_s,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq3_s,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq3_s,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): [1;32mOK[0m
  MUL_MAT(type_a=iq3_s,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): [1;32mOK[0m
  MUL_MAT(type_a=iq3_s,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq3_s,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq3_s,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq3_s,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq3_s,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq3_s,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq3_s,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq3_s,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq3_s,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq3_s,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq3_s,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq3_s,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq3_s,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq3_s,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq4_xs,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq4_xs,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq4_xs,type_b=f32,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq4_xs,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq4_xs,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq4_xs,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): [1;32mOK[0m
  MUL_MAT(type_a=iq4_xs,type_b=f32,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): [1;32mOK[0m
  MUL_MAT(type_a=iq4_xs,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq4_xs,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq4_xs,type_b=f32,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq4_xs,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq4_xs,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): [1;32mOK[0m
  MUL_MAT(type_a=iq4_xs,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): [1;32mOK[0m
  MUL_MAT(type_a=iq4_xs,type_b=f32,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): [1;32mOK[0m
  MUL_MAT(type_a=iq4_xs,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq4_xs,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq4_xs,type_b=f16,m=16,n=1,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq4_xs,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq4_xs,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq4_xs,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[1,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq4_xs,type_b=f16,m=16,n=1,k=256,bs=[10,10],nr=[2,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq4_xs,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq4_xs,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq4_xs,type_b=f16,m=16,n=16,k=256,bs=[10,1],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq4_xs,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq4_xs,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,1]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq4_xs,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[1,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT(type_a=iq4_xs,type_b=f16,m=16,n=16,k=256,bs=[10,10],nr=[2,2]): not supported [CPU] not supported [CPU] 
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=2,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=2,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=2,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=2,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=4,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=4,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=4,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=4,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=4,id=2,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=4,id=2,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=4,id=3,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=4,id=3,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,id=2,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,id=2,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,id=3,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,id=3,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,id=4,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,id=4,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,id=5,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,id=5,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,id=6,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,id=6,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,id=7,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,id=7,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=2,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=2,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=2,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=2,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=4,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=4,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=4,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=4,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=4,id=2,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=4,id=2,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=4,id=3,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=4,id=3,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,id=2,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,id=2,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,id=3,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,id=3,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,id=4,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,id=4,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,id=5,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,id=5,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,id=6,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,id=6,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,id=7,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,id=7,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=2,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=2,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=2,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=2,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=4,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=4,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=4,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=4,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=4,id=2,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=4,id=2,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=4,id=3,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=4,id=3,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,id=2,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,id=2,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,id=3,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,id=3,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,id=4,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,id=4,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,id=5,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,id=5,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,id=6,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,id=6,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,id=7,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,id=7,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=2,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=2,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=2,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=2,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=4,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=4,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=4,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=4,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=4,id=2,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=4,id=2,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=4,id=3,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=4,id=3,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=8,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=8,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=8,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=8,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=8,id=2,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=8,id=2,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=8,id=3,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=8,id=3,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=8,id=4,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=8,id=4,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=8,id=5,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=8,id=5,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=8,id=6,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=8,id=6,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=8,id=7,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=8,id=7,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_0,type_b=f32,n_mats=2,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_0,type_b=f32,n_mats=2,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_0,type_b=f32,n_mats=2,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_0,type_b=f32,n_mats=2,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_0,type_b=f32,n_mats=4,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_0,type_b=f32,n_mats=4,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_0,type_b=f32,n_mats=4,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_0,type_b=f32,n_mats=4,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_0,type_b=f32,n_mats=4,id=2,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_0,type_b=f32,n_mats=4,id=2,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_0,type_b=f32,n_mats=4,id=3,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_0,type_b=f32,n_mats=4,id=3,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_0,type_b=f32,n_mats=8,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_0,type_b=f32,n_mats=8,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_0,type_b=f32,n_mats=8,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_0,type_b=f32,n_mats=8,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_0,type_b=f32,n_mats=8,id=2,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_0,type_b=f32,n_mats=8,id=2,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_0,type_b=f32,n_mats=8,id=3,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_0,type_b=f32,n_mats=8,id=3,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_0,type_b=f32,n_mats=8,id=4,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_0,type_b=f32,n_mats=8,id=4,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_0,type_b=f32,n_mats=8,id=5,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_0,type_b=f32,n_mats=8,id=5,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_0,type_b=f32,n_mats=8,id=6,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_0,type_b=f32,n_mats=8,id=6,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_0,type_b=f32,n_mats=8,id=7,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_0,type_b=f32,n_mats=8,id=7,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_1,type_b=f32,n_mats=2,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_1,type_b=f32,n_mats=2,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_1,type_b=f32,n_mats=2,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_1,type_b=f32,n_mats=2,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_1,type_b=f32,n_mats=4,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_1,type_b=f32,n_mats=4,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_1,type_b=f32,n_mats=4,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_1,type_b=f32,n_mats=4,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_1,type_b=f32,n_mats=4,id=2,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_1,type_b=f32,n_mats=4,id=2,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_1,type_b=f32,n_mats=4,id=3,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_1,type_b=f32,n_mats=4,id=3,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_1,type_b=f32,n_mats=8,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_1,type_b=f32,n_mats=8,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_1,type_b=f32,n_mats=8,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_1,type_b=f32,n_mats=8,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_1,type_b=f32,n_mats=8,id=2,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_1,type_b=f32,n_mats=8,id=2,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_1,type_b=f32,n_mats=8,id=3,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_1,type_b=f32,n_mats=8,id=3,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_1,type_b=f32,n_mats=8,id=4,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_1,type_b=f32,n_mats=8,id=4,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_1,type_b=f32,n_mats=8,id=5,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_1,type_b=f32,n_mats=8,id=5,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_1,type_b=f32,n_mats=8,id=6,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_1,type_b=f32,n_mats=8,id=6,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_1,type_b=f32,n_mats=8,id=7,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_1,type_b=f32,n_mats=8,id=7,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=2,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=2,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=2,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=2,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=4,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=4,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=4,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=4,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=4,id=2,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=4,id=2,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=4,id=3,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=4,id=3,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=8,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=8,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=8,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=8,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=8,id=2,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=8,id=2,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=8,id=3,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=8,id=3,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=8,id=4,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=8,id=4,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=8,id=5,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=8,id=5,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=8,id=6,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=8,id=6,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=8,id=7,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=8,id=7,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q2_K,type_b=f32,n_mats=2,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q2_K,type_b=f32,n_mats=2,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q2_K,type_b=f32,n_mats=2,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q2_K,type_b=f32,n_mats=2,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q2_K,type_b=f32,n_mats=4,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q2_K,type_b=f32,n_mats=4,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q2_K,type_b=f32,n_mats=4,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q2_K,type_b=f32,n_mats=4,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q2_K,type_b=f32,n_mats=4,id=2,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q2_K,type_b=f32,n_mats=4,id=2,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q2_K,type_b=f32,n_mats=4,id=3,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q2_K,type_b=f32,n_mats=4,id=3,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q2_K,type_b=f32,n_mats=8,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q2_K,type_b=f32,n_mats=8,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q2_K,type_b=f32,n_mats=8,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q2_K,type_b=f32,n_mats=8,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q2_K,type_b=f32,n_mats=8,id=2,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q2_K,type_b=f32,n_mats=8,id=2,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q2_K,type_b=f32,n_mats=8,id=3,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q2_K,type_b=f32,n_mats=8,id=3,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q2_K,type_b=f32,n_mats=8,id=4,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q2_K,type_b=f32,n_mats=8,id=4,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q2_K,type_b=f32,n_mats=8,id=5,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q2_K,type_b=f32,n_mats=8,id=5,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q2_K,type_b=f32,n_mats=8,id=6,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q2_K,type_b=f32,n_mats=8,id=6,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q2_K,type_b=f32,n_mats=8,id=7,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q2_K,type_b=f32,n_mats=8,id=7,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q3_K,type_b=f32,n_mats=2,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q3_K,type_b=f32,n_mats=2,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q3_K,type_b=f32,n_mats=2,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q3_K,type_b=f32,n_mats=2,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q3_K,type_b=f32,n_mats=4,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q3_K,type_b=f32,n_mats=4,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q3_K,type_b=f32,n_mats=4,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q3_K,type_b=f32,n_mats=4,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q3_K,type_b=f32,n_mats=4,id=2,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q3_K,type_b=f32,n_mats=4,id=2,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q3_K,type_b=f32,n_mats=4,id=3,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q3_K,type_b=f32,n_mats=4,id=3,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q3_K,type_b=f32,n_mats=8,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q3_K,type_b=f32,n_mats=8,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q3_K,type_b=f32,n_mats=8,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q3_K,type_b=f32,n_mats=8,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q3_K,type_b=f32,n_mats=8,id=2,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q3_K,type_b=f32,n_mats=8,id=2,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q3_K,type_b=f32,n_mats=8,id=3,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q3_K,type_b=f32,n_mats=8,id=3,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q3_K,type_b=f32,n_mats=8,id=4,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q3_K,type_b=f32,n_mats=8,id=4,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q3_K,type_b=f32,n_mats=8,id=5,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q3_K,type_b=f32,n_mats=8,id=5,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q3_K,type_b=f32,n_mats=8,id=6,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q3_K,type_b=f32,n_mats=8,id=6,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q3_K,type_b=f32,n_mats=8,id=7,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q3_K,type_b=f32,n_mats=8,id=7,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=2,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=2,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=2,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=2,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=4,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=4,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=4,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=4,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=4,id=2,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=4,id=2,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=4,id=3,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=4,id=3,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,id=2,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,id=2,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,id=3,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,id=3,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,id=4,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,id=4,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,id=5,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,id=5,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,id=6,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,id=6,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,id=7,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,id=7,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_K,type_b=f32,n_mats=2,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_K,type_b=f32,n_mats=2,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_K,type_b=f32,n_mats=2,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_K,type_b=f32,n_mats=2,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_K,type_b=f32,n_mats=4,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_K,type_b=f32,n_mats=4,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_K,type_b=f32,n_mats=4,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_K,type_b=f32,n_mats=4,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_K,type_b=f32,n_mats=4,id=2,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_K,type_b=f32,n_mats=4,id=2,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_K,type_b=f32,n_mats=4,id=3,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_K,type_b=f32,n_mats=4,id=3,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_K,type_b=f32,n_mats=8,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_K,type_b=f32,n_mats=8,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_K,type_b=f32,n_mats=8,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_K,type_b=f32,n_mats=8,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_K,type_b=f32,n_mats=8,id=2,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_K,type_b=f32,n_mats=8,id=2,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_K,type_b=f32,n_mats=8,id=3,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_K,type_b=f32,n_mats=8,id=3,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_K,type_b=f32,n_mats=8,id=4,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_K,type_b=f32,n_mats=8,id=4,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_K,type_b=f32,n_mats=8,id=5,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_K,type_b=f32,n_mats=8,id=5,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_K,type_b=f32,n_mats=8,id=6,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_K,type_b=f32,n_mats=8,id=6,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_K,type_b=f32,n_mats=8,id=7,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_K,type_b=f32,n_mats=8,id=7,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q6_K,type_b=f32,n_mats=2,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q6_K,type_b=f32,n_mats=2,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q6_K,type_b=f32,n_mats=2,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q6_K,type_b=f32,n_mats=2,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q6_K,type_b=f32,n_mats=4,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q6_K,type_b=f32,n_mats=4,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q6_K,type_b=f32,n_mats=4,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q6_K,type_b=f32,n_mats=4,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q6_K,type_b=f32,n_mats=4,id=2,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q6_K,type_b=f32,n_mats=4,id=2,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q6_K,type_b=f32,n_mats=4,id=3,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q6_K,type_b=f32,n_mats=4,id=3,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q6_K,type_b=f32,n_mats=8,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q6_K,type_b=f32,n_mats=8,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q6_K,type_b=f32,n_mats=8,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q6_K,type_b=f32,n_mats=8,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q6_K,type_b=f32,n_mats=8,id=2,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q6_K,type_b=f32,n_mats=8,id=2,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q6_K,type_b=f32,n_mats=8,id=3,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q6_K,type_b=f32,n_mats=8,id=3,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q6_K,type_b=f32,n_mats=8,id=4,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q6_K,type_b=f32,n_mats=8,id=4,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q6_K,type_b=f32,n_mats=8,id=5,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q6_K,type_b=f32,n_mats=8,id=5,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q6_K,type_b=f32,n_mats=8,id=6,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q6_K,type_b=f32,n_mats=8,id=6,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=q6_K,type_b=f32,n_mats=8,id=7,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=q6_K,type_b=f32,n_mats=8,id=7,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=2,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=2,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=2,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=2,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=4,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=4,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=4,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=4,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=4,id=2,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=4,id=2,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=4,id=3,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=4,id=3,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,id=2,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,id=2,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,id=3,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,id=3,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,id=4,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,id=4,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,id=5,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,id=5,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,id=6,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,id=6,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,id=7,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,id=7,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xs,type_b=f32,n_mats=2,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xs,type_b=f32,n_mats=2,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xs,type_b=f32,n_mats=2,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xs,type_b=f32,n_mats=2,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xs,type_b=f32,n_mats=4,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xs,type_b=f32,n_mats=4,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xs,type_b=f32,n_mats=4,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xs,type_b=f32,n_mats=4,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xs,type_b=f32,n_mats=4,id=2,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xs,type_b=f32,n_mats=4,id=2,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xs,type_b=f32,n_mats=4,id=3,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xs,type_b=f32,n_mats=4,id=3,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xs,type_b=f32,n_mats=8,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xs,type_b=f32,n_mats=8,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xs,type_b=f32,n_mats=8,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xs,type_b=f32,n_mats=8,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xs,type_b=f32,n_mats=8,id=2,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xs,type_b=f32,n_mats=8,id=2,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xs,type_b=f32,n_mats=8,id=3,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xs,type_b=f32,n_mats=8,id=3,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xs,type_b=f32,n_mats=8,id=4,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xs,type_b=f32,n_mats=8,id=4,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xs,type_b=f32,n_mats=8,id=5,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xs,type_b=f32,n_mats=8,id=5,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xs,type_b=f32,n_mats=8,id=6,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xs,type_b=f32,n_mats=8,id=6,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xs,type_b=f32,n_mats=8,id=7,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xs,type_b=f32,n_mats=8,id=7,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_s,type_b=f32,n_mats=2,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_s,type_b=f32,n_mats=2,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_s,type_b=f32,n_mats=2,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_s,type_b=f32,n_mats=2,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_s,type_b=f32,n_mats=4,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_s,type_b=f32,n_mats=4,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_s,type_b=f32,n_mats=4,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_s,type_b=f32,n_mats=4,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_s,type_b=f32,n_mats=4,id=2,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_s,type_b=f32,n_mats=4,id=2,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_s,type_b=f32,n_mats=4,id=3,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_s,type_b=f32,n_mats=4,id=3,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_s,type_b=f32,n_mats=8,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_s,type_b=f32,n_mats=8,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_s,type_b=f32,n_mats=8,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_s,type_b=f32,n_mats=8,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_s,type_b=f32,n_mats=8,id=2,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_s,type_b=f32,n_mats=8,id=2,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_s,type_b=f32,n_mats=8,id=3,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_s,type_b=f32,n_mats=8,id=3,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_s,type_b=f32,n_mats=8,id=4,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_s,type_b=f32,n_mats=8,id=4,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_s,type_b=f32,n_mats=8,id=5,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_s,type_b=f32,n_mats=8,id=5,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_s,type_b=f32,n_mats=8,id=6,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_s,type_b=f32,n_mats=8,id=6,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_s,type_b=f32,n_mats=8,id=7,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_s,type_b=f32,n_mats=8,id=7,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_xxs,type_b=f32,n_mats=2,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_xxs,type_b=f32,n_mats=2,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_xxs,type_b=f32,n_mats=2,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_xxs,type_b=f32,n_mats=2,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_xxs,type_b=f32,n_mats=4,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_xxs,type_b=f32,n_mats=4,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_xxs,type_b=f32,n_mats=4,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_xxs,type_b=f32,n_mats=4,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_xxs,type_b=f32,n_mats=4,id=2,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_xxs,type_b=f32,n_mats=4,id=2,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_xxs,type_b=f32,n_mats=4,id=3,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_xxs,type_b=f32,n_mats=4,id=3,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_xxs,type_b=f32,n_mats=8,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_xxs,type_b=f32,n_mats=8,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_xxs,type_b=f32,n_mats=8,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_xxs,type_b=f32,n_mats=8,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_xxs,type_b=f32,n_mats=8,id=2,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_xxs,type_b=f32,n_mats=8,id=2,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_xxs,type_b=f32,n_mats=8,id=3,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_xxs,type_b=f32,n_mats=8,id=3,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_xxs,type_b=f32,n_mats=8,id=4,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_xxs,type_b=f32,n_mats=8,id=4,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_xxs,type_b=f32,n_mats=8,id=5,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_xxs,type_b=f32,n_mats=8,id=5,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_xxs,type_b=f32,n_mats=8,id=6,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_xxs,type_b=f32,n_mats=8,id=6,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_xxs,type_b=f32,n_mats=8,id=7,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_xxs,type_b=f32,n_mats=8,id=7,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq1_s,type_b=f32,n_mats=2,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq1_s,type_b=f32,n_mats=2,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq1_s,type_b=f32,n_mats=2,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq1_s,type_b=f32,n_mats=2,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq1_s,type_b=f32,n_mats=4,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq1_s,type_b=f32,n_mats=4,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq1_s,type_b=f32,n_mats=4,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq1_s,type_b=f32,n_mats=4,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq1_s,type_b=f32,n_mats=4,id=2,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq1_s,type_b=f32,n_mats=4,id=2,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq1_s,type_b=f32,n_mats=4,id=3,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq1_s,type_b=f32,n_mats=4,id=3,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq1_s,type_b=f32,n_mats=8,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq1_s,type_b=f32,n_mats=8,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq1_s,type_b=f32,n_mats=8,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq1_s,type_b=f32,n_mats=8,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq1_s,type_b=f32,n_mats=8,id=2,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq1_s,type_b=f32,n_mats=8,id=2,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq1_s,type_b=f32,n_mats=8,id=3,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq1_s,type_b=f32,n_mats=8,id=3,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq1_s,type_b=f32,n_mats=8,id=4,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq1_s,type_b=f32,n_mats=8,id=4,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq1_s,type_b=f32,n_mats=8,id=5,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq1_s,type_b=f32,n_mats=8,id=5,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq1_s,type_b=f32,n_mats=8,id=6,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq1_s,type_b=f32,n_mats=8,id=6,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq1_s,type_b=f32,n_mats=8,id=7,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq1_s,type_b=f32,n_mats=8,id=7,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_nl,type_b=f32,n_mats=2,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_nl,type_b=f32,n_mats=2,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_nl,type_b=f32,n_mats=2,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_nl,type_b=f32,n_mats=2,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_nl,type_b=f32,n_mats=4,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_nl,type_b=f32,n_mats=4,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_nl,type_b=f32,n_mats=4,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_nl,type_b=f32,n_mats=4,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_nl,type_b=f32,n_mats=4,id=2,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_nl,type_b=f32,n_mats=4,id=2,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_nl,type_b=f32,n_mats=4,id=3,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_nl,type_b=f32,n_mats=4,id=3,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_nl,type_b=f32,n_mats=8,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_nl,type_b=f32,n_mats=8,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_nl,type_b=f32,n_mats=8,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_nl,type_b=f32,n_mats=8,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_nl,type_b=f32,n_mats=8,id=2,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_nl,type_b=f32,n_mats=8,id=2,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_nl,type_b=f32,n_mats=8,id=3,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_nl,type_b=f32,n_mats=8,id=3,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_nl,type_b=f32,n_mats=8,id=4,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_nl,type_b=f32,n_mats=8,id=4,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_nl,type_b=f32,n_mats=8,id=5,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_nl,type_b=f32,n_mats=8,id=5,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_nl,type_b=f32,n_mats=8,id=6,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_nl,type_b=f32,n_mats=8,id=6,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_nl,type_b=f32,n_mats=8,id=7,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_nl,type_b=f32,n_mats=8,id=7,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_s,type_b=f32,n_mats=2,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_s,type_b=f32,n_mats=2,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_s,type_b=f32,n_mats=2,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_s,type_b=f32,n_mats=2,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_s,type_b=f32,n_mats=4,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_s,type_b=f32,n_mats=4,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_s,type_b=f32,n_mats=4,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_s,type_b=f32,n_mats=4,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_s,type_b=f32,n_mats=4,id=2,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_s,type_b=f32,n_mats=4,id=2,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_s,type_b=f32,n_mats=4,id=3,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_s,type_b=f32,n_mats=4,id=3,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_s,type_b=f32,n_mats=8,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_s,type_b=f32,n_mats=8,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_s,type_b=f32,n_mats=8,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_s,type_b=f32,n_mats=8,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_s,type_b=f32,n_mats=8,id=2,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_s,type_b=f32,n_mats=8,id=2,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_s,type_b=f32,n_mats=8,id=3,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_s,type_b=f32,n_mats=8,id=3,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_s,type_b=f32,n_mats=8,id=4,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_s,type_b=f32,n_mats=8,id=4,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_s,type_b=f32,n_mats=8,id=5,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_s,type_b=f32,n_mats=8,id=5,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_s,type_b=f32,n_mats=8,id=6,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_s,type_b=f32,n_mats=8,id=6,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_s,type_b=f32,n_mats=8,id=7,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_s,type_b=f32,n_mats=8,id=7,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_xs,type_b=f32,n_mats=2,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_xs,type_b=f32,n_mats=2,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_xs,type_b=f32,n_mats=2,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_xs,type_b=f32,n_mats=2,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_xs,type_b=f32,n_mats=4,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_xs,type_b=f32,n_mats=4,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_xs,type_b=f32,n_mats=4,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_xs,type_b=f32,n_mats=4,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_xs,type_b=f32,n_mats=4,id=2,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_xs,type_b=f32,n_mats=4,id=2,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_xs,type_b=f32,n_mats=4,id=3,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_xs,type_b=f32,n_mats=4,id=3,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_xs,type_b=f32,n_mats=8,id=0,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_xs,type_b=f32,n_mats=8,id=0,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_xs,type_b=f32,n_mats=8,id=1,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_xs,type_b=f32,n_mats=8,id=1,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_xs,type_b=f32,n_mats=8,id=2,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_xs,type_b=f32,n_mats=8,id=2,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_xs,type_b=f32,n_mats=8,id=3,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_xs,type_b=f32,n_mats=8,id=3,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_xs,type_b=f32,n_mats=8,id=4,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_xs,type_b=f32,n_mats=8,id=4,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_xs,type_b=f32,n_mats=8,id=5,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_xs,type_b=f32,n_mats=8,id=5,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_xs,type_b=f32,n_mats=8,id=6,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_xs,type_b=f32,n_mats=8,id=6,m=16,n=16,k=256,v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_xs,type_b=f32,n_mats=8,id=7,m=16,n=16,k=256,v=0): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_xs,type_b=f32,n_mats=8,id=7,m=16,n=16,k=256,v=1): [1;32mOK[0m
  SQR(type=f32,ne=[10,10,10,10]): [1;32mOK[0m
  CLAMP(type=f32,ne=[10,10,10,10],min=-0.500000,max=0.500000): [1;32mOK[0m
  DIAG_MASK_INF(type=f32,ne=[10,10,1,1],n_past=5): [1;32mOK[0m
  DIAG_MASK_INF(type=f32,ne=[10,10,10,1],n_past=5): [1;32mOK[0m
  DIAG_MASK_INF(type=f32,ne=[10,10,10,10],n_past=5): [1;32mOK[0m
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
  SOFT_MAX(type=f32,ne=[16,16,1,1],mask=0,scale=1.000000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[15,15,1,1],mask=0,scale=1.000000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[16,1024,1,1],mask=0,scale=1.000000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[15,1023,1,1],mask=0,scale=1.000000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1024,16,1,1],mask=0,scale=1.000000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1023,15,1,1],mask=0,scale=1.000000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1024,1024,1,1],mask=0,scale=1.000000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1023,1023,1,1],mask=0,scale=1.000000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[16,16,1,1],mask=0,scale=0.100000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[15,15,1,1],mask=0,scale=0.100000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[16,1024,1,1],mask=0,scale=0.100000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[15,1023,1,1],mask=0,scale=0.100000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1024,16,1,1],mask=0,scale=0.100000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1023,15,1,1],mask=0,scale=0.100000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1024,1024,1,1],mask=0,scale=0.100000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1023,1023,1,1],mask=0,scale=0.100000,max_bias=8.000000): [1;32mOK[0m
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
  SOFT_MAX(type=f32,ne=[16,2,32,1],mask=0,scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[32,2,32,1],mask=1,scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[16,2,32,1],mask=0,scale=0.100000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[32,2,32,1],mask=1,scale=0.100000,max_bias=8.000000): [1;32mOK[0m
  ROPE(type=f32,ne=[128,32,10,1],n_dims=128,mode=0,n_ctx=512): [1;32mOK[0m
  ROPE(type=f32,ne=[128,40,10,1],n_dims=128,mode=0,n_ctx=512): [1;32mOK[0m
  ROPE(type=f32,ne=[128,52,10,1],n_dims=128,mode=0,n_ctx=512): [1;32mOK[0m
  ROPE(type=f32,ne=[128,64,10,1],n_dims=128,mode=0,n_ctx=512): [1;32mOK[0m
  ROPE(type=f32,ne=[64,1,10,1],n_dims=64,mode=2,n_ctx=512): [1;32mOK[0m
  ROPE(type=f32,ne=[64,71,10,1],n_dims=64,mode=2,n_ctx=512): [1;32mOK[0m
  ROPE(type=f32,ne=[64,8,10,1],n_dims=64,mode=2,n_ctx=512): [1;32mOK[0m
  ROPE(type=f32,ne=[64,128,10,1],n_dims=64,mode=2,n_ctx=512): [1;32mOK[0m
  ROPE(type=f32,ne=[80,32,10,1],n_dims=20,mode=2,n_ctx=512): [1;32mOK[0m
  ROPE(type=f32,ne=[80,32,10,1],n_dims=32,mode=2,n_ctx=512): [1;32mOK[0m
  ROPE(type=f16,ne=[128,32,10,1],n_dims=128,mode=0,n_ctx=512): [1;32mOK[0m
  ROPE(type=f16,ne=[128,40,10,1],n_dims=128,mode=0,n_ctx=512): [1;32mOK[0m
  ROPE(type=f16,ne=[128,52,10,1],n_dims=128,mode=0,n_ctx=512): [1;32mOK[0m
  ROPE(type=f16,ne=[128,64,10,1],n_dims=128,mode=0,n_ctx=512): [1;32mOK[0m
  ROPE(type=f16,ne=[64,1,10,1],n_dims=64,mode=2,n_ctx=512): [1;32mOK[0m
  ROPE(type=f16,ne=[64,71,10,1],n_dims=64,mode=2,n_ctx=512): [1;32mOK[0m
  ROPE(type=f16,ne=[64,8,10,1],n_dims=64,mode=2,n_ctx=512): [1;32mOK[0m
  ROPE(type=f16,ne=[64,128,10,1],n_dims=64,mode=2,n_ctx=512): [1;32mOK[0m
  ROPE(type=f16,ne=[80,32,10,1],n_dims=20,mode=2,n_ctx=512): [1;32mOK[0m
  ROPE(type=f16,ne=[80,32,10,1],n_dims=32,mode=2,n_ctx=512): [1;32mOK[0m
  CONCAT(type=f32,ne=[10,10,10,10],b_ne2=10): [1;32mOK[0m
  CONCAT(type=i32,ne=[10,10,10,10],b_ne2=10): [1;32mOK[0m
  ARGSORT(type=f32,ne=[8,1,1,1],order=0): [1;32mOK[0m
  ARGSORT(type=f32,ne=[16,10,10,10],order=0): [1;32mOK[0m
  ARGSORT(type=f32,ne=[8,1,1,1],order=1): [1;32mOK[0m
  ARGSORT(type=f32,ne=[16,10,10,10],order=1): [1;32mOK[0m
  SUM_ROWS(type=f32,ne=[10,10,10,10]): [1;32mOK[0m
  UPSCALE(type=f32,ne=[512,512,3,1],scale_factor=2): [1;32mOK[0m
  GROUP_NORM(type=f32,ne=[64,64,320,1],num_groups=32): [1;32mOK[0m
  ACC(type=f32,ne_a=[1024,577,1,1],ne_b=[1024,576,1,1]): [1;32mOK[0m
  PAD(type=f32,ne_a=[512,512,1,1],pad_0=1,pad_1=1): [1;32mOK[0m
  LEAKY_RELU(type=f32,ne_a=[10,10,10,10],negative_slope=0.100000): [1;32mOK[0m
  1593/1593 tests passed
  Backend CPU: [1;32mOK[0m

Backend 2/3 (SYCL0)
  Backend name: SYCL
  ABS(type=f32,ne=[128,10,10,10]): not supported [SYCL] 
  SGN(type=f32,ne=[128,10,10,10]): not supported [SYCL] 
  NEG(type=f32,ne=[128,10,10,10]): not supported [SYCL] 
  STEP(type=f32,ne=[128,10,10,10]): not supported [SYCL] 
  TANH(type=f32,ne=[128,10,10,10]): [1;32mOK[0m
  ELU(type=f32,ne=[128,10,10,10]): not supported [SYCL] 
  RELU(type=f32,ne=[128,10,10,10]): [1;32mOK[0m
  GELU(type=f32,ne=[128,10,10,10]): [1;32mOK[0m
  GELU_QUICK(type=f32,ne=[128,10,10,10]): [GELU_QUICK] inf mismatch: SYCL=-nan CPU=-0.000000 [1;31mFAIL[0m
  SILU(type=f32,ne=[128,10,10,10]): [SILU] inf mismatch: SYCL=-nan CPU=-0.000000 [1;31mFAIL[0m
  HARDSWISH(type=f32,ne=[128,10,10,10]): not supported [SYCL] 
  HARDSIGMOID(type=f32,ne=[128,10,10,10]): not supported [SYCL] 
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
  GET_ROWS(type=q4_1,n=256,m=5,r=4,b=1,v=0): [GET_ROWS] NMSE = 0.000000154 > 0.000000100 [1;31mFAIL[0m
  GET_ROWS(type=q4_1,n=256,m=5,r=4,b=1,v=1): [GET_ROWS] NMSE = 0.000000147 > 0.000000100 [1;31mFAIL[0m
  GET_ROWS(type=q4_1,n=256,m=5,r=4,b=7,v=0): [GET_ROWS] NMSE = 0.000000141 > 0.000000100 [1;31mFAIL[0m
  GET_ROWS(type=q4_1,n=256,m=5,r=4,b=7,v=1): [GET_ROWS] NMSE = 0.000000154 > 0.000000100 [1;31mFAIL[0m
  GET_ROWS(type=q5_0,n=256,m=5,r=4,b=1,v=0): [1;32mOK[0m
  GET_ROWS(type=q5_0,n=256,m=5,r=4,b=1,v=1): [1;32mOK[0m
  GET_ROWS(type=q5_0,n=256,m=5,r=4,b=7,v=0): [1;32mOK[0m
  GET_ROWS(type=q5_0,n=256,m=5,r=4,b=7,v=1): [1;32mOK[0m
  GET_ROWS(type=q5_1,n=256,m=5,r=4,b=1,v=0): [GET_ROWS] NMSE = 0.000000126 > 0.000000100 [1;31mFAIL[0m
  GET_ROWS(type=q5_1,n=256,m=5,r=4,b=1,v=1): [GET_ROWS] NMSE = 0.000000135 > 0.000000100 [1;31mFAIL[0m
  GET_ROWS(type=q5_1,n=256,m=5,r=4,b=7,v=0): [GET_ROWS] NMSE = 0.000000136 > 0.000000100 [1;31mFAIL[0m
  GET_ROWS(type=q5_1,n=256,m=5,r=4,b=7,v=1): [GET_ROWS] NMSE = 0.000000144 > 0.000000100 [1;31mFAIL[0m
  GET_ROWS(type=q8_0,n=256,m=5,r=4,b=1,v=0): [1;32mOK[0m
  GET_ROWS(type=q8_0,n=256,m=5,r=4,b=1,v=1): [1;32mOK[0m
  GET_ROWS(type=q8_0,n=256,m=5,r=4,b=7,v=0): [1;32mOK[0m
  GET_ROWS(type=q8_0,n=256,m=5,r=4,b=7,v=1): [1;32mOK[0m
  GET_ROWS(type=q2_K,n=256,m=5,r=4,b=1,v=0): not supported [SYCL] 
  GET_ROWS(type=q2_K,n=256,m=5,r=4,b=1,v=1): not supported [SYCL] 
  GET_ROWS(type=q2_K,n=256,m=5,r=4,b=7,v=0): not supported [SYCL] 
  GET_ROWS(type=q2_K,n=256,m=5,r=4,b=7,v=1): not supported [SYCL] 
  GET_ROWS(type=q3_K,n=256,m=5,r=4,b=1,v=0): not supported [SYCL] 
  GET_ROWS(type=q3_K,n=256,m=5,r=4,b=1,v=1): not supported [SYCL] 
  GET_ROWS(type=q3_K,n=256,m=5,r=4,b=7,v=0): not supported [SYCL] 
  GET_ROWS(type=q3_K,n=256,m=5,r=4,b=7,v=1): not supported [SYCL] 
  GET_ROWS(type=q4_K,n=256,m=5,r=4,b=1,v=0): not supported [SYCL] 
  GET_ROWS(type=q4_K,n=256,m=5,r=4,b=1,v=1): not supported [SYCL] 
  GET_ROWS(type=q4_K,n=256,m=5,r=4,b=7,v=0): not supported [SYCL] 
  GET_ROWS(type=q4_K,n=256,m=5,r=4,b=7,v=1): not supported [SYCL] 
  GET_ROWS(type=q5_K,n=256,m=5,r=4,b=1,v=0): not supported [SYCL] 
  GET_ROWS(type=q5_K,n=256,m=5,r=4,b=1,v=1): not supported [SYCL] 
  GET_ROWS(type=q5_K,n=256,m=5,r=4,b=7,v=0): not supported [SYCL] 
  GET_ROWS(type=q5_K,n=256,m=5,r=4,b=7,v=1): not supported [SYCL] 
  GET_ROWS(type=q6_K,n=256,m=5,r=4,b=1,v=0): not supported [SYCL] 
  GET_ROWS(type=q6_K,n=256,m=5,r=4,b=1,v=1): not supported [SYCL] 
  GET_ROWS(type=q6_K,n=256,m=5,r=4,b=7,v=0): not supported [SYCL] 
  GET_ROWS(type=q6_K,n=256,m=5,r=4,b=7,v=1): not supported [SYCL] 
  GET_ROWS(type=iq2_xxs,n=256,m=5,r=4,b=1,v=0): not supported [SYCL] 
  GET_ROWS(type=iq2_xxs,n=256,m=5,r=4,b=1,v=1): not supported [SYCL] 
  GET_ROWS(type=iq2_xxs,n=256,m=5,r=4,b=7,v=0): not supported [SYCL] 
  GET_ROWS(type=iq2_xxs,n=256,m=5,r=4,b=7,v=1): not supported [SYCL] 
  GET_ROWS(type=iq2_xs,n=256,m=5,r=4,b=1,v=0): not supported [SYCL] 
  GET_ROWS(type=iq2_xs,n=256,m=5,r=4,b=1,v=1): not supported [SYCL] 
  GET_ROWS(type=iq2_xs,n=256,m=5,r=4,b=7,v=0): not supported [SYCL] 
  GET_ROWS(type=iq2_xs,n=256,m=5,r=4,b=7,v=1): not supported [SYCL] 
  GET_ROWS(type=iq2_s,n=256,m=5,r=4,b=1,v=0): not supported [SYCL] 
  GET_ROWS(type=iq2_s,n=256,m=5,r=4,b=1,v=1): not supported [SYCL] 
  GET_ROWS(type=iq2_s,n=256,m=5,r=4,b=7,v=0): not supported [SYCL] 
  GET_ROWS(type=iq2_s,n=256,m=5,r=4,b=7,v=1): not supported [SYCL] 
  GET_ROWS(type=iq3_xxs,n=256,m=5,r=4,b=1,v=0): not supported [SYCL] 
  GET_ROWS(type=iq3_xxs,n=256,m=5,r=4,b=1,v=1): not supported [SYCL] 
  GET_ROWS(type=iq3_xxs,n=256,m=5,r=4,b=7,v=0): not supported [SYCL] 
  GET_ROWS(type=iq3_xxs,n=256,m=5,r=4,b=7,v=1): not supported [SYCL] 
  GET_ROWS(type=iq1_s,n=256,m=5,r=4,b=1,v=0): not supported [SYCL] 
  GET_ROWS(type=iq1_s,n=256,m=5,r=4,b=1,v=1): not supported [SYCL] 
  GET_ROWS(type=iq1_s,n=256,m=5,r=4,b=7,v=0): not supported [SYCL] 
  GET_ROWS(type=iq1_s,n=256,m=5,r=4,b=7,v=1): not supported [SYCL] 
  GET_ROWS(type=iq4_nl,n=256,m=5,r=4,b=1,v=0): not supported [SYCL] 
  GET_ROWS(type=iq4_nl,n=256,m=5,r=4,b=1,v=1): not supported [SYCL] 
  GET_ROWS(type=iq4_nl,n=256,m=5,r=4,b=7,v=0): not supported [SYCL] 
  GET_ROWS(type=iq4_nl,n=256,m=5,r=4,b=7,v=1): not supported [SYCL] 
  GET_ROWS(type=iq3_s,n=256,m=5,r=4,b=1,v=0): not supported [SYCL] 
  GET_ROWS(type=iq3_s,n=256,m=5,r=4,b=1,v=1): not supported [SYCL] 
  GET_ROWS(type=iq3_s,n=256,m=5,r=4,b=7,v=0): not supported [SYCL] 
  GET_ROWS(type=iq3_s,n=256,m=5,r=4,b=7,v=1): not supported [SYCL] 
  GET_ROWS(type=iq4_xs,n=256,m=5,r=4,b=1,v=0): not supported [SYCL] 
  GET_ROWS(type=iq4_xs,n=256,m=5,r=4,b=1,v=1): not supported [SYCL] 
  GET_ROWS(type=iq4_xs,n=256,m=5,r=4,b=7,v=0): not supported [SYCL] 
  GET_ROWS(type=iq4_xs,n=256,m=5,r=4,b=7,v=1): not supported [SYCL] 
  GET_ROWS(type=i32,n=256,m=5,r=4,b=1,v=0): not supported [SYCL] 
  GET_ROWS(type=i32,n=256,m=5,r=4,b=1,v=1): not supported [SYCL] 
  GET_ROWS(type=i32,n=256,m=5,r=4,b=7,v=0): not supported [SYCL] 
  GET_ROWS(type=i32,n=256,m=5,r=4,b=7,v=1): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=1,s1=1,p0=0,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=1,s1=1,p0=0,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=1,s1=1,p0=1,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=1,s1=1,p0=1,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=1,s1=2,p0=0,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=1,s1=2,p0=0,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=1,s1=2,p0=1,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=1,s1=2,p0=1,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=2,s1=1,p0=0,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=2,s1=1,p0=0,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=2,s1=1,p0=1,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=2,s1=1,p0=1,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=2,s1=2,p0=0,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=2,s1=2,p0=0,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=2,s1=2,p0=1,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=2,s1=2,p0=1,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=1,s1=1,p0=0,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=1,s1=1,p0=0,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=1,s1=1,p0=1,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=1,s1=1,p0=1,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=1,s1=2,p0=0,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=1,s1=2,p0=0,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=1,s1=2,p0=1,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=1,s1=2,p0=1,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=2,s1=1,p0=0,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=2,s1=1,p0=0,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=2,s1=1,p0=1,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=2,s1=1,p0=1,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=2,s1=2,p0=0,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=2,s1=2,p0=0,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=2,s1=2,p0=1,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=2,s1=2,p0=1,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=1,s1=1,p0=0,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=1,s1=1,p0=0,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=1,s1=1,p0=1,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=1,s1=1,p0=1,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=1,s1=2,p0=0,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=1,s1=2,p0=0,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=1,s1=2,p0=1,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=1,s1=2,p0=1,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=2,s1=1,p0=0,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=2,s1=1,p0=0,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=2,s1=1,p0=1,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=2,s1=1,p0=1,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=2,s1=2,p0=0,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=2,s1=2,p0=0,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=2,s1=2,p0=1,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=2,s1=2,p0=1,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=1,s1=1,p0=0,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=1,s1=1,p0=0,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=1,s1=1,p0=1,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=1,s1=1,p0=1,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=1,s1=2,p0=0,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=1,s1=2,p0=0,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=1,s1=2,p0=1,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=1,s1=2,p0=1,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=2,s1=1,p0=0,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=2,s1=1,p0=0,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=2,s1=1,p0=1,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=2,s1=1,p0=1,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=2,s1=2,p0=0,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=2,s1=2,p0=0,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=2,s1=2,p0=1,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=avg,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=2,s1=2,p0=1,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=1,s1=1,p0=0,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=1,s1=1,p0=0,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=1,s1=1,p0=1,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=1,s1=1,p0=1,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=1,s1=2,p0=0,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=1,s1=2,p0=0,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=1,s1=2,p0=1,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=1,s1=2,p0=1,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=2,s1=1,p0=0,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=2,s1=1,p0=0,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=2,s1=1,p0=1,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=2,s1=1,p0=1,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=2,s1=2,p0=0,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=2,s1=2,p0=0,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=2,s1=2,p0=1,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=1,s0=2,s1=2,p0=1,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=1,s1=1,p0=0,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=1,s1=1,p0=0,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=1,s1=1,p0=1,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=1,s1=1,p0=1,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=1,s1=2,p0=0,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=1,s1=2,p0=0,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=1,s1=2,p0=1,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=1,s1=2,p0=1,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=2,s1=1,p0=0,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=2,s1=1,p0=0,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=2,s1=1,p0=1,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=2,s1=1,p0=1,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=2,s1=2,p0=0,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=2,s1=2,p0=0,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=2,s1=2,p0=1,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=1,k1=3,s0=2,s1=2,p0=1,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=1,s1=1,p0=0,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=1,s1=1,p0=0,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=1,s1=1,p0=1,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=1,s1=1,p0=1,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=1,s1=2,p0=0,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=1,s1=2,p0=0,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=1,s1=2,p0=1,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=1,s1=2,p0=1,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=2,s1=1,p0=0,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=2,s1=1,p0=0,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=2,s1=1,p0=1,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=2,s1=1,p0=1,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=2,s1=2,p0=0,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=2,s1=2,p0=0,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=2,s1=2,p0=1,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=1,s0=2,s1=2,p0=1,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=1,s1=1,p0=0,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=1,s1=1,p0=0,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=1,s1=1,p0=1,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=1,s1=1,p0=1,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=1,s1=2,p0=0,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=1,s1=2,p0=0,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=1,s1=2,p0=1,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=1,s1=2,p0=1,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=2,s1=1,p0=0,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=2,s1=1,p0=0,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=2,s1=1,p0=1,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=2,s1=1,p0=1,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=2,s1=2,p0=0,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=2,s1=2,p0=0,p1=1): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=2,s1=2,p0=1,p1=0): not supported [SYCL] 
  POOL_2D(pool_type=max,type_input=f32,ne_input=[10,10,3,1],k0=3,k1=3,s0=2,s1=2,p0=1,p1=1): not supported [SYCL] 
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
  CPY(type_src=f16,type_dst=f32,ne=[256,4,4,4]): not supported [SYCL] 
  CPY(type_src=f16,type_dst=f16,ne=[256,4,4,4]): [1;32mOK[0m
  CPY(type_src=f16,type_dst=q4_0,ne=[256,4,4,4]): not supported [SYCL] 
  CPY(type_src=f16,type_dst=q4_1,ne=[256,4,4,4]): not supported [SYCL] 
  CPY(type_src=f16,type_dst=q5_0,ne=[256,4,4,4]): not supported [SYCL] 
  CPY(type_src=f16,type_dst=q5_1,ne=[256,4,4,4]): not supported [SYCL] 
  CPY(type_src=f16,type_dst=q8_0,ne=[256,4,4,4]): not supported [SYCL] 
  CPY(type_src=f16,type_dst=q2_K,ne=[256,4,4,4]): not supported [SYCL] 
  CPY(type_src=f16,type_dst=q3_K,ne=[256,4,4,4]): not supported [SYCL] 
  CPY(type_src=f16,type_dst=q4_K,ne=[256,4,4,4]): not supported [SYCL] 
  CPY(type_src=f16,type_dst=q5_K,ne=[256,4,4,4]): not supported [SYCL] 
  CPY(type_src=f16,type_dst=q6_K,ne=[256,4,4,4]): not supported [SYCL] 
  CPY(type_src=f16,type_dst=iq2_xxs,ne=[256,4,4,4]): not supported [SYCL] not supported [CPU] 
  CPY(type_src=f16,type_dst=iq2_xs,ne=[256,4,4,4]): not supported [SYCL] not supported [CPU] 
  CPY(type_src=f16,type_dst=iq2_s,ne=[256,4,4,4]): not supported [SYCL] 
  CPY(type_src=f16,type_dst=iq3_xxs,ne=[256,4,4,4]): not supported [SYCL] 
  CPY(type_src=f16,type_dst=iq1_s,ne=[256,4,4,4]): not supported [SYCL] not supported [CPU] 
  CPY(type_src=f16,type_dst=iq4_nl,ne=[256,4,4,4]): not supported [SYCL] 
  CPY(type_src=f16,type_dst=iq3_s,ne=[256,4,4,4]): not supported [SYCL] 
  CPY(type_src=f16,type_dst=iq4_xs,ne=[256,4,4,4]): not supported [SYCL] 
  CPY(type_src=f32,type_dst=f32,ne=[256,4,4,4]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=f16,ne=[256,4,4,4]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=q4_0,ne=[256,4,4,4]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=q4_1,ne=[256,4,4,4]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=q5_0,ne=[256,4,4,4]): not supported [SYCL] 
  CPY(type_src=f32,type_dst=q5_1,ne=[256,4,4,4]): not supported [SYCL] 
  CPY(type_src=f32,type_dst=q8_0,ne=[256,4,4,4]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=q2_K,ne=[256,4,4,4]): not supported [SYCL] 
  CPY(type_src=f32,type_dst=q3_K,ne=[256,4,4,4]): not supported [SYCL] 
  CPY(type_src=f32,type_dst=q4_K,ne=[256,4,4,4]): not supported [SYCL] 
  CPY(type_src=f32,type_dst=q5_K,ne=[256,4,4,4]): not supported [SYCL] 
  CPY(type_src=f32,type_dst=q6_K,ne=[256,4,4,4]): not supported [SYCL] 
  CPY(type_src=f32,type_dst=iq2_xxs,ne=[256,4,4,4]): not supported [SYCL] not supported [CPU] 
  CPY(type_src=f32,type_dst=iq2_xs,ne=[256,4,4,4]): not supported [SYCL] not supported [CPU] 
  CPY(type_src=f32,type_dst=iq2_s,ne=[256,4,4,4]): not supported [SYCL] 
  CPY(type_src=f32,type_dst=iq3_xxs,ne=[256,4,4,4]): not supported [SYCL] 
  CPY(type_src=f32,type_dst=iq1_s,ne=[256,4,4,4]): not supported [SYCL] not supported [CPU] 
  CPY(type_src=f32,type_dst=iq4_nl,ne=[256,4,4,4]): not supported [SYCL] 
  CPY(type_src=f32,type_dst=iq3_s,ne=[256,4,4,4]): not supported [SYCL] 
  CPY(type_src=f32,type_dst=iq4_xs,ne=[256,4,4,4]): not supported [SYCL] 
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
  NORM(type=f32,ne=[64,10,10,10],eps=0.000001): warning: <unknown>:0:0: loop not unrolled: the optimizer was unable to perform the requested transformation; the transformation might be disabled or specified as part of an unsupported transformation ordering
warning: <unknown>:0:0: loop not unrolled: the optimizer was unable to perform the requested transformation; the transformation might be disabled or specified as part of an unsupported transformation ordering
warning: <unknown>:0:0: loop not unrolled: the optimizer was unable to perform the requested transformation; the transformation might be disabled or specified as part of an unsupported transformation ordering
warning: <unknown>:0:0: loop not unrolled: the optimizer was unable to perform the requested transformation; the transformation might be disabled or specified as part of an unsupported transformation ordering
The program was built for 1 devices
Build program log for '12th Gen Intel(R) Core(TM) i5-1250P':
Compilation started
Compilation done
Linking started
Linking done
Device build started
Options used by backend compiler: 
Failed to build device program
CompilerException Failed to lookup symbol _ZTSZZL22soft_max_f32_submitterILb1ELi0ELi0EEvPKfS1_S1_PfiiffffjN4sycl3_V15rangeILi3EEES6_mPNS4_5queueEENKUlRNS4_7handlerEE_clESA_EUlNS4_7nd_itemILi3EEEE_
JIT session error: Symbols not found: [ _Z11fmax_commonDv32_fS_S_ ]
Failed to materialize symbols: { (main, { _ZTSZZL22soft_max_f32_submitterILb1ELi0ELi0EEvPKfS1_S1_PfiiffffjN4sycl3_V15rangeILi3EEES6_mPNS4_5queueEENKUlRNS4_7handlerEE_clESA_EUlNS4_7nd_itemILi3EEEE_, _ZTSZZL22soft_max_f32_submitterILb1ELi32ELi32EEvPKfS1_S1_PfiiffffjN4sycl3_V15rangeILi3EEES6_mPNS4_5queueEENKUlRNS4_7handlerEE_clESA_EUlNS4_7nd_itemILi3EEEE_, _ZTSZZL22soft_max_f32_submitterILb0ELi0ELi0EEvPKfS1_S1_PfiiffffjN4sycl3_V15rangeILi3EEES6_mPNS4_5queueEENKUlRNS4_7handlerEE_clESA_EUlNS4_7nd_itemILi3EEEE_, _ZGVdN32uuuuuu__ZTSZZL19group_norm_f32_syclPKfPfiiiPN4sycl3_V15queueEENKUlRNS3_7handlerEE0_clES7_EUlNS3_7nd_itemILi3EEEE_, _ZTSZZL22soft_max_f32_submitterILb1ELi256ELi256EEvPKfS1_S1_PfiiffffjN4sycl3_V15rangeILi3EEES6_mPNS4_5queueEENKUlRNS4_7handlerEE_clESA_EUlNS4_7nd_itemILi3EEEE_, _ZGVdN32uuuuuuuuuuuu__ZTSZZL22soft_max_f32_submitterILb0ELi0ELi0EEvPKfS1_S1_PfiiffffjN4sycl3_V15rangeILi3EEES6_mPNS4_5queueEENKUlRNS4_7handlerEE_clESA_EUlNS4_7nd_itemILi3EEEE_, _ZTSZZL22soft_max_f32_submitterILb1ELi2048ELi1024EEvPKfS1_S1_PfiiffffjN4sycl3_V15rangeILi3EEES6_mPNS4_5queueEENKUlRNS4_7handlerEE_clESA_EUlNS4_7nd_itemILi3EEEE_, _ZGVdN32uuuuuu__ZTSZZL13norm_f32_syclPKfPfiifPN4sycl3_V15queueEENKUlRNS3_7handlerEE0_clES7_EUlNS3_7nd_itemILi3EEEE_, _ZTSZZL13norm_f32_syclPKfPfiifPN4sycl3_V15queueEENKUlRNS3_7handlerEE_clES7_EUlNS3_7nd_itemILi3EEEE_, _ZGVdN32uuuuuuuuuuu__ZTSZZL22soft_max_f32_submitterILb1ELi512ELi512EEvPKfS1_S1_PfiiffffjN4sycl3_V15rangeILi3EEES6_mPNS4_5queueEENKUlRNS4_7handlerEE_clESA_EUlNS4_7nd_itemILi3EEEE_, _ZGVdN32uuuuuuuuuuu__ZTSZZL22soft_max_f32_submitterILb1ELi2048ELi1024EEvPKfS1_S1_PfiiffffjN4sycl3_V15rangeILi3EEES6_mPNS4_5queueEENKUlRNS4_7handlerEE_clESA_EUlNS4_7nd_itemILi3EEEE_, _ZTSZZL19group_norm_f32_syclPKfPfiiiPN4sycl3_V15queueEENKUlRNS3_7handlerEE0_clES7_EUlNS3_7nd_itemILi3EEEE_, _ZTSZZL13norm_f32_syclPKfPfiifPN4sycl3_V15queueEENKUlRNS3_7handlerEE0_clES7_EUlNS3_7nd_itemILi3EEEE_, _ZTSZZL22soft_max_f32_submitterILb1ELi128ELi128EEvPKfS1_S1_PfiiffffjN4sycl3_V15rangeILi3EEES6_mPNS4_5queueEENKUlRNS4_7handlerEE_clESA_EUlNS4_7nd_itemILi3EEEE_, _ZGVdN32uuuuuuuuuuu__ZTSZZL22soft_max_f32_submitterILb1ELi4096ELi1024EEvPKfS1_S1_PfiiffffjN4sycl3_V15rangeILi3EEES6_mPNS4_5queueEENKUlRNS4_7handlerEE_clESA_EUlNS4_7nd_itemILi3EEEE_, _ZTSZZL22soft_max_f32_submitterILb1ELi4096ELi1024EEvPKfS1_S1_PfiiffffjN4sycl3_V15rangeILi3EEES6_mPNS4_5queueEENKUlRNS4_7handlerEE_clESA_EUlNS4_7nd_itemILi3EEEE_, _ZGVdN32uuuuuuuuuuu__ZTSZZL22soft_max_f32_submitterILb1ELi128ELi128EEvPKfS1_S1_PfiiffffjN4sycl3_V15rangeILi3EEES6_mPNS4_5queueEENKUlRNS4_7handlerEE_clESA_EUlNS4_7nd_itemILi3EEEE_, _ZGVdN32uuuuuuuuuuu__ZTSZZL22soft_max_f32_submitterILb1ELi64ELi64EEvPKfS1_S1_PfiiffffjN4sycl3_V15rangeILi3EEES6_mPNS4_5queueEENKUlRNS4_7handlerEE_clESA_EUlNS4_7nd_itemILi3EEEE_, _ZGVdN32uuuuuuuuuuuu__ZTSZZL22soft_max_f32_submitterILb1ELi0ELi0EEvPKfS1_S1_PfiiffffjN4sycl3_V15rangeILi3EEES6_mPNS4_5queueEENKUlRNS4_7handlerEE_clESA_EUlNS4_7nd_itemILi3EEEE_, _ZTSZL17sum_rows_f32_syclPKfPfiiPN4sycl3_V15queueEEUlNS3_7nd_itemILi3EEEE_, _ZGVdN32uuuuuuuuuuu__ZTSZZL22soft_max_f32_submitterILb1ELi256ELi256EEvPKfS1_S1_PfiiffffjN4sycl3_V15rangeILi3EEES6_mPNS4_5queueEENKUlRNS4_7handlerEE_clESA_EUlNS4_7nd_itemILi3EEEE_, _ZGVdN32uuuuuu__ZTSZZL17rms_norm_f32_syclPKfPfiifPN4sycl3_V15queueEENKUlRNS3_7handlerEE0_clES7_EUlNS3_7nd_itemILi3EEEE_, _ZGVdN32uuuuuuuuuuu__ZTSZZL22soft_max_f32_submitterILb1ELi1024ELi1024EEvPKfS1_S1_PfiiffffjN4sycl3_V15rangeILi3EEES6_mPNS4_5queueEENKUlRNS4_7handlerEE_clESA_EUlNS4_7nd_itemILi3EEEE_, _ZTSZZL22soft_max_f32_submitterILb1ELi64ELi64EEvPKfS1_S1_PfiiffffjN4sycl3_V15rangeILi3EEES6_mPNS4_5queueEENKUlRNS4_7handlerEE_clESA_EUlNS4_7nd_itemILi3EEEE_, _ZTSZZL17rms_norm_f32_syclPKfPfiifPN4sycl3_V15queueEENKUlRNS3_7handlerEE_clES7_EUlNS3_7nd_itemILi3EEEE_, _ZTSZZL22soft_max_f32_submitterILb1ELi1024ELi1024EEvPKfS1_S1_PfiiffffjN4sycl3_V15rangeILi3EEES6_mPNS4_5queueEENKUlRNS4_7handlerEE_clESA_EUlNS4_7nd_itemILi3EEEE_, _ZTSZZL22soft_max_f32_submitterILb1ELi512ELi512EEvPKfS1_S1_PfiiffffjN4sycl3_V15rangeILi3EEES6_mPNS4_5queueEENKUlRNS4_7handlerEE_clESA_EUlNS4_7nd_itemILi3EEEE_, _ZTSZZL19group_norm_f32_syclPKfPfiiiPN4sycl3_V15queueEENKUlRNS3_7handlerEE_clES7_EUlNS3_7nd_itemILi3EEEE_, _ZTSZZL17rms_norm_f32_syclPKfPfiifPN4sycl3_V15queueEENKUlRNS3_7handlerEE0_clES7_EUlNS3_7nd_itemILi3EEEE_ }) }

 -11 (PI_ERROR_BUILD_PROGRAM_FAILURE)Exception caught at file:/var/jenkins_home/workspace/llama.cpp/llama.cpp/ggml-sycl.cpp, line:12661

      Start 21: test-rope
21/21 Test #21: test-rope ...........................   Passed    0.14 sec

95% tests passed, 1 tests failed out of 21

Label Time Summary:
main    =  51.39 sec*proc (21 tests)

Total Test time (real) =  51.40 sec

The following tests FAILED:
	 20 - test-backend-ops (Failed)
Errors while running CTest

real	0m51.404s
user	1m4.521s
sys	0m8.634s
```
