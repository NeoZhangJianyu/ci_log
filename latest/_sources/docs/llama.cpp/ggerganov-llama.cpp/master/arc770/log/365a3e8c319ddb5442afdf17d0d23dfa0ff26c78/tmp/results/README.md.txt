### ctest_release

Runs ctest in release mode
- status: 8
```
+ ctest --output-on-failure -L main
Test project /home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/build-ci-release
      Start  1: test-tokenizer-0-bert-bge
 1/41 Test  #1: test-tokenizer-0-bert-bge .........   Passed    0.11 sec
      Start  2: test-tokenizer-0-command-r
 2/41 Test  #2: test-tokenizer-0-command-r ........   Passed    0.39 sec
      Start  3: test-tokenizer-0-deepseek-coder
 3/41 Test  #3: test-tokenizer-0-deepseek-coder ...   Passed    0.10 sec
      Start  4: test-tokenizer-0-deepseek-llm
 4/41 Test  #4: test-tokenizer-0-deepseek-llm .....   Passed    0.17 sec
      Start  5: test-tokenizer-0-falcon
 5/41 Test  #5: test-tokenizer-0-falcon ...........   Passed    0.12 sec
      Start  6: test-tokenizer-0-gpt-2
 6/41 Test  #6: test-tokenizer-0-gpt-2 ............   Passed    0.11 sec
      Start  7: test-tokenizer-0-llama-bpe
 7/41 Test  #7: test-tokenizer-0-llama-bpe ........   Passed    0.27 sec
      Start  8: test-tokenizer-0-llama-spm
 8/41 Test  #8: test-tokenizer-0-llama-spm ........   Passed    0.09 sec
      Start  9: test-tokenizer-0-mpt
 9/41 Test  #9: test-tokenizer-0-mpt ..............   Passed    0.11 sec
      Start 10: test-tokenizer-0-phi-3
10/41 Test #10: test-tokenizer-0-phi-3 ............   Passed    0.09 sec
      Start 11: test-tokenizer-0-qwen2
11/41 Test #11: test-tokenizer-0-qwen2 ............   Passed    0.23 sec
      Start 12: test-tokenizer-0-refact
12/41 Test #12: test-tokenizer-0-refact ...........   Passed    0.11 sec
      Start 13: test-tokenizer-0-starcoder
13/41 Test #13: test-tokenizer-0-starcoder ........   Passed    0.11 sec
      Start 14: test-tokenizers-ggml-vocabs
14/41 Test #14: test-tokenizers-ggml-vocabs .......***Failed    2.91 sec
Already up to date.
main : reading vocab from: '/home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/models/ggml-vocabs/PLaMo2/ggml-vocab-plamo2.gguf'
llama_model_load_from_file_impl: using device SYCL0 (Intel(R) Arc(TM) A770 Graphics) (unknown id) - 15473 MiB free
gguf_init_from_file_impl: invalid magic characters: 'vers', expected 'GGUF'
llama_model_load: error loading model: llama_model_loader: failed to load model from /home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/models/ggml-vocabs/PLaMo2/ggml-vocab-plamo2.gguf
llama_model_load_from_file_impl: failed to load model
main: error: failed to load vocab '/home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/models/ggml-vocabs/PLaMo2/ggml-vocab-plamo2.gguf'
main : reading vocab from: '/home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/models/ggml-vocabs/RWKV/ggml-vocab-rwkv-7-world.gguf'
llama_model_load_from_file_impl: using device SYCL0 (Intel(R) Arc(TM) A770 Graphics) (unknown id) - 15473 MiB free
gguf_init_from_file_impl: invalid magic characters: 'vers', expected 'GGUF'
llama_model_load: error loading model: llama_model_loader: failed to load model from /home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/models/ggml-vocabs/RWKV/ggml-vocab-rwkv-7-world.gguf
llama_model_load_from_file_impl: failed to load model
main: error: failed to load vocab '/home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/models/ggml-vocabs/RWKV/ggml-vocab-rwkv-7-world.gguf'
main : reading vocab from: '/home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/models/ggml-vocabs/SPM/ggml-vocab-gemma-3.gguf'
llama_model_load_from_file_impl: using device SYCL0 (Intel(R) Arc(TM) A770 Graphics) (unknown id) - 15473 MiB free
gguf_init_from_file_impl: invalid magic characters: 'vers', expected 'GGUF'
llama_model_load: error loading model: llama_model_loader: failed to load model from /home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/models/ggml-vocabs/SPM/ggml-vocab-gemma-3.gguf
llama_model_load_from_file_impl: failed to load model
main: error: failed to load vocab '/home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/models/ggml-vocabs/SPM/ggml-vocab-gemma-3.gguf'
main : reading vocab from: '/home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/models/ggml-vocabs/UGM/ggml-vocab-nomic-bert-moe.gguf'
llama_model_load_from_file_impl: using device SYCL0 (Intel(R) Arc(TM) A770 Graphics) (unknown id) - 15473 MiB free
gguf_init_from_file_impl: invalid magic characters: 'vers', expected 'GGUF'
llama_model_load: error loading model: llama_model_loader: failed to load model from /home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/models/ggml-vocabs/UGM/ggml-vocab-nomic-bert-moe.gguf
llama_model_load_from_file_impl: failed to load model
main: error: failed to load vocab '/home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/models/ggml-vocabs/UGM/ggml-vocab-nomic-bert-moe.gguf'
main : reading vocab from: '/home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/models/ggml-vocabs/WPM/ggml-vocab-jina-v2-en.gguf'
llama_model_load_from_file_impl: using device SYCL0 (Intel(R) Arc(TM) A770 Graphics) (unknown id) - 15473 MiB free
gguf_init_from_file_impl: invalid magic characters: 'vers', expected 'GGUF'
llama_model_load: error loading model: llama_model_loader: failed to load model from /home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/models/ggml-vocabs/WPM/ggml-vocab-jina-v2-en.gguf
llama_model_load_from_file_impl: failed to load model
main: error: failed to load vocab '/home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/models/ggml-vocabs/WPM/ggml-vocab-jina-v2-en.gguf'

      Start 15: test-sampling
15/41 Test #15: test-sampling .....................   Passed    0.85 sec
      Start 16: test-grammar-parser
16/41 Test #16: test-grammar-parser ...............   Passed    0.05 sec
      Start 17: test-grammar-integration
17/41 Test #17: test-grammar-integration ..........   Passed    0.05 sec
      Start 18: test-llama-grammar
18/41 Test #18: test-llama-grammar ................   Passed    0.04 sec
      Start 19: test-chat
19/41 Test #19: test-chat .........................   Passed    0.60 sec
      Start 20: test-json-schema-to-grammar
20/41 Test #20: test-json-schema-to-grammar .......   Passed    1.99 sec
      Start 21: test-tokenizer-1-llama-spm
21/41 Test #21: test-tokenizer-1-llama-spm ........   Passed    0.17 sec
      Start 22: test-chat-parser
22/41 Test #22: test-chat-parser ..................   Passed    0.05 sec
      Start 23: test-chat-peg-parser
23/41 Test #23: test-chat-peg-parser ..............   Passed    0.08 sec
      Start 24: test-chat-template
24/41 Test #24: test-chat-template ................   Passed    0.05 sec
      Start 25: test-jinja
25/41 Test #25: test-jinja ........................   Passed    0.08 sec
      Start 26: test-json-partial
26/41 Test #26: test-json-partial .................   Passed    0.04 sec
      Start 27: test-log
27/41 Test #27: test-log ..........................   Passed    0.06 sec
      Start 28: test-peg-parser
28/41 Test #28: test-peg-parser ...................   Passed    0.05 sec
      Start 29: test-regex-partial
29/41 Test #29: test-regex-partial ................   Passed    0.03 sec
      Start 30: test-download-model
30/41 Test #30: test-download-model ...............***Failed  132.63 sec
-- Downloading tinyllamas/stories15M-q4_0.gguf from ggml-org/models...
CMake Error at /home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/cmake/download-models.cmake:8 (file):
  file DOWNLOAD cannot compute hash on failed download

    status: [28;"Timeout was reached"]



      Start 31: test-thread-safety
Failed test dependencies: test-download-model
31/41 Test #31: test-thread-safety ................***Not Run   0.00 sec
      Start 32: test-arg-parser
32/41 Test #32: test-arg-parser ...................   Passed    1.09 sec
      Start 33: test-opt
33/41 Test #33: test-opt ..........................   Passed    0.16 sec
      Start 34: test-gguf
34/41 Test #34: test-gguf .........................   Passed    0.32 sec
      Start 35: test-backend-ops
35/41 Test #35: test-backend-ops ..................Subprocess aborted***Exception:  22.21 sec
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
| 0| [level_zero:gpu:0]|                Intel Arc A770 Graphics|  12.55|    512|    1024|   32| 16225M|         1.3.29735+27|
SYCL Optimization Feature:
|ID|        Device Type|Reorder|
|--|-------------------|-------|
| 0| [level_zero:gpu:0]|      Y|
Testing 2 devices

Backend 1/2: SYCL0
  Device description: Intel(R) Arc(TM) A770 Graphics
  Device memory: 15473 MB (15473 MB free)

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
  EXPM1(type=f16,ne_a=[128,2,2,2],v=0): not supported [SYCL0] 
  EXPM1(type=f16,ne_a=[5,7,11,13],v=0): not supported [SYCL0] 
  SOFTPLUS(type=f16,ne_a=[128,2,2,2],v=0): not supported [SYCL0] 
  SOFTPLUS(type=f16,ne_a=[5,7,11,13],v=0): not supported [SYCL0] 
  GELU_ERF(type=f16,ne_a=[128,2,2,2],v=0): [1;32mOK[0m
  GELU_ERF(type=f16,ne_a=[5,7,11,13],v=0): [1;32mOK[0m
  FLOOR(type=f16,ne_a=[128,2,2,2],v=0): [1;32mOK[0m
  FLOOR(type=f16,ne_a=[5,7,11,13],v=0): [1;32mOK[0m
  CEIL(type=f16,ne_a=[128,2,2,2],v=0): [1;32mOK[0m
  CEIL(type=f16,ne_a=[5,7,11,13],v=0): [1;32mOK[0m
  ROUND(type=f16,ne_a=[128,2,2,2],v=0): [1;32mOK[0m
  ROUND(type=f16,ne_a=[5,7,11,13],v=0): [1;32mOK[0m
  TRUNC(type=f16,ne_a=[128,2,2,2],v=0): [1;32mOK[0m
  TRUNC(type=f16,ne_a=[5,7,11,13],v=0): [1;32mOK[0m
  ABS(type=f16,ne_a=[128,2,2,2],v=1): [1;32mOK[0m
  ABS(type=f16,ne_a=[5,7,11,13],v=1): [1;32mOK[0m
  SGN(type=f16,ne_a=[128,2,2,2],v=1): [1;32mOK[0m
  SGN(type=f16,ne_a=[5,7,11,13],v=1): [1;32mOK[0m
  NEG(type=f16,ne_a=[128,2,2,2],v=1): [1;32mOK[0m
  NEG(type=f16,ne_a=[5,7,11,13],v=1): [1;32mOK[0m
  STEP(type=f16,ne_a=[128,2,2,2],v=1): [1;32mOK[0m
  STEP(type=f16,ne_a=[5,7,11,13],v=1): [1;32mOK[0m
  TANH(type=f16,ne_a=[128,2,2,2],v=1): [1;32mOK[0m
  TANH(type=f16,ne_a=[5,7,11,13],v=1): [1;32mOK[0m
  ELU(type=f16,ne_a=[128,2,2,2],v=1): [1;32mOK[0m
  ELU(type=f16,ne_a=[5,7,11,13],v=1): [1;32mOK[0m
  RELU(type=f16,ne_a=[128,2,2,2],v=1): [1;32mOK[0m
  RELU(type=f16,ne_a=[5,7,11,13],v=1): [1;32mOK[0m
  SIGMOID(type=f16,ne_a=[128,2,2,2],v=1): [1;32mOK[0m
  SIGMOID(type=f16,ne_a=[5,7,11,13],v=1): [1;32mOK[0m
  GELU(type=f16,ne_a=[128,2,2,2],v=1): [1;32mOK[0m
  GELU(type=f16,ne_a=[5,7,11,13],v=1): [1;32mOK[0m
  GELU_QUICK(type=f16,ne_a=[128,2,2,2],v=1): [1;32mOK[0m
  GELU_QUICK(type=f16,ne_a=[5,7,11,13],v=1): [1;32mOK[0m
  SILU(type=f16,ne_a=[128,2,2,2],v=1): [1;32mOK[0m
  SILU(type=f16,ne_a=[5,7,11,13],v=1): [1;32mOK[0m
  HARDSWISH(type=f16,ne_a=[128,2,2,2],v=1): [1;32mOK[0m
  HARDSWISH(type=f16,ne_a=[5,7,11,13],v=1): [1;32mOK[0m
  HARDSIGMOID(type=f16,ne_a=[128,2,2,2],v=1): [1;32mOK[0m
  HARDSIGMOID(type=f16,ne_a=[5,7,11,13],v=1): [1;32mOK[0m
  EXP(type=f16,ne_a=[128,2,2,2],v=1): [1;32mOK[0m
  EXP(type=f16,ne_a=[5,7,11,13],v=1): [1;32mOK[0m
  EXPM1(type=f16,ne_a=[128,2,2,2],v=1): not supported [SYCL0] 
  EXPM1(type=f16,ne_a=[5,7,11,13],v=1): not supported [SYCL0] 
  SOFTPLUS(type=f16,ne_a=[128,2,2,2],v=1): not supported [SYCL0] 
  SOFTPLUS(type=f16,ne_a=[5,7,11,13],v=1): not supported [SYCL0] 
  GELU_ERF(type=f16,ne_a=[128,2,2,2],v=1): [1;32mOK[0m
  GELU_ERF(type=f16,ne_a=[5,7,11,13],v=1): [1;32mOK[0m
  FLOOR(type=f16,ne_a=[128,2,2,2],v=1): not supported [SYCL0] 
  FLOOR(type=f16,ne_a=[5,7,11,13],v=1): not supported [SYCL0] 
  CEIL(type=f16,ne_a=[128,2,2,2],v=1): not supported [SYCL0] 
  CEIL(type=f16,ne_a=[5,7,11,13],v=1): not supported [SYCL0] 
  ROUND(type=f16,ne_a=[128,2,2,2],v=1): not supported [SYCL0] 
  ROUND(type=f16,ne_a=[5,7,11,13],v=1): not supported [SYCL0] 
  TRUNC(type=f16,ne_a=[128,2,2,2],v=1): not supported [SYCL0] 
  TRUNC(type=f16,ne_a=[5,7,11,13],v=1): not supported [SYCL0] 
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
  EXPM1(type=f32,ne_a=[128,2,2,2],v=0): not supported [SYCL0] 
  EXPM1(type=f32,ne_a=[5,7,11,13],v=0): not supported [SYCL0] 
  SOFTPLUS(type=f32,ne_a=[128,2,2,2],v=0): not supported [SYCL0] 
  SOFTPLUS(type=f32,ne_a=[5,7,11,13],v=0): not supported [SYCL0] 
  GELU_ERF(type=f32,ne_a=[128,2,2,2],v=0): [1;32mOK[0m
  GELU_ERF(type=f32,ne_a=[5,7,11,13],v=0): [1;32mOK[0m
  FLOOR(type=f32,ne_a=[128,2,2,2],v=0): [1;32mOK[0m
  FLOOR(type=f32,ne_a=[5,7,11,13],v=0): [1;32mOK[0m
  CEIL(type=f32,ne_a=[128,2,2,2],v=0): [1;32mOK[0m
  CEIL(type=f32,ne_a=[5,7,11,13],v=0): [1;32mOK[0m
  ROUND(type=f32,ne_a=[128,2,2,2],v=0): [1;32mOK[0m
  ROUND(type=f32,ne_a=[5,7,11,13],v=0): [1;32mOK[0m
  TRUNC(type=f32,ne_a=[128,2,2,2],v=0): [1;32mOK[0m
  TRUNC(type=f32,ne_a=[5,7,11,13],v=0): [1;32mOK[0m
  ABS(type=f32,ne_a=[128,2,2,2],v=1): [1;32mOK[0m
  ABS(type=f32,ne_a=[5,7,11,13],v=1): [1;32mOK[0m
  SGN(type=f32,ne_a=[128,2,2,2],v=1): [1;32mOK[0m
  SGN(type=f32,ne_a=[5,7,11,13],v=1): [1;32mOK[0m
  NEG(type=f32,ne_a=[128,2,2,2],v=1): [1;32mOK[0m
  NEG(type=f32,ne_a=[5,7,11,13],v=1): [1;32mOK[0m
  STEP(type=f32,ne_a=[128,2,2,2],v=1): [1;32mOK[0m
  STEP(type=f32,ne_a=[5,7,11,13],v=1): [1;32mOK[0m
  TANH(type=f32,ne_a=[128,2,2,2],v=1): [1;32mOK[0m
  TANH(type=f32,ne_a=[5,7,11,13],v=1): [1;32mOK[0m
  ELU(type=f32,ne_a=[128,2,2,2],v=1): [1;32mOK[0m
  ELU(type=f32,ne_a=[5,7,11,13],v=1): [1;32mOK[0m
  RELU(type=f32,ne_a=[128,2,2,2],v=1): [1;32mOK[0m
  RELU(type=f32,ne_a=[5,7,11,13],v=1): [1;32mOK[0m
  SIGMOID(type=f32,ne_a=[128,2,2,2],v=1): [1;32mOK[0m
  SIGMOID(type=f32,ne_a=[5,7,11,13],v=1): [1;32mOK[0m
  GELU(type=f32,ne_a=[128,2,2,2],v=1): [1;32mOK[0m
  GELU(type=f32,ne_a=[5,7,11,13],v=1): [1;32mOK[0m
  GELU_QUICK(type=f32,ne_a=[128,2,2,2],v=1): [1;32mOK[0m
  GELU_QUICK(type=f32,ne_a=[5,7,11,13],v=1): [1;32mOK[0m
  SILU(type=f32,ne_a=[128,2,2,2],v=1): [1;32mOK[0m
  SILU(type=f32,ne_a=[5,7,11,13],v=1): [1;32mOK[0m
  HARDSWISH(type=f32,ne_a=[128,2,2,2],v=1): [1;32mOK[0m
  HARDSWISH(type=f32,ne_a=[5,7,11,13],v=1): [1;32mOK[0m
  HARDSIGMOID(type=f32,ne_a=[128,2,2,2],v=1): [1;32mOK[0m
  HARDSIGMOID(type=f32,ne_a=[5,7,11,13],v=1): [1;32mOK[0m
  EXP(type=f32,ne_a=[128,2,2,2],v=1): [1;32mOK[0m
  EXP(type=f32,ne_a=[5,7,11,13],v=1): [1;32mOK[0m
  EXPM1(type=f32,ne_a=[128,2,2,2],v=1): not supported [SYCL0] 
  EXPM1(type=f32,ne_a=[5,7,11,13],v=1): not supported [SYCL0] 
  SOFTPLUS(type=f32,ne_a=[128,2,2,2],v=1): not supported [SYCL0] 
  SOFTPLUS(type=f32,ne_a=[5,7,11,13],v=1): not supported [SYCL0] 
  GELU_ERF(type=f32,ne_a=[128,2,2,2],v=1): [1;32mOK[0m
  GELU_ERF(type=f32,ne_a=[5,7,11,13],v=1): [1;32mOK[0m
  FLOOR(type=f32,ne_a=[128,2,2,2],v=1): not supported [SYCL0] 
  FLOOR(type=f32,ne_a=[5,7,11,13],v=1): not supported [SYCL0] 
  CEIL(type=f32,ne_a=[128,2,2,2],v=1): not supported [SYCL0] 
  CEIL(type=f32,ne_a=[5,7,11,13],v=1): not supported [SYCL0] 
  ROUND(type=f32,ne_a=[128,2,2,2],v=1): not supported [SYCL0] 
  ROUND(type=f32,ne_a=[5,7,11,13],v=1): not supported [SYCL0] 
  TRUNC(type=f32,ne_a=[128,2,2,2],v=1): not supported [SYCL0] 
  TRUNC(type=f32,ne_a=[5,7,11,13],v=1): not supported [SYCL0] 
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
  SWIGLU_OAI(type=f32,ne_a=[128,2,2,2],v=0,alpha=0.500000,limit=2.000000): [1;32mOK[0m
  SWIGLU_OAI(type=f32,ne_a=[128,2,2,2],v=0,alpha=0.500000,limit=7.000000): [1;32mOK[0m
  SWIGLU_OAI(type=f32,ne_a=[128,2,2,2],v=0,alpha=1.702000,limit=2.000000): [1;32mOK[0m
  SWIGLU_OAI(type=f32,ne_a=[128,2,2,2],v=0,alpha=1.702000,limit=7.000000): [1;32mOK[0m
  SWIGLU_OAI(type=f32,ne_a=[128,2,2,2],v=1,alpha=0.500000,limit=2.000000): [1;32mOK[0m
  SWIGLU_OAI(type=f32,ne_a=[128,2,2,2],v=1,alpha=0.500000,limit=7.000000): [1;32mOK[0m
  SWIGLU_OAI(type=f32,ne_a=[128,2,2,2],v=1,alpha=1.702000,limit=2.000000): [1;32mOK[0m
  SWIGLU_OAI(type=f32,ne_a=[128,2,2,2],v=1,alpha=1.702000,limit=7.000000): [1;32mOK[0m
  GET_ROWS(type=f32,n=76800,m=5,r=4,be1=1,be2=2,v=0): [1;32mOK[0m
  GET_ROWS(type=f32,n=256,m=80000,r=70000,be1=2,be2=1,v=0): [1;32mOK[0m
  GET_ROWS(type=f32,n=256,m=5,r=4,be1=700,be2=100,v=0): [1;32mOK[0m
  GET_ROWS(type=q4_0,n=76800,m=5,r=4,be1=1,be2=2,v=0): [1;32mOK[0m
  GET_ROWS(type=q4_0,n=256,m=80000,r=70000,be1=2,be2=1,v=0): [1;32mOK[0m
  GET_ROWS(type=q4_0,n=256,m=5,r=4,be1=700,be2=100,v=0): [1;32mOK[0m
  GET_ROWS(type=f32,n=1,m=8,r=2,be1=1,be2=1,v=0): [1;32mOK[0m
  GET_ROWS(type=f32,n=256,m=5,r=4,be1=1,be2=1,v=0): [1;32mOK[0m
  GET_ROWS(type=f32,n=256,m=5,r=4,be1=1,be2=1,v=1): [1;32mOK[0m
  GET_ROWS(type=f32,n=256,m=5,r=4,be1=7,be2=1,v=0): [1;32mOK[0m
  GET_ROWS(type=f32,n=256,m=5,r=4,be1=7,be2=1,v=1): [1;32mOK[0m
  GET_ROWS(type=f16,n=256,m=5,r=4,be1=1,be2=1,v=0): [1;32mOK[0m
  GET_ROWS(type=f16,n=256,m=5,r=4,be1=1,be2=1,v=1): [1;32mOK[0m
  GET_ROWS(type=f16,n=256,m=5,r=4,be1=7,be2=1,v=0): [1;32mOK[0m
  GET_ROWS(type=f16,n=256,m=5,r=4,be1=7,be2=1,v=1): [1;32mOK[0m
  GET_ROWS(type=bf16,n=256,m=5,r=4,be1=1,be2=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=bf16,n=256,m=5,r=4,be1=1,be2=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=bf16,n=256,m=5,r=4,be1=7,be2=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=bf16,n=256,m=5,r=4,be1=7,be2=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=q4_0,n=256,m=5,r=4,be1=1,be2=1,v=0): [1;32mOK[0m
  GET_ROWS(type=q4_0,n=256,m=5,r=4,be1=1,be2=1,v=1): [1;32mOK[0m
  GET_ROWS(type=q4_0,n=256,m=5,r=4,be1=7,be2=1,v=0): [1;32mOK[0m
  GET_ROWS(type=q4_0,n=256,m=5,r=4,be1=7,be2=1,v=1): [1;32mOK[0m
  GET_ROWS(type=q4_1,n=256,m=5,r=4,be1=1,be2=1,v=0): [1;32mOK[0m
  GET_ROWS(type=q4_1,n=256,m=5,r=4,be1=1,be2=1,v=1): [1;32mOK[0m
  GET_ROWS(type=q4_1,n=256,m=5,r=4,be1=7,be2=1,v=0): [1;32mOK[0m
  GET_ROWS(type=q4_1,n=256,m=5,r=4,be1=7,be2=1,v=1): [1;32mOK[0m
  GET_ROWS(type=q5_0,n=256,m=5,r=4,be1=1,be2=1,v=0): [1;32mOK[0m
  GET_ROWS(type=q5_0,n=256,m=5,r=4,be1=1,be2=1,v=1): [1;32mOK[0m
  GET_ROWS(type=q5_0,n=256,m=5,r=4,be1=7,be2=1,v=0): [1;32mOK[0m
  GET_ROWS(type=q5_0,n=256,m=5,r=4,be1=7,be2=1,v=1): [1;32mOK[0m
  GET_ROWS(type=q5_1,n=256,m=5,r=4,be1=1,be2=1,v=0): [1;32mOK[0m
  GET_ROWS(type=q5_1,n=256,m=5,r=4,be1=1,be2=1,v=1): [1;32mOK[0m
  GET_ROWS(type=q5_1,n=256,m=5,r=4,be1=7,be2=1,v=0): [1;32mOK[0m
  GET_ROWS(type=q5_1,n=256,m=5,r=4,be1=7,be2=1,v=1): [1;32mOK[0m
  GET_ROWS(type=q8_0,n=256,m=5,r=4,be1=1,be2=1,v=0): [1;32mOK[0m
  GET_ROWS(type=q8_0,n=256,m=5,r=4,be1=1,be2=1,v=1): [1;32mOK[0m
  GET_ROWS(type=q8_0,n=256,m=5,r=4,be1=7,be2=1,v=0): [1;32mOK[0m
  GET_ROWS(type=q8_0,n=256,m=5,r=4,be1=7,be2=1,v=1): [1;32mOK[0m
  GET_ROWS(type=mxfp4,n=256,m=5,r=4,be1=1,be2=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=mxfp4,n=256,m=5,r=4,be1=1,be2=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=mxfp4,n=256,m=5,r=4,be1=7,be2=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=mxfp4,n=256,m=5,r=4,be1=7,be2=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=q2_K,n=256,m=5,r=4,be1=1,be2=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=q2_K,n=256,m=5,r=4,be1=1,be2=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=q2_K,n=256,m=5,r=4,be1=7,be2=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=q2_K,n=256,m=5,r=4,be1=7,be2=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=q3_K,n=256,m=5,r=4,be1=1,be2=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=q3_K,n=256,m=5,r=4,be1=1,be2=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=q3_K,n=256,m=5,r=4,be1=7,be2=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=q3_K,n=256,m=5,r=4,be1=7,be2=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=q4_K,n=256,m=5,r=4,be1=1,be2=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=q4_K,n=256,m=5,r=4,be1=1,be2=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=q4_K,n=256,m=5,r=4,be1=7,be2=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=q4_K,n=256,m=5,r=4,be1=7,be2=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=q5_K,n=256,m=5,r=4,be1=1,be2=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=q5_K,n=256,m=5,r=4,be1=1,be2=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=q5_K,n=256,m=5,r=4,be1=7,be2=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=q5_K,n=256,m=5,r=4,be1=7,be2=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=q6_K,n=256,m=5,r=4,be1=1,be2=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=q6_K,n=256,m=5,r=4,be1=1,be2=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=q6_K,n=256,m=5,r=4,be1=7,be2=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=q6_K,n=256,m=5,r=4,be1=7,be2=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=iq2_xxs,n=256,m=5,r=4,be1=1,be2=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=iq2_xxs,n=256,m=5,r=4,be1=1,be2=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=iq2_xxs,n=256,m=5,r=4,be1=7,be2=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=iq2_xxs,n=256,m=5,r=4,be1=7,be2=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=iq2_xs,n=256,m=5,r=4,be1=1,be2=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=iq2_xs,n=256,m=5,r=4,be1=1,be2=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=iq2_xs,n=256,m=5,r=4,be1=7,be2=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=iq2_xs,n=256,m=5,r=4,be1=7,be2=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=iq2_s,n=256,m=5,r=4,be1=1,be2=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=iq2_s,n=256,m=5,r=4,be1=1,be2=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=iq2_s,n=256,m=5,r=4,be1=7,be2=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=iq2_s,n=256,m=5,r=4,be1=7,be2=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=iq3_xxs,n=256,m=5,r=4,be1=1,be2=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=iq3_xxs,n=256,m=5,r=4,be1=1,be2=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=iq3_xxs,n=256,m=5,r=4,be1=7,be2=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=iq3_xxs,n=256,m=5,r=4,be1=7,be2=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=iq1_s,n=256,m=5,r=4,be1=1,be2=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=iq1_s,n=256,m=5,r=4,be1=1,be2=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=iq1_s,n=256,m=5,r=4,be1=7,be2=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=iq1_s,n=256,m=5,r=4,be1=7,be2=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=iq1_m,n=256,m=5,r=4,be1=1,be2=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=iq1_m,n=256,m=5,r=4,be1=1,be2=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=iq1_m,n=256,m=5,r=4,be1=7,be2=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=iq1_m,n=256,m=5,r=4,be1=7,be2=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=iq4_nl,n=256,m=5,r=4,be1=1,be2=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=iq4_nl,n=256,m=5,r=4,be1=1,be2=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=iq4_nl,n=256,m=5,r=4,be1=7,be2=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=iq4_nl,n=256,m=5,r=4,be1=7,be2=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=iq3_s,n=256,m=5,r=4,be1=1,be2=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=iq3_s,n=256,m=5,r=4,be1=1,be2=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=iq3_s,n=256,m=5,r=4,be1=7,be2=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=iq3_s,n=256,m=5,r=4,be1=7,be2=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=iq4_xs,n=256,m=5,r=4,be1=1,be2=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=iq4_xs,n=256,m=5,r=4,be1=1,be2=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=iq4_xs,n=256,m=5,r=4,be1=7,be2=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=iq4_xs,n=256,m=5,r=4,be1=7,be2=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=i32,n=256,m=5,r=4,be1=1,be2=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=i32,n=256,m=5,r=4,be1=1,be2=1,v=1): not supported [SYCL0] 
  GET_ROWS(type=i32,n=256,m=5,r=4,be1=7,be2=1,v=0): not supported [SYCL0] 
  GET_ROWS(type=i32,n=256,m=5,r=4,be1=7,be2=1,v=1): not supported [SYCL0] 
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
  GET_ROWS_BACK(type=mxfp4,n=256,m=5,r=4,b=1,v=0): not supported [SYCL0] 
  GET_ROWS_BACK(type=mxfp4,n=256,m=5,r=4,b=1,v=1): not supported [SYCL0] 
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
  SET_ROWS(type=f32,type_idx=i64,ne=[1,8,1,3],nr23=[1,1],r=2,v=0): [1;32mOK[0m
  SET_ROWS(type=f32,type_idx=i32,ne=[1,8,1,3],nr23=[1,1],r=2,v=0): [1;32mOK[0m
  SET_ROWS(type=q8_0,type_idx=i32,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): [1;32mOK[0m
  SET_ROWS(type=f32,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): [1;32mOK[0m
  SET_ROWS(type=f32,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=0): [1;32mOK[0m
  SET_ROWS(type=f32,type_idx=i64,ne=[3,3,1,1],nr23=[2,3],r=2,v=0): [1;32mOK[0m
  SET_ROWS(type=f32,type_idx=i64,ne=[31,3,1,1],nr23=[2,3],r=2,v=0): [1;32mOK[0m
  SET_ROWS(type=f32,type_idx=i64,ne=[33,5,1,1],nr23=[2,3],r=1,v=0): [1;32mOK[0m
  SET_ROWS(type=f32,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=1): [1;32mOK[0m
  SET_ROWS(type=f32,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=1): [1;32mOK[0m
  SET_ROWS(type=f32,type_idx=i64,ne=[3,3,1,1],nr23=[2,3],r=2,v=1): [1;32mOK[0m
  SET_ROWS(type=f32,type_idx=i64,ne=[31,3,1,1],nr23=[2,3],r=2,v=1): [1;32mOK[0m
  SET_ROWS(type=f32,type_idx=i64,ne=[33,5,1,1],nr23=[2,3],r=1,v=1): [1;32mOK[0m
  SET_ROWS(type=f32,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=0): [1;32mOK[0m
  SET_ROWS(type=f32,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=0): [1;32mOK[0m
  SET_ROWS(type=f32,type_idx=i64,ne=[3,3,7,1],nr23=[2,3],r=2,v=0): [1;32mOK[0m
  SET_ROWS(type=f32,type_idx=i64,ne=[31,3,7,1],nr23=[2,3],r=2,v=0): [1;32mOK[0m
  SET_ROWS(type=f32,type_idx=i64,ne=[33,5,1,7],nr23=[2,3],r=1,v=0): [1;32mOK[0m
  SET_ROWS(type=f32,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=1): [1;32mOK[0m
  SET_ROWS(type=f32,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=1): [1;32mOK[0m
  SET_ROWS(type=f32,type_idx=i64,ne=[3,3,7,1],nr23=[2,3],r=2,v=1): [1;32mOK[0m
  SET_ROWS(type=f32,type_idx=i64,ne=[31,3,7,1],nr23=[2,3],r=2,v=1): [1;32mOK[0m
  SET_ROWS(type=f32,type_idx=i64,ne=[33,5,1,7],nr23=[2,3],r=1,v=1): [1;32mOK[0m
  SET_ROWS(type=f16,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): [1;32mOK[0m
  SET_ROWS(type=f16,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=0): [1;32mOK[0m
  SET_ROWS(type=f16,type_idx=i64,ne=[3,3,1,1],nr23=[2,3],r=2,v=0): [1;32mOK[0m
  SET_ROWS(type=f16,type_idx=i64,ne=[31,3,1,1],nr23=[2,3],r=2,v=0): [1;32mOK[0m
  SET_ROWS(type=f16,type_idx=i64,ne=[33,5,1,1],nr23=[2,3],r=1,v=0): [1;32mOK[0m
  SET_ROWS(type=f16,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=1): [1;32mOK[0m
  SET_ROWS(type=f16,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=1): [1;32mOK[0m
  SET_ROWS(type=f16,type_idx=i64,ne=[3,3,1,1],nr23=[2,3],r=2,v=1): [1;32mOK[0m
  SET_ROWS(type=f16,type_idx=i64,ne=[31,3,1,1],nr23=[2,3],r=2,v=1): [1;32mOK[0m
  SET_ROWS(type=f16,type_idx=i64,ne=[33,5,1,1],nr23=[2,3],r=1,v=1): [1;32mOK[0m
  SET_ROWS(type=f16,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=0): [1;32mOK[0m
  SET_ROWS(type=f16,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=0): [1;32mOK[0m
  SET_ROWS(type=f16,type_idx=i64,ne=[3,3,7,1],nr23=[2,3],r=2,v=0): [1;32mOK[0m
  SET_ROWS(type=f16,type_idx=i64,ne=[31,3,7,1],nr23=[2,3],r=2,v=0): [1;32mOK[0m
  SET_ROWS(type=f16,type_idx=i64,ne=[33,5,1,7],nr23=[2,3],r=1,v=0): [1;32mOK[0m
  SET_ROWS(type=f16,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=1): [1;32mOK[0m
  SET_ROWS(type=f16,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=1): [1;32mOK[0m
  SET_ROWS(type=f16,type_idx=i64,ne=[3,3,7,1],nr23=[2,3],r=2,v=1): [1;32mOK[0m
  SET_ROWS(type=f16,type_idx=i64,ne=[31,3,7,1],nr23=[2,3],r=2,v=1): [1;32mOK[0m
  SET_ROWS(type=f16,type_idx=i64,ne=[33,5,1,7],nr23=[2,3],r=1,v=1): [1;32mOK[0m
  SET_ROWS(type=bf16,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): [1;32mOK[0m
  SET_ROWS(type=bf16,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=0): [1;32mOK[0m
  SET_ROWS(type=bf16,type_idx=i64,ne=[3,3,1,1],nr23=[2,3],r=2,v=0): [1;32mOK[0m
  SET_ROWS(type=bf16,type_idx=i64,ne=[31,3,1,1],nr23=[2,3],r=2,v=0): [1;32mOK[0m
  SET_ROWS(type=bf16,type_idx=i64,ne=[33,5,1,1],nr23=[2,3],r=1,v=0): [1;32mOK[0m
  SET_ROWS(type=bf16,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=1): [1;32mOK[0m
  SET_ROWS(type=bf16,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=1): [1;32mOK[0m
  SET_ROWS(type=bf16,type_idx=i64,ne=[3,3,1,1],nr23=[2,3],r=2,v=1): [1;32mOK[0m
  SET_ROWS(type=bf16,type_idx=i64,ne=[31,3,1,1],nr23=[2,3],r=2,v=1): [1;32mOK[0m
  SET_ROWS(type=bf16,type_idx=i64,ne=[33,5,1,1],nr23=[2,3],r=1,v=1): [1;32mOK[0m
  SET_ROWS(type=bf16,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=0): [1;32mOK[0m
  SET_ROWS(type=bf16,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=0): [1;32mOK[0m
  SET_ROWS(type=bf16,type_idx=i64,ne=[3,3,7,1],nr23=[2,3],r=2,v=0): [1;32mOK[0m
  SET_ROWS(type=bf16,type_idx=i64,ne=[31,3,7,1],nr23=[2,3],r=2,v=0): [1;32mOK[0m
  SET_ROWS(type=bf16,type_idx=i64,ne=[33,5,1,7],nr23=[2,3],r=1,v=0): [1;32mOK[0m
  SET_ROWS(type=bf16,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=1): [1;32mOK[0m
  SET_ROWS(type=bf16,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=1): [1;32mOK[0m
  SET_ROWS(type=bf16,type_idx=i64,ne=[3,3,7,1],nr23=[2,3],r=2,v=1): [1;32mOK[0m
  SET_ROWS(type=bf16,type_idx=i64,ne=[31,3,7,1],nr23=[2,3],r=2,v=1): [1;32mOK[0m
  SET_ROWS(type=bf16,type_idx=i64,ne=[33,5,1,7],nr23=[2,3],r=1,v=1): [1;32mOK[0m
  SET_ROWS(type=q4_0,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): [1;32mOK[0m
  SET_ROWS(type=q4_0,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=0): [1;32mOK[0m
  SET_ROWS(type=q4_0,type_idx=i64,ne=[96,3,1,1],nr23=[2,3],r=2,v=0): [1;32mOK[0m
  SET_ROWS(type=q4_0,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=1): [1;32mOK[0m
  SET_ROWS(type=q4_0,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=1): [1;32mOK[0m
  SET_ROWS(type=q4_0,type_idx=i64,ne=[96,3,1,1],nr23=[2,3],r=2,v=1): [1;32mOK[0m
  SET_ROWS(type=q4_0,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=0): [1;32mOK[0m
  SET_ROWS(type=q4_0,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=0): [1;32mOK[0m
  SET_ROWS(type=q4_0,type_idx=i64,ne=[96,3,7,1],nr23=[2,3],r=2,v=0): [1;32mOK[0m
  SET_ROWS(type=q4_0,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=1): [1;32mOK[0m
  SET_ROWS(type=q4_0,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=1): [1;32mOK[0m
  SET_ROWS(type=q4_0,type_idx=i64,ne=[96,3,7,1],nr23=[2,3],r=2,v=1): [1;32mOK[0m
  SET_ROWS(type=q4_1,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): [1;32mOK[0m
  SET_ROWS(type=q4_1,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=0): [1;32mOK[0m
  SET_ROWS(type=q4_1,type_idx=i64,ne=[96,3,1,1],nr23=[2,3],r=2,v=0): [1;32mOK[0m
  SET_ROWS(type=q4_1,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=1): [1;32mOK[0m
  SET_ROWS(type=q4_1,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=1): [1;32mOK[0m
  SET_ROWS(type=q4_1,type_idx=i64,ne=[96,3,1,1],nr23=[2,3],r=2,v=1): [1;32mOK[0m
  SET_ROWS(type=q4_1,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=0): [1;32mOK[0m
  SET_ROWS(type=q4_1,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=0): [1;32mOK[0m
  SET_ROWS(type=q4_1,type_idx=i64,ne=[96,3,7,1],nr23=[2,3],r=2,v=0): [1;32mOK[0m
  SET_ROWS(type=q4_1,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=1): [1;32mOK[0m
  SET_ROWS(type=q4_1,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=1): [1;32mOK[0m
  SET_ROWS(type=q4_1,type_idx=i64,ne=[96,3,7,1],nr23=[2,3],r=2,v=1): [1;32mOK[0m
  SET_ROWS(type=q5_0,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): [1;32mOK[0m
  SET_ROWS(type=q5_0,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=0): [1;32mOK[0m
  SET_ROWS(type=q5_0,type_idx=i64,ne=[96,3,1,1],nr23=[2,3],r=2,v=0): [1;32mOK[0m
  SET_ROWS(type=q5_0,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=1): [1;32mOK[0m
  SET_ROWS(type=q5_0,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=1): [1;32mOK[0m
  SET_ROWS(type=q5_0,type_idx=i64,ne=[96,3,1,1],nr23=[2,3],r=2,v=1): [1;32mOK[0m
  SET_ROWS(type=q5_0,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=0): [1;32mOK[0m
  SET_ROWS(type=q5_0,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=0): [1;32mOK[0m
  SET_ROWS(type=q5_0,type_idx=i64,ne=[96,3,7,1],nr23=[2,3],r=2,v=0): [1;32mOK[0m
  SET_ROWS(type=q5_0,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=1): [1;32mOK[0m
  SET_ROWS(type=q5_0,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=1): [1;32mOK[0m
  SET_ROWS(type=q5_0,type_idx=i64,ne=[96,3,7,1],nr23=[2,3],r=2,v=1): [1;32mOK[0m
  SET_ROWS(type=q5_1,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): [1;32mOK[0m
  SET_ROWS(type=q5_1,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=0): [1;32mOK[0m
  SET_ROWS(type=q5_1,type_idx=i64,ne=[96,3,1,1],nr23=[2,3],r=2,v=0): [1;32mOK[0m
  SET_ROWS(type=q5_1,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=1): [1;32mOK[0m
  SET_ROWS(type=q5_1,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=1): [1;32mOK[0m
  SET_ROWS(type=q5_1,type_idx=i64,ne=[96,3,1,1],nr23=[2,3],r=2,v=1): [1;32mOK[0m
  SET_ROWS(type=q5_1,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=0): [1;32mOK[0m
  SET_ROWS(type=q5_1,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=0): [1;32mOK[0m
  SET_ROWS(type=q5_1,type_idx=i64,ne=[96,3,7,1],nr23=[2,3],r=2,v=0): [1;32mOK[0m
  SET_ROWS(type=q5_1,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=1): [1;32mOK[0m
  SET_ROWS(type=q5_1,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=1): [1;32mOK[0m
  SET_ROWS(type=q5_1,type_idx=i64,ne=[96,3,7,1],nr23=[2,3],r=2,v=1): [1;32mOK[0m
  SET_ROWS(type=q8_0,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): [1;32mOK[0m
  SET_ROWS(type=q8_0,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=0): [1;32mOK[0m
  SET_ROWS(type=q8_0,type_idx=i64,ne=[96,3,1,1],nr23=[2,3],r=2,v=0): [1;32mOK[0m
  SET_ROWS(type=q8_0,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=1): [1;32mOK[0m
  SET_ROWS(type=q8_0,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=1): [1;32mOK[0m
  SET_ROWS(type=q8_0,type_idx=i64,ne=[96,3,1,1],nr23=[2,3],r=2,v=1): [1;32mOK[0m
  SET_ROWS(type=q8_0,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=0): [1;32mOK[0m
  SET_ROWS(type=q8_0,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=0): [1;32mOK[0m
  SET_ROWS(type=q8_0,type_idx=i64,ne=[96,3,7,1],nr23=[2,3],r=2,v=0): [1;32mOK[0m
  SET_ROWS(type=q8_0,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=1): [1;32mOK[0m
  SET_ROWS(type=q8_0,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=1): [1;32mOK[0m
  SET_ROWS(type=q8_0,type_idx=i64,ne=[96,3,7,1],nr23=[2,3],r=2,v=1): [1;32mOK[0m
  SET_ROWS(type=mxfp4,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=mxfp4,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=mxfp4,type_idx=i64,ne=[96,3,1,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=mxfp4,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=mxfp4,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=mxfp4,type_idx=i64,ne=[96,3,1,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=mxfp4,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=mxfp4,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=mxfp4,type_idx=i64,ne=[96,3,7,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=mxfp4,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=mxfp4,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=mxfp4,type_idx=i64,ne=[96,3,7,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=q2_K,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=q2_K,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=q2_K,type_idx=i64,ne=[768,3,1,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=q2_K,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=q2_K,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=q2_K,type_idx=i64,ne=[768,3,1,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=q2_K,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=q2_K,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=q2_K,type_idx=i64,ne=[768,3,7,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=q2_K,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=q2_K,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=q2_K,type_idx=i64,ne=[768,3,7,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=q3_K,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=q3_K,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=q3_K,type_idx=i64,ne=[768,3,1,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=q3_K,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=q3_K,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=q3_K,type_idx=i64,ne=[768,3,1,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=q3_K,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=q3_K,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=q3_K,type_idx=i64,ne=[768,3,7,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=q3_K,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=q3_K,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=q3_K,type_idx=i64,ne=[768,3,7,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=q4_K,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=q4_K,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=q4_K,type_idx=i64,ne=[768,3,1,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=q4_K,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=q4_K,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=q4_K,type_idx=i64,ne=[768,3,1,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=q4_K,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=q4_K,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=q4_K,type_idx=i64,ne=[768,3,7,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=q4_K,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=q4_K,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=q4_K,type_idx=i64,ne=[768,3,7,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=q5_K,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=q5_K,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=q5_K,type_idx=i64,ne=[768,3,1,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=q5_K,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=q5_K,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=q5_K,type_idx=i64,ne=[768,3,1,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=q5_K,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=q5_K,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=q5_K,type_idx=i64,ne=[768,3,7,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=q5_K,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=q5_K,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=q5_K,type_idx=i64,ne=[768,3,7,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=q6_K,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=q6_K,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=q6_K,type_idx=i64,ne=[768,3,1,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=q6_K,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=q6_K,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=q6_K,type_idx=i64,ne=[768,3,1,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=q6_K,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=q6_K,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=q6_K,type_idx=i64,ne=[768,3,7,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=q6_K,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=q6_K,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=q6_K,type_idx=i64,ne=[768,3,7,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq2_xxs,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq2_xxs,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq2_xxs,type_idx=i64,ne=[768,3,1,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq2_xxs,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq2_xxs,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq2_xxs,type_idx=i64,ne=[768,3,1,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq2_xxs,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq2_xxs,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq2_xxs,type_idx=i64,ne=[768,3,7,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq2_xxs,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq2_xxs,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq2_xxs,type_idx=i64,ne=[768,3,7,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq2_xs,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq2_xs,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq2_xs,type_idx=i64,ne=[768,3,1,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq2_xs,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq2_xs,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq2_xs,type_idx=i64,ne=[768,3,1,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq2_xs,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq2_xs,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq2_xs,type_idx=i64,ne=[768,3,7,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq2_xs,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq2_xs,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq2_xs,type_idx=i64,ne=[768,3,7,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq2_s,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq2_s,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq2_s,type_idx=i64,ne=[768,3,1,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq2_s,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq2_s,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq2_s,type_idx=i64,ne=[768,3,1,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq2_s,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq2_s,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq2_s,type_idx=i64,ne=[768,3,7,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq2_s,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq2_s,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq2_s,type_idx=i64,ne=[768,3,7,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq3_xxs,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq3_xxs,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq3_xxs,type_idx=i64,ne=[768,3,1,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq3_xxs,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq3_xxs,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq3_xxs,type_idx=i64,ne=[768,3,1,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq3_xxs,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq3_xxs,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq3_xxs,type_idx=i64,ne=[768,3,7,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq3_xxs,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq3_xxs,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq3_xxs,type_idx=i64,ne=[768,3,7,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq1_s,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq1_s,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq1_s,type_idx=i64,ne=[768,3,1,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq1_s,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq1_s,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq1_s,type_idx=i64,ne=[768,3,1,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq1_s,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq1_s,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq1_s,type_idx=i64,ne=[768,3,7,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq1_s,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq1_s,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq1_s,type_idx=i64,ne=[768,3,7,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq1_m,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq1_m,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq1_m,type_idx=i64,ne=[768,3,1,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq1_m,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq1_m,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq1_m,type_idx=i64,ne=[768,3,1,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq1_m,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq1_m,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq1_m,type_idx=i64,ne=[768,3,7,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq1_m,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq1_m,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq1_m,type_idx=i64,ne=[768,3,7,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq4_nl,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): [1;32mOK[0m
  SET_ROWS(type=iq4_nl,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=0): [1;32mOK[0m
  SET_ROWS(type=iq4_nl,type_idx=i64,ne=[96,3,1,1],nr23=[2,3],r=2,v=0): [1;32mOK[0m
  SET_ROWS(type=iq4_nl,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=1): [1;32mOK[0m
  SET_ROWS(type=iq4_nl,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=1): [1;32mOK[0m
  SET_ROWS(type=iq4_nl,type_idx=i64,ne=[96,3,1,1],nr23=[2,3],r=2,v=1): [1;32mOK[0m
  SET_ROWS(type=iq4_nl,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=0): [1;32mOK[0m
  SET_ROWS(type=iq4_nl,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=0): [1;32mOK[0m
  SET_ROWS(type=iq4_nl,type_idx=i64,ne=[96,3,7,1],nr23=[2,3],r=2,v=0): [1;32mOK[0m
  SET_ROWS(type=iq4_nl,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=1): [1;32mOK[0m
  SET_ROWS(type=iq4_nl,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=1): [1;32mOK[0m
  SET_ROWS(type=iq4_nl,type_idx=i64,ne=[96,3,7,1],nr23=[2,3],r=2,v=1): [1;32mOK[0m
  SET_ROWS(type=iq3_s,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq3_s,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq3_s,type_idx=i64,ne=[768,3,1,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq3_s,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq3_s,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq3_s,type_idx=i64,ne=[768,3,1,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq3_s,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq3_s,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq3_s,type_idx=i64,ne=[768,3,7,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq3_s,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq3_s,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq3_s,type_idx=i64,ne=[768,3,7,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq4_xs,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq4_xs,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq4_xs,type_idx=i64,ne=[768,3,1,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq4_xs,type_idx=i64,ne=[256,5,1,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq4_xs,type_idx=i64,ne=[256,11,1,1],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq4_xs,type_idx=i64,ne=[768,3,1,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq4_xs,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq4_xs,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq4_xs,type_idx=i64,ne=[768,3,7,1],nr23=[2,3],r=2,v=0): not supported [SYCL0] 
  SET_ROWS(type=iq4_xs,type_idx=i64,ne=[256,5,7,3],nr23=[1,1],r=1,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq4_xs,type_idx=i64,ne=[256,11,1,7],nr23=[2,3],r=7,v=1): not supported [SYCL0] 
  SET_ROWS(type=iq4_xs,type_idx=i64,ne=[768,3,7,1],nr23=[2,3],r=2,v=1): not supported [SYCL0] 
  ROPE_SET_ROWS(type=f16,type_idx=i64,ne_a=[128,32,1,1],mode=0): [1;32mOK[0m
  ROPE_SET_ROWS(type=f16,type_idx=i64,ne_a=[128,32,1,3],mode=0): [1;32mOK[0m
  ROPE_SET_ROWS(type=f16,type_idx=i64,ne_a=[128,32,8,1],mode=0): [1;32mOK[0m
  ROPE_SET_ROWS(type=f16,type_idx=i64,ne_a=[128,32,8,3],mode=0): [1;32mOK[0m
  ROPE_SET_ROWS(type=f16,type_idx=i64,ne_a=[128,32,512,1],mode=0): [1;32mOK[0m
  ROPE_SET_ROWS(type=f16,type_idx=i64,ne_a=[128,32,512,3],mode=0): [1;32mOK[0m
  ROPE_SET_ROWS(type=f32,type_idx=i64,ne_a=[128,32,1,1],mode=0): [1;32mOK[0m
  ROPE_SET_ROWS(type=f32,type_idx=i64,ne_a=[128,32,1,3],mode=0): [1;32mOK[0m
  ROPE_SET_ROWS(type=f32,type_idx=i64,ne_a=[128,32,8,1],mode=0): [1;32mOK[0m
  ROPE_SET_ROWS(type=f32,type_idx=i64,ne_a=[128,32,8,3],mode=0): [1;32mOK[0m
  ROPE_SET_ROWS(type=f32,type_idx=i64,ne_a=[128,32,512,1],mode=0): [1;32mOK[0m
  ROPE_SET_ROWS(type=f32,type_idx=i64,ne_a=[128,32,512,3],mode=0): [1;32mOK[0m
  ROPE_SET_ROWS(type=f16,type_idx=i64,ne_a=[128,32,1,1],mode=2): [1;32mOK[0m
  ROPE_SET_ROWS(type=f16,type_idx=i64,ne_a=[128,32,1,3],mode=2): [1;32mOK[0m
  ROPE_SET_ROWS(type=f16,type_idx=i64,ne_a=[128,32,8,1],mode=2): [1;32mOK[0m
  ROPE_SET_ROWS(type=f16,type_idx=i64,ne_a=[128,32,8,3],mode=2): [1;32mOK[0m
  ROPE_SET_ROWS(type=f16,type_idx=i64,ne_a=[128,32,512,1],mode=2): [1;32mOK[0m
  ROPE_SET_ROWS(type=f16,type_idx=i64,ne_a=[128,32,512,3],mode=2): [1;32mOK[0m
  ROPE_SET_ROWS(type=f32,type_idx=i64,ne_a=[128,32,1,1],mode=2): [1;32mOK[0m
  ROPE_SET_ROWS(type=f32,type_idx=i64,ne_a=[128,32,1,3],mode=2): [1;32mOK[0m
  ROPE_SET_ROWS(type=f32,type_idx=i64,ne_a=[128,32,8,1],mode=2): [1;32mOK[0m
  ROPE_SET_ROWS(type=f32,type_idx=i64,ne_a=[128,32,8,3],mode=2): [1;32mOK[0m
  ROPE_SET_ROWS(type=f32,type_idx=i64,ne_a=[128,32,512,1],mode=2): [1;32mOK[0m
  ROPE_SET_ROWS(type=f32,type_idx=i64,ne_a=[128,32,512,3],mode=2): [1;32mOK[0m
  ROPE_SET_ROWS(type=f16,type_idx=i64,ne_a=[128,32,1,1],mode=8): [1;32mOK[0m
  ROPE_SET_ROWS(type=f16,type_idx=i64,ne_a=[128,32,1,3],mode=8): [1;32mOK[0m
  ROPE_SET_ROWS(type=f16,type_idx=i64,ne_a=[128,32,8,1],mode=8): [1;32mOK[0m
  ROPE_SET_ROWS(type=f16,type_idx=i64,ne_a=[128,32,8,3],mode=8): [1;32mOK[0m
  ROPE_SET_ROWS(type=f16,type_idx=i64,ne_a=[128,32,512,1],mode=8): [1;32mOK[0m
  ROPE_SET_ROWS(type=f16,type_idx=i64,ne_a=[128,32,512,3],mode=8): [1;32mOK[0m
  ROPE_SET_ROWS(type=f32,type_idx=i64,ne_a=[128,32,1,1],mode=8): [1;32mOK[0m
  ROPE_SET_ROWS(type=f32,type_idx=i64,ne_a=[128,32,1,3],mode=8): [1;32mOK[0m
  ROPE_SET_ROWS(type=f32,type_idx=i64,ne_a=[128,32,8,1],mode=8): [1;32mOK[0m
  ROPE_SET_ROWS(type=f32,type_idx=i64,ne_a=[128,32,8,3],mode=8): [1;32mOK[0m
  ROPE_SET_ROWS(type=f32,type_idx=i64,ne_a=[128,32,512,1],mode=8): [1;32mOK[0m
  ROPE_SET_ROWS(type=f32,type_idx=i64,ne_a=[128,32,512,3],mode=8): [1;32mOK[0m
  ROPE_SET_ROWS(type=f16,type_idx=i64,ne_a=[128,32,1,1],mode=24): [1;32mOK[0m
  ROPE_SET_ROWS(type=f16,type_idx=i64,ne_a=[128,32,1,3],mode=24): [1;32mOK[0m
  ROPE_SET_ROWS(type=f16,type_idx=i64,ne_a=[128,32,8,1],mode=24): [1;32mOK[0m
  ROPE_SET_ROWS(type=f16,type_idx=i64,ne_a=[128,32,8,3],mode=24): [1;32mOK[0m
  ROPE_SET_ROWS(type=f16,type_idx=i64,ne_a=[128,32,512,1],mode=24): [1;32mOK[0m
  ROPE_SET_ROWS(type=f16,type_idx=i64,ne_a=[128,32,512,3],mode=24): [1;32mOK[0m
  ROPE_SET_ROWS(type=f32,type_idx=i64,ne_a=[128,32,1,1],mode=24): [1;32mOK[0m
  ROPE_SET_ROWS(type=f32,type_idx=i64,ne_a=[128,32,1,3],mode=24): [1;32mOK[0m
  ROPE_SET_ROWS(type=f32,type_idx=i64,ne_a=[128,32,8,1],mode=24): [1;32mOK[0m
  ROPE_SET_ROWS(type=f32,type_idx=i64,ne_a=[128,32,8,3],mode=24): [1;32mOK[0m
  ROPE_SET_ROWS(type=f32,type_idx=i64,ne_a=[128,32,512,1],mode=24): [1;32mOK[0m
  ROPE_SET_ROWS(type=f32,type_idx=i64,ne_a=[128,32,512,3],mode=24): [1;32mOK[0m
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
  POOL_1D(pool_type=avg,type_input=f32,ne_input=[10,3,2,1],k0=1,s0=1,p0=0): not supported [SYCL0] 
  POOL_1D(pool_type=avg,type_input=f32,ne_input=[11,1,3,2],k0=1,s0=1,p0=0): not supported [SYCL0] 
  POOL_1D(pool_type=avg,type_input=f32,ne_input=[128,2,1,3],k0=1,s0=1,p0=0): not supported [SYCL0] 
  POOL_1D(pool_type=avg,type_input=f32,ne_input=[10,3,2,1],k0=1,s0=1,p0=1): not supported [SYCL0] 
  POOL_1D(pool_type=avg,type_input=f32,ne_input=[11,1,3,2],k0=1,s0=1,p0=1): not supported [SYCL0] 
  POOL_1D(pool_type=avg,type_input=f32,ne_input=[128,2,1,3],k0=1,s0=1,p0=1): not supported [SYCL0] 
  POOL_1D(pool_type=avg,type_input=f32,ne_input=[10,3,2,1],k0=1,s0=2,p0=0): not supported [SYCL0] 
  POOL_1D(pool_type=avg,type_input=f32,ne_input=[11,1,3,2],k0=1,s0=2,p0=0): not supported [SYCL0] 
  POOL_1D(pool_type=avg,type_input=f32,ne_input=[128,2,1,3],k0=1,s0=2,p0=0): not supported [SYCL0] 
  POOL_1D(pool_type=avg,type_input=f32,ne_input=[10,3,2,1],k0=1,s0=2,p0=1): not supported [SYCL0] 
  POOL_1D(pool_type=avg,type_input=f32,ne_input=[11,1,3,2],k0=1,s0=2,p0=1): not supported [SYCL0] 
  POOL_1D(pool_type=avg,type_input=f32,ne_input=[128,2,1,3],k0=1,s0=2,p0=1): not supported [SYCL0] 
  POOL_1D(pool_type=avg,type_input=f32,ne_input=[10,3,2,1],k0=3,s0=1,p0=0): not supported [SYCL0] 
  POOL_1D(pool_type=avg,type_input=f32,ne_input=[11,1,3,2],k0=3,s0=1,p0=0): not supported [SYCL0] 
  POOL_1D(pool_type=avg,type_input=f32,ne_input=[128,2,1,3],k0=3,s0=1,p0=0): not supported [SYCL0] 
  POOL_1D(pool_type=avg,type_input=f32,ne_input=[10,3,2,1],k0=3,s0=1,p0=1): not supported [SYCL0] 
  POOL_1D(pool_type=avg,type_input=f32,ne_input=[11,1,3,2],k0=3,s0=1,p0=1): not supported [SYCL0] 
  POOL_1D(pool_type=avg,type_input=f32,ne_input=[128,2,1,3],k0=3,s0=1,p0=1): not supported [SYCL0] 
  POOL_1D(pool_type=avg,type_input=f32,ne_input=[10,3,2,1],k0=3,s0=2,p0=0): not supported [SYCL0] 
  POOL_1D(pool_type=avg,type_input=f32,ne_input=[11,1,3,2],k0=3,s0=2,p0=0): not supported [SYCL0] 
  POOL_1D(pool_type=avg,type_input=f32,ne_input=[128,2,1,3],k0=3,s0=2,p0=0): not supported [SYCL0] 
  POOL_1D(pool_type=avg,type_input=f32,ne_input=[10,3,2,1],k0=3,s0=2,p0=1): not supported [SYCL0] 
  POOL_1D(pool_type=avg,type_input=f32,ne_input=[11,1,3,2],k0=3,s0=2,p0=1): not supported [SYCL0] 
  POOL_1D(pool_type=avg,type_input=f32,ne_input=[128,2,1,3],k0=3,s0=2,p0=1): not supported [SYCL0] 
  POOL_1D(pool_type=max,type_input=f32,ne_input=[10,3,2,1],k0=1,s0=1,p0=0): not supported [SYCL0] 
  POOL_1D(pool_type=max,type_input=f32,ne_input=[11,1,3,2],k0=1,s0=1,p0=0): not supported [SYCL0] 
  POOL_1D(pool_type=max,type_input=f32,ne_input=[128,2,1,3],k0=1,s0=1,p0=0): not supported [SYCL0] 
  POOL_1D(pool_type=max,type_input=f32,ne_input=[10,3,2,1],k0=1,s0=1,p0=1): not supported [SYCL0] 
  POOL_1D(pool_type=max,type_input=f32,ne_input=[11,1,3,2],k0=1,s0=1,p0=1): not supported [SYCL0] 
  POOL_1D(pool_type=max,type_input=f32,ne_input=[128,2,1,3],k0=1,s0=1,p0=1): not supported [SYCL0] 
  POOL_1D(pool_type=max,type_input=f32,ne_input=[10,3,2,1],k0=1,s0=2,p0=0): not supported [SYCL0] 
  POOL_1D(pool_type=max,type_input=f32,ne_input=[11,1,3,2],k0=1,s0=2,p0=0): not supported [SYCL0] 
  POOL_1D(pool_type=max,type_input=f32,ne_input=[128,2,1,3],k0=1,s0=2,p0=0): not supported [SYCL0] 
  POOL_1D(pool_type=max,type_input=f32,ne_input=[10,3,2,1],k0=1,s0=2,p0=1): not supported [SYCL0] 
  POOL_1D(pool_type=max,type_input=f32,ne_input=[11,1,3,2],k0=1,s0=2,p0=1): not supported [SYCL0] 
  POOL_1D(pool_type=max,type_input=f32,ne_input=[128,2,1,3],k0=1,s0=2,p0=1): not supported [SYCL0] 
  POOL_1D(pool_type=max,type_input=f32,ne_input=[10,3,2,1],k0=3,s0=1,p0=0): not supported [SYCL0] 
  POOL_1D(pool_type=max,type_input=f32,ne_input=[11,1,3,2],k0=3,s0=1,p0=0): not supported [SYCL0] 
  POOL_1D(pool_type=max,type_input=f32,ne_input=[128,2,1,3],k0=3,s0=1,p0=0): not supported [SYCL0] 
  POOL_1D(pool_type=max,type_input=f32,ne_input=[10,3,2,1],k0=3,s0=1,p0=1): not supported [SYCL0] 
  POOL_1D(pool_type=max,type_input=f32,ne_input=[11,1,3,2],k0=3,s0=1,p0=1): not supported [SYCL0] 
  POOL_1D(pool_type=max,type_input=f32,ne_input=[128,2,1,3],k0=3,s0=1,p0=1): not supported [SYCL0] 
  POOL_1D(pool_type=max,type_input=f32,ne_input=[10,3,2,1],k0=3,s0=2,p0=0): not supported [SYCL0] 
  POOL_1D(pool_type=max,type_input=f32,ne_input=[11,1,3,2],k0=3,s0=2,p0=0): not supported [SYCL0] 
  POOL_1D(pool_type=max,type_input=f32,ne_input=[128,2,1,3],k0=3,s0=2,p0=0): not supported [SYCL0] 
  POOL_1D(pool_type=max,type_input=f32,ne_input=[10,3,2,1],k0=3,s0=2,p0=1): not supported [SYCL0] 
  POOL_1D(pool_type=max,type_input=f32,ne_input=[11,1,3,2],k0=3,s0=2,p0=1): not supported [SYCL0] 
  POOL_1D(pool_type=max,type_input=f32,ne_input=[128,2,1,3],k0=3,s0=2,p0=1): not supported [SYCL0] 
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
  IM2COL(type_input=f32,type_kernel=f16,dst_type=f16,ne_input=[5,5,1,32],ne_kernel=[3,4,1,32],s0=1,s1=1,p0=0,p1=0,d0=1,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[2,2,1536,729],ne_kernel=[2,2,1536,4096],s0=1,s1=1,p0=0,p1=0,d0=1,d1=1,is_2D=1): [1;32mOK[0m
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[10,10,10,9],ne_kernel=[3,3,3,1],IC=3,s0=1,s1=1,s2=1,p0=1,p1=1,p2=1,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f16,dst_type=f32,ne_input=[10,10,10,9],ne_kernel=[3,3,3,1],IC=3,s0=1,s1=1,s2=1,p0=1,p1=1,p2=1,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f16,dst_type=f16,ne_input=[10,10,10,9],ne_kernel=[3,3,3,1],IC=3,s0=1,s1=1,s2=1,p0=1,p1=1,p2=1,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=0,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=0,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=0,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=0,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=0,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=0,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=0,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=0,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=0,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=0,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=0,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=0,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=0,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=0,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=0,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=0,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=3,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=3,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=3,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=3,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=3,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=3,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=3,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=3,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=3,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=3,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=3,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=3,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=3,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=3,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=3,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=3,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=3,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=3,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=3,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=3,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=3,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=3,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=3,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=3,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=3,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=3,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=3,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=3,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=3,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=3,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=3,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=3,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=3,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=3,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=3,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=3,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=3,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=3,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=3,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=3,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=3,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=3,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=3,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=3,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=3,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=3,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=3,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=3,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=3,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=3,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=3,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=3,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=3,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=3,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=3,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=3,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=3,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=3,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=3,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=3,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=3,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=0,p1=3,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=3,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=0,p1=3,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=0,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=0,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=0,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=0,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=0,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=0,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=0,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=0,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=0,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=0,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=0,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=0,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=0,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=0,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=0,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=0,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=0,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=0,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=0,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=0,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=0,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=0,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=0,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=0,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=0,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=0,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=0,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=0,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=0,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=0,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=0,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=0,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=0,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=0,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=0,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=0,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=0,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=0,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=0,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=0,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=0,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=0,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=0,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=0,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=0,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=0,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=0,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=0,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=0,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=0,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=0,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=0,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=0,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=0,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=0,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=0,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=0,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=0,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=0,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=0,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=0,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=0,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=0,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=0,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=3,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=3,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=3,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=3,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=3,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=3,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=3,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=3,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=3,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=3,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=3,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=3,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=3,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=3,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=3,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=3,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=3,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=3,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=3,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=3,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=3,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=3,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=3,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=3,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=3,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=3,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=3,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=3,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=3,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=3,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=3,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=3,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=3,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=3,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=3,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=3,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=3,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=3,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=3,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=3,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=3,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=3,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=3,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=3,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=3,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=3,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=3,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=3,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=3,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=3,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=3,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=3,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=3,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=3,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=3,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=3,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=3,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=3,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=3,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=3,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=3,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=1,p0=3,p1=3,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=3,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=1,p0=3,p1=3,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=0,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=0,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=0,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=0,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=0,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=0,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=0,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=0,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=0,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=0,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=0,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=0,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=0,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=0,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=0,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=0,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=0,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=0,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=0,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=0,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=0,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=0,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=0,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=0,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=0,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=0,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=0,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=0,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=0,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=0,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=0,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=0,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=0,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=0,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=0,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=0,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=0,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=0,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=0,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=0,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=0,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=0,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=0,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=0,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=0,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=0,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=0,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=0,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=0,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=0,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=0,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=0,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=0,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=0,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=0,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=0,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=0,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=0,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=0,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=0,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=3,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=3,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=3,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=3,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=3,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=3,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=3,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=3,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=3,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=3,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=3,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=3,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=3,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=3,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=3,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=3,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=3,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=3,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=3,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=3,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=3,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=3,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=3,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=3,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=3,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=3,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=3,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=3,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=3,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=3,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=3,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=3,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=3,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=3,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=3,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=3,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=3,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=3,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=3,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=3,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=3,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=3,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=3,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=3,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=3,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=3,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=3,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=3,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=3,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=3,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=3,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=3,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=3,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=3,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=3,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=3,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=3,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=3,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=3,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=3,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=3,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=0,p1=3,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=3,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=0,p1=3,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=0,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=0,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=0,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=0,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=0,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=0,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=0,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=0,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=0,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=0,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=0,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=0,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=0,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=0,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=0,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=0,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=0,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=0,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=0,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=0,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=0,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=0,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=0,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=0,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=0,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=0,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=0,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=0,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=0,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=0,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=0,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=0,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=0,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=0,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=0,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=0,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=0,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=0,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=0,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=0,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=0,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=0,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=0,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=0,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=0,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=0,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=0,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=0,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=0,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=0,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=0,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=0,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=0,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=0,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=0,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=0,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=0,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=0,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=0,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=0,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=0,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=0,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=0,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=0,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=3,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=3,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=3,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=3,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=3,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=3,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=3,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=3,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=3,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=3,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=3,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=3,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=3,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=3,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=3,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=3,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=3,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=3,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=3,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=3,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=3,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=3,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=3,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=3,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=3,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=3,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=3,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=3,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=3,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=3,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=3,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=3,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=3,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=3,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=3,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=3,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=3,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=3,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=3,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=3,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=3,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=3,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=3,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=3,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=3,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=3,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=3,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=3,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=3,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=3,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=3,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=3,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=3,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=3,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=3,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=3,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=3,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=3,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=3,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=3,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=3,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=1,s2=3,p0=3,p1=3,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=3,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=1,s2=3,p0=3,p1=3,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=0,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=0,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=0,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=0,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=0,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=0,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=0,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=0,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=0,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=0,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=0,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=0,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=0,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=0,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=0,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=0,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=0,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=0,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=0,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=0,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=0,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=0,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=0,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=0,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=0,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=0,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=0,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=0,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=0,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=0,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=0,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=0,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=0,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=0,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=0,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=0,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=0,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=0,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=0,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=0,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=0,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=0,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=0,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=0,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=0,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=0,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=0,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=0,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=0,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=0,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=0,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=0,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=0,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=0,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=0,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=0,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=3,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=3,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=3,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=3,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=3,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=3,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=3,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=3,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=3,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=3,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=3,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=3,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=3,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=3,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=3,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=3,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=3,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=3,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=3,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=3,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=3,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=3,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=3,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=3,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=3,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=3,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=3,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=3,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=3,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=3,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=3,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=3,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=3,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=3,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=3,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=3,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=3,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=3,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=3,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=3,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=3,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=3,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=3,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=3,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=3,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=3,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=3,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=3,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=3,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=3,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=3,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=3,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=3,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=3,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=3,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=3,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=3,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=3,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=3,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=3,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=3,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=0,p1=3,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=3,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=0,p1=3,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=0,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=0,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=0,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=0,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=0,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=0,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=0,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=0,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=0,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=0,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=0,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=0,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=0,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=0,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=0,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=0,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=0,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=0,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=0,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=0,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=0,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=0,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=0,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=0,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=0,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=0,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=0,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=0,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=0,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=0,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=0,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=0,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=0,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=0,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=0,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=0,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=0,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=0,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=0,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=0,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=0,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=0,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=0,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=0,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=0,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=0,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=0,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=0,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=0,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=0,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=0,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=0,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=0,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=0,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=0,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=0,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=0,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=0,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=0,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=0,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=0,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=0,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=0,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=0,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=3,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=3,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=3,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=3,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=3,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=3,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=3,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=3,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=3,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=3,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=3,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=3,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=3,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=3,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=3,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=3,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=3,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=3,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=3,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=3,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=3,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=3,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=3,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=3,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=3,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=3,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=3,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=3,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=3,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=3,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=3,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=3,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=3,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=3,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=3,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=3,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=3,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=3,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=3,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=3,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=3,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=3,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=3,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=3,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=3,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=3,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=3,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=3,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=3,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=3,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=3,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=3,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=3,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=3,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=3,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=3,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=3,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=3,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=3,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=3,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=3,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=1,p0=3,p1=3,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=3,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=1,p0=3,p1=3,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=0,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=0,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=0,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=0,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=0,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=0,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=0,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=0,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=0,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=0,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=0,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=0,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=0,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=0,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=0,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=0,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=0,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=0,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=0,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=0,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=0,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=0,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=0,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=0,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=0,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=0,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=0,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=0,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=0,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=0,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=0,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=0,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=0,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=0,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=0,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=0,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=0,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=0,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=0,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=0,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=0,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=0,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=0,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=0,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=0,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=0,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=0,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=0,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=0,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=0,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=0,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=0,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=0,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=0,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=0,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=0,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=0,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=0,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=0,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=0,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=3,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=3,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=3,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=3,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=3,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=3,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=3,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=3,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=3,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=3,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=3,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=3,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=3,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=3,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=3,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=3,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=3,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=3,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=3,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=3,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=3,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=3,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=3,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=3,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=3,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=3,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=3,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=3,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=3,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=3,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=3,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=3,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=3,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=3,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=3,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=3,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=3,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=3,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=3,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=3,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=3,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=3,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=3,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=3,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=3,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=3,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=3,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=3,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=3,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=3,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=3,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=3,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=3,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=3,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=3,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=3,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=3,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=3,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=3,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=3,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=3,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=0,p1=3,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=3,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=0,p1=3,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=0,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=0,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=0,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=0,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=0,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=0,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=0,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=0,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=0,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=0,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=0,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=0,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=0,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=0,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=0,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=0,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=0,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=0,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=0,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=0,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=0,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=0,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=0,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=0,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=0,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=0,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=0,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=0,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=0,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=0,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=0,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=0,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=0,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=0,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=0,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=0,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=0,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=0,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=0,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=0,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=0,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=0,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=0,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=0,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=0,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=0,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=0,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=0,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=0,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=0,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=0,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=0,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=0,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=0,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=0,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=0,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=0,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=0,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=0,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=0,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=0,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=0,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=0,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=0,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=3,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=3,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=3,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=3,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=3,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=3,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=3,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=3,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=3,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=3,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=3,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=3,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=3,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=3,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=3,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=3,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=3,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=3,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=3,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=3,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=3,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=3,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=3,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=3,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=3,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=3,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=3,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=3,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=3,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=3,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=3,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=3,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=3,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=3,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=3,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=3,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=3,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=3,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=3,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=3,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=3,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=3,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=3,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=3,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=3,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=3,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=3,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=3,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=3,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=3,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=3,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=3,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=3,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=3,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=3,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=3,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=3,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=3,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=3,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=3,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=3,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=1,s1=3,s2=3,p0=3,p1=3,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=3,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=1,s1=3,s2=3,p0=3,p1=3,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=0,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=0,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=0,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=0,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=0,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=0,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=0,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=0,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=0,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=0,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=0,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=0,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=0,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=0,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=0,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=0,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=0,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=0,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=0,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=0,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=0,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=0,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=0,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=0,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=0,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=0,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=0,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=0,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=0,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=0,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=0,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=0,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=0,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=0,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=0,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=0,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=0,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=0,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=0,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=0,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=0,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=0,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=0,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=0,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=0,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=0,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=0,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=0,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=3,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=3,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=3,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=3,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=3,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=3,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=3,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=3,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=3,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=3,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=3,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=3,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=3,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=3,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=3,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=3,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=3,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=3,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=3,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=3,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=3,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=3,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=3,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=3,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=3,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=3,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=3,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=3,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=3,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=3,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=3,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=3,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=3,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=3,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=3,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=3,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=3,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=3,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=3,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=3,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=3,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=3,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=3,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=3,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=3,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=3,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=3,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=3,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=3,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=3,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=3,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=3,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=3,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=3,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=3,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=3,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=3,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=3,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=3,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=3,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=3,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=0,p1=3,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=3,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=0,p1=3,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=0,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=0,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=0,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=0,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=0,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=0,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=0,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=0,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=0,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=0,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=0,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=0,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=0,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=0,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=0,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=0,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=0,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=0,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=0,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=0,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=0,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=0,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=0,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=0,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=0,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=0,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=0,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=0,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=0,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=0,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=0,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=0,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=0,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=0,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=0,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=0,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=0,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=0,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=0,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=0,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=0,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=0,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=0,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=0,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=0,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=0,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=0,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=0,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=0,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=0,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=0,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=0,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=0,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=0,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=0,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=0,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=0,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=0,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=0,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=0,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=0,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=0,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=0,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=0,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=3,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=3,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=3,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=3,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=3,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=3,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=3,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=3,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=3,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=3,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=3,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=3,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=3,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=3,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=3,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=3,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=3,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=3,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=3,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=3,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=3,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=3,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=3,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=3,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=3,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=3,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=3,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=3,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=3,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=3,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=3,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=3,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=3,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=3,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=3,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=3,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=3,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=3,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=3,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=3,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=3,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=3,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=3,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=3,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=3,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=3,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=3,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=3,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=3,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=3,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=3,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=3,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=3,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=3,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=3,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=3,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=3,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=3,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=3,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=3,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=3,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=1,p0=3,p1=3,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=3,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=1,p0=3,p1=3,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=0,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=0,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=0,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=0,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=0,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=0,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=0,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=0,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=0,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=0,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=0,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=0,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=0,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=0,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=0,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=0,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=0,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=0,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=0,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=0,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=0,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=0,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=0,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=0,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=0,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=0,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=0,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=0,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=0,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=0,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=0,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=0,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=0,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=0,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=0,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=0,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=0,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=0,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=0,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=0,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=0,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=0,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=0,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=0,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=0,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=0,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=0,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=0,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=0,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=0,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=0,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=0,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=0,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=0,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=0,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=0,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=0,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=0,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=0,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=0,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=3,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=3,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=3,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=3,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=3,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=3,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=3,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=3,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=3,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=3,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=3,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=3,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=3,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=3,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=3,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=3,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=3,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=3,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=3,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=3,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=3,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=3,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=3,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=3,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=3,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=3,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=3,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=3,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=3,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=3,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=3,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=3,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=3,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=3,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=3,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=3,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=3,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=3,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=3,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=3,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=3,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=3,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=3,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=3,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=3,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=3,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=3,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=3,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=3,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=3,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=3,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=3,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=3,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=3,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=3,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=3,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=3,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=3,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=3,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=3,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=3,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=0,p1=3,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=3,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=0,p1=3,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=0,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=0,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=0,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=0,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=0,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=0,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=0,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=0,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=0,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=0,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=0,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=0,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=0,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=0,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=0,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=0,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=0,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=0,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=0,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=0,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=0,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=0,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=0,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=0,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=0,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=0,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=0,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=0,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=0,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=0,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=0,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=0,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=0,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=0,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=0,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=0,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=0,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=0,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=0,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=0,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=0,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=0,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=0,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=0,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=0,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=0,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=0,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=0,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=0,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=0,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=0,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=0,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=0,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=0,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=0,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=0,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=0,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=0,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=0,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=0,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=0,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=0,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=0,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=0,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=3,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=3,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=3,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=3,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=3,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=3,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=3,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=3,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=3,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=3,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=3,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=3,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=3,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=3,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=3,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=3,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=3,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=3,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=3,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=3,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=3,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=3,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=3,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=3,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=3,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=3,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=3,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=3,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=3,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=3,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=3,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=3,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=3,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=3,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=3,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=3,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=3,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=3,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=3,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=3,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=3,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=3,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=3,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=3,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=3,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=3,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=3,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=3,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=3,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=3,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=3,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=3,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=3,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=3,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=3,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=3,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=3,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=3,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=3,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=3,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=3,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=1,s2=3,p0=3,p1=3,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=3,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=1,s2=3,p0=3,p1=3,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=0,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=0,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=0,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=0,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=0,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=0,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=0,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=0,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=0,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=0,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=0,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=0,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=0,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=0,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=0,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=0,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=0,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=0,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=0,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=0,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=0,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=0,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=0,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=0,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=0,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=0,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=0,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=0,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=0,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=0,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=0,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=0,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=0,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=0,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=0,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=0,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=0,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=0,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=0,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=0,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=0,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=0,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=0,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=0,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=0,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=0,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=0,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=0,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=0,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=0,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=0,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=0,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=0,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=0,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=0,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=0,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=3,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=3,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=3,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=3,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=3,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=3,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=3,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=3,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=3,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=3,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=3,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=3,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=3,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=3,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=3,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=3,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=3,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=3,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=3,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=3,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=3,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=3,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=3,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=3,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=3,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=3,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=3,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=3,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=3,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=3,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=3,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=3,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=3,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=3,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=3,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=3,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=3,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=3,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=3,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=3,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=3,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=3,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=3,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=3,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=3,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=3,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=3,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=3,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=3,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=3,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=3,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=3,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=3,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=3,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=3,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=3,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=3,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=3,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=3,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=3,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=3,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=0,p1=3,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=3,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=0,p1=3,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=0,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=0,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=0,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=0,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=0,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=0,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=0,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=0,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=0,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=0,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=0,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=0,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=0,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=0,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=0,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=0,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=0,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=0,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=0,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=0,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=0,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=0,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=0,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=0,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=0,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=0,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=0,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=0,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=0,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=0,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=0,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=0,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=0,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=0,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=0,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=0,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=0,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=0,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=0,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=0,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=0,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=0,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=0,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=0,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=0,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=0,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=0,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=0,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=0,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=0,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=0,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=0,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=0,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=0,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=0,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=0,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=0,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=0,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=0,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=0,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=0,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=0,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=0,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=0,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=3,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=3,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=3,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=3,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=3,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=3,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=3,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=3,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=3,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=3,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=3,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=3,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=3,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=3,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=3,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=3,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=3,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=3,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=3,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=3,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=3,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=3,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=3,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=3,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=3,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=3,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=3,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=3,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=3,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=3,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=3,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=3,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=3,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=3,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=3,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=3,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=3,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=3,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=3,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=3,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=3,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=3,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=3,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=3,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=3,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=3,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=3,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=3,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=3,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=3,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=3,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=3,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=3,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=3,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=3,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=3,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=3,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=3,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=3,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=3,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=3,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=1,p0=3,p1=3,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=3,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=1,p0=3,p1=3,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=0,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=0,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=0,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=0,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=0,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=0,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=0,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=0,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=0,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=0,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=0,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=0,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=0,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=0,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=0,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=0,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=0,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=0,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=0,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=0,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=0,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=0,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=0,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=0,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=0,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=0,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=0,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=0,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=0,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=0,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=0,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=0,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=0,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=0,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=0,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=0,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=0,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=0,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=0,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=0,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=0,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=0,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=0,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=0,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=0,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=0,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=0,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=0,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=0,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=0,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=0,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=0,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=0,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=0,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=0,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=0,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=0,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=0,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=0,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=0,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=3,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=3,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=3,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=3,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=3,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=3,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=3,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=3,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=3,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=3,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=3,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=3,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=3,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=3,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=3,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=3,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=3,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=3,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=3,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=3,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=3,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=3,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=3,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=3,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=3,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=3,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=3,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=3,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=3,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=3,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=3,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=3,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=3,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=3,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=3,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=3,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=3,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=3,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=3,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=3,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=3,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=3,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=3,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=3,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=3,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=3,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=3,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=3,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=3,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=3,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=3,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=3,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=3,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=3,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=3,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=3,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=3,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=3,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=3,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=3,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=3,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=0,p1=3,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=3,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=0,p1=3,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=0,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=0,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=0,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=0,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=0,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=0,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=0,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=0,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=0,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=0,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=0,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=0,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=0,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=0,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=0,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=0,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=0,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=0,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=0,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=0,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=0,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=0,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=0,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=0,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=0,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=0,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=0,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=0,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=0,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=0,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=0,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=0,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=0,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=0,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=0,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=0,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=0,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=0,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=0,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=0,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=0,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=0,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=0,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=0,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=0,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=0,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=0,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=0,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=0,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=0,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=0,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=0,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=0,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=0,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=0,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=0,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=0,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=0,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=0,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=0,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=0,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=0,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=0,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=0,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=3,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=3,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=3,p2=0,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=3,p2=0,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=3,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=3,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=3,p2=0,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=3,p2=0,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=3,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=3,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=3,p2=0,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=3,p2=0,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=3,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=3,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=3,p2=0,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=3,p2=0,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=3,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=3,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=3,p2=0,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=3,p2=0,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=3,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=3,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=3,p2=0,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=3,p2=0,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=3,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=3,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=3,p2=0,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=3,p2=0,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=3,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=3,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=3,p2=0,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=3,p2=0,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=3,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=3,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=3,p2=3,d0=1,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=3,p2=3,d0=1,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=3,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=3,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=3,p2=3,d0=1,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=3,p2=3,d0=1,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=3,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=3,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=3,p2=3,d0=1,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=3,p2=3,d0=1,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=3,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=3,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=3,p2=3,d0=1,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=3,p2=3,d0=1,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=3,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=3,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=3,p2=3,d0=3,d1=1,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=3,p2=3,d0=3,d1=1,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=3,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=3,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=3,p2=3,d0=3,d1=1,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=3,p2=3,d0=3,d1=1,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=3,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=3,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=3,p2=3,d0=3,d1=3,d2=1,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=3,p2=3,d0=3,d1=3,d2=1,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=3,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=1,s0=3,s1=3,s2=3,p0=3,p1=3,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=3,p2=3,d0=3,d1=3,d2=3,v=0): not supported [SYCL0] 
  IM2COL_3D(type_input=f32,type_kernel=f32,dst_type=f32,ne_input=[20,20,10,3],ne_kernel=[3,3,3,3],IC=3,s0=3,s1=3,s2=3,p0=3,p1=3,p2=3,d0=3,d1=3,d2=3,v=1): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,1,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,1,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,1,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,1,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,1,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,1,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,1,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,1,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,1,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,1,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,1,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,1,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,1,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,1,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,1,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,1,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,1,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,1,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,1,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,1,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,1,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,1,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,1,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,1,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,1,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,1,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,1,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,1,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,2,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,2,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,2,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,2,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,2,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,2,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,2,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,2,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,2,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,2,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,2,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,2,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,2,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,2,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,2,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,2,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,2,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,2,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,2,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,2,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,2,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,2,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,2,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,2,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,2,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,2,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,2,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,2,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,3,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,3,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,3,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,3,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,3,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,3,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,3,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,3,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,3,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,3,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,3,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,3,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,3,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,3,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,3,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,3,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,3,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,3,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,3,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,3,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,3,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,3,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,3,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,3,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,3,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,3,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,3,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,3,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,11,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,11,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,11,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,11,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,11,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,11,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,11,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,11,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,11,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,11,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,11,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,11,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,11,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,11,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,1,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,1,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,1,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,1,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,1,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,1,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,1,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,1,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,1,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,1,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,1,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,1,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,1,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,1,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,1,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,1,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,1,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,1,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,1,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,1,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,1,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,1,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,1,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,1,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,1,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,1,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,1,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,1,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,2,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,2,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,2,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,2,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,2,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,2,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,2,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,2,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,2,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,2,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,2,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,2,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,2,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,2,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,2,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,2,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,2,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,2,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,2,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,2,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,2,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,2,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,2,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,2,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,2,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,2,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,2,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,2,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,3,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,3,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,3,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,3,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,3,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,3,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,3,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,3,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,3,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,3,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,3,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,3,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,3,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,3,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,3,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,3,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,3,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,3,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,3,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,3,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,3,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,3,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,3,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,3,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,3,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,3,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,3,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,3,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,11,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,11,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,11,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,11,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,11,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,11,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,11,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,11,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,11,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,11,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,11,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,11,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,11,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,11,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,1,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,1,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,1,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,1,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,1,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,1,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,1,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,1,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,1,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,1,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,1,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,1,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,1,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,1,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,1,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,1,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,1,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,1,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,1,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,1,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,1,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,1,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,1,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,1,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,1,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,1,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,1,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,1,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,2,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,2,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,2,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,2,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,2,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,2,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,2,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,2,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,2,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,2,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,2,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,2,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,2,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,2,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,2,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,2,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,2,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,2,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,2,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,2,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,2,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,2,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,2,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,2,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,2,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,2,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,2,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,2,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,3,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,3,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,3,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,3,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,3,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,3,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,3,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,3,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,3,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,3,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,3,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,3,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,3,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,3,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,3,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,3,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,3,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,3,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,3,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,3,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,3,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,3,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,3,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,3,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,3,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,3,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,3,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,3,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,11,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,11,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,11,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,11,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,11,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,11,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,11,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,11,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,11,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,11,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,11,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,11,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,11,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,11,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,1,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,1,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,1,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,1,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,1,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,1,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,1,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,1,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,1,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,1,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,1,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,1,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,1,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,1,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,1,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,1,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,1,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,1,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,1,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,1,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,1,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,1,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,1,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,1,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,1,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,1,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,1,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,1,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,2,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,2,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,2,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,2,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,2,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,2,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,2,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,2,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,2,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,2,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,2,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,2,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,2,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,2,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,2,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,2,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,2,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,2,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,2,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,2,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,2,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,2,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,2,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,2,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,2,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,2,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,2,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,2,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,3,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,3,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,3,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,3,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,3,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,3,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,3,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,3,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,3,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,3,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,3,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,3,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,3,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,3,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,3,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,3,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,3,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,3,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,3,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,3,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,3,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,3,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,3,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,3,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,3,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,3,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,3,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,3,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,11,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,11,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,11,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,11,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,11,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,11,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,11,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,11,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,11,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,11,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,11,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,11,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,11,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,11,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,1,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,1,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,1,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,1,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,1,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,1,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,1,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,1,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,1,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,1,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,1,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,1,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,1,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,1,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,1,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,1,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,1,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,1,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,1,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,1,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,1,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,1,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,1,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,1,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,1,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,1,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,1,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,1,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,2,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,2,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,2,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,2,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,2,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,2,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,2,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,2,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,2,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,2,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,2,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,2,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,2,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,2,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,2,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,2,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,2,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,2,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,2,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,2,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,2,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,2,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,2,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,2,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,2,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,2,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,2,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,2,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,3,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,3,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,3,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,3,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,3,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,3,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,3,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,3,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,3,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,3,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,3,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,3,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,3,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,3,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,3,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,3,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,3,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,3,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,3,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,3,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,3,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,3,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,3,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,3,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,3,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,3,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,3,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,3,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,11,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,11,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,11,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,11,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,11,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,11,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,11,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,11,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,11,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,11,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,11,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,11,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,11,1,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,11,1,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,1,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,1,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,1,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,1,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,1,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,1,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,1,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,1,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,1,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,1,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,1,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,1,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,1,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,1,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,1,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,1,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,1,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,1,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,1,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,1,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,1,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,1,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,1,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,1,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,1,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,1,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,1,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,1,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,2,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,2,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,2,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,2,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,2,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,2,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,2,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,2,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,2,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,2,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,2,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,2,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,2,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,2,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,2,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,2,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,2,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,2,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,2,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,2,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,2,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,2,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,2,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,2,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,2,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,2,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,2,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,2,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,3,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,3,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,3,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,3,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,3,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,3,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,3,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,3,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,3,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,3,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,3,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,3,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,3,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,3,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,3,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,3,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,3,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,3,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,3,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,3,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,3,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,3,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,3,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,3,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,3,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,3,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,3,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,3,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,11,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,11,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,11,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,11,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,11,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,11,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,11,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,11,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,11,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,11,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,11,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,11,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,11,1,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,11,1,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,1,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,1,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,1,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,1,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,1,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,1,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,1,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,1,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,1,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,1,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,1,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,1,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,1,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,1,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,1,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,1,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,1,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,1,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,1,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,1,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,1,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,1,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,1,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,1,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,1,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,1,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,1,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,1,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,2,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,2,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,2,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,2,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,2,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,2,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,2,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,2,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,2,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,2,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,2,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,2,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,2,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,2,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,2,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,2,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,2,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,2,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,2,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,2,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,2,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,2,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,2,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,2,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,2,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,2,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,2,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,2,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,3,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,3,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,3,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,3,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,3,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,3,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,3,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,3,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,3,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,3,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,3,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,3,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,3,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,3,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,3,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,3,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,3,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,3,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,3,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,3,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,3,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,3,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,3,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,3,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,3,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,3,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,3,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,3,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,11,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,11,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,11,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,11,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,11,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,11,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,11,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,11,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,11,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,11,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,11,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,11,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,11,25,1],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,11,25,1],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,1,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,1,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,1,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,1,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,1,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,1,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,1,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,1,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,1,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,1,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,1,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,1,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,1,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,1,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,1,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,1,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,1,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,1,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,1,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,1,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,1,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,1,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,1,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,1,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,1,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,1,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,1,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,1,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,2,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,2,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,2,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,2,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,2,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,2,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,2,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,2,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,2,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,2,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,2,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,2,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,2,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,2,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,2,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,2,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,2,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,2,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,2,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,2,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,2,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,2,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,2,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,2,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,2,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,2,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,2,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,2,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,3,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,3,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,3,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,3,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,3,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,3,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,3,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,3,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,3,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,3,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,3,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,3,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,3,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,3,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,3,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,3,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,3,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,3,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,3,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,3,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,3,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,3,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,3,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,3,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,3,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,3,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,3,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,3,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,11,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,11,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,11,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,11,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,11,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,11,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,11,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,11,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,11,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,11,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,11,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,11,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,11,25,12],type_kernel=f32,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,11,25,12],type_kernel=f16,stride0=1,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,1,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,1,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,1,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,1,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,1,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,1,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,1,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,1,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,1,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,1,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,1,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,1,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,1,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,1,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,1,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,1,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,1,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,1,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,1,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,1,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,1,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,1,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,1,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,1,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,1,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,1,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,1,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,1,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,2,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,2,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,2,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,2,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,2,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,2,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,2,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,2,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,2,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,2,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,2,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,2,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,2,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,2,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,2,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,2,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,2,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,2,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,2,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,2,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,2,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,2,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,2,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,2,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,2,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,2,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,2,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,2,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,3,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,3,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,3,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,3,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,3,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,3,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,3,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,3,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,3,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,3,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,3,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,3,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,3,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,3,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,3,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,3,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,3,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,3,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,3,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,3,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,3,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,3,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,3,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,3,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,3,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,3,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,3,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,3,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,11,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,11,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,11,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,11,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,11,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,11,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,11,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,11,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,11,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,11,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,11,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,11,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,11,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,11,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,1,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,1,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,1,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,1,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,1,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,1,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,1,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,1,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,1,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,1,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,1,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,1,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,1,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,1,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,1,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,1,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,1,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,1,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,1,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,1,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,1,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,1,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,1,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,1,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,1,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,1,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,1,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,1,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,2,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,2,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,2,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,2,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,2,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,2,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,2,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,2,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,2,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,2,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,2,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,2,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,2,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,2,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,2,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,2,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,2,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,2,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,2,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,2,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,2,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,2,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,2,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,2,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,2,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,2,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,2,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,2,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,3,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,3,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,3,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,3,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,3,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,3,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,3,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,3,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,3,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,3,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,3,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,3,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,3,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,3,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,3,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,3,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,3,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,3,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,3,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,3,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,3,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,3,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,3,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,3,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,3,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,3,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,3,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,3,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,11,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,11,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,11,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,11,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,11,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,11,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,11,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,11,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,11,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,11,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,11,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,11,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,11,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,11,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,1,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,1,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,1,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,1,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,1,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,1,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,1,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,1,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,1,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,1,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,1,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,1,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,1,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,1,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,1,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,1,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,1,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,1,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,1,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,1,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,1,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,1,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,1,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,1,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,1,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,1,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,1,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,1,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,2,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,2,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,2,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,2,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,2,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,2,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,2,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,2,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,2,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,2,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,2,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,2,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,2,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,2,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,2,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,2,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,2,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,2,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,2,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,2,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,2,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,2,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,2,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,2,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,2,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,2,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,2,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,2,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,3,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,3,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,3,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,3,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,3,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,3,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,3,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,3,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,3,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,3,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,3,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,3,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,3,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,3,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,3,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,3,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,3,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,3,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,3,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,3,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,3,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,3,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,3,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,3,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,3,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,3,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,3,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,3,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,11,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,11,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,11,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,11,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,11,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,11,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,11,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,11,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,11,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,11,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,11,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,11,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,11,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,11,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,1,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,1,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,1,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,1,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,1,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,1,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,1,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,1,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,1,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,1,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,1,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,1,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,1,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,1,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,1,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,1,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,1,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,1,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,1,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,1,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,1,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,1,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,1,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,1,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,1,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,1,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,1,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,1,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,2,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,2,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,2,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,2,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,2,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,2,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,2,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,2,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,2,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,2,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,2,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,2,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,2,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,2,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,2,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,2,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,2,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,2,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,2,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,2,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,2,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,2,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,2,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,2,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,2,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,2,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,2,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,2,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,3,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,3,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,3,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,3,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,3,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,3,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,3,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,3,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,3,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,3,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,3,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,3,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,3,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,3,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,3,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,3,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,3,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,3,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,3,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,3,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,3,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,3,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,3,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,3,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,3,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,3,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,3,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,3,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,11,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,11,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,11,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,11,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,11,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,11,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,11,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,11,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,11,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,11,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,11,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,11,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,11,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,11,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=2,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,1,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,1,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,1,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,1,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,1,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,1,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,1,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,1,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,1,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,1,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,1,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,1,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,1,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,1,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,1,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,1,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,1,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,1,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,1,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,1,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,1,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,1,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,1,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,1,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,1,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,1,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,1,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,1,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,2,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,2,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,2,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,2,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,2,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,2,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,2,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,2,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,2,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,2,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,2,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,2,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,2,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,2,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,2,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,2,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,2,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,2,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,2,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,2,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,2,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,2,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,2,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,2,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,2,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,2,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,2,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,2,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,3,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,3,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,3,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,3,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,3,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,3,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,3,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,3,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,3,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,3,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,3,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,3,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,3,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,3,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,3,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,3,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,3,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,3,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,3,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,3,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,3,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,3,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,3,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,3,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,3,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,3,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,3,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,3,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,11,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,11,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,11,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,11,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,11,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,11,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,11,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,11,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,11,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,11,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,11,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,11,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,11,1,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,11,1,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,1,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,1,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,1,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,1,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,1,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,1,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,1,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,1,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,1,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,1,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,1,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,1,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,1,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,1,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,1,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,1,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,1,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,1,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,1,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,1,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,1,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,1,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,1,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,1,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,1,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,1,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,1,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,1,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,2,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,2,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,2,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,2,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,2,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,2,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,2,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,2,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,2,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,2,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,2,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,2,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,2,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,2,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,2,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,2,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,2,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,2,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,2,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,2,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,2,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,2,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,2,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,2,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,2,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,2,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,2,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,2,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,3,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[1,3,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,3,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[1,3,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,3,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,3,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,3,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,3,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,3,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[2,3,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,3,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[2,3,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,3,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,3,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,3,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,3,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,3,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,1,2],ne_kernel=[3,3,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,3,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[3,3,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,3,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,3,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,3,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,3,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,3,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,1,2],ne_kernel=[11,3,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,3,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,3,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,11,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[1,11,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,11,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[1,11,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,11,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[2,11,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,11,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[2,11,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,11,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,1,2],ne_kernel=[3,11,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,11,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[3,11,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,11,1,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,1,2],ne_kernel=[11,11,1,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,1,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,1,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,1,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,1,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,1,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,1,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,1,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,1,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,1,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,1,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,1,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,1,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,1,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,1,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,1,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,1,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,1,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,1,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,1,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,1,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,1,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,1,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,1,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,1,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,1,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,1,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,1,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,1,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,2,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,2,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,2,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,2,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,2,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,2,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,2,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,2,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,2,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,2,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,2,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,2,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,2,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,2,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,2,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,2,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,2,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,2,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,2,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,2,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,2,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,2,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,2,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,2,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,2,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,2,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,2,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,2,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,3,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,3,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,3,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,3,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,3,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,3,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,3,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,3,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,3,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,3,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,3,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,3,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,3,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,3,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,3,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,3,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,3,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,3,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,3,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,3,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,3,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,3,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,3,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,3,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,3,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,3,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,3,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,3,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,11,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,11,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,11,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,11,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,11,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,11,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,11,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,11,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,11,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,11,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,11,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,11,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,11,25,1],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,11,25,1],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,1,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,1,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,1,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,1,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,1,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,1,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,1,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,1,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,1,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,1,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,1,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,1,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,1,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,1,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,1,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,1,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,1,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,1,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,1,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,1,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,1,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,1,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,1,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,1,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,1,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,1,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,1,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,1,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,2,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,2,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,2,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,2,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,2,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,2,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,2,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,2,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,2,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,2,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,2,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,2,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,2,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,2,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,2,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,2,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,2,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,2,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,2,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,2,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,2,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,2,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,2,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,2,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,2,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,2,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,2,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,2,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,3,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[1,3,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,3,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[1,3,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,3,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,3,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,3,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,3,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,3,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[2,3,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,3,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[2,3,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,3,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,3,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,3,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,3,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,3,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,1,25,2],ne_kernel=[3,3,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,3,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[3,3,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,3,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,3,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,3,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,3,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,3,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,1,25,2],ne_kernel=[11,3,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,3,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,3,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,11,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[1,11,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,11,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[1,11,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,11,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[2,11,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,11,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[2,11,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,11,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[1,133,25,2],ne_kernel=[3,11,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,11,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[3,11,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,11,25,12],type_kernel=f32,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D(ne_input=[141,133,25,2],ne_kernel=[11,11,25,12],type_kernel=f16,stride0=3,stride1=5,padding0=5,padding1=5,dilation0=2,dilation1=4,cwhn=0): not supported [SYCL0] 
  CONV_2D_DW(ne_input=[17,34,9,1],ne_kernel=[3,3,1,9],stride=1,padding=0,dilation=1,cwhn=0): not supported [SYCL0] 
  CONV_2D_DW(ne_input=[17,34,9,1],ne_kernel=[3,3,1,9],stride=1,padding=0,dilation=1,cwhn=1): not supported [SYCL0] 
  CONV_2D_DW(ne_input=[32,8,64,1],ne_kernel=[3,3,1,64],stride=2,padding=1,dilation=1,cwhn=0): not supported [SYCL0] 
  CONV_2D_DW(ne_input=[32,8,64,1],ne_kernel=[3,3,1,64],stride=2,padding=1,dilation=1,cwhn=1): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=2,d1=2,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=1,p1=1,p2=1,d0=1,d1=1,d2=1,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=1,p1=1,p2=1,d0=2,d1=2,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=0,p1=0,p2=0,d0=2,d1=2,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=1,p1=1,p2=1,d0=1,d1=1,d2=1,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=1,p1=1,p2=1,d0=2,d1=2,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=2,d1=2,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=1,p1=1,p2=1,d0=1,d1=1,d2=1,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=1,p1=1,p2=1,d0=2,d1=2,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=0,p1=0,p2=0,d0=2,d1=2,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=1,p1=1,p2=1,d0=1,d1=1,d2=1,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=1,p1=1,p2=1,d0=2,d1=2,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=2,d1=2,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=1,p1=1,p2=1,d0=1,d1=1,d2=1,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=1,p1=1,p2=1,d0=2,d1=2,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=0,p1=0,p2=0,d0=2,d1=2,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=1,p1=1,p2=1,d0=1,d1=1,d2=1,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=1,p1=1,p2=1,d0=2,d1=2,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=2,d1=2,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=1,p1=1,p2=1,d0=1,d1=1,d2=1,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=1,p1=1,p2=1,d0=2,d1=2,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=0,p1=0,p2=0,d0=2,d1=2,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=1,p1=1,p2=1,d0=1,d1=1,d2=1,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=1,p1=1,p2=1,d0=2,d1=2,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=2,d1=2,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=1,p1=1,p2=1,d0=1,d1=1,d2=1,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=1,p1=1,p2=1,d0=2,d1=2,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=0,p1=0,p2=0,d0=2,d1=2,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=1,p1=1,p2=1,d0=1,d1=1,d2=1,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=1,p1=1,p2=1,d0=2,d1=2,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=2,d1=2,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=1,p1=1,p2=1,d0=1,d1=1,d2=1,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=1,p1=1,p2=1,d0=2,d1=2,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=0,p1=0,p2=0,d0=2,d1=2,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=1,p1=1,p2=1,d0=1,d1=1,d2=1,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=1,p1=1,p2=1,d0=2,d1=2,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=2,d1=2,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=1,p1=1,p2=1,d0=1,d1=1,d2=1,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=1,p1=1,p2=1,d0=2,d1=2,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=0,p1=0,p2=0,d0=2,d1=2,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=1,p1=1,p2=1,d0=1,d1=1,d2=1,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=1,p1=1,p2=1,d0=2,d1=2,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=2,d1=2,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=1,p1=1,p2=1,d0=1,d1=1,d2=1,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=1,p1=1,p2=1,d0=2,d1=2,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=0,p1=0,p2=0,d0=2,d1=2,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=1,p1=1,p2=1,d0=1,d1=1,d2=1,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=1,p1=1,p2=1,d0=2,d1=2,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=4,ID=8,IH=8,IW=8,OC=8,KD=1,KH=1,KW=1,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,type_kernel=f32): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=2,d1=2,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=1,p1=1,p2=1,d0=1,d1=1,d2=1,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=1,p1=1,p2=1,d0=2,d1=2,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=0,p1=0,p2=0,d0=2,d1=2,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=1,p1=1,p2=1,d0=1,d1=1,d2=1,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=1,p1=1,p2=1,d0=2,d1=2,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=2,d1=2,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=1,p1=1,p2=1,d0=1,d1=1,d2=1,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=1,p1=1,p2=1,d0=2,d1=2,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=0,p1=0,p2=0,d0=2,d1=2,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=1,p1=1,p2=1,d0=1,d1=1,d2=1,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=1,p1=1,p2=1,d0=2,d1=2,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=2,d1=2,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=1,p1=1,p2=1,d0=1,d1=1,d2=1,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=1,p1=1,p2=1,d0=2,d1=2,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=0,p1=0,p2=0,d0=2,d1=2,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=1,p1=1,p2=1,d0=1,d1=1,d2=1,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=1,p1=1,p2=1,d0=2,d1=2,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=2,d1=2,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=1,p1=1,p2=1,d0=1,d1=1,d2=1,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=1,p1=1,p2=1,d0=2,d1=2,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=0,p1=0,p2=0,d0=2,d1=2,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=1,p1=1,p2=1,d0=1,d1=1,d2=1,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=1,p1=1,p2=1,d0=2,d1=2,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=2,d1=2,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=1,p1=1,p2=1,d0=1,d1=1,d2=1,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=1,p1=1,p2=1,d0=2,d1=2,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=0,p1=0,p2=0,d0=2,d1=2,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=1,p1=1,p2=1,d0=1,d1=1,d2=1,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=1,p1=1,p2=1,d0=2,d1=2,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=2,d1=2,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=1,p1=1,p2=1,d0=1,d1=1,d2=1,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=1,p1=1,p2=1,d0=2,d1=2,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=0,p1=0,p2=0,d0=2,d1=2,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=1,p1=1,p2=1,d0=1,d1=1,d2=1,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=1,p1=1,p2=1,d0=2,d1=2,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=1,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=2,d1=2,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=1,p1=1,p2=1,d0=1,d1=1,d2=1,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=1,p1=1,p2=1,d0=2,d1=2,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=0,p1=0,p2=0,d0=2,d1=2,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=1,p1=1,p2=1,d0=1,d1=1,d2=1,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=1,p1=1,p2=1,d0=2,d1=2,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=1,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=2,d1=2,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=1,p1=1,p2=1,d0=1,d1=1,d2=1,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=1,s1=1,s2=1,p0=1,p1=1,p2=1,d0=2,d1=2,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=0,p1=0,p2=0,d0=2,d1=2,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=1,p1=1,p2=1,d0=1,d1=1,d2=1,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=3,KW=3,s0=2,s1=2,s2=2,p0=1,p1=1,p2=1,d0=2,d1=2,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=2,IC=3,ID=18,IH=22,IW=20,OC=4,KD=3,KH=1,KW=5,s0=2,s1=1,s2=1,p0=2,p1=0,p2=1,d0=1,d1=1,d2=2,type_kernel=f16): not supported [SYCL0] 
  CONV_3D(N=1,IC=4,ID=8,IH=8,IW=8,OC=8,KD=1,KH=1,KW=1,s0=1,s1=1,s2=1,p0=0,p1=0,p2=0,d0=1,d1=1,d2=1,type_kernel=f16): not supported [SYCL0] 
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
  CONV_TRANSPOSE_2D(ne_input=[129,63,35,1],ne_kernel=[3,3,48,35],stride=1): not supported [SYCL0] 
  COUNT_EQUAL(type=f32,ne=[4,500,1,1]): [1;32mOK[0m
  COUNT_EQUAL(type=f32,ne=[4,5000,1,1]): [1;32mOK[0m
  ARGMAX(type=f32,ne=[32,1,1,1]): [1;32mOK[0m
  ARGMAX(type=f32,ne=[32,513,1,1]): [1;32mOK[0m
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
  REPEAT_BACK(type=f32,ne=[8,6,4,2],nr=[1,1,1,1],v=0): [1;32mOK[0m
  REPEAT_BACK(type=f32,ne=[8,6,4,2],nr=[2,1,1,1],v=0): [1;32mOK[0m
  REPEAT_BACK(type=f32,ne=[8,6,4,2],nr=[1,2,1,1],v=0): [1;32mOK[0m
  REPEAT_BACK(type=f32,ne=[8,6,4,2],nr=[1,1,2,1],v=0): [1;32mOK[0m
  REPEAT_BACK(type=f32,ne=[8,6,4,2],nr=[1,1,1,2],v=0): [1;32mOK[0m
  REPEAT_BACK(type=f32,ne=[8,6,4,2],nr=[1,1,1,1],v=1): [1;32mOK[0m
  REPEAT_BACK(type=f32,ne=[8,6,4,2],nr=[2,1,1,1],v=1): [1;32mOK[0m
  REPEAT_BACK(type=f32,ne=[8,6,4,2],nr=[1,2,1,1],v=1): [1;32mOK[0m
  REPEAT_BACK(type=f32,ne=[8,6,4,2],nr=[1,1,2,1],v=1): [1;32mOK[0m
  REPEAT_BACK(type=f32,ne=[8,6,4,2],nr=[1,1,1,2],v=1): [1;32mOK[0m
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
  SET(type_src=f32,type_dst=f32,ne=[6,5,4,3],dim=1): [1;32mOK[0m
  SET(type_src=f32,type_dst=f32,ne=[6,5,4,3],dim=2): [1;32mOK[0m
  SET(type_src=f32,type_dst=f32,ne=[6,5,4,3],dim=3): [1;32mOK[0m
  SET(type_src=i32,type_dst=i32,ne=[6,5,4,3],dim=1): not supported [SYCL0] 
  SET(type_src=i32,type_dst=i32,ne=[6,5,4,3],dim=2): not supported [SYCL0] 
  SET(type_src=i32,type_dst=i32,ne=[6,5,4,3],dim=3): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=f32,ne=[1,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=f32,type_dst=f32,ne=[1,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=f32,type_dst=f32,ne=[1,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=f32,type_dst=f32,ne=[2,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=f32,type_dst=f32,ne=[2,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=f32,type_dst=f32,ne=[2,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=f32,type_dst=f32,ne=[3,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=f32,type_dst=f32,ne=[3,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=f32,type_dst=f32,ne=[3,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=f16,type_dst=f16,ne=[1,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=f16,type_dst=f16,ne=[1,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=f16,type_dst=f16,ne=[1,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=f16,type_dst=f16,ne=[2,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=f16,type_dst=f16,ne=[2,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=f16,type_dst=f16,ne=[2,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=f16,type_dst=f16,ne=[3,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=f16,type_dst=f16,ne=[3,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=f16,type_dst=f16,ne=[3,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=bf16,type_dst=bf16,ne=[1,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=bf16,ne=[1,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=bf16,ne=[1,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=bf16,ne=[2,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=bf16,ne=[2,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=bf16,ne=[2,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=bf16,ne=[3,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=bf16,ne=[3,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=bf16,ne=[3,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=q4_0,type_dst=q4_0,ne=[32,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q4_0,type_dst=q4_0,ne=[32,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q4_0,type_dst=q4_0,ne=[32,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q4_0,type_dst=q4_0,ne=[64,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q4_0,type_dst=q4_0,ne=[64,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q4_0,type_dst=q4_0,ne=[64,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q4_0,type_dst=q4_0,ne=[96,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q4_0,type_dst=q4_0,ne=[96,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q4_0,type_dst=q4_0,ne=[96,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q4_1,type_dst=q4_1,ne=[32,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q4_1,type_dst=q4_1,ne=[32,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q4_1,type_dst=q4_1,ne=[32,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q4_1,type_dst=q4_1,ne=[64,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q4_1,type_dst=q4_1,ne=[64,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q4_1,type_dst=q4_1,ne=[64,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q4_1,type_dst=q4_1,ne=[96,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q4_1,type_dst=q4_1,ne=[96,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q4_1,type_dst=q4_1,ne=[96,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q5_0,type_dst=q5_0,ne=[32,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q5_0,type_dst=q5_0,ne=[32,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q5_0,type_dst=q5_0,ne=[32,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q5_0,type_dst=q5_0,ne=[64,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q5_0,type_dst=q5_0,ne=[64,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q5_0,type_dst=q5_0,ne=[64,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q5_0,type_dst=q5_0,ne=[96,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q5_0,type_dst=q5_0,ne=[96,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q5_0,type_dst=q5_0,ne=[96,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q5_1,type_dst=q5_1,ne=[32,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q5_1,type_dst=q5_1,ne=[32,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q5_1,type_dst=q5_1,ne=[32,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q5_1,type_dst=q5_1,ne=[64,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q5_1,type_dst=q5_1,ne=[64,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q5_1,type_dst=q5_1,ne=[64,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q5_1,type_dst=q5_1,ne=[96,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q5_1,type_dst=q5_1,ne=[96,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q5_1,type_dst=q5_1,ne=[96,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q8_0,type_dst=q8_0,ne=[32,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q8_0,type_dst=q8_0,ne=[32,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q8_0,type_dst=q8_0,ne=[32,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q8_0,type_dst=q8_0,ne=[64,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q8_0,type_dst=q8_0,ne=[64,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q8_0,type_dst=q8_0,ne=[64,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q8_0,type_dst=q8_0,ne=[96,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q8_0,type_dst=q8_0,ne=[96,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q8_0,type_dst=q8_0,ne=[96,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=mxfp4,type_dst=mxfp4,ne=[32,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=mxfp4,type_dst=mxfp4,ne=[32,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=mxfp4,type_dst=mxfp4,ne=[32,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=mxfp4,type_dst=mxfp4,ne=[64,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=mxfp4,type_dst=mxfp4,ne=[64,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=mxfp4,type_dst=mxfp4,ne=[64,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=mxfp4,type_dst=mxfp4,ne=[96,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=mxfp4,type_dst=mxfp4,ne=[96,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=mxfp4,type_dst=mxfp4,ne=[96,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=q2_K,type_dst=q2_K,ne=[256,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q2_K,type_dst=q2_K,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=q2_K,type_dst=q2_K,ne=[256,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=q2_K,type_dst=q2_K,ne=[512,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q2_K,type_dst=q2_K,ne=[512,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=q2_K,type_dst=q2_K,ne=[512,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=q2_K,type_dst=q2_K,ne=[768,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q2_K,type_dst=q2_K,ne=[768,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=q2_K,type_dst=q2_K,ne=[768,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=q3_K,type_dst=q3_K,ne=[256,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q3_K,type_dst=q3_K,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=q3_K,type_dst=q3_K,ne=[256,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=q3_K,type_dst=q3_K,ne=[512,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q3_K,type_dst=q3_K,ne=[512,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=q3_K,type_dst=q3_K,ne=[512,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=q3_K,type_dst=q3_K,ne=[768,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q3_K,type_dst=q3_K,ne=[768,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=q3_K,type_dst=q3_K,ne=[768,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=q4_K,type_dst=q4_K,ne=[256,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q4_K,type_dst=q4_K,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=q4_K,type_dst=q4_K,ne=[256,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=q4_K,type_dst=q4_K,ne=[512,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q4_K,type_dst=q4_K,ne=[512,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=q4_K,type_dst=q4_K,ne=[512,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=q4_K,type_dst=q4_K,ne=[768,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q4_K,type_dst=q4_K,ne=[768,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=q4_K,type_dst=q4_K,ne=[768,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=q5_K,type_dst=q5_K,ne=[256,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q5_K,type_dst=q5_K,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=q5_K,type_dst=q5_K,ne=[256,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=q5_K,type_dst=q5_K,ne=[512,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q5_K,type_dst=q5_K,ne=[512,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=q5_K,type_dst=q5_K,ne=[512,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=q5_K,type_dst=q5_K,ne=[768,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q5_K,type_dst=q5_K,ne=[768,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=q5_K,type_dst=q5_K,ne=[768,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=q6_K,type_dst=q6_K,ne=[256,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q6_K,type_dst=q6_K,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=q6_K,type_dst=q6_K,ne=[256,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=q6_K,type_dst=q6_K,ne=[512,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q6_K,type_dst=q6_K,ne=[512,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=q6_K,type_dst=q6_K,ne=[512,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=q6_K,type_dst=q6_K,ne=[768,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q6_K,type_dst=q6_K,ne=[768,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=q6_K,type_dst=q6_K,ne=[768,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq2_xxs,type_dst=iq2_xxs,ne=[256,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq2_xxs,type_dst=iq2_xxs,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq2_xxs,type_dst=iq2_xxs,ne=[256,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq2_xxs,type_dst=iq2_xxs,ne=[512,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq2_xxs,type_dst=iq2_xxs,ne=[512,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq2_xxs,type_dst=iq2_xxs,ne=[512,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq2_xxs,type_dst=iq2_xxs,ne=[768,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq2_xxs,type_dst=iq2_xxs,ne=[768,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq2_xxs,type_dst=iq2_xxs,ne=[768,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq2_xs,type_dst=iq2_xs,ne=[256,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq2_xs,type_dst=iq2_xs,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq2_xs,type_dst=iq2_xs,ne=[256,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq2_xs,type_dst=iq2_xs,ne=[512,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq2_xs,type_dst=iq2_xs,ne=[512,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq2_xs,type_dst=iq2_xs,ne=[512,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq2_xs,type_dst=iq2_xs,ne=[768,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq2_xs,type_dst=iq2_xs,ne=[768,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq2_xs,type_dst=iq2_xs,ne=[768,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq2_s,type_dst=iq2_s,ne=[256,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq2_s,type_dst=iq2_s,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq2_s,type_dst=iq2_s,ne=[256,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq2_s,type_dst=iq2_s,ne=[512,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq2_s,type_dst=iq2_s,ne=[512,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq2_s,type_dst=iq2_s,ne=[512,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq2_s,type_dst=iq2_s,ne=[768,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq2_s,type_dst=iq2_s,ne=[768,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq2_s,type_dst=iq2_s,ne=[768,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq3_xxs,type_dst=iq3_xxs,ne=[256,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq3_xxs,type_dst=iq3_xxs,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq3_xxs,type_dst=iq3_xxs,ne=[256,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq3_xxs,type_dst=iq3_xxs,ne=[512,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq3_xxs,type_dst=iq3_xxs,ne=[512,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq3_xxs,type_dst=iq3_xxs,ne=[512,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq3_xxs,type_dst=iq3_xxs,ne=[768,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq3_xxs,type_dst=iq3_xxs,ne=[768,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq3_xxs,type_dst=iq3_xxs,ne=[768,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq1_s,type_dst=iq1_s,ne=[256,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq1_s,type_dst=iq1_s,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq1_s,type_dst=iq1_s,ne=[256,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq1_s,type_dst=iq1_s,ne=[512,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq1_s,type_dst=iq1_s,ne=[512,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq1_s,type_dst=iq1_s,ne=[512,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq1_s,type_dst=iq1_s,ne=[768,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq1_s,type_dst=iq1_s,ne=[768,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq1_s,type_dst=iq1_s,ne=[768,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq1_m,type_dst=iq1_m,ne=[256,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq1_m,type_dst=iq1_m,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq1_m,type_dst=iq1_m,ne=[256,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq1_m,type_dst=iq1_m,ne=[512,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq1_m,type_dst=iq1_m,ne=[512,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq1_m,type_dst=iq1_m,ne=[512,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq1_m,type_dst=iq1_m,ne=[768,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq1_m,type_dst=iq1_m,ne=[768,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq1_m,type_dst=iq1_m,ne=[768,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq4_nl,type_dst=iq4_nl,ne=[32,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=iq4_nl,type_dst=iq4_nl,ne=[32,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq4_nl,type_dst=iq4_nl,ne=[32,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq4_nl,type_dst=iq4_nl,ne=[64,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=iq4_nl,type_dst=iq4_nl,ne=[64,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq4_nl,type_dst=iq4_nl,ne=[64,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq4_nl,type_dst=iq4_nl,ne=[96,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=iq4_nl,type_dst=iq4_nl,ne=[96,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq4_nl,type_dst=iq4_nl,ne=[96,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq3_s,type_dst=iq3_s,ne=[256,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq3_s,type_dst=iq3_s,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq3_s,type_dst=iq3_s,ne=[256,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq3_s,type_dst=iq3_s,ne=[512,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq3_s,type_dst=iq3_s,ne=[512,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq3_s,type_dst=iq3_s,ne=[512,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq3_s,type_dst=iq3_s,ne=[768,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq3_s,type_dst=iq3_s,ne=[768,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq3_s,type_dst=iq3_s,ne=[768,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq4_xs,type_dst=iq4_xs,ne=[256,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=iq4_xs,type_dst=iq4_xs,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq4_xs,type_dst=iq4_xs,ne=[256,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq4_xs,type_dst=iq4_xs,ne=[512,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=iq4_xs,type_dst=iq4_xs,ne=[512,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq4_xs,type_dst=iq4_xs,ne=[512,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq4_xs,type_dst=iq4_xs,ne=[768,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=iq4_xs,type_dst=iq4_xs,ne=[768,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq4_xs,type_dst=iq4_xs,ne=[768,2,3,4],permute_src=[0,3,1,2],permute_dst=[0,2,1,3],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=f16,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=f16,type_dst=f16,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=f16,type_dst=f16,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=f16,type_dst=bf16,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=bf16,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q4_0,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q4_0,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q4_1,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q4_1,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q5_0,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q5_0,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q5_1,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q5_1,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q8_0,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q8_0,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=mxfp4,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=mxfp4,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q2_K,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q2_K,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q3_K,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q3_K,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q4_K,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q4_K,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q5_K,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q5_K,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q6_K,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=q6_K,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq2_xxs,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq2_xxs,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq2_xs,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq2_xs,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq2_s,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq2_s,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq3_xxs,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq3_xxs,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq1_s,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq1_s,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq1_m,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq1_m,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq4_nl,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq4_nl,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq3_s,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq3_s,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq4_xs,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=iq4_xs,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=f16,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=f16,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=bf16,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=bf16,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=q4_0,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=q4_0,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=q4_1,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=q4_1,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=q5_0,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=q5_0,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=q5_1,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=q5_1,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=q8_0,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=q8_0,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=mxfp4,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=mxfp4,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=q2_K,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=q2_K,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=q3_K,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=q3_K,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=q4_K,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=q4_K,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=q5_K,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=q5_K,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=q6_K,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=q6_K,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=iq2_xxs,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=iq2_xxs,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=iq2_xs,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=iq2_xs,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=iq2_s,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=iq2_s,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=iq3_xxs,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=iq3_xxs,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=iq1_s,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=iq1_s,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=iq1_m,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=iq1_m,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=iq4_nl,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=iq4_nl,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=iq3_s,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=iq3_s,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=iq4_xs,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=iq4_xs,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=f32,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=f32,type_dst=f16,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=f32,type_dst=f16,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=f32,type_dst=bf16,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=bf16,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=q4_0,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=f32,type_dst=q4_0,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=f32,type_dst=q4_1,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=f32,type_dst=q4_1,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=f32,type_dst=q5_0,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=f32,type_dst=q5_0,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=f32,type_dst=q5_1,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=f32,type_dst=q5_1,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=f32,type_dst=q8_0,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=f32,type_dst=q8_0,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=f32,type_dst=mxfp4,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=mxfp4,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=q2_K,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=q2_K,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=q3_K,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=q3_K,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=q4_K,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=q4_K,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=q5_K,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=q5_K,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=q6_K,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=q6_K,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq2_xxs,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq2_xxs,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq2_xs,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq2_xs,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq2_s,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq2_s,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq3_xxs,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq3_xxs,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq1_s,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq1_s,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq1_m,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq1_m,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq4_nl,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=f32,type_dst=iq4_nl,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=f32,type_dst=iq3_s,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq3_s,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq4_xs,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=iq4_xs,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=f32,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=f16,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=f16,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=bf16,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=bf16,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=q4_0,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q4_0,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q4_1,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q4_1,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q5_0,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q5_0,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q5_1,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q5_1,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q8_0,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=q8_0,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=mxfp4,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=mxfp4,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=q2_K,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=q2_K,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=q3_K,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=q3_K,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=q4_K,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=q4_K,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=q5_K,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=q5_K,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=q6_K,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=q6_K,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq2_xxs,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq2_xxs,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq2_xs,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq2_xs,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq2_s,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq2_s,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq3_xxs,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq3_xxs,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq1_s,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq1_s,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq1_m,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq1_m,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq4_nl,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq4_nl,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq3_s,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq3_s,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq4_xs,type_dst=f32,ne=[256,4,4,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=iq4_xs,type_dst=f32,ne=[256,2,3,4],permute_src=[0,2,1,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=f16,ne=[256,2,3,4],permute_src=[1,0,2,3],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=f16,type_dst=f32,ne=[256,2,3,4],permute_src=[1,0,2,3],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=f32,type_dst=f16,ne=[256,2,3,4],permute_src=[1,0,2,3],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=f32,type_dst=f32,ne=[256,2,3,4],permute_src=[1,0,2,3],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CPY(type_src=f32,type_dst=i32,ne=[256,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=i32,ne=[256,2,3,4],permute_src=[1,0,2,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=i32,type_dst=f32,ne=[256,2,3,4],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=i32,type_dst=f32,ne=[256,2,3,4],permute_src=[1,0,2,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=f16,ne=[256,4,3,1],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=1): [1;32mOK[0m
  CPY(type_src=f32,type_dst=f32,ne=[256,4,3,1],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=1): [1;32mOK[0m
  CPY(type_src=f32,type_dst=f32,ne=[256,4,3,3],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=1): [1;32mOK[0m
  CPY(type_src=bf16,type_dst=bf16,ne=[256,4,3,1],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=1): not supported [SYCL0] 
  CPY(type_src=f16,type_dst=f16,ne=[256,4,1,1],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=1): [1;32mOK[0m
  CPY(type_src=f32,type_dst=f32,ne=[256,4,1,1],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=1): [1;32mOK[0m
  CPY(type_src=bf16,type_dst=bf16,ne=[256,4,1,1],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=1): not supported [SYCL0] 
  CPY(type_src=i32,type_dst=i32,ne=[256,4,1,1],permute_src=[0,0,0,0],permute_dst=[0,0,0,0],_src_transpose=1): not supported [SYCL0] 
  CPY(type_src=i32,type_dst=i32,ne=[256,1,4,1],permute_src=[1,2,0,3],permute_dst=[0,0,0,0],_src_transpose=0): not supported [SYCL0] 
  CPY(type_src=f32,type_dst=f32,ne=[256,1,4,1],permute_src=[1,2,0,3],permute_dst=[0,0,0,0],_src_transpose=0): [1;32mOK[0m
  CONT(type=f32,ne=[2,1,1,1],use_view_slice=1): [1;32mOK[0m
  CONT(type=f32,ne=[2,1,3,5],use_view_slice=1): [1;32mOK[0m
  CONT(type=f32,ne=[2,3,5,7],use_view_slice=1): [1;32mOK[0m
  CONT(type=f32,ne=[1,4,4,1],use_view_slice=1): [1;32mOK[0m
  CONT(type=f32,ne=[1,8,17,1],use_view_slice=1): [1;32mOK[0m
  CONT(type=f32,ne=[10,10,10,1],use_view_slice=1): [1;32mOK[0m
  CONT(type=f32,ne=[2,1,1,1],use_view_slice=0): [1;32mOK[0m
  CONT(type=f32,ne=[2,1,3,5],use_view_slice=0): [1;32mOK[0m
  CONT(type=f32,ne=[2,3,5,7],use_view_slice=0): [1;32mOK[0m
  CONT(type=f32,ne=[1,4,4,1],use_view_slice=0): [1;32mOK[0m
  CONT(type=f32,ne=[1,8,17,1],use_view_slice=0): [1;32mOK[0m
  CONT(type=f32,ne=[10,10,10,1],use_view_slice=0): [1;32mOK[0m
  CONT(type=i32,ne=[2,1,1,1],use_view_slice=1): [1;32mOK[0m
  CONT(type=i32,ne=[2,1,3,5],use_view_slice=1): [1;32mOK[0m
  CONT(type=i32,ne=[2,3,5,7],use_view_slice=1): [1;32mOK[0m
  CONT(type=i32,ne=[1,4,4,1],use_view_slice=1): [1;32mOK[0m
  CONT(type=i32,ne=[1,8,17,1],use_view_slice=1): [1;32mOK[0m
  CONT(type=i32,ne=[10,10,10,1],use_view_slice=1): [1;32mOK[0m
  CONT(type=i32,ne=[2,1,1,1],use_view_slice=0): [1;32mOK[0m
  CONT(type=i32,ne=[2,1,3,5],use_view_slice=0): [1;32mOK[0m
  CONT(type=i32,ne=[2,3,5,7],use_view_slice=0): [1;32mOK[0m
  CONT(type=i32,ne=[1,4,4,1],use_view_slice=0): [1;32mOK[0m
  CONT(type=i32,ne=[1,8,17,1],use_view_slice=0): [1;32mOK[0m
  CONT(type=i32,ne=[10,10,10,1],use_view_slice=0): [1;32mOK[0m
  CONT(type=f16,ne=[2,1,1,1],use_view_slice=0): [1;32mOK[0m
  CONT(type=f16,ne=[2,1,3,5],use_view_slice=0): [1;32mOK[0m
  CONT(type=f16,ne=[2,3,5,7],use_view_slice=0): [1;32mOK[0m
  CONT(type=f16,ne=[1,4,4,1],use_view_slice=0): [1;32mOK[0m
  CONT(type=f16,ne=[1,8,17,1],use_view_slice=0): [1;32mOK[0m
  CONT(type=f16,ne=[10,10,10,1],use_view_slice=0): [1;32mOK[0m
  CONT(type=bf16,ne=[2,1,1,1],use_view_slice=0): not supported [SYCL0] 
  CONT(type=bf16,ne=[2,1,3,5],use_view_slice=0): not supported [SYCL0] 
  CONT(type=bf16,ne=[2,3,5,7],use_view_slice=0): not supported [SYCL0] 
  CONT(type=bf16,ne=[1,4,4,1],use_view_slice=0): not supported [SYCL0] 
  CONT(type=bf16,ne=[1,8,17,1],use_view_slice=0): not supported [SYCL0] 
  CONT(type=bf16,ne=[10,10,10,1],use_view_slice=0): not supported [SYCL0] 
  ADD(type=f16,ne=[1,1,8,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  SUB(type=f16,ne=[1,1,8,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  MUL(type=f16,ne=[1,1,8,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  DIV(type=f16,ne=[1,1,8,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  ADD(type=f16,ne=[1,1,1,1],nr=[32,1,1,1],nf=1): [1;32mOK[0m
  SUB(type=f16,ne=[1,1,1,1],nr=[32,1,1,1],nf=1): [1;32mOK[0m
  MUL(type=f16,ne=[1,1,1,1],nr=[32,1,1,1],nf=1): [1;32mOK[0m
  DIV(type=f16,ne=[1,1,1,1],nr=[32,1,1,1],nf=1): [1;32mOK[0m
  ADD(type=f16,ne=[1,1,320,320],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  SUB(type=f16,ne=[1,1,320,320],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  MUL(type=f16,ne=[1,1,320,320],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  DIV(type=f16,ne=[1,1,320,320],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  ADD(type=f16,ne=[10,5,1,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  SUB(type=f16,ne=[10,5,1,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  MUL(type=f16,ne=[10,5,1,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  DIV(type=f16,ne=[10,5,1,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  ADD(type=f16,ne=[10,5,4,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  SUB(type=f16,ne=[10,5,4,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  MUL(type=f16,ne=[10,5,4,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  DIV(type=f16,ne=[10,5,4,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  ADD(type=f16,ne=[10,5,4,3],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  SUB(type=f16,ne=[10,5,4,3],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  MUL(type=f16,ne=[10,5,4,3],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  DIV(type=f16,ne=[10,5,4,3],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  ADD(type=f16,ne=[10,5,4,3],nr=[2,1,1,1],nf=1): [1;32mOK[0m
  SUB(type=f16,ne=[10,5,4,3],nr=[2,1,1,1],nf=1): [1;32mOK[0m
  MUL(type=f16,ne=[10,5,4,3],nr=[2,1,1,1],nf=1): [1;32mOK[0m
  DIV(type=f16,ne=[10,5,4,3],nr=[2,1,1,1],nf=1): [1;32mOK[0m
  ADD(type=f16,ne=[10,5,4,3],nr=[1,2,1,1],nf=1): [1;32mOK[0m
  SUB(type=f16,ne=[10,5,4,3],nr=[1,2,1,1],nf=1): [1;32mOK[0m
  MUL(type=f16,ne=[10,5,4,3],nr=[1,2,1,1],nf=1): [1;32mOK[0m
  DIV(type=f16,ne=[10,5,4,3],nr=[1,2,1,1],nf=1): [1;32mOK[0m
  ADD(type=f16,ne=[10,5,4,3],nr=[1,1,2,1],nf=1): [1;32mOK[0m
  SUB(type=f16,ne=[10,5,4,3],nr=[1,1,2,1],nf=1): [1;32mOK[0m
  MUL(type=f16,ne=[10,5,4,3],nr=[1,1,2,1],nf=1): [1;32mOK[0m
  DIV(type=f16,ne=[10,5,4,3],nr=[1,1,2,1],nf=1): [1;32mOK[0m
  ADD(type=f16,ne=[10,5,4,3],nr=[1,1,1,2],nf=1): [1;32mOK[0m
  SUB(type=f16,ne=[10,5,4,3],nr=[1,1,1,2],nf=1): [1;32mOK[0m
  MUL(type=f16,ne=[10,5,4,3],nr=[1,1,1,2],nf=1): [1;32mOK[0m
  DIV(type=f16,ne=[10,5,4,3],nr=[1,1,1,2],nf=1): [1;32mOK[0m
  ADD(type=f16,ne=[10,5,4,3],nr=[1,1,2,2],nf=1): [1;32mOK[0m
  SUB(type=f16,ne=[10,5,4,3],nr=[1,1,2,2],nf=1): [1;32mOK[0m
  MUL(type=f16,ne=[10,5,4,3],nr=[1,1,2,2],nf=1): [1;32mOK[0m
  DIV(type=f16,ne=[10,5,4,3],nr=[1,1,2,2],nf=1): [1;32mOK[0m
  ADD(type=f16,ne=[10,5,4,3],nr=[1,2,2,2],nf=1): [1;32mOK[0m
  SUB(type=f16,ne=[10,5,4,3],nr=[1,2,2,2],nf=1): [1;32mOK[0m
  MUL(type=f16,ne=[10,5,4,3],nr=[1,2,2,2],nf=1): [1;32mOK[0m
  DIV(type=f16,ne=[10,5,4,3],nr=[1,2,2,2],nf=1): [1;32mOK[0m
  ADD(type=f16,ne=[10,5,4,3],nr=[2,2,2,2],nf=1): [1;32mOK[0m
  SUB(type=f16,ne=[10,5,4,3],nr=[2,2,2,2],nf=1): [1;32mOK[0m
  MUL(type=f16,ne=[10,5,4,3],nr=[2,2,2,2],nf=1): [1;32mOK[0m
  DIV(type=f16,ne=[10,5,4,3],nr=[2,2,2,2],nf=1): [1;32mOK[0m
  ADD(type=f16,ne=[1,1,65536,1],nr=[256,1,1,1],nf=1): [1;32mOK[0m
  SUB(type=f16,ne=[1,1,65536,1],nr=[256,1,1,1],nf=1): [1;32mOK[0m
  MUL(type=f16,ne=[1,1,65536,1],nr=[256,1,1,1],nf=1): [1;32mOK[0m
  DIV(type=f16,ne=[1,1,65536,1],nr=[256,1,1,1],nf=1): [1;32mOK[0m
  ADD(type=f16,ne=[1280,1,1,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  SUB(type=f16,ne=[1280,1,1,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  MUL(type=f16,ne=[1280,1,1,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  DIV(type=f16,ne=[1280,1,1,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  ADD(type=f16,ne=[1280,1,1,1],nr=[1,16,16,1],nf=1): [1;32mOK[0m
  SUB(type=f16,ne=[1280,1,1,1],nr=[1,16,16,1],nf=1): [1;32mOK[0m
  MUL(type=f16,ne=[1280,1,1,1],nr=[1,16,16,1],nf=1): [1;32mOK[0m
  DIV(type=f16,ne=[1280,1,1,1],nr=[1,16,16,1],nf=1): [1;32mOK[0m
  ADD(type=f16,ne=[1280,16,16,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  SUB(type=f16,ne=[1280,16,16,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  MUL(type=f16,ne=[1280,16,16,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  DIV(type=f16,ne=[1280,16,16,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  ADD(type=f16,ne=[1280,1,1,1],nr=[1,256,1,1],nf=1): [1;32mOK[0m
  SUB(type=f16,ne=[1280,1,1,1],nr=[1,256,1,1],nf=1): [1;32mOK[0m
  MUL(type=f16,ne=[1280,1,1,1],nr=[1,256,1,1],nf=1): [1;32mOK[0m
  DIV(type=f16,ne=[1280,1,1,1],nr=[1,256,1,1],nf=1): [1;32mOK[0m
  ADD(type=f16,ne=[1,1,1280,1],nr=[16,16,1,1],nf=1): [1;32mOK[0m
  SUB(type=f16,ne=[1,1,1280,1],nr=[16,16,1,1],nf=1): [1;32mOK[0m
  MUL(type=f16,ne=[1,1,1280,1],nr=[16,16,1,1],nf=1): [1;32mOK[0m
  DIV(type=f16,ne=[1,1,1280,1],nr=[16,16,1,1],nf=1): [1;32mOK[0m
  ADD(type=f16,ne=[16,16,1280,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  SUB(type=f16,ne=[16,16,1280,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  MUL(type=f16,ne=[16,16,1280,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  DIV(type=f16,ne=[16,16,1280,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  ADD(type=f16,ne=[1,1,1920,1],nr=[16,16,1,1],nf=1): [1;32mOK[0m
  SUB(type=f16,ne=[1,1,1920,1],nr=[16,16,1,1],nf=1): [1;32mOK[0m
  MUL(type=f16,ne=[1,1,1920,1],nr=[16,16,1,1],nf=1): [1;32mOK[0m
  DIV(type=f16,ne=[1,1,1920,1],nr=[16,16,1,1],nf=1): [1;32mOK[0m
  ADD(type=f16,ne=[1,1,2560,1],nr=[16,16,1,1],nf=1): [1;32mOK[0m
  SUB(type=f16,ne=[1,1,2560,1],nr=[16,16,1,1],nf=1): [1;32mOK[0m
  MUL(type=f16,ne=[1,1,2560,1],nr=[16,16,1,1],nf=1): [1;32mOK[0m
  DIV(type=f16,ne=[1,1,2560,1],nr=[16,16,1,1],nf=1): [1;32mOK[0m
  ADD(type=f16,ne=[1,1,1280,1],nr=[32,32,1,1],nf=1): [1;32mOK[0m
  SUB(type=f16,ne=[1,1,1280,1],nr=[32,32,1,1],nf=1): [1;32mOK[0m
  MUL(type=f16,ne=[1,1,1280,1],nr=[32,32,1,1],nf=1): [1;32mOK[0m
  DIV(type=f16,ne=[1,1,1280,1],nr=[32,32,1,1],nf=1): [1;32mOK[0m
  ADD(type=f16,ne=[1,1,1920,1],nr=[32,32,1,1],nf=1): [1;32mOK[0m
  SUB(type=f16,ne=[1,1,1920,1],nr=[32,32,1,1],nf=1): [1;32mOK[0m
  MUL(type=f16,ne=[1,1,1920,1],nr=[32,32,1,1],nf=1): [1;32mOK[0m
  DIV(type=f16,ne=[1,1,1920,1],nr=[32,32,1,1],nf=1): [1;32mOK[0m
  ADD(type=f16,ne=[1,1,640,1],nr=[32,32,1,1],nf=1): [1;32mOK[0m
  SUB(type=f16,ne=[1,1,640,1],nr=[32,32,1,1],nf=1): [1;32mOK[0m
  MUL(type=f16,ne=[1,1,640,1],nr=[32,32,1,1],nf=1): [1;32mOK[0m
  DIV(type=f16,ne=[1,1,640,1],nr=[32,32,1,1],nf=1): [1;32mOK[0m
  ADD(type=f16,ne=[5120,1,1,1],nr=[1,256,1,1],nf=1): [1;32mOK[0m
  SUB(type=f16,ne=[5120,1,1,1],nr=[1,256,1,1],nf=1): [1;32mOK[0m
  MUL(type=f16,ne=[5120,1,1,1],nr=[1,256,1,1],nf=1): [1;32mOK[0m
  DIV(type=f16,ne=[5120,1,1,1],nr=[1,256,1,1],nf=1): [1;32mOK[0m
  ADD(type=f16,ne=[640,1,1,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  SUB(type=f16,ne=[640,1,1,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  MUL(type=f16,ne=[640,1,1,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  DIV(type=f16,ne=[640,1,1,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  ADD(type=f16,ne=[64,262144,1,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  SUB(type=f16,ne=[64,262144,1,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  MUL(type=f16,ne=[64,262144,1,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  DIV(type=f16,ne=[64,262144,1,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  ADD(type=f32,ne=[1,1,8,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  SUB(type=f32,ne=[1,1,8,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  MUL(type=f32,ne=[1,1,8,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  DIV(type=f32,ne=[1,1,8,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  ADD(type=f32,ne=[1,1,1,1],nr=[32,1,1,1],nf=1): [1;32mOK[0m
  SUB(type=f32,ne=[1,1,1,1],nr=[32,1,1,1],nf=1): [1;32mOK[0m
  MUL(type=f32,ne=[1,1,1,1],nr=[32,1,1,1],nf=1): [1;32mOK[0m
  DIV(type=f32,ne=[1,1,1,1],nr=[32,1,1,1],nf=1): [1;32mOK[0m
  ADD(type=f32,ne=[1,1,320,320],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  SUB(type=f32,ne=[1,1,320,320],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  MUL(type=f32,ne=[1,1,320,320],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  DIV(type=f32,ne=[1,1,320,320],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  ADD(type=f32,ne=[10,5,1,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  SUB(type=f32,ne=[10,5,1,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  MUL(type=f32,ne=[10,5,1,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  DIV(type=f32,ne=[10,5,1,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  ADD(type=f32,ne=[10,5,4,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  SUB(type=f32,ne=[10,5,4,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  MUL(type=f32,ne=[10,5,4,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  DIV(type=f32,ne=[10,5,4,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  ADD(type=f32,ne=[10,5,4,3],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  SUB(type=f32,ne=[10,5,4,3],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  MUL(type=f32,ne=[10,5,4,3],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  DIV(type=f32,ne=[10,5,4,3],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  ADD(type=f32,ne=[10,5,4,3],nr=[2,1,1,1],nf=1): [1;32mOK[0m
  SUB(type=f32,ne=[10,5,4,3],nr=[2,1,1,1],nf=1): [1;32mOK[0m
  MUL(type=f32,ne=[10,5,4,3],nr=[2,1,1,1],nf=1): [1;32mOK[0m
  DIV(type=f32,ne=[10,5,4,3],nr=[2,1,1,1],nf=1): [1;32mOK[0m
  ADD(type=f32,ne=[10,5,4,3],nr=[1,2,1,1],nf=1): [1;32mOK[0m
  SUB(type=f32,ne=[10,5,4,3],nr=[1,2,1,1],nf=1): [1;32mOK[0m
  MUL(type=f32,ne=[10,5,4,3],nr=[1,2,1,1],nf=1): [1;32mOK[0m
  DIV(type=f32,ne=[10,5,4,3],nr=[1,2,1,1],nf=1): [1;32mOK[0m
  ADD(type=f32,ne=[10,5,4,3],nr=[1,1,2,1],nf=1): [1;32mOK[0m
  SUB(type=f32,ne=[10,5,4,3],nr=[1,1,2,1],nf=1): [1;32mOK[0m
  MUL(type=f32,ne=[10,5,4,3],nr=[1,1,2,1],nf=1): [1;32mOK[0m
  DIV(type=f32,ne=[10,5,4,3],nr=[1,1,2,1],nf=1): [1;32mOK[0m
  ADD(type=f32,ne=[10,5,4,3],nr=[1,1,1,2],nf=1): [1;32mOK[0m
  SUB(type=f32,ne=[10,5,4,3],nr=[1,1,1,2],nf=1): [1;32mOK[0m
  MUL(type=f32,ne=[10,5,4,3],nr=[1,1,1,2],nf=1): [1;32mOK[0m
  DIV(type=f32,ne=[10,5,4,3],nr=[1,1,1,2],nf=1): [1;32mOK[0m
  ADD(type=f32,ne=[10,5,4,3],nr=[1,1,2,2],nf=1): [1;32mOK[0m
  SUB(type=f32,ne=[10,5,4,3],nr=[1,1,2,2],nf=1): [1;32mOK[0m
  MUL(type=f32,ne=[10,5,4,3],nr=[1,1,2,2],nf=1): [1;32mOK[0m
  DIV(type=f32,ne=[10,5,4,3],nr=[1,1,2,2],nf=1): [1;32mOK[0m
  ADD(type=f32,ne=[10,5,4,3],nr=[1,2,2,2],nf=1): [1;32mOK[0m
  SUB(type=f32,ne=[10,5,4,3],nr=[1,2,2,2],nf=1): [1;32mOK[0m
  MUL(type=f32,ne=[10,5,4,3],nr=[1,2,2,2],nf=1): [1;32mOK[0m
  DIV(type=f32,ne=[10,5,4,3],nr=[1,2,2,2],nf=1): [1;32mOK[0m
  ADD(type=f32,ne=[10,5,4,3],nr=[2,2,2,2],nf=1): [1;32mOK[0m
  SUB(type=f32,ne=[10,5,4,3],nr=[2,2,2,2],nf=1): [1;32mOK[0m
  MUL(type=f32,ne=[10,5,4,3],nr=[2,2,2,2],nf=1): [1;32mOK[0m
  DIV(type=f32,ne=[10,5,4,3],nr=[2,2,2,2],nf=1): [1;32mOK[0m
  ADD(type=f32,ne=[1,1,65536,1],nr=[256,1,1,1],nf=1): [1;32mOK[0m
  SUB(type=f32,ne=[1,1,65536,1],nr=[256,1,1,1],nf=1): [1;32mOK[0m
  MUL(type=f32,ne=[1,1,65536,1],nr=[256,1,1,1],nf=1): [1;32mOK[0m
  DIV(type=f32,ne=[1,1,65536,1],nr=[256,1,1,1],nf=1): [1;32mOK[0m
  ADD(type=f32,ne=[1280,1,1,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  SUB(type=f32,ne=[1280,1,1,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  MUL(type=f32,ne=[1280,1,1,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  DIV(type=f32,ne=[1280,1,1,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  ADD(type=f32,ne=[1280,1,1,1],nr=[1,16,16,1],nf=1): [1;32mOK[0m
  SUB(type=f32,ne=[1280,1,1,1],nr=[1,16,16,1],nf=1): [1;32mOK[0m
  MUL(type=f32,ne=[1280,1,1,1],nr=[1,16,16,1],nf=1): [1;32mOK[0m
  DIV(type=f32,ne=[1280,1,1,1],nr=[1,16,16,1],nf=1): [1;32mOK[0m
  ADD(type=f32,ne=[1280,16,16,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  SUB(type=f32,ne=[1280,16,16,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  MUL(type=f32,ne=[1280,16,16,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  DIV(type=f32,ne=[1280,16,16,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  ADD(type=f32,ne=[1280,1,1,1],nr=[1,256,1,1],nf=1): [1;32mOK[0m
  SUB(type=f32,ne=[1280,1,1,1],nr=[1,256,1,1],nf=1): [1;32mOK[0m
  MUL(type=f32,ne=[1280,1,1,1],nr=[1,256,1,1],nf=1): [1;32mOK[0m
  DIV(type=f32,ne=[1280,1,1,1],nr=[1,256,1,1],nf=1): [1;32mOK[0m
  ADD(type=f32,ne=[1,1,1280,1],nr=[16,16,1,1],nf=1): [1;32mOK[0m
  SUB(type=f32,ne=[1,1,1280,1],nr=[16,16,1,1],nf=1): [1;32mOK[0m
  MUL(type=f32,ne=[1,1,1280,1],nr=[16,16,1,1],nf=1): [1;32mOK[0m
  DIV(type=f32,ne=[1,1,1280,1],nr=[16,16,1,1],nf=1): [1;32mOK[0m
  ADD(type=f32,ne=[16,16,1280,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  SUB(type=f32,ne=[16,16,1280,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  MUL(type=f32,ne=[16,16,1280,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  DIV(type=f32,ne=[16,16,1280,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  ADD(type=f32,ne=[1,1,1920,1],nr=[16,16,1,1],nf=1): [1;32mOK[0m
  SUB(type=f32,ne=[1,1,1920,1],nr=[16,16,1,1],nf=1): [1;32mOK[0m
  MUL(type=f32,ne=[1,1,1920,1],nr=[16,16,1,1],nf=1): [1;32mOK[0m
  DIV(type=f32,ne=[1,1,1920,1],nr=[16,16,1,1],nf=1): [1;32mOK[0m
  ADD(type=f32,ne=[1,1,2560,1],nr=[16,16,1,1],nf=1): [1;32mOK[0m
  SUB(type=f32,ne=[1,1,2560,1],nr=[16,16,1,1],nf=1): [1;32mOK[0m
  MUL(type=f32,ne=[1,1,2560,1],nr=[16,16,1,1],nf=1): [1;32mOK[0m
  DIV(type=f32,ne=[1,1,2560,1],nr=[16,16,1,1],nf=1): [1;32mOK[0m
  ADD(type=f32,ne=[1,1,1280,1],nr=[32,32,1,1],nf=1): [1;32mOK[0m
  SUB(type=f32,ne=[1,1,1280,1],nr=[32,32,1,1],nf=1): [1;32mOK[0m
  MUL(type=f32,ne=[1,1,1280,1],nr=[32,32,1,1],nf=1): [1;32mOK[0m
  DIV(type=f32,ne=[1,1,1280,1],nr=[32,32,1,1],nf=1): [1;32mOK[0m
  ADD(type=f32,ne=[1,1,1920,1],nr=[32,32,1,1],nf=1): [1;32mOK[0m
  SUB(type=f32,ne=[1,1,1920,1],nr=[32,32,1,1],nf=1): [1;32mOK[0m
  MUL(type=f32,ne=[1,1,1920,1],nr=[32,32,1,1],nf=1): [1;32mOK[0m
  DIV(type=f32,ne=[1,1,1920,1],nr=[32,32,1,1],nf=1): [1;32mOK[0m
  ADD(type=f32,ne=[1,1,640,1],nr=[32,32,1,1],nf=1): [1;32mOK[0m
  SUB(type=f32,ne=[1,1,640,1],nr=[32,32,1,1],nf=1): [1;32mOK[0m
  MUL(type=f32,ne=[1,1,640,1],nr=[32,32,1,1],nf=1): [1;32mOK[0m
  DIV(type=f32,ne=[1,1,640,1],nr=[32,32,1,1],nf=1): [1;32mOK[0m
  ADD(type=f32,ne=[5120,1,1,1],nr=[1,256,1,1],nf=1): [1;32mOK[0m
  SUB(type=f32,ne=[5120,1,1,1],nr=[1,256,1,1],nf=1): [1;32mOK[0m
  MUL(type=f32,ne=[5120,1,1,1],nr=[1,256,1,1],nf=1): [1;32mOK[0m
  DIV(type=f32,ne=[5120,1,1,1],nr=[1,256,1,1],nf=1): [1;32mOK[0m
  ADD(type=f32,ne=[640,1,1,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  SUB(type=f32,ne=[640,1,1,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  MUL(type=f32,ne=[640,1,1,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  DIV(type=f32,ne=[640,1,1,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  ADD(type=f32,ne=[64,262144,1,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  SUB(type=f32,ne=[64,262144,1,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  MUL(type=f32,ne=[64,262144,1,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  DIV(type=f32,ne=[64,262144,1,1],nr=[1,1,1,1],nf=1): [1;32mOK[0m
  ADD(type=f32,ne=[16,5,4,3],nr=[1,1,1,1],nf=16): [1;32mOK[0m
  MUL(type=f32,ne=[16,5,4,3],nr=[1,1,1,1],nf=16): [1;32mOK[0m
  SUB(type=f32,ne=[16,5,4,3],nr=[1,1,1,1],nf=16): [1;32mOK[0m
  DIV(type=f32,ne=[16,5,4,3],nr=[1,1,1,1],nf=16): [1;32mOK[0m
  ADD(type=f32,ne=[10,5,4,3],nr=[2,1,1,1],nf=2): [1;32mOK[0m
  ADD(type=f32,ne=[16,5,4,3],nr=[1,2,1,1],nf=3): [1;32mOK[0m
  ADD(type=f32,ne=[10,5,4,3],nr=[1,1,2,1],nf=4): [1;32mOK[0m
  ADD(type=f32,ne=[16,5,4,3],nr=[1,1,1,2],nf=5): [1;32mOK[0m
  ADD(type=f32,ne=[10,5,4,3],nr=[1,1,2,2],nf=6): [1;32mOK[0m
  ADD(type=f32,ne=[10,5,4,3],nr=[1,2,2,2],nf=7): [1;32mOK[0m
  ADD(type=f32,ne=[16,5,4,3],nr=[2,2,2,2],nf=8): [1;32mOK[0m
  ADD(type=f32,ne=[16,5,4,3],nr=[1,1,1,1],nf=16): [1;32mOK[0m
  ADD1(type=f32,ne=[10,5,4,3]): [1;32mOK[0m
  ADD1(type=f32,ne=[1024,1024,1,1]): [1;32mOK[0m
  SCALE(type=f32,ne=[10,10,10,10],scale=2.000000,bias=0.000000,inplace=0): [1;32mOK[0m
  SCALE(type=f32,ne=[10,10,10,10],scale=2.000000,bias=1.000000,inplace=0): [1;32mOK[0m
  SCALE(type=f32,ne=[10,10,10,10],scale=2.000000,bias=1.000000,inplace=1): [1;32mOK[0m
  SCALE(type=f32,ne=[100,10,10,10],scale=2.000000,bias=1.000000,inplace=0): [1;32mOK[0m
  SOFTCAP(type=f32,ne=[10,10,10,10],softcap=50.000000): [1;32mOK[0m
  SILU_BACK(type=f32,ne=[64,5,4,3],eps=0.000001): not supported [SYCL0] 
  NORM(type=f32,ne=[64,5,4,3],v=0,eps=0.000000): [1;32mOK[0m
  RMS_NORM(type=f32,ne=[64,5,4,3],v=0,eps=0.000000,inplace=0): [1;32mOK[0m
  NORM(type=f32,ne=[64,5,4,3],v=1,eps=0.000000): [1;32mOK[0m
  RMS_NORM(type=f32,ne=[64,5,4,3],v=1,eps=0.000000,inplace=0): [1;32mOK[0m
  RMS_NORM_BACK(type=f32,ne=[64,5,4,3],eps=0.000000): [1;32mOK[0m
  L2_NORM(type=f32,ne=[64,5,4,3]): [1;32mOK[0m
/home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/ggml/src/ggml-sycl/norm.cpp:254: GGML_ASSERT(ncols % WARP_SIZE == 0) failed
[New LWP 154118]
[New LWP 154117]
[New LWP 154116]
[New LWP 152479]
warning: File "/opt/intel/oneapi/compiler/2025.3/lib/libsycl.so.8.0.0-gdb.py" auto-loading has been declined by your `auto-load safe-path' set to "$debugdir:$datadir/auto-load".
To enable execution of this file add
	add-auto-load-safe-path /opt/intel/oneapi/compiler/2025.3/lib/libsycl.so.8.0.0-gdb.py
