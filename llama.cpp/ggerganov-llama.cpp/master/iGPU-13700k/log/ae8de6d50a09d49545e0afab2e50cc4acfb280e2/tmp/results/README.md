### ctest_release

Runs ctest in release mode
- status: 8
```
+ ctest --output-on-failure -L main
Test project /home/jianyuzh/ws/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/build-ci-release
      Start  1: test-tokenizer-0-bert-bge
 1/28 Test  #1: test-tokenizer-0-bert-bge .........   Passed    0.09 sec
      Start  2: test-tokenizer-0-command-r
 2/28 Test  #2: test-tokenizer-0-command-r ........   Passed    0.40 sec
      Start  3: test-tokenizer-0-deepseek-coder
 3/28 Test  #3: test-tokenizer-0-deepseek-coder ...   Passed    0.09 sec
      Start  4: test-tokenizer-0-deepseek-llm
 4/28 Test  #4: test-tokenizer-0-deepseek-llm .....   Passed    0.19 sec
      Start  5: test-tokenizer-0-falcon
 5/28 Test  #5: test-tokenizer-0-falcon ...........   Passed    0.12 sec
      Start  6: test-tokenizer-0-gpt-2
 6/28 Test  #6: test-tokenizer-0-gpt-2 ............   Passed    0.11 sec
      Start  7: test-tokenizer-0-llama-bpe
 7/28 Test  #7: test-tokenizer-0-llama-bpe ........   Passed    0.32 sec
      Start  8: test-tokenizer-0-llama-spm
 8/28 Test  #8: test-tokenizer-0-llama-spm ........   Passed    0.07 sec
      Start  9: test-tokenizer-0-mpt
 9/28 Test  #9: test-tokenizer-0-mpt ..............   Passed    0.10 sec
      Start 10: test-tokenizer-0-phi-3
10/28 Test #10: test-tokenizer-0-phi-3 ............   Passed    0.06 sec
      Start 11: test-tokenizer-0-qwen2
11/28 Test #11: test-tokenizer-0-qwen2 ............   Passed    0.24 sec
      Start 12: test-tokenizer-0-refact
12/28 Test #12: test-tokenizer-0-refact ...........   Passed    0.11 sec
      Start 13: test-tokenizer-0-starcoder
13/28 Test #13: test-tokenizer-0-starcoder ........   Passed    0.10 sec
      Start 14: test-tokenizer-1-llama-spm
14/28 Test #14: test-tokenizer-1-llama-spm ........   Passed    0.14 sec
      Start 15: test-log
15/28 Test #15: test-log ..........................   Passed    0.04 sec
      Start 16: test-arg-parser
16/28 Test #16: test-arg-parser ...................   Passed    0.07 sec
      Start 17: test-quantize-fns
17/28 Test #17: test-quantize-fns .................   Passed   10.07 sec
      Start 18: test-quantize-perf
18/28 Test #18: test-quantize-perf ................   Passed    0.08 sec
      Start 19: test-sampling
19/28 Test #19: test-sampling .....................   Passed    0.84 sec
      Start 20: test-chat-template
20/28 Test #20: test-chat-template ................   Passed    0.03 sec
      Start 21: test-grammar-parser
21/28 Test #21: test-grammar-parser ...............   Passed    0.04 sec
      Start 22: test-llama-grammar
22/28 Test #22: test-llama-grammar ................   Passed    0.05 sec
      Start 23: test-grammar-integration
23/28 Test #23: test-grammar-integration ..........   Passed    0.05 sec
      Start 24: test-grad0
24/28 Test #24: test-grad0 ........................   Passed    0.23 sec
      Start 25: test-barrier
25/28 Test #25: test-barrier ......................   Passed    0.17 sec
      Start 26: test-backend-ops
26/28 Test #26: test-backend-ops ..................   Passed   33.43 sec
      Start 27: test-rope
27/28 Test #27: test-rope .........................   Passed    0.06 sec
      Start 30: test-json-schema-to-grammar
28/28 Test #30: test-json-schema-to-grammar .......Subprocess aborted***Exception:   1.58 sec
LLAMA_NODE_AVAILABLE = false
LLAMA_PYTHON_AVAILABLE = false
#
# Testing JSON schema conversion (C++)
#
- min 0
- min 1
- min 3
- min 9
- min 10
- min 25
- max 30
- min -5
- min -123
- max -5
- max 1
- max 100
- min 0 max 23
- min 15 max 300
- min 5 max 30
- min -123 max 42
- min -10 max 10
- unknown type (failure expected)
Error: JSON schema conversion failed:
Unrecognized schema: {"type":"kaboom"}
- invalid type (failure expected)
Error: JSON schema conversion failed:
Unrecognized schema: {"type":123}
- empty schema (object)
- exotic formats
- string
- string w/ min length 1
- string w/ min length 3
- string w/ max length
- string w/ min & max length
- boolean
- integer
- string const
- non-string const
- non-string enum
- string array
- nullable string array
- tuple1
- tuple2
- number
- minItems
- maxItems 1
- maxItems 2
- min + maxItems
- min + max items with min + max values across zero
- min + max items with min + max values
- simple regexp
- regexp escapes
- regexp quote
- regexp with top-level alternation
- regexp
- required props in original order
- 1 optional prop
- N optional props
- required + optional props each in original order
- additional props
- additional props (true)
- additional props (implicit)
- empty w/o additional props
- required + additional props
- optional + additional props
- required + optional + additional props
- optional props with empty name
- optional props with nested names
- optional props with common prefix
- top-level $ref
- anyOf
- mix of allOf, anyOf and $ref (similar to https://json.schemastore.org/tsconfig.json)
- conflicting names
Python version is sufficient
#
# Testing JSON schema conversion (Python)
#
- min 0
- min 1
- min 3
- min 9
- min 10
- min 25
- max 30
- min -5
- min -123
- max -5
- max 1
- max 100
- min 0 max 23
- min 15 max 300
- min 5 max 30
- min -123 max 42
- min -10 max 10
- unknown type (failure expected)
Traceback (most recent call last):
  File "/home/jianyuzh/ws/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/./examples/json_schema_to_grammar.py", line 811, in <module>
    main()
  File "/home/jianyuzh/ws/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/./examples/json_schema_to_grammar.py", line 806, in main
    converter.visit(schema, '')
  File "/home/jianyuzh/ws/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/./examples/json_schema_to_grammar.py", line 667, in visit
    assert schema_type in PRIMITIVE_RULES, f'Unrecognized schema: {schema}'
AssertionError: Unrecognized schema: {'type': 'kaboom'}
- invalid type (failure expected)
Traceback (most recent call last):
  File "/home/jianyuzh/ws/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/./examples/json_schema_to_grammar.py", line 811, in <module>
    main()
  File "/home/jianyuzh/ws/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/./examples/json_schema_to_grammar.py", line 806, in main
    converter.visit(schema, '')
  File "/home/jianyuzh/ws/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/./examples/json_schema_to_grammar.py", line 667, in visit
    assert schema_type in PRIMITIVE_RULES, f'Unrecognized schema: {schema}'
AssertionError: Unrecognized schema: {'type': 123}
- empty schema (object)
- exotic formats
- string
- string w/ min length 1
- string w/ min length 3
- string w/ max length
- string w/ min & max length
- boolean
- integer
- string const
- non-string const
- non-string enum
- string array
- nullable string array
- tuple1
- tuple2
- number
- minItems
- maxItems 1
- maxItems 2
- min + maxItems
- min + max items with min + max values across zero
- min + max items with min + max values
- simple regexp
- regexp escapes
- regexp quote
- regexp with top-level alternation
- regexp
- required props in original order
- 1 optional prop
- N optional props
- required + optional props each in original order
- additional props
- additional props (true)
- additional props (implicit)
- empty w/o additional props
- required + additional props
- optional + additional props
- required + optional + additional props
- optional props with empty name
- optional props with nested names
- optional props with common prefix
- top-level $ref
- anyOf
- mix of allOf, anyOf and $ref (similar to https://json.schemastore.org/tsconfig.json)
- conflicting names
v12.22.9
#
# Testing JSON schema conversion (JavaScript)
#
- min 0
file:///home/jianyuzh/ws/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/tests/run-json-schema-to-grammar.mjs:8
schema = await converter.resolveRefs(schema, url)
         ^^^^^

SyntaxError: Unexpected reserved word
    at Loader.moduleStrategy (internal/modules/esm/translators.js:133:18)
    at async link (internal/modules/esm/module_job.js:42:21)
#
# Test 'min 0' failed.
#
{
            "type": "integer",
            "minimum": 0
        }
# EXPECTED STATUS: SUCCESS
# ACTUAL STATUS: FAILURE
test-json-schema-to-grammar: /home/jianyuzh/ws/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/tests/test-json-schema-to-grammar.cpp:60: void TestCase::verify_status(TestCaseStatus) const: Assertion `false' failed.


96% tests passed, 1 tests failed out of 28

Label Time Summary:
main    =  48.89 sec*proc (28 tests)

Total Test time (real) =  48.90 sec

The following tests FAILED:
	 30 - test-json-schema-to-grammar (Subprocess aborted)
Errors while running CTest

real	0m48.898s
user	0m54.413s
sys	0m21.048s
```