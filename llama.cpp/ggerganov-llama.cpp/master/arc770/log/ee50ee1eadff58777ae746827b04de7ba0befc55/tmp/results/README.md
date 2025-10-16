### ctest_release

Runs ctest in release mode
- status: 8
```
+ ctest --output-on-failure -L main
Test project /home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/build-ci-release
      Start  1: test-tokenizer-0-bert-bge
 1/37 Test  #1: test-tokenizer-0-bert-bge .........   Passed    0.24 sec
      Start  2: test-tokenizer-0-command-r
 2/37 Test  #2: test-tokenizer-0-command-r ........   Passed    0.37 sec
      Start  3: test-tokenizer-0-deepseek-coder
 3/37 Test  #3: test-tokenizer-0-deepseek-coder ...   Passed    0.09 sec
      Start  4: test-tokenizer-0-deepseek-llm
 4/37 Test  #4: test-tokenizer-0-deepseek-llm .....   Passed    0.17 sec
      Start  5: test-tokenizer-0-falcon
 5/37 Test  #5: test-tokenizer-0-falcon ...........   Passed    0.12 sec
      Start  6: test-tokenizer-0-gpt-2
 6/37 Test  #6: test-tokenizer-0-gpt-2 ............   Passed    0.10 sec
      Start  7: test-tokenizer-0-llama-bpe
 7/37 Test  #7: test-tokenizer-0-llama-bpe ........   Passed    0.25 sec
      Start  8: test-tokenizer-0-llama-spm
 8/37 Test  #8: test-tokenizer-0-llama-spm ........   Passed    0.08 sec
      Start  9: test-tokenizer-0-mpt
 9/37 Test  #9: test-tokenizer-0-mpt ..............   Passed    0.11 sec
      Start 10: test-tokenizer-0-phi-3
10/37 Test #10: test-tokenizer-0-phi-3 ............   Passed    0.09 sec
      Start 11: test-tokenizer-0-qwen2
11/37 Test #11: test-tokenizer-0-qwen2 ............   Passed    0.22 sec
      Start 12: test-tokenizer-0-refact
12/37 Test #12: test-tokenizer-0-refact ...........   Passed    0.10 sec
      Start 13: test-tokenizer-0-starcoder
13/37 Test #13: test-tokenizer-0-starcoder ........   Passed    0.11 sec
      Start 14: test-tokenizers-ggml-vocabs
14/37 Test #14: test-tokenizers-ggml-vocabs .......***Failed    3.67 sec
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
15/37 Test #15: test-sampling .....................   Passed    0.85 sec
      Start 16: test-grammar-parser
16/37 Test #16: test-grammar-parser ...............   Passed    0.03 sec
      Start 17: test-grammar-integration
17/37 Test #17: test-grammar-integration ..........   Passed    0.04 sec
      Start 18: test-llama-grammar
18/37 Test #18: test-llama-grammar ................   Passed    0.03 sec
      Start 19: test-chat
19/37 Test #19: test-chat .........................   Passed    0.70 sec
      Start 20: test-json-schema-to-grammar
20/37 Test #20: test-json-schema-to-grammar .......   Passed    1.87 sec
      Start 21: test-tokenizer-1-llama-spm
21/37 Test #21: test-tokenizer-1-llama-spm ........   Passed    0.16 sec
      Start 22: test-chat-parser
22/37 Test #22: test-chat-parser ..................   Passed    0.04 sec
      Start 23: test-chat-template
23/37 Test #23: test-chat-template ................   Passed    0.12 sec
      Start 24: test-json-partial
24/37 Test #24: test-json-partial .................   Passed    0.03 sec
      Start 25: test-log
25/37 Test #25: test-log ..........................   Passed    0.05 sec
      Start 26: test-regex-partial
26/37 Test #26: test-regex-partial ................   Passed    0.04 sec
      Start 27: test-thread-safety
27/37 Test #27: test-thread-safety ................***Failed    0.06 sec
'https' scheme is not supported.

      Start 28: test-arg-parser
28/37 Test #28: test-arg-parser ...................   Passed   13.73 sec
      Start 29: test-opt
29/37 Test #29: test-opt ..........................   Passed    0.19 sec
      Start 30: test-gguf
30/37 Test #30: test-gguf .........................   Passed    0.44 sec
      Start 31: test-backend-ops
31/37 Test #31: test-backend-ops ..................   Passed   54.87 sec
      Start 34: test-barrier
32/37 Test #34: test-barrier ......................   Passed    0.95 sec
      Start 35: test-quantize-fns
33/37 Test #35: test-quantize-fns .................   Passed   12.11 sec
      Start 36: test-quantize-perf
34/37 Test #36: test-quantize-perf ................   Passed    0.09 sec
      Start 37: test-rope
35/37 Test #37: test-rope .........................   Passed    0.08 sec
      Start 38: test-mtmd-c-api
36/37 Test #38: test-mtmd-c-api ...................   Passed    0.04 sec
      Start 39: test-alloc
37/37 Test #39: test-alloc ........................   Passed    0.03 sec

95% tests passed, 2 tests failed out of 37

Label Time Summary:
main    =  92.33 sec*proc (37 tests)

Total Test time (real) =  92.34 sec

The following tests FAILED:
	 14 - test-tokenizers-ggml-vocabs (Failed)
	 27 - test-thread-safety (Failed)
Errors while running CTest

real	1m32.440s
user	1m28.361s
sys	0m26.990s
```
