### ctest_release

Runs ctest in release mode
- status: 8
```
+ ctest --output-on-failure -L main
Test project /hd1/jianyuzh/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/build-ci-release
      Start  1: test-tokenizer-0-bert-bge
 1/44 Test  #1: test-tokenizer-0-bert-bge .........   Passed    0.19 sec
      Start  2: test-tokenizer-0-command-r
 2/44 Test  #2: test-tokenizer-0-command-r ........   Passed    0.32 sec
      Start  3: test-tokenizer-0-deepseek-coder
 3/44 Test  #3: test-tokenizer-0-deepseek-coder ...   Passed    0.09 sec
      Start  4: test-tokenizer-0-deepseek-llm
 4/44 Test  #4: test-tokenizer-0-deepseek-llm .....   Passed    0.15 sec
      Start  5: test-tokenizer-0-falcon
 5/44 Test  #5: test-tokenizer-0-falcon ...........   Passed    0.12 sec
      Start  6: test-tokenizer-0-gemma-4
 6/44 Test  #6: test-tokenizer-0-gemma-4 ..........   Passed    0.42 sec
      Start  7: test-tokenizer-0-gpt-2
 7/44 Test  #7: test-tokenizer-0-gpt-2 ............   Passed    0.11 sec
      Start  8: test-tokenizer-0-llama-bpe
 8/44 Test  #8: test-tokenizer-0-llama-bpe ........   Passed    0.23 sec
      Start  9: test-tokenizer-0-llama-spm
 9/44 Test  #9: test-tokenizer-0-llama-spm ........   Passed    0.08 sec
      Start 10: test-tokenizer-0-mpt
10/44 Test #10: test-tokenizer-0-mpt ..............   Passed    0.11 sec
      Start 11: test-tokenizer-0-phi-3
11/44 Test #11: test-tokenizer-0-phi-3 ............   Passed    0.08 sec
      Start 12: test-tokenizer-0-qwen2
12/44 Test #12: test-tokenizer-0-qwen2 ............   Passed    0.19 sec
      Start 13: test-tokenizer-0-refact
13/44 Test #13: test-tokenizer-0-refact ...........   Passed    0.11 sec
      Start 14: test-tokenizer-0-starcoder
14/44 Test #14: test-tokenizer-0-starcoder ........   Passed    0.11 sec
      Start 15: test-tokenizers-ggml-vocabs
15/44 Test #15: test-tokenizers-ggml-vocabs .......   Passed    1.46 sec
      Start 16: test-sampling
16/44 Test #16: test-sampling .....................   Passed    0.71 sec
      Start 17: test-reasoning-budget
17/44 Test #17: test-reasoning-budget .............   Passed    0.05 sec
      Start 18: test-grammar-parser
18/44 Test #18: test-grammar-parser ...............   Passed    0.04 sec
      Start 19: test-grammar-integration
19/44 Test #19: test-grammar-integration ..........   Passed    0.05 sec
      Start 20: test-llama-grammar
20/44 Test #20: test-llama-grammar ................   Passed    0.04 sec
      Start 21: test-chat
21/44 Test #21: test-chat .........................   Passed    1.52 sec
      Start 22: test-json-schema-to-grammar
22/44 Test #22: test-json-schema-to-grammar .......   Passed    1.81 sec
      Start 23: test-tokenizer-1-llama-spm
23/44 Test #23: test-tokenizer-1-llama-spm ........   Passed    0.25 sec
      Start 24: test-llama-archs
24/44 Test #24: test-llama-archs ..................Subprocess aborted***Exception:  13.21 sec
main: using seed 3632209032
|     Model arch.|                        Device|Config|   NMSE vs. CPU|Roundtrip|
|----------------|------------------------------|------|---------------|---------|
|            clip|Intel(R) Arc(TM) A770 Graphics| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|            clip|13th Gen Intel(R) Core(TM) i7-13700K| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|            clip|                          Meta| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|           llama|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (3.66e-11)|       [1;32mOK[0m|
|           llama|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|           llama|                          Meta| Dense|  [1;32mOK[0m (3.66e-11)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|           llama|Intel(R) Arc(TM) A770 Graphics|   MoE|  [1;32mOK[0m (3.66e-11)|       [1;32mOK[0m|
|           llama|13th Gen Intel(R) Core(TM) i7-13700K|   MoE|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|           llama|                          Meta|   MoE|  [1;32mOK[0m (3.66e-11)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|          llama4|Intel(R) Arc(TM) A770 Graphics|   MoE|  [1;32mOK[0m (5.77e-11)|       [1;32mOK[0m|
|          llama4|13th Gen Intel(R) Core(TM) i7-13700K|   MoE|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|          llama4|                          Meta|   MoE|  [1;32mOK[0m (5.77e-11)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|            deci|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (5.64e-09)|       [1;32mOK[0m|
|            deci|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|            deci|                          Meta| Dense|  [1;32mOK[0m (5.64e-09)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|          falcon|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (4.50e-10)|       [1;32mOK[0m|
|          falcon|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|          falcon|                          Meta| Dense|  [1;32mOK[0m (4.50e-10)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|        baichuan|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (3.03e-11)|       [1;32mOK[0m|
|        baichuan|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|        baichuan|                          Meta| Dense|  [1;32mOK[0m (3.03e-11)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|            grok|Intel(R) Arc(TM) A770 Graphics|   MoE|  [1;32mOK[0m (3.90e-14)|       [1;32mOK[0m|
|            grok|13th Gen Intel(R) Core(TM) i7-13700K|   MoE|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
|            grok|                          Meta|   MoE|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|            gpt2|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (2.83e-09)|       [1;32mOK[0m|
|            gpt2|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|            gpt2|                          Meta| Dense|  [1;32mOK[0m (2.83e-09)|     [1;33mSKIP[0m|
|            gptj|Intel(R) Arc(TM) A770 Graphics| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|            gptj|13th Gen Intel(R) Core(TM) i7-13700K| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|            gptj|                          Meta| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|         gptneox|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (2.93e-09)|       [1;32mOK[0m|
|         gptneox|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|         gptneox|                          Meta| Dense|  [1;32mOK[0m (2.93e-09)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|             mpt|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (7.46e-09)|       [1;32mOK[0m|
|             mpt|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
|             mpt|                          Meta| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|       starcoder|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (2.83e-09)|       [1;32mOK[0m|
|       starcoder|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|       starcoder|                          Meta| Dense|  [1;32mOK[0m (2.83e-09)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|          refact|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (2.08e-11)|       [1;32mOK[0m|
|          refact|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|          refact|                          Meta| Dense|  [1;32mOK[0m (2.08e-11)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|          refact|Intel(R) Arc(TM) A770 Graphics|   MoE|  [1;32mOK[0m (1.91e-11)|       [1;32mOK[0m|
|          refact|13th Gen Intel(R) Core(TM) i7-13700K|   MoE|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|          refact|                          Meta|   MoE|  [1;32mOK[0m (1.91e-11)|     [1;33mSKIP[0m|
|            bert|Intel(R) Arc(TM) A770 Graphics| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|            bert|13th Gen Intel(R) Core(TM) i7-13700K| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|            bert|                          Meta| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|     modern-bert|Intel(R) Arc(TM) A770 Graphics| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|     modern-bert|13th Gen Intel(R) Core(TM) i7-13700K| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|     modern-bert|                          Meta| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|      nomic-bert|Intel(R) Arc(TM) A770 Graphics| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|      nomic-bert|13th Gen Intel(R) Core(TM) i7-13700K| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|      nomic-bert|                          Meta| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|  nomic-bert-moe|Intel(R) Arc(TM) A770 Graphics| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|  nomic-bert-moe|13th Gen Intel(R) Core(TM) i7-13700K| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|  nomic-bert-moe|                          Meta| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|        neo-bert|Intel(R) Arc(TM) A770 Graphics| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|        neo-bert|13th Gen Intel(R) Core(TM) i7-13700K| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|        neo-bert|                          Meta| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|    jina-bert-v2|Intel(R) Arc(TM) A770 Graphics| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|    jina-bert-v2|13th Gen Intel(R) Core(TM) i7-13700K| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|    jina-bert-v2|                          Meta| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|    jina-bert-v3|Intel(R) Arc(TM) A770 Graphics| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|    jina-bert-v3|13th Gen Intel(R) Core(TM) i7-13700K| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|    jina-bert-v3|                          Meta| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|        eurobert|Intel(R) Arc(TM) A770 Graphics| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|        eurobert|13th Gen Intel(R) Core(TM) i7-13700K| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|        eurobert|                          Meta| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|           bloom|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (1.96e-09)|       [1;32mOK[0m|
|           bloom|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|           bloom|                          Meta| Dense|  [1;32mOK[0m (1.96e-09)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|        stablelm|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (1.50e-08)|       [1;32mOK[0m|
|        stablelm|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|        stablelm|                          Meta| Dense|  [1;32mOK[0m (1.50e-08)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|            qwen|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (2.35e-08)|       [1;32mOK[0m|
|            qwen|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|            qwen|                          Meta| Dense|  [1;32mOK[0m (2.35e-08)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|           qwen2|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (5.36e-10)|       [1;32mOK[0m|
|           qwen2|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|           qwen2|                          Meta| Dense|  [1;32mOK[0m (5.36e-10)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|        qwen2moe|Intel(R) Arc(TM) A770 Graphics|   MoE|  [1;32mOK[0m (2.09e-08)|       [1;32mOK[0m|
|        qwen2moe|13th Gen Intel(R) Core(TM) i7-13700K|   MoE|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|        qwen2moe|                          Meta|   MoE|  [1;32mOK[0m (2.09e-08)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|         qwen2vl|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (2.08e-08)|       [1;32mOK[0m|
|         qwen2vl|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|         qwen2vl|                          Meta| Dense|  [1;32mOK[0m (2.08e-08)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|           qwen3|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (3.56e-14)|       [1;32mOK[0m|
|           qwen3|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|           qwen3|                          Meta| Dense|  [1;32mOK[0m (3.56e-14)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|        qwen3moe|Intel(R) Arc(TM) A770 Graphics|   MoE|  [1;32mOK[0m (3.56e-14)|       [1;32mOK[0m|
|        qwen3moe|13th Gen Intel(R) Core(TM) i7-13700K|   MoE|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|        qwen3moe|                          Meta|   MoE|  [1;32mOK[0m (3.56e-14)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|       qwen3next|Intel(R) Arc(TM) A770 Graphics|   MoE|  [1;32mOK[0m (3.53e-12)|     [1;33mSKIP[0m|
|       qwen3next|13th Gen Intel(R) Core(TM) i7-13700K|   MoE|  [1;32mOK[0m (0.00e+00)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|       qwen3next|                          Meta|   MoE|  [1;32mOK[0m (3.53e-12)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|         qwen3vl|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (3.00e-11)|       [1;32mOK[0m|
|         qwen3vl|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|         qwen3vl|                          Meta| Dense|  [1;32mOK[0m (3.00e-11)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|      qwen3vlmoe|Intel(R) Arc(TM) A770 Graphics|   MoE|  [1;32mOK[0m (3.00e-11)|       [1;32mOK[0m|
|      qwen3vlmoe|13th Gen Intel(R) Core(TM) i7-13700K|   MoE|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|      qwen3vlmoe|                          Meta|   MoE|  [1;32mOK[0m (3.00e-11)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|          qwen35|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (3.63e-14)|     [1;33mSKIP[0m|
|          qwen35|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|          qwen35|                          Meta| Dense|  [1;32mOK[0m (3.63e-14)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|       qwen35moe|Intel(R) Arc(TM) A770 Graphics|   MoE|  [1;32mOK[0m (3.63e-14)|     [1;33mSKIP[0m|
|       qwen35moe|13th Gen Intel(R) Core(TM) i7-13700K|   MoE|  [1;32mOK[0m (0.00e+00)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|       qwen35moe|                          Meta|   MoE|  [1;32mOK[0m (3.63e-14)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|            phi2|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (1.55e-10)|       [1;32mOK[0m|
|            phi2|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|            phi2|                          Meta| Dense|  [1;32mOK[0m (1.55e-10)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|            phi3|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (2.97e-11)|       [1;32mOK[0m|
|            phi3|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|            phi3|                          Meta| Dense|  [1;32mOK[0m (2.97e-11)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|          phimoe|Intel(R) Arc(TM) A770 Graphics|   MoE|  [1;32mOK[0m (7.89e-12)|       [1;32mOK[0m|
|          phimoe|13th Gen Intel(R) Core(TM) i7-13700K|   MoE|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|          phimoe|                          Meta|   MoE|  [1;32mOK[0m (7.89e-12)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|           plamo|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (3.10e-11)|       [1;32mOK[0m|
|           plamo|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|           plamo|                          Meta| Dense|  [1;32mOK[0m (3.10e-11)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|          plamo2|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (1.30e-10)|       [1;32mOK[0m|
|          plamo2|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
|          plamo2|                          Meta| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|          plamo3|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (2.72e-10)|     [1;33mSKIP[0m|
|          plamo3|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|          plamo3|                          Meta| Dense|  [1;32mOK[0m (2.72e-10)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|       codeshell|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (2.93e-09)|       [1;32mOK[0m|
|       codeshell|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|       codeshell|                          Meta| Dense|  [1;32mOK[0m (2.93e-09)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|           orion|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (3.94e-10)|       [1;32mOK[0m|
|           orion|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|           orion|                          Meta| Dense|  [1;32mOK[0m (3.94e-10)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|       internlm2|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (3.03e-11)|       [1;32mOK[0m|
|       internlm2|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|       internlm2|                          Meta| Dense|  [1;32mOK[0m (3.03e-11)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|         minicpm|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (2.51e-10)|       [1;32mOK[0m|
|         minicpm|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|         minicpm|                          Meta| Dense|  [1;32mOK[0m (2.51e-10)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|         minicpm|Intel(R) Arc(TM) A770 Graphics|   MoE|  [1;32mOK[0m (1.72e-10)|       [1;32mOK[0m|
|         minicpm|13th Gen Intel(R) Core(TM) i7-13700K|   MoE|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|         minicpm|                          Meta|   MoE|  [1;32mOK[0m (1.72e-10)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|        minicpm3|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (1.15e-13)|       [1;32mOK[0m|
|        minicpm3|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
|        minicpm3|                          Meta| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|           gemma|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (1.47e-13)|       [1;32mOK[0m|
|           gemma|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|           gemma|                          Meta| Dense|  [1;32mOK[0m (1.47e-13)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|          gemma2|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (1.08e-12)|       [1;32mOK[0m|
|          gemma2|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|          gemma2|                          Meta| Dense|  [1;32mOK[0m (1.08e-12)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|          gemma3|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (1.07e-12)|     [1;33mSKIP[0m|
|          gemma3|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|          gemma3|                          Meta| Dense|  [1;32mOK[0m (1.07e-12)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|         gemma3n|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (5.34e-08)|     [1;33mSKIP[0m|
|         gemma3n|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|     [1;33mSKIP[0m|
|         gemma3n|                          Meta| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|          gemma4|Intel(R) Arc(TM) A770 Graphics| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|          gemma4|13th Gen Intel(R) Core(TM) i7-13700K| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|          gemma4|                          Meta| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
| gemma-embedding|Intel(R) Arc(TM) A770 Graphics| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
| gemma-embedding|13th Gen Intel(R) Core(TM) i7-13700K| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
| gemma-embedding|                          Meta| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|      starcoder2|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (2.87e-09)|       [1;32mOK[0m|
|      starcoder2|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|      starcoder2|                          Meta| Dense|  [1;32mOK[0m (2.87e-09)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|           mamba|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (3.47e-14)|       [1;32mOK[0m|
|           mamba|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
|           mamba|                          Meta| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|          mamba2|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (3.47e-14)|       [1;32mOK[0m|
|          mamba2|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
|          mamba2|                          Meta| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|           jamba|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (2.15e-11)|       [1;32mOK[0m|
|           jamba|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
|           jamba|                          Meta| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|       falcon-h1|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (3.76e-11)|       [1;32mOK[0m|
|       falcon-h1|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
|       falcon-h1|                          Meta| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|          xverse|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (3.03e-11)|       [1;32mOK[0m|
|          xverse|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|          xverse|                          Meta| Dense|  [1;32mOK[0m (3.03e-11)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|       command-r|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (2.73e-11)|       [1;32mOK[0m|
|       command-r|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|       command-r|                          Meta| Dense|  [1;32mOK[0m (2.73e-11)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|         cohere2|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (2.70e-11)|     [1;33mSKIP[0m|
|         cohere2|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|         cohere2|                          Meta| Dense|  [1;32mOK[0m (2.70e-11)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|            dbrx|Intel(R) Arc(TM) A770 Graphics|   MoE|  [1;32mOK[0m (2.74e-11)|       [1;32mOK[0m|
|            dbrx|13th Gen Intel(R) Core(TM) i7-13700K|   MoE|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|            dbrx|                          Meta|   MoE|  [1;32mOK[0m (2.74e-11)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|            olmo|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (4.67e-07)|       [1;32mOK[0m|
|            olmo|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|            olmo|                          Meta| Dense|  [1;32mOK[0m (4.67e-07)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|           olmo2|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (2.66e-10)|     [1;33mSKIP[0m|
|           olmo2|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|     [1;33mSKIP[0m|
|           olmo2|                          Meta| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|           olmoe|Intel(R) Arc(TM) A770 Graphics|   MoE|  [1;32mOK[0m (3.00e-11)|       [1;32mOK[0m|
|           olmoe|13th Gen Intel(R) Core(TM) i7-13700K|   MoE|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
|           olmoe|                          Meta|   MoE|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|         openelm|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (2.98e-11)|       [1;32mOK[0m|
|         openelm|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|         openelm|                          Meta| Dense|  [1;32mOK[0m (2.98e-11)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|          arctic|Intel(R) Arc(TM) A770 Graphics|   MoE|  [1;32mOK[0m (3.07e-11)|       [1;32mOK[0m|
|          arctic|13th Gen Intel(R) Core(TM) i7-13700K|   MoE|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|          arctic|                          Meta|   MoE|  [1;32mOK[0m (3.07e-11)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|        deepseek|Intel(R) Arc(TM) A770 Graphics|   MoE|  [1;32mOK[0m (3.03e-11)|       [1;32mOK[0m|
|        deepseek|13th Gen Intel(R) Core(TM) i7-13700K|   MoE|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|        deepseek|                          Meta|   MoE|  [1;32mOK[0m (3.03e-11)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|       deepseek2|Intel(R) Arc(TM) A770 Graphics|   MoE|  [1;32mOK[0m (3.41e-13)|     [1;31mFAIL[0m|
|       deepseek2|13th Gen Intel(R) Core(TM) i7-13700K|   MoE|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
|       deepseek2|                          Meta|   MoE|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|   deepseek2-ocr|Intel(R) Arc(TM) A770 Graphics| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|   deepseek2-ocr|13th Gen Intel(R) Core(TM) i7-13700K| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|   deepseek2-ocr|                          Meta| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|         chatglm|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (2.35e-08)|       [1;32mOK[0m|
|         chatglm|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|         chatglm|                          Meta| Dense|  [1;32mOK[0m (2.35e-08)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|            glm4|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (9.81e-08)|       [1;32mOK[0m|
|            glm4|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|            glm4|                          Meta| Dense|  [1;32mOK[0m (9.81e-08)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|         glm4moe|Intel(R) Arc(TM) A770 Graphics|   MoE|  [1;32mOK[0m (2.11e-08)|       [1;32mOK[0m|
|         glm4moe|13th Gen Intel(R) Core(TM) i7-13700K|   MoE|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|         glm4moe|                          Meta|   MoE|  [1;32mOK[0m (2.11e-08)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|         glm-dsa|Intel(R) Arc(TM) A770 Graphics|   MoE|  [1;32mOK[0m (3.38e-13)|     [1;31mFAIL[0m|
|         glm-dsa|13th Gen Intel(R) Core(TM) i7-13700K|   MoE|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
|         glm-dsa|                          Meta|   MoE|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|          bitnet|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (3.69e-14)|     [1;33mSKIP[0m|
|          bitnet|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|     [1;33mSKIP[0m|
|          bitnet|                          Meta| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|              t5|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (3.18e-11)|     [1;33mSKIP[0m|
|              t5|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|     [1;33mSKIP[0m|
|              t5|                          Meta| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|       t5encoder|Intel(R) Arc(TM) A770 Graphics| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|       t5encoder|13th Gen Intel(R) Core(TM) i7-13700K| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|       t5encoder|                          Meta| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|            jais|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (1.92e-09)|       [1;32mOK[0m|
|            jais|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|            jais|                          Meta| Dense|  [1;32mOK[0m (1.92e-09)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|           jais2|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (3.02e-09)|       [1;32mOK[0m|
|           jais2|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|           jais2|                          Meta| Dense|  [1;32mOK[0m (3.02e-09)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|        nemotron|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (3.02e-09)|       [1;32mOK[0m|
|        nemotron|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|        nemotron|                          Meta| Dense|  [1;32mOK[0m (3.02e-09)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|      nemotron_h|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (6.22e-09)|       [1;32mOK[0m|
|      nemotron_h|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
|      nemotron_h|                          Meta| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|  nemotron_h_moe|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (6.22e-09)|       [1;32mOK[0m|
|  nemotron_h_moe|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
|  nemotron_h_moe|                          Meta| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|          exaone|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (3.03e-11)|       [1;32mOK[0m|
|          exaone|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|          exaone|                          Meta| Dense|  [1;32mOK[0m (3.03e-11)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|         exaone4|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (2.87e-10)|       [1;32mOK[0m|
|         exaone4|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|         exaone4|                          Meta| Dense|  [1;32mOK[0m (2.87e-10)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|      exaone-moe|Intel(R) Arc(TM) A770 Graphics|   MoE|  [1;32mOK[0m (2.83e-11)|     [1;33mSKIP[0m|
|      exaone-moe|13th Gen Intel(R) Core(TM) i7-13700K|   MoE|  [1;32mOK[0m (0.00e+00)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|      exaone-moe|                          Meta|   MoE|  [1;32mOK[0m (2.83e-11)|     [1;33mSKIP[0m|
|           rwkv6|Intel(R) Arc(TM) A770 Graphics| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|           rwkv6|13th Gen Intel(R) Core(TM) i7-13700K| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|           rwkv6|                          Meta| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|      rwkv6qwen2|Intel(R) Arc(TM) A770 Graphics| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|      rwkv6qwen2|13th Gen Intel(R) Core(TM) i7-13700K| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|      rwkv6qwen2|                          Meta| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|           rwkv7|Intel(R) Arc(TM) A770 Graphics| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|           rwkv7|13th Gen Intel(R) Core(TM) i7-13700K| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|           rwkv7|                          Meta| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|          arwkv7|Intel(R) Arc(TM) A770 Graphics| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|          arwkv7|13th Gen Intel(R) Core(TM) i7-13700K| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|          arwkv7|                          Meta| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|         granite|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (5.64e-09)|       [1;32mOK[0m|
|         granite|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|         granite|                          Meta| Dense|  [1;32mOK[0m (5.64e-09)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|         granite|Intel(R) Arc(TM) A770 Graphics|   MoE|  [1;32mOK[0m (1.02e-08)|       [1;32mOK[0m|
|         granite|13th Gen Intel(R) Core(TM) i7-13700K|   MoE|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|         granite|                          Meta|   MoE|  [1;32mOK[0m (1.02e-08)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|      granitemoe|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (5.64e-09)|       [1;32mOK[0m|
|      granitemoe|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|      granitemoe|                          Meta| Dense|  [1;32mOK[0m (5.64e-09)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|      granitemoe|Intel(R) Arc(TM) A770 Graphics|   MoE|  [1;32mOK[0m (1.02e-08)|       [1;32mOK[0m|
|      granitemoe|13th Gen Intel(R) Core(TM) i7-13700K|   MoE|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|      granitemoe|                          Meta|   MoE|  [1;32mOK[0m (1.02e-08)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|   granitehybrid|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (3.85e-09)|       [1;32mOK[0m|
|   granitehybrid|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
|   granitehybrid|                          Meta| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|       chameleon|Intel(R) Arc(TM) A770 Graphics| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|       chameleon|13th Gen Intel(R) Core(TM) i7-13700K| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|       chameleon|                          Meta| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|wavtokenizer-dec|Intel(R) Arc(TM) A770 Graphics| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|wavtokenizer-dec|13th Gen Intel(R) Core(TM) i7-13700K| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|wavtokenizer-dec|                          Meta| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|             plm|Intel(R) Arc(TM) A770 Graphics| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|             plm|13th Gen Intel(R) Core(TM) i7-13700K| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
|             plm|                          Meta| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|      bailingmoe|Intel(R) Arc(TM) A770 Graphics|   MoE|  [1;32mOK[0m (3.01e-11)|       [1;32mOK[0m|
|      bailingmoe|13th Gen Intel(R) Core(TM) i7-13700K|   MoE|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|      bailingmoe|                          Meta|   MoE|  [1;32mOK[0m (3.01e-11)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|     bailingmoe2|Intel(R) Arc(TM) A770 Graphics|   MoE|  [1;32mOK[0m (2.94e-11)|       [1;32mOK[0m|
|     bailingmoe2|13th Gen Intel(R) Core(TM) i7-13700K|   MoE|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|     bailingmoe2|                          Meta|   MoE|  [1;32mOK[0m (2.94e-11)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|           dots1|Intel(R) Arc(TM) A770 Graphics|   MoE|  [1;32mOK[0m (3.00e-11)|       [1;32mOK[0m|
|           dots1|13th Gen Intel(R) Core(TM) i7-13700K|   MoE|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|           dots1|                          Meta|   MoE|  [1;32mOK[0m (3.00e-11)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|           arcee|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (2.96e-11)|       [1;32mOK[0m|
|           arcee|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|           arcee|                          Meta| Dense|  [1;32mOK[0m (2.96e-11)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|           afmoe|Intel(R) Arc(TM) A770 Graphics|   MoE|  [1;32mOK[0m (3.34e-13)|     [1;33mSKIP[0m|
|           afmoe|13th Gen Intel(R) Core(TM) i7-13700K|   MoE|  [1;32mOK[0m (0.00e+00)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|           afmoe|                          Meta|   MoE|  [1;32mOK[0m (3.34e-13)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|        ernie4_5|Intel(R) Arc(TM) A770 Graphics|   MoE|  [1;32mOK[0m (2.08e-08)|       [1;32mOK[0m|
|        ernie4_5|13th Gen Intel(R) Core(TM) i7-13700K|   MoE|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|        ernie4_5|                          Meta|   MoE|  [1;32mOK[0m (2.08e-08)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|    ernie4_5-moe|Intel(R) Arc(TM) A770 Graphics|   MoE|  [1;32mOK[0m (2.08e-08)|       [1;32mOK[0m|
|    ernie4_5-moe|13th Gen Intel(R) Core(TM) i7-13700K|   MoE|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|    ernie4_5-moe|                          Meta|   MoE|  [1;32mOK[0m (2.08e-08)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|     hunyuan-moe|Intel(R) Arc(TM) A770 Graphics|   MoE|  [1;32mOK[0m (2.97e-11)|       [1;32mOK[0m|
|     hunyuan-moe|13th Gen Intel(R) Core(TM) i7-13700K|   MoE|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|     hunyuan-moe|                          Meta|   MoE|  [1;32mOK[0m (2.97e-11)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|   hunyuan-dense|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (2.99e-11)|       [1;32mOK[0m|
|   hunyuan-dense|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|   hunyuan-dense|                          Meta| Dense|  [1;32mOK[0m (2.99e-11)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|         smollm3|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (3.03e-11)|       [1;32mOK[0m|
|         smollm3|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|         smollm3|                          Meta| Dense|  [1;32mOK[0m (3.03e-11)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|         gpt-oss|Intel(R) Arc(TM) A770 Graphics|   MoE|  [1;32mOK[0m (4.16e-09)|       [1;32mOK[0m|
|         gpt-oss|13th Gen Intel(R) Core(TM) i7-13700K|   MoE|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|         gpt-oss|                          Meta|   MoE|  [1;32mOK[0m (4.16e-09)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|            lfm2|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (1.80e-11)|       [1;32mOK[0m|
|            lfm2|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
|            lfm2|                          Meta| Dense|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|         lfm2moe|Intel(R) Arc(TM) A770 Graphics|   MoE|  [1;32mOK[0m (1.89e-11)|       [1;32mOK[0m|
|         lfm2moe|13th Gen Intel(R) Core(TM) i7-13700K|   MoE|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
|         lfm2moe|                          Meta|   MoE|[1;33mSKIP[0m           |     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|           dream|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (1.47e-08)|       [1;32mOK[0m|
|           dream|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|           dream|                          Meta| Dense|  [1;32mOK[0m (1.47e-08)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|    smallthinker|Intel(R) Arc(TM) A770 Graphics|   MoE|  [1;32mOK[0m (3.00e-11)|       [1;32mOK[0m|
|    smallthinker|13th Gen Intel(R) Core(TM) i7-13700K|   MoE|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|    smallthinker|                          Meta|   MoE|  [1;32mOK[0m (3.00e-11)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|           llada|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (2.51e-11)|       [1;32mOK[0m|
|           llada|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|           llada|                          Meta| Dense|  [1;32mOK[0m (2.51e-11)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|       llada-moe|Intel(R) Arc(TM) A770 Graphics|   MoE|  [1;32mOK[0m (2.32e-11)|       [1;32mOK[0m|
|       llada-moe|13th Gen Intel(R) Core(TM) i7-13700K|   MoE|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|       llada-moe|                          Meta|   MoE|  [1;32mOK[0m (2.32e-11)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|        seed_oss|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (2.09e-08)|       [1;32mOK[0m|
|        seed_oss|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|        seed_oss|                          Meta| Dense|  [1;32mOK[0m (2.09e-08)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|        grovemoe|Intel(R) Arc(TM) A770 Graphics|   MoE|  [1;32mOK[0m (3.00e-11)|       [1;32mOK[0m|
|        grovemoe|13th Gen Intel(R) Core(TM) i7-13700K|   MoE|  [1;32mOK[0m (0.00e+00)|       [1;32mOK[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|        grovemoe|                          Meta|   MoE|  [1;32mOK[0m (3.00e-11)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
|         apertus|Intel(R) Arc(TM) A770 Graphics| Dense|  [1;32mOK[0m (6.38e-11)|     [1;33mSKIP[0m|
|         apertus|13th Gen Intel(R) Core(TM) i7-13700K| Dense|  [1;32mOK[0m (0.00e+00)|     [1;33mSKIP[0m|
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
/hd1/jianyuzh/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/ggml/src/ggml-backend-meta.cpp:557: fatal error
[New LWP 1438179]
[New LWP 1438178]
[New LWP 1438177]
[New LWP 1438176]
[New LWP 1438175]
[New LWP 1438163]
warning: File "/opt/intel/oneapi/compiler/2025.3/lib/libsycl.so.8.0.0-gdb.py" auto-loading has been declined by your `auto-load safe-path' set to "$debugdir:$datadir/auto-load".
To enable execution of this file add
	add-auto-load-safe-path /opt/intel/oneapi/compiler/2025.3/lib/libsycl.so.8.0.0-gdb.py
