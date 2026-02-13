### ctest_release

Runs ctest in release mode
- status: 8
```
+ ctest --output-on-failure -L main
Test project /home/zjy/ws/jenkins-home/workspace/ci-1250/ggerganov-llama.cpp/build-ci-release
      Start  1: test-tokenizer-0-bert-bge
 1/41 Test  #1: test-tokenizer-0-bert-bge .........   Passed    0.66 sec
      Start  2: test-tokenizer-0-command-r
 2/41 Test  #2: test-tokenizer-0-command-r ........   Passed    0.46 sec
      Start  3: test-tokenizer-0-deepseek-coder
 3/41 Test  #3: test-tokenizer-0-deepseek-coder ...   Passed    0.13 sec
      Start  4: test-tokenizer-0-deepseek-llm
 4/41 Test  #4: test-tokenizer-0-deepseek-llm .....   Passed    0.20 sec
      Start  5: test-tokenizer-0-falcon
 5/41 Test  #5: test-tokenizer-0-falcon ...........   Passed    0.17 sec
      Start  6: test-tokenizer-0-gpt-2
 6/41 Test  #6: test-tokenizer-0-gpt-2 ............   Passed    0.14 sec
      Start  7: test-tokenizer-0-llama-bpe
 7/41 Test  #7: test-tokenizer-0-llama-bpe ........   Passed    0.33 sec
      Start  8: test-tokenizer-0-llama-spm
 8/41 Test  #8: test-tokenizer-0-llama-spm ........   Passed    0.11 sec
      Start  9: test-tokenizer-0-mpt
 9/41 Test  #9: test-tokenizer-0-mpt ..............   Passed    0.14 sec
      Start 10: test-tokenizer-0-phi-3
10/41 Test #10: test-tokenizer-0-phi-3 ............   Passed    0.12 sec
      Start 11: test-tokenizer-0-qwen2
11/41 Test #11: test-tokenizer-0-qwen2 ............   Passed    0.29 sec
      Start 12: test-tokenizer-0-refact
12/41 Test #12: test-tokenizer-0-refact ...........   Passed    0.14 sec
      Start 13: test-tokenizer-0-starcoder
13/41 Test #13: test-tokenizer-0-starcoder ........   Passed    0.15 sec
      Start 14: test-tokenizers-ggml-vocabs
14/41 Test #14: test-tokenizers-ggml-vocabs .......***Failed    2.51 sec
Already up to date.
main : reading vocab from: '/home/zjy/ws/jenkins-home/workspace/ci-1250/ggerganov-llama.cpp/models/ggml-vocabs/PLaMo2/ggml-vocab-plamo2.gguf'
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
llama_model_load_from_file_impl: using device SYCL0 (Intel(R) Iris(R) Xe Graphics) (unknown id) - 29476 MiB free
gguf_init_from_file_impl: invalid magic characters: 'vers', expected 'GGUF'
llama_model_load: error loading model: llama_model_loader: failed to load model from /home/zjy/ws/jenkins-home/workspace/ci-1250/ggerganov-llama.cpp/models/ggml-vocabs/PLaMo2/ggml-vocab-plamo2.gguf
llama_model_load_from_file_impl: failed to load model
main: error: failed to load vocab '/home/zjy/ws/jenkins-home/workspace/ci-1250/ggerganov-llama.cpp/models/ggml-vocabs/PLaMo2/ggml-vocab-plamo2.gguf'
main : reading vocab from: '/home/zjy/ws/jenkins-home/workspace/ci-1250/ggerganov-llama.cpp/models/ggml-vocabs/RWKV/ggml-vocab-rwkv-7-world.gguf'
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
llama_model_load_from_file_impl: using device SYCL0 (Intel(R) Iris(R) Xe Graphics) (unknown id) - 29476 MiB free
gguf_init_from_file_impl: invalid magic characters: 'vers', expected 'GGUF'
llama_model_load: error loading model: llama_model_loader: failed to load model from /home/zjy/ws/jenkins-home/workspace/ci-1250/ggerganov-llama.cpp/models/ggml-vocabs/RWKV/ggml-vocab-rwkv-7-world.gguf
llama_model_load_from_file_impl: failed to load model
main: error: failed to load vocab '/home/zjy/ws/jenkins-home/workspace/ci-1250/ggerganov-llama.cpp/models/ggml-vocabs/RWKV/ggml-vocab-rwkv-7-world.gguf'
main : reading vocab from: '/home/zjy/ws/jenkins-home/workspace/ci-1250/ggerganov-llama.cpp/models/ggml-vocabs/SPM/ggml-vocab-gemma-3.gguf'
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
llama_model_load_from_file_impl: using device SYCL0 (Intel(R) Iris(R) Xe Graphics) (unknown id) - 29476 MiB free
gguf_init_from_file_impl: invalid magic characters: 'vers', expected 'GGUF'
llama_model_load: error loading model: llama_model_loader: failed to load model from /home/zjy/ws/jenkins-home/workspace/ci-1250/ggerganov-llama.cpp/models/ggml-vocabs/SPM/ggml-vocab-gemma-3.gguf
llama_model_load_from_file_impl: failed to load model
main: error: failed to load vocab '/home/zjy/ws/jenkins-home/workspace/ci-1250/ggerganov-llama.cpp/models/ggml-vocabs/SPM/ggml-vocab-gemma-3.gguf'
main : reading vocab from: '/home/zjy/ws/jenkins-home/workspace/ci-1250/ggerganov-llama.cpp/models/ggml-vocabs/UGM/ggml-vocab-nomic-bert-moe.gguf'
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
llama_model_load_from_file_impl: using device SYCL0 (Intel(R) Iris(R) Xe Graphics) (unknown id) - 29476 MiB free
gguf_init_from_file_impl: invalid magic characters: 'vers', expected 'GGUF'
llama_model_load: error loading model: llama_model_loader: failed to load model from /home/zjy/ws/jenkins-home/workspace/ci-1250/ggerganov-llama.cpp/models/ggml-vocabs/UGM/ggml-vocab-nomic-bert-moe.gguf
llama_model_load_from_file_impl: failed to load model
main: error: failed to load vocab '/home/zjy/ws/jenkins-home/workspace/ci-1250/ggerganov-llama.cpp/models/ggml-vocabs/UGM/ggml-vocab-nomic-bert-moe.gguf'
main : reading vocab from: '/home/zjy/ws/jenkins-home/workspace/ci-1250/ggerganov-llama.cpp/models/ggml-vocabs/WPM/ggml-vocab-jina-v2-en.gguf'
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
llama_model_load_from_file_impl: using device SYCL0 (Intel(R) Iris(R) Xe Graphics) (unknown id) - 29476 MiB free
gguf_init_from_file_impl: invalid magic characters: 'vers', expected 'GGUF'
llama_model_load: error loading model: llama_model_loader: failed to load model from /home/zjy/ws/jenkins-home/workspace/ci-1250/ggerganov-llama.cpp/models/ggml-vocabs/WPM/ggml-vocab-jina-v2-en.gguf
llama_model_load_from_file_impl: failed to load model
main: error: failed to load vocab '/home/zjy/ws/jenkins-home/workspace/ci-1250/ggerganov-llama.cpp/models/ggml-vocabs/WPM/ggml-vocab-jina-v2-en.gguf'

      Start 15: test-sampling
15/41 Test #15: test-sampling .....................   Passed    0.96 sec
      Start 16: test-grammar-parser
16/41 Test #16: test-grammar-parser ...............   Passed    0.03 sec
      Start 17: test-grammar-integration
17/41 Test #17: test-grammar-integration ..........   Passed    0.04 sec
      Start 18: test-llama-grammar
18/41 Test #18: test-llama-grammar ................   Passed    0.03 sec
      Start 19: test-chat
19/41 Test #19: test-chat .........................   Passed    0.66 sec
      Start 20: test-json-schema-to-grammar
20/41 Test #20: test-json-schema-to-grammar .......   Passed    1.79 sec
      Start 21: test-tokenizer-1-llama-spm
21/41 Test #21: test-tokenizer-1-llama-spm ........   Passed    0.21 sec
      Start 22: test-chat-parser
22/41 Test #22: test-chat-parser ..................   Passed    0.04 sec
      Start 23: test-chat-peg-parser
23/41 Test #23: test-chat-peg-parser ..............   Passed    0.07 sec
      Start 24: test-chat-template
24/41 Test #24: test-chat-template ................   Passed    0.05 sec
      Start 25: test-jinja
25/41 Test #25: test-jinja ........................   Passed    0.09 sec
      Start 27: test-json-partial
26/41 Test #27: test-json-partial .................   Passed    0.04 sec
      Start 28: test-log
27/41 Test #28: test-log ..........................   Passed    0.05 sec
      Start 29: test-peg-parser
28/41 Test #29: test-peg-parser ...................   Passed    0.04 sec
      Start 30: test-regex-partial
29/41 Test #30: test-regex-partial ................   Passed    0.03 sec
      Start 31: test-download-model
30/41 Test #31: test-download-model ...............***Failed  132.82 sec
-- Downloading tinyllamas/stories15M-q4_0.gguf from ggml-org/models...
CMake Error at /home/zjy/ws/jenkins-home/workspace/ci-1250/ggerganov-llama.cpp/cmake/download-models.cmake:8 (file):
  file DOWNLOAD cannot compute hash on failed download

    status: [28;"Timeout was reached"]



      Start 32: test-thread-safety
Failed test dependencies: test-download-model
31/41 Test #32: test-thread-safety ................***Not Run   0.00 sec
      Start 33: test-arg-parser
32/41 Test #33: test-arg-parser ...................   Passed    1.29 sec
      Start 34: test-opt
33/41 Test #34: test-opt ..........................   Passed    0.18 sec
      Start 35: test-gguf
34/41 Test #35: test-gguf .........................   Passed    0.39 sec
      Start 36: test-backend-ops
35/41 Test #36: test-backend-ops ..................   Passed  117.13 sec
      Start 41: test-barrier
36/41 Test #41: test-barrier ......................   Passed    1.38 sec
      Start 42: test-quantize-fns
37/41 Test #42: test-quantize-fns .................   Passed   13.92 sec
      Start 43: test-quantize-perf
38/41 Test #43: test-quantize-perf ................   Passed    0.09 sec
      Start 44: test-rope
39/41 Test #44: test-rope .........................   Passed    0.09 sec
      Start 45: test-mtmd-c-api
40/41 Test #45: test-mtmd-c-api ...................   Passed    0.04 sec
      Start 46: test-alloc
41/41 Test #46: test-alloc ........................   Passed    0.03 sec

93% tests passed, 3 tests failed out of 41

Label Time Summary:
main    = 144.22 sec*proc (40 tests)

Total Test time (real) = 277.06 sec

The following tests FAILED:
	 14 - test-tokenizers-ggml-vocabs (Failed)
	 31 - test-download-model (Failed)
	 32 - test-thread-safety (Not Run)
Errors while running CTest

real	4m37.104s
user	3m36.254s
sys	1m8.291s
```
