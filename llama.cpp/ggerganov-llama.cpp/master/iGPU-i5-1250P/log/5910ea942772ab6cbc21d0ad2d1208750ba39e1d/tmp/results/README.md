### ctest_release

Runs ctest in release mode
- status: 0
```
+ ctest --output-on-failure -L main
Test project /home/zjy/ws/jenkins-home/workspace/ci-1250@2/ggerganov-llama.cpp/build-ci-release
      Start  1: test-tokenizer-0-bert-bge
 1/25 Test  #1: test-tokenizer-0-bert-bge .........   Passed    0.05 sec
      Start  2: test-tokenizer-0-command-r
 2/25 Test  #2: test-tokenizer-0-command-r ........   Passed    0.46 sec
      Start  3: test-tokenizer-0-deepseek-coder
 3/25 Test  #3: test-tokenizer-0-deepseek-coder ...   Passed    0.07 sec
      Start  4: test-tokenizer-0-deepseek-llm
 4/25 Test  #4: test-tokenizer-0-deepseek-llm .....   Passed    0.19 sec
      Start  5: test-tokenizer-0-falcon
 5/25 Test  #5: test-tokenizer-0-falcon ...........   Passed    0.12 sec
      Start  6: test-tokenizer-0-gpt-2
 6/25 Test  #6: test-tokenizer-0-gpt-2 ............   Passed    0.09 sec
      Start  7: test-tokenizer-0-llama-bpe
 7/25 Test  #7: test-tokenizer-0-llama-bpe ........   Passed    0.33 sec
      Start  8: test-tokenizer-0-llama-spm
 8/25 Test  #8: test-tokenizer-0-llama-spm ........   Passed    0.05 sec
      Start  9: test-tokenizer-0-mpt
 9/25 Test  #9: test-tokenizer-0-mpt ..............   Passed    0.10 sec
      Start 10: test-tokenizer-0-phi-3
10/25 Test #10: test-tokenizer-0-phi-3 ............   Passed    0.05 sec
      Start 11: test-tokenizer-0-qwen2
11/25 Test #11: test-tokenizer-0-qwen2 ............   Passed    0.26 sec
      Start 12: test-tokenizer-0-refact
12/25 Test #12: test-tokenizer-0-refact ...........   Passed    0.09 sec
      Start 13: test-tokenizer-0-starcoder
13/25 Test #13: test-tokenizer-0-starcoder ........   Passed    0.09 sec
      Start 14: test-tokenizer-1-llama-spm
14/25 Test #14: test-tokenizer-1-llama-spm ........   Passed    0.15 sec
      Start 15: test-quantize-fns
15/25 Test #15: test-quantize-fns .................   Passed   13.71 sec
      Start 16: test-quantize-perf
16/25 Test #16: test-quantize-perf ................   Passed    3.85 sec
      Start 17: test-sampling
17/25 Test #17: test-sampling .....................   Passed    0.03 sec
      Start 18: test-chat-template
18/25 Test #18: test-chat-template ................   Passed    0.03 sec
      Start 19: test-grammar-parser
19/25 Test #19: test-grammar-parser ...............   Passed    0.03 sec
      Start 20: test-llama-grammar
20/25 Test #20: test-llama-grammar ................   Passed    0.03 sec
      Start 21: test-grammar-integration
21/25 Test #21: test-grammar-integration ..........   Passed    0.03 sec
      Start 22: test-grad0
22/25 Test #22: test-grad0 ........................   Passed    0.24 sec
      Start 23: test-backend-ops
23/25 Test #23: test-backend-ops ..................   Passed   28.51 sec
      Start 24: test-rope
24/25 Test #24: test-rope .........................   Passed    0.06 sec
      Start 27: test-json-schema-to-grammar
25/25 Test #27: test-json-schema-to-grammar .......   Passed    1.52 sec

100% tests passed, 0 tests failed out of 25

Label Time Summary:
main    =  50.15 sec*proc (25 tests)

Total Test time (real) =  50.16 sec

real	0m50.168s
user	1m6.166s
sys	0m5.244s
```
