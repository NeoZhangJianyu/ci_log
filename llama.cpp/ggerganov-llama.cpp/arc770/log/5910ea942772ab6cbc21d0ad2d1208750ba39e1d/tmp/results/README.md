### ctest_release

Runs ctest in release mode
- status: 8
```
+ ctest --output-on-failure -L main
Test project /home/jianyuzh/ws/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/build-ci-release
      Start  1: test-tokenizer-0-bert-bge
 1/25 Test  #1: test-tokenizer-0-bert-bge .........   Passed    0.04 sec
      Start  2: test-tokenizer-0-command-r
 2/25 Test  #2: test-tokenizer-0-command-r ........   Passed    0.34 sec
      Start  3: test-tokenizer-0-deepseek-coder
 3/25 Test  #3: test-tokenizer-0-deepseek-coder ...   Passed    0.07 sec
      Start  4: test-tokenizer-0-deepseek-llm
 4/25 Test  #4: test-tokenizer-0-deepseek-llm .....   Passed    0.15 sec
      Start  5: test-tokenizer-0-falcon
 5/25 Test  #5: test-tokenizer-0-falcon ...........   Passed    0.09 sec
      Start  6: test-tokenizer-0-gpt-2
 6/25 Test  #6: test-tokenizer-0-gpt-2 ............   Passed    0.08 sec
      Start  7: test-tokenizer-0-llama-bpe
 7/25 Test  #7: test-tokenizer-0-llama-bpe ........   Passed    0.26 sec
      Start  8: test-tokenizer-0-llama-spm
 8/25 Test  #8: test-tokenizer-0-llama-spm ........   Passed    0.05 sec
      Start  9: test-tokenizer-0-mpt
 9/25 Test  #9: test-tokenizer-0-mpt ..............   Passed    0.08 sec
      Start 10: test-tokenizer-0-phi-3
10/25 Test #10: test-tokenizer-0-phi-3 ............   Passed    0.04 sec
      Start 11: test-tokenizer-0-qwen2
11/25 Test #11: test-tokenizer-0-qwen2 ............   Passed    0.19 sec
      Start 12: test-tokenizer-0-refact
12/25 Test #12: test-tokenizer-0-refact ...........   Passed    0.08 sec
      Start 13: test-tokenizer-0-starcoder
13/25 Test #13: test-tokenizer-0-starcoder ........   Passed    0.08 sec
      Start 14: test-tokenizer-1-llama-spm
14/25 Test #14: test-tokenizer-1-llama-spm ........   Passed    0.10 sec
      Start 15: test-quantize-fns
15/25 Test #15: test-quantize-fns .................   Passed   10.00 sec
      Start 16: test-quantize-perf
16/25 Test #16: test-quantize-perf ................   Passed    2.81 sec
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
22/25 Test #22: test-grad0 ........................   Passed    0.19 sec
      Start 23: test-backend-ops
23/25 Test #23: test-backend-ops ..................   Passed   19.45 sec
      Start 24: test-rope
24/25 Test #24: test-rope .........................   Passed    0.05 sec
      Start 27: test-json-schema-to-grammar
25/25 Test #27: test-json-schema-to-grammar .......Subprocess aborted***Exception:   1.31 sec
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
test-json-schema-to-grammar: /home/jianyuzh/ws/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/tests/test-json-schema-to-grammar.cpp:58: void TestCase::verify_status(TestCaseStatus) const: Assertion `false' failed.


96% tests passed, 1 tests failed out of 25

Label Time Summary:
main    =  35.60 sec*proc (25 tests)

Total Test time (real) =  35.61 sec

The following tests FAILED:
	 27 - test-json-schema-to-grammar (Subprocess aborted)
Errors while running CTest

real	0m35.610s
user	0m43.329s
sys	0m3.447s
```