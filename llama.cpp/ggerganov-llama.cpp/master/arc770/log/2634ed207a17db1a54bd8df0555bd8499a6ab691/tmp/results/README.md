### ctest_release

Runs ctest in release mode
- status: 8
```
+ ctest --output-on-failure -L main
Test project /hd1/jianyuzh/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/build-ci-release
      Start  1: test-tokenizer-0-bert-bge
 1/41 Test  #1: test-tokenizer-0-bert-bge .........   Passed    0.20 sec
      Start  2: test-tokenizer-0-command-r
 2/41 Test  #2: test-tokenizer-0-command-r ........   Passed    0.46 sec
      Start  3: test-tokenizer-0-deepseek-coder
 3/41 Test  #3: test-tokenizer-0-deepseek-coder ...   Passed    0.10 sec
      Start  4: test-tokenizer-0-deepseek-llm
 4/41 Test  #4: test-tokenizer-0-deepseek-llm .....   Passed    0.21 sec
      Start  5: test-tokenizer-0-falcon
 5/41 Test  #5: test-tokenizer-0-falcon ...........   Passed    0.14 sec
      Start  6: test-tokenizer-0-gpt-2
 6/41 Test  #6: test-tokenizer-0-gpt-2 ............   Passed    0.14 sec
      Start  7: test-tokenizer-0-llama-bpe
 7/41 Test  #7: test-tokenizer-0-llama-bpe ........   Passed    0.34 sec
      Start  8: test-tokenizer-0-llama-spm
 8/41 Test  #8: test-tokenizer-0-llama-spm ........   Passed    0.08 sec
      Start  9: test-tokenizer-0-mpt
 9/41 Test  #9: test-tokenizer-0-mpt ..............   Passed    0.14 sec
      Start 10: test-tokenizer-0-phi-3
10/41 Test #10: test-tokenizer-0-phi-3 ............   Passed    0.10 sec
      Start 11: test-tokenizer-0-qwen2
11/41 Test #11: test-tokenizer-0-qwen2 ............   Passed    0.35 sec
      Start 12: test-tokenizer-0-refact
12/41 Test #12: test-tokenizer-0-refact ...........   Passed    0.13 sec
      Start 13: test-tokenizer-0-starcoder
13/41 Test #13: test-tokenizer-0-starcoder ........   Passed    0.14 sec
      Start 14: test-tokenizers-ggml-vocabs
14/41 Test #14: test-tokenizers-ggml-vocabs .......   Passed    1.59 sec
      Start 15: test-sampling
15/41 Test #15: test-sampling .....................   Passed    0.71 sec
      Start 16: test-grammar-parser
16/41 Test #16: test-grammar-parser ...............   Passed    0.04 sec
      Start 17: test-grammar-integration
17/41 Test #17: test-grammar-integration ..........   Passed    0.04 sec
      Start 18: test-llama-grammar
18/41 Test #18: test-llama-grammar ................   Passed    0.03 sec
      Start 19: test-chat
19/41 Test #19: test-chat .........................   Passed    0.52 sec
      Start 20: test-json-schema-to-grammar
20/41 Test #20: test-json-schema-to-grammar .......   Passed    1.64 sec
      Start 21: test-tokenizer-1-llama-spm
21/41 Test #21: test-tokenizer-1-llama-spm ........   Passed    0.22 sec
      Start 22: test-chat-parser
22/41 Test #22: test-chat-parser ..................   Passed    0.03 sec
      Start 23: test-chat-peg-parser
23/41 Test #23: test-chat-peg-parser ..............   Passed    0.07 sec
      Start 24: test-chat-template
24/41 Test #24: test-chat-template ................   Passed    0.05 sec
      Start 25: test-jinja
25/41 Test #25: test-jinja ........................   Passed    0.07 sec
      Start 27: test-json-partial
26/41 Test #27: test-json-partial .................   Passed    0.03 sec
      Start 28: test-log
27/41 Test #28: test-log ..........................   Passed    0.05 sec
      Start 29: test-peg-parser
28/41 Test #29: test-peg-parser ...................   Passed    0.03 sec
      Start 30: test-regex-partial
29/41 Test #30: test-regex-partial ................   Passed    0.03 sec
      Start 31: test-download-model
30/41 Test #31: test-download-model ...............   Passed    9.29 sec
      Start 32: test-thread-safety
31/41 Test #32: test-thread-safety ................Subprocess aborted***Exception:   4.62 sec
build: 7900 (2634ed207) with GNU 13.3.0 for Linux x86_64
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
load: special_eos_id is not in special_eog_ids - the tokenizer config may be incorrect
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
print_info: pooling type          = 0
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
load: special_eos_id is not in special_eog_ids - the tokenizer config may be incorrect
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
print_info: pooling type          = 0
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
load: special_eos_id is not in special_eog_ids - the tokenizer config may be incorrect
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
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
print_info: n_group_used          = 0
print_info: causal attn           = 1
print_info: pooling type          = 0
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
Creating context 1/4 for model 1/3
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
Creating context 2/4 for model 1/3
Creating context 4/4 for model 1/3
Creating context 3/4 for model 1/3
Creating context 1/4 for model 2/3
| 0| [level_zero:gpu:0]|                Intel Arc A770 Graphics|  12.55|    512|    1024|   32| 16225M|         1.14.37020+3|
SYCL Optimization Feature:
|ID|        Device Type|Reorder|
|--|-------------------|-------|
Creating context 2/4 for model 2/3
| 0| [level_zero:gpu:0]|      Y|
Creating context 1/4 for model 3/3
llama_context: constructing llama_context
llama_context: n_seq_max     = 1
llama_context: n_ctx         = 256
llama_context: n_ctx_seq     = 256
llama_context: n_batch       = 256
llama_context: n_ubatch      = 32
llama_context: causal_attn   = 1
llama_context: flash_attn    = auto
llama_context: kv_unified    = false
Creating context 4/4 for model 2/3
Creating context 3/4 for model 2/3
llama_context: freq_base     = 10000.0
llama_context: freq_scale    = 1
llama_context: n_ctx_seq (256) > n_ctx_train (128) -- possible training context overflow
Creating context 2/4 for model 3/3
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
llama_context: constructing llama_context
llama_context: n_seq_max     = 1
llama_context: n_ctx         = 256
llama_context: n_ctx_seq     = 256
llama_context: n_batch       = 256
llama_context: constructing llama_context
Creating context 3/4 for model 3/3
llama_context: n_seq_max     = 1
llama_context: n_ctx         = 256
llama_context: n_ubatch      = 32
llama_context: n_ctx_seq     = 256
llama_context: causal_attn   = 1
llama_context: n_batch       = 256
llama_context: n_ubatch      = 32
llama_context: flash_attn    = auto
llama_context: causal_attn   = 1
llama_context: flash_attn    = auto
llama_context: kv_unified    = false
llama_context: kv_unified    = false
llama_context: freq_base     = 10000.0
llama_context: freq_base     = 10000.0
llama_context: freq_scale    = 1
llama_context: freq_scale    = 1
llama_context: n_ctx_seq (256) > n_ctx_train (128) -- possible training context overflow
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
llama_context:  SYCL_Host  output buffer size =     0.12 MiB
llama_context:  SYCL_Host  output buffer size =     0.12 MiB
llama_context:        CPU  output buffer size =     0.12 MiB
llama_context:        CPU  output buffer size =     0.12 MiB
llama_context: constructing llama_context
llama_context: n_seq_max     = 1
llama_context: n_ctx         = 256
llama_context: n_ctx_seq     = 256
llama_context: n_batch       = 256
llama_context: n_ubatch      = 32
llama_context: causal_attn   = 1
llama_context: flash_attn    = auto
llama_context: kv_unified    = false
llama_context: constructing llama_context
llama_context: constructing llama_context
llama_context: n_seq_max     = 1
llama_context: n_ctx         = 256
llama_context: n_seq_max     = 1
llama_context: n_ctx_seq     = 256
llama_context: freq_base     = 10000.0
llama_context: freq_scale    = 1
llama_context: n_batch       = 256
llama_context: n_ctx_seq (256) > n_ctx_train (128) -- possible training context overflow
llama_context: constructing llama_context
llama_context: n_seq_max     = 1
llama_context: n_ctx         = 256
llama_context: n_ctx_seq     = 256
llama_context: n_ctx         = 256
llama_context: n_ctx_seq     = 256
llama_context: n_ubatch      = 32
llama_context: n_batch       = 256
llama_context: n_ubatch      = 32
llama_context: causal_attn   = 1
llama_context: causal_attn   = 1
llama_context: flash_attn    = auto
llama_context: kv_unified    = false
llama_context: flash_attn    = auto
llama_context: n_batch       = 256
llama_context: freq_base     = 10000.0
llama_context: kv_unified    = false
llama_context: freq_scale    = 1
llama_context: n_ctx_seq (256) > n_ctx_train (128) -- possible training context overflow
llama_context: n_ubatch      = 32
llama_context: causal_attn   = 1
llama_context: flash_attn    = auto
llama_context: kv_unified    = false
llama_context: freq_base     = 10000.0
Creating context 4/4 for model 3/3
llama_context: freq_base     = 10000.0
llama_context: freq_scale    = 1
llama_context: n_ctx_seq (256) > n_ctx_train (128) -- possible training context overflow
llama_context: freq_scale    = 1
llama_context: n_ctx_seq (256) > n_ctx_train (128) -- possible training context overflow
llama_kv_cache:        CPU KV buffer size =     1.69 MiB
llama_context: constructing llama_context
llama_context: n_seq_max     = 1
llama_context: n_ctx         = 256
llama_context: n_ctx_seq     = 256
llama_context: n_batch       = 256
llama_context:  SYCL_Host  output buffer size =     0.12 MiB
llama_context: n_ubatch      = 32
llama_context: causal_attn   = 1
llama_context: flash_attn    = auto
llama_context: kv_unified    = false
llama_context: freq_base     = 10000.0
llama_context:        CPU  output buffer size =     0.12 MiB
llama_context: freq_scale    = 1
llama_context: n_ctx_seq (256) > n_ctx_train (128) -- possible training context overflow
llama_kv_cache:        CPU KV buffer size =     1.69 MiB
llama_context:  SYCL_Host  output buffer size =     0.12 MiB
llama_context:        CPU  output buffer size =     0.12 MiB
llama_context:  SYCL_Host  output buffer size =     0.12 MiB
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
llama_kv_cache:        CPU KV buffer size =     1.69 MiB
llama_context:  SYCL_Host  output buffer size =     0.12 MiB
llama_kv_cache:      SYCL0 KV buffer size =     1.69 MiB
llama_kv_cache: size =    1.69 MiB (   256 cells,   6 layers,  1/1 seqs), K (f16):    0.84 MiB, V (f16):    0.84 MiB
sched_reserve: reserving ...
llama_kv_cache: size =    1.69 MiB (   256 cells,   6 layers,  1/1 seqs), K (f16):    0.84 MiB, V (f16):    0.84 MiB
sched_reserve: reserving ...
llama_kv_cache: size =    1.69 MiB (   256 cells,   6 layers,  1/1 seqs), K (f16):    0.84 MiB, V (f16):    0.84 MiB
sched_reserve: reserving ...
llama_kv_cache:      SYCL0 KV buffer size =     1.69 MiB
llama_kv_cache: size =    1.69 MiB (   256 cells,   6 layers,  1/1 seqs), K (f16):    0.84 MiB, V (f16):    0.84 MiB
sched_reserve: reserving ...
llama_kv_cache: size =    1.69 MiB (   256 cells,   6 layers,  1/1 seqs), K (f16):    0.84 MiB, V (f16):    0.84 MiB
sched_reserve: reserving ...
sched_reserve: layer 0 is assigned to device SYCL0 but the Flash Attention tensor is assigned to device CPU (usually due to missing support)
sched_reserve: Flash Attention was auto, set to disabled
llama_kv_cache:      SYCL0 KV buffer size =     1.69 MiB
llama_kv_cache: size =    1.69 MiB (   256 cells,   6 layers,  1/1 seqs), K (f16):    0.84 MiB, V (f16):    0.84 MiB
sched_reserve: reserving ...
llama_kv_cache: size =    1.69 MiB (   256 cells,   6 layers,  1/1 seqs), K (f16):    0.84 MiB, V (f16):    0.84 MiB
sched_reserve: reserving ...
sched_reserve: Flash Attention was auto, set to enabled
sched_reserve: Flash Attention was auto, set to enabled
sched_reserve: layer 0 is assigned to device SYCL0 but the Flash Attention tensor is assigned to device CPU (usually due to missing support)
sched_reserve: Flash Attention was auto, set to disabled
sched_reserve:        CPU compute buffer size =     4.13 MiB
sched_reserve: graph nodes  = 193
sched_reserve: graph splits = 1
sched_reserve: reserve took 0.49 ms, sched copies = 1
sched_reserve:        CPU compute buffer size =     4.13 MiB
sched_reserve: graph nodes  = 193
sched_reserve: graph splits = 1
sched_reserve: reserve took 0.50 ms, sched copies = 1
sched_reserve: layer 0 is assigned to device SYCL0 but the Flash Attention tensor is assigned to device CPU (usually due to missing support)
sched_reserve: Flash Attention was auto, set to disabled
llama_kv_cache:      SYCL0 KV buffer size =     1.69 MiB
sched_reserve: Flash Attention was auto, set to enabled
llama_kv_cache: size =    1.69 MiB (   256 cells,   6 layers,  1/1 seqs), K (f16):    0.84 MiB, V (f16):    0.84 MiB
sched_reserve: reserving ...
sched_reserve:      SYCL0 compute buffer size =     4.08 MiB
sched_reserve:  SYCL_Host compute buffer size =     0.10 MiB
sched_reserve: graph nodes  = 222
sched_reserve: graph splits = 2
sched_reserve: reserve took 0.90 ms, sched copies = 1
sched_reserve: Flash Attention was auto, set to enabled
sched_reserve:      SYCL0 compute buffer size =     4.08 MiB
sched_reserve:  SYCL_Host compute buffer size =     0.10 MiB
sched_reserve: graph nodes  = 222
sched_reserve: graph splits = 2
sched_reserve: reserve took 0.75 ms, sched copies = 1
sched_reserve:        CPU compute buffer size =     4.13 MiB
sched_reserve: graph nodes  = 193
sched_reserve: graph splits = 1
sched_reserve: reserve took 0.84 ms, sched copies = 1
llama_kv_cache:      SYCL0 KV buffer size =     1.69 MiB
sched_reserve:        CPU compute buffer size =     4.13 MiB
sched_reserve: graph nodes  = 193
sched_reserve: graph splits = 1
sched_reserve: reserve took 0.74 ms, sched copies = 1
sched_reserve: layer 0 is assigned to device SYCL0 but the Flash Attention tensor is assigned to device CPU (usually due to missing support)
sched_reserve: Flash Attention was auto, set to disabled
sched_reserve:      SYCL0 compute buffer size =     4.08 MiB
sched_reserve:  SYCL_Host compute buffer size =     0.10 MiB
sched_reserve: graph nodes  = 222
sched_reserve: graph splits = 2
sched_reserve: reserve took 1.05 ms, sched copies = 1
llama_kv_cache:      SYCL0 KV buffer size =     1.69 MiB
llama_kv_cache:      SYCL0 KV buffer size =     1.69 MiB
sched_reserve:      SYCL0 compute buffer size =     4.08 MiB
sched_reserve:  SYCL_Host compute buffer size =     0.10 MiB
sched_reserve: graph nodes  = 222
sched_reserve: graph splits = 2
sched_reserve: reserve took 1.16 ms, sched copies = 1
llama_kv_cache:      SYCL0 KV buffer size =     1.69 MiB
Model 2/3, Context 3/4: The meaning of life is a small, little girl who loves to explore. One day she was in her backyard, looking around and noticed something strange.
Suddenly, she saw a little frog sitting on a rock. It was a big, green frog!
The frog looked up at her and said, "Hi! Do you want to come and play with me?"
The little girl was very excited, but the frog was so big that she could not move. She said, "No thank you. I don't want to stay in the yard."
The frog didn't answer. He just

Model 2/3, Context 1/4: The meaning of life is full of hope. It is a warm day and the sun is bright and the sky is a lovely blue. The sun is so friendly and lovely. 
Mummy and Daddy are getting ready. Little Jim, what do you want to do?" 
Mummy said, "Let's make something special. What would you like to make?" 
Jim thought for a moment and then said, "I want to make something toast!" 
Mummy and Daddy smiled. They both got to work and soon had made toast. As soon as it was done, they both had a big

Model 2/3, Context 4/4: The meaning of life is on the most original day. One day, it started to rain and the rain started to fall. Little Jack was scared he wouldn't be able to jump in the puddles. He ran inside and started to cry.
Mummy came in and saw Jack crying. She asked Jack, "What happened? Why are you crying?"
Jack said, "The rain rained and I can't jump in the puddles."
Mummy said, "Little Jack, don't worry. Let's go outside and jump in the puddles and you can jump in

Model 2/3, Context 2/4: The meaning of life is a little boy. He has a big heart and he loves to be kind to everyone around him. One day, he was walking through the park when he saw a big, blue bird. It was so pretty and the bird was so small. He wanted to be friends with it.
The bird looked at him and said, "I am a bit scared."
The boy smiled and said, "I want to be your friend, but I only have a lot of money."
The bird looked at him and said, "I have a price. You can't have me. You are too big for me."

llama_kv_cache: size =    1.69 MiB (   256 cells,   6 layers,  1/1 seqs), K (f16):    0.84 MiB, V (f16):    0.84 MiB
sched_reserve: reserving ...
sched_reserve: layer 0 is assigned to device SYCL0 but the Flash Attention tensor is assigned to device CPU (usually due to missing support)
sched_reserve: Flash Attention was auto, set to disabled
sched_reserve:      SYCL0 compute buffer size =     4.08 MiB
sched_reserve:  SYCL_Host compute buffer size =     0.10 MiB
sched_reserve: graph nodes  = 222
sched_reserve: graph splits = 2
sched_reserve: reserve took 0.93 ms, sched copies = 1
llama_kv_cache: size =    1.69 MiB (   256 cells,   6 layers,  1/1 seqs), K (f16):    0.84 MiB, V (f16):    0.84 MiB
sched_reserve: reserving ...
llama_kv_cache: size =    1.69 MiB (   256 cells,   6 layers,  1/1 seqs), K (f16):    0.84 MiB, V (f16):    0.84 MiB
sched_reserve: reserving ...
llama_kv_cache: size =    1.69 MiB (   256 cells,   6 layers,  1/1 seqs), K (f16):    0.84 MiB, V (f16):    0.84 MiB
sched_reserve: reserving ...
sched_reserve: layer 0 is assigned to device SYCL0 but the Flash Attention tensor is assigned to device CPU (usually due to missing support)
sched_reserve: Flash Attention was auto, set to disabled
sched_reserve: layer 0 is assigned to device SYCL0 but the Flash Attention tensor is assigned to device CPU (usually due to missing support)
sched_reserve: Flash Attention was auto, set to disabled
sched_reserve: layer 0 is assigned to device SYCL0 but the Flash Attention tensor is assigned to device CPU (usually due to missing support)
sched_reserve: Flash Attention was auto, set to disabled
sched_reserve:      SYCL0 compute buffer size =     4.08 MiB
sched_reserve:  SYCL_Host compute buffer size =     0.10 MiB
sched_reserve: graph nodes  = 222
sched_reserve: graph splits = 2
sched_reserve:      SYCL0 compute buffer size =     4.08 MiB
sched_reserve: reserve took 1.18 ms, sched copies = 1
sched_reserve:  SYCL_Host compute buffer size =     0.10 MiB
sched_reserve: graph nodes  = 222
sched_reserve: graph splits = 2
sched_reserve: reserve took 0.86 ms, sched copies = 1
sched_reserve:      SYCL0 compute buffer size =     4.08 MiB
sched_reserve:  SYCL_Host compute buffer size =     0.10 MiB
sched_reserve: graph nodes  = 222
sched_reserve: graph splits = 2
sched_reserve: reserve took 1.23 ms, sched copies = 1
Model 3/3, Context 3/4: The meaning of life is

corrupted double-linked list

      Start 33: test-arg-parser
32/41 Test #33: test-arg-parser ...................Subprocess aborted***Exception: 539.63 sec
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
-sm,   --split-mode {none,layer,row}    how to split the model across multiple GPUs, one of:
                                        - none: use one GPU only
                                        - layer (default): split layers and KV across GPUs
                                        - row: split rows across GPUs
                                        (env: LLAMA_ARG_SPLIT_MODE)


to show complete usage, run with -h
error: invalid argument: --draft
error: --model is required

error while handling environment variable "LLAMA_ARG_THREADS": stoi


warn: LLAMA_ARG_MODEL environment variable is set, but will be overwritten by command line argument -m
[New LWP 3131361]
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
0x00007cc2b3b10813 in __GI___wait4 (pid=3150099, stat_loc=0x0, options=0, usage=0x0) at ../sysdeps/unix/sysv/linux/wait4.c:30
warning: 30	../sysdeps/unix/sysv/linux/wait4.c: No such file or directory
#0  0x00007cc2b3b10813 in __GI___wait4 (pid=3150099, stat_loc=0x0, options=0, usage=0x0) at ../sysdeps/unix/sysv/linux/wait4.c:30
30	in ../sysdeps/unix/sysv/linux/wait4.c
#1  0x00007cc2b4b98123 in ggml_print_backtrace () from /hd1/jianyuzh/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/build-ci-release/bin/libggml-base.so.0
#2  0x00007cc2b4baac06 in ggml_uncaught_exception() () from /hd1/jianyuzh/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/build-ci-release/bin/libggml-base.so.0
#3  0x00007cc2b3ebb0da in ?? () from /lib/x86_64-linux-gnu/libstdc++.so.6
#4  0x00007cc2b3ea5a55 in std::terminate() () from /lib/x86_64-linux-gnu/libstdc++.so.6
#5  0x00007cc2b3ebb391 in __cxa_throw () from /lib/x86_64-linux-gnu/libstdc++.so.6
#6  0x00000000004fc4b0 in common_remote_get_content(std::__cxx11::basic_string<char, std::char_traits<char>, std::allocator<char> > const&, common_remote_params const&) ()
#7  0x00000000004249f5 in main ()
[Inferior 1 (process 3131359) detached]
terminate called after throwing an instance of 'std::runtime_error'
  what():  error: cannot make GET request

      Start 34: test-opt
33/41 Test #34: test-opt ..........................   Passed    0.21 sec
      Start 35: test-gguf
34/41 Test #35: test-gguf .........................   Passed    0.30 sec
      Start 36: test-backend-ops
35/41 Test #36: test-backend-ops ..................   Passed   70.20 sec
      Start 41: test-barrier
36/41 Test #41: test-barrier ......................   Passed    1.13 sec
      Start 42: test-quantize-fns
37/41 Test #42: test-quantize-fns .................   Passed   10.46 sec
      Start 43: test-quantize-perf
38/41 Test #43: test-quantize-perf ................   Passed    0.11 sec
      Start 44: test-rope
39/41 Test #44: test-rope .........................   Passed    0.07 sec
      Start 45: test-mtmd-c-api
40/41 Test #45: test-mtmd-c-api ...................   Passed    0.18 sec
      Start 46: test-alloc
41/41 Test #46: test-alloc ........................   Passed    0.21 sec

95% tests passed, 2 tests failed out of 41

Label Time Summary:
main    = 634.81 sec*proc (40 tests)

Total Test time (real) = 644.32 sec

The following tests FAILED:
	 32 - test-thread-safety (Subprocess aborted)
	 33 - test-arg-parser (Subprocess aborted)
Errors while running CTest

real	10m44.338s
user	2m55.621s
sys	0m38.063s
```