line to your configuration file "/home/jianyuzh/.config/gdb/gdbinit".
To completely disable this security protection add
	set auto-load safe-path /
line to your configuration file "/home/jianyuzh/.config/gdb/gdbinit".
For more information about this security protection see the
"Auto-loading safe path" section in the GDB manual.  E.g., run from the shell:
	info "(gdb)Auto-loading safe path"
[Thread debugging using libthread_db enabled]
Using host libthread_db library "/lib/x86_64-linux-gnu/libthread_db.so.1".
0x000076948d910813 in __GI___wait4 (pid=1438482, stat_loc=0x0, options=0, usage=0x0) at ../sysdeps/unix/sysv/linux/wait4.c:30
warning: 30	../sysdeps/unix/sysv/linux/wait4.c: No such file or directory
#0  0x000076948d910813 in __GI___wait4 (pid=1438482, stat_loc=0x0, options=0, usage=0x0) at ../sysdeps/unix/sysv/linux/wait4.c:30
30	in ../sysdeps/unix/sysv/linux/wait4.c
#1  0x0000769490d59503 in ggml_print_backtrace () from /hd1/jianyuzh/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/build-ci-release/bin/libggml-base.so.0
#2  0x0000769490d596ab in ggml_abort () from /hd1/jianyuzh/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/build-ci-release/bin/libggml-base.so.0
#3  0x0000769490d82ed4 in ggml_backend_meta_get_split_state(ggml_tensor const*, bool)::$_5::operator()(std::vector<ggml_backend_meta_split_state, std::allocator<ggml_backend_meta_split_state> > const&) const () from /hd1/jianyuzh/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/build-ci-release/bin/libggml-base.so.0
#4  0x0000769490d81146 in ggml_backend_meta_get_split_state(ggml_tensor const*, bool)::$_18::operator()() const () from /hd1/jianyuzh/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/build-ci-release/bin/libggml-base.so.0
#5  0x0000769490d7f377 in ggml_backend_meta_get_split_state(ggml_tensor const*, bool) () from /hd1/jianyuzh/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/build-ci-release/bin/libggml-base.so.0
#6  0x0000769490d7b736 in ggml_backend_meta_buffer_init_tensor(ggml_backend_buffer*, ggml_tensor*) () from /hd1/jianyuzh/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/build-ci-release/bin/libggml-base.so.0
#7  0x0000769490d6f14c in ggml_gallocr_alloc_graph () from /hd1/jianyuzh/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/build-ci-release/bin/libggml-base.so.0
#8  0x0000769490d76f9a in ggml_backend_sched_alloc_graph () from /hd1/jianyuzh/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/build-ci-release/bin/libggml-base.so.0
#9  0x0000769490e98146 in llama_context::process_ubatch(llama_ubatch const&, llm_graph_type, llama_memory_context_i*, ggml_status&) () from /hd1/jianyuzh/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/build-ci-release/bin/libllama.so.0
#10 0x0000769490e99e1e in llama_context::decode(llama_batch const&) () from /hd1/jianyuzh/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/build-ci-release/bin/libllama.so.0
#11 0x0000769490e9e72b in llama_decode () from /hd1/jianyuzh/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/build-ci-release/bin/libllama.so.0
#12 0x0000000000419dbc in get_logits(llama_model*, llama_context*, std::vector<int, std::allocator<int> > const&, bool) ()
#13 0x0000000000417639 in main ()
[Inferior 1 (process 1438122) detached]

      Start 25: test-chat-peg-parser
