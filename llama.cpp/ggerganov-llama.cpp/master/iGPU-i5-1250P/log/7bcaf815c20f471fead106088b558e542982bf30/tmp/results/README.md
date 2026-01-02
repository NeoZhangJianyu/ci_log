### ctest_release

Runs ctest in release mode
- status: 8
```
+ ctest --output-on-failure -L main
Test project /home/zjy/ws/jenkins-home/workspace/ci-1250/ggerganov-llama.cpp/build-ci-release
      Start  1: test-tokenizer-0-bert-bge
 1/39 Test  #1: test-tokenizer-0-bert-bge .........   Passed    0.12 sec
      Start  2: test-tokenizer-0-command-r
 2/39 Test  #2: test-tokenizer-0-command-r ........   Passed    0.45 sec
      Start  3: test-tokenizer-0-deepseek-coder
 3/39 Test  #3: test-tokenizer-0-deepseek-coder ...   Passed    0.13 sec
      Start  4: test-tokenizer-0-deepseek-llm
 4/39 Test  #4: test-tokenizer-0-deepseek-llm .....   Passed    0.20 sec
      Start  5: test-tokenizer-0-falcon
 5/39 Test  #5: test-tokenizer-0-falcon ...........   Passed    0.15 sec
      Start  6: test-tokenizer-0-gpt-2
 6/39 Test  #6: test-tokenizer-0-gpt-2 ............   Passed    0.14 sec
      Start  7: test-tokenizer-0-llama-bpe
 7/39 Test  #7: test-tokenizer-0-llama-bpe ........   Passed    0.29 sec
      Start  8: test-tokenizer-0-llama-spm
 8/39 Test  #8: test-tokenizer-0-llama-spm ........   Passed    0.11 sec
      Start  9: test-tokenizer-0-mpt
 9/39 Test  #9: test-tokenizer-0-mpt ..............   Passed    0.14 sec
      Start 10: test-tokenizer-0-phi-3
10/39 Test #10: test-tokenizer-0-phi-3 ............   Passed    0.11 sec
      Start 11: test-tokenizer-0-qwen2
11/39 Test #11: test-tokenizer-0-qwen2 ............   Passed    0.28 sec
      Start 12: test-tokenizer-0-refact
12/39 Test #12: test-tokenizer-0-refact ...........   Passed    0.13 sec
      Start 13: test-tokenizer-0-starcoder
13/39 Test #13: test-tokenizer-0-starcoder ........   Passed    0.13 sec
      Start 14: test-tokenizers-ggml-vocabs
14/39 Test #14: test-tokenizers-ggml-vocabs .......***Failed    3.18 sec
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
15/39 Test #15: test-sampling .....................   Passed    0.97 sec
      Start 16: test-grammar-parser
16/39 Test #16: test-grammar-parser ...............   Passed    0.03 sec
      Start 17: test-grammar-integration
17/39 Test #17: test-grammar-integration ..........   Passed    0.04 sec
      Start 18: test-llama-grammar
18/39 Test #18: test-llama-grammar ................   Passed    0.03 sec
      Start 19: test-chat
19/39 Test #19: test-chat .........................   Passed    1.47 sec
      Start 20: test-json-schema-to-grammar
20/39 Test #20: test-json-schema-to-grammar .......   Passed    1.84 sec
      Start 21: test-tokenizer-1-llama-spm
21/39 Test #21: test-tokenizer-1-llama-spm ........   Passed    0.22 sec
      Start 22: test-chat-parser
22/39 Test #22: test-chat-parser ..................   Passed    0.03 sec
      Start 23: test-chat-peg-parser
23/39 Test #23: test-chat-peg-parser ..............   Passed    0.07 sec
      Start 24: test-chat-template
24/39 Test #24: test-chat-template ................   Passed    0.11 sec
      Start 25: test-json-partial
25/39 Test #25: test-json-partial .................   Passed    0.03 sec
      Start 26: test-log
26/39 Test #26: test-log ..........................   Passed    0.04 sec
      Start 27: test-peg-parser
27/39 Test #27: test-peg-parser ...................   Passed    0.04 sec
      Start 28: test-regex-partial
28/39 Test #28: test-regex-partial ................   Passed    0.03 sec
      Start 29: test-thread-safety
29/39 Test #29: test-thread-safety ................***Failed    0.09 sec
'https' scheme is not supported.

      Start 30: test-arg-parser
30/39 Test #30: test-arg-parser ...................   Passed   20.64 sec
      Start 31: test-opt
31/39 Test #31: test-opt ..........................   Passed    0.22 sec
      Start 32: test-gguf
32/39 Test #32: test-gguf .........................   Passed    0.30 sec
      Start 33: test-backend-ops
33/39 Test #33: test-backend-ops ..................   Passed  111.57 sec
      Start 37: test-barrier
34/39 Test #37: test-barrier ......................   Passed    1.37 sec
      Start 38: test-quantize-fns
35/39 Test #38: test-quantize-fns .................   Passed   14.04 sec
      Start 39: test-quantize-perf
36/39 Test #39: test-quantize-perf ................   Passed    0.09 sec
      Start 40: test-rope
37/39 Test #40: test-rope .........................   Passed    0.09 sec
      Start 41: test-mtmd-c-api
38/39 Test #41: test-mtmd-c-api ...................   Passed    0.04 sec
      Start 42: test-alloc
39/39 Test #42: test-alloc ........................   Passed    0.03 sec

95% tests passed, 2 tests failed out of 39

Label Time Summary:
main    = 159.01 sec*proc (39 tests)

Total Test time (real) = 159.03 sec

The following tests FAILED:
	 14 - test-tokenizers-ggml-vocabs (Failed)
	 29 - test-thread-safety (Failed)
Errors while running CTest

real	2m39.036s
user	3m35.740s
sys	1m4.696s
```
