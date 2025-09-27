### ctest_release

Runs ctest in release mode
- status: 8
```
+ ctest --output-on-failure -L main
Test project /home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/build-ci-release
      Start  1: test-tokenizer-0-bert-bge
 1/35 Test  #1: test-tokenizer-0-bert-bge .........   Passed    0.08 sec
      Start  2: test-tokenizer-0-command-r
 2/35 Test  #2: test-tokenizer-0-command-r ........   Passed    0.39 sec
      Start  3: test-tokenizer-0-deepseek-coder
 3/35 Test  #3: test-tokenizer-0-deepseek-coder ...   Passed    0.10 sec
      Start  4: test-tokenizer-0-deepseek-llm
 4/35 Test  #4: test-tokenizer-0-deepseek-llm .....   Passed    0.16 sec
      Start  5: test-tokenizer-0-falcon
 5/35 Test  #5: test-tokenizer-0-falcon ...........   Passed    0.12 sec
      Start  6: test-tokenizer-0-gpt-2
 6/35 Test  #6: test-tokenizer-0-gpt-2 ............   Passed    0.11 sec
      Start  7: test-tokenizer-0-llama-bpe
 7/35 Test  #7: test-tokenizer-0-llama-bpe ........   Passed    0.28 sec
      Start  8: test-tokenizer-0-llama-spm
 8/35 Test  #8: test-tokenizer-0-llama-spm ........   Passed    0.08 sec
      Start  9: test-tokenizer-0-mpt
 9/35 Test  #9: test-tokenizer-0-mpt ..............   Passed    0.11 sec
      Start 10: test-tokenizer-0-phi-3
10/35 Test #10: test-tokenizer-0-phi-3 ............   Passed    0.08 sec
      Start 11: test-tokenizer-0-qwen2
11/35 Test #11: test-tokenizer-0-qwen2 ............   Passed    0.26 sec
      Start 12: test-tokenizer-0-refact
12/35 Test #12: test-tokenizer-0-refact ...........   Passed    0.11 sec
      Start 13: test-tokenizer-0-starcoder
13/35 Test #13: test-tokenizer-0-starcoder ........   Passed    0.11 sec
      Start 14: test-tokenizers-ggml-vocabs
14/35 Test #14: test-tokenizers-ggml-vocabs .......***Failed    2.48 sec
Already up to date.
main : reading vocab from: '/home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/models/ggml-vocabs/PLaMo2/ggml-vocab-plamo2.gguf'
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
llama_model_load_from_file_impl: using device SYCL0 (Intel(R) UHD Graphics 730) - 14265 MiB free
gguf_init_from_file_impl: invalid magic characters: 'vers', expected 'GGUF'
llama_model_load: error loading model: llama_model_loader: failed to load model from /home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/models/ggml-vocabs/PLaMo2/ggml-vocab-plamo2.gguf
llama_model_load_from_file_impl: failed to load model
main: error: failed to load vocab '/home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/models/ggml-vocabs/PLaMo2/ggml-vocab-plamo2.gguf'
main : reading vocab from: '/home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/models/ggml-vocabs/RWKV/ggml-vocab-rwkv-7-world.gguf'
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
llama_model_load_from_file_impl: using device SYCL0 (Intel(R) UHD Graphics 730) - 14265 MiB free
gguf_init_from_file_impl: invalid magic characters: 'vers', expected 'GGUF'
llama_model_load: error loading model: llama_model_loader: failed to load model from /home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/models/ggml-vocabs/RWKV/ggml-vocab-rwkv-7-world.gguf
llama_model_load_from_file_impl: failed to load model
main: error: failed to load vocab '/home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/models/ggml-vocabs/RWKV/ggml-vocab-rwkv-7-world.gguf'
main : reading vocab from: '/home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/models/ggml-vocabs/SPM/ggml-vocab-gemma-3.gguf'
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
llama_model_load_from_file_impl: using device SYCL0 (Intel(R) UHD Graphics 730) - 14265 MiB free
gguf_init_from_file_impl: invalid magic characters: 'vers', expected 'GGUF'
llama_model_load: error loading model: llama_model_loader: failed to load model from /home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/models/ggml-vocabs/SPM/ggml-vocab-gemma-3.gguf
llama_model_load_from_file_impl: failed to load model
main: error: failed to load vocab '/home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/models/ggml-vocabs/SPM/ggml-vocab-gemma-3.gguf'
main : reading vocab from: '/home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/models/ggml-vocabs/UGM/ggml-vocab-nomic-bert-moe.gguf'
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
llama_model_load_from_file_impl: using device SYCL0 (Intel(R) UHD Graphics 730) - 14265 MiB free
gguf_init_from_file_impl: invalid magic characters: 'vers', expected 'GGUF'
llama_model_load: error loading model: llama_model_loader: failed to load model from /home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/models/ggml-vocabs/UGM/ggml-vocab-nomic-bert-moe.gguf
llama_model_load_from_file_impl: failed to load model
main: error: failed to load vocab '/home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/models/ggml-vocabs/UGM/ggml-vocab-nomic-bert-moe.gguf'
main : reading vocab from: '/home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/models/ggml-vocabs/WPM/ggml-vocab-jina-v2-en.gguf'
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
llama_model_load_from_file_impl: using device SYCL0 (Intel(R) UHD Graphics 730) - 14265 MiB free
gguf_init_from_file_impl: invalid magic characters: 'vers', expected 'GGUF'
llama_model_load: error loading model: llama_model_loader: failed to load model from /home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/models/ggml-vocabs/WPM/ggml-vocab-jina-v2-en.gguf
llama_model_load_from_file_impl: failed to load model
main: error: failed to load vocab '/home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/models/ggml-vocabs/WPM/ggml-vocab-jina-v2-en.gguf'

      Start 15: test-sampling
15/35 Test #15: test-sampling .....................   Passed    1.06 sec
      Start 16: test-grammar-parser
16/35 Test #16: test-grammar-parser ...............   Passed    0.04 sec
      Start 17: test-grammar-integration
17/35 Test #17: test-grammar-integration ..........   Passed    0.04 sec
      Start 18: test-llama-grammar
18/35 Test #18: test-llama-grammar ................   Passed    0.04 sec
      Start 19: test-chat
19/35 Test #19: test-chat .........................   Passed    0.45 sec
      Start 20: test-json-schema-to-grammar
20/35 Test #20: test-json-schema-to-grammar .......   Passed    1.91 sec
      Start 21: test-tokenizer-1-llama-spm
21/35 Test #21: test-tokenizer-1-llama-spm ........   Passed    0.18 sec
      Start 22: test-chat-parser
22/35 Test #22: test-chat-parser ..................   Passed    0.04 sec
      Start 23: test-chat-template
23/35 Test #23: test-chat-template ................   Passed    0.11 sec
      Start 24: test-json-partial
24/35 Test #24: test-json-partial .................   Passed    0.03 sec
      Start 25: test-log
25/35 Test #25: test-log ..........................   Passed    0.05 sec
      Start 26: test-regex-partial
26/35 Test #26: test-regex-partial ................   Passed    0.04 sec
      Start 27: test-thread-safety
27/35 Test #27: test-thread-safety ................***Failed    0.06 sec
error: built without CURL, cannot download model from the internet
error: failed to download model from https://huggingface.co/ggml-org/models/resolve/main/tinyllamas/stories15M-q4_0.gguf

      Start 28: test-arg-parser
28/35 Test #28: test-arg-parser ...................   Passed    0.08 sec
      Start 29: test-gguf
29/35 Test #29: test-gguf .........................   Passed    0.23 sec
      Start 30: test-backend-ops
30/35 Test #30: test-backend-ops ..................***Failed   30.68 sec
Running with Environment Variables:
  GGML_SYCL_DEBUG: 0
  GGML_SYCL_DISABLE_OPT: 0
  GGML_SYCL_DISABLE_GRAPH: 1
  GGML_SYCL_DISABLE_DNN: 0
  GGML_SYCL_PRIORITIZE_DMMV: 0
Build with Macros:
  GGML_SYCL_FORCE_MMQ: no
  GGML_SYCL_F16: yes
Found 1 SYCL devices:
|  |                   |                                       |       |Max    |        |Max  |Global |                     |
|  |                   |                                       |       |compute|Max work|sub  |mem    |                     |
|ID|        Device Type|                                   Name|Version|units  |group   |group|size   |       Driver version|
|--|-------------------|---------------------------------------|-------|-------|--------|-----|-------|---------------------|
| 0| [level_zero:gpu:0]|                 Intel UHD Graphics 730|   12.2|     32|     512|   32| 14958M|         1.3.29735+27|
SYCL Optimization Feature:
|ID|        Device Type|Reorder|
|--|-------------------|-------|
| 0| [level_zero:gpu:0]|      Y|
Testing 2 devices

get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
Backend 1/2: SYCL0
  Device description: Intel(R) UHD Graphics 730
  Device memory: 14265 MB (14265 MB free)

  ABS(type=f16,ne_a=[128,2,2,2],v=0): [1;32mOK[0m
  ABS(type=f16,ne_a=[5,7,11,13],v=0): [1;32mOK[0m
  SGN(type=f16,ne_a=[128,2,2,2],v=0): [1;32mOK[0m
  SGN(type=f16,ne_a=[5,7,11,13],v=0): [1;32mOK[0m
  NEG(type=f16,ne_a=[128,2,2,2],v=0): [1;32mOK[0m
  NEG(type=f16,ne_a=[5,7,11,13],v=0): [1;32mOK[0m
  STEP(type=f16,ne_a=[128,2,2,2],v=0): [1;32mOK[0m
  STEP(type=f16,ne_a=[5,7,11,13],v=0): [1;32mOK[0m
  TANH(type=f16,ne_a=[128,2,2,2],v=0): [1;32mOK[0m
  TANH(type=f16,ne_a=[5,7,11,13],v=0): [1;32mOK[0m
  ELU(type=f16,ne_a=[128,2,2,2],v=0): [1;32mOK[0m
  ELU(type=f16,ne_a=[5,7,11,13],v=0): [1;32mOK[0m
  RELU(type=f16,ne_a=[128,2,2,2],v=0): [1;32mOK[0m
  RELU(type=f16,ne_a=[5,7,11,13],v=0): [1;32mOK[0m
  SIGMOID(type=f16,ne_a=[128,2,2,2],v=0): [1;32mOK[0m
  SIGMOID(type=f16,ne_a=[5,7,11,13],v=0): [1;32mOK[0m
  GELU(type=f16,ne_a=[128,2,2,2],v=0): [1;32mOK[0m
  GELU(type=f16,ne_a=[5,7,11,13],v=0): [1;32mOK[0m
  GELU_QUICK(type=f16,ne_a=[128,2,2,2],v=0): [1;32mOK[0m
  GELU_QUICK(type=f16,ne_a=[5,7,11,13],v=0): [1;32mOK[0m
  SILU(type=f16,ne_a=[128,2,2,2],v=0): [1;32mOK[0m
  SILU(type=f16,ne_a=[5,7,11,13],v=0): [1;32mOK[0m
  HARDSWISH(type=f16,ne_a=[128,2,2,2],v=0): [1;32mOK[0m
  HARDSWISH(type=f16,ne_a=[5,7,11,13],v=0): [1;32mOK[0m
  HARDSIGMOID(type=f16,ne_a=[128,2,2,2],v=0): [1;32mOK[0m
  HARDSIGMOID(type=f16,ne_a=[5,7,11,13],v=0): [1;32mOK[0m
  EXP(type=f16,ne_a=[128,2,2,2],v=0): [1;32mOK[0m
  EXP(type=f16,ne_a=[5,7,11,13],v=0): [1;32mOK[0m
  GELU_ERF(type=f16,ne_a=[128,2,2,2],v=0): [1;32mOK[0m
  GELU_ERF(type=f16,ne_a=[5,7,11,13],v=0): [1;32mOK[0m
  ABS(type=f16,ne_a=[128,2,2,2],v=1): not supported [SYCL0] 
  ABS(type=f16,ne_a=[5,7,11,13],v=1): not supported [SYCL0] 
  SGN(type=f16,ne_a=[128,2,2,2],v=1): not supported [SYCL0] 
  SGN(type=f16,ne_a=[5,7,11,13],v=1): not supported [SYCL0] 
  NEG(type=f16,ne_a=[128,2,2,2],v=1): not supported [SYCL0] 
  NEG(type=f16,ne_a=[5,7,11,13],v=1): not supported [SYCL0] 
  STEP(type=f16,ne_a=[128,2,2,2],v=1): not supported [SYCL0] 
  STEP(type=f16,ne_a=[5,7,11,13],v=1): not supported [SYCL0] 
  TANH(type=f16,ne_a=[128,2,2,2],v=1): not supported [SYCL0] 
  TANH(type=f16,ne_a=[5,7,11,13],v=1): not supported [SYCL0] 
  ELU(type=f16,ne_a=[128,2,2,2],v=1): not supported [SYCL0] 
  ELU(type=f16,ne_a=[5,7,11,13],v=1): not supported [SYCL0] 
  RELU(type=f16,ne_a=[128,2,2,2],v=1): not supported [SYCL0] 
  RELU(type=f16,ne_a=[5,7,11,13],v=1): not supported [SYCL0] 
  SIGMOID(type=f16,ne_a=[128,2,2,2],v=1): not supported [SYCL0] 
  SIGMOID(type=f16,ne_a=[5,7,11,13],v=1): not supported [SYCL0] 
  GELU(type=f16,ne_a=[128,2,2,2],v=1): not supported [SYCL0] 
  GELU(type=f16,ne_a=[5,7,11,13],v=1): not supported [SYCL0] 
  GELU_QUICK(type=f16,ne_a=[128,2,2,2],v=1): not supported [SYCL0] 
  GELU_QUICK(type=f16,ne_a=[5,7,11,13],v=1): not supported [SYCL0] 
  SILU(type=f16,ne_a=[128,2,2,2],v=1): not supported [SYCL0] 
  SILU(type=f16,ne_a=[5,7,11,13],v=1): not supported [SYCL0] 
  HARDSWISH(type=f16,ne_a=[128,2,2,2],v=1): not supported [SYCL0] 
  HARDSWISH(type=f16,ne_a=[5,7,11,13],v=1): not supported [SYCL0] 
  HARDSIGMOID(type=f16,ne_a=[128,2,2,2],v=1): not supported [SYCL0] 
  HARDSIGMOID(type=f16,ne_a=[5,7,11,13],v=1): not supported [SYCL0] 
  EXP(type=f16,ne_a=[128,2,2,2],v=1): not supported [SYCL0] 
  EXP(type=f16,ne_a=[5,7,11,13],v=1): not supported [SYCL0] 
  GELU_ERF(type=f16,ne_a=[128,2,2,2],v=1): not supported [SYCL0] 
  GELU_ERF(type=f16,ne_a=[5,7,11,13],v=1): not supported [SYCL0] 
  ABS(type=f32,ne_a=[128,2,2,2],v=0): [1;32mOK[0m
  ABS(type=f32,ne_a=[5,7,11,13],v=0): [1;32mOK[0m
  SGN(type=f32,ne_a=[128,2,2,2],v=0): [1;32mOK[0m
  SGN(type=f32,ne_a=[5,7,11,13],v=0): [1;32mOK[0m
  NEG(type=f32,ne_a=[128,2,2,2],v=0): [1;32mOK[0m
  NEG(type=f32,ne_a=[5,7,11,13],v=0): [1;32mOK[0m
  STEP(type=f32,ne_a=[128,2,2,2],v=0): [1;32mOK[0m
  STEP(type=f32,ne_a=[5,7,11,13],v=0): [1;32mOK[0m
  TANH(type=f32,ne_a=[128,2,2,2],v=0): [1;32mOK[0m
  TANH(type=f32,ne_a=[5,7,11,13],v=0): [1;32mOK[0m
  ELU(type=f32,ne_a=[128,2,2,2],v=0): [1;32mOK[0m
  ELU(type=f32,ne_a=[5,7,11,13],v=0): [1;32mOK[0m
  RELU(type=f32,ne_a=[128,2,2,2],v=0): [1;32mOK[0m
  RELU(type=f32,ne_a=[5,7,11,13],v=0): [1;32mOK[0m
  SIGMOID(type=f32,ne_a=[128,2,2,2],v=0): [1;32mOK[0m
  SIGMOID(type=f32,ne_a=[5,7,11,13],v=0): [1;32mOK[0m
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
  EXP(type=f32,ne_a=[128,2,2,2],v=0): [1;32mOK[0m
  EXP(type=f32,ne_a=[5,7,11,13],v=0): [1;32mOK[0m
  GELU_ERF(type=f32,ne_a=[128,2,2,2],v=0): [1;32mOK[0m
  GELU_ERF(type=f32,ne_a=[5,7,11,13],v=0): [1;32mOK[0m
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
  GELU_ERF(type=f32,ne_a=[128,2,2,2],v=1): not supported [SYCL0] 
  GELU_ERF(type=f32,ne_a=[5,7,11,13],v=1): not supported [SYCL0] 
  REGLU(type=f16,ne_a=[128,2,2,2],v=0,swapped=0): [1;32mOK[0m
  REGLU(type=f16,ne_a=[5,7,11,13],v=0,swapped=0): [1;32mOK[0m
  REGLU(type=f16,ne_a=[128,2,2,2],v=0,swapped=1): [1;32mOK[0m
  REGLU(type=f16,ne_a=[5,7,11,13],v=0,swapped=1): [1;32mOK[0m
  REGLU(type=f16,ne_a=[128,2,2,2],v=0,split): [1;32mOK[0m
  REGLU(type=f16,ne_a=[5,7,11,13],v=0,split): [1;32mOK[0m
  GEGLU(type=f16,ne_a=[128,2,2,2],v=0,swapped=0): [1;32mOK[0m
  GEGLU(type=f16,ne_a=[5,7,11,13],v=0,swapped=0): [1;32mOK[0m
  GEGLU(type=f16,ne_a=[128,2,2,2],v=0,swapped=1): [1;32mOK[0m
  GEGLU(type=f16,ne_a=[5,7,11,13],v=0,swapped=1): [1;32mOK[0m
  GEGLU(type=f16,ne_a=[128,2,2,2],v=0,split): [1;32mOK[0m
  GEGLU(type=f16,ne_a=[5,7,11,13],v=0,split): [1;32mOK[0m
  SWIGLU(type=f16,ne_a=[128,2,2,2],v=0,swapped=0): [1;32mOK[0m
  SWIGLU(type=f16,ne_a=[5,7,11,13],v=0,swapped=0): [1;32mOK[0m
  SWIGLU(type=f16,ne_a=[128,2,2,2],v=0,swapped=1): [1;32mOK[0m
  SWIGLU(type=f16,ne_a=[5,7,11,13],v=0,swapped=1): [1;32mOK[0m
  SWIGLU(type=f16,ne_a=[128,2,2,2],v=0,split): [1;32mOK[0m
  SWIGLU(type=f16,ne_a=[5,7,11,13],v=0,split): [1;32mOK[0m
  GEGLU_ERF(type=f16,ne_a=[128,2,2,2],v=0,swapped=0): [1;32mOK[0m
  GEGLU_ERF(type=f16,ne_a=[5,7,11,13],v=0,swapped=0): [1;32mOK[0m
  GEGLU_ERF(type=f16,ne_a=[128,2,2,2],v=0,swapped=1): [1;32mOK[0m
  GEGLU_ERF(type=f16,ne_a=[5,7,11,13],v=0,swapped=1): [1;32mOK[0m
  GEGLU_ERF(type=f16,ne_a=[128,2,2,2],v=0,split): [1;32mOK[0m
  GEGLU_ERF(type=f16,ne_a=[5,7,11,13],v=0,split): [1;32mOK[0m
  GEGLU_QUICK(type=f16,ne_a=[128,2,2,2],v=0,swapped=0): [1;32mOK[0m
  GEGLU_QUICK(type=f16,ne_a=[5,7,11,13],v=0,swapped=0): [1;32mOK[0m
  GEGLU_QUICK(type=f16,ne_a=[128,2,2,2],v=0,swapped=1): [1;32mOK[0m
  GEGLU_QUICK(type=f16,ne_a=[5,7,11,13],v=0,swapped=1): [1;32mOK[0m
  GEGLU_QUICK(type=f16,ne_a=[128,2,2,2],v=0,split): [1;32mOK[0m
  GEGLU_QUICK(type=f16,ne_a=[5,7,11,13],v=0,split): [1;32mOK[0m
  REGLU(type=f16,ne_a=[128,2,2,2],v=1,swapped=0): [1;32mOK[0m
  REGLU(type=f16,ne_a=[5,7,11,13],v=1,swapped=0): [1;32mOK[0m
  REGLU(type=f16,ne_a=[128,2,2,2],v=1,swapped=1): [1;32mOK[0m
  REGLU(type=f16,ne_a=[5,7,11,13],v=1,swapped=1): [1;32mOK[0m
  REGLU(type=f16,ne_a=[128,2,2,2],v=1,split): [1;32mOK[0m
  REGLU(type=f16,ne_a=[5,7,11,13],v=1,split): [1;32mOK[0m
  GEGLU(type=f16,ne_a=[128,2,2,2],v=1,swapped=0): [1;32mOK[0m
  GEGLU(type=f16,ne_a=[5,7,11,13],v=1,swapped=0): [1;32mOK[0m
  GEGLU(type=f16,ne_a=[128,2,2,2],v=1,swapped=1): [1;32mOK[0m
  GEGLU(type=f16,ne_a=[5,7,11,13],v=1,swapped=1): [1;32mOK[0m
  GEGLU(type=f16,ne_a=[128,2,2,2],v=1,split): [1;32mOK[0m
  GEGLU(type=f16,ne_a=[5,7,11,13],v=1,split): [1;32mOK[0m
  SWIGLU(type=f16,ne_a=[128,2,2,2],v=1,swapped=0): [1;32mOK[0m
  SWIGLU(type=f16,ne_a=[5,7,11,13],v=1,swapped=0): [1;32mOK[0m
  SWIGLU(type=f16,ne_a=[128,2,2,2],v=1,swapped=1): [1;32mOK[0m
  SWIGLU(type=f16,ne_a=[5,7,11,13],v=1,swapped=1): [1;32mOK[0m
  SWIGLU(type=f16,ne_a=[128,2,2,2],v=1,split): [1;32mOK[0m
  SWIGLU(type=f16,ne_a=[5,7,11,13],v=1,split): [1;32mOK[0m
  GEGLU_ERF(type=f16,ne_a=[128,2,2,2],v=1,swapped=0): [1;32mOK[0m
  GEGLU_ERF(type=f16,ne_a=[5,7,11,13],v=1,swapped=0): [1;32mOK[0m
  GEGLU_ERF(type=f16,ne_a=[128,2,2,2],v=1,swapped=1): [1;32mOK[0m
  GEGLU_ERF(type=f16,ne_a=[5,7,11,13],v=1,swapped=1): [1;32mOK[0m
  GEGLU_ERF(type=f16,ne_a=[128,2,2,2],v=1,split): [1;32mOK[0m
  GEGLU_ERF(type=f16,ne_a=[5,7,11,13],v=1,split): [1;32mOK[0m
  GEGLU_QUICK(type=f16,ne_a=[128,2,2,2],v=1,swapped=0): [1;32mOK[0m
  GEGLU_QUICK(type=f16,ne_a=[5,7,11,13],v=1,swapped=0): [1;32mOK[0m
  GEGLU_QUICK(type=f16,ne_a=[128,2,2,2],v=1,swapped=1): [1;32mOK[0m
  GEGLU_QUICK(type=f16,ne_a=[5,7,11,13],v=1,swapped=1): [1;32mOK[0m
  GEGLU_QUICK(type=f16,ne_a=[128,2,2,2],v=1,split): [1;32mOK[0m
  GEGLU_QUICK(type=f16,ne_a=[5,7,11,13],v=1,split): [1;32mOK[0m
  REGLU(type=f32,ne_a=[128,2,2,2],v=0,swapped=0): [1;32mOK[0m
  REGLU(type=f32,ne_a=[5,7,11,13],v=0,swapped=0): [1;32mOK[0m
  REGLU(type=f32,ne_a=[128,2,2,2],v=0,swapped=1): [1;32mOK[0m
  REGLU(type=f32,ne_a=[5,7,11,13],v=0,swapped=1): [1;32mOK[0m
  REGLU(type=f32,ne_a=[128,2,2,2],v=0,split): [1;32mOK[0m
  REGLU(type=f32,ne_a=[5,7,11,13],v=0,split): [1;32mOK[0m
  GEGLU(type=f32,ne_a=[128,2,2,2],v=0,swapped=0): [1;32mOK[0m
  GEGLU(type=f32,ne_a=[5,7,11,13],v=0,swapped=0): [1;32mOK[0m
  GEGLU(type=f32,ne_a=[128,2,2,2],v=0,swapped=1): [1;32mOK[0m
  GEGLU(type=f32,ne_a=[5,7,11,13],v=0,swapped=1): [1;32mOK[0m
  GEGLU(type=f32,ne_a=[128,2,2,2],v=0,split): [1;32mOK[0m
  GEGLU(type=f32,ne_a=[5,7,11,13],v=0,split): [1;32mOK[0m
  SWIGLU(type=f32,ne_a=[128,2,2,2],v=0,swapped=0): [1;32mOK[0m
  SWIGLU(type=f32,ne_a=[5,7,11,13],v=0,swapped=0): [1;32mOK[0m
  SWIGLU(type=f32,ne_a=[128,2,2,2],v=0,swapped=1): [1;32mOK[0m
  SWIGLU(type=f32,ne_a=[5,7,11,13],v=0,swapped=1): [1;32mOK[0m
  SWIGLU(type=f32,ne_a=[128,2,2,2],v=0,split): [1;32mOK[0m
  SWIGLU(type=f32,ne_a=[5,7,11,13],v=0,split): [1;32mOK[0m
  GEGLU_ERF(type=f32,ne_a=[128,2,2,2],v=0,swapped=0): [1;32mOK[0m
  GEGLU_ERF(type=f32,ne_a=[5,7,11,13],v=0,swapped=0): [1;32mOK[0m
  GEGLU_ERF(type=f32,ne_a=[128,2,2,2],v=0,swapped=1): [1;32mOK[0m
  GEGLU_ERF(type=f32,ne_a=[5,7,11,13],v=0,swapped=1): [1;32mOK[0m
  GEGLU_ERF(type=f32,ne_a=[128,2,2,2],v=0,split): [1;32mOK[0m
  GEGLU_ERF(type=f32,ne_a=[5,7,11,13],v=0,split): [1;32mOK[0m
  GEGLU_QUICK(type=f32,ne_a=[128,2,2,2],v=0,swapped=0): [1;32mOK[0m
  GEGLU_QUICK(type=f32,ne_a=[5,7,11,13],v=0,swapped=0): [1;32mOK[0m
  GEGLU_QUICK(type=f32,ne_a=[128,2,2,2],v=0,swapped=1): [1;32mOK[0m
  GEGLU_QUICK(type=f32,ne_a=[5,7,11,13],v=0,swapped=1): [1;32mOK[0m
  GEGLU_QUICK(type=f32,ne_a=[128,2,2,2],v=0,split): [1;32mOK[0m
  GEGLU_QUICK(type=f32,ne_a=[5,7,11,13],v=0,split): [1;32mOK[0m
  REGLU(type=f32,ne_a=[128,2,2,2],v=1,swapped=0): [1;32mOK[0m
  REGLU(type=f32,ne_a=[5,7,11,13],v=1,swapped=0): [1;32mOK[0m
  REGLU(type=f32,ne_a=[128,2,2,2],v=1,swapped=1): [1;32mOK[0m
  REGLU(type=f32,ne_a=[5,7,11,13],v=1,swapped=1): [1;32mOK[0m
  REGLU(type=f32,ne_a=[128,2,2,2],v=1,split): [1;32mOK[0m
  REGLU(type=f32,ne_a=[5,7,11,13],v=1,split): [1;32mOK[0m
  GEGLU(type=f32,ne_a=[128,2,2,2],v=1,swapped=0): [1;32mOK[0m
  GEGLU(type=f32,ne_a=[5,7,11,13],v=1,swapped=0): [1;32mOK[0m
  GEGLU(type=f32,ne_a=[128,2,2,2],v=1,swapped=1): [1;32mOK[0m
  GEGLU(type=f32,ne_a=[5,7,11,13],v=1,swapped=1): [1;32mOK[0m
  GEGLU(type=f32,ne_a=[128,2,2,2],v=1,split): [1;32mOK[0m
  GEGLU(type=f32,ne_a=[5,7,11,13],v=1,split): [1;32mOK[0m
  SWIGLU(type=f32,ne_a=[128,2,2,2],v=1,swapped=0): [1;32mOK[0m
  SWIGLU(type=f32,ne_a=[5,7,11,13],v=1,swapped=0): [1;32mOK[0m
  SWIGLU(type=f32,ne_a=[128,2,2,2],v=1,swapped=1): [1;32mOK[0m
  SWIGLU(type=f32,ne_a=[5,7,11,13],v=1,swapped=1): [1;32mOK[0m
  SWIGLU(type=f32,ne_a=[128,2,2,2],v=1,split): [1;32mOK[0m
  SWIGLU(type=f32,ne_a=[5,7,11,13],v=1,split): [1;32mOK[0m
  GEGLU_ERF(type=f32,ne_a=[128,2,2,2],v=1,swapped=0): [1;32mOK[0m
  GEGLU_ERF(type=f32,ne_a=[5,7,11,13],v=1,swapped=0): [1;32mOK[0m
  GEGLU_ERF(type=f32,ne_a=[128,2,2,2],v=1,swapped=1): [1;32mOK[0m
  GEGLU_ERF(type=f32,ne_a=[5,7,11,13],v=1,swapped=1): [1;32mOK[0m
  GEGLU_ERF(type=f32,ne_a=[128,2,2,2],v=1,split): [1;32mOK[0m
  GEGLU_ERF(type=f32,ne_a=[5,7,11,13],v=1,split): [1;32mOK[0m
  GEGLU_QUICK(type=f32,ne_a=[128,2,2,2],v=1,swapped=0): [1;32mOK[0m
  GEGLU_QUICK(type=f32,ne_a=[5,7,11,13],v=1,swapped=0): [1;32mOK[0m
  GEGLU_QUICK(type=f32,ne_a=[128,2,2,2],v=1,swapped=1): [1;32mOK[0m
  GEGLU_QUICK(type=f32,ne_a=[5,7,11,13],v=1,swapped=1): [1;32mOK[0m
  GEGLU_QUICK(type=f32,ne_a=[128,2,2,2],v=1,split): [1;32mOK[0m
  GEGLU_QUICK(type=f32,ne_a=[5,7,11,13],v=1,split): [1;32mOK[0m
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
  GET_ROWS_BACK(type=f32,n=1,m=8,r=2,b=1,v=0): not supported [SYCL0] 
  GET_ROWS_BACK(type=f32,n=256,m=5,r=4,b=1,v=0): not supported [SYCL0] 
  GET_ROWS_BACK(type=f32,n=256,m=5,r=4,b=1,v=1): not supported [SYCL0] 
  GET_ROWS_BACK(type=f16,n=256,m=5,r=4,b=1,v=0): not supported [SYCL0] 
  GET_ROWS_BACK(type=f16,n=256,m=5,r=4,b=1,v=1): not supported [SYCL0] 
  GET_ROWS_BACK(type=bf16,n=256,m=5,r=4,b=1,v=0): not supported [SYCL0] 
  GET_ROWS_BACK(type=bf16,n=256,m=5,r=4,b=1,v=1): not supported [SYCL0] 
  GET_ROWS_BACK(type=q4_0,n=256,m=5,r=4,b=1,v=0): not supported [SYCL0] 
  GET_ROWS_BACK(type=q4_0,n=256,m=5,r=4,b=1,v=1): not supported [SYCL0] 
  GET_ROWS_BACK(type=q4_1,n=256,m=5,r=4,b=1,v=0): not supported [SYCL0] 
  GET_ROWS_BACK(type=q4_1,n=256,m=5,r=4,b=1,v=1): not supported [SYCL0] 
  GET_ROWS_BACK(type=q5_0,n=256,m=5,r=4,b=1,v=0): not supported [SYCL0] 
  GET_ROWS_BACK(type=q5_0,n=256,m=5,r=4,b=1,v=1): not supported [SYCL0] 
  GET_ROWS_BACK(type=q5_1,n=256,m=5,r=4,b=1,v=0): not supported [SYCL0] 
  GET_ROWS_BACK(type=q5_1,n=256,m=5,r=4,b=1,v=1): not supported [SYCL0] 
  GET_ROWS_BACK(type=q8_0,n=256,m=5,r=4,b=1,v=0): not supported [SYCL0] 
  GET_ROWS_BACK(type=q8_0,n=256,m=5,r=4,b=1,v=1): not supported [SYCL0] 
  GET_ROWS_BACK(type=q2_K,n=256,m=5,r=4,b=1,v=0): not supported [SYCL0] 
  GET_ROWS_BACK(type=q2_K,n=256,m=5,r=4,b=1,v=1): not supported [SYCL0] 
  GET_ROWS_BACK(type=q3_K,n=256,m=5,r=4,b=1,v=0): not supported [SYCL0] 
  GET_ROWS_BACK(type=q3_K,n=256,m=5,r=4,b=1,v=1): not supported [SYCL0] 
  GET_ROWS_BACK(type=q4_K,n=256,m=5,r=4,b=1,v=0): not supported [SYCL0] 
  GET_ROWS_BACK(type=q4_K,n=256,m=5,r=4,b=1,v=1): not supported [SYCL0] 
  GET_ROWS_BACK(type=q5_K,n=256,m=5,r=4,b=1,v=0): not supported [SYCL0] 
  GET_ROWS_BACK(type=q5_K,n=256,m=5,r=4,b=1,v=1): not supported [SYCL0] 
  GET_ROWS_BACK(type=q6_K,n=256,m=5,r=4,b=1,v=0): not supported [SYCL0] 
  GET_ROWS_BACK(type=q6_K,n=256,m=5,r=4,b=1,v=1): not supported [SYCL0] 
  GET_ROWS_BACK(type=iq2_xxs,n=256,m=5,r=4,b=1,v=0): not supported [SYCL0] 
  GET_ROWS_BACK(type=iq2_xxs,n=256,m=5,r=4,b=1,v=1): not supported [SYCL0] 
  GET_ROWS_BACK(type=iq2_xs,n=256,m=5,r=4,b=1,v=0): not supported [SYCL0] 
  GET_ROWS_BACK(type=iq2_xs,n=256,m=5,r=4,b=1,v=1): not supported [SYCL0] 
  GET_ROWS_BACK(type=iq2_s,n=256,m=5,r=4,b=1,v=0): not supported [SYCL0] 
  GET_ROWS_BACK(type=iq2_s,n=256,m=5,r=4,b=1,v=1): not supported [SYCL0] 
  GET_ROWS_BACK(type=iq3_xxs,n=256,m=5,r=4,b=1,v=0): not supported [SYCL0] 
  GET_ROWS_BACK(type=iq3_xxs,n=256,m=5,r=4,b=1,v=1): not supported [SYCL0] 
  GET_ROWS_BACK(type=iq1_s,n=256,m=5,r=4,b=1,v=0): not supported [SYCL0] 
  GET_ROWS_BACK(type=iq1_s,n=256,m=5,r=4,b=1,v=1): not supported [SYCL0] 
  GET_ROWS_BACK(type=iq1_m,n=256,m=5,r=4,b=1,v=0): not supported [SYCL0] 
  GET_ROWS_BACK(type=iq1_m,n=256,m=5,r=4,b=1,v=1): not supported [SYCL0] 
  GET_ROWS_BACK(type=iq4_nl,n=256,m=5,r=4,b=1,v=0): not supported [SYCL0] 
  GET_ROWS_BACK(type=iq4_nl,n=256,m=5,r=4,b=1,v=1): not supported [SYCL0] 
  GET_ROWS_BACK(type=iq3_s,n=256,m=5,r=4,b=1,v=0): not supported [SYCL0] 
  GET_ROWS_BACK(type=iq3_s,n=256,m=5,r=4,b=1,v=1): not supported [SYCL0] 
  GET_ROWS_BACK(type=iq4_xs,n=256,m=5,r=4,b=1,v=0): not supported [SYCL0] 
  GET_ROWS_BACK(type=iq4_xs,n=256,m=5,r=4,b=1,v=1): not supported [SYCL0] 
  GET_ROWS_BACK(type=i32,n=256,m=5,r=4,b=1,v=0): not supported [SYCL0] 
  GET_ROWS_BACK(type=i32,n=256,m=5,r=4,b=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=f32,ne=[1,8,1,3],nr23=[1,1],r=2,v=0): [1;32mOK[0m
  SET_ROWS(type=f32,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): [1;32mOK[0m
  SET_ROWS(type=f32,ne=[256,11,1,1],nr23=[2,3],r=7,v=0): [1;32mOK[0m
  SET_ROWS(type=f32,ne=[3,3,1,1],nr23=[2,3],r=2,v=0): [1;32mOK[0m
  SET_ROWS(type=f32,ne=[31,3,1,1],nr23=[2,3],r=2,v=0): [1;32mOK[0m
  SET_ROWS(type=f32,ne=[33,5,1,1],nr23=[2,3],r=1,v=0): [1;32mOK[0m
  SET_ROWS(type=f32,ne=[256,5,1,3],nr23=[1,1],r=1,v=1): [1;32mOK[0m
  SET_ROWS(type=f32,ne=[256,11,1,1],nr23=[2,3],r=7,v=1): [1;32mOK[0m
  SET_ROWS(type=f32,ne=[3,3,1,1],nr23=[2,3],r=2,v=1): [1;32mOK[0m
  SET_ROWS(type=f32,ne=[31,3,1,1],nr23=[2,3],r=2,v=1): [1;32mOK[0m
  SET_ROWS(type=f32,ne=[33,5,1,1],nr23=[2,3],r=1,v=1): [1;32mOK[0m
  SET_ROWS(type=f32,ne=[256,5,7,3],nr23=[1,1],r=1,v=0): [1;32mOK[0m
  SET_ROWS(type=f32,ne=[256,11,1,7],nr23=[2,3],r=7,v=0): [1;32mOK[0m
  SET_ROWS(type=f32,ne=[3,3,7,1],nr23=[2,3],r=2,v=0): [1;32mOK[0m
  SET_ROWS(type=f32,ne=[31,3,7,1],nr23=[2,3],r=2,v=0): [1;32mOK[0m
  SET_ROWS(type=f32,ne=[33,5,1,7],nr23=[2,3],r=1,v=0): [1;32mOK[0m
  SET_ROWS(type=f32,ne=[256,5,7,3],nr23=[1,1],r=1,v=1): [1;32mOK[0m
  SET_ROWS(type=f32,ne=[256,11,1,7],nr23=[2,3],r=7,v=1): [1;32mOK[0m
  SET_ROWS(type=f32,ne=[3,3,7,1],nr23=[2,3],r=2,v=1): [1;32mOK[0m
  SET_ROWS(type=f32,ne=[31,3,7,1],nr23=[2,3],r=2,v=1): [1;32mOK[0m
  SET_ROWS(type=f32,ne=[33,5,1,7],nr23=[2,3],r=1,v=1): [1;32mOK[0m
  SET_ROWS(type=f16,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): [1;32mOK[0m
  SET_ROWS(type=f16,ne=[256,11,1,1],nr23=[2,3],r=7,v=0): [1;32mOK[0m
  SET_ROWS(type=f16,ne=[3,3,1,1],nr23=[2,3],r=2,v=0): [1;32mOK[0m
  SET_ROWS(type=f16,ne=[31,3,1,1],nr23=[2,3],r=2,v=0): [1;32mOK[0m
  SET_ROWS(type=f16,ne=[33,5,1,1],nr23=[2,3],r=1,v=0): [1;32mOK[0m
  SET_ROWS(type=f16,ne=[256,5,1,3],nr23=[1,1],r=1,v=1): [1;32mOK[0m
  SET_ROWS(type=f16,ne=[256,11,1,1],nr23=[2,3],r=7,v=1): [1;32mOK[0m
  SET_ROWS(type=f16,ne=[3,3,1,1],nr23=[2,3],r=2,v=1): [1;32mOK[0m
  SET_ROWS(type=f16,ne=[31,3,1,1],nr23=[2,3],r=2,v=1): [1;32mOK[0m
  SET_ROWS(type=f16,ne=[33,5,1,1],nr23=[2,3],r=1,v=1): [1;32mOK[0m
  SET_ROWS(type=f16,ne=[256,5,7,3],nr23=[1,1],r=1,v=0): [1;32mOK[0m
  SET_ROWS(type=f16,ne=[256,11,1,7],nr23=[2,3],r=7,v=0): [1;32mOK[0m
  SET_ROWS(type=f16,ne=[3,3,7,1],nr23=[2,3],r=2,v=0): [1;32mOK[0m
  SET_ROWS(type=f16,ne=[31,3,7,1],nr23=[2,3],r=2,v=0): [1;32mOK[0m
  SET_ROWS(type=f16,ne=[33,5,1,7],nr23=[2,3],r=1,v=0): [1;32mOK[0m
  SET_ROWS(type=f16,ne=[256,5,7,3],nr23=[1,1],r=1,v=1): [1;32mOK[0m
  SET_ROWS(type=f16,ne=[256,11,1,7],nr23=[2,3],r=7,v=1): [1;32mOK[0m
  SET_ROWS(type=f16,ne=[3,3,7,1],nr23=[2,3],r=2,v=1): [1;32mOK[0m
  SET_ROWS(type=f16,ne=[31,3,7,1],nr23=[2,3],r=2,v=1): [1;32mOK[0m
  SET_ROWS(type=f16,ne=[33,5,1,7],nr23=[2,3],r=1,v=1): [1;32mOK[0m
  SET_ROWS(type=bf16,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=bf16,ne=[256,11,1,1],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=bf16,ne=[3,3,1,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=bf16,ne=[31,3,1,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=bf16,ne=[33,5,1,1],nr23=[2,3],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=bf16,ne=[256,5,1,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=bf16,ne=[256,11,1,1],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=bf16,ne=[3,3,1,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=bf16,ne=[31,3,1,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=bf16,ne=[33,5,1,1],nr23=[2,3],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=bf16,ne=[256,5,7,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=bf16,ne=[256,11,1,7],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=bf16,ne=[3,3,7,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=bf16,ne=[31,3,7,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=bf16,ne=[33,5,1,7],nr23=[2,3],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=bf16,ne=[256,5,7,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=bf16,ne=[256,11,1,7],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=bf16,ne=[3,3,7,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=bf16,ne=[31,3,7,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=bf16,ne=[33,5,1,7],nr23=[2,3],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=q4_0,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=q4_0,ne=[256,11,1,1],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=q4_0,ne=[96,3,1,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=q4_0,ne=[256,5,1,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=q4_0,ne=[256,11,1,1],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=q4_0,ne=[96,3,1,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=q4_0,ne=[256,5,7,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=q4_0,ne=[256,11,1,7],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=q4_0,ne=[96,3,7,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=q4_0,ne=[256,5,7,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=q4_0,ne=[256,11,1,7],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=q4_0,ne=[96,3,7,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=q4_1,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=q4_1,ne=[256,11,1,1],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=q4_1,ne=[96,3,1,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=q4_1,ne=[256,5,1,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=q4_1,ne=[256,11,1,1],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=q4_1,ne=[96,3,1,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=q4_1,ne=[256,5,7,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=q4_1,ne=[256,11,1,7],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=q4_1,ne=[96,3,7,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=q4_1,ne=[256,5,7,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=q4_1,ne=[256,11,1,7],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=q4_1,ne=[96,3,7,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=q5_0,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=q5_0,ne=[256,11,1,1],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=q5_0,ne=[96,3,1,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=q5_0,ne=[256,5,1,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=q5_0,ne=[256,11,1,1],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=q5_0,ne=[96,3,1,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=q5_0,ne=[256,5,7,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=q5_0,ne=[256,11,1,7],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=q5_0,ne=[96,3,7,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=q5_0,ne=[256,5,7,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=q5_0,ne=[256,11,1,7],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=q5_0,ne=[96,3,7,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=q5_1,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=q5_1,ne=[256,11,1,1],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=q5_1,ne=[96,3,1,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=q5_1,ne=[256,5,1,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=q5_1,ne=[256,11,1,1],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=q5_1,ne=[96,3,1,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=q5_1,ne=[256,5,7,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=q5_1,ne=[256,11,1,7],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=q5_1,ne=[96,3,7,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=q5_1,ne=[256,5,7,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=q5_1,ne=[256,11,1,7],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=q5_1,ne=[96,3,7,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=q8_0,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=q8_0,ne=[256,11,1,1],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=q8_0,ne=[96,3,1,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=q8_0,ne=[256,5,1,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=q8_0,ne=[256,11,1,1],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=q8_0,ne=[96,3,1,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=q8_0,ne=[256,5,7,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=q8_0,ne=[256,11,1,7],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=q8_0,ne=[96,3,7,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=q8_0,ne=[256,5,7,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=q8_0,ne=[256,11,1,7],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=q8_0,ne=[96,3,7,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=q2_K,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=q2_K,ne=[256,11,1,1],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=q2_K,ne=[768,3,1,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=q2_K,ne=[256,5,1,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=q2_K,ne=[256,11,1,1],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=q2_K,ne=[768,3,1,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=q2_K,ne=[256,5,7,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=q2_K,ne=[256,11,1,7],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=q2_K,ne=[768,3,7,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=q2_K,ne=[256,5,7,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=q2_K,ne=[256,11,1,7],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=q2_K,ne=[768,3,7,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=q3_K,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=q3_K,ne=[256,11,1,1],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=q3_K,ne=[768,3,1,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=q3_K,ne=[256,5,1,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=q3_K,ne=[256,11,1,1],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=q3_K,ne=[768,3,1,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=q3_K,ne=[256,5,7,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=q3_K,ne=[256,11,1,7],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=q3_K,ne=[768,3,7,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=q3_K,ne=[256,5,7,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=q3_K,ne=[256,11,1,7],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=q3_K,ne=[768,3,7,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=q4_K,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=q4_K,ne=[256,11,1,1],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=q4_K,ne=[768,3,1,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=q4_K,ne=[256,5,1,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=q4_K,ne=[256,11,1,1],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=q4_K,ne=[768,3,1,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=q4_K,ne=[256,5,7,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=q4_K,ne=[256,11,1,7],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=q4_K,ne=[768,3,7,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=q4_K,ne=[256,5,7,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=q4_K,ne=[256,11,1,7],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=q4_K,ne=[768,3,7,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=q5_K,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=q5_K,ne=[256,11,1,1],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=q5_K,ne=[768,3,1,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=q5_K,ne=[256,5,1,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=q5_K,ne=[256,11,1,1],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=q5_K,ne=[768,3,1,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=q5_K,ne=[256,5,7,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=q5_K,ne=[256,11,1,7],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=q5_K,ne=[768,3,7,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=q5_K,ne=[256,5,7,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=q5_K,ne=[256,11,1,7],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=q5_K,ne=[768,3,7,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=q6_K,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=q6_K,ne=[256,11,1,1],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=q6_K,ne=[768,3,1,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=q6_K,ne=[256,5,1,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=q6_K,ne=[256,11,1,1],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=q6_K,ne=[768,3,1,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=q6_K,ne=[256,5,7,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=q6_K,ne=[256,11,1,7],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=q6_K,ne=[768,3,7,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=q6_K,ne=[256,5,7,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=q6_K,ne=[256,11,1,7],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=q6_K,ne=[768,3,7,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq2_xxs,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq2_xxs,ne=[256,11,1,1],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq2_xxs,ne=[768,3,1,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq2_xxs,ne=[256,5,1,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq2_xxs,ne=[256,11,1,1],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq2_xxs,ne=[768,3,1,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq2_xxs,ne=[256,5,7,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq2_xxs,ne=[256,11,1,7],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq2_xxs,ne=[768,3,7,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq2_xxs,ne=[256,5,7,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq2_xxs,ne=[256,11,1,7],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq2_xxs,ne=[768,3,7,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq2_xs,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq2_xs,ne=[256,11,1,1],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq2_xs,ne=[768,3,1,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq2_xs,ne=[256,5,1,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq2_xs,ne=[256,11,1,1],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq2_xs,ne=[768,3,1,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq2_xs,ne=[256,5,7,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq2_xs,ne=[256,11,1,7],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq2_xs,ne=[768,3,7,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq2_xs,ne=[256,5,7,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq2_xs,ne=[256,11,1,7],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq2_xs,ne=[768,3,7,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq2_s,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq2_s,ne=[256,11,1,1],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq2_s,ne=[768,3,1,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq2_s,ne=[256,5,1,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq2_s,ne=[256,11,1,1],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq2_s,ne=[768,3,1,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq2_s,ne=[256,5,7,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq2_s,ne=[256,11,1,7],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq2_s,ne=[768,3,7,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq2_s,ne=[256,5,7,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq2_s,ne=[256,11,1,7],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq2_s,ne=[768,3,7,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq3_xxs,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq3_xxs,ne=[256,11,1,1],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq3_xxs,ne=[768,3,1,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq3_xxs,ne=[256,5,1,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq3_xxs,ne=[256,11,1,1],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq3_xxs,ne=[768,3,1,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq3_xxs,ne=[256,5,7,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq3_xxs,ne=[256,11,1,7],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq3_xxs,ne=[768,3,7,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq3_xxs,ne=[256,5,7,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq3_xxs,ne=[256,11,1,7],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq3_xxs,ne=[768,3,7,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq1_s,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq1_s,ne=[256,11,1,1],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq1_s,ne=[768,3,1,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq1_s,ne=[256,5,1,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq1_s,ne=[256,11,1,1],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq1_s,ne=[768,3,1,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq1_s,ne=[256,5,7,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq1_s,ne=[256,11,1,7],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq1_s,ne=[768,3,7,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq1_s,ne=[256,5,7,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq1_s,ne=[256,11,1,7],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq1_s,ne=[768,3,7,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq1_m,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq1_m,ne=[256,11,1,1],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq1_m,ne=[768,3,1,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq1_m,ne=[256,5,1,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq1_m,ne=[256,11,1,1],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq1_m,ne=[768,3,1,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq1_m,ne=[256,5,7,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq1_m,ne=[256,11,1,7],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq1_m,ne=[768,3,7,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq1_m,ne=[256,5,7,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq1_m,ne=[256,11,1,7],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq1_m,ne=[768,3,7,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq4_nl,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq4_nl,ne=[256,11,1,1],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq4_nl,ne=[96,3,1,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq4_nl,ne=[256,5,1,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq4_nl,ne=[256,11,1,1],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq4_nl,ne=[96,3,1,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq4_nl,ne=[256,5,7,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq4_nl,ne=[256,11,1,7],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq4_nl,ne=[96,3,7,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq4_nl,ne=[256,5,7,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq4_nl,ne=[256,11,1,7],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq4_nl,ne=[96,3,7,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq3_s,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq3_s,ne=[256,11,1,1],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq3_s,ne=[768,3,1,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq3_s,ne=[256,5,1,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq3_s,ne=[256,11,1,1],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq3_s,ne=[768,3,1,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq3_s,ne=[256,5,7,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq3_s,ne=[256,11,1,7],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq3_s,ne=[768,3,7,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq3_s,ne=[256,5,7,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq3_s,ne=[256,11,1,7],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq3_s,ne=[768,3,7,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq4_xs,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq4_xs,ne=[256,11,1,1],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq4_xs,ne=[768,3,1,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq4_xs,ne=[256,5,1,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq4_xs,ne=[256,11,1,1],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq4_xs,ne=[768,3,1,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq4_xs,ne=[256,5,7,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq4_xs,ne=[256,11,1,7],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq4_xs,ne=[768,3,7,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq4_xs,ne=[256,5,7,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq4_xs,ne=[256,11,1,7],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq4_xs,ne=[768,3,7,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
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
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[3000,128,1,1],ne_kernel=[3,128,1280,1],s0=1,s1=0,p0=1,p1=0,d0=1,d1=0,is_2D=0): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f16,dst_type=f32,ne_input=[3000,128,1,1],ne_kernel=[3,128,1280,1],s0=1,s1=0,p0=1,p1=0,d0=1,d1=0,is_2D=0): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f16,dst_type=f16,ne_input=[3000,128,1,1],ne_kernel=[3,128,1280,1],s0=1,s1=0,p0=1,p1=0,d0=1,d1=0,is_2D=0): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,2,2,1],ne_kernel=[3,2,2,1],s0=1,s1=0,p0=0,p1=0,d0=1,d1=0,is_2D=0): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,2,2,1],ne_kernel=[3,2,2,1],s0=1,s1=0,p0=0,p1=0,d0=3,d1=0,is_2D=0): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,2,2,1],ne_kernel=[3,2,2,1],s0=1,s1=0,p0=3,p1=0,d0=1,d1=0,is_2D=0): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,2,2,1],ne_kernel=[3,2,2,1],s0=1,s1=0,p0=3,p1=0,d0=3,d1=0,is_2D=0): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,2,2,1],ne_kernel=[3,2,2,1],s0=3,s1=0,p0=0,p1=0,d0=1,d1=0,is_2D=0): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,2,2,1],ne_kernel=[3,2,2,1],s0=3,s1=0,p0=0,p1=0,d0=3,d1=0,is_2D=0): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,2,2,1],ne_kernel=[3,2,2,1],s0=3,s1=0,p0=3,p1=0,d0=1,d1=0,is_2D=0): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,2,2,1],ne_kernel=[3,2,2,1],s0=3,s1=0,p0=3,p1=0,d0=3,d1=0,is_2D=0): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[10,10,3,1],ne_kernel=[3,3,3,1],s0=1,s1=1,p0=1,p1=1,d0=1,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f16,dst_type=f32,ne_input=[10,10,3,1],ne_kernel=[3,3,3,1],s0=1,s1=1,p0=1,p1=1,d0=1,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f16,dst_type=f16,ne_input=[10,10,3,1],ne_kernel=[3,3,3,1],s0=1,s1=1,p0=1,p1=1,d0=1,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=1,s1=1,p0=0,p1=0,d0=1,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=1,s1=1,p0=0,p1=0,d0=1,d1=3,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=1,s1=1,p0=0,p1=0,d0=3,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=1,s1=1,p0=0,p1=0,d0=3,d1=3,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=1,s1=1,p0=0,p1=3,d0=1,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=1,s1=1,p0=0,p1=3,d0=1,d1=3,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=1,s1=1,p0=0,p1=3,d0=3,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=1,s1=1,p0=0,p1=3,d0=3,d1=3,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=1,s1=1,p0=3,p1=0,d0=1,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=1,s1=1,p0=3,p1=0,d0=1,d1=3,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=1,s1=1,p0=3,p1=0,d0=3,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=1,s1=1,p0=3,p1=0,d0=3,d1=3,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=1,s1=1,p0=3,p1=3,d0=1,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=1,s1=1,p0=3,p1=3,d0=1,d1=3,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=1,s1=1,p0=3,p1=3,d0=3,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=1,s1=1,p0=3,p1=3,d0=3,d1=3,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=1,s1=3,p0=0,p1=0,d0=1,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=1,s1=3,p0=0,p1=0,d0=1,d1=3,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=1,s1=3,p0=0,p1=0,d0=3,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=1,s1=3,p0=0,p1=0,d0=3,d1=3,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=1,s1=3,p0=0,p1=3,d0=1,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=1,s1=3,p0=0,p1=3,d0=1,d1=3,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=1,s1=3,p0=0,p1=3,d0=3,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=1,s1=3,p0=0,p1=3,d0=3,d1=3,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=1,s1=3,p0=3,p1=0,d0=1,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=1,s1=3,p0=3,p1=0,d0=1,d1=3,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=1,s1=3,p0=3,p1=0,d0=3,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=1,s1=3,p0=3,p1=0,d0=3,d1=3,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=1,s1=3,p0=3,p1=3,d0=1,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=1,s1=3,p0=3,p1=3,d0=1,d1=3,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=1,s1=3,p0=3,p1=3,d0=3,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=1,s1=3,p0=3,p1=3,d0=3,d1=3,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=3,s1=1,p0=0,p1=0,d0=1,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=3,s1=1,p0=0,p1=0,d0=1,d1=3,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=3,s1=1,p0=0,p1=0,d0=3,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=3,s1=1,p0=0,p1=0,d0=3,d1=3,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=3,s1=1,p0=0,p1=3,d0=1,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=3,s1=1,p0=0,p1=3,d0=1,d1=3,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=3,s1=1,p0=0,p1=3,d0=3,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=3,s1=1,p0=0,p1=3,d0=3,d1=3,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=3,s1=1,p0=3,p1=0,d0=1,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=3,s1=1,p0=3,p1=0,d0=1,d1=3,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=3,s1=1,p0=3,p1=0,d0=3,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=3,s1=1,p0=3,p1=0,d0=3,d1=3,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=3,s1=1,p0=3,p1=3,d0=1,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=3,s1=1,p0=3,p1=3,d0=1,d1=3,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=3,s1=1,p0=3,p1=3,d0=3,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=3,s1=1,p0=3,p1=3,d0=3,d1=3,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=3,s1=3,p0=0,p1=0,d0=1,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=3,s1=3,p0=0,p1=0,d0=1,d1=3,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=3,s1=3,p0=0,p1=0,d0=3,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=3,s1=3,p0=0,p1=0,d0=3,d1=3,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=3,s1=3,p0=0,p1=3,d0=1,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=3,s1=3,p0=0,p1=3,d0=1,d1=3,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=3,s1=3,p0=0,p1=3,d0=3,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=3,s1=3,p0=0,p1=3,d0=3,d1=3,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=3,s1=3,p0=3,p1=0,d0=1,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=3,s1=3,p0=3,p1=0,d0=1,d1=3,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=3,s1=3,p0=3,p1=0,d0=3,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=3,s1=3,p0=3,p1=0,d0=3,d1=3,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=3,s1=3,p0=3,p1=3,d0=1,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=3,s1=3,p0=3,p1=3,d0=1,d1=3,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=3,s1=3,p0=3,p1=3,d0=3,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,2,2],ne_kernel=[3,3,2,2],s0=3,s1=3,p0=3,p1=3,d0=3,d1=3,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f16,dst_type=f16,ne_input=[12,12,1,32],ne_kernel=[3,3,1,32],s0=1,s1=1,p0=1,p1=1,d0=1,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f16,dst_type=f16,ne_input=[12,12,2,32],ne_kernel=[3,3,2,32],s0=1,s1=1,p0=1,p1=1,d0=1,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f16,dst_type=f16,ne_input=[12,12,1,1024],ne_kernel=[3,3,1,1024],s0=1,s1=1,p0=1,p1=1,d0=1,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f16,dst_type=f16,ne_input=[12,12,2,1024],ne_kernel=[3,3,2,1024],s0=1,s1=1,p0=1,p1=1,d0=1,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f16,dst_type=f16,ne_input=[12,12,1,2048],ne_kernel=[3,3,1,2048],s0=1,s1=1,p0=1,p1=1,d0=1,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f16,dst_type=f16,ne_input=[12,12,2,2048],ne_kernel=[3,3,2,2048],s0=1,s1=1,p0=1,p1=1,d0=1,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f16,dst_type=f16,ne_input=[12,12,1,2560],ne_kernel=[3,3,1,2560],s0=1,s1=1,p0=1,p1=1,d0=1,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f16,dst_type=f16,ne_input=[12,12,2,2560],ne_kernel=[3,3,2,2560],s0=1,s1=1,p0=1,p1=1,d0=1,d1=1,is_2D=1): [1;32mOK[0m
  CONV_2D_DW(ne_input=[17,34,9,1],ne_kernel=[3,3,1,9],stride=1,padding=0,dilation=1,cwhn=0): not supported [SYCL0] 
  CONV_2D_DW(ne_input=[17,34,9,1],ne_kernel=[3,3,1,9],stride=1,padding=0,dilation=1,cwhn=1): not supported [SYCL0] 
  CONV_2D_DW(ne_input=[32,8,64,1],ne_kernel=[3,3,1,64],stride=2,padding=1,dilation=1,cwhn=0): not supported [SYCL0] 
  CONV_2D_DW(ne_input=[32,8,64,1],ne_kernel=[3,3,1,64],stride=2,padding=1,dilation=1,cwhn=1): not supported [SYCL0] 
  CONV_TRANSPOSE_1D(ne_input=[1,1,1,1],ne_kernel=[1,1,1,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[1,1,1,1],ne_kernel=[1,1,1,1],s0=2,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[1,1,1,1],ne_kernel=[1,1,1,1],s0=3,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[2,1,1,1],ne_kernel=[1,1,1,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[2,1,1,1],ne_kernel=[1,1,1,1],s0=2,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[2,1,1,1],ne_kernel=[1,1,1,1],s0=3,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[13,1,1,1],ne_kernel=[1,1,1,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[13,1,1,1],ne_kernel=[1,1,1,1],s0=2,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[13,1,1,1],ne_kernel=[1,1,1,1],s0=3,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[1,1,1,1],ne_kernel=[3,1,1,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[1,1,1,1],ne_kernel=[3,1,1,1],s0=2,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[1,1,1,1],ne_kernel=[3,1,1,1],s0=3,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[2,1,1,1],ne_kernel=[3,1,1,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[2,1,1,1],ne_kernel=[3,1,1,1],s0=2,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[2,1,1,1],ne_kernel=[3,1,1,1],s0=3,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[13,1,1,1],ne_kernel=[3,1,1,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[13,1,1,1],ne_kernel=[3,1,1,1],s0=2,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[13,1,1,1],ne_kernel=[3,1,1,1],s0=3,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[1,1,1,1],ne_kernel=[1337,1,1,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[1,1,1,1],ne_kernel=[1337,1,1,1],s0=2,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[1,1,1,1],ne_kernel=[1337,1,1,1],s0=3,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[2,1,1,1],ne_kernel=[1337,1,1,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[2,1,1,1],ne_kernel=[1337,1,1,1],s0=2,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[2,1,1,1],ne_kernel=[1337,1,1,1],s0=3,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[13,1,1,1],ne_kernel=[1337,1,1,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[13,1,1,1],ne_kernel=[1337,1,1,1],s0=2,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[13,1,1,1],ne_kernel=[1337,1,1,1],s0=3,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[1,7,1,1],ne_kernel=[1,1,7,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[1,7,1,1],ne_kernel=[1,1,7,1],s0=2,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[1,7,1,1],ne_kernel=[1,1,7,1],s0=3,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[2,7,1,1],ne_kernel=[1,1,7,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[2,7,1,1],ne_kernel=[1,1,7,1],s0=2,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[2,7,1,1],ne_kernel=[1,1,7,1],s0=3,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[13,7,1,1],ne_kernel=[1,1,7,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[13,7,1,1],ne_kernel=[1,1,7,1],s0=2,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[13,7,1,1],ne_kernel=[1,1,7,1],s0=3,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[1,7,1,1],ne_kernel=[3,1,7,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[1,7,1,1],ne_kernel=[3,1,7,1],s0=2,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[1,7,1,1],ne_kernel=[3,1,7,1],s0=3,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[2,7,1,1],ne_kernel=[3,1,7,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[2,7,1,1],ne_kernel=[3,1,7,1],s0=2,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[2,7,1,1],ne_kernel=[3,1,7,1],s0=3,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[13,7,1,1],ne_kernel=[3,1,7,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[13,7,1,1],ne_kernel=[3,1,7,1],s0=2,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[13,7,1,1],ne_kernel=[3,1,7,1],s0=3,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[1,7,1,1],ne_kernel=[1337,1,7,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[1,7,1,1],ne_kernel=[1337,1,7,1],s0=2,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[1,7,1,1],ne_kernel=[1337,1,7,1],s0=3,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[2,7,1,1],ne_kernel=[1337,1,7,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[2,7,1,1],ne_kernel=[1337,1,7,1],s0=2,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[2,7,1,1],ne_kernel=[1337,1,7,1],s0=3,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[13,7,1,1],ne_kernel=[1337,1,7,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[13,7,1,1],ne_kernel=[1337,1,7,1],s0=2,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[13,7,1,1],ne_kernel=[1337,1,7,1],s0=3,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[1,1,1,1],ne_kernel=[1,9,1,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[1,1,1,1],ne_kernel=[1,9,1,1],s0=2,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[1,1,1,1],ne_kernel=[1,9,1,1],s0=3,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[2,1,1,1],ne_kernel=[1,9,1,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[2,1,1,1],ne_kernel=[1,9,1,1],s0=2,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[2,1,1,1],ne_kernel=[1,9,1,1],s0=3,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[13,1,1,1],ne_kernel=[1,9,1,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[13,1,1,1],ne_kernel=[1,9,1,1],s0=2,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[13,1,1,1],ne_kernel=[1,9,1,1],s0=3,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[1,1,1,1],ne_kernel=[3,9,1,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[1,1,1,1],ne_kernel=[3,9,1,1],s0=2,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[1,1,1,1],ne_kernel=[3,9,1,1],s0=3,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[2,1,1,1],ne_kernel=[3,9,1,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[2,1,1,1],ne_kernel=[3,9,1,1],s0=2,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[2,1,1,1],ne_kernel=[3,9,1,1],s0=3,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[13,1,1,1],ne_kernel=[3,9,1,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[13,1,1,1],ne_kernel=[3,9,1,1],s0=2,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[13,1,1,1],ne_kernel=[3,9,1,1],s0=3,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[1,1,1,1],ne_kernel=[1337,9,1,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[1,1,1,1],ne_kernel=[1337,9,1,1],s0=2,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[1,1,1,1],ne_kernel=[1337,9,1,1],s0=3,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[2,1,1,1],ne_kernel=[1337,9,1,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[2,1,1,1],ne_kernel=[1337,9,1,1],s0=2,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[2,1,1,1],ne_kernel=[1337,9,1,1],s0=3,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[13,1,1,1],ne_kernel=[1337,9,1,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[13,1,1,1],ne_kernel=[1337,9,1,1],s0=2,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[13,1,1,1],ne_kernel=[1337,9,1,1],s0=3,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[1,7,1,1],ne_kernel=[1,9,7,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[1,7,1,1],ne_kernel=[1,9,7,1],s0=2,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[1,7,1,1],ne_kernel=[1,9,7,1],s0=3,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[2,7,1,1],ne_kernel=[1,9,7,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[2,7,1,1],ne_kernel=[1,9,7,1],s0=2,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[2,7,1,1],ne_kernel=[1,9,7,1],s0=3,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[13,7,1,1],ne_kernel=[1,9,7,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[13,7,1,1],ne_kernel=[1,9,7,1],s0=2,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[13,7,1,1],ne_kernel=[1,9,7,1],s0=3,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[1,7,1,1],ne_kernel=[3,9,7,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[1,7,1,1],ne_kernel=[3,9,7,1],s0=2,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[1,7,1,1],ne_kernel=[3,9,7,1],s0=3,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[2,7,1,1],ne_kernel=[3,9,7,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[2,7,1,1],ne_kernel=[3,9,7,1],s0=2,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[2,7,1,1],ne_kernel=[3,9,7,1],s0=3,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[13,7,1,1],ne_kernel=[3,9,7,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[13,7,1,1],ne_kernel=[3,9,7,1],s0=2,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[13,7,1,1],ne_kernel=[3,9,7,1],s0=3,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[1,7,1,1],ne_kernel=[1337,9,7,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[1,7,1,1],ne_kernel=[1337,9,7,1],s0=2,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[1,7,1,1],ne_kernel=[1337,9,7,1],s0=3,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[2,7,1,1],ne_kernel=[1337,9,7,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[2,7,1,1],ne_kernel=[1337,9,7,1],s0=2,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[2,7,1,1],ne_kernel=[1337,9,7,1],s0=3,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[13,7,1,1],ne_kernel=[1337,9,7,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[13,7,1,1],ne_kernel=[1337,9,7,1],s0=2,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[13,7,1,1],ne_kernel=[1337,9,7,1],s0=3,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[197,32,1,1],ne_kernel=[16,32,32,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[3,2,1,1],ne_kernel=[2,3,2,1],s0=3,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[3,2,1,1],ne_kernel=[2,3,2,1],s0=2,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[3,2,1,1],ne_kernel=[2,3,2,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[3,2,1,1],ne_kernel=[3,2,2,1],s0=2,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[3,2,1,1],ne_kernel=[3,2,2,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[3,2,1,1],ne_kernel=[3,1,2,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_1D(ne_input=[2,1,1,1],ne_kernel=[3,1,1,1],s0=1,p0=0,d0=1): [1;32mOK[0m
  CONV_TRANSPOSE_2D(ne_input=[3,2,3,1],ne_kernel=[2,2,1,3],stride=1): not supported [SYCL0] 
  CONV_TRANSPOSE_2D(ne_input=[10,10,9,1],ne_kernel=[3,3,1,9],stride=2): not supported [SYCL0] 
  COUNT_EQUAL(type=f32,ne=[4,500,1,1]): not supported [SYCL0] 
  COUNT_EQUAL(type=f32,ne=[4,5000,1,1]): not supported [SYCL0] 
  ARGMAX(type=f32,ne=[32,1,1,1]): [1;32mOK[0m
  ARGMAX(type=f32,ne=[100,10,1,1]): [1;32mOK[0m
  ARGMAX(type=f32,ne=[1024,10,1,1]): [1;32mOK[0m
  ARGMAX(type=f32,ne=[1024,12,1,1]): [1;32mOK[0m
  ARGMAX(type=f32,ne=[2000,10,1,1]): [1;32mOK[0m
  ARGMAX(type=f32,ne=[5438,3,1,1]): [1;32mOK[0m
  REPEAT(type=f32,ne=[10,5,4,1],nr=[1,1,1,1]): [1;32mOK[0m
  REPEAT(type=f32,ne=[10,5,4,1],nr=[2,1,1,1]): [1;32mOK[0m
  REPEAT(type=f32,ne=[10,5,4,1],nr=[1,2,1,1]): [1;32mOK[0m
  REPEAT(type=f32,ne=[10,5,4,1],nr=[1,1,2,1]): [1;32mOK[0m
  REPEAT(type=f32,ne=[10,5,4,1],nr=[1,1,1,2]): [1;32mOK[0m
  REPEAT(type=i32,ne=[10,5,4,1],nr=[2,1,1,1]): [1;32mOK[0m
  REPEAT(type=i16,ne=[10,5,4,1],nr=[1,1,1,2]): [1;32mOK[0m
  REPEAT(type=f32,ne=[10,5,4,3],nr=[1,1,1,1]): [1;32mOK[0m
  REPEAT(type=f32,ne=[10,5,4,3],nr=[2,1,1,1]): [1;32mOK[0m
  REPEAT(type=f32,ne=[10,5,4,3],nr=[1,2,1,1]): [1;32mOK[0m
  REPEAT(type=f32,ne=[10,5,4,3],nr=[1,1,2,1]): [1;32mOK[0m
  REPEAT(type=f32,ne=[10,5,4,3],nr=[1,1,1,2]): [1;32mOK[0m
  REPEAT(type=i32,ne=[10,5,4,3],nr=[2,1,1,1]): [1;32mOK[0m
  REPEAT(type=i16,ne=[10,5,4,3],nr=[1,1,1,2]): [1;32mOK[0m
  REPEAT_BACK(type=f32,ne=[8,6,4,2],nr=[1,1,1,1],v=0): not supported [SYCL0] 
  REPEAT_BACK(type=f32,ne=[8,6,4,2],nr=[2,1,1,1],v=0): not supported [SYCL0] 
  REPEAT_BACK(type=f32,ne=[8,6,4,2],nr=[1,2,1,1],v=0): not supported [SYCL0] 
  REPEAT_BACK(type=f32,ne=[8,6,4,2],nr=[1,1,2,1],v=0): not supported [SYCL0] 
  REPEAT_BACK(type=f32,ne=[8,6,4,2],nr=[1,1,1,2],v=0): not supported [SYCL0] 
  REPEAT_BACK(type=f32,ne=[8,6,4,2],nr=[1,1,1,1],v=1): not supported [SYCL0] 
  REPEAT_BACK(type=f32,ne=[8,6,4,2],nr=[2,1,1,1],v=1): not supported [SYCL0] 
  REPEAT_BACK(type=f32,ne=[8,6,4,2],nr=[1,2,1,1],v=1): not supported [SYCL0] 
  REPEAT_BACK(type=f32,ne=[8,6,4,2],nr=[1,1,2,1],v=1): not supported [SYCL0] 
  REPEAT_BACK(type=f32,ne=[8,6,4,2],nr=[1,1,1,2],v=1): not supported [SYCL0] 
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
  SET(type_src=i32,type_dst=i32,ne=[6,5,4,3],dim=1): not supported [SYCL0] 
  SET(type_src=i32,type_dst=i32,ne=[6,5,4,3],dim=2): not supported [SYCL0] 
  SET(type_src=i32,type_dst=i32,ne=[6,5,4,3],dim=3): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=f32,ne=[1,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=f32,ne=[1,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=f32,ne=[1,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=f32,ne=[2,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=f32,ne=[2,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=f32,ne=[2,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=f32,ne=[3,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=f32,ne=[3,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=f32,ne=[3,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): [1;32mOK[0m
  CPY(type_src=f16,type_dst=f16,ne=[1,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=f16,type_dst=f16,ne=[1,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=f16,type_dst=f16,ne=[1,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): [1;32mOK[0m
  CPY(type_src=f16,type_dst=f16,ne=[2,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=f16,type_dst=f16,ne=[2,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=f16,type_dst=f16,ne=[2,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): [1;32mOK[0m
  CPY(type_src=f16,type_dst=f16,ne=[3,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=f16,type_dst=f16,ne=[3,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=f16,type_dst=f16,ne=[3,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): [1;32mOK[0m
  CPY(type_src=bf16,type_dst=bf16,ne=[1,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=bf16,ne=[1,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=bf16,ne=[1,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=bf16,ne=[2,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=bf16,ne=[2,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=bf16,ne=[2,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=bf16,ne=[3,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=bf16,ne=[3,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=bf16,ne=[3,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=q4_0,type_dst=q4_0,ne=[32,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q4_0,type_dst=q4_0,ne=[32,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q4_0,type_dst=q4_0,ne=[32,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): [1;32mOK[0m
  CPY(type_src=q4_0,type_dst=q4_0,ne=[64,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q4_0,type_dst=q4_0,ne=[64,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q4_0,type_dst=q4_0,ne=[64,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): [1;32mOK[0m
  CPY(type_src=q4_0,type_dst=q4_0,ne=[96,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q4_0,type_dst=q4_0,ne=[96,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q4_0,type_dst=q4_0,ne=[96,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): [1;32mOK[0m
  CPY(type_src=q4_1,type_dst=q4_1,ne=[32,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q4_1,type_dst=q4_1,ne=[32,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q4_1,type_dst=q4_1,ne=[32,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): [1;32mOK[0m
  CPY(type_src=q4_1,type_dst=q4_1,ne=[64,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q4_1,type_dst=q4_1,ne=[64,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q4_1,type_dst=q4_1,ne=[64,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): [1;32mOK[0m
  CPY(type_src=q4_1,type_dst=q4_1,ne=[96,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q4_1,type_dst=q4_1,ne=[96,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q4_1,type_dst=q4_1,ne=[96,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): [1;32mOK[0m
  CPY(type_src=q5_0,type_dst=q5_0,ne=[32,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q5_0,type_dst=q5_0,ne=[32,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q5_0,type_dst=q5_0,ne=[32,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): [1;32mOK[0m
  CPY(type_src=q5_0,type_dst=q5_0,ne=[64,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q5_0,type_dst=q5_0,ne=[64,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q5_0,type_dst=q5_0,ne=[64,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): [1;32mOK[0m
  CPY(type_src=q5_0,type_dst=q5_0,ne=[96,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q5_0,type_dst=q5_0,ne=[96,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q5_0,type_dst=q5_0,ne=[96,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): [1;32mOK[0m
  CPY(type_src=q5_1,type_dst=q5_1,ne=[32,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q5_1,type_dst=q5_1,ne=[32,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q5_1,type_dst=q5_1,ne=[32,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): [1;32mOK[0m
  CPY(type_src=q5_1,type_dst=q5_1,ne=[64,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q5_1,type_dst=q5_1,ne=[64,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q5_1,type_dst=q5_1,ne=[64,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): [1;32mOK[0m
  CPY(type_src=q5_1,type_dst=q5_1,ne=[96,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q5_1,type_dst=q5_1,ne=[96,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q5_1,type_dst=q5_1,ne=[96,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): [1;32mOK[0m
  CPY(type_src=q8_0,type_dst=q8_0,ne=[32,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q8_0,type_dst=q8_0,ne=[32,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q8_0,type_dst=q8_0,ne=[32,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): [1;32mOK[0m
  CPY(type_src=q8_0,type_dst=q8_0,ne=[64,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q8_0,type_dst=q8_0,ne=[64,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q8_0,type_dst=q8_0,ne=[64,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): [1;32mOK[0m
  CPY(type_src=q8_0,type_dst=q8_0,ne=[96,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q8_0,type_dst=q8_0,ne=[96,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q8_0,type_dst=q8_0,ne=[96,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): [1;32mOK[0m
  CPY(type_src=q2_K,type_dst=q2_K,ne=[256,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q2_K,type_dst=q2_K,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=q2_K,type_dst=q2_K,ne=[256,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=q2_K,type_dst=q2_K,ne=[512,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q2_K,type_dst=q2_K,ne=[512,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=q2_K,type_dst=q2_K,ne=[512,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=q2_K,type_dst=q2_K,ne=[768,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q2_K,type_dst=q2_K,ne=[768,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=q2_K,type_dst=q2_K,ne=[768,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=q3_K,type_dst=q3_K,ne=[256,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q3_K,type_dst=q3_K,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=q3_K,type_dst=q3_K,ne=[256,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=q3_K,type_dst=q3_K,ne=[512,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q3_K,type_dst=q3_K,ne=[512,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=q3_K,type_dst=q3_K,ne=[512,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=q3_K,type_dst=q3_K,ne=[768,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q3_K,type_dst=q3_K,ne=[768,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=q3_K,type_dst=q3_K,ne=[768,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=q4_K,type_dst=q4_K,ne=[256,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q4_K,type_dst=q4_K,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=q4_K,type_dst=q4_K,ne=[256,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=q4_K,type_dst=q4_K,ne=[512,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q4_K,type_dst=q4_K,ne=[512,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=q4_K,type_dst=q4_K,ne=[512,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=q4_K,type_dst=q4_K,ne=[768,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q4_K,type_dst=q4_K,ne=[768,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=q4_K,type_dst=q4_K,ne=[768,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=q5_K,type_dst=q5_K,ne=[256,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q5_K,type_dst=q5_K,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=q5_K,type_dst=q5_K,ne=[256,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=q5_K,type_dst=q5_K,ne=[512,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q5_K,type_dst=q5_K,ne=[512,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=q5_K,type_dst=q5_K,ne=[512,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=q5_K,type_dst=q5_K,ne=[768,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q5_K,type_dst=q5_K,ne=[768,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=q5_K,type_dst=q5_K,ne=[768,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=q6_K,type_dst=q6_K,ne=[256,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q6_K,type_dst=q6_K,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=q6_K,type_dst=q6_K,ne=[256,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=q6_K,type_dst=q6_K,ne=[512,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q6_K,type_dst=q6_K,ne=[512,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=q6_K,type_dst=q6_K,ne=[512,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=q6_K,type_dst=q6_K,ne=[768,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q6_K,type_dst=q6_K,ne=[768,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=q6_K,type_dst=q6_K,ne=[768,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=iq2_xxs,type_dst=iq2_xxs,ne=[256,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq2_xxs,type_dst=iq2_xxs,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq2_xxs,type_dst=iq2_xxs,ne=[256,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=iq2_xxs,type_dst=iq2_xxs,ne=[512,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq2_xxs,type_dst=iq2_xxs,ne=[512,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq2_xxs,type_dst=iq2_xxs,ne=[512,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=iq2_xxs,type_dst=iq2_xxs,ne=[768,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq2_xxs,type_dst=iq2_xxs,ne=[768,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq2_xxs,type_dst=iq2_xxs,ne=[768,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=iq2_xs,type_dst=iq2_xs,ne=[256,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq2_xs,type_dst=iq2_xs,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq2_xs,type_dst=iq2_xs,ne=[256,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=iq2_xs,type_dst=iq2_xs,ne=[512,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq2_xs,type_dst=iq2_xs,ne=[512,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq2_xs,type_dst=iq2_xs,ne=[512,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=iq2_xs,type_dst=iq2_xs,ne=[768,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq2_xs,type_dst=iq2_xs,ne=[768,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq2_xs,type_dst=iq2_xs,ne=[768,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=iq2_s,type_dst=iq2_s,ne=[256,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq2_s,type_dst=iq2_s,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq2_s,type_dst=iq2_s,ne=[256,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=iq2_s,type_dst=iq2_s,ne=[512,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq2_s,type_dst=iq2_s,ne=[512,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq2_s,type_dst=iq2_s,ne=[512,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=iq2_s,type_dst=iq2_s,ne=[768,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq2_s,type_dst=iq2_s,ne=[768,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq2_s,type_dst=iq2_s,ne=[768,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=iq3_xxs,type_dst=iq3_xxs,ne=[256,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq3_xxs,type_dst=iq3_xxs,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq3_xxs,type_dst=iq3_xxs,ne=[256,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=iq3_xxs,type_dst=iq3_xxs,ne=[512,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq3_xxs,type_dst=iq3_xxs,ne=[512,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq3_xxs,type_dst=iq3_xxs,ne=[512,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=iq3_xxs,type_dst=iq3_xxs,ne=[768,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq3_xxs,type_dst=iq3_xxs,ne=[768,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq3_xxs,type_dst=iq3_xxs,ne=[768,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=iq1_s,type_dst=iq1_s,ne=[256,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq1_s,type_dst=iq1_s,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq1_s,type_dst=iq1_s,ne=[256,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=iq1_s,type_dst=iq1_s,ne=[512,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq1_s,type_dst=iq1_s,ne=[512,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq1_s,type_dst=iq1_s,ne=[512,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=iq1_s,type_dst=iq1_s,ne=[768,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq1_s,type_dst=iq1_s,ne=[768,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq1_s,type_dst=iq1_s,ne=[768,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=iq1_m,type_dst=iq1_m,ne=[256,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq1_m,type_dst=iq1_m,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq1_m,type_dst=iq1_m,ne=[256,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=iq1_m,type_dst=iq1_m,ne=[512,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq1_m,type_dst=iq1_m,ne=[512,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq1_m,type_dst=iq1_m,ne=[512,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=iq1_m,type_dst=iq1_m,ne=[768,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq1_m,type_dst=iq1_m,ne=[768,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq1_m,type_dst=iq1_m,ne=[768,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=iq4_nl,type_dst=iq4_nl,ne=[32,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=iq4_nl,type_dst=iq4_nl,ne=[32,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq4_nl,type_dst=iq4_nl,ne=[32,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=iq4_nl,type_dst=iq4_nl,ne=[64,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=iq4_nl,type_dst=iq4_nl,ne=[64,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq4_nl,type_dst=iq4_nl,ne=[64,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=iq4_nl,type_dst=iq4_nl,ne=[96,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=iq4_nl,type_dst=iq4_nl,ne=[96,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq4_nl,type_dst=iq4_nl,ne=[96,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=iq3_s,type_dst=iq3_s,ne=[256,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq3_s,type_dst=iq3_s,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq3_s,type_dst=iq3_s,ne=[256,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=iq3_s,type_dst=iq3_s,ne=[512,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq3_s,type_dst=iq3_s,ne=[512,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq3_s,type_dst=iq3_s,ne=[512,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=iq3_s,type_dst=iq3_s,ne=[768,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq3_s,type_dst=iq3_s,ne=[768,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq3_s,type_dst=iq3_s,ne=[768,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=iq4_xs,type_dst=iq4_xs,ne=[256,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=iq4_xs,type_dst=iq4_xs,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq4_xs,type_dst=iq4_xs,ne=[256,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=iq4_xs,type_dst=iq4_xs,ne=[512,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=iq4_xs,type_dst=iq4_xs,ne=[512,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq4_xs,type_dst=iq4_xs,ne=[512,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=iq4_xs,type_dst=iq4_xs,ne=[768,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=iq4_xs,type_dst=iq4_xs,ne=[768,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq4_xs,type_dst=iq4_xs,ne=[768,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=f16,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=f16,type_dst=f16,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=f16,type_dst=f16,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=f16,type_dst=bf16,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=bf16,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q4_0,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q4_0,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q4_1,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q4_1,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q5_0,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q5_0,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q5_1,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q5_1,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q8_0,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q8_0,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q2_K,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q2_K,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q3_K,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q3_K,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q4_K,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q4_K,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q5_K,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q5_K,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q6_K,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q6_K,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq2_xxs,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq2_xxs,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq2_xs,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq2_xs,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq2_s,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq2_s,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq3_xxs,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq3_xxs,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq1_s,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq1_s,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq1_m,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq1_m,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq4_nl,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq4_nl,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq3_s,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq3_s,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq4_xs,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq4_xs,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=f16,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=f16,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=bf16,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=bf16,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=q4_0,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=q4_0,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=q4_1,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=q4_1,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=q5_0,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=q5_0,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=q5_1,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=q5_1,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=q8_0,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=q8_0,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=q2_K,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=q2_K,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=q3_K,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=q3_K,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=q4_K,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=q4_K,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=q5_K,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=q5_K,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=q6_K,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=q6_K,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=iq2_xxs,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=iq2_xxs,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=iq2_xs,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=iq2_xs,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=iq2_s,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=iq2_s,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=iq3_xxs,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=iq3_xxs,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=iq1_s,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=iq1_s,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=iq1_m,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=iq1_m,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=iq4_nl,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=iq4_nl,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=iq3_s,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=iq3_s,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=iq4_xs,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=iq4_xs,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=f16,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=f16,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=bf16,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=bf16,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=q4_0,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=q4_0,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): [1;32mOK[0m
[CPY] NMSE = 0.000002884 > 0.000001000   CPY(type_src=f32,type_dst=q4_1,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;31mFAIL[0m
  CPY(type_src=f32,type_dst=q4_1,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=q5_0,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=q5_0,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=q5_1,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=q5_1,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=q8_0,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=q8_0,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=q2_K,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=q2_K,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=q3_K,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=q3_K,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=q4_K,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=q4_K,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=q5_K,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=q5_K,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=q6_K,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=q6_K,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq2_xxs,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq2_xxs,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq2_xs,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq2_xs,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq2_s,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq2_s,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq3_xxs,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq3_xxs,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq1_s,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq1_s,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq1_m,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq1_m,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq4_nl,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=iq4_nl,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=iq3_s,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq3_s,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq4_xs,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq4_xs,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=f16,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=f16,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=bf16,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=q4_0,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q4_0,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q4_1,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q4_1,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q5_0,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q5_0,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q5_1,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q5_1,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q8_0,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q8_0,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=q2_K,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=q2_K,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=q3_K,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=q3_K,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=q4_K,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=q4_K,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=q5_K,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=q5_K,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=q6_K,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=q6_K,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq2_xxs,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq2_xxs,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq2_xs,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq2_xs,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq2_s,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq2_s,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq3_xxs,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq3_xxs,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq1_s,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq1_s,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq1_m,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq1_m,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq4_nl,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq4_nl,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq3_s,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq3_s,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq4_xs,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=iq4_xs,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0]): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=f16,ne=[256,2,3,4],permute_src=[1,0,2,3],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=f16,type_dst=f32,ne=[256,2,3,4],permute_src=[1,0,2,3],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=f16,ne=[256,2,3,4],permute_src=[1,0,2,3],permute_dst=[0,0,0,0]): [1;32mOK[0m
  CPY(type_src=f32,type_dst=f32,ne=[256,2,3,4],permute_src=[1,0,2,3],permute_dst=[0,0,0,0]): [1;32mOK[0m
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
  ADD(type=f16,ne=[1,1,8,1],nr=[1,1,1,1]): [1;32mOK[0m
  SUB(type=f16,ne=[1,1,8,1],nr=[1,1,1,1]): [1;32mOK[0m
  MUL(type=f16,ne=[1,1,8,1],nr=[1,1,1,1]): [1;32mOK[0m
  DIV(type=f16,ne=[1,1,8,1],nr=[1,1,1,1]): [1;32mOK[0m
  ADD(type=f16,ne=[1,1,1,1],nr=[32,1,1,1]): [1;32mOK[0m
  SUB(type=f16,ne=[1,1,1,1],nr=[32,1,1,1]): [1;32mOK[0m
  MUL(type=f16,ne=[1,1,1,1],nr=[32,1,1,1]): [1;32mOK[0m
  DIV(type=f16,ne=[1,1,1,1],nr=[32,1,1,1]): [1;32mOK[0m
  ADD(type=f16,ne=[1,1,320,320],nr=[1,1,1,1]): [1;32mOK[0m
  SUB(type=f16,ne=[1,1,320,320],nr=[1,1,1,1]): [1;32mOK[0m
  MUL(type=f16,ne=[1,1,320,320],nr=[1,1,1,1]): [1;32mOK[0m
  DIV(type=f16,ne=[1,1,320,320],nr=[1,1,1,1]): [1;32mOK[0m
  ADD(type=f16,ne=[10,5,1,1],nr=[1,1,1,1]): [1;32mOK[0m
  SUB(type=f16,ne=[10,5,1,1],nr=[1,1,1,1]): [1;32mOK[0m
  MUL(type=f16,ne=[10,5,1,1],nr=[1,1,1,1]): [1;32mOK[0m
  DIV(type=f16,ne=[10,5,1,1],nr=[1,1,1,1]): [1;32mOK[0m
  ADD(type=f16,ne=[10,5,4,1],nr=[1,1,1,1]): [1;32mOK[0m
  SUB(type=f16,ne=[10,5,4,1],nr=[1,1,1,1]): [1;32mOK[0m
  MUL(type=f16,ne=[10,5,4,1],nr=[1,1,1,1]): [1;32mOK[0m
  DIV(type=f16,ne=[10,5,4,1],nr=[1,1,1,1]): [1;32mOK[0m
  ADD(type=f16,ne=[10,5,4,3],nr=[1,1,1,1]): [1;32mOK[0m
  SUB(type=f16,ne=[10,5,4,3],nr=[1,1,1,1]): [1;32mOK[0m
  MUL(type=f16,ne=[10,5,4,3],nr=[1,1,1,1]): [1;32mOK[0m
  DIV(type=f16,ne=[10,5,4,3],nr=[1,1,1,1]): [1;32mOK[0m
  ADD(type=f16,ne=[10,5,4,3],nr=[2,1,1,1]): [1;32mOK[0m
  SUB(type=f16,ne=[10,5,4,3],nr=[2,1,1,1]): [1;32mOK[0m
  MUL(type=f16,ne=[10,5,4,3],nr=[2,1,1,1]): [1;32mOK[0m
  DIV(type=f16,ne=[10,5,4,3],nr=[2,1,1,1]): [1;32mOK[0m
  ADD(type=f16,ne=[10,5,4,3],nr=[1,2,1,1]): [1;32mOK[0m
  SUB(type=f16,ne=[10,5,4,3],nr=[1,2,1,1]): [1;32mOK[0m
  MUL(type=f16,ne=[10,5,4,3],nr=[1,2,1,1]): [1;32mOK[0m
  DIV(type=f16,ne=[10,5,4,3],nr=[1,2,1,1]): [1;32mOK[0m
  ADD(type=f16,ne=[10,5,4,3],nr=[1,1,2,1]): [1;32mOK[0m
  SUB(type=f16,ne=[10,5,4,3],nr=[1,1,2,1]): [1;32mOK[0m
  MUL(type=f16,ne=[10,5,4,3],nr=[1,1,2,1]): [1;32mOK[0m
  DIV(type=f16,ne=[10,5,4,3],nr=[1,1,2,1]): [1;32mOK[0m
  ADD(type=f16,ne=[10,5,4,3],nr=[1,1,1,2]): [1;32mOK[0m
  SUB(type=f16,ne=[10,5,4,3],nr=[1,1,1,2]): [1;32mOK[0m
  MUL(type=f16,ne=[10,5,4,3],nr=[1,1,1,2]): [1;32mOK[0m
  DIV(type=f16,ne=[10,5,4,3],nr=[1,1,1,2]): [1;32mOK[0m
  ADD(type=f16,ne=[10,5,4,3],nr=[1,1,2,2]): [1;32mOK[0m
  SUB(type=f16,ne=[10,5,4,3],nr=[1,1,2,2]): [1;32mOK[0m
  MUL(type=f16,ne=[10,5,4,3],nr=[1,1,2,2]): [1;32mOK[0m
  DIV(type=f16,ne=[10,5,4,3],nr=[1,1,2,2]): [1;32mOK[0m
  ADD(type=f16,ne=[10,5,4,3],nr=[1,2,2,2]): [1;32mOK[0m
  SUB(type=f16,ne=[10,5,4,3],nr=[1,2,2,2]): [1;32mOK[0m
  MUL(type=f16,ne=[10,5,4,3],nr=[1,2,2,2]): [1;32mOK[0m
  DIV(type=f16,ne=[10,5,4,3],nr=[1,2,2,2]): [1;32mOK[0m
  ADD(type=f16,ne=[10,5,4,3],nr=[2,2,2,2]): [1;32mOK[0m
  SUB(type=f16,ne=[10,5,4,3],nr=[2,2,2,2]): [1;32mOK[0m
  MUL(type=f16,ne=[10,5,4,3],nr=[2,2,2,2]): [1;32mOK[0m
  DIV(type=f16,ne=[10,5,4,3],nr=[2,2,2,2]): [1;32mOK[0m
  ADD(type=f16,ne=[1280,1,1,1],nr=[1,1,1,1]): [1;32mOK[0m
  SUB(type=f16,ne=[1280,1,1,1],nr=[1,1,1,1]): [1;32mOK[0m
  MUL(type=f16,ne=[1280,1,1,1],nr=[1,1,1,1]): [1;32mOK[0m
  DIV(type=f16,ne=[1280,1,1,1],nr=[1,1,1,1]): [1;32mOK[0m
  ADD(type=f16,ne=[1280,1,1,1],nr=[1,16,16,1]): [1;32mOK[0m
  SUB(type=f16,ne=[1280,1,1,1],nr=[1,16,16,1]): [1;32mOK[0m
  MUL(type=f16,ne=[1280,1,1,1],nr=[1,16,16,1]): [1;32mOK[0m
  DIV(type=f16,ne=[1280,1,1,1],nr=[1,16,16,1]): [1;32mOK[0m
  ADD(type=f16,ne=[1280,16,16,1],nr=[1,1,1,1]): [1;32mOK[0m
  SUB(type=f16,ne=[1280,16,16,1],nr=[1,1,1,1]): [1;32mOK[0m
  MUL(type=f16,ne=[1280,16,16,1],nr=[1,1,1,1]): [1;32mOK[0m
  DIV(type=f16,ne=[1280,16,16,1],nr=[1,1,1,1]): [1;32mOK[0m
  ADD(type=f16,ne=[1280,1,1,1],nr=[1,256,1,1]): [1;32mOK[0m
  SUB(type=f16,ne=[1280,1,1,1],nr=[1,256,1,1]): [1;32mOK[0m
  MUL(type=f16,ne=[1280,1,1,1],nr=[1,256,1,1]): [1;32mOK[0m
  DIV(type=f16,ne=[1280,1,1,1],nr=[1,256,1,1]): [1;32mOK[0m
  ADD(type=f16,ne=[1,1,1280,1],nr=[16,16,1,1]): [1;32mOK[0m
  SUB(type=f16,ne=[1,1,1280,1],nr=[16,16,1,1]): [1;32mOK[0m
  MUL(type=f16,ne=[1,1,1280,1],nr=[16,16,1,1]): [1;32mOK[0m
  DIV(type=f16,ne=[1,1,1280,1],nr=[16,16,1,1]): [1;32mOK[0m
  ADD(type=f16,ne=[16,16,1280,1],nr=[1,1,1,1]): [1;32mOK[0m
  SUB(type=f16,ne=[16,16,1280,1],nr=[1,1,1,1]): [1;32mOK[0m
  MUL(type=f16,ne=[16,16,1280,1],nr=[1,1,1,1]): [1;32mOK[0m
  DIV(type=f16,ne=[16,16,1280,1],nr=[1,1,1,1]): [1;32mOK[0m
  ADD(type=f16,ne=[1,1,1920,1],nr=[16,16,1,1]): [1;32mOK[0m
  SUB(type=f16,ne=[1,1,1920,1],nr=[16,16,1,1]): [1;32mOK[0m
  MUL(type=f16,ne=[1,1,1920,1],nr=[16,16,1,1]): [1;32mOK[0m
  DIV(type=f16,ne=[1,1,1920,1],nr=[16,16,1,1]): [1;32mOK[0m
  ADD(type=f16,ne=[1,1,2560,1],nr=[16,16,1,1]): [1;32mOK[0m
  SUB(type=f16,ne=[1,1,2560,1],nr=[16,16,1,1]): [1;32mOK[0m
  MUL(type=f16,ne=[1,1,2560,1],nr=[16,16,1,1]): [1;32mOK[0m
  DIV(type=f16,ne=[1,1,2560,1],nr=[16,16,1,1]): [1;32mOK[0m
  ADD(type=f16,ne=[1,1,1280,1],nr=[32,32,1,1]): [1;32mOK[0m
  SUB(type=f16,ne=[1,1,1280,1],nr=[32,32,1,1]): [1;32mOK[0m
  MUL(type=f16,ne=[1,1,1280,1],nr=[32,32,1,1]): [1;32mOK[0m
  DIV(type=f16,ne=[1,1,1280,1],nr=[32,32,1,1]): [1;32mOK[0m
  ADD(type=f16,ne=[1,1,1920,1],nr=[32,32,1,1]): [1;32mOK[0m
  SUB(type=f16,ne=[1,1,1920,1],nr=[32,32,1,1]): [1;32mOK[0m
  MUL(type=f16,ne=[1,1,1920,1],nr=[32,32,1,1]): [1;32mOK[0m
  DIV(type=f16,ne=[1,1,1920,1],nr=[32,32,1,1]): [1;32mOK[0m
  ADD(type=f16,ne=[1,1,640,1],nr=[32,32,1,1]): [1;32mOK[0m
  SUB(type=f16,ne=[1,1,640,1],nr=[32,32,1,1]): [1;32mOK[0m
  MUL(type=f16,ne=[1,1,640,1],nr=[32,32,1,1]): [1;32mOK[0m
  DIV(type=f16,ne=[1,1,640,1],nr=[32,32,1,1]): [1;32mOK[0m
  ADD(type=f16,ne=[5120,1,1,1],nr=[1,256,1,1]): [1;32mOK[0m
  SUB(type=f16,ne=[5120,1,1,1],nr=[1,256,1,1]): [1;32mOK[0m
  MUL(type=f16,ne=[5120,1,1,1],nr=[1,256,1,1]): [1;32mOK[0m
  DIV(type=f16,ne=[5120,1,1,1],nr=[1,256,1,1]): [1;32mOK[0m
  ADD(type=f16,ne=[640,1,1,1],nr=[1,1,1,1]): [1;32mOK[0m
  SUB(type=f16,ne=[640,1,1,1],nr=[1,1,1,1]): [1;32mOK[0m
  MUL(type=f16,ne=[640,1,1,1],nr=[1,1,1,1]): [1;32mOK[0m
  DIV(type=f16,ne=[640,1,1,1],nr=[1,1,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[1,1,8,1],nr=[1,1,1,1]): [1;32mOK[0m
  SUB(type=f32,ne=[1,1,8,1],nr=[1,1,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[1,1,8,1],nr=[1,1,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[1,1,8,1],nr=[1,1,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[1,1,1,1],nr=[32,1,1,1]): [1;32mOK[0m
  SUB(type=f32,ne=[1,1,1,1],nr=[32,1,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[1,1,1,1],nr=[32,1,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[1,1,1,1],nr=[32,1,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[1,1,320,320],nr=[1,1,1,1]): [1;32mOK[0m
  SUB(type=f32,ne=[1,1,320,320],nr=[1,1,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[1,1,320,320],nr=[1,1,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[1,1,320,320],nr=[1,1,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[10,5,1,1],nr=[1,1,1,1]): [1;32mOK[0m
  SUB(type=f32,ne=[10,5,1,1],nr=[1,1,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[10,5,1,1],nr=[1,1,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[10,5,1,1],nr=[1,1,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[10,5,4,1],nr=[1,1,1,1]): [1;32mOK[0m
  SUB(type=f32,ne=[10,5,4,1],nr=[1,1,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[10,5,4,1],nr=[1,1,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[10,5,4,1],nr=[1,1,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[10,5,4,3],nr=[1,1,1,1]): [1;32mOK[0m
  SUB(type=f32,ne=[10,5,4,3],nr=[1,1,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[10,5,4,3],nr=[1,1,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[10,5,4,3],nr=[1,1,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[10,5,4,3],nr=[2,1,1,1]): [1;32mOK[0m
  SUB(type=f32,ne=[10,5,4,3],nr=[2,1,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[10,5,4,3],nr=[2,1,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[10,5,4,3],nr=[2,1,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[10,5,4,3],nr=[1,2,1,1]): [1;32mOK[0m
  SUB(type=f32,ne=[10,5,4,3],nr=[1,2,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[10,5,4,3],nr=[1,2,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[10,5,4,3],nr=[1,2,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[10,5,4,3],nr=[1,1,2,1]): [1;32mOK[0m
  SUB(type=f32,ne=[10,5,4,3],nr=[1,1,2,1]): [1;32mOK[0m
  MUL(type=f32,ne=[10,5,4,3],nr=[1,1,2,1]): [1;32mOK[0m
  DIV(type=f32,ne=[10,5,4,3],nr=[1,1,2,1]): [1;32mOK[0m
  ADD(type=f32,ne=[10,5,4,3],nr=[1,1,1,2]): [1;32mOK[0m
  SUB(type=f32,ne=[10,5,4,3],nr=[1,1,1,2]): [1;32mOK[0m
  MUL(type=f32,ne=[10,5,4,3],nr=[1,1,1,2]): [1;32mOK[0m
  DIV(type=f32,ne=[10,5,4,3],nr=[1,1,1,2]): [1;32mOK[0m
  ADD(type=f32,ne=[10,5,4,3],nr=[1,1,2,2]): [1;32mOK[0m
  SUB(type=f32,ne=[10,5,4,3],nr=[1,1,2,2]): [1;32mOK[0m
  MUL(type=f32,ne=[10,5,4,3],nr=[1,1,2,2]): [1;32mOK[0m
  DIV(type=f32,ne=[10,5,4,3],nr=[1,1,2,2]): [1;32mOK[0m
  ADD(type=f32,ne=[10,5,4,3],nr=[1,2,2,2]): [1;32mOK[0m
  SUB(type=f32,ne=[10,5,4,3],nr=[1,2,2,2]): [1;32mOK[0m
  MUL(type=f32,ne=[10,5,4,3],nr=[1,2,2,2]): [1;32mOK[0m
  DIV(type=f32,ne=[10,5,4,3],nr=[1,2,2,2]): [1;32mOK[0m
  ADD(type=f32,ne=[10,5,4,3],nr=[2,2,2,2]): [1;32mOK[0m
  SUB(type=f32,ne=[10,5,4,3],nr=[2,2,2,2]): [1;32mOK[0m
  MUL(type=f32,ne=[10,5,4,3],nr=[2,2,2,2]): [1;32mOK[0m
  DIV(type=f32,ne=[10,5,4,3],nr=[2,2,2,2]): [1;32mOK[0m
  ADD(type=f32,ne=[1280,1,1,1],nr=[1,1,1,1]): [1;32mOK[0m
  SUB(type=f32,ne=[1280,1,1,1],nr=[1,1,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[1280,1,1,1],nr=[1,1,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[1280,1,1,1],nr=[1,1,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[1280,1,1,1],nr=[1,16,16,1]): [1;32mOK[0m
  SUB(type=f32,ne=[1280,1,1,1],nr=[1,16,16,1]): [1;32mOK[0m
  MUL(type=f32,ne=[1280,1,1,1],nr=[1,16,16,1]): [1;32mOK[0m
  DIV(type=f32,ne=[1280,1,1,1],nr=[1,16,16,1]): [1;32mOK[0m
  ADD(type=f32,ne=[1280,16,16,1],nr=[1,1,1,1]): [1;32mOK[0m
  SUB(type=f32,ne=[1280,16,16,1],nr=[1,1,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[1280,16,16,1],nr=[1,1,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[1280,16,16,1],nr=[1,1,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[1280,1,1,1],nr=[1,256,1,1]): [1;32mOK[0m
  SUB(type=f32,ne=[1280,1,1,1],nr=[1,256,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[1280,1,1,1],nr=[1,256,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[1280,1,1,1],nr=[1,256,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[1,1,1280,1],nr=[16,16,1,1]): [1;32mOK[0m
  SUB(type=f32,ne=[1,1,1280,1],nr=[16,16,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[1,1,1280,1],nr=[16,16,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[1,1,1280,1],nr=[16,16,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[16,16,1280,1],nr=[1,1,1,1]): [1;32mOK[0m
  SUB(type=f32,ne=[16,16,1280,1],nr=[1,1,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[16,16,1280,1],nr=[1,1,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[16,16,1280,1],nr=[1,1,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[1,1,1920,1],nr=[16,16,1,1]): [1;32mOK[0m
  SUB(type=f32,ne=[1,1,1920,1],nr=[16,16,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[1,1,1920,1],nr=[16,16,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[1,1,1920,1],nr=[16,16,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[1,1,2560,1],nr=[16,16,1,1]): [1;32mOK[0m
  SUB(type=f32,ne=[1,1,2560,1],nr=[16,16,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[1,1,2560,1],nr=[16,16,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[1,1,2560,1],nr=[16,16,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[1,1,1280,1],nr=[32,32,1,1]): [1;32mOK[0m
  SUB(type=f32,ne=[1,1,1280,1],nr=[32,32,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[1,1,1280,1],nr=[32,32,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[1,1,1280,1],nr=[32,32,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[1,1,1920,1],nr=[32,32,1,1]): [1;32mOK[0m
  SUB(type=f32,ne=[1,1,1920,1],nr=[32,32,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[1,1,1920,1],nr=[32,32,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[1,1,1920,1],nr=[32,32,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[1,1,640,1],nr=[32,32,1,1]): [1;32mOK[0m
  SUB(type=f32,ne=[1,1,640,1],nr=[32,32,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[1,1,640,1],nr=[32,32,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[1,1,640,1],nr=[32,32,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[5120,1,1,1],nr=[1,256,1,1]): [1;32mOK[0m
  SUB(type=f32,ne=[5120,1,1,1],nr=[1,256,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[5120,1,1,1],nr=[1,256,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[5120,1,1,1],nr=[1,256,1,1]): [1;32mOK[0m
  ADD(type=f32,ne=[640,1,1,1],nr=[1,1,1,1]): [1;32mOK[0m
  SUB(type=f32,ne=[640,1,1,1],nr=[1,1,1,1]): [1;32mOK[0m
  MUL(type=f32,ne=[640,1,1,1],nr=[1,1,1,1]): [1;32mOK[0m
  DIV(type=f32,ne=[640,1,1,1],nr=[1,1,1,1]): [1;32mOK[0m
  ADD1(type=f32,ne=[10,5,4,3]): [1;32mOK[0m
  SCALE(type=f32,ne=[10,10,10,10],scale=2.000000,bias=0.000000): [1;32mOK[0m
  SCALE(type=f32,ne=[10,10,10,10],scale=2.000000,bias=1.000000): [1;32mOK[0m
  SILU_BACK(type=f32,ne=[64,5,4,3],eps=0.000001): not supported [SYCL0] 
  NORM(type=f32,ne=[64,5,4,3],v=0,eps=0.000000): [1;32mOK[0m
  RMS_NORM(type=f32,ne=[64,5,4,3],v=0,eps=0.000000): [1;32mOK[0m
  NORM(type=f32,ne=[64,5,4,3],v=1,eps=0.000000): [1;32mOK[0m
  RMS_NORM(type=f32,ne=[64,5,4,3],v=1,eps=0.000000): [1;32mOK[0m
  RMS_NORM_BACK(type=f32,ne=[64,5,4,3],eps=0.000000): not supported [SYCL0] 
  L2_NORM(type=f32,ne=[64,5,4,3]): [1;32mOK[0m
  NORM(type=f32,ne=[64,5,4,3],v=0,eps=0.000001): [1;32mOK[0m
  RMS_NORM(type=f32,ne=[64,5,4,3],v=0,eps=0.000001): [1;32mOK[0m
  NORM(type=f32,ne=[64,5,4,3],v=1,eps=0.000001): [1;32mOK[0m
  RMS_NORM(type=f32,ne=[64,5,4,3],v=1,eps=0.000001): [1;32mOK[0m
  RMS_NORM_BACK(type=f32,ne=[64,5,4,3],eps=0.000001): not supported [SYCL0] 
  L2_NORM(type=f32,ne=[64,5,4,3]): [1;32mOK[0m
  NORM(type=f32,ne=[64,5,4,3],v=0,eps=0.000100): [1;32mOK[0m
  RMS_NORM(type=f32,ne=[64,5,4,3],v=0,eps=0.000100): [1;32mOK[0m
  NORM(type=f32,ne=[64,5,4,3],v=1,eps=0.000100): [1;32mOK[0m
  RMS_NORM(type=f32,ne=[64,5,4,3],v=1,eps=0.000100): [1;32mOK[0m
  RMS_NORM_BACK(type=f32,ne=[64,5,4,3],eps=0.000100): not supported [SYCL0] 
  L2_NORM(type=f32,ne=[64,5,4,3]): [1;32mOK[0m
  NORM(type=f32,ne=[64,5,4,3],v=0,eps=0.100000): [1;32mOK[0m
  RMS_NORM(type=f32,ne=[64,5,4,3],v=0,eps=0.100000): [1;32mOK[0m
  NORM(type=f32,ne=[64,5,4,3],v=1,eps=0.100000): [1;32mOK[0m
  RMS_NORM(type=f32,ne=[64,5,4,3],v=1,eps=0.100000): [1;32mOK[0m
  RMS_NORM_BACK(type=f32,ne=[64,5,4,3],eps=0.100000): not supported [SYCL0] 
  L2_NORM(type=f32,ne=[64,5,4,3]): [1;32mOK[0m
  RMS_NORM_MUL(type=f32,ne=[64,5,4,3],eps=0.000000): [1;32mOK[0m
  RMS_NORM_MUL(type=f32,ne=[64,5,4,3],eps=0.000001): [1;32mOK[0m
  RMS_NORM_MUL(type=f32,ne=[64,5,4,3],eps=0.000100): [1;32mOK[0m
  RMS_NORM_MUL(type=f32,ne=[64,5,4,3],eps=0.100000): [1;32mOK[0m
  RMS_NORM_MUL(type=f32,ne=[64,5,4,3],eps=1.000000): [1;32mOK[0m
  L2_NORM(type=f32,ne=[64,5,4,3]): [1;32mOK[0m
  SSM_CONV(type=f32,ne_a=[4,1024,1,1],ne_b=[3,1024,1,1]): not supported [SYCL0] 
  SSM_CONV(type=f32,ne_a=[8,1024,1,1],ne_b=[3,1024,1,1]): not supported [SYCL0] 
  SSM_CONV(type=f32,ne_a=[4,1024,4,1],ne_b=[3,1024,1,1]): not supported [SYCL0] 
  SSM_CONV(type=f32,ne_a=[4,1536,1,1],ne_b=[3,1536,1,1]): not supported [SYCL0] 
  SSM_CONV(type=f32,ne_a=[8,1536,1,1],ne_b=[3,1536,1,1]): not supported [SYCL0] 
  SSM_CONV(type=f32,ne_a=[4,1536,4,1],ne_b=[3,1536,1,1]): not supported [SYCL0] 
  SSM_CONV(type=f32,ne_a=[4,2048,1,1],ne_b=[3,2048,1,1]): not supported [SYCL0] 
  SSM_CONV(type=f32,ne_a=[8,2048,1,1],ne_b=[3,2048,1,1]): not supported [SYCL0] 
  SSM_CONV(type=f32,ne_a=[4,2048,4,1],ne_b=[3,2048,1,1]): not supported [SYCL0] 
  SSM_CONV(type=f32,ne_a=[4,1024,1,1],ne_b=[4,1024,1,1]): not supported [SYCL0] 
  SSM_CONV(type=f32,ne_a=[8,1024,1,1],ne_b=[4,1024,1,1]): not supported [SYCL0] 
  SSM_CONV(type=f32,ne_a=[4,1024,4,1],ne_b=[4,1024,1,1]): not supported [SYCL0] 
  SSM_CONV(type=f32,ne_a=[4,1536,1,1],ne_b=[4,1536,1,1]): not supported [SYCL0] 
  SSM_CONV(type=f32,ne_a=[8,1536,1,1],ne_b=[4,1536,1,1]): not supported [SYCL0] 
  SSM_CONV(type=f32,ne_a=[4,1536,4,1],ne_b=[4,1536,1,1]): not supported [SYCL0] 
  SSM_CONV(type=f32,ne_a=[4,2048,1,1],ne_b=[4,2048,1,1]): not supported [SYCL0] 
  SSM_CONV(type=f32,ne_a=[8,2048,1,1],ne_b=[4,2048,1,1]): not supported [SYCL0] 
  SSM_CONV(type=f32,ne_a=[4,2048,4,1],ne_b=[4,2048,1,1]): not supported [SYCL0] 
  SSM_SCAN(type=f32,d_state=16,head_dim=1,n_head=1024,n_group=1,n_seq_tokens=32,n_seqs=4): not supported [SYCL0] 
  SSM_SCAN(type=f32,d_state=128,head_dim=64,n_head=16,n_group=2,n_seq_tokens=32,n_seqs=4): not supported [SYCL0] 
  SSM_SCAN(type=f32,d_state=256,head_dim=64,n_head=8,n_group=2,n_seq_tokens=32,n_seqs=4): not supported [SYCL0] 
  RWKV_WKV6(type=f32,head_count=32,head_size=64,n_seq_tokens=1,n_seqs=1): [1;32mOK[0m
  RWKV_WKV6(type=f32,head_count=32,head_size=64,n_seq_tokens=32,n_seqs=1): [1;32mOK[0m
  RWKV_WKV6(type=f32,head_count=32,head_size=64,n_seq_tokens=32,n_seqs=4): [1;32mOK[0m
  RWKV_WKV6(type=f32,head_count=32,head_size=64,n_seq_tokens=128,n_seqs=4): [1;32mOK[0m
  RWKV_WKV7(type=f32,head_count=32,head_size=64,n_seq_tokens=1,n_seqs=1): [1;32mOK[0m
  RWKV_WKV7(type=f32,head_count=32,head_size=64,n_seq_tokens=32,n_seqs=1): [1;32mOK[0m
  RWKV_WKV7(type=f32,head_count=32,head_size=64,n_seq_tokens=32,n_seqs=4): [1;32mOK[0m
  RWKV_WKV7(type=f32,head_count=32,head_size=64,n_seq_tokens=128,n_seqs=4): [1;32mOK[0m
  GATED_LINEAR_ATTN(type=f32,head_count=32,head_size=64,n_seq_tokens=1,n_seqs=1): [1;32mOK[0m
  GATED_LINEAR_ATTN(type=f32,head_count=32,head_size=64,n_seq_tokens=32,n_seqs=1): [1;32mOK[0m
  GATED_LINEAR_ATTN(type=f32,head_count=32,head_size=64,n_seq_tokens=32,n_seqs=4): [1;32mOK[0m
  GATED_LINEAR_ATTN(type=f32,head_count=32,head_size=64,n_seq_tokens=128,n_seqs=4): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=2,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=3,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=4,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=5,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=6,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=7,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=8,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=9,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=2,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=3,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=4,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=5,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=6,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=7,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=8,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=9,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=bf16,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=bf16,type_b=f32,m=16,n=2,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=bf16,type_b=f32,m=16,n=3,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=bf16,type_b=f32,m=16,n=4,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=bf16,type_b=f32,m=16,n=5,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=bf16,type_b=f32,m=16,n=6,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=bf16,type_b=f32,m=16,n=7,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=bf16,type_b=f32,m=16,n=8,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=bf16,type_b=f32,m=16,n=9,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=2,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=3,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=4,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=5,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=6,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=7,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=8,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=9,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=2,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=3,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=4,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=5,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=6,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=7,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=8,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=9,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q5_0,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q5_0,type_b=f32,m=16,n=2,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q5_0,type_b=f32,m=16,n=3,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q5_0,type_b=f32,m=16,n=4,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q5_0,type_b=f32,m=16,n=5,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q5_0,type_b=f32,m=16,n=6,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q5_0,type_b=f32,m=16,n=7,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q5_0,type_b=f32,m=16,n=8,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q5_0,type_b=f32,m=16,n=9,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q5_1,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q5_1,type_b=f32,m=16,n=2,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q5_1,type_b=f32,m=16,n=3,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q5_1,type_b=f32,m=16,n=4,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q5_1,type_b=f32,m=16,n=5,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q5_1,type_b=f32,m=16,n=6,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q5_1,type_b=f32,m=16,n=7,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q5_1,type_b=f32,m=16,n=8,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q5_1,type_b=f32,m=16,n=9,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=2,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=3,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=4,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=5,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=6,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=7,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=8,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=9,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q2_K,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q2_K,type_b=f32,m=16,n=2,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q2_K,type_b=f32,m=16,n=3,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q2_K,type_b=f32,m=16,n=4,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q2_K,type_b=f32,m=16,n=5,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q2_K,type_b=f32,m=16,n=6,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q2_K,type_b=f32,m=16,n=7,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q2_K,type_b=f32,m=16,n=8,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q2_K,type_b=f32,m=16,n=9,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q3_K,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q3_K,type_b=f32,m=16,n=2,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q3_K,type_b=f32,m=16,n=3,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q3_K,type_b=f32,m=16,n=4,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q3_K,type_b=f32,m=16,n=5,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q3_K,type_b=f32,m=16,n=6,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q3_K,type_b=f32,m=16,n=7,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q3_K,type_b=f32,m=16,n=8,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q3_K,type_b=f32,m=16,n=9,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=2,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=3,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=4,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=5,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=6,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=7,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=8,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=9,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q5_K,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q5_K,type_b=f32,m=16,n=2,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q5_K,type_b=f32,m=16,n=3,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q5_K,type_b=f32,m=16,n=4,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q5_K,type_b=f32,m=16,n=5,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q5_K,type_b=f32,m=16,n=6,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q5_K,type_b=f32,m=16,n=7,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q5_K,type_b=f32,m=16,n=8,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q5_K,type_b=f32,m=16,n=9,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q6_K,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q6_K,type_b=f32,m=16,n=2,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q6_K,type_b=f32,m=16,n=3,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q6_K,type_b=f32,m=16,n=4,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q6_K,type_b=f32,m=16,n=5,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q6_K,type_b=f32,m=16,n=6,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q6_K,type_b=f32,m=16,n=7,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q6_K,type_b=f32,m=16,n=8,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q6_K,type_b=f32,m=16,n=9,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=2,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=3,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=4,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=5,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=6,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=7,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=8,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=9,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xs,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xs,type_b=f32,m=16,n=2,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xs,type_b=f32,m=16,n=3,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xs,type_b=f32,m=16,n=4,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xs,type_b=f32,m=16,n=5,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xs,type_b=f32,m=16,n=6,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xs,type_b=f32,m=16,n=7,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xs,type_b=f32,m=16,n=8,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xs,type_b=f32,m=16,n=9,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq2_s,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq2_s,type_b=f32,m=16,n=2,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq2_s,type_b=f32,m=16,n=3,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq2_s,type_b=f32,m=16,n=4,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq2_s,type_b=f32,m=16,n=5,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq2_s,type_b=f32,m=16,n=6,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq2_s,type_b=f32,m=16,n=7,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq2_s,type_b=f32,m=16,n=8,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq2_s,type_b=f32,m=16,n=9,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq3_xxs,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq3_xxs,type_b=f32,m=16,n=2,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq3_xxs,type_b=f32,m=16,n=3,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq3_xxs,type_b=f32,m=16,n=4,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq3_xxs,type_b=f32,m=16,n=5,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq3_xxs,type_b=f32,m=16,n=6,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq3_xxs,type_b=f32,m=16,n=7,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq3_xxs,type_b=f32,m=16,n=8,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq3_xxs,type_b=f32,m=16,n=9,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq1_s,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq1_s,type_b=f32,m=16,n=2,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq1_s,type_b=f32,m=16,n=3,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq1_s,type_b=f32,m=16,n=4,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq1_s,type_b=f32,m=16,n=5,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq1_s,type_b=f32,m=16,n=6,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq1_s,type_b=f32,m=16,n=7,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq1_s,type_b=f32,m=16,n=8,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq1_s,type_b=f32,m=16,n=9,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq1_m,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq1_m,type_b=f32,m=16,n=2,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq1_m,type_b=f32,m=16,n=3,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq1_m,type_b=f32,m=16,n=4,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq1_m,type_b=f32,m=16,n=5,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq1_m,type_b=f32,m=16,n=6,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq1_m,type_b=f32,m=16,n=7,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq1_m,type_b=f32,m=16,n=8,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq1_m,type_b=f32,m=16,n=9,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq4_nl,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq4_nl,type_b=f32,m=16,n=2,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq4_nl,type_b=f32,m=16,n=3,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq4_nl,type_b=f32,m=16,n=4,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq4_nl,type_b=f32,m=16,n=5,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq4_nl,type_b=f32,m=16,n=6,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq4_nl,type_b=f32,m=16,n=7,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq4_nl,type_b=f32,m=16,n=8,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq4_nl,type_b=f32,m=16,n=9,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq3_s,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq3_s,type_b=f32,m=16,n=2,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq3_s,type_b=f32,m=16,n=3,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq3_s,type_b=f32,m=16,n=4,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq3_s,type_b=f32,m=16,n=5,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq3_s,type_b=f32,m=16,n=6,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq3_s,type_b=f32,m=16,n=7,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq3_s,type_b=f32,m=16,n=8,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq3_s,type_b=f32,m=16,n=9,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq4_xs,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq4_xs,type_b=f32,m=16,n=2,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq4_xs,type_b=f32,m=16,n=3,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq4_xs,type_b=f32,m=16,n=4,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq4_xs,type_b=f32,m=16,n=5,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq4_xs,type_b=f32,m=16,n=6,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq4_xs,type_b=f32,m=16,n=7,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq4_xs,type_b=f32,m=16,n=8,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq4_xs,type_b=f32,m=16,n=9,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=1,k=256,bs=[3,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=1,k=256,bs=[3,1],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=1,k=256,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=1,k=256,bs=[3,2],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=1,k=256,bs=[3,2],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=1,k=256,bs=[3,2],nr=[2,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=16,k=256,bs=[3,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=16,k=256,bs=[3,1],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=16,k=256,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=16,k=256,bs=[3,2],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=16,k=256,bs=[3,2],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=16,k=256,bs=[3,2],nr=[2,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=1,k=256,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=1,k=256,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=1,k=256,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=8,k=256,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=8,k=256,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=8,k=256,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=16,k=256,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=16,k=256,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=16,k=256,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=1,k=4,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=1,k=4,bs=[1,1],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=1,k=4,bs=[1,1],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=1,k=4,bs=[3,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=1,k=4,bs=[3,1],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=1,k=4,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=1,k=4,bs=[3,2],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=1,k=4,bs=[3,2],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=1,k=4,bs=[3,2],nr=[2,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=16,k=4,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=16,k=4,bs=[1,1],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=16,k=4,bs=[1,1],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=16,k=4,bs=[3,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=16,k=4,bs=[3,1],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=16,k=4,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=16,k=4,bs=[3,2],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=16,k=4,bs=[3,2],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=16,k=4,bs=[3,2],nr=[2,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=1,k=4,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=1,k=4,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=1,k=4,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=8,k=4,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=8,k=4,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=8,k=4,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=16,k=4,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=16,k=4,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=16,k=4,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=1,k=1024,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=8,k=1024,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=16,n=16,k=1024,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[2,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=1,k=256,bs=[3,1],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=1,k=256,bs=[3,1],nr=[2,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=1,k=256,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=1,k=256,bs=[3,2],nr=[2,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=1,k=256,bs=[3,2],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=1,k=256,bs=[3,2],nr=[2,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[2,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=16,k=256,bs=[3,1],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=16,k=256,bs=[3,1],nr=[2,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=16,k=256,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=16,k=256,bs=[3,2],nr=[2,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=16,k=256,bs=[3,2],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=16,k=256,bs=[3,2],nr=[2,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=1,k=256,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=1,k=256,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=1,k=256,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=8,k=256,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=8,k=256,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=8,k=256,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=16,k=256,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=16,k=256,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=16,k=256,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=1,k=4,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=1,k=4,bs=[1,1],nr=[2,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=1,k=4,bs=[1,1],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=1,k=4,bs=[3,1],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=1,k=4,bs=[3,1],nr=[2,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=1,k=4,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=1,k=4,bs=[3,2],nr=[2,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=1,k=4,bs=[3,2],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=1,k=4,bs=[3,2],nr=[2,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=16,k=4,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=16,k=4,bs=[1,1],nr=[2,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=16,k=4,bs=[1,1],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=16,k=4,bs=[3,1],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=16,k=4,bs=[3,1],nr=[2,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=16,k=4,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=16,k=4,bs=[3,2],nr=[2,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=16,k=4,bs=[3,2],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=16,k=4,bs=[3,2],nr=[2,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=1,k=4,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=1,k=4,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=1,k=4,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=8,k=4,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=8,k=4,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=8,k=4,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=16,k=4,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=16,k=4,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=16,k=4,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=1,k=1024,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=8,k=1024,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f16,m=16,n=16,k=1024,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=1,k=256,bs=[3,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=1,k=256,bs=[3,1],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=1,k=256,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=1,k=256,bs=[3,2],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=1,k=256,bs=[3,2],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=1,k=256,bs=[3,2],nr=[2,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=16,k=256,bs=[3,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=16,k=256,bs=[3,1],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=16,k=256,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=16,k=256,bs=[3,2],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=16,k=256,bs=[3,2],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=16,k=256,bs=[3,2],nr=[2,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=1,k=256,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=1,k=256,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=1,k=256,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=8,k=256,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=8,k=256,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=8,k=256,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=16,k=256,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=16,k=256,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=16,k=256,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=1,k=4,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=1,k=4,bs=[1,1],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=1,k=4,bs=[1,1],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=1,k=4,bs=[3,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=1,k=4,bs=[3,1],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=1,k=4,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=1,k=4,bs=[3,2],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=1,k=4,bs=[3,2],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=1,k=4,bs=[3,2],nr=[2,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=16,k=4,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=16,k=4,bs=[1,1],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=16,k=4,bs=[1,1],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=16,k=4,bs=[3,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=16,k=4,bs=[3,1],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=16,k=4,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=16,k=4,bs=[3,2],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=16,k=4,bs=[3,2],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=16,k=4,bs=[3,2],nr=[2,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=1,k=4,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=1,k=4,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=1,k=4,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=8,k=4,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=8,k=4,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=8,k=4,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=16,k=4,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=16,k=4,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=16,k=4,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=1,k=1024,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=8,k=1024,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=16,n=16,k=1024,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=1,k=256,bs=[3,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=1,k=256,bs=[3,1],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=1,k=256,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=1,k=256,bs=[3,2],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=1,k=256,bs=[3,2],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=1,k=256,bs=[3,2],nr=[2,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=16,k=256,bs=[3,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=16,k=256,bs=[3,1],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=16,k=256,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=16,k=256,bs=[3,2],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=16,k=256,bs=[3,2],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=16,k=256,bs=[3,2],nr=[2,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=1,k=256,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=1,k=256,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=1,k=256,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=8,k=256,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=8,k=256,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=8,k=256,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=16,k=256,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=16,k=256,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=16,k=256,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=1,k=4,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=1,k=4,bs=[1,1],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=1,k=4,bs=[1,1],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=1,k=4,bs=[3,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=1,k=4,bs=[3,1],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=1,k=4,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=1,k=4,bs=[3,2],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=1,k=4,bs=[3,2],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=1,k=4,bs=[3,2],nr=[2,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=16,k=4,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=16,k=4,bs=[1,1],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=16,k=4,bs=[1,1],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=16,k=4,bs=[3,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=16,k=4,bs=[3,1],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=16,k=4,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=16,k=4,bs=[3,2],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=16,k=4,bs=[3,2],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=16,k=4,bs=[3,2],nr=[2,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=1,k=4,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=1,k=4,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=1,k=4,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=8,k=4,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=8,k=4,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=8,k=4,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=16,k=4,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=16,k=4,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=16,k=4,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=1,k=1024,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=8,k=1024,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f16,m=16,n=16,k=1024,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=1,k=256,bs=[3,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=1,k=256,bs=[3,1],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=1,k=256,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=1,k=256,bs=[3,2],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=1,k=256,bs=[3,2],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=1,k=256,bs=[3,2],nr=[2,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=16,k=256,bs=[3,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=16,k=256,bs=[3,1],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=16,k=256,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=16,k=256,bs=[3,2],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=16,k=256,bs=[3,2],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=16,k=256,bs=[3,2],nr=[2,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=1,k=256,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=1,k=256,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=1,k=256,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=8,k=256,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=8,k=256,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=8,k=256,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=16,k=256,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=16,k=256,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=16,k=256,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=1,k=1024,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=8,k=1024,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=16,k=1024,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[2,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=1,k=256,bs=[3,1],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=1,k=256,bs=[3,1],nr=[2,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=1,k=256,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=1,k=256,bs=[3,2],nr=[2,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=1,k=256,bs=[3,2],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=1,k=256,bs=[3,2],nr=[2,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[2,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=16,k=256,bs=[3,1],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=16,k=256,bs=[3,1],nr=[2,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=16,k=256,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=16,k=256,bs=[3,2],nr=[2,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=16,k=256,bs=[3,2],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=16,k=256,bs=[3,2],nr=[2,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=1,k=256,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=1,k=256,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=1,k=256,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=8,k=256,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=8,k=256,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=8,k=256,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=16,k=256,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=16,k=256,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=16,k=256,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=1,k=1024,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=8,k=1024,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q8_0,type_b=f16,m=16,n=16,k=1024,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=1,k=256,bs=[3,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=1,k=256,bs=[3,1],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=1,k=256,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=1,k=256,bs=[3,2],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=1,k=256,bs=[3,2],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=1,k=256,bs=[3,2],nr=[2,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=16,k=256,bs=[3,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=16,k=256,bs=[3,1],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=16,k=256,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=16,k=256,bs=[3,2],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=16,k=256,bs=[3,2],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=16,k=256,bs=[3,2],nr=[2,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=1,k=256,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=1,k=256,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=1,k=256,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=8,k=256,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=8,k=256,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=8,k=256,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=16,k=256,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=16,k=256,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=16,k=256,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=1,k=1024,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=8,k=1024,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f32,m=16,n=16,k=1024,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[2,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=1,k=256,bs=[3,1],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=1,k=256,bs=[3,1],nr=[2,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=1,k=256,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=1,k=256,bs=[3,2],nr=[2,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=1,k=256,bs=[3,2],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=1,k=256,bs=[3,2],nr=[2,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[2,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=16,k=256,bs=[3,1],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=16,k=256,bs=[3,1],nr=[2,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=16,k=256,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=16,k=256,bs=[3,2],nr=[2,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=16,k=256,bs=[3,2],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=16,k=256,bs=[3,2],nr=[2,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=1,k=256,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=1,k=256,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=1,k=256,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=8,k=256,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=8,k=256,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=8,k=256,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=16,k=256,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=16,k=256,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=16,k=256,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=1,k=1024,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=8,k=1024,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_0,type_b=f16,m=16,n=16,k=1024,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=1,k=256,bs=[3,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=1,k=256,bs=[3,1],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=1,k=256,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=1,k=256,bs=[3,2],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=1,k=256,bs=[3,2],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=1,k=256,bs=[3,2],nr=[2,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=16,k=256,bs=[3,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=16,k=256,bs=[3,1],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=16,k=256,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=16,k=256,bs=[3,2],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=16,k=256,bs=[3,2],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=16,k=256,bs=[3,2],nr=[2,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=1,k=256,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=1,k=256,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=1,k=256,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=8,k=256,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=8,k=256,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=8,k=256,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=16,k=256,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=16,k=256,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=16,k=256,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=1,k=1024,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=8,k=1024,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=16,k=1024,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[2,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=1,k=256,bs=[3,1],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=1,k=256,bs=[3,1],nr=[2,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=1,k=256,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=1,k=256,bs=[3,2],nr=[2,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=1,k=256,bs=[3,2],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=1,k=256,bs=[3,2],nr=[2,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[2,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=16,k=256,bs=[3,1],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=16,k=256,bs=[3,1],nr=[2,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=16,k=256,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=16,k=256,bs=[3,2],nr=[2,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=16,k=256,bs=[3,2],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=16,k=256,bs=[3,2],nr=[2,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=1,k=256,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=1,k=256,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=1,k=256,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=8,k=256,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=8,k=256,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=8,k=256,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=16,k=256,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=16,k=256,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=16,k=256,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=1,k=1024,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=8,k=1024,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_1,type_b=f16,m=16,n=16,k=1024,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=1,k=256,bs=[3,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=1,k=256,bs=[3,1],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=1,k=256,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=1,k=256,bs=[3,2],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=1,k=256,bs=[3,2],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=1,k=256,bs=[3,2],nr=[2,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=16,k=256,bs=[3,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=16,k=256,bs=[3,1],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=16,k=256,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=16,k=256,bs=[3,2],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=16,k=256,bs=[3,2],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=16,k=256,bs=[3,2],nr=[2,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=1,k=256,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=1,k=256,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=1,k=256,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=8,k=256,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=8,k=256,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=8,k=256,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=16,k=256,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=16,k=256,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=16,k=256,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=1,k=1024,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=8,k=1024,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f32,m=16,n=16,k=1024,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[2,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=1,k=256,bs=[3,1],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=1,k=256,bs=[3,1],nr=[2,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=1,k=256,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=1,k=256,bs=[3,2],nr=[2,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=1,k=256,bs=[3,2],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=1,k=256,bs=[3,2],nr=[2,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[2,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=16,k=256,bs=[3,1],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=16,k=256,bs=[3,1],nr=[2,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=16,k=256,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=16,k=256,bs=[3,2],nr=[2,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=16,k=256,bs=[3,2],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=16,k=256,bs=[3,2],nr=[2,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=1,k=256,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=1,k=256,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=1,k=256,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=8,k=256,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=8,k=256,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=8,k=256,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=16,k=256,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=16,k=256,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=16,k=256,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=1,k=1024,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=8,k=1024,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_K,type_b=f16,m=16,n=16,k=1024,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[2,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=1,k=256,bs=[3,1],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=1,k=256,bs=[3,1],nr=[2,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=1,k=256,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=1,k=256,bs=[3,2],nr=[2,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=1,k=256,bs=[3,2],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=1,k=256,bs=[3,2],nr=[2,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=16,k=256,bs=[1,1],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=16,k=256,bs=[3,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=16,k=256,bs=[3,1],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=16,k=256,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=16,k=256,bs=[3,2],nr=[2,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=16,k=256,bs=[3,2],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=16,k=256,bs=[3,2],nr=[2,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=1,k=256,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=1,k=256,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=1,k=256,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=8,k=256,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=8,k=256,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=8,k=256,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=16,k=256,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=16,k=256,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=16,k=256,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=1,k=1024,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=8,k=1024,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xxs,type_b=f32,m=16,n=16,k=1024,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[2,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=1,k=256,bs=[1,1],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=1,k=256,bs=[3,1],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=1,k=256,bs=[3,1],nr=[2,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=1,k=256,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=1,k=256,bs=[3,2],nr=[2,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=1,k=256,bs=[3,2],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=1,k=256,bs=[3,2],nr=[2,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[2,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=16,k=256,bs=[1,1],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=16,k=256,bs=[3,1],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=16,k=256,bs=[3,1],nr=[2,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=16,k=256,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=16,k=256,bs=[3,2],nr=[2,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=16,k=256,bs=[3,2],nr=[1,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=16,k=256,bs=[3,2],nr=[2,2],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=1,k=256,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=1,k=256,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=1,k=256,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=8,k=256,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=8,k=256,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=8,k=256,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=16,k=256,bs=[2,3],nr=[1,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=16,k=256,bs=[2,3],nr=[1,1],per=[0,1,3,2],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=16,k=256,bs=[2,3],nr=[1,1],per=[0,3,2,1],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=1,k=1024,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=8,k=1024,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=iq2_xxs,type_b=f16,m=16,n=16,k=1024,bs=[3,2],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=1,k=32,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q4_1,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q5_0,type_b=f32,m=16,n=1,k=32,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q5_0,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q5_1,type_b=f32,m=16,n=1,k=32,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q5_1,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=1,k=32,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q8_0,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q2_K,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q3_K,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q5_K,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=q6_K,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq2_xs,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq2_s,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq3_xxs,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq1_s,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq1_m,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq4_nl,type_b=f32,m=16,n=1,k=32,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq4_nl,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq3_s,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=iq4_xs,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=bf16,type_b=f32,m=16,n=1,k=1,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=bf16,type_b=f32,m=16,n=1,k=256,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=f16,type_b=f32,m=64,n=2,k=128,bs=[8,1],nr=[1,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=83,n=2,k=128,bs=[8,1],nr=[4,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=64,n=2,k=64,bs=[8,1],nr=[4,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=83,n=2,k=64,bs=[8,1],nr=[4,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=64,n=45,k=128,bs=[8,1],nr=[4,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=128,n=45,k=64,bs=[8,1],nr=[4,1],per=[0,1,2,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=1056,n=1,k=193,bs=[1,1],nr=[4,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=1056,n=1,k=67,bs=[1,1],nr=[4,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=1056,n=1,k=128,bs=[1,1],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=128,n=1,k=1056,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=bf16,type_b=f32,m=1056,n=1,k=128,bs=[1,1],nr=[1,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=bf16,type_b=f32,m=128,n=1,k=1056,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=1): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=1056,n=1,k=128,bs=[1,1],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=128,n=1,k=1056,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=1056,n=1,k=129,bs=[1,1],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=128,n=1,k=1057,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=bf16,type_b=f32,m=1056,n=1,k=129,bs=[1,1],nr=[1,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=bf16,type_b=f32,m=128,n=1,k=1057,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=1): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=1056,n=1,k=129,bs=[1,1],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=128,n=1,k=1057,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=1057,n=1,k=128,bs=[1,1],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=129,n=1,k=1056,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=bf16,type_b=f32,m=1057,n=1,k=128,bs=[1,1],nr=[1,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=bf16,type_b=f32,m=129,n=1,k=1056,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=1): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=1057,n=1,k=128,bs=[1,1],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=129,n=1,k=1056,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=1057,n=1,k=129,bs=[1,1],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=129,n=1,k=1057,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=bf16,type_b=f32,m=1057,n=1,k=129,bs=[1,1],nr=[1,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=bf16,type_b=f32,m=129,n=1,k=1057,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=1): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=1057,n=1,k=129,bs=[1,1],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=129,n=1,k=1057,bs=[1,1],nr=[1,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=1056,n=1,k=128,bs=[1,1],nr=[4,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=128,n=1,k=1056,bs=[1,1],nr=[4,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=bf16,type_b=f32,m=1056,n=1,k=128,bs=[1,1],nr=[4,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=bf16,type_b=f32,m=128,n=1,k=1056,bs=[1,1],nr=[4,1],per=[0,1,2,3],v=1): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=1056,n=1,k=128,bs=[1,1],nr=[4,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=128,n=1,k=1056,bs=[1,1],nr=[4,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=1056,n=1,k=129,bs=[1,1],nr=[4,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=128,n=1,k=1057,bs=[1,1],nr=[4,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=bf16,type_b=f32,m=1056,n=1,k=129,bs=[1,1],nr=[4,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=bf16,type_b=f32,m=128,n=1,k=1057,bs=[1,1],nr=[4,1],per=[0,1,2,3],v=1): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=1056,n=1,k=129,bs=[1,1],nr=[4,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=128,n=1,k=1057,bs=[1,1],nr=[4,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=1057,n=1,k=128,bs=[1,1],nr=[4,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=129,n=1,k=1056,bs=[1,1],nr=[4,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=bf16,type_b=f32,m=1057,n=1,k=128,bs=[1,1],nr=[4,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=bf16,type_b=f32,m=129,n=1,k=1056,bs=[1,1],nr=[4,1],per=[0,1,2,3],v=1): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=1057,n=1,k=128,bs=[1,1],nr=[4,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=129,n=1,k=1056,bs=[1,1],nr=[4,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=1057,n=1,k=129,bs=[1,1],nr=[4,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=129,n=1,k=1057,bs=[1,1],nr=[4,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=bf16,type_b=f32,m=1057,n=1,k=129,bs=[1,1],nr=[4,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=bf16,type_b=f32,m=129,n=1,k=1057,bs=[1,1],nr=[4,1],per=[0,1,2,3],v=1): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=1057,n=1,k=129,bs=[1,1],nr=[4,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=129,n=1,k=1057,bs=[1,1],nr=[4,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=1056,n=1,k=128,bs=[2,1],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=128,n=1,k=1056,bs=[2,1],nr=[1,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=bf16,type_b=f32,m=1056,n=1,k=128,bs=[2,1],nr=[1,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=bf16,type_b=f32,m=128,n=1,k=1056,bs=[2,1],nr=[1,1],per=[0,1,2,3],v=1): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=1056,n=1,k=128,bs=[2,1],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=128,n=1,k=1056,bs=[2,1],nr=[1,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=1056,n=1,k=129,bs=[2,1],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=128,n=1,k=1057,bs=[2,1],nr=[1,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=bf16,type_b=f32,m=1056,n=1,k=129,bs=[2,1],nr=[1,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=bf16,type_b=f32,m=128,n=1,k=1057,bs=[2,1],nr=[1,1],per=[0,1,2,3],v=1): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=1056,n=1,k=129,bs=[2,1],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=128,n=1,k=1057,bs=[2,1],nr=[1,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=1057,n=1,k=128,bs=[2,1],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=129,n=1,k=1056,bs=[2,1],nr=[1,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=bf16,type_b=f32,m=1057,n=1,k=128,bs=[2,1],nr=[1,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=bf16,type_b=f32,m=129,n=1,k=1056,bs=[2,1],nr=[1,1],per=[0,1,2,3],v=1): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=1057,n=1,k=128,bs=[2,1],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=129,n=1,k=1056,bs=[2,1],nr=[1,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=1057,n=1,k=129,bs=[2,1],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=129,n=1,k=1057,bs=[2,1],nr=[1,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=bf16,type_b=f32,m=1057,n=1,k=129,bs=[2,1],nr=[1,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=bf16,type_b=f32,m=129,n=1,k=1057,bs=[2,1],nr=[1,1],per=[0,1,2,3],v=1): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=1057,n=1,k=129,bs=[2,1],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=129,n=1,k=1057,bs=[2,1],nr=[1,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=1056,n=1,k=128,bs=[2,1],nr=[4,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=128,n=1,k=1056,bs=[2,1],nr=[4,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=bf16,type_b=f32,m=1056,n=1,k=128,bs=[2,1],nr=[4,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=bf16,type_b=f32,m=128,n=1,k=1056,bs=[2,1],nr=[4,1],per=[0,1,2,3],v=1): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=1056,n=1,k=128,bs=[2,1],nr=[4,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=128,n=1,k=1056,bs=[2,1],nr=[4,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=1056,n=1,k=129,bs=[2,1],nr=[4,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=128,n=1,k=1057,bs=[2,1],nr=[4,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=bf16,type_b=f32,m=1056,n=1,k=129,bs=[2,1],nr=[4,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=bf16,type_b=f32,m=128,n=1,k=1057,bs=[2,1],nr=[4,1],per=[0,1,2,3],v=1): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=1056,n=1,k=129,bs=[2,1],nr=[4,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=128,n=1,k=1057,bs=[2,1],nr=[4,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=1057,n=1,k=128,bs=[2,1],nr=[4,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=129,n=1,k=1056,bs=[2,1],nr=[4,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=bf16,type_b=f32,m=1057,n=1,k=128,bs=[2,1],nr=[4,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=bf16,type_b=f32,m=129,n=1,k=1056,bs=[2,1],nr=[4,1],per=[0,1,2,3],v=1): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=1057,n=1,k=128,bs=[2,1],nr=[4,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=129,n=1,k=1056,bs=[2,1],nr=[4,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=1057,n=1,k=129,bs=[2,1],nr=[4,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=129,n=1,k=1057,bs=[2,1],nr=[4,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=bf16,type_b=f32,m=1057,n=1,k=129,bs=[2,1],nr=[4,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=bf16,type_b=f32,m=129,n=1,k=1057,bs=[2,1],nr=[4,1],per=[0,1,2,3],v=1): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=1057,n=1,k=129,bs=[2,1],nr=[4,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=129,n=1,k=1057,bs=[2,1],nr=[4,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=1056,n=1,k=128,bs=[4,1],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=128,n=1,k=1056,bs=[4,1],nr=[1,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=bf16,type_b=f32,m=1056,n=1,k=128,bs=[4,1],nr=[1,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=bf16,type_b=f32,m=128,n=1,k=1056,bs=[4,1],nr=[1,1],per=[0,1,2,3],v=1): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=1056,n=1,k=128,bs=[4,1],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=128,n=1,k=1056,bs=[4,1],nr=[1,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=1056,n=1,k=129,bs=[4,1],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=128,n=1,k=1057,bs=[4,1],nr=[1,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=bf16,type_b=f32,m=1056,n=1,k=129,bs=[4,1],nr=[1,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=bf16,type_b=f32,m=128,n=1,k=1057,bs=[4,1],nr=[1,1],per=[0,1,2,3],v=1): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=1056,n=1,k=129,bs=[4,1],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=128,n=1,k=1057,bs=[4,1],nr=[1,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=1057,n=1,k=128,bs=[4,1],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=129,n=1,k=1056,bs=[4,1],nr=[1,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=bf16,type_b=f32,m=1057,n=1,k=128,bs=[4,1],nr=[1,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=bf16,type_b=f32,m=129,n=1,k=1056,bs=[4,1],nr=[1,1],per=[0,1,2,3],v=1): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=1057,n=1,k=128,bs=[4,1],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=129,n=1,k=1056,bs=[4,1],nr=[1,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=1057,n=1,k=129,bs=[4,1],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=129,n=1,k=1057,bs=[4,1],nr=[1,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=bf16,type_b=f32,m=1057,n=1,k=129,bs=[4,1],nr=[1,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=bf16,type_b=f32,m=129,n=1,k=1057,bs=[4,1],nr=[1,1],per=[0,1,2,3],v=1): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=1057,n=1,k=129,bs=[4,1],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=129,n=1,k=1057,bs=[4,1],nr=[1,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=1056,n=1,k=128,bs=[4,1],nr=[4,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=128,n=1,k=1056,bs=[4,1],nr=[4,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=bf16,type_b=f32,m=1056,n=1,k=128,bs=[4,1],nr=[4,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=bf16,type_b=f32,m=128,n=1,k=1056,bs=[4,1],nr=[4,1],per=[0,1,2,3],v=1): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=1056,n=1,k=128,bs=[4,1],nr=[4,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=128,n=1,k=1056,bs=[4,1],nr=[4,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=1056,n=1,k=129,bs=[4,1],nr=[4,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=128,n=1,k=1057,bs=[4,1],nr=[4,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=bf16,type_b=f32,m=1056,n=1,k=129,bs=[4,1],nr=[4,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=bf16,type_b=f32,m=128,n=1,k=1057,bs=[4,1],nr=[4,1],per=[0,1,2,3],v=1): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=1056,n=1,k=129,bs=[4,1],nr=[4,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=128,n=1,k=1057,bs=[4,1],nr=[4,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=1057,n=1,k=128,bs=[4,1],nr=[4,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=129,n=1,k=1056,bs=[4,1],nr=[4,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=bf16,type_b=f32,m=1057,n=1,k=128,bs=[4,1],nr=[4,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=bf16,type_b=f32,m=129,n=1,k=1056,bs=[4,1],nr=[4,1],per=[0,1,2,3],v=1): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=1057,n=1,k=128,bs=[4,1],nr=[4,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=129,n=1,k=1056,bs=[4,1],nr=[4,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=1057,n=1,k=129,bs=[4,1],nr=[4,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=129,n=1,k=1057,bs=[4,1],nr=[4,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=bf16,type_b=f32,m=1057,n=1,k=129,bs=[4,1],nr=[4,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=bf16,type_b=f32,m=129,n=1,k=1057,bs=[4,1],nr=[4,1],per=[0,1,2,3],v=1): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=1057,n=1,k=129,bs=[4,1],nr=[4,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=129,n=1,k=1057,bs=[4,1],nr=[4,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=1056,n=1,k=128,bs=[8,1],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=128,n=1,k=1056,bs=[8,1],nr=[1,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=bf16,type_b=f32,m=1056,n=1,k=128,bs=[8,1],nr=[1,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=bf16,type_b=f32,m=128,n=1,k=1056,bs=[8,1],nr=[1,1],per=[0,1,2,3],v=1): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=1056,n=1,k=128,bs=[8,1],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=128,n=1,k=1056,bs=[8,1],nr=[1,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=1056,n=1,k=129,bs=[8,1],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=128,n=1,k=1057,bs=[8,1],nr=[1,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=bf16,type_b=f32,m=1056,n=1,k=129,bs=[8,1],nr=[1,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=bf16,type_b=f32,m=128,n=1,k=1057,bs=[8,1],nr=[1,1],per=[0,1,2,3],v=1): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=1056,n=1,k=129,bs=[8,1],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=128,n=1,k=1057,bs=[8,1],nr=[1,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=1057,n=1,k=128,bs=[8,1],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=129,n=1,k=1056,bs=[8,1],nr=[1,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=bf16,type_b=f32,m=1057,n=1,k=128,bs=[8,1],nr=[1,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=bf16,type_b=f32,m=129,n=1,k=1056,bs=[8,1],nr=[1,1],per=[0,1,2,3],v=1): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=1057,n=1,k=128,bs=[8,1],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=129,n=1,k=1056,bs=[8,1],nr=[1,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=1057,n=1,k=129,bs=[8,1],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=129,n=1,k=1057,bs=[8,1],nr=[1,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=bf16,type_b=f32,m=1057,n=1,k=129,bs=[8,1],nr=[1,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=bf16,type_b=f32,m=129,n=1,k=1057,bs=[8,1],nr=[1,1],per=[0,1,2,3],v=1): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=1057,n=1,k=129,bs=[8,1],nr=[1,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=129,n=1,k=1057,bs=[8,1],nr=[1,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=1056,n=1,k=128,bs=[8,1],nr=[4,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=128,n=1,k=1056,bs=[8,1],nr=[4,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=bf16,type_b=f32,m=1056,n=1,k=128,bs=[8,1],nr=[4,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=bf16,type_b=f32,m=128,n=1,k=1056,bs=[8,1],nr=[4,1],per=[0,1,2,3],v=1): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=1056,n=1,k=128,bs=[8,1],nr=[4,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=128,n=1,k=1056,bs=[8,1],nr=[4,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=1056,n=1,k=129,bs=[8,1],nr=[4,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=128,n=1,k=1057,bs=[8,1],nr=[4,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=bf16,type_b=f32,m=1056,n=1,k=129,bs=[8,1],nr=[4,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=bf16,type_b=f32,m=128,n=1,k=1057,bs=[8,1],nr=[4,1],per=[0,1,2,3],v=1): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=1056,n=1,k=129,bs=[8,1],nr=[4,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=128,n=1,k=1057,bs=[8,1],nr=[4,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=1057,n=1,k=128,bs=[8,1],nr=[4,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=129,n=1,k=1056,bs=[8,1],nr=[4,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=bf16,type_b=f32,m=1057,n=1,k=128,bs=[8,1],nr=[4,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=bf16,type_b=f32,m=129,n=1,k=1056,bs=[8,1],nr=[4,1],per=[0,1,2,3],v=1): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=1057,n=1,k=128,bs=[8,1],nr=[4,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=129,n=1,k=1056,bs=[8,1],nr=[4,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=1057,n=1,k=129,bs=[8,1],nr=[4,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f16,type_b=f32,m=129,n=1,k=1057,bs=[8,1],nr=[4,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT(type_a=bf16,type_b=f32,m=1057,n=1,k=129,bs=[8,1],nr=[4,1],per=[0,2,1,3],v=0): not supported [SYCL0] 
  MUL_MAT(type_a=bf16,type_b=f32,m=129,n=1,k=1057,bs=[8,1],nr=[4,1],per=[0,1,2,3],v=1): not supported [SYCL0] 
  MUL_MAT(type_a=f32,type_b=f32,m=1057,n=1,k=129,bs=[8,1],nr=[4,1],per=[0,2,1,3],v=0): [1;32mOK[0m
  MUL_MAT(type_a=f32,type_b=f32,m=129,n=1,k=1057,bs=[8,1],nr=[4,1],per=[0,1,2,3],v=1): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=16,n_used=16,b=0,m=32,n=1024,k=16): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=16,n_used=16,b=1,m=32,n=1024,k=16): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=4,n_used=1,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=4,n_used=1,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=4,n_used=1,b=0,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=4,n_used=1,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=4,n_used=1,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=4,n_used=1,b=1,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=4,n_used=2,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=4,n_used=2,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=4,n_used=2,b=1,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=4,n_used=4,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=4,n_used=4,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=4,n_used=4,b=0,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=4,n_used=4,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=4,n_used=4,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=4,n_used=4,b=1,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,n_used=1,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,n_used=1,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,n_used=1,b=0,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,n_used=1,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,n_used=1,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,n_used=1,b=1,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,n_used=2,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,n_used=2,b=0,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,n_used=2,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,n_used=2,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,n_used=2,b=1,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,n_used=4,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,n_used=4,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,n_used=4,b=0,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,n_used=4,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,n_used=4,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f32,type_b=f32,n_mats=8,n_used=4,b=1,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=4,n_used=1,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=4,n_used=1,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=4,n_used=1,b=0,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=4,n_used=1,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=4,n_used=1,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=4,n_used=1,b=1,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=4,n_used=2,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=4,n_used=2,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=4,n_used=2,b=1,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=4,n_used=4,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=4,n_used=4,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=4,n_used=4,b=0,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=4,n_used=4,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=4,n_used=4,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=4,n_used=4,b=1,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,n_used=1,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,n_used=1,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,n_used=1,b=0,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,n_used=1,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,n_used=1,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,n_used=1,b=1,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,n_used=2,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,n_used=2,b=0,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,n_used=2,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,n_used=2,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,n_used=2,b=1,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,n_used=4,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,n_used=4,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,n_used=4,b=0,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,n_used=4,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,n_used=4,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=f16,type_b=f32,n_mats=8,n_used=4,b=1,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=4,n_used=1,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=4,n_used=1,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=4,n_used=1,b=0,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=4,n_used=1,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=4,n_used=1,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=4,n_used=1,b=1,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=4,n_used=2,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=4,n_used=2,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=4,n_used=2,b=1,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=4,n_used=4,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=4,n_used=4,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=4,n_used=4,b=0,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=4,n_used=4,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=4,n_used=4,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=4,n_used=4,b=1,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=8,n_used=1,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=8,n_used=1,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=8,n_used=1,b=0,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=8,n_used=1,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=8,n_used=1,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=8,n_used=1,b=1,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=8,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=8,n_used=2,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=8,n_used=2,b=0,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=8,n_used=2,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=8,n_used=2,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=8,n_used=2,b=1,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=8,n_used=4,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=8,n_used=4,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=8,n_used=4,b=0,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=8,n_used=4,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=8,n_used=4,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=8,n_used=4,b=1,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=4,n_used=1,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=4,n_used=1,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=4,n_used=1,b=0,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=4,n_used=1,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=4,n_used=1,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=4,n_used=1,b=1,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=4,n_used=2,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=4,n_used=2,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=4,n_used=2,b=1,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=4,n_used=4,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=4,n_used=4,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=4,n_used=4,b=0,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=4,n_used=4,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=4,n_used=4,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=4,n_used=4,b=1,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,n_used=1,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,n_used=1,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,n_used=1,b=0,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,n_used=1,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,n_used=1,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,n_used=1,b=1,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,n_used=2,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,n_used=2,b=0,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,n_used=2,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,n_used=2,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,n_used=2,b=1,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,n_used=4,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,n_used=4,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,n_used=4,b=0,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,n_used=4,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,n_used=4,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_0,type_b=f32,n_mats=8,n_used=4,b=1,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=4,n_used=1,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=4,n_used=1,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=4,n_used=1,b=0,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=4,n_used=1,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=4,n_used=1,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=4,n_used=1,b=1,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=4,n_used=2,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=4,n_used=2,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=4,n_used=2,b=1,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=4,n_used=4,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=4,n_used=4,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=4,n_used=4,b=0,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=4,n_used=4,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=4,n_used=4,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=4,n_used=4,b=1,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=8,n_used=1,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=8,n_used=1,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=8,n_used=1,b=0,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=8,n_used=1,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=8,n_used=1,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=8,n_used=1,b=1,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=8,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=8,n_used=2,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=8,n_used=2,b=0,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=8,n_used=2,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=8,n_used=2,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=8,n_used=2,b=1,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=8,n_used=4,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=8,n_used=4,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=8,n_used=4,b=0,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=8,n_used=4,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=8,n_used=4,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=8,n_used=4,b=1,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=4,n_used=1,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=4,n_used=1,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=4,n_used=1,b=0,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=4,n_used=1,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=4,n_used=1,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=4,n_used=1,b=1,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=4,n_used=2,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=4,n_used=2,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=4,n_used=2,b=1,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=4,n_used=4,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=4,n_used=4,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=4,n_used=4,b=0,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=4,n_used=4,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=4,n_used=4,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=4,n_used=4,b=1,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,n_used=1,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,n_used=1,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,n_used=1,b=0,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,n_used=1,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,n_used=1,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,n_used=1,b=1,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,n_used=2,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,n_used=2,b=0,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,n_used=2,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,n_used=2,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,n_used=2,b=1,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,n_used=4,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,n_used=4,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,n_used=4,b=0,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,n_used=4,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,n_used=4,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_K,type_b=f32,n_mats=8,n_used=4,b=1,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=4,n_used=1,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=4,n_used=1,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=4,n_used=1,b=0,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=4,n_used=1,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=4,n_used=1,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=4,n_used=1,b=1,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=4,n_used=2,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=4,n_used=2,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=4,n_used=2,b=1,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=4,n_used=4,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=4,n_used=4,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=4,n_used=4,b=0,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=4,n_used=4,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=4,n_used=4,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=4,n_used=4,b=1,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,n_used=1,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,n_used=1,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,n_used=1,b=0,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,n_used=1,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,n_used=1,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,n_used=1,b=1,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,n_used=2,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,n_used=2,b=0,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,n_used=2,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,n_used=2,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,n_used=2,b=1,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,n_used=4,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,n_used=4,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,n_used=4,b=0,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,n_used=4,b=1,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,n_used=4,b=1,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xxs,type_b=f32,n_mats=8,n_used=4,b=1,m=512,n=129,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q4_1,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_0,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_0,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_1,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_1,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q8_0,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q2_K,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q2_K,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q3_K,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q3_K,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_K,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q5_K,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q6_K,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=q6_K,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xs,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_xs,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_s,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq2_s,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_xxs,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_xxs,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq1_s,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq1_s,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq1_m,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq1_m,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_nl,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_nl,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_s,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq3_s,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_xs,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=iq4_xs,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=32,k=256): [1;32mOK[0m
  MUL_MAT_ID(type_a=bf16,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=1,k=256): not supported [SYCL0] 
  MUL_MAT_ID(type_a=bf16,type_b=f32,n_mats=4,n_used=2,b=0,m=512,n=32,k=256): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=1,k=1,bs=[1,1],nr=[1,1],trans_b=0): [1;32mOK[0m
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=1,k=1,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=1,k=1,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=1,k=1,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=1,k=1,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=1,k=1,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=1,k=1,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=1,k=1,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=1,k=1,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=1,k=1,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=1,k=1,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=1,k=1,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=1,k=1,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=1,k=1,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=1,k=1,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=1,k=1,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=1,k=16,bs=[1,1],nr=[1,1],trans_b=0): [1;32mOK[0m
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=1,k=16,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=1,k=16,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=1,k=16,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=1,k=16,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=1,k=16,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=1,k=16,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=1,k=16,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=1,k=16,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=1,k=16,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=1,k=16,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=1,k=16,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=1,k=16,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=1,k=16,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=1,k=16,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=1,k=16,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=16,k=1,bs=[1,1],nr=[1,1],trans_b=0): [1;32mOK[0m
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=16,k=1,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=16,k=1,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=16,k=1,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=16,k=1,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=16,k=1,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=16,k=1,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=16,k=1,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=16,k=1,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=16,k=1,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=16,k=1,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=16,k=1,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=16,k=1,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=16,k=1,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=16,k=1,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=16,k=1,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=16,k=16,bs=[1,1],nr=[1,1],trans_b=0): [1;32mOK[0m
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=16,k=16,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=16,k=16,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=16,k=16,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=16,k=16,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=16,k=16,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=16,k=16,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=16,k=16,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=16,k=16,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=16,k=16,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=16,k=16,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=16,k=16,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=16,k=16,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=16,k=16,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=16,k=16,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f32,m=256,n=16,k=16,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=1,k=1,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=1,k=1,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=1,k=1,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=1,k=1,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=1,k=1,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=1,k=1,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=1,k=1,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=1,k=1,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=1,k=1,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=1,k=1,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=1,k=1,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=1,k=1,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=1,k=1,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=1,k=1,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=1,k=1,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=1,k=1,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=1,k=16,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=1,k=16,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=1,k=16,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=1,k=16,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=1,k=16,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=1,k=16,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=1,k=16,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=1,k=16,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=1,k=16,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=1,k=16,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=1,k=16,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=1,k=16,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=1,k=16,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=1,k=16,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=1,k=16,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=1,k=16,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=16,k=1,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=16,k=1,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=16,k=1,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=16,k=1,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=16,k=1,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=16,k=1,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=16,k=1,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=16,k=1,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=16,k=1,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=16,k=1,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=16,k=1,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=16,k=1,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=16,k=1,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=16,k=1,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=16,k=1,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=16,k=1,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=16,k=16,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=16,k=16,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=16,k=16,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=16,k=16,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=16,k=16,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=16,k=16,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=16,k=16,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=16,k=16,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=16,k=16,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=16,k=16,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=16,k=16,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=16,k=16,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=16,k=16,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=16,k=16,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=16,k=16,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f32,type_b=f16,m=256,n=16,k=16,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=1,k=1,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=1,k=1,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=1,k=1,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=1,k=1,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=1,k=1,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=1,k=1,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=1,k=1,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=1,k=1,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=1,k=1,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=1,k=1,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=1,k=1,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=1,k=1,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=1,k=1,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=1,k=1,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=1,k=1,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=1,k=1,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=1,k=16,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=1,k=16,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=1,k=16,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=1,k=16,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=1,k=16,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=1,k=16,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=1,k=16,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=1,k=16,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=1,k=16,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=1,k=16,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=1,k=16,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=1,k=16,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=1,k=16,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=1,k=16,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=1,k=16,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=1,k=16,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=16,k=1,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=16,k=1,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=16,k=1,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=16,k=1,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=16,k=1,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=16,k=1,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=16,k=1,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=16,k=1,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=16,k=1,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=16,k=1,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=16,k=1,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=16,k=1,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=16,k=1,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=16,k=1,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=16,k=1,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=16,k=1,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=16,k=16,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=16,k=16,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=16,k=16,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=16,k=16,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=16,k=16,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=16,k=16,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=16,k=16,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=16,k=16,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=16,k=16,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=16,k=16,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=16,k=16,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=16,k=16,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=16,k=16,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=16,k=16,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=16,k=16,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f32,m=256,n=16,k=16,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=1,k=1,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=1,k=1,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=1,k=1,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=1,k=1,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=1,k=1,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=1,k=1,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=1,k=1,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=1,k=1,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=1,k=1,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=1,k=1,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=1,k=1,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=1,k=1,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=1,k=1,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=1,k=1,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=1,k=1,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=1,k=1,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=1,k=16,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=1,k=16,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=1,k=16,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=1,k=16,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=1,k=16,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=1,k=16,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=1,k=16,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=1,k=16,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=1,k=16,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=1,k=16,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=1,k=16,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=1,k=16,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=1,k=16,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=1,k=16,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=1,k=16,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=1,k=16,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=16,k=1,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=16,k=1,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=16,k=1,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=16,k=1,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=16,k=1,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=16,k=1,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=16,k=1,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=16,k=1,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=16,k=1,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=16,k=1,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=16,k=1,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=16,k=1,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=16,k=1,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=16,k=1,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=16,k=1,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=16,k=1,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=16,k=16,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=16,k=16,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=16,k=16,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=16,k=16,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=16,k=16,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=16,k=16,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=16,k=16,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=16,k=16,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=16,k=16,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=16,k=16,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=16,k=16,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=16,k=16,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=16,k=16,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=16,k=16,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=16,k=16,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=f16,type_b=f16,m=256,n=16,k=16,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=1,k=1,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=1,k=1,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=1,k=1,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=1,k=1,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=1,k=1,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=1,k=1,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=1,k=1,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=1,k=1,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=1,k=1,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=1,k=1,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=1,k=1,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=1,k=1,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=1,k=1,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=1,k=1,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=1,k=1,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=1,k=1,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=1,k=16,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=1,k=16,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=1,k=16,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=1,k=16,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=1,k=16,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=1,k=16,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=1,k=16,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=1,k=16,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=1,k=16,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=1,k=16,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=1,k=16,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=1,k=16,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=1,k=16,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=1,k=16,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=1,k=16,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=1,k=16,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=16,k=1,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=16,k=1,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=16,k=1,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=16,k=1,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=16,k=1,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=16,k=1,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=16,k=1,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=16,k=1,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=16,k=1,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=16,k=1,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=16,k=1,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=16,k=1,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=16,k=1,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=16,k=1,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=16,k=1,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=16,k=1,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=16,k=16,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=16,k=16,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=16,k=16,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=16,k=16,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=16,k=16,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=16,k=16,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=16,k=16,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=16,k=16,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=16,k=16,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=16,k=16,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=16,k=16,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=16,k=16,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=16,k=16,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=16,k=16,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=16,k=16,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f32,m=256,n=16,k=16,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=1,k=1,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=1,k=1,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=1,k=1,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=1,k=1,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=1,k=1,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=1,k=1,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=1,k=1,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=1,k=1,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=1,k=1,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=1,k=1,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=1,k=1,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=1,k=1,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=1,k=1,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=1,k=1,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=1,k=1,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=1,k=1,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=1,k=16,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=1,k=16,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=1,k=16,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=1,k=16,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=1,k=16,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=1,k=16,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=1,k=16,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=1,k=16,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=1,k=16,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=1,k=16,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=1,k=16,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=1,k=16,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=1,k=16,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=1,k=16,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=1,k=16,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=1,k=16,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=16,k=1,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=16,k=1,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=16,k=1,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=16,k=1,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=16,k=1,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=16,k=1,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=16,k=1,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=16,k=1,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=16,k=1,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=16,k=1,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=16,k=1,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=16,k=1,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=16,k=1,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=16,k=1,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=16,k=1,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=16,k=1,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=16,k=16,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=16,k=16,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=16,k=16,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=16,k=16,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=16,k=16,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=16,k=16,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=16,k=16,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=16,k=16,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=16,k=16,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=16,k=16,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=16,k=16,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=16,k=16,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=16,k=16,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=16,k=16,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=16,k=16,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q8_0,type_b=f16,m=256,n=16,k=16,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=1,k=1,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=1,k=1,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=1,k=1,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=1,k=1,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=1,k=1,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=1,k=1,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=1,k=1,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=1,k=1,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=1,k=1,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=1,k=1,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=1,k=1,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=1,k=1,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=1,k=1,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=1,k=1,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=1,k=1,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=1,k=1,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=1,k=16,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=1,k=16,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=1,k=16,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=1,k=16,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=1,k=16,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=1,k=16,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=1,k=16,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=1,k=16,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=1,k=16,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=1,k=16,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=1,k=16,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=1,k=16,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=1,k=16,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=1,k=16,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=1,k=16,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=1,k=16,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=16,k=1,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=16,k=1,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=16,k=1,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=16,k=1,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=16,k=1,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=16,k=1,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=16,k=1,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=16,k=1,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=16,k=1,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=16,k=1,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=16,k=1,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=16,k=1,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=16,k=1,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=16,k=1,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=16,k=1,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=16,k=1,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=16,k=16,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=16,k=16,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=16,k=16,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=16,k=16,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=16,k=16,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=16,k=16,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=16,k=16,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=16,k=16,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=16,k=16,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=16,k=16,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=16,k=16,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=16,k=16,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=16,k=16,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=16,k=16,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=16,k=16,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f32,m=256,n=16,k=16,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=1,k=1,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=1,k=1,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=1,k=1,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=1,k=1,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=1,k=1,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=1,k=1,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=1,k=1,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=1,k=1,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=1,k=1,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=1,k=1,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=1,k=1,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=1,k=1,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=1,k=1,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=1,k=1,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=1,k=1,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=1,k=1,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=1,k=16,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=1,k=16,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=1,k=16,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=1,k=16,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=1,k=16,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=1,k=16,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=1,k=16,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=1,k=16,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=1,k=16,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=1,k=16,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=1,k=16,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=1,k=16,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=1,k=16,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=1,k=16,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=1,k=16,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=1,k=16,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=16,k=1,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=16,k=1,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=16,k=1,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=16,k=1,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=16,k=1,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=16,k=1,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=16,k=1,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=16,k=1,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=16,k=1,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=16,k=1,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=16,k=1,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=16,k=1,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=16,k=1,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=16,k=1,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=16,k=1,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=16,k=1,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=16,k=16,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=16,k=16,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=16,k=16,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=16,k=16,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=16,k=16,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=16,k=16,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=16,k=16,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=16,k=16,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=16,k=16,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=16,k=16,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=16,k=16,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=16,k=16,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=16,k=16,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=16,k=16,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=16,k=16,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_0,type_b=f16,m=256,n=16,k=16,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=1,k=1,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=1,k=1,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=1,k=1,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=1,k=1,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=1,k=1,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=1,k=1,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=1,k=1,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=1,k=1,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=1,k=1,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=1,k=1,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=1,k=1,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=1,k=1,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=1,k=1,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=1,k=1,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=1,k=1,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=1,k=1,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=1,k=16,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=1,k=16,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=1,k=16,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=1,k=16,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=1,k=16,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=1,k=16,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=1,k=16,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=1,k=16,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=1,k=16,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=1,k=16,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=1,k=16,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=1,k=16,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=1,k=16,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=1,k=16,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=1,k=16,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=1,k=16,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=16,k=1,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=16,k=1,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=16,k=1,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=16,k=1,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=16,k=1,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=16,k=1,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=16,k=1,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=16,k=1,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=16,k=1,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=16,k=1,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=16,k=1,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=16,k=1,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=16,k=1,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=16,k=1,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=16,k=1,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=16,k=1,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=16,k=16,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=16,k=16,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=16,k=16,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=16,k=16,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=16,k=16,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=16,k=16,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=16,k=16,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=16,k=16,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=16,k=16,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=16,k=16,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=16,k=16,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=16,k=16,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=16,k=16,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=16,k=16,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=16,k=16,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f32,m=256,n=16,k=16,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=1,k=1,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=1,k=1,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=1,k=1,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=1,k=1,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=1,k=1,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=1,k=1,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=1,k=1,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=1,k=1,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=1,k=1,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=1,k=1,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=1,k=1,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=1,k=1,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=1,k=1,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=1,k=1,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=1,k=1,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=1,k=1,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=1,k=16,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=1,k=16,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=1,k=16,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=1,k=16,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=1,k=16,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=1,k=16,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=1,k=16,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=1,k=16,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=1,k=16,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=1,k=16,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=1,k=16,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=1,k=16,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=1,k=16,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=1,k=16,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=1,k=16,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=1,k=16,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=16,k=1,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=16,k=1,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=16,k=1,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=16,k=1,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=16,k=1,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=16,k=1,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=16,k=1,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=16,k=1,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=16,k=1,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=16,k=1,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=16,k=1,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=16,k=1,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=16,k=1,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=16,k=1,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=16,k=1,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=16,k=1,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=16,k=16,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=16,k=16,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=16,k=16,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=16,k=16,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=16,k=16,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=16,k=16,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=16,k=16,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=16,k=16,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=16,k=16,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=16,k=16,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=16,k=16,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=16,k=16,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=16,k=16,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=16,k=16,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=16,k=16,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_1,type_b=f16,m=256,n=16,k=16,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=1,k=1,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=1,k=1,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=1,k=1,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=1,k=1,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=1,k=1,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=1,k=1,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=1,k=1,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=1,k=1,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=1,k=1,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=1,k=1,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=1,k=1,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=1,k=1,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=1,k=1,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=1,k=1,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=1,k=1,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=1,k=1,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=1,k=16,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=1,k=16,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=1,k=16,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=1,k=16,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=1,k=16,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=1,k=16,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=1,k=16,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=1,k=16,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=1,k=16,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=1,k=16,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=1,k=16,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=1,k=16,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=1,k=16,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=1,k=16,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=1,k=16,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=1,k=16,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=16,k=1,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=16,k=1,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=16,k=1,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=16,k=1,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=16,k=1,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=16,k=1,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=16,k=1,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=16,k=1,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=16,k=1,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=16,k=1,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=16,k=1,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=16,k=1,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=16,k=1,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=16,k=1,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=16,k=1,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=16,k=1,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=16,k=16,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=16,k=16,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=16,k=16,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=16,k=16,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=16,k=16,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=16,k=16,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=16,k=16,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=16,k=16,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=16,k=16,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=16,k=16,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=16,k=16,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=16,k=16,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=16,k=16,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=16,k=16,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=16,k=16,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f32,m=256,n=16,k=16,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=1,k=1,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=1,k=1,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=1,k=1,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=1,k=1,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=1,k=1,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=1,k=1,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=1,k=1,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=1,k=1,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=1,k=1,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=1,k=1,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=1,k=1,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=1,k=1,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=1,k=1,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=1,k=1,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=1,k=1,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=1,k=1,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=1,k=16,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=1,k=16,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=1,k=16,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=1,k=16,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=1,k=16,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=1,k=16,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=1,k=16,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=1,k=16,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=1,k=16,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=1,k=16,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=1,k=16,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=1,k=16,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=1,k=16,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=1,k=16,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=1,k=16,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=1,k=16,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=16,k=1,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=16,k=1,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=16,k=1,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=16,k=1,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=16,k=1,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=16,k=1,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=16,k=1,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=16,k=1,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=16,k=1,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=16,k=1,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=16,k=1,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=16,k=1,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=16,k=1,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=16,k=1,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=16,k=1,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=16,k=1,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=16,k=16,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=16,k=16,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=16,k=16,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=16,k=16,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=16,k=16,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=16,k=16,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=16,k=16,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=16,k=16,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=16,k=16,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=16,k=16,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=16,k=16,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=16,k=16,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=16,k=16,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=16,k=16,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=16,k=16,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=q4_K,type_b=f16,m=256,n=16,k=16,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=1,k=1,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=1,k=1,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=1,k=1,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=1,k=1,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=1,k=1,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=1,k=1,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=1,k=1,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=1,k=1,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=1,k=1,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=1,k=1,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=1,k=1,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=1,k=1,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=1,k=1,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=1,k=1,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=1,k=1,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=1,k=1,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=1,k=16,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=1,k=16,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=1,k=16,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=1,k=16,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=1,k=16,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=1,k=16,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=1,k=16,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=1,k=16,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=1,k=16,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=1,k=16,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=1,k=16,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=1,k=16,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=1,k=16,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=1,k=16,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=1,k=16,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=1,k=16,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=16,k=1,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=16,k=1,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=16,k=1,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=16,k=1,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=16,k=1,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=16,k=1,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=16,k=1,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=16,k=1,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=16,k=1,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=16,k=1,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=16,k=1,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=16,k=1,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=16,k=1,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=16,k=1,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=16,k=1,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=16,k=1,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=16,k=16,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=16,k=16,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=16,k=16,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=16,k=16,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=16,k=16,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=16,k=16,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=16,k=16,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=16,k=16,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=16,k=16,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=16,k=16,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=16,k=16,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=16,k=16,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=16,k=16,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=16,k=16,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=16,k=16,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f32,m=256,n=16,k=16,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=1,k=1,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=1,k=1,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=1,k=1,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=1,k=1,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=1,k=1,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=1,k=1,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=1,k=1,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=1,k=1,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=1,k=1,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=1,k=1,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=1,k=1,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=1,k=1,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=1,k=1,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=1,k=1,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=1,k=1,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=1,k=1,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=1,k=16,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=1,k=16,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=1,k=16,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=1,k=16,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=1,k=16,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=1,k=16,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=1,k=16,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=1,k=16,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=1,k=16,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=1,k=16,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=1,k=16,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=1,k=16,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=1,k=16,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=1,k=16,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=1,k=16,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=1,k=16,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=16,k=1,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=16,k=1,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=16,k=1,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=16,k=1,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=16,k=1,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=16,k=1,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=16,k=1,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=16,k=1,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=16,k=1,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=16,k=1,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=16,k=1,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=16,k=1,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=16,k=1,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=16,k=1,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=16,k=1,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=16,k=1,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=16,k=16,bs=[1,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=16,k=16,bs=[1,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=16,k=16,bs=[1,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=16,k=16,bs=[1,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=16,k=16,bs=[1,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=16,k=16,bs=[1,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=16,k=16,bs=[1,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=16,k=16,bs=[1,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=16,k=16,bs=[3,1],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=16,k=16,bs=[3,1],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=16,k=16,bs=[3,1],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=16,k=16,bs=[3,1],nr=[2,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=16,k=16,bs=[3,3],nr=[1,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=16,k=16,bs=[3,3],nr=[1,2],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=16,k=16,bs=[3,3],nr=[2,1],trans_b=0): not supported [SYCL0] 
  OUT_PROD(type_a=iq2_xxs,type_b=f16,m=256,n=16,k=16,bs=[3,3],nr=[2,2],trans_b=0): not supported [SYCL0] 
  SQR(type=f16,ne=[10,5,4,3]): [1;32mOK[0m
  SQRT(type=f16,ne=[10,3,3,2]): [1;32mOK[0m
  LOG(type=f16,ne=[10,5,4,3]): [1;32mOK[0m
  SIN(type=f16,ne=[10,2,2,2]): [1;32mOK[0m
  COS(type=f16,ne=[10,2,2,2]): [1;32mOK[0m
  CLAMP(type=f16,ne=[10,5,4,3],min=-0.500000,max=0.500000): [1;32mOK[0m
  SQR(type=f32,ne=[10,5,4,3]): [1;32mOK[0m
  SQRT(type=f32,ne=[10,3,3,2]): [1;32mOK[0m
  LOG(type=f32,ne=[10,5,4,3]): [1;32mOK[0m
  SIN(type=f32,ne=[10,2,2,2]): [1;32mOK[0m
  COS(type=f32,ne=[10,2,2,2]): [1;32mOK[0m
  CLAMP(type=f32,ne=[10,5,4,3],min=-0.500000,max=0.500000): [1;32mOK[0m
  DIAG_MASK_INF(type=f32,ne=[10,10,1,1],n_past=5): [1;32mOK[0m
  DIAG_MASK_INF(type=f32,ne=[10,10,3,1],n_past=5): [1;32mOK[0m
  DIAG_MASK_INF(type=f32,ne=[10,10,3,2],n_past=5): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[16,16,1,1],mask=0,m_prec=f32,nr23=[1,1],scale=1.000000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[15,15,1,1],mask=0,m_prec=f32,nr23=[1,1],scale=1.000000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[16,1024,1,1],mask=0,m_prec=f32,nr23=[1,1],scale=1.000000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[15,1023,1,1],mask=0,m_prec=f32,nr23=[1,1],scale=1.000000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1024,16,1,1],mask=0,m_prec=f32,nr23=[1,1],scale=1.000000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1023,15,1,1],mask=0,m_prec=f32,nr23=[1,1],scale=1.000000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1024,1024,1,1],mask=0,m_prec=f32,nr23=[1,1],scale=1.000000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1023,1023,1,1],mask=0,m_prec=f32,nr23=[1,1],scale=1.000000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[16,16,1,1],mask=0,m_prec=f32,nr23=[1,1],scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[15,15,1,1],mask=0,m_prec=f32,nr23=[1,1],scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[16,1024,1,1],mask=0,m_prec=f32,nr23=[1,1],scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[15,1023,1,1],mask=0,m_prec=f32,nr23=[1,1],scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1024,16,1,1],mask=0,m_prec=f32,nr23=[1,1],scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1023,15,1,1],mask=0,m_prec=f32,nr23=[1,1],scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1024,1024,1,1],mask=0,m_prec=f32,nr23=[1,1],scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1023,1023,1,1],mask=0,m_prec=f32,nr23=[1,1],scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[16,16,1,1],mask=1,m_prec=f32,nr23=[1,1],scale=1.000000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[15,15,1,1],mask=1,m_prec=f32,nr23=[1,1],scale=1.000000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[16,16,1,3],mask=1,m_prec=f32,nr23=[3,1],scale=1.000000,max_bias=0.000000): not supported [SYCL0] 
  SOFT_MAX(type=f32,ne=[15,15,1,1],mask=1,m_prec=f32,nr23=[2,3],scale=1.000000,max_bias=0.000000): not supported [SYCL0] 
  SOFT_MAX(type=f32,ne=[16,16,1,1],mask=1,m_prec=f16,nr23=[1,1],scale=1.000000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[15,15,1,1],mask=1,m_prec=f16,nr23=[1,1],scale=1.000000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[16,16,1,3],mask=1,m_prec=f16,nr23=[3,1],scale=1.000000,max_bias=0.000000): not supported [SYCL0] 
  SOFT_MAX(type=f32,ne=[15,15,1,1],mask=1,m_prec=f16,nr23=[2,3],scale=1.000000,max_bias=0.000000): not supported [SYCL0] 
  SOFT_MAX(type=f32,ne=[16,1024,1,1],mask=1,m_prec=f32,nr23=[1,1],scale=1.000000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[15,1023,1,1],mask=1,m_prec=f32,nr23=[1,1],scale=1.000000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[16,1024,1,1],mask=1,m_prec=f16,nr23=[1,1],scale=1.000000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[15,1023,1,1],mask=1,m_prec=f16,nr23=[1,1],scale=1.000000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1024,16,1,1],mask=1,m_prec=f32,nr23=[1,1],scale=1.000000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1023,15,1,1],mask=1,m_prec=f32,nr23=[1,1],scale=1.000000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1024,16,1,1],mask=1,m_prec=f16,nr23=[1,1],scale=1.000000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1023,15,1,1],mask=1,m_prec=f16,nr23=[1,1],scale=1.000000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1024,1024,1,1],mask=1,m_prec=f32,nr23=[1,1],scale=1.000000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1023,1023,1,1],mask=1,m_prec=f32,nr23=[1,1],scale=1.000000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1024,1024,1,1],mask=1,m_prec=f16,nr23=[1,1],scale=1.000000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1023,1023,1,1],mask=1,m_prec=f16,nr23=[1,1],scale=1.000000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[16,16,1,1],mask=1,m_prec=f32,nr23=[1,1],scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[15,15,1,1],mask=1,m_prec=f32,nr23=[1,1],scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[16,16,1,3],mask=1,m_prec=f32,nr23=[3,1],scale=0.100000,max_bias=0.000000): not supported [SYCL0] 
  SOFT_MAX(type=f32,ne=[15,15,1,1],mask=1,m_prec=f32,nr23=[2,3],scale=0.100000,max_bias=0.000000): not supported [SYCL0] 
  SOFT_MAX(type=f32,ne=[16,16,1,1],mask=1,m_prec=f16,nr23=[1,1],scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[15,15,1,1],mask=1,m_prec=f16,nr23=[1,1],scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[16,16,1,3],mask=1,m_prec=f16,nr23=[3,1],scale=0.100000,max_bias=0.000000): not supported [SYCL0] 
  SOFT_MAX(type=f32,ne=[15,15,1,1],mask=1,m_prec=f16,nr23=[2,3],scale=0.100000,max_bias=0.000000): not supported [SYCL0] 
  SOFT_MAX(type=f32,ne=[16,1024,1,1],mask=1,m_prec=f32,nr23=[1,1],scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[15,1023,1,1],mask=1,m_prec=f32,nr23=[1,1],scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[16,1024,1,1],mask=1,m_prec=f16,nr23=[1,1],scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[15,1023,1,1],mask=1,m_prec=f16,nr23=[1,1],scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1024,16,1,1],mask=1,m_prec=f32,nr23=[1,1],scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1023,15,1,1],mask=1,m_prec=f32,nr23=[1,1],scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1024,16,1,1],mask=1,m_prec=f16,nr23=[1,1],scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1023,15,1,1],mask=1,m_prec=f16,nr23=[1,1],scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1024,1024,1,1],mask=1,m_prec=f32,nr23=[1,1],scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1023,1023,1,1],mask=1,m_prec=f32,nr23=[1,1],scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1024,1024,1,1],mask=1,m_prec=f16,nr23=[1,1],scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1023,1023,1,1],mask=1,m_prec=f16,nr23=[1,1],scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[16,16,1,1],mask=1,m_prec=f32,nr23=[1,1],scale=1.000000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[15,15,1,1],mask=1,m_prec=f32,nr23=[1,1],scale=1.000000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[16,16,1,3],mask=1,m_prec=f32,nr23=[3,1],scale=1.000000,max_bias=8.000000): not supported [SYCL0] 
  SOFT_MAX(type=f32,ne=[15,15,1,1],mask=1,m_prec=f32,nr23=[2,3],scale=1.000000,max_bias=8.000000): not supported [SYCL0] 
  SOFT_MAX(type=f32,ne=[16,16,1,1],mask=1,m_prec=f16,nr23=[1,1],scale=1.000000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[15,15,1,1],mask=1,m_prec=f16,nr23=[1,1],scale=1.000000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[16,16,1,3],mask=1,m_prec=f16,nr23=[3,1],scale=1.000000,max_bias=8.000000): not supported [SYCL0] 
  SOFT_MAX(type=f32,ne=[15,15,1,1],mask=1,m_prec=f16,nr23=[2,3],scale=1.000000,max_bias=8.000000): not supported [SYCL0] 
  SOFT_MAX(type=f32,ne=[16,1024,1,1],mask=1,m_prec=f32,nr23=[1,1],scale=1.000000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[15,1023,1,1],mask=1,m_prec=f32,nr23=[1,1],scale=1.000000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[16,1024,1,1],mask=1,m_prec=f16,nr23=[1,1],scale=1.000000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[15,1023,1,1],mask=1,m_prec=f16,nr23=[1,1],scale=1.000000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1024,16,1,1],mask=1,m_prec=f32,nr23=[1,1],scale=1.000000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1023,15,1,1],mask=1,m_prec=f32,nr23=[1,1],scale=1.000000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1024,16,1,1],mask=1,m_prec=f16,nr23=[1,1],scale=1.000000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1023,15,1,1],mask=1,m_prec=f16,nr23=[1,1],scale=1.000000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1024,1024,1,1],mask=1,m_prec=f32,nr23=[1,1],scale=1.000000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1023,1023,1,1],mask=1,m_prec=f32,nr23=[1,1],scale=1.000000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1024,1024,1,1],mask=1,m_prec=f16,nr23=[1,1],scale=1.000000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1023,1023,1,1],mask=1,m_prec=f16,nr23=[1,1],scale=1.000000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[16,16,1,1],mask=1,m_prec=f32,nr23=[1,1],scale=0.100000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[15,15,1,1],mask=1,m_prec=f32,nr23=[1,1],scale=0.100000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[16,16,1,3],mask=1,m_prec=f32,nr23=[3,1],scale=0.100000,max_bias=8.000000): not supported [SYCL0] 
  SOFT_MAX(type=f32,ne=[15,15,1,1],mask=1,m_prec=f32,nr23=[2,3],scale=0.100000,max_bias=8.000000): not supported [SYCL0] 
  SOFT_MAX(type=f32,ne=[16,16,1,1],mask=1,m_prec=f16,nr23=[1,1],scale=0.100000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[15,15,1,1],mask=1,m_prec=f16,nr23=[1,1],scale=0.100000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[16,16,1,3],mask=1,m_prec=f16,nr23=[3,1],scale=0.100000,max_bias=8.000000): not supported [SYCL0] 
  SOFT_MAX(type=f32,ne=[15,15,1,1],mask=1,m_prec=f16,nr23=[2,3],scale=0.100000,max_bias=8.000000): not supported [SYCL0] 
  SOFT_MAX(type=f32,ne=[16,1024,1,1],mask=1,m_prec=f32,nr23=[1,1],scale=0.100000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[15,1023,1,1],mask=1,m_prec=f32,nr23=[1,1],scale=0.100000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[16,1024,1,1],mask=1,m_prec=f16,nr23=[1,1],scale=0.100000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[15,1023,1,1],mask=1,m_prec=f16,nr23=[1,1],scale=0.100000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1024,16,1,1],mask=1,m_prec=f32,nr23=[1,1],scale=0.100000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1023,15,1,1],mask=1,m_prec=f32,nr23=[1,1],scale=0.100000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1024,16,1,1],mask=1,m_prec=f16,nr23=[1,1],scale=0.100000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1023,15,1,1],mask=1,m_prec=f16,nr23=[1,1],scale=0.100000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1024,1024,1,1],mask=1,m_prec=f32,nr23=[1,1],scale=0.100000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1023,1023,1,1],mask=1,m_prec=f32,nr23=[1,1],scale=0.100000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1024,1024,1,1],mask=1,m_prec=f16,nr23=[1,1],scale=0.100000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[1023,1023,1,1],mask=1,m_prec=f16,nr23=[1,1],scale=0.100000,max_bias=8.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[16,2,32,1],mask=1,m_prec=f32,nr23=[1,1],scale=0.100000,max_bias=0.000000): not supported [SYCL0] 
  SOFT_MAX(type=f32,ne=[16,2,32,1],mask=1,m_prec=f16,nr23=[1,1],scale=0.100000,max_bias=0.000000): not supported [SYCL0] 
  SOFT_MAX(type=f32,ne=[16,2,32,1],mask=0,m_prec=f32,nr23=[1,1],scale=0.100000,max_bias=0.000000): [1;32mOK[0m
  SOFT_MAX(type=f32,ne=[32,2,32,1],mask=1,m_prec=f32,nr23=[1,1],scale=0.100000,max_bias=0.000000): not supported [SYCL0] 
  SOFT_MAX(type=f32,ne=[32,2,32,1],mask=1,m_prec=f16,nr23=[1,1],scale=0.100000,max_bias=0.000000): not supported [SYCL0] 
  SOFT_MAX(type=f32,ne=[32,2,32,1],mask=1,m_prec=f32,nr23=[1,1],scale=0.100000,max_bias=8.000000): not supported [SYCL0] 
  SOFT_MAX(type=f32,ne=[32,2,32,1],mask=1,m_prec=f16,nr23=[1,1],scale=0.100000,max_bias=8.000000): not supported [SYCL0] 
  SOFT_MAX_BACK(type=f32,ne=[16,16,1,1],scale=1.000000,max_bias=0.000000): not supported [SYCL0] 
  SOFT_MAX_BACK(type=f32,ne=[15,15,1,1],scale=1.000000,max_bias=0.000000): not supported [SYCL0] 
  SOFT_MAX_BACK(type=f32,ne=[16,1024,1,1],scale=1.000000,max_bias=0.000000): not supported [SYCL0] 
  SOFT_MAX_BACK(type=f32,ne=[15,1023,1,1],scale=1.000000,max_bias=0.000000): not supported [SYCL0] 
  SOFT_MAX_BACK(type=f32,ne=[1024,16,1,1],scale=1.000000,max_bias=0.000000): not supported [SYCL0] 
  SOFT_MAX_BACK(type=f32,ne=[1023,15,1,1],scale=1.000000,max_bias=0.000000): not supported [SYCL0] 
  SOFT_MAX_BACK(type=f32,ne=[1024,1024,1,1],scale=1.000000,max_bias=0.000000): not supported [SYCL0] 
  SOFT_MAX_BACK(type=f32,ne=[1023,1023,1,1],scale=1.000000,max_bias=0.000000): not supported [SYCL0] 
  SOFT_MAX_BACK(type=f32,ne=[16,16,1,1],scale=0.100000,max_bias=0.000000): not supported [SYCL0] 
  SOFT_MAX_BACK(type=f32,ne=[15,15,1,1],scale=0.100000,max_bias=0.000000): not supported [SYCL0] 
  SOFT_MAX_BACK(type=f32,ne=[16,1024,1,1],scale=0.100000,max_bias=0.000000): not supported [SYCL0] 
  SOFT_MAX_BACK(type=f32,ne=[15,1023,1,1],scale=0.100000,max_bias=0.000000): not supported [SYCL0] 
  SOFT_MAX_BACK(type=f32,ne=[1024,16,1,1],scale=0.100000,max_bias=0.000000): not supported [SYCL0] 
  SOFT_MAX_BACK(type=f32,ne=[1023,15,1,1],scale=0.100000,max_bias=0.000000): not supported [SYCL0] 
  SOFT_MAX_BACK(type=f32,ne=[1024,1024,1,1],scale=0.100000,max_bias=0.000000): not supported [SYCL0] 
  SOFT_MAX_BACK(type=f32,ne=[1023,1023,1,1],scale=0.100000,max_bias=0.000000): not supported [SYCL0] 
  SOFT_MAX_BACK(type=f32,ne=[16,16,1,1],scale=1.000000,max_bias=8.000000): not supported [SYCL0] 
  SOFT_MAX_BACK(type=f32,ne=[15,15,1,1],scale=1.000000,max_bias=8.000000): not supported [SYCL0] 
  SOFT_MAX_BACK(type=f32,ne=[16,1024,1,1],scale=1.000000,max_bias=8.000000): not supported [SYCL0] 
  SOFT_MAX_BACK(type=f32,ne=[15,1023,1,1],scale=1.000000,max_bias=8.000000): not supported [SYCL0] 
  SOFT_MAX_BACK(type=f32,ne=[1024,16,1,1],scale=1.000000,max_bias=8.000000): not supported [SYCL0] 
  SOFT_MAX_BACK(type=f32,ne=[1023,15,1,1],scale=1.000000,max_bias=8.000000): not supported [SYCL0] 
  SOFT_MAX_BACK(type=f32,ne=[1024,1024,1,1],scale=1.000000,max_bias=8.000000): not supported [SYCL0] 
  SOFT_MAX_BACK(type=f32,ne=[1023,1023,1,1],scale=1.000000,max_bias=8.000000): not supported [SYCL0] 
  SOFT_MAX_BACK(type=f32,ne=[16,16,1,1],scale=0.100000,max_bias=8.000000): not supported [SYCL0] 
  SOFT_MAX_BACK(type=f32,ne=[15,15,1,1],scale=0.100000,max_bias=8.000000): not supported [SYCL0] 
  SOFT_MAX_BACK(type=f32,ne=[16,1024,1,1],scale=0.100000,max_bias=8.000000): not supported [SYCL0] 
  SOFT_MAX_BACK(type=f32,ne=[15,1023,1,1],scale=0.100000,max_bias=8.000000): not supported [SYCL0] 
  SOFT_MAX_BACK(type=f32,ne=[1024,16,1,1],scale=0.100000,max_bias=8.000000): not supported [SYCL0] 
  SOFT_MAX_BACK(type=f32,ne=[1023,15,1,1],scale=0.100000,max_bias=8.000000): not supported [SYCL0] 
  SOFT_MAX_BACK(type=f32,ne=[1024,1024,1,1],scale=0.100000,max_bias=8.000000): not supported [SYCL0] 
  SOFT_MAX_BACK(type=f32,ne=[1023,1023,1,1],scale=0.100000,max_bias=8.000000): not supported [SYCL0] 
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,40,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,52,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,64,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,1,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,71,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,8,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[80,32,2,1],n_dims=20,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[80,32,2,1],n_dims=32,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[80,32,4,1],n_dims=32,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[80,32,2,1],n_dims=20,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[80,32,2,1],n_dims=32,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[80,32,4,1],n_dims=32,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,12,2,1],n_dims=128,mode=8,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,28,2,1],n_dims=128,mode=8,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,12,2,1],n_dims=20,mode=8,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,28,2,1],n_dims=32,mode=8,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[80,16,2,1],n_dims=80,mode=24,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,40,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,52,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,64,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,1,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,71,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,8,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[80,32,2,1],n_dims=20,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[80,32,2,1],n_dims=32,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[80,32,4,1],n_dims=32,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[80,32,2,1],n_dims=20,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[80,32,2,1],n_dims=32,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[80,32,4,1],n_dims=32,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,12,2,1],n_dims=128,mode=8,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,28,2,1],n_dims=128,mode=8,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,12,2,1],n_dims=20,mode=8,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,28,2,1],n_dims=32,mode=8,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[80,16,2,1],n_dims=80,mode=24,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,40,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,52,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,64,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,1,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,71,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,8,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[80,32,2,1],n_dims=20,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[80,32,2,1],n_dims=32,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[80,32,4,1],n_dims=32,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[80,32,2,1],n_dims=20,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[80,32,2,1],n_dims=32,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[80,32,4,1],n_dims=32,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,12,2,1],n_dims=128,mode=8,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,28,2,1],n_dims=128,mode=8,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,12,2,1],n_dims=20,mode=8,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,28,2,1],n_dims=32,mode=8,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[80,16,2,1],n_dims=80,mode=24,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,40,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,52,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,64,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,1,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,71,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,8,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[80,32,2,1],n_dims=20,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[80,32,2,1],n_dims=32,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[80,32,4,1],n_dims=32,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[80,32,2,1],n_dims=20,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[80,32,2,1],n_dims=32,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[80,32,4,1],n_dims=32,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,12,2,1],n_dims=128,mode=8,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,28,2,1],n_dims=128,mode=8,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,12,2,1],n_dims=20,mode=8,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,28,2,1],n_dims=32,mode=8,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[80,16,2,1],n_dims=80,mode=24,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=0,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=0,v=1): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=1,v=0): [1;32mOK[0m
  ROPE(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=1,v=1): [1;32mOK[0m
  ROPE(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=1,v=1): [1;32mOK[0m
  ROPE_BACK(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,40,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,52,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,64,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[64,1,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[64,71,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[64,8,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[80,32,2,1],n_dims=20,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[80,32,2,1],n_dims=32,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[80,32,4,1],n_dims=32,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[80,32,2,1],n_dims=20,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[80,32,2,1],n_dims=32,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[80,32,4,1],n_dims=32,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,12,2,1],n_dims=128,mode=8,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,28,2,1],n_dims=128,mode=8,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,12,2,1],n_dims=20,mode=8,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,28,2,1],n_dims=32,mode=8,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[80,16,2,1],n_dims=80,mode=24,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,40,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,52,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,64,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[64,1,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[64,71,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[64,8,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[80,32,2,1],n_dims=20,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[80,32,2,1],n_dims=32,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[80,32,4,1],n_dims=32,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[80,32,2,1],n_dims=20,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[80,32,2,1],n_dims=32,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[80,32,4,1],n_dims=32,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,12,2,1],n_dims=128,mode=8,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,28,2,1],n_dims=128,mode=8,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,12,2,1],n_dims=20,mode=8,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,28,2,1],n_dims=32,mode=8,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[80,16,2,1],n_dims=80,mode=24,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,40,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,52,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,64,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[64,1,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[64,71,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[64,8,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[80,32,2,1],n_dims=20,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[80,32,2,1],n_dims=32,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[80,32,4,1],n_dims=32,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[80,32,2,1],n_dims=20,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[80,32,2,1],n_dims=32,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[80,32,4,1],n_dims=32,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,12,2,1],n_dims=128,mode=8,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,28,2,1],n_dims=128,mode=8,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,12,2,1],n_dims=20,mode=8,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,28,2,1],n_dims=32,mode=8,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[80,16,2,1],n_dims=80,mode=24,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,40,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,52,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,64,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[64,1,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[64,71,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[64,8,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[80,32,2,1],n_dims=20,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[80,32,2,1],n_dims=32,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[80,32,4,1],n_dims=32,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[80,32,2,1],n_dims=20,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[80,32,2,1],n_dims=32,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[80,32,4,1],n_dims=32,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,12,2,1],n_dims=128,mode=8,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,28,2,1],n_dims=128,mode=8,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,12,2,1],n_dims=20,mode=8,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,28,2,1],n_dims=32,mode=8,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[80,16,2,1],n_dims=80,mode=24,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.000000,af=1.424500,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.000000,ef=0.746500,af=1.424500,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.000000,af=1.424500,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.000000,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f32,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=0,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=0,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=1,v=0): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[128,32,2,1],n_dims=128,mode=0,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=1,v=1): not supported [SYCL0] 
  ROPE_BACK(type=f16,ne_a=[64,128,2,1],n_dims=64,mode=2,n_ctx=512,fs=1.424500,ef=0.746500,af=1.424500,ff=1,v=1): not supported [SYCL0] 
  CONCAT(type=f32,ne_a=[11,12,13,14],ne_b_d=7,dim=0,v=0): [1;32mOK[0m
  CONCAT(type=i32,ne_a=[11,12,13,14],ne_b_d=7,dim=0,v=0): not supported [SYCL0] 
  CONCAT(type=f32,ne_a=[11,12,13,14],ne_b_d=7,dim=1,v=0): [1;32mOK[0m
  CONCAT(type=i32,ne_a=[11,12,13,14],ne_b_d=7,dim=1,v=0): not supported [SYCL0] 
  CONCAT(type=f32,ne_a=[11,12,13,14],ne_b_d=7,dim=2,v=0): [1;32mOK[0m
  CONCAT(type=i32,ne_a=[11,12,13,14],ne_b_d=7,dim=2,v=0): not supported [SYCL0] 
  CONCAT(type=f32,ne_a=[11,12,13,14],ne_b_d=7,dim=3,v=0): [1;32mOK[0m
  CONCAT(type=i32,ne_a=[11,12,13,14],ne_b_d=7,dim=3,v=0): not supported [SYCL0] 
  CONCAT(type=f32,ne_a=[11,12,13,14],ne_b_d=7,dim=0,v=1): [1;32mOK[0m
  CONCAT(type=i32,ne_a=[11,12,13,14],ne_b_d=7,dim=0,v=1): not supported [SYCL0] 
  CONCAT(type=f32,ne_a=[11,12,13,14],ne_b_d=7,dim=1,v=1): [1;32mOK[0m
  CONCAT(type=i32,ne_a=[11,12,13,14],ne_b_d=7,dim=1,v=1): not supported [SYCL0] 
  CONCAT(type=f32,ne_a=[11,12,13,14],ne_b_d=7,dim=2,v=1): [1;32mOK[0m
  CONCAT(type=i32,ne_a=[11,12,13,14],ne_b_d=7,dim=2,v=1): not supported [SYCL0] 
  CONCAT(type=f32,ne_a=[11,12,13,14],ne_b_d=7,dim=3,v=1): [1;32mOK[0m
  CONCAT(type=i32,ne_a=[11,12,13,14],ne_b_d=7,dim=3,v=1): not supported [SYCL0] 
  CONCAT(type=f32,ne_a=[11,12,13,14],ne_b_d=7,dim=0,v=2): [1;32mOK[0m
  CONCAT(type=i32,ne_a=[11,12,13,14],ne_b_d=7,dim=0,v=2): not supported [SYCL0] 
  CONCAT(type=f32,ne_a=[11,12,13,14],ne_b_d=7,dim=1,v=2): [1;32mOK[0m
  CONCAT(type=i32,ne_a=[11,12,13,14],ne_b_d=7,dim=1,v=2): not supported [SYCL0] 
  CONCAT(type=f32,ne_a=[11,12,13,14],ne_b_d=7,dim=2,v=2): [1;32mOK[0m
  CONCAT(type=i32,ne_a=[11,12,13,14],ne_b_d=7,dim=2,v=2): not supported [SYCL0] 
  CONCAT(type=f32,ne_a=[11,12,13,14],ne_b_d=7,dim=3,v=2): [1;32mOK[0m
  CONCAT(type=i32,ne_a=[11,12,13,14],ne_b_d=7,dim=3,v=2): not supported [SYCL0] 
  CONCAT(type=f32,ne_a=[11,12,13,14],ne_b_d=7,dim=0,v=3): [1;32mOK[0m
  CONCAT(type=i32,ne_a=[11,12,13,14],ne_b_d=7,dim=0,v=3): not supported [SYCL0] 
  CONCAT(type=f32,ne_a=[11,12,13,14],ne_b_d=7,dim=1,v=3): [1;32mOK[0m
  CONCAT(type=i32,ne_a=[11,12,13,14],ne_b_d=7,dim=1,v=3): not supported [SYCL0] 
  CONCAT(type=f32,ne_a=[11,12,13,14],ne_b_d=7,dim=2,v=3): [1;32mOK[0m
  CONCAT(type=i32,ne_a=[11,12,13,14],ne_b_d=7,dim=2,v=3): not supported [SYCL0] 
  CONCAT(type=f32,ne_a=[11,12,13,14],ne_b_d=7,dim=3,v=3): [1;32mOK[0m
  CONCAT(type=i32,ne_a=[11,12,13,14],ne_b_d=7,dim=3,v=3): not supported [SYCL0] 
  ARGSORT(type=f32,ne=[8,1,1,1],order=0): [1;32mOK[0m
  ARGSORT(type=f32,ne=[16,10,10,10],order=0): [1;32mOK[0m
  ARGSORT(type=f32,ne=[60,10,10,10],order=0): [1;32mOK[0m
  ARGSORT(type=f32,ne=[8,1,1,1],order=1): [1;32mOK[0m
  ARGSORT(type=f32,ne=[16,10,10,10],order=1): [1;32mOK[0m
  ARGSORT(type=f32,ne=[60,10,10,10],order=1): [1;32mOK[0m
  UPSCALE(type=f32,ne=[512,512,3,2],scale_factor=2,mode=nearest,transpose=0): [1;32mOK[0m
  UPSCALE(type=f32,ne=[512,512,3,2],scale_factor=2,mode=nearest,transpose=1): [1;32mOK[0m
  UPSCALE(type=f32,ne=[2,5,7,11],ne_tgt=[5,7,11,13],mode=0): [1;32mOK[0m
  UPSCALE(type=f32,ne=[5,7,11,13],ne_tgt=[2,5,7,11],mode=0): [1;32mOK[0m
  UPSCALE(type=f32,ne=[512,512,3,2],scale_factor=2,mode=bilinear,transpose=0): not supported [SYCL0] 
  UPSCALE(type=f32,ne=[512,512,3,2],scale_factor=2,mode=bilinear,transpose=1): not supported [SYCL0] 
  UPSCALE(type=f32,ne=[2,5,7,11],ne_tgt=[5,7,11,13],mode=1): not supported [SYCL0] 
  UPSCALE(type=f32,ne=[5,7,11,13],ne_tgt=[2,5,7,11],mode=1): not supported [SYCL0] 
  UPSCALE(type=f32,ne=[2,5,7,11],ne_tgt=[5,7,11,13],mode=257): not supported [SYCL0] 
  SUM(type=f32,ne=[10,5,4,3]): [1;32mOK[0m
  SUM_ROWS(type=f32,ne=[10,5,4,3]): [1;32mOK[0m
  MEAN(type=f32,ne=[10,5,4,3]): not supported [SYCL0] 
  GROUP_NORM(type=f32,ne=[64,64,320,1],num_groups=32,eps=0.000001): [1;32mOK[0m
  GROUP_NORM(type=f32,ne=[9,9,1280,1],num_groups=32,eps=0.000001): [1;32mOK[0m
  ACC(type=f32,ne_a=[256,17,1,1],ne_b=[256,16,1,1]): [1;32mOK[0m
  PAD(type=f32,ne_a=[512,512,1,1],pad_0=1,pad_1=1): [1;32mOK[0m
  PAD_REFLECT_1D(type=f32,ne_a=[512,34,2,1],pad_0=10,pad_1=9): not supported [SYCL0] 
  ROLL(shift0=3,shift1=-2,shift3=1,shift4=-1): not supported [SYCL0] 
  ARANGE(type=f32,start=0.000000,stop=10.000000,step=1.000000): not supported [SYCL0] 
  TIMESTEP_EMBEDDING(type=f32,ne_a=[2,1,1,1],dim=320,max_period=10000): [1;32mOK[0m
  LEAKY_RELU(type=f32,ne_a=[10,5,4,3],negative_slope=0.100000): [1;32mOK[0m
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,1],kv=1024,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[1,3],kv=1024,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=64,hsv=64,nh=4,nr23=[4,3],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[1,1],kv=1024,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=80,hsv=80,nh=4,nr23=[4,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=128,hsv=128,nh=4,nr23=[16,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=10.000000,prec=def,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[1,1],kv=1024,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=128,nh=4,nr23=[4,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[1,1],kv=1024,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=192,hsv=192,nh=4,nr23=[4,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[1,1],kv=1024,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=256,hsv=256,nh=4,nr23=[4,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,2,1,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=1,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=3,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=32,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=35,mask=1,max_bias=8.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[1,1],kv=1024,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=1,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=3,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=32,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=f16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=bf16,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q8_0,permute=[0,1,2,3]): not supported [SYCL0] 
  FLASH_ATTN_EXT(hsk=576,hsv=512,nh=4,nr23=[4,1],kv=512,nb=35,mask=0,max_bias=0.000000,logit_softcap=0.000000,prec=f32,type_KV=q4_0,permute=[0,1,2,3]): not supported [SYCL0] 
  CROSS_ENTROPY_LOSS(type=f32,ne=[10,5,4,3]): not supported [SYCL0] 
  CROSS_ENTROPY_LOSS(type=f32,ne=[30000,1,1,1]): not supported [SYCL0] 
  CROSS_ENTROPY_LOSS_BACK(type=f32,ne=[10,5,4,3]): not supported [SYCL0] 
  CROSS_ENTROPY_LOSS_BACK(type=f32,ne=[30000,1,1,1]): not supported [SYCL0] 
  OPT_STEP_ADAMW(type=f32,ne=[10,5,4,3]): not supported [SYCL0] 
  6550/6551 tests passed
  Backend SYCL0: [1;31mFAIL[0m
Backend 2/2: CPU
  Skipping CPU backend
1/2 backends passed
[1;31mFAIL[0m

      Start 33: test-barrier
31/35 Test #33: test-barrier ......................   Passed    1.02 sec
      Start 34: test-quantize-fns
32/35 Test #34: test-quantize-fns .................   Passed   14.47 sec
      Start 35: test-quantize-perf
33/35 Test #35: test-quantize-perf ................   Passed    0.36 sec
      Start 36: test-rope
34/35 Test #36: test-rope .........................   Passed    0.34 sec
      Start 37: test-mtmd-c-api
35/35 Test #37: test-mtmd-c-api ...................   Passed    0.14 sec

91% tests passed, 3 tests failed out of 35

Label Time Summary:
main    =  55.82 sec*proc (35 tests)

Total Test time (real) =  55.84 sec

The following tests FAILED:
	 14 - test-tokenizers-ggml-vocabs (Failed)
	 27 - test-thread-safety (Failed)
	 30 - test-backend-ops (Failed)
Errors while running CTest

real	0m55.848s
user	0m56.546s
sys	0m12.357s
```