line to your configuration file "/home/zjy/.config/gdb/gdbinit".
To completely disable this security protection add
	set auto-load safe-path /
line to your configuration file "/home/zjy/.config/gdb/gdbinit".
For more information about this security protection see the
"Auto-loading safe path" section in the GDB manual.  E.g., run from the shell:
	info "(gdb)Auto-loading safe path"
[Thread debugging using libthread_db enabled]
Using host libthread_db library "/lib/x86_64-linux-gnu/libthread_db.so.1".
0x00007ac99ad10813 in __GI___wait4 (pid=307707, stat_loc=0x0, options=0, usage=0x0) at ../sysdeps/unix/sysv/linux/wait4.c:30
warning: 30	../sysdeps/unix/sysv/linux/wait4.c: No such file or directory
#0  0x00007ac99ad10813 in __GI___wait4 (pid=307707, stat_loc=0x0, options=0, usage=0x0) at ../sysdeps/unix/sysv/linux/wait4.c:30
30	in ../sysdeps/unix/sysv/linux/wait4.c
#1  0x00007ac99bd25103 in ggml_print_backtrace () from /home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/build-ci-release/bin/libggml-base.so.0
#2  0x00007ac99bd252ab in ggml_abort () from /home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/build-ci-release/bin/libggml-base.so.0
#3  0x00007ac99b559b29 in ggml_sycl_op_norm(ggml_backend_sycl_context&, ggml_tensor*) () from /home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/build-ci-release/bin/libggml-sycl.so.0
#4  0x00007ac99b452902 in ggml_sycl_norm(ggml_backend_sycl_context&, ggml_tensor*) () from /home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/build-ci-release/bin/libggml-sycl.so.0
#5  0x00007ac99b451d5e in ggml_backend_sycl_graph_compute_impl(ggml_backend_sycl_context*, ggml_cgraph*) () from /home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/build-ci-release/bin/libggml-sycl.so.0
#6  0x00007ac99b4507d7 in ggml_backend_sycl_graph_compute(ggml_backend*, ggml_cgraph*) () from /home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/build-ci-release/bin/libggml-sycl.so.0
#7  0x00007ac99bd4416c in ggml_backend_compare_graph_backend () from /home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/build-ci-release/bin/libggml-base.so.0
#8  0x00000000004ce367 in test_case::eval(ggml_backend*, ggml_backend*, char const*, printer*) ()
#9  0x00000000004140ce in main ()
[Inferior 1 (process 152478) detached]

      Start 40: test-barrier
36/41 Test #40: test-barrier ......................   Passed    1.17 sec
      Start 41: test-quantize-fns
37/41 Test #41: test-quantize-fns .................   Passed   12.39 sec
      Start 42: test-quantize-perf
38/41 Test #42: test-quantize-perf ................   Passed    0.09 sec
      Start 43: test-rope
39/41 Test #43: test-rope .........................   Passed    0.09 sec
      Start 44: test-m.html-c-api
40/41 Test #44: test-m.html-c-api ...................   Passed    0.04 sec
      Start 45: test-alloc
41/41 Test #45: test-alloc ........................   Passed    0.04 sec

90% tests passed, 4 tests failed out of 41

Label Time Summary:
main    =  46.72 sec*proc (40 tests)

Total Test time (real) = 179.37 sec

The following tests FAILED:
	 14 - test-tokenizers-ggml-vocabs (Failed)
	 30 - test-download-model (Failed)
	 31 - test-thread-safety (Not Run)
	 35 - test-backend-ops (Subprocess aborted)
Errors while running CTest

real	2m59.385s
user	0m41.828s
sys	0m16.075s
```
