### ctest_release

Runs ctest in release mode
- status: 8
```
+ ctest --output-on-failure -L main
Test project /home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/build-ci-release
      Start  1: test-tokenizer-0-bert-bge
 1/34 Test  #1: test-tokenizer-0-bert-bge .........   Passed    0.08 sec
      Start  2: test-tokenizer-0-command-r
 2/34 Test  #2: test-tokenizer-0-command-r ........   Passed    0.36 sec
      Start  3: test-tokenizer-0-deepseek-coder
 3/34 Test  #3: test-tokenizer-0-deepseek-coder ...   Passed    0.10 sec
      Start  4: test-tokenizer-0-deepseek-llm
 4/34 Test  #4: test-tokenizer-0-deepseek-llm .....   Passed    0.16 sec
      Start  5: test-tokenizer-0-falcon
 5/34 Test  #5: test-tokenizer-0-falcon ...........   Passed    0.11 sec
      Start  6: test-tokenizer-0-gpt-2
 6/34 Test  #6: test-tokenizer-0-gpt-2 ............   Passed    0.10 sec
      Start  7: test-tokenizer-0-llama-bpe
 7/34 Test  #7: test-tokenizer-0-llama-bpe ........   Passed    0.25 sec
      Start  8: test-tokenizer-0-llama-spm
 8/34 Test  #8: test-tokenizer-0-llama-spm ........   Passed    0.08 sec
      Start  9: test-tokenizer-0-mpt
 9/34 Test  #9: test-tokenizer-0-mpt ..............   Passed    0.10 sec
      Start 10: test-tokenizer-0-phi-3
10/34 Test #10: test-tokenizer-0-phi-3 ............   Passed    0.07 sec
      Start 11: test-tokenizer-0-qwen2
11/34 Test #11: test-tokenizer-0-qwen2 ............   Passed    0.22 sec
      Start 12: test-tokenizer-0-refact
12/34 Test #12: test-tokenizer-0-refact ...........   Passed    0.10 sec
      Start 13: test-tokenizer-0-starcoder
13/34 Test #13: test-tokenizer-0-starcoder ........   Passed    0.10 sec
      Start 14: test-tokenizers-ggml-vocabs
14/34 Test #14: test-tokenizers-ggml-vocabs .......***Failed    2.40 sec
Already up to date.
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
15/34 Test #15: test-sampling .....................   Passed    0.97 sec
      Start 16: test-grammar-parser
16/34 Test #16: test-grammar-parser ...............   Passed    0.03 sec
      Start 17: test-grammar-integration
17/34 Test #17: test-grammar-integration ..........   Passed    0.03 sec
      Start 18: test-llama-grammar
18/34 Test #18: test-llama-grammar ................   Passed    0.03 sec
      Start 19: test-chat
19/34 Test #19: test-chat .........................   Passed    0.39 sec
      Start 20: test-json-schema-to-grammar
20/34 Test #20: test-json-schema-to-grammar .......   Passed    1.78 sec
      Start 21: test-tokenizer-1-llama-spm
21/34 Test #21: test-tokenizer-1-llama-spm ........   Passed    0.17 sec
      Start 22: test-chat-parser
22/34 Test #22: test-chat-parser ..................   Passed    0.03 sec
      Start 23: test-chat-template
23/34 Test #23: test-chat-template ................   Passed    0.10 sec
      Start 24: test-json-partial
24/34 Test #24: test-json-partial .................   Passed    0.03 sec
      Start 25: test-log
25/34 Test #25: test-log ..........................   Passed    0.04 sec
      Start 26: test-regex-partial
26/34 Test #26: test-regex-partial ................   Passed    0.03 sec
      Start 27: test-arg-parser
27/34 Test #27: test-arg-parser ...................   Passed    0.08 sec
      Start 28: test-gguf
28/34 Test #28: test-gguf .........................   Passed    0.28 sec
      Start 29: test-backend-ops
29/34 Test #29: test-backend-ops ..................   Passed   27.06 sec
      Start 32: test-barrier
30/34 Test #32: test-barrier ......................   Passed    1.00 sec
      Start 33: test-quantize-fns
31/34 Test #33: test-quantize-fns .................   Passed   12.73 sec
      Start 34: test-quantize-perf
32/34 Test #34: test-quantize-perf ................   Passed    0.08 sec
      Start 35: test-rope
33/34 Test #35: test-rope .........................   Passed    0.08 sec
      Start 36: test-mtmd-c-api
34/34 Test #36: test-mtmd-c-api ...................   Passed    0.03 sec

97% tests passed, 1 tests failed out of 34

Label Time Summary:
main    =  49.22 sec*proc (34 tests)

Total Test time (real) =  49.23 sec

The following tests FAILED:
	 14 - test-tokenizers-ggml-vocabs (Failed)
Errors while running CTest

real	0m49.261s
user	0m52.418s
sys	0m10.488s
```
