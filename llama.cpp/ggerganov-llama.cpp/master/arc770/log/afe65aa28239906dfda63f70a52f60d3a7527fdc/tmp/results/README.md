### ctest_release

Runs ctest in release mode
- status: 8
```
+ ctest --output-on-failure -L main
Test project /hd1/jianyuzh/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/build-ci-release
      Start  1: test-tokenizer-0-bert-bge
 1/43 Test  #1: test-tokenizer-0-bert-bge .........   Passed    0.16 sec
      Start  2: test-tokenizer-0-command-r
 2/43 Test  #2: test-tokenizer-0-command-r ........   Passed    0.31 sec
      Start  3: test-tokenizer-0-deepseek-coder
 3/43 Test  #3: test-tokenizer-0-deepseek-coder ...   Passed    0.09 sec
      Start  4: test-tokenizer-0-deepseek-llm
 4/43 Test  #4: test-tokenizer-0-deepseek-llm .....   Passed    0.15 sec
      Start  5: test-tokenizer-0-falcon
 5/43 Test  #5: test-tokenizer-0-falcon ...........   Passed    0.12 sec
      Start  6: test-tokenizer-0-gpt-2
 6/43 Test  #6: test-tokenizer-0-gpt-2 ............   Passed    0.10 sec
      Start  7: test-tokenizer-0-llama-bpe
 7/43 Test  #7: test-tokenizer-0-llama-bpe ........   Passed    0.21 sec
      Start  8: test-tokenizer-0-llama-spm
 8/43 Test  #8: test-tokenizer-0-llama-spm ........   Passed    0.07 sec
      Start  9: test-tokenizer-0-mpt
 9/43 Test  #9: test-tokenizer-0-mpt ..............   Passed    0.10 sec
      Start 10: test-tokenizer-0-phi-3
10/43 Test #10: test-tokenizer-0-phi-3 ............   Passed    0.09 sec
      Start 11: test-tokenizer-0-qwen2
11/43 Test #11: test-tokenizer-0-qwen2 ............   Passed    0.22 sec
      Start 12: test-tokenizer-0-refact
12/43 Test #12: test-tokenizer-0-refact ...........   Passed    0.12 sec
      Start 13: test-tokenizer-0-starcoder
13/43 Test #13: test-tokenizer-0-starcoder ........   Passed    0.10 sec
      Start 14: test-tokenizers-ggml-vocabs
14/43 Test #14: test-tokenizers-ggml-vocabs .......   Passed    1.48 sec
      Start 15: test-sampling
15/43 Test #15: test-sampling .....................   Passed    0.74 sec
      Start 16: test-reasoning-budget
16/43 Test #16: test-reasoning-budget .............   Passed    0.04 sec
      Start 17: test-grammar-parser
17/43 Test #17: test-grammar-parser ...............   Passed    0.04 sec
      Start 18: test-grammar-integration
18/43 Test #18: test-grammar-integration ..........   Passed    0.05 sec
      Start 19: test-llama-grammar
19/43 Test #19: test-llama-grammar ................   Passed    0.05 sec
      Start 20: test-chat
20/43 Test #20: test-chat .........................   Passed    1.37 sec
      Start 21: test-json-schema-to-grammar
21/43 Test #21: test-json-schema-to-grammar .......   Passed    1.82 sec
      Start 22: test-tokenizer-1-llama-spm
22/43 Test #22: test-tokenizer-1-llama-spm ........   Passed    0.15 sec
      Start 23: test-llama-archs
23/43 Test #23: test-llama-archs ..................   Passed    4.49 sec
      Start 24: test-chat-peg-parser
24/43 Test #24: test-chat-peg-parser ..............   Passed    0.06 sec
      Start 25: test-jinja
25/43 Test #25: test-jinja ........................   Passed    0.09 sec
      Start 27: test-chat-auto-parser
26/43 Test #27: test-chat-auto-parser .............   Passed    0.09 sec
      Start 28: test-chat-template
27/43 Test #28: test-chat-template ................   Passed    0.08 sec
      Start 29: test-json-partial
28/43 Test #29: test-json-partial .................   Passed    0.04 sec
      Start 30: test-log
29/43 Test #30: test-log ..........................   Passed    0.05 sec
      Start 31: test-peg-parser
30/43 Test #31: test-peg-parser ...................   Passed    0.04 sec
      Start 32: test-regex-partial
31/43 Test #32: test-regex-partial ................   Passed    0.04 sec
      Start 33: test-download-model
32/43 Test #33: test-download-model ...............   Passed    9.03 sec
      Start 34: test-thread-safety
33/43 Test #34: test-thread-safety ................***Exception: SegFault  4.38 sec
build: 8576 (afe65aa28) with GNU 13.3.0 for Linux x86_64
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
print_info: f_max_alibi_bias      = 0.0e+00
print_info: f_logit_scale         = 0.0e+00
print_info: f_attn_scale          = 0.0e+00
print_info: n_ff                  = 768
print_info: n_expert              = 0
print_info: n_expert_used         = 0
print_info: n_expert_groups       = 0
print_info: n_group_used          = 0
print_info: causal attn           = 1
get_memory_info: [warning] ext_intel_free_memory is not supported (export/set ZES_ENABLE_SYSMAN=1 to support), use total memory as free memory
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
Creating context 2/4 for model 2/3
Creating context 2/4 for model 1/3
Creating context 4/4 for model 1/3
| 0| [level_zero:gpu:0]|                Intel Arc A770 Graphics|  12.55|    512|    1024|   32| 16225M|         1.14.37020+3|
Creating context 3/4 for model 1/3
SYCL Optimization Feature:
|ID|        Device Type|Reorder|
|--|-------------------|-------|
Creating context 4/4 for model 2/3
| 0| [level_zero:gpu:0]|      Y|
llama_context: constructing llama_context
llama_context: n_seq_max     = 1
llama_context: n_ctx         = 256
llama_context: n_ctx_seq     = 256
llama_context: n_batch       = 256
Creating context 3/4 for model 2/3
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
llama_context: freq_base     = 10000.0
llama_context: freq_scale    = 1
llama_context: n_ctx_seq (256) > n_ctx_train (128) -- possible training context overflow
llama_context: constructing llama_context
Creating context 1/4 for model 2/3
llama_context: n_seq_max     = 1
llama_context: n_ctx         = 256
llama_context: n_ctx_seq     = 256
llama_context: constructing llama_context
llama_context: n_seq_max     = 1
llama_context: n_ctx         = 256
llama_context: n_ctx_seq     = 256
llama_context: n_batch       = 256
llama_context: n_ubatch      = 32
llama_context: n_batch       = 256
llama_context: causal_attn   = 1
llama_context: n_ubatch      = 32
llama_context: flash_attn    = auto
llama_context: causal_attn   = 1
llama_context: kv_unified    = false
llama_context: flash_attn    = auto
llama_context: kv_unified    = false
llama_context: freq_base     = 10000.0
llama_context: freq_scale    = 1
llama_context: n_ctx_seq (256) > n_ctx_train (128) -- possible training context overflow
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
llama_context:        CPU  output buffer size =     0.12 MiB
llama_context:        CPU  output buffer size =     0.12 MiB
llama_context:  SYCL_Host  output buffer size =     0.12 MiB
Creating context 2/4 for model 3/3
llama_kv_cache:        CPU KV buffer size =     1.69 MiB
llama_context:  SYCL_Host  output buffer size =     0.12 MiB
llama_context:        CPU  output buffer size =     0.12 MiB
llama_context:  SYCL_Host  output buffer size =     0.12 MiB
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
llama_context:  SYCL_Host  output buffer size =     0.12 MiB
llama_context: constructing llama_context
llama_kv_cache:        CPU KV buffer size =     1.69 MiB
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
Creating context 3/4 for model 3/3
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
llama_context:        CPU  output buffer size =     0.12 MiB
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
llama_kv_cache:        CPU KV buffer size =     1.69 MiB
llama_context:  SYCL_Host  output buffer size =     0.12 MiB
llama_context:  SYCL_Host  output buffer size =     0.12 MiB
llama_kv_cache:      SYCL0 KV buffer size =     1.69 MiB
llama_kv_cache: size =    1.69 MiB (   256 cells,   6 layers,  1/1 seqs), K (f16):    0.84 MiB, V (f16):    0.84 MiB
sched_reserve: reserving ...
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
sched_reserve: resolving fused Gated Delta Net support:
sched_reserve: Flash Attention was auto, set to enabled
sched_reserve: resolving fused Gated Delta Net support:
sched_reserve: Flash Attention was auto, set to enabled
sched_reserve: resolving fused Gated Delta Net support:
sched_reserve: fused Gated Delta Net (autoregressive) enabled
sched_reserve: fused Gated Delta Net (autoregressive) enabled
sched_reserve: fused Gated Delta Net (autoregressive) enabled
sched_reserve: fused Gated Delta Net (chunked) enabled
sched_reserve: fused Gated Delta Net (chunked) enabled
sched_reserve: fused Gated Delta Net (chunked) enabled
llama_kv_cache:      SYCL0 KV buffer size =     1.69 MiB
sched_reserve: Flash Attention was auto, set to enabled
sched_reserve: resolving fused Gated Delta Net support:
llama_kv_cache: size =    1.69 MiB (   256 cells,   6 layers,  1/1 seqs), K (f16):    0.84 MiB, V (f16):    0.84 MiB
sched_reserve: reserving ...
sched_reserve: fused Gated Delta Net (autoregressive) enabled
sched_reserve: Flash Attention was auto, set to enabled
sched_reserve: resolving fused Gated Delta Net support:
sched_reserve: fused Gated Delta Net (chunked) enabled
sched_reserve: fused Gated Delta Net (autoregressive) enabled
sched_reserve:        CPU compute buffer size =     4.13 MiB
sched_reserve: graph nodes  = 193
sched_reserve: graph splits = 1
sched_reserve: reserve took 0.57 ms, sched copies = 1
sched_reserve:        CPU compute buffer size =     4.13 MiB
sched_reserve: graph nodes  = 193
sched_reserve: graph splits = 1
sched_reserve: reserve took 0.58 ms, sched copies = 1
sched_reserve: fused Gated Delta Net (chunked) enabled
llama_kv_cache:      SYCL0 KV buffer size =     1.69 MiB
sched_reserve:        CPU compute buffer size =     4.13 MiB
sched_reserve: graph nodes  = 193
sched_reserve: graph splits = 1
sched_reserve: reserve took 0.57 ms, sched copies = 1
sched_reserve:        CPU compute buffer size =     4.13 MiB
sched_reserve: graph nodes  = 193
sched_reserve: graph splits = 1
sched_reserve: reserve took 0.60 ms, sched copies = 1
sched_reserve: layer 0 is assigned to device SYCL0 but the Flash Attention tensor is assigned to device CPU (usually due to missing support)
sched_reserve: Flash Attention was auto, set to disabled
sched_reserve: resolving fused Gated Delta Net support:
llama_kv_cache: size =    1.69 MiB (   256 cells,   6 layers,  1/1 seqs), K (f16):    0.84 MiB, V (f16):    0.84 MiB
sched_reserve: reserving ...
sched_reserve: fused Gated Delta Net (autoregressive) enabled
sched_reserve: fused Gated Delta Net (chunked) enabled
sched_reserve:      SYCL0 compute buffer size =     4.08 MiB
sched_reserve:  SYCL_Host compute buffer size =     0.10 MiB
sched_reserve: graph nodes  = 222
sched_reserve: graph splits = 2
sched_reserve: reserve took 1.02 ms, sched copies = 1
sched_reserve: layer 0 is assigned to device SYCL0 but the Flash Attention tensor is assigned to device CPU (usually due to missing support)
sched_reserve: Flash Attention was auto, set to disabled
sched_reserve: resolving fused Gated Delta Net support:
llama_kv_cache:      SYCL0 KV buffer size =     1.69 MiB
llama_kv_cache: size =    1.69 MiB (   256 cells,   6 layers,  1/1 seqs), K (f16):    0.84 MiB, V (f16):    0.84 MiB
sched_reserve: reserving ...
sched_reserve: fused Gated Delta Net (autoregressive) enabled
sched_reserve: fused Gated Delta Net (chunked) enabled
sched_reserve: layer 0 is assigned to device SYCL0 but the Flash Attention tensor is assigned to device CPU (usually due to missing support)
sched_reserve: Flash Attention was auto, set to disabled
sched_reserve: resolving fused Gated Delta Net support:
sched_reserve: fused Gated Delta Net (autoregressive) enabled
sched_reserve: layer 0 is assigned to device SYCL0 but the Flash Attention tensor is assigned to device CPU (usually due to missing support)
sched_reserve: Flash Attention was auto, set to disabled
sched_reserve: resolving fused Gated Delta Net support:
sched_reserve: fused Gated Delta Net (chunked) enabled
sched_reserve: fused Gated Delta Net (autoregressive) enabled
sched_reserve: fused Gated Delta Net (chunked) enabled
llama_kv_cache:      SYCL0 KV buffer size =     1.69 MiB
sched_reserve:      SYCL0 compute buffer size =     4.08 MiB
sched_reserve:  SYCL_Host compute buffer size =     0.10 MiB
sched_reserve: graph nodes  = 222
sched_reserve: graph splits = 2
sched_reserve: reserve took 1.40 ms, sched copies = 1
sched_reserve:      SYCL0 compute buffer size =     4.08 MiB
sched_reserve:  SYCL_Host compute buffer size =     0.10 MiB
sched_reserve: graph nodes  = 222
sched_reserve: graph splits = 2
sched_reserve: reserve took 1.05 ms, sched copies = 1
llama_kv_cache:      SYCL0 KV buffer size =     1.69 MiB
sched_reserve:      SYCL0 compute buffer size =     4.08 MiB
sched_reserve:  SYCL_Host compute buffer size =     0.10 MiB
sched_reserve: graph nodes  = 222
sched_reserve: graph splits = 2
sched_reserve: reserve took 1.75 ms, sched copies = 1
sched_reserve:      SYCL0 compute buffer size =     4.08 MiB
sched_reserve:  SYCL_Host compute buffer size =     0.10 MiB
sched_reserve: graph nodes  = 222
sched_reserve: graph splits = 2
sched_reserve: reserve took 1.01 ms, sched copies = 1
llama_kv_cache:      SYCL0 KV buffer size =     1.69 MiB
llama_kv_cache: size =    1.69 MiB (   256 cells,   6 layers,  1/1 seqs), K (f16):    0.84 MiB, V (f16):    0.84 MiB
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
sched_reserve: reserve took 1.36 ms, sched copies = 1
llama_kv_cache: size =    1.69 MiB (   256 cells,   6 layers,  1/1 seqs), K (f16):    0.84 MiB, V (f16):    0.84 MiB
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
sched_reserve: reserve took 0.98 ms, sched copies = 1
llama_kv_cache: size =    1.69 MiB (   256 cells,   6 layers,  1/1 seqs), K (f16):    0.84 MiB, V (f16):    0.84 MiB
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
sched_reserve: reserve took 0.91 ms, sched copies = 1
Model 2/3, Context 1/4: The meaning of life is a bit scary. Everyone in town is scared of the world and no one wants to go near it. But one day, a little boy came to the town. He was only three years old but he was very curious.
"What is that?" he asked his mom.
"That is a door," she said. "I don't have a way to open it."
The little boy was so curious that he decided to try and find the door. He found it and he tried to open it but it didn't work. He was very scared.
Just then a kind old man came

Model 2/3, Context 2/4: The meaning of life is called summer. It is a beautiful day.
John was so excited to go outside and play in the sun. He had been looking forward to it! He ran and ran until he reached the playground.
John looked around and saw a huge slide. He was so excited to go! He ran over to it and climbed up the slide. Once he was at the top he could see everything. He could see the trees, the birds and the sky. He could see the park from the top. He could see the slides and the swings and the playground.
John was so excited to see all the wonderful

Model 2/3, Context 4/4: The meaning of life is a bit different from any other little one. Today, it is a special day, but it is still very cold outside.
The doorbell rang and the door opened. The little boy was so excited to see the door! He ran to it and found that there was a big, warm fireway! He was so happy.
He jumped up and began to climb up, but soon he got very tired. He wanted to go back inside, but he wasn't done yet. He wanted to keep going, but he just had to head up.
He sat in the fireplace, and the fire was warm

Model 2/3, Context 3/4: The meaning of life is on its own and it always makes people very happy.
One day, the meaning of its life was gone. It was so sad that it decided to hide.
The other people in the city were so sad and angry that they started to hate the same thing.
Then one day, a little girl came to the city. She saw the colorful buildings, and she thought it looked like a special place. She decided to go and explore.
The people in the city were scared and tried to stop her. But it was too late! The people were so sad that their life was gone.
The little girl was

Model 1/3, Context 4/4: The meaning of life is

Model 3/3, Context 3/4: The meaning of life is

Model 1/3, Context 3/4: The meaning of life is

Model 3/3, Context 1/4: The meaning of life is


      Start 35: test-arg-parser
34/43 Test #35: test-arg-parser ...................Subprocess aborted***Exception: 539.20 sec
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
[New LWP 1003160]
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
0x00007e483f510813 in __GI___wait4 (pid=1021347, stat_loc=0x0, options=0, usage=0x0) at ../sysdeps/unix/sysv/linux/wait4.c:30
warning: 30	../sysdeps/unix/sysv/linux/wait4.c: No such file or directory
#0  0x00007e483f510813 in __GI___wait4 (pid=1021347, stat_loc=0x0, options=0, usage=0x0) at ../sysdeps/unix/sysv/linux/wait4.c:30
30	in ../sysdeps/unix/sysv/linux/wait4.c
#1  0x00007e48427641a3 in ggml_print_backtrace () from /hd1/jianyuzh/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/build-ci-release/bin/libggml-base.so.0
#2  0x00007e4842777326 in ggml_uncaught_exception() () from /hd1/jianyuzh/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/build-ci-release/bin/libggml-base.so.0
#3  0x00007e483f8bb0da in ?? () from /lib/x86_64-linux-gnu/libstdc++.so.6
#4  0x00007e483f8a5a55 in std::terminate() () from /lib/x86_64-linux-gnu/libstdc++.so.6
#5  0x00007e483f8bb391 in __cxa_throw () from /lib/x86_64-linux-gnu/libstdc++.so.6
#6  0x00000000004d1d80 in common_remote_get_content(std::__cxx11::basic_string<char, std::char_traits<char>, std::allocator<char> > const&, common_remote_params const&) ()
#7  0x0000000000429535 in main ()
[Inferior 1 (process 1003158) detached]
terminate called after throwing an instance of 'std::runtime_error'
  what():  error: cannot make GET request

      Start 36: test-opt
35/43 Test #36: test-opt ..........................   Passed    0.15 sec
      Start 37: test-gguf
36/43 Test #37: test-gguf .........................***Timeout 1500.11 sec

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
gguf_init_from_file_ptr: total number of elements in tensor 'my_tensor_0' with shape (8589934588, 8589934588, 8589934588, 8589934588) is >= 9223372036854775807
gguf_init_from_file_ptr: failed to read tensor info
gguf_init_from_file_ptr: tensor 'my_tensor_0' with shape (39358, 39358, 39358, 39358) has a size in bytes > 18446744073709551615
gguf_init_from_file_ptr: failed to read tensor info
gguf_init_from_file_ptr: tensor 'my_tensor_0' has invalid ggml type 41. should be in [0, 41)
gguf_init_from_file_ptr: failed to read tensor info
gguf_init_from_file_ptr: tensor 'my_tensor_0' has offset 18446744073709551615, expected 0
gguf_init_from_file_ptr: failed to read tensor data
gguf_init_from_file_ptr: duplicate tensor name 'my_tensor' for tensors 0 and 1
gguf_init_from_file_ptr: failed to read tensor info
gguf_init_from_file_ptr: alignment 13 is not a power of 2
gguf_init_from_file_ptr: tensor 'my_tensor_1' has offset 261954, expected 261984
gguf_init_from_file_ptr: failed to read tensor data
gguf_init_from_file_ptr: failed to read tensor data binary blob
gguf_init_from_file_ptr: alignment 13 is not a power of 2
gguf_init_from_file_ptr: tensor 'my_tensor_1' has offset 261954, expected 261984
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

      Start 38: test-backend-ops
37/43 Test #38: test-backend-ops ..................Subprocess aborted***Exception:   6.30 sec
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
Exception caught at file:/hd1/jianyuzh/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/ggml/src/ggml-sycl/ggml-sycl.cpp, line:4335, func:operator()
SYCL error: CHECK_TRY_ERROR((stream)->wait()): Exception caught in this line of code.
  in function ggml_backend_sycl_synchronize at /hd1/jianyuzh/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/ggml/src/ggml-sycl/ggml-sycl.cpp:4335
/hd1/jianyuzh/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/ggml/src/ggml-sycl/../ggml-sycl/common.hpp:134: SYCL error
[New LWP 1072854]
[New LWP 1072702]
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
0x000078ccb8d10813 in __GI___wait4 (pid=1073011, stat_loc=0x0, options=0, usage=0x0) at ../sysdeps/unix/sysv/linux/wait4.c:30
warning: 30	../sysdeps/unix/sysv/linux/wait4.c: No such file or directory
#0  0x000078ccb8d10813 in __GI___wait4 (pid=1073011, stat_loc=0x0, options=0, usage=0x0) at ../sysdeps/unix/sysv/linux/wait4.c:30
30	in ../sysdeps/unix/sysv/linux/wait4.c
#1  0x000078ccbbfdb1a3 in ggml_print_backtrace () from /hd1/jianyuzh/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/build-ci-release/bin/libggml-base.so.0
#2  0x000078ccbbfdb34b in ggml_abort () from /hd1/jianyuzh/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/build-ci-release/bin/libggml-base.so.0
#3  0x000078ccb94fe718 in ggml_sycl_error(char const*, char const*, char const*, int, char const*) () from /hd1/jianyuzh/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/build-ci-release/bin/libggml-sycl.so.0
#4  0x000078ccb950d868 in ggml_backend_sycl_synchronize(ggml_backend*) () from /hd1/jianyuzh/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/build-ci-release/bin/libggml-sycl.so.0
#5  0x000078ccbbffa8ca in ggml_backend_compare_graph_backend () from /hd1/jianyuzh/llama.cpp/llama.cpp_ci/ggerganov-llama.cpp/build-ci-release/bin/libggml-base.so.0
#6  0x00000000004d95f7 in test_case::eval(ggml_backend*, ggml_backend*, char const*, printer*) ()
#7  0x000000000041669e in main ()
[Inferior 1 (process 1072700) detached]

      Start 43: test-barrier
38/43 Test #43: test-barrier ......................   Passed    0.99 sec
      Start 44: test-quantize-fns
39/43 Test #44: test-quantize-fns .................   Passed   10.35 sec
      Start 45: test-quantize-perf
40/43 Test #45: test-quantize-perf ................   Passed    0.08 sec
      Start 46: test-rope
41/43 Test #46: test-rope .........................   Passed    0.07 sec
      Start 47: test-mtmd-c-api
42/43 Test #47: test-mtmd-c-api ...................   Passed    0.04 sec
      Start 48: test-alloc
43/43 Test #48: test-alloc ........................   Passed    0.04 sec

91% tests passed, 4 tests failed out of 43

Label Time Summary:
main    = 2074.27 sec*proc (42 tests)

Total Test time (real) = 2083.31 sec

The following tests FAILED:
	 34 - test-thread-safety (SEGFAULT)
	 35 - test-arg-parser (Subprocess aborted)
	 37 - test-gguf (Timeout)
	 38 - test-backend-ops (Subprocess aborted)
Errors while running CTest

real	34m43.314s
user	11m24.592s
sys	14m17.540s
```