25/44 Test #25: test-chat-peg-parser ..............   Passed    0.05 sec
      Start 26: test-jinja
26/44 Test #26: test-jinja ........................   Passed    0.08 sec
      Start 28: test-chat-auto-parser
27/44 Test #28: test-chat-auto-parser .............   Passed    0.10 sec
      Start 29: test-chat-template
28/44 Test #29: test-chat-template ................   Passed    0.09 sec
      Start 30: test-json-partial
29/44 Test #30: test-json-partial .................   Passed    0.04 sec
      Start 31: test-log
30/44 Test #31: test-log ..........................   Passed    0.05 sec
      Start 32: test-peg-parser
31/44 Test #32: test-peg-parser ...................   Passed    0.05 sec
      Start 33: test-regex-partial
32/44 Test #33: test-regex-partial ................   Passed    0.04 sec
      Start 34: test-download-model
33/44 Test #34: test-download-model ...............   Passed    9.78 sec
      Start 35: test-thread-safety
34/44 Test #35: test-thread-safety ................***Exception: SegFault  3.37 sec
system_info: n_threads = 2 (n_threads_batch = 2) / 24 | CPU : SSE3 = 1 | SSSE3 = 1 | AVX = 1 | AVX_VNNI = 1 | AVX2 = 1 | F16C = 1 | FMA = 1 | BMI2 = 1 | LLAMAFILE = 1 | OPENMP = 1 | REPACK = 1 | 
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
llama_model_load_from_file_impl: using device SYCL0 (Intel(R) Arc(TM) A770 Graphics) (unknown id) - 15473 MiB free
llama_model_loader: loaded meta data with 20 key-value pairs and 57 tensors from /hd1/jianyuzh/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/build-ci-release/tinyllamas/stories15M-q4_0.gguf (version GGUF V3 (latest))
llama_model_loader: Dumping metadata keys/values. Note: KV overrides do not apply in this output.
llama_model_loader: - kv   0:                      tokenizer.ggml.tokens arr[str,32000]   = ["<unk>", "<s>", "</s>", "<0x00>", "<...
llama_model_loader: - kv   1:                      tokenizer.ggml.scores arr[f32,32000]   = [0.000000, 0.000000, 0.000000, 0.0000...
llama_model_loader: - kv   2:                  tokenizer.ggml.token_type arr[i32,32000]   = [2, 3, 3, 6, 6, 6, 6, 6, 6, 6, 6, 6, ...
llama_model_loader: - kv   3:                       tokenizer.ggml.model str              = llama
llama_model_loader: - kv   4:                       general.architecture str              = llama
llama_model_loader: - kv   5:                               general.name str              = llama
llama_model_loader: - kv   6:            tokenizer.ggml.unknown_token_id u32              = 0
llama_model_loader: - kv   7:                tokenizer.ggml.bos_token_id u32              = 1
llama_model_loader: - kv   8:                tokenizer.ggml.eos_token_id u32              = 2
llama_model_loader: - kv   9:          tokenizer.ggml.seperator_token_id u32              = 4294967295
llama_model_loader: - kv  10:            tokenizer.ggml.padding_token_id u32              = 4294967295
llama_model_loader: - kv  11:                       llama.context_length u32              = 128
llama_model_loader: - kv  12:                     llama.embedding_length u32              = 288
llama_model_loader: - kv  13:                  llama.feed_forward_length u32              = 768
llama_model_loader: - kv  14:                 llama.attention.head_count u32              = 6
llama_model_loader: - kv  15:                          llama.block_count u32              = 6
llama_model_loader: - kv  16:                 llama.rope.dimension_count u32              = 48
llama_model_loader: - kv  17:     llama.attention.layer_norm_rms_epsilon f32              = 0.000010
llama_model_loader: - kv  18:               general.quantization_version u32              = 2
llama_model_loader: - kv  19:                          general.file_type u32              = 2
llama_model_loader: - type  f32:   13 tensors
llama_model_loader: - type q4_0:   43 tensors
llama_model_loader: - type q8_0:    1 tensors
print_info: file format = GGUF V3 (latest)
print_info: file type   = Q4_0
print_info: file size   = 17.50 MiB (6.01 BPW) 
load: empty token at index 30143
load: bad special token: 'tokenizer.ggml.seperator_token_id' = 4294967295, using default id -1
load: bad special token: 'tokenizer.ggml.padding_token_id' = 4294967295, using default id -1
load: 0 unused tokens
load: printing all EOG tokens:
load:   - 2 ('</s>')
load: special tokens cache size = 3
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
load: token to piece cache size = 0.1684 MB
print_info: arch                  = llama
print_info: vocab_only            = 0
print_info: no_alloc              = 0
print_info: n_ctx_train           = 128
print_info: n_embd                = 288
print_info: n_embd_inp            = 288
print_info: n_layer               = 6
print_info: n_head                = 6
print_info: n_head_kv             = 6
print_info: n_rot                 = 48
print_info: n_swa                 = 0
print_info: is_swa_any            = 0
print_info: n_embd_head_k         = 48
print_info: n_embd_head_v         = 48
print_info: n_gqa                 = 1
print_info: n_embd_k_gqa          = 288
print_info: n_embd_v_gqa          = 288
print_info: f_norm_eps            = 0.0e+00
print_info: f_norm_rms_eps        = 1.0e-05
print_info: f_clamp_kqv           = 0.0e+00
print_info: f_max_alibi_bias      = 0.0e+00
print_info: f_logit_scale         = 0.0e+00
print_info: f_attn_scale          = 0.0e+00
print_info: n_ff                  = 768
print_info: n_expert              = 0
print_info: n_expert_used         = 0
print_info: n_expert_groups       = 0
print_info: n_group_used          = 0
print_info: causal attn           = 1
print_info: pooling type          = -1
print_info: rope type             = 0
print_info: rope scaling          = linear
print_info: freq_base_train       = 10000.0
print_info: freq_scale_train      = 1
print_info: n_ctx_orig_yarn       = 128
print_info: rope_yarn_log_mul     = 0.0000
print_info: rope_finetuned        = unknown
print_info: model type            = ?B
print_info: model params          = 24.41 M
print_info: general.name          = llama
print_info: vocab type            = SPM
print_info: n_vocab               = 32000
print_info: n_merges              = 0
print_info: BOS token             = 1 '<s>'
print_info: EOS token             = 2 '</s>'
print_info: UNK token             = 0 '<unk>'
print_info: LF token              = 13 '<0x0A>'
print_info: EOG token             = 2 '</s>'
print_info: max token length      = 48
load_tensors: loading model tensors, this can take a while... (mmap = true, direct_io = false)
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
load_tensors: offloading output layer to GPU
load_tensors: offloading 5 repeating layers to GPU
load_tensors: offloaded 7/7 layers to GPU
load_tensors:   CPU_Mapped model buffer size =     4.94 MiB
load_tensors:        SYCL0 model buffer size =    12.56 MiB
.....................
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
llama_model_loader: loaded meta data with 20 key-value pairs and 57 tensors from /hd1/jianyuzh/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/build-ci-release/tinyllamas/stories15M-q4_0.gguf (version GGUF V3 (latest))
llama_model_loader: Dumping metadata keys/values. Note: KV overrides do not apply in this output.
llama_model_loader: - kv   0:                      tokenizer.ggml.tokens arr[str,32000]   = ["<unk>", "<s>", "</s>", "<0x00>", "<...
llama_model_loader: - kv   1:                      tokenizer.ggml.scores arr[f32,32000]   = [0.000000, 0.000000, 0.000000, 0.0000...
llama_model_loader: - kv   2:                  tokenizer.ggml.token_type arr[i32,32000]   = [2, 3, 3, 6, 6, 6, 6, 6, 6, 6, 6, 6, ...
llama_model_loader: - kv   3:                       tokenizer.ggml.model str              = llama
llama_model_loader: - kv   4:                       general.architecture str              = llama
llama_model_loader: - kv   5:                               general.name str              = llama
llama_model_loader: - kv   6:            tokenizer.ggml.unknown_token_id u32              = 0
llama_model_loader: - kv   7:                tokenizer.ggml.bos_token_id u32              = 1
llama_model_loader: - kv   8:                tokenizer.ggml.eos_token_id u32              = 2
llama_model_loader: - kv   9:          tokenizer.ggml.seperator_token_id u32              = 4294967295
llama_model_loader: - kv  10:            tokenizer.ggml.padding_token_id u32              = 4294967295
llama_model_loader: - kv  11:                       llama.context_length u32              = 128
llama_model_loader: - kv  12:                     llama.embedding_length u32              = 288
llama_model_loader: - kv  13:                  llama.feed_forward_length u32              = 768
llama_model_loader: - kv  14:                 llama.attention.head_count u32              = 6
llama_model_loader: - kv  15:                          llama.block_count u32              = 6
llama_model_loader: - kv  16:                 llama.rope.dimension_count u32              = 48
llama_model_loader: - kv  17:     llama.attention.layer_norm_rms_epsilon f32              = 0.000010
llama_model_loader: - kv  18:               general.quantization_version u32              = 2
llama_model_loader: - kv  19:                          general.file_type u32              = 2
llama_model_loader: - type  f32:   13 tensors
llama_model_loader: - type q4_0:   43 tensors
llama_model_loader: - type q8_0:    1 tensors
print_info: file format = GGUF V3 (latest)
print_info: file type   = Q4_0
print_info: file size   = 17.50 MiB (6.01 BPW) 
load: empty token at index 30143
load: bad special token: 'tokenizer.ggml.seperator_token_id' = 4294967295, using default id -1
load: bad special token: 'tokenizer.ggml.padding_token_id' = 4294967295, using default id -1
load: 0 unused tokens
load: printing all EOG tokens:
load:   - 2 ('</s>')
load: special tokens cache size = 3
load: token to piece cache size = 0.1684 MB
print_info: arch                  = llama
print_info: vocab_only            = 0
print_info: no_alloc              = 0
print_info: n_ctx_train           = 128
print_info: n_embd                = 288
print_info: n_embd_inp            = 288
print_info: n_layer               = 6
print_info: n_head                = 6
print_info: n_head_kv             = 6
print_info: n_rot                 = 48
print_info: n_swa                 = 0
print_info: is_swa_any            = 0
print_info: n_embd_head_k         = 48
print_info: n_embd_head_v         = 48
print_info: n_gqa                 = 1
print_info: n_embd_k_gqa          = 288
print_info: n_embd_v_gqa          = 288
print_info: f_norm_eps            = 0.0e+00
print_info: f_norm_rms_eps        = 1.0e-05
print_info: f_clamp_kqv           = 0.0e+00
print_info: f_max_alibi_bias      = 0.0e+00
print_info: f_logit_scale         = 0.0e+00
print_info: f_attn_scale          = 0.0e+00
print_info: n_ff                  = 768
print_info: n_expert              = 0
print_info: n_expert_used         = 0
print_info: n_expert_groups       = 0
print_info: n_group_used          = 0
print_info: causal attn           = 1
print_info: pooling type          = -1
print_info: rope type             = 0
print_info: rope scaling          = linear
print_info: freq_base_train       = 10000.0
print_info: freq_scale_train      = 1
print_info: n_ctx_orig_yarn       = 128
print_info: rope_yarn_log_mul     = 0.0000
print_info: rope_finetuned        = unknown
print_info: model type            = ?B
print_info: model params          = 24.41 M
print_info: general.name          = llama
print_info: vocab type            = SPM
print_info: n_vocab               = 32000
print_info: n_merges              = 0
print_info: BOS token             = 1 '<s>'
print_info: EOS token             = 2 '</s>'
print_info: UNK token             = 0 '<unk>'
print_info: LF token              = 13 '<0x0A>'
print_info: EOG token             = 2 '</s>'
print_info: max token length      = 48
load_tensors: loading model tensors, this can take a while... (mmap = true, direct_io = false)
load_tensors: offloading output layer to GPU
load_tensors: offloading 5 repeating layers to GPU
load_tensors: offloaded 7/7 layers to GPU
load_tensors:   CPU_Mapped model buffer size =    17.50 MiB
load_tensors:   CPU_REPACK model buffer size =     3.20 MiB
.....................
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
llama_model_load_from_file_impl: using device SYCL0 (Intel(R) Arc(TM) A770 Graphics) (unknown id) - 15473 MiB free
llama_model_loader: loaded meta data with 20 key-value pairs and 57 tensors from /hd1/jianyuzh/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/build-ci-release/tinyllamas/stories15M-q4_0.gguf (version GGUF V3 (latest))
llama_model_loader: Dumping metadata keys/values. Note: KV overrides do not apply in this output.
llama_model_loader: - kv   0:                      tokenizer.ggml.tokens arr[str,32000]   = ["<unk>", "<s>", "</s>", "<0x00>", "<...
llama_model_loader: - kv   1:                      tokenizer.ggml.scores arr[f32,32000]   = [0.000000, 0.000000, 0.000000, 0.0000...
llama_model_loader: - kv   2:                  tokenizer.ggml.token_type arr[i32,32000]   = [2, 3, 3, 6, 6, 6, 6, 6, 6, 6, 6, 6, ...
llama_model_loader: - kv   3:                       tokenizer.ggml.model str              = llama
llama_model_loader: - kv   4:                       general.architecture str              = llama
llama_model_loader: - kv   5:                               general.name str              = llama
llama_model_loader: - kv   6:            tokenizer.ggml.unknown_token_id u32              = 0
llama_model_loader: - kv   7:                tokenizer.ggml.bos_token_id u32              = 1
llama_model_loader: - kv   8:                tokenizer.ggml.eos_token_id u32              = 2
llama_model_loader: - kv   9:          tokenizer.ggml.seperator_token_id u32              = 4294967295
llama_model_loader: - kv  10:            tokenizer.ggml.padding_token_id u32              = 4294967295
llama_model_loader: - kv  11:                       llama.context_length u32              = 128
llama_model_loader: - kv  12:                     llama.embedding_length u32              = 288
llama_model_loader: - kv  13:                  llama.feed_forward_length u32              = 768
llama_model_loader: - kv  14:                 llama.attention.head_count u32              = 6
llama_model_loader: - kv  15:                          llama.block_count u32              = 6
llama_model_loader: - kv  16:                 llama.rope.dimension_count u32              = 48
llama_model_loader: - kv  17:     llama.attention.layer_norm_rms_epsilon f32              = 0.000010
llama_model_loader: - kv  18:               general.quantization_version u32              = 2
llama_model_loader: - kv  19:                          general.file_type u32              = 2
llama_model_loader: - type  f32:   13 tensors
llama_model_loader: - type q4_0:   43 tensors
llama_model_loader: - type q8_0:    1 tensors
print_info: file format = GGUF V3 (latest)
print_info: file type   = Q4_0
print_info: file size   = 17.50 MiB (6.01 BPW) 
load: empty token at index 30143
load: bad special token: 'tokenizer.ggml.seperator_token_id' = 4294967295, using default id -1
load: bad special token: 'tokenizer.ggml.padding_token_id' = 4294967295, using default id -1
load: 0 unused tokens
load: printing all EOG tokens:
load:   - 2 ('</s>')
load: special tokens cache size = 3
load: token to piece cache size = 0.1684 MB
print_info: arch                  = llama
print_info: vocab_only            = 0
print_info: no_alloc              = 0
print_info: n_ctx_train           = 128
print_info: n_embd                = 288
print_info: n_embd_inp            = 288
print_info: n_layer               = 6
print_info: n_head                = 6
print_info: n_head_kv             = 6
print_info: n_rot                 = 48
print_info: n_swa                 = 0
print_info: is_swa_any            = 0
print_info: n_embd_head_k         = 48
print_info: n_embd_head_v         = 48
print_info: n_gqa                 = 1
print_info: n_embd_k_gqa          = 288
print_info: n_embd_v_gqa          = 288
print_info: f_norm_eps            = 0.0e+00
print_info: f_norm_rms_eps        = 1.0e-05
print_info: f_clamp_kqv           = 0.0e+00
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
print_info: f_max_alibi_bias      = 0.0e+00
print_info: f_logit_scale         = 0.0e+00
print_info: f_attn_scale          = 0.0e+00
print_info: n_ff                  = 768
print_info: n_expert              = 0
print_info: n_expert_used         = 0
print_info: n_expert_groups       = 0
print_info: n_group_used          = 0
print_info: causal attn           = 1
print_info: pooling type          = -1
print_info: rope type             = 0
print_info: rope scaling          = linear
print_info: freq_base_train       = 10000.0
print_info: freq_scale_train      = 1
print_info: n_ctx_orig_yarn       = 128
print_info: rope_yarn_log_mul     = 0.0000
print_info: rope_finetuned        = unknown
print_info: model type            = ?B
print_info: model params          = 24.41 M
print_info: general.name          = llama
print_info: vocab type            = SPM
print_info: n_vocab               = 32000
print_info: n_merges              = 0
print_info: BOS token             = 1 '<s>'
print_info: EOS token             = 2 '</s>'
print_info: UNK token             = 0 '<unk>'
print_info: LF token              = 13 '<0x0A>'
print_info: EOG token             = 2 '</s>'
print_info: max token length      = 48
load_tensors: loading model tensors, this can take a while... (mmap = true, direct_io = false)
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
load_tensors: offloading output layer to GPU
load_tensors: offloading 5 repeating layers to GPU
load_tensors: offloaded 7/7 layers to GPU
load_tensors:   CPU_Mapped model buffer size =     4.94 MiB
load_tensors:        SYCL0 model buffer size =    12.56 MiB
.....................
Creating context 2/4 for model 1/3
llama_context: constructing llama_context
llama_context: n_seq_max     = 1
llama_context: n_ctx         = 256
llama_context: n_ctx_seq     = 256
llama_context: n_batch       = 256
llama_context: n_ubatch      = 32
llama_context: causal_attn   = 1
llama_context: flash_attn    = auto
llama_context: kv_unified    = false
llama_context: freq_base     = 10000.0
llama_context: freq_scale    = 1
llama_context: n_ctx_seq (256) > n_ctx_train (128) -- possible training context overflow
Creating context 2/4 for model 2/3
Build with Macros:
  GGML_SYCL_FORCE_MMQ: no
  GGML_SYCL_F16: yes
  GGML_SYCL_GRAPH: yes
  GGML_SYCL_DNNL: yes
Creating context 3/4 for model 2/3
Running with Environment Variables:
  GGML_SYCL_DEBUG: 0
  GGML_SYCL_DISABLE_OPT: 0
  GGML_SYCL_DISABLE_GRAPH: 1
  GGML_SYCL_DISABLE_DNN: 0
  GGML_SYCL_PRIORITIZE_DMMV: 0
  GGML_SYCL_ENABLE_FLASH_ATTN: 1
Found 1 SYCL devices:
|  |                   |                                       |       |Max    |        |Max  |Global |                     |
|  |                   |                                       |       |compute|Max work|sub  |mem    |                     |
|ID|        Device Type|                                   Name|Version|units  |group   |group|size   |       Driver version|
|--|-------------------|---------------------------------------|-------|-------|--------|-----|-------|---------------------|
Creating context 3/4 for model 1/3
llama_context: constructing llama_context
llama_context: n_seq_max     = 1
llama_context: n_ctx         = 256
llama_context: n_ctx_seq     = 256
llama_context: n_batch       = 256
llama_context: n_ubatch      = 32
llama_context: causal_attn   = 1
Creating context 4/4 for model 1/3
llama_context: flash_attn    = auto
Creating context 1/4 for model 2/3
llama_context: kv_unified    = false
llama_context: constructing llama_context
llama_context: freq_base     = 10000.0
llama_context: freq_scale    = 1
llama_context: n_seq_max     = 1
llama_context: n_ctx_seq (256) > n_ctx_train (128) -- possible training context overflow
llama_context: n_ctx         = 256
llama_context: n_ctx_seq     = 256
llama_context: n_batch       = 256
llama_context: n_ubatch      = 32
llama_context: causal_attn   = 1
llama_context: flash_attn    = auto
llama_context: kv_unified    = false
Creating context 1/4 for model 3/3
llama_context: freq_base     = 10000.0
llama_context: freq_scale    = 1
llama_context: n_ctx_seq (256) > n_ctx_train (128) -- possible training context overflow
| 0| [level_zero:gpu:0]|                Intel Arc A770 Graphics|  12.55|    512|    1024|   32| 16225M|         1.14.37020+3|
SYCL Optimization Feature:
|ID|        Device Type|Reorder|
llama_context: constructing llama_context
|--|-------------------|-------|
llama_context: n_seq_max     = 1
llama_context: n_ctx         = 256
llama_context: n_ctx_seq     = 256
llama_context: n_batch       = 256
llama_context: n_ubatch      = 32
llama_context: causal_attn   = 1
llama_context: flash_attn    = auto
llama_context: kv_unified    = false
llama_context: freq_base     = 10000.0
llama_context: freq_scale    = 1
llama_context: n_ctx_seq (256) > n_ctx_train (128) -- possible training context overflow
| 0| [level_zero:gpu:0]|      Y|
Creating context 4/4 for model 2/3
llama_context: constructing llama_context
llama_context: n_seq_max     = 1
llama_context: n_ctx         = 256
llama_context: n_ctx_seq     = 256
llama_context: n_batch       = 256
llama_context: n_ubatch      = 32
llama_context: causal_attn   = 1
llama_context: flash_attn    = auto
llama_context: kv_unified    = false
llama_context: freq_base     = 10000.0
llama_context: freq_scale    = 1
llama_context: n_ctx_seq (256) > n_ctx_train (128) -- possible training context overflow
llama_context: constructing llama_context
llama_context:        CPU  output buffer size =     0.12 MiB
llama_context: n_seq_max     = 1
llama_context: n_ctx         = 256
llama_context: n_ctx_seq     = 256
llama_context: n_batch       = 256
llama_context: n_ubatch      = 32
llama_context:        CPU  output buffer size =     0.12 MiB
llama_context: causal_attn   = 1
llama_context: flash_attn    = auto
llama_context: kv_unified    = false
llama_context: freq_base     = 10000.0
llama_context: freq_scale    = 1
llama_context: n_ctx_seq (256) > n_ctx_train (128) -- possible training context overflow
Creating context 2/4 for model 3/3
Creating context 1/4 for model 1/3
Creating context 3/4 for model 3/3
llama_context: constructing llama_context
llama_context: n_seq_max     = 1
llama_context: n_ctx         = 256
llama_context: n_ctx_seq     = 256
llama_context: n_batch       = 256
llama_context: n_ubatch      = 32
llama_context: causal_attn   = 1
llama_context: flash_attn    = auto
llama_context: kv_unified    = false
llama_context: freq_base     = 10000.0
llama_context: freq_scale    = 1
llama_context: n_ctx_seq (256) > n_ctx_train (128) -- possible training context overflow
llama_context:        CPU  output buffer size =     0.12 MiB
llama_kv_cache:        CPU KV buffer size =     1.69 MiB
llama_context:  SYCL_Host  output buffer size =     0.12 MiB
llama_context:  SYCL_Host  output buffer size =     0.12 MiB
llama_context: constructing llama_context
llama_context: n_seq_max     = 1
llama_context: n_ctx         = 256
llama_context: n_ctx_seq     = 256
llama_context: n_batch       = 256
llama_context: n_ubatch      = 32
llama_context: causal_attn   = 1
llama_context: flash_attn    = auto
llama_context: kv_unified    = false
llama_context: freq_base     = 10000.0
llama_context: freq_scale    = 1
llama_context: n_ctx_seq (256) > n_ctx_train (128) -- possible training context overflow
llama_context:        CPU  output buffer size =     0.12 MiB
llama_kv_cache:        CPU KV buffer size =     1.69 MiB
llama_kv_cache:        CPU KV buffer size =     1.69 MiB
llama_kv_cache:        CPU KV buffer size =     1.69 MiB
llama_context: constructing llama_context
llama_context: n_seq_max     = 1
llama_context: n_ctx         = 256
llama_context: n_ctx_seq     = 256
llama_context: n_batch       = 256
llama_context: n_ubatch      = 32
llama_context: causal_attn   = 1
llama_context: flash_attn    = auto
llama_context: kv_unified    = false
llama_context: freq_base     = 10000.0
llama_context: freq_scale    = 1
llama_context: n_ctx_seq (256) > n_ctx_train (128) -- possible training context overflow
llama_context:  SYCL_Host  output buffer size =     0.12 MiB
llama_context:  SYCL_Host  output buffer size =     0.12 MiB
llama_context:  SYCL_Host  output buffer size =     0.12 MiB
llama_context: constructing llama_context
llama_context: n_seq_max     = 1
llama_context: n_ctx         = 256
llama_context: n_ctx_seq     = 256
llama_context: n_batch       = 256
llama_context: n_ubatch      = 32
llama_context: causal_attn   = 1
llama_context: flash_attn    = auto
llama_context: kv_unified    = false
llama_context: freq_base     = 10000.0
llama_context: freq_scale    = 1
llama_context: n_ctx_seq (256) > n_ctx_train (128) -- possible training context overflow
Creating context 4/4 for model 3/3
llama_context:  SYCL_Host  output buffer size =     0.12 MiB
llama_context: constructing llama_context
llama_context: n_seq_max     = 1
llama_context: n_ctx         = 256
llama_context: n_ctx_seq     = 256
llama_context: n_batch       = 256
llama_context: n_ubatch      = 32
llama_context: causal_attn   = 1
llama_context: flash_attn    = auto
llama_context: kv_unified    = false
llama_context: freq_base     = 10000.0
llama_context: freq_scale    = 1
llama_context: n_ctx_seq (256) > n_ctx_train (128) -- possible training context overflow
llama_context: constructing llama_context
llama_context: n_seq_max     = 1
llama_context: n_ctx         = 256
llama_context: n_ctx_seq     = 256
llama_context: n_batch       = 256
llama_context: n_ubatch      = 32
llama_context: causal_attn   = 1
llama_context: flash_attn    = auto
llama_context: kv_unified    = false
llama_context: freq_base     = 10000.0
llama_context: freq_scale    = 1
llama_context: n_ctx_seq (256) > n_ctx_train (128) -- possible training context overflow
llama_kv_cache:      SYCL0 KV buffer size =     1.69 MiB
llama_context:  SYCL_Host  output buffer size =     0.12 MiB
llama_kv_cache: size =    1.69 MiB (   256 cells,   6 layers,  1/1 seqs), K (f16):    0.84 MiB, V (f16):    0.84 MiB
llama_kv_cache: attn_rot_k = 0, n_embd_head_k_all = 48
llama_kv_cache: attn_rot_v = 0, n_embd_head_k_all = 48
llama_context:  SYCL_Host  output buffer size =     0.12 MiB
sched_reserve: reserving ...
llama_kv_cache: size =    1.69 MiB (   256 cells,   6 layers,  1/1 seqs), K (f16):    0.84 MiB, V (f16):    0.84 MiB
llama_kv_cache: attn_rot_k = 0, n_embd_head_k_all = 48
llama_kv_cache: attn_rot_v = 0, n_embd_head_k_all = 48
sched_reserve: reserving ...
llama_kv_cache: size =    1.69 MiB (   256 cells,   6 layers,  1/1 seqs), K (f16):    0.84 MiB, V (f16):    0.84 MiB
llama_kv_cache: attn_rot_k = 0, n_embd_head_k_all = 48
llama_kv_cache: attn_rot_v = 0, n_embd_head_k_all = 48
llama_kv_cache: size =    1.69 MiB (   256 cells,   6 layers,  1/1 seqs), K (f16):    0.84 MiB, V (f16):    0.84 MiB
sched_reserve: reserving ...
llama_kv_cache: attn_rot_k = 0, n_embd_head_k_all = 48
llama_kv_cache: attn_rot_v = 0, n_embd_head_k_all = 48
sched_reserve: reserving ...
llama_kv_cache: size =    1.69 MiB (   256 cells,   6 layers,  1/1 seqs), K (f16):    0.84 MiB, V (f16):    0.84 MiB
llama_kv_cache: attn_rot_k = 0, n_embd_head_k_all = 48
llama_kv_cache: attn_rot_v = 0, n_embd_head_k_all = 48
sched_reserve: reserving ...
llama_kv_cache:      SYCL0 KV buffer size =     1.69 MiB
llama_kv_cache: size =    1.69 MiB (   256 cells,   6 layers,  1/1 seqs), K (f16):    0.84 MiB, V (f16):    0.84 MiB
llama_kv_cache: attn_rot_k = 0, n_embd_head_k_all = 48
llama_kv_cache: attn_rot_v = 0, n_embd_head_k_all = 48
sched_reserve: reserving ...
sched_reserve: Flash Attention was auto, set to enabled
sched_reserve: resolving fused Gated Delta Net support:
sched_reserve: layer 0 is assigned to device SYCL0 but the Flash Attention tensor is assigned to device CPU (usually due to missing support)
sched_reserve: Flash Attention was auto, set to disabled
sched_reserve: resolving fused Gated Delta Net support:
sched_reserve: fused Gated Delta Net (autoregressive) enabled
sched_reserve: fused Gated Delta Net (autoregressive) enabled
sched_reserve: Flash Attention was auto, set to enabled
sched_reserve: resolving fused Gated Delta Net support:
sched_reserve: Flash Attention was auto, set to enabled
sched_reserve: fused Gated Delta Net (chunked) enabled
sched_reserve: resolving fused Gated Delta Net support:
sched_reserve: fused Gated Delta Net (autoregressive) enabled
sched_reserve: fused Gated Delta Net (chunked) enabled
sched_reserve: fused Gated Delta Net (autoregressive) enabled
sched_reserve: Flash Attention was auto, set to enabled
sched_reserve: resolving fused Gated Delta Net support:
sched_reserve: fused Gated Delta Net (chunked) enabled
sched_reserve: fused Gated Delta Net (chunked) enabled
sched_reserve: fused Gated Delta Net (autoregressive) enabled
sched_reserve: fused Gated Delta Net (chunked) enabled
llama_kv_cache:      SYCL0 KV buffer size =     1.69 MiB
sched_reserve:        CPU compute buffer size =     4.13 MiB
sched_reserve: graph nodes  = 193
sched_reserve: graph splits = 1
sched_reserve: reserve took 0.66 ms, sched copies = 1
sched_reserve: layer 0 is assigned to device SYCL0 but the Flash Attention tensor is assigned to device CPU (usually due to missing support)
sched_reserve: Flash Attention was auto, set to disabled
sched_reserve: resolving fused Gated Delta Net support:
sched_reserve:        CPU compute buffer size =     4.13 MiB
sched_reserve: graph nodes  = 193
sched_reserve: graph splits = 1
sched_reserve: reserve took 0.57 ms, sched copies = 1
sched_reserve:        CPU compute buffer size =     4.13 MiB
sched_reserve: graph nodes  = 193
sched_reserve: graph splits = 1
sched_reserve: reserve took 0.57 ms, sched copies = 1
sched_reserve: fused Gated Delta Net (autoregressive) enabled
sched_reserve:        CPU compute buffer size =     4.13 MiB
sched_reserve: graph nodes  = 193
sched_reserve: graph splits = 1
sched_reserve: reserve took 0.61 ms, sched copies = 1
sched_reserve: fused Gated Delta Net (chunked) enabled
llama_kv_cache: size =    1.69 MiB (   256 cells,   6 layers,  1/1 seqs), K (f16):    0.84 MiB, V (f16):    0.84 MiB
llama_kv_cache: attn_rot_k = 0, n_embd_head_k_all = 48
llama_kv_cache: attn_rot_v = 0, n_embd_head_k_all = 48
sched_reserve: reserving ...
llama_kv_cache:      SYCL0 KV buffer size =     1.69 MiB
llama_kv_cache: size =    1.69 MiB (   256 cells,   6 layers,  1/1 seqs), K (f16):    0.84 MiB, V (f16):    0.84 MiB
llama_kv_cache: attn_rot_k = 0, n_embd_head_k_all = 48
llama_kv_cache: attn_rot_v = 0, n_embd_head_k_all = 48
sched_reserve: reserving ...
sched_reserve:      SYCL0 compute buffer size =     4.08 MiB
sched_reserve:  SYCL_Host compute buffer size =     0.10 MiB
sched_reserve: graph nodes  = 222
sched_reserve: graph splits = 2
sched_reserve: reserve took 0.98 ms, sched copies = 1
llama_kv_cache:      SYCL0 KV buffer size =     1.69 MiB
sched_reserve: layer 0 is assigned to device SYCL0 but the Flash Attention tensor is assigned to device CPU (usually due to missing support)
sched_reserve: Flash Attention was auto, set to disabled
sched_reserve: resolving fused Gated Delta Net support:
llama_kv_cache: size =    1.69 MiB (   256 cells,   6 layers,  1/1 seqs), K (f16):    0.84 MiB, V (f16):    0.84 MiB
llama_kv_cache: attn_rot_k = 0, n_embd_head_k_all = 48
llama_kv_cache: attn_rot_v = 0, n_embd_head_k_all = 48
sched_reserve: reserving ...
sched_reserve: fused Gated Delta Net (autoregressive) enabled
sched_reserve: fused Gated Delta Net (chunked) enabled
sched_reserve: layer 0 is assigned to device SYCL0 but the Flash Attention tensor is assigned to device CPU (usually due to missing support)
sched_reserve: Flash Attention was auto, set to disabled
sched_reserve: resolving fused Gated Delta Net support:
sched_reserve:      SYCL0 compute buffer size =     4.08 MiB
sched_reserve:  SYCL_Host compute buffer size =     0.10 MiB
sched_reserve: graph nodes  = 222
sched_reserve: graph splits = 2
sched_reserve: reserve took 0.99 ms, sched copies = 1
sched_reserve: fused Gated Delta Net (autoregressive) enabled
sched_reserve: fused Gated Delta Net (chunked) enabled
llama_kv_cache:      SYCL0 KV buffer size =     1.69 MiB
sched_reserve: layer 0 is assigned to device SYCL0 but the Flash Attention tensor is assigned to device CPU (usually due to missing support)
sched_reserve: Flash Attention was auto, set to disabled
sched_reserve: resolving fused Gated Delta Net support:
llama_kv_cache:      SYCL0 KV buffer size =     1.69 MiB
sched_reserve: fused Gated Delta Net (autoregressive) enabled
sched_reserve: fused Gated Delta Net (chunked) enabled
sched_reserve:      SYCL0 compute buffer size =     4.08 MiB
sched_reserve:  SYCL_Host compute buffer size =     0.10 MiB
sched_reserve: graph nodes  = 222
sched_reserve: graph splits = 2
sched_reserve: reserve took 0.95 ms, sched copies = 1
llama_kv_cache:      SYCL0 KV buffer size =     1.69 MiB
sched_reserve:      SYCL0 compute buffer size =     4.08 MiB
sched_reserve:  SYCL_Host compute buffer size =     0.10 MiB
sched_reserve: graph nodes  = 222
sched_reserve: graph splits = 2
sched_reserve: reserve took 1.02 ms, sched copies = 1
sched_reserve:      SYCL0 compute buffer size =     4.08 MiB
sched_reserve:  SYCL_Host compute buffer size =     0.10 MiB
sched_reserve: graph nodes  = 222
sched_reserve: graph splits = 2
sched_reserve: reserve took 1.44 ms, sched copies = 1
llama_kv_cache: size =    1.69 MiB (   256 cells,   6 layers,  1/1 seqs), K (f16):    0.84 MiB, V (f16):    0.84 MiB
llama_kv_cache: attn_rot_k = 0, n_embd_head_k_all = 48
llama_kv_cache: attn_rot_v = 0, n_embd_head_k_all = 48
sched_reserve: reserving ...
llama_kv_cache: size =    1.69 MiB (   256 cells,   6 layers,  1/1 seqs), K (f16):    0.84 MiB, V (f16):    0.84 MiB
llama_kv_cache: attn_rot_k = 0, n_embd_head_k_all = 48
llama_kv_cache: attn_rot_v = 0, n_embd_head_k_all = 48
sched_reserve: reserving ...
sched_reserve: layer 0 is assigned to device SYCL0 but the Flash Attention tensor is assigned to device CPU (usually due to missing support)
sched_reserve: Flash Attention was auto, set to disabled
sched_reserve: resolving fused Gated Delta Net support:
sched_reserve: fused Gated Delta Net (autoregressive) enabled
sched_reserve: fused Gated Delta Net (chunked) enabled
sched_reserve: layer 0 is assigned to device SYCL0 but the Flash Attention tensor is assigned to device CPU (usually due to missing support)
sched_reserve: Flash Attention was auto, set to disabled
sched_reserve: resolving fused Gated Delta Net support:
sched_reserve: fused Gated Delta Net (autoregressive) enabled
sched_reserve: fused Gated Delta Net (chunked) enabled
sched_reserve:      SYCL0 compute buffer size =     4.08 MiB
sched_reserve:  SYCL_Host compute buffer size =     0.10 MiB
sched_reserve: graph nodes  = 222
sched_reserve: graph splits = 2
sched_reserve: reserve took 1.06 ms, sched copies = 1
sched_reserve:      SYCL0 compute buffer size =     4.08 MiB
sched_reserve:  SYCL_Host compute buffer size =     0.10 MiB
sched_reserve: graph nodes  = 222
sched_reserve: graph splits = 2
sched_reserve: reserve took 1.41 ms, sched copies = 1
llama_kv_cache: size =    1.69 MiB (   256 cells,   6 layers,  1/1 seqs), K (f16):    0.84 MiB, V (f16):    0.84 MiB
llama_kv_cache: attn_rot_k = 0, n_embd_head_k_all = 48
llama_kv_cache: attn_rot_v = 0, n_embd_head_k_all = 48
sched_reserve: reserving ...
sched_reserve: layer 0 is assigned to device SYCL0 but the Flash Attention tensor is assigned to device CPU (usually due to missing support)
sched_reserve: Flash Attention was auto, set to disabled
sched_reserve: resolving fused Gated Delta Net support:
sched_reserve: fused Gated Delta Net (autoregressive) enabled
sched_reserve: fused Gated Delta Net (chunked) enabled
sched_reserve:      SYCL0 compute buffer size =     4.08 MiB
sched_reserve:  SYCL_Host compute buffer size =     0.10 MiB
sched_reserve: graph nodes  = 222
sched_reserve: graph splits = 2
sched_reserve: reserve took 0.92 ms, sched copies = 1
Model 2/3, Context 3/4: The meaning of life is on the inside of you. Every time you do something new, the mystery might appear. But who knows you can do that?".
The question she was for, not for a three year old. But the little one was just too young to understand. She was very persistent, but eventually she figured out what was coming next.
When the answer appeared, the little one was so happy. He was so excited to learn and try new things. He was so persistent that he soon found the answer he thought was perfect.
He had a big smile on his face and was proud of himself for being able to understand the answer.

Model 2/3, Context 2/4: The meaning of life is all over the world for. Each day, life is just a bit longer.
But one day, the start of a beautiful journey was starting. On the way, the road suddenly started to reverse. Suddenly, it started to move very fast and it stopped in the middle of the road.
The driver of the car was so surprised. He had never seen something like this before. He was very confused.
Then, suddenly, he noticed that a little bird had gotten loose and was flying right up to the tree. He stopped the car and asked the bird, "What's wrong?".
The bird

Model 2/3, Context 4/4: The meaning of life is in the air. It is a beautiful day for a walk in the park. On the walk there was a little girl. She was very small and she was scared. But then she saw something. A big, pretty bird was standing in the middle of the path.
The little girl was so curious. She wanted to get closer to the bird. She tried to climb the side of the path, but she was too small. She was too small. The bird was very brave. 
The bird flew away and the little girl was happy. But then something else happened. A big cloud of mist came and it

Model 2/3, Context 1/4: The meaning of life is on the ground. It is a distant, but it's a reminder. One day, the sun was shining and the birds were chirping. It was a beautiful day, and the sun was shining very brightly.
Mary was sad because the sky was still glowing. But then she saw something in the distance. It was a beautiful butterfly! She was so excited.
Mary wanted to catch the butterfly. She ran as fast as she could, and soon she caught it in her hands. She was so happy and excited to look at the butterfly. She

Model 1/3, Context 2/4: The meaning of life is <s>	

Model 1/3, Context 4/4: The meaning of life is#
#<s>#

Model 1/3, Context 1/4: The meaning of life is

Model 1/3, Context 3/4: The meaning of life is<unk><s>!<s>	

Model 3/3, Context 2/4: The meaning of life is

Model 3/3, Context 1/4: The meaning of life is

Model 3/3, Context 4/4: The meaning of life is


      Start 36: test-arg-parser
35/44 Test #36: test-arg-parser ...................Subprocess aborted***Exception: 539.98 sec
error while handling argument "-m": expected value for argument

usage:
-m,    --model FNAME                    model path to load
                                        (env: LLAMA_ARG_MODEL)


to show complete usage, run with -h
error while handling argument "-ngl": stoi

usage:
-ngl,  --gpu-layers, --n-gpu-layers N   max. number of layers to store in VRAM, either an exact number,
                                        'auto', or 'all' (default: auto)
                                        (env: LLAMA_ARG_N_GPU_LAYERS)


to show complete usage, run with -h
error while handling argument "-sm": invalid value

usage:
-sm,   --split-mode {none,layer,row,tensor}
                                        how to split the model across multiple GPUs, one of:
                                        - none: use one GPU only
                                        - layer (default): split layers and KV across GPUs (pipelined)
                                        - row: split weight across GPUs by rows (parallelized)
                                        - tensor: split weights and KV across GPUs (parallelized)
                                        (env: LLAMA_ARG_SPLIT_MODE)


to show complete usage, run with -h
error: invalid argument: --draft
error: --model is required

error while handling environment variable "LLAMA_ARG_THREADS": stoi


warn: LLAMA_ARG_MODEL environment variable is set, but will be overwritten by command line argument -m
[New LWP 1439089]
warning: File "/opt/intel/oneapi/compiler/2025.3/lib/libsycl.so.8.0.0-gdb.py" auto-loading has been declined by your `auto-load safe-path' set to "$debugdir:$datadir/auto-load".
To enable execution of this file add
	add-auto-load-safe-path /opt/intel/oneapi/compiler/2025.3/lib/libsycl.so.8.0.0-gdb.py
line to your configuration file "/home/jianyuzh/.config/gdb/gdbinit".
To completely disable this security protection add
	set auto-load safe-path /
line to your configuration file "/home/jianyuzh/.config/gdb/gdbinit".
For more information about this security protection see the
"Auto-loading safe path" section in the GDB manual.  E.g., run from the shell:
	info "(gdb)Auto-loading safe path"
[Thread debugging using libthread_db enabled]
Using host libthread_db library "/lib/x86_64-linux-gnu/libthread_db.so.1".
0x000079df2db10813 in __GI___wait4 (pid=1457336, stat_loc=0x0, options=0, usage=0x0) at ../sysdeps/unix/sysv/linux/wait4.c:30
warning: 30	../sysdeps/unix/sysv/linux/wait4.c: No such file or directory
#0  0x000079df2db10813 in __GI___wait4 (pid=1457336, stat_loc=0x0, options=0, usage=0x0) at ../sysdeps/unix/sysv/linux/wait4.c:30
30	in ../sysdeps/unix/sysv/linux/wait4.c
#1  0x000079df313df503 in ggml_print_backtrace () from /hd1/jianyuzh/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/build-ci-release/bin/libggml-base.so.0
#2  0x000079df313f26c6 in ggml_uncaught_exception() () from /hd1/jianyuzh/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/build-ci-release/bin/libggml-base.so.0
#3  0x000079df2debb0da in ?? () from /lib/x86_64-linux-gnu/libstdc++.so.6
#4  0x000079df2dea5a55 in std::terminate() () from /lib/x86_64-linux-gnu/libstdc++.so.6
#5  0x000079df2debb391 in __cxa_throw () from /lib/x86_64-linux-gnu/libstdc++.so.6
#6  0x00000000004db8c0 in common_remote_get_content(std::__cxx11::basic_string<char, std::char_traits<char>, std::allocator<char> > const&, common_remote_params const&) ()
#7  0x0000000000429345 in main ()
[Inferior 1 (process 1439087) detached]
terminate called after throwing an instance of 'std::runtime_error'
  what():  error: cannot make GET request

      Start 37: test-opt
36/44 Test #37: test-opt ..........................   Passed    0.17 sec
      Start 38: test-gguf
37/44 Test #38: test-gguf .........................***Timeout 1500.05 sec

gguf_init_from_file_ptr: invalid magic characters: 'FUGG', expected 'GGUF'
gguf_init_from_file_ptr: bad GGUF version: 0
gguf_init_from_file_ptr: failed to read header
gguf_init_from_file_ptr: GGUFv1 is no longer supported, please use a more up-to-date version
gguf_init_from_file_ptr: failed to read header
gguf_init_from_file_ptr: this GGUF file is version 4 but this software only supports up to version 3
gguf_init_from_file_ptr: failed to read header
gguf_init_from_file_ptr: number of key value pairs is -1 but must be in [0, 209622091746699450]
gguf_init_from_file_ptr: failed to read header
gguf_init_from_file_ptr: number of tensors is -1 but must be in [0, 53624256028225440]
gguf_init_from_file_ptr: failed to read header
read: string length 18446744073709551615 exceeds maximum 1073741824
gguf_init_from_file_ptr: failed to read key-value pairs
gguf_init_from_file_ptr: key 'my_key_0' has invalid GGUF type 13
gguf_init_from_file_ptr: failed to read key-value pairs
gguf_init_from_file_ptr: duplicate key 'my_key_0' for tensors 0 and 1 
gguf_init_from_file_ptr: failed to read key-value pairs
gguf_init_from_file_ptr: alignment 13 is not a power of 2
gguf_init_from_file_ptr: tensor name 0 is too long: 87 >= 64
gguf_init_from_file_ptr: failed to read tensor info
gguf_init_from_file_ptr: tensor 'my_tensor_0' has invalid number of dimensions: 5 > 4
gguf_init_from_file_ptr: failed to read tensor info
gguf_init_from_file_ptr: tensor 'my_tensor_0' dimension 0 has invalid number of elements: -1 < 0
gguf_init_from_file_ptr: failed to read tensor info
gguf_init_from_file_ptr: total number of elements in tensor 'my_tensor_0' with shape (8589934588, 8589934588, 1, 1) is >= 9223372036854775807
gguf_init_from_file_ptr: failed to read tensor info
gguf_init_from_file_ptr: tensor 'my_tensor_0' with shape (1533685239, 1533685239, 1, 1) has a size in bytes > 18446744073709551615
gguf_init_from_file_ptr: failed to read tensor info
gguf_init_from_file_ptr: tensor 'my_tensor_0' has invalid ggml type 42. should be in [0, 42)
gguf_init_from_file_ptr: failed to read tensor info
gguf_init_from_file_ptr: tensor 'my_tensor_0' has offset 18446744073709551615, expected 0
gguf_init_from_file_ptr: failed to read tensor data
gguf_init_from_file_ptr: duplicate tensor name 'my_tensor' for tensors 0 and 1
gguf_init_from_file_ptr: failed to read tensor info
gguf_init_from_file_ptr: alignment 13 is not a power of 2
gguf_init_from_file_ptr: tensor 'my_tensor_1' has offset 168, expected 192
gguf_init_from_file_ptr: failed to read tensor data
gguf_init_from_file_ptr: failed to read tensor data binary blob
gguf_init_from_file_ptr: alignment 13 is not a power of 2
gguf_init_from_file_ptr: tensor 'my_tensor_1' has offset 168, expected 192
gguf_init_from_file_ptr: failed to read tensor data
gguf_init_from_file_ptr: memory size overflow while allocating ggml context
test_handcrafted_file: handcrafted_file_type=HEADER_BAD_MAGIC
test_handcrafted_file:   - context_null: [1;32mOK[0m

test_handcrafted_file: handcrafted_file_type=HEADER_BAD_VERSION_0
test_handcrafted_file:   - context_null: [1;32mOK[0m

test_handcrafted_file: handcrafted_file_type=HEADER_BAD_VERSION_1
test_handcrafted_file:   - context_null: [1;32mOK[0m

test_handcrafted_file: handcrafted_file_type=HEADER_BAD_VERSION_FUTURE
test_handcrafted_file:   - context_null: [1;32mOK[0m

test_handcrafted_file: handcrafted_file_type=HEADER_BAD_N_KV
test_handcrafted_file:   - context_null: [1;32mOK[0m

test_handcrafted_file: handcrafted_file_type=HEADER_BAD_N_TENSORS
test_handcrafted_file:   - context_null: [1;32mOK[0m

test_handcrafted_file: handcrafted_file_type=HEADER_EMPTY
test_handcrafted_file:   - context_not_null: [1;32mOK[0m
test_handcrafted_file:   - check_header: [1;32mOK[0m

test_handcrafted_file: handcrafted_file_type=KV_BAD_KEY_SIZE
test_handcrafted_file:   - context_null: [1;32mOK[0m

test_handcrafted_file: handcrafted_file_type=KV_BAD_TYPE
test_handcrafted_file:   - context_null: [1;32mOK[0m

test_handcrafted_file: handcrafted_file_type=KV_DUPLICATE_KEY
test_handcrafted_file:   - context_null: [1;32mOK[0m

test_handcrafted_file: handcrafted_file_type=KV_BAD_ALIGN
test_handcrafted_file:   - context_null: [1;32mOK[0m

test_handcrafted_file: handcrafted_file_type=KV_RANDOM_KV
test_handcrafted_file:   - context_not_null: [1;32mOK[0m
test_handcrafted_file:   - check_header: [1;32mOK[0m
test_handcrafted_file:   - check_kv: [1;32mOK[0m

test_handcrafted_file: handcrafted_file_type=TENSORS_BAD_NAME_SIZE
test_handcrafted_file:   - context_null: [1;32mOK[0m

test_handcrafted_file: handcrafted_file_type=TENSORS_BAD_N_DIMS
test_handcrafted_file:   - context_null: [1;32mOK[0m

test_handcrafted_file: handcrafted_file_type=TENSORS_BAD_SHAPE
test_handcrafted_file:   - context_null: [1;32mOK[0m

test_handcrafted_file: handcrafted_file_type=TENSORS_NE_TOO_BIG
test_handcrafted_file:   - context_null: [1;32mOK[0m

test_handcrafted_file: handcrafted_file_type=TENSORS_NBYTES_TOO_BIG
test_handcrafted_file:   - context_null: [1;32mOK[0m

test_handcrafted_file: handcrafted_file_type=TENSORS_BAD_TYPE
test_handcrafted_file:   - context_null: [1;32mOK[0m

test_handcrafted_file: handcrafted_file_type=TENSORS_BAD_OFFSET
test_handcrafted_file:   - context_null: [1;32mOK[0m

test_handcrafted_file: handcrafted_file_type=TENSORS_DUPLICATE_NAME
test_handcrafted_file:   - context_null: [1;32mOK[0m

test_handcrafted_file: handcrafted_file_type=TENSORS_BAD_ALIGN
test_handcrafted_file:   - context_null: [1;32mOK[0m

test_handcrafted_file: handcrafted_file_type=TENSORS_INCONSISTENT_ALIGN
test_handcrafted_file:   - context_null: [1;32mOK[0m

test_handcrafted_file: handcrafted_file_type=TENSORS_SUCCESS
test_handcrafted_file:   - context_not_null: [1;32mOK[0m
test_handcrafted_file:   - check_header: [1;32mOK[0m
test_handcrafted_file:   - check_kv: [1;32mOK[0m
test_handcrafted_file:   - check_tensors: [1;32mOK[0m

test_handcrafted_file: handcrafted_file_type=TENSORS_CUSTOM_ALIGN
test_handcrafted_file:   - context_not_null: [1;32mOK[0m
test_handcrafted_file:   - check_header: [1;32mOK[0m
test_handcrafted_file:   - check_kv: [1;32mOK[0m
test_handcrafted_file:   - check_tensors: [1;32mOK[0m

test_handcrafted_file: handcrafted_file_type=DATA_NOT_ENOUGH_DATA
test_handcrafted_file:   - context_null: [1;32mOK[0m
test_handcrafted_file:   - no_dangling_ggml_context_pointer: [1;32mOK[0m

test_handcrafted_file: handcrafted_file_type=DATA_BAD_ALIGN
test_handcrafted_file:   - context_null: [1;32mOK[0m
test_handcrafted_file:   - no_dangling_ggml_context_pointer: [1;32mOK[0m

test_handcrafted_file: handcrafted_file_type=DATA_INCONSISTENT_ALIGN
test_handcrafted_file:   - context_null: [1;32mOK[0m
test_handcrafted_file:   - no_dangling_ggml_context_pointer: [1;32mOK[0m

test_handcrafted_file: handcrafted_file_type=DATA_MEM_SIZE_OVERFLOW
test_handcrafted_file:   - context_null: [1;32mOK[0m
test_handcraBuild with Macros:
  GGML_SYCL_FORCE_MMQ: no
  GGML_SYCL_F16: yes
  GGML_SYCL_GRAPH: yes
  GGML_SYCL_DNNL: yes
Running with Environment Variables:
  GGML_SYCL_DEBUG: 0
  GGML_SYCL_DISABLE_OPT: 0
  GGML_SYCL_DISABLE_GRAPH: 1
  GGML_SYCL_DISABLE_DNN: 0
  GGML_SYCL_PRIORITIZE_DMMV: 0
  GGML_SYCL_ENABLE_FLASH_ATTN: 1
Found 1 SYCL devices:
|  |                   |                                       |       |Max    |        |Max  |Global |                     |
|  |                   |                                       |       |compute|Max work|sub  |mem    |                     |
|ID|        Device Type|                                   Name|Version|units  |group   |group|size   |       Driver version|
|--|-------------------|---------------------------------------|-------|-------|--------|-----|-------|---------------------|
| 0| [level_zero:gpu:0]|                Intel Arc A770 Graphics|  12.55|    512|    1024|   32| 16225M|         1.14.37020+3|
SYCL Optimization Feature:
|ID|        Device Type|Reorder|
|--|-------------------|-------|
| 0| [level_zero:gpu:0]|      Y|

      Start 39: test-backend-ops
38/44 Test #39: test-backend-ops ..................Subprocess aborted***Exception:   6.35 sec
Build with Macros:
  GGML_SYCL_FORCE_MMQ: no
  GGML_SYCL_F16: yes
  GGML_SYCL_GRAPH: yes
  GGML_SYCL_DNNL: yes
Running with Environment Variables:
  GGML_SYCL_DEBUG: 0
  GGML_SYCL_DISABLE_OPT: 0
  GGML_SYCL_DISABLE_GRAPH: 1
  GGML_SYCL_DISABLE_DNN: 0
  GGML_SYCL_PRIORITIZE_DMMV: 0
  GGML_SYCL_ENABLE_FLASH_ATTN: 1
Found 1 SYCL devices:
|  |                   |                                       |       |Max    |        |Max  |Global |                     |
|  |                   |                                       |       |compute|Max work|sub  |mem    |                     |
|ID|        Device Type|                                   Name|Version|units  |group   |group|size   |       Driver version|
|--|-------------------|---------------------------------------|-------|-------|--------|-----|-------|---------------------|
| 0| [level_zero:gpu:0]|                Intel Arc A770 Graphics|  12.55|    512|    1024|   32| 16225M|         1.14.37020+3|
SYCL Optimization Feature:
|ID|        Device Type|Reorder|
|--|-------------------|-------|
| 0| [level_zero:gpu:0]|      Y|
Testing 2 devices

get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
Backend 1/2: SYCL0
  Device description: Intel(R) Arc(TM) A770 Graphics
  Device memory: 15473 MB (15473 MB free)

level_zero backend failed with error: 20 (UR_RESULT_ERROR_DEVICE_LOST)
Exception caught at file:/hd1/jianyuzh/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/ggml/src/ggml-sycl/ggml-sycl.cpp, line:4396, func:operator()
SYCL error: CHECK_TRY_ERROR((stream)->wait()): Exception caught in this line of code.
  in function ggml_backend_sycl_synchronize at /hd1/jianyuzh/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/ggml/src/ggml-sycl/ggml-sycl.cpp:4396
/hd1/jianyuzh/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/ggml/src/ggml-sycl/../ggml-sycl/common.hpp:135: SYCL error
[New LWP 1508811]
[New LWP 1508658]
warning: File "/opt/intel/oneapi/compiler/2025.3/lib/libsycl.so.8.0.0-gdb.py" auto-loading has been declined by your `auto-load safe-path' set to "$debugdir:$datadir/auto-load".
To enable execution of this file add
	add-auto-load-safe-path /opt/intel/oneapi/compiler/2025.3/lib/libsycl.so.8.0.0-gdb.py
line to your configuration file "/home/jianyuzh/.config/gdb/gdbinit".
To completely disable this security protection add
	set auto-load safe-path /
line to your configuration file "/home/jianyuzh/.config/gdb/gdbinit".
For more information about this security protection see the
"Auto-loading safe path" section in the GDB manual.  E.g., run from the shell:
	info "(gdb)Auto-loading safe path"
[Thread debugging using libthread_db enabled]
Using host libthread_db library "/lib/x86_64-linux-gnu/libthread_db.so.1".
0x00007b1943b10813 in __GI___wait4 (pid=1509042, stat_loc=0x0, options=0, usage=0x0) at ../sysdeps/unix/sysv/linux/wait4.c:30
warning: 30	../sysdeps/unix/sysv/linux/wait4.c: No such file or directory
#0  0x00007b1943b10813 in __GI___wait4 (pid=1509042, stat_loc=0x0, options=0, usage=0x0) at ../sysdeps/unix/sysv/linux/wait4.c:30
30	in ../sysdeps/unix/sysv/linux/wait4.c
#1  0x00007b1947322503 in ggml_print_backtrace () from /hd1/jianyuzh/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/build-ci-release/bin/libggml-base.so.0
#2  0x00007b19473226ab in ggml_abort () from /hd1/jianyuzh/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/build-ci-release/bin/libggml-base.so.0
#3  0x00007b1944324768 in ggml_sycl_error(char const*, char const*, char const*, int, char const*) () from /hd1/jianyuzh/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/build-ci-release/bin/libggml-sycl.so.0
#4  0x00007b1944333998 in ggml_backend_sycl_synchronize(ggml_backend*) () from /hd1/jianyuzh/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/build-ci-release/bin/libggml-sycl.so.0
#5  0x00007b1947342b6a in ggml_backend_compare_graph_backend () from /hd1/jianyuzh/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/build-ci-release/bin/libggml-base.so.0
#6  0x00000000004d8ed7 in test_case::eval(ggml_backend*, ggml_backend*, char const*, printer*) ()
#7  0x000000000041668e in main ()
[Inferior 1 (process 1508656) detached]

      Start 44: test-barrier
39/44 Test #44: test-barrier ......................   Passed    0.98 sec
      Start 45: test-quantize-fns
40/44 Test #45: test-quantize-fns .................   Passed   10.51 sec
      Start 46: test-quantize-perf
41/44 Test #46: test-quantize-perf ................   Passed    0.08 sec
      Start 47: test-rope
42/44 Test #47: test-rope .........................   Passed    0.08 sec
      Start 48: test-mtmd-c-api
43/44 Test #48: test-mtmd-c-api ...................   Passed    0.05 sec
      Start 49: test-alloc
44/44 Test #49: test-alloc ........................   Passed    0.04 sec

89% tests passed, 5 tests failed out of 44

Label Time Summary:
main    = 2083.58 sec*proc (43 tests)

Total Test time (real) = 2093.38 sec

The following tests FAILED:
	 24 - test-llama-archs (Subprocess aborted)
	 35 - test-thread-safety (SEGFAULT)
	 36 - test-arg-parser (Subprocess aborted)
	 38 - test-gguf (Timeout)
	 39 - test-backend-ops (Subprocess aborted)
Errors while running CTest

real	34m53.384s
user	11m32.155s
sys	14m18.409s
```
