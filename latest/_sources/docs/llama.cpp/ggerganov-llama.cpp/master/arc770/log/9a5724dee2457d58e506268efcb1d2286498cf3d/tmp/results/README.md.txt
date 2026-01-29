### ctest_release

Runs ctest in release mode
- status: 8
```
+ ctest --output-on-failure -L main
Test project /home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/build-ci-release
      Start  1: test-tokenizer-0-bert-bge
 1/47 Test  #1: test-tokenizer-0-bert-bge ...........   Passed    0.31 sec
      Start  2: test-tokenizer-0-command-r
 2/47 Test  #2: test-tokenizer-0-command-r ..........   Passed    0.39 sec
      Start  3: test-tokenizer-0-deepseek-coder
 3/47 Test  #3: test-tokenizer-0-deepseek-coder .....   Passed    0.10 sec
      Start  4: test-tokenizer-0-deepseek-llm
 4/47 Test  #4: test-tokenizer-0-deepseek-llm .......   Passed    0.18 sec
      Start  5: test-tokenizer-0-falcon
 5/47 Test  #5: test-tokenizer-0-falcon .............   Passed    0.13 sec
      Start  6: test-tokenizer-0-gpt-2
 6/47 Test  #6: test-tokenizer-0-gpt-2 ..............   Passed    0.12 sec
      Start  7: test-tokenizer-0-llama-bpe
 7/47 Test  #7: test-tokenizer-0-llama-bpe ..........   Passed    0.27 sec
      Start  8: test-tokenizer-0-llama-spm
 8/47 Test  #8: test-tokenizer-0-llama-spm ..........   Passed    0.09 sec
      Start  9: test-tokenizer-0-mpt
 9/47 Test  #9: test-tokenizer-0-mpt ................   Passed    0.11 sec
      Start 10: test-tokenizer-0-phi-3
10/47 Test #10: test-tokenizer-0-phi-3 ..............   Passed    0.09 sec
      Start 11: test-tokenizer-0-qwen2
11/47 Test #11: test-tokenizer-0-qwen2 ..............   Passed    0.24 sec
      Start 12: test-tokenizer-0-refact
12/47 Test #12: test-tokenizer-0-refact .............   Passed    0.11 sec
      Start 13: test-tokenizer-0-starcoder
13/47 Test #13: test-tokenizer-0-starcoder ..........   Passed    0.12 sec
      Start 14: test-tokenizers-ggml-vocabs
14/47 Test #14: test-tokenizers-ggml-vocabs .........***Failed    2.86 sec
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
15/47 Test #15: test-sampling .......................   Passed    0.83 sec
      Start 16: test-grammar-parser
16/47 Test #16: test-grammar-parser .................   Passed    0.04 sec
      Start 17: test-grammar-integration
17/47 Test #17: test-grammar-integration ............   Passed    0.04 sec
      Start 18: test-llama-grammar
18/47 Test #18: test-llama-grammar ..................   Passed    0.04 sec
      Start 19: test-chat
19/47 Test #19: test-chat ...........................   Passed    1.36 sec
      Start 20: test-json-schema-to-grammar
20/47 Test #20: test-json-schema-to-grammar .........   Passed    1.99 sec
      Start 21: test-tokenizer-1-llama-spm
21/47 Test #21: test-tokenizer-1-llama-spm ..........   Passed    0.18 sec
      Start 22: test-chat-parser
22/47 Test #22: test-chat-parser ....................   Passed    0.05 sec
      Start 23: test-chat-peg-parser
23/47 Test #23: test-chat-peg-parser ................   Passed    0.08 sec
      Start 24: test-chat-template
24/47 Test #24: test-chat-template ..................   Passed    0.11 sec
      Start 25: test-json-partial
25/47 Test #25: test-json-partial ...................   Passed    0.05 sec
      Start 26: test-log
26/47 Test #26: test-log ............................   Passed    0.06 sec
      Start 27: test-peg-parser
27/47 Test #27: test-peg-parser .....................   Passed    0.04 sec
      Start 28: test-regex-partial
28/47 Test #28: test-regex-partial ..................   Passed    0.04 sec
      Start 29: test-thread-safety
29/47 Test #29: test-thread-safety ..................***Failed    0.07 sec
'https' scheme is not supported.

      Start 30: test-arg-parser
30/47 Test #30: test-arg-parser .....................   Passed    1.68 sec
      Start 31: test-opt
31/47 Test #31: test-opt ............................   Passed    0.16 sec
      Start 32: test-gguf
32/47 Test #32: test-gguf ...........................   Passed    0.27 sec
      Start 33: test-backend-ops
33/47 Test #33: test-backend-ops ....................   Passed  100.65 sec
      Start 37: test-backend-sampler-greedy
34/47 Test #37: test-backend-sampler-greedy .........   Passed    0.04 sec
      Start 38: test-backend-sampler-temp
35/47 Test #38: test-backend-sampler-temp ...........   Passed    0.05 sec
      Start 39: test-backend-sampler-top_k
36/47 Test #39: test-backend-sampler-top_k ..........   Passed    0.05 sec
      Start 40: test-backend-sampler-dist
37/47 Test #40: test-backend-sampler-dist ...........   Passed    0.05 sec
      Start 41: test-backend-sampler-dist-and-cpu
38/47 Test #41: test-backend-sampler-dist-and-cpu ...   Passed    0.03 sec
      Start 42: test-backend-sampler-logit-bias
39/47 Test #42: test-backend-sampler-logit-bias .....   Passed    0.04 sec
      Start 43: test-backend-sampler-mul_seq
40/47 Test #43: test-backend-sampler-mul_seq ........   Passed    0.05 sec
      Start 44: test-backend-sampler-set-sampler
41/47 Test #44: test-backend-sampler-set-sampler ....   Passed    0.04 sec
      Start 46: test-barrier
42/47 Test #46: test-barrier ........................   Passed    1.20 sec
      Start 47: test-quantize-fns
43/47 Test #47: test-quantize-fns ...................   Passed   12.51 sec
      Start 48: test-quantize-perf
44/47 Test #48: test-quantize-perf ..................   Passed    0.09 sec
      Start 49: test-rope
45/47 Test #49: test-rope ...........................   Passed    0.09 sec
      Start 50: test-m.html-c-api
46/47 Test #50: test-m.html-c-api .....................   Passed    0.05 sec
      Start 51: test-alloc
47/47 Test #51: test-alloc ..........................   Passed    0.04 sec

96% tests passed, 2 tests failed out of 47

Label Time Summary:
main    = 127.18 sec*proc (47 tests)

Total Test time (real) = 127.20 sec

The following tests FAILED:
	 14 - test-tokenizers-ggml-vocabs (Failed)
	 29 - test-thread-safety (Failed)
Errors while running CTest

real	2m7.236s
user	3m19.512s
sys	0m52.731s
```
