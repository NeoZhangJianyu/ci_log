### ctest_release

Runs ctest in release mode
- status: 8
```
+ ctest --output-on-failure -L main
Test project /home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/build-ci-release
      Start  1: test-tokenizer-0-bert-bge
 1/41 Test  #1: test-tokenizer-0-bert-bge .........   Passed    0.33 sec
      Start  2: test-tokenizer-0-command-r
 2/41 Test  #2: test-tokenizer-0-command-r ........   Passed    0.39 sec
      Start  3: test-tokenizer-0-deepseek-coder
 3/41 Test  #3: test-tokenizer-0-deepseek-coder ...   Passed    0.10 sec
      Start  4: test-tokenizer-0-deepseek-llm
 4/41 Test  #4: test-tokenizer-0-deepseek-llm .....   Passed    0.17 sec
      Start  5: test-tokenizer-0-falcon
 5/41 Test  #5: test-tokenizer-0-falcon ...........   Passed    0.13 sec
      Start  6: test-tokenizer-0-gpt-2
 6/41 Test  #6: test-tokenizer-0-gpt-2 ............   Passed    0.12 sec
      Start  7: test-tokenizer-0-llama-bpe
 7/41 Test  #7: test-tokenizer-0-llama-bpe ........   Passed    0.26 sec
      Start  8: test-tokenizer-0-llama-spm
 8/41 Test  #8: test-tokenizer-0-llama-spm ........   Passed    0.09 sec
      Start  9: test-tokenizer-0-mpt
 9/41 Test  #9: test-tokenizer-0-mpt ..............   Passed    0.11 sec
      Start 10: test-tokenizer-0-phi-3
10/41 Test #10: test-tokenizer-0-phi-3 ............   Passed    0.09 sec
      Start 11: test-tokenizer-0-qwen2
11/41 Test #11: test-tokenizer-0-qwen2 ............   Passed    0.23 sec
      Start 12: test-tokenizer-0-refact
12/41 Test #12: test-tokenizer-0-refact ...........   Passed    0.11 sec
      Start 13: test-tokenizer-0-starcoder
13/41 Test #13: test-tokenizer-0-starcoder ........   Passed    0.12 sec
      Start 14: test-tokenizers-ggml-vocabs
14/41 Test #14: test-tokenizers-ggml-vocabs .......***Failed    2.30 sec
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
15/41 Test #15: test-sampling .....................   Passed    0.84 sec
      Start 16: test-grammar-parser
16/41 Test #16: test-grammar-parser ...............   Passed    0.04 sec
      Start 17: test-grammar-integration
17/41 Test #17: test-grammar-integration ..........   Passed    0.04 sec
      Start 18: test-llama-grammar
18/41 Test #18: test-llama-grammar ................   Passed    0.04 sec
      Start 19: test-chat
19/41 Test #19: test-chat .........................   Passed    0.66 sec
      Start 20: test-json-schema-to-grammar
20/41 Test #20: test-json-schema-to-grammar .......   Passed    1.96 sec
      Start 21: test-tokenizer-1-llama-spm
21/41 Test #21: test-tokenizer-1-llama-spm ........   Passed    0.18 sec
      Start 22: test-chat-parser
22/41 Test #22: test-chat-parser ..................   Passed    0.04 sec
      Start 23: test-chat-peg-parser
23/41 Test #23: test-chat-peg-parser ..............   Passed    0.08 sec
      Start 24: test-chat-template
24/41 Test #24: test-chat-template ................   Passed    0.06 sec
      Start 25: test-jinja
25/41 Test #25: test-jinja ........................   Passed    0.10 sec
      Start 27: test-json-partial
26/41 Test #27: test-json-partial .................   Passed    0.04 sec
      Start 28: test-log
27/41 Test #28: test-log ..........................   Passed    0.06 sec
      Start 29: test-peg-parser
28/41 Test #29: test-peg-parser ...................   Passed    0.04 sec
      Start 30: test-regex-partial
29/41 Test #30: test-regex-partial ................   Passed    0.04 sec
      Start 31: test-download-model
30/41 Test #31: test-download-model ...............   Passed   16.16 sec
      Start 32: test-thread-safety
31/41 Test #32: test-thread-safety ................Subprocess aborted***Exception:  11.03 sec
build: 7878 (d284baf1b) with GNU 13.3.0 for Linux x86_64
system_info: n_threads = 2 (n_threads_batch = 2) / 16 | CPU : SSE3 = 1 | SSSE3 = 1 | AVX = 1 | AVX_VNNI = 1 | AVX2 = 1 | F16C = 1 | FMA = 1 | BMI2 = 1 | LLAMAFILE = 1 | OPENMP = 1 | REPACK = 1 | 
llama_model_load_from_file_impl: using device SYCL0 (Intel(R) Arc(TM) A770 Graphics) (unknown id) - 15473 MiB free
llama_model_loader: loaded meta data with 20 key-value pairs and 57 tensors from /home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/build-ci-release/tinyllamas/stories15M-q4_0.gguf (version GGUF V3 (latest))
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
load_tensors:   CPU_Mapped model buffer size =     4.94 MiB
load_tensors:        SYCL0 model buffer size =    12.56 MiB
.....................
llama_model_loader: loaded meta data with 20 key-value pairs and 57 tensors from /home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/build-ci-release/tinyllamas/stories15M-q4_0.gguf (version GGUF V3 (latest))
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
llama_model_load_from_file_impl: using device SYCL0 (Intel(R) Arc(TM) A770 Graphics) (unknown id) - 15473 MiB free
llama_model_loader: loaded meta data with 20 key-value pairs and 57 tensors from /home/zjy/ws/jenkins/workspace/ci-arc770/ggerganov-llama.cpp/build-ci-release/tinyllamas/stories15M-q4_0.gguf (version GGUF V3 (latest))
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
Creating context 4/4 for model 1/3
|  |                   |                                       |       |Max    |        |Max  |Global |                     |
|  |                   |                                       |       |compute|Max work|sub  |mem    |                     |
|ID|        Device Type|                                   Name|Version|units  |group   |group|size   |       Driver version|
|--|-------------------|---------------------------------------|-------|-------|--------|-----|-------|---------------------|
llama_context: constructing llama_context
llama_context: n_seq_max     = 1
llama_context: n_ctx         = 256
llama_context: n_ctx_seq     = 256
llama_context: n_batch       = 256
Creating context 2/4 for model 1/3
Creating context 1/4 for model 2/3
llama_context: n_ubatch      = 32
llama_context: causal_attn   = 1
llama_context: flash_attn    = auto
llama_context: kv_unified    = false
llama_context: freq_base     = 10000.0
llama_context: freq_scale    = 1
llama_context: n_ctx_seq (256) > n_ctx_train (128) -- possible training context overflow
Creating context 2/4 for model 2/3
Creating context 3/4 for model 1/3
| 0| [level_zero:gpu:0]|                Intel Arc A770 Graphics|  12.55|    512|    1024|   32| 16225M|         1.3.29735+27|
llama_context:  SYCL_Host  output buffer size =     0.12 MiB
SYCL Optimization Feature:
|ID|        Device Type|Reorder|
|--|-------------------|-------|
Creating context 3/4 for model 2/3
| 0| [level_zero:gpu:0]|      Y|
Creating context 4/4 for model 2/3
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
llama_context: constructing llama_context
llama_context: n_seq_max     = 1
llama_context: n_ctx         = 256
llama_context: n_ctx_seq     = 256
llama_context: n_batch       = 256
llama_context: n_ubatch      = 32
llama_context: causal_attn   = 1
llama_context: flash_attn    = auto
llama_context: kv_unified    = false
llama_context:        CPU  output buffer size =     0.12 MiB
llama_context: constructing llama_context
llama_context: n_seq_max     = 1
llama_context: n_ctx         = 256
llama_context: n_ctx_seq     = 256
llama_context: n_batch       = 256
llama_context: n_ubatch      = 32
llama_context: causal_attn   = 1
llama_context: flash_attn    = auto
llama_context: freq_base     = 10000.0
llama_context: kv_unified    = false
llama_context: freq_scale    = 1
llama_context: n_ctx_seq (256) > n_ctx_train (128) -- possible training context overflow
llama_context:        CPU  output buffer size =     0.12 MiB
llama_context: freq_base     = 10000.0
llama_context: freq_scale    = 1
llama_context: n_ctx_seq (256) > n_ctx_train (128) -- possible training context overflow
llama_context:  SYCL_Host  output buffer size =     0.12 MiB
llama_context:  SYCL_Host  output buffer size =     0.12 MiB
llama_kv_cache:        CPU KV buffer size =     1.69 MiB
llama_kv_cache:        CPU KV buffer size =     1.69 MiB
Creating context 1/4 for model 3/3
llama_context: constructing llama_context
llama_context: constructing llama_context
llama_context: n_seq_max     = 1
llama_context: n_ctx         = 256
llama_context: n_ctx_seq     = 256
llama_context: n_seq_max     = 1
llama_context: n_batch       = 256
llama_context: n_ctx         = 256
llama_context: n_ubatch      = 32
llama_context: n_ctx_seq     = 256
llama_context: n_batch       = 256
llama_context: causal_attn   = 1
llama_context: n_ubatch      = 32
llama_context: flash_attn    = auto
llama_context: causal_attn   = 1
llama_context: flash_attn    = auto
llama_context: kv_unified    = false
Creating context 2/4 for model 3/3
llama_context: kv_unified    = false
llama_context: freq_base     = 10000.0
llama_context: freq_base     = 10000.0
llama_context: freq_scale    = 1
llama_context: n_ctx_seq (256) > n_ctx_train (128) -- possible training context overflow
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
llama_kv_cache:      SYCL0 KV buffer size =     1.69 MiB
llama_context:        CPU  output buffer size =     0.12 MiB
llama_context: freq_base     = 10000.0
llama_context: freq_scale    = 1
llama_context: n_ctx_seq (256) > n_ctx_train (128) -- possible training context overflow
llama_context:        CPU  output buffer size =     0.12 MiB
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
llama_kv_cache:      SYCL0 KV buffer size =     1.69 MiB
llama_context: freq_base     = 10000.0
llama_context: freq_scale    = 1
llama_context: n_ctx_seq (256) > n_ctx_train (128) -- possible training context overflow
Creating context 3/4 for model 3/3
llama_context:  SYCL_Host  output buffer size =     0.12 MiB
llama_kv_cache:        CPU KV buffer size =     1.69 MiB
Creating context 4/4 for model 3/3
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
llama_kv_cache:        CPU KV buffer size =     1.69 MiB
llama_context:  SYCL_Host  output buffer size =     0.12 MiB
llama_context:  SYCL_Host  output buffer size =     0.12 MiB
llama_kv_cache:      SYCL0 KV buffer size =     1.69 MiB
llama_kv_cache:      SYCL0 KV buffer size =     1.69 MiB
llama_kv_cache: size =    1.69 MiB (   256 cells,   6 layers,  1/1 seqs), K (f16):    0.84 MiB, V (f16):    0.84 MiB
sched_reserve: reserving ...
llama_kv_cache:      SYCL0 KV buffer size =     1.69 MiB
llama_kv_cache: size =    1.69 MiB (   256 cells,   6 layers,  1/1 seqs), K (f16):    0.84 MiB, V (f16):    0.84 MiB
llama_kv_cache:      SYCL0 KV buffer size =     1.69 MiB
sched_reserve: reserving ...
llama_kv_cache:      SYCL0 KV buffer size =     1.69 MiB
llama_kv_cache:      SYCL0 KV buffer size =     1.69 MiB
llama_kv_cache: size =    1.69 MiB (   256 cells,   6 layers,  1/1 seqs), K (f16):    0.84 MiB, V (f16):    0.84 MiB
llama_kv_cache: size =    1.69 MiB (   256 cells,   6 layers,  1/1 seqs), K (f16):    0.84 MiB, V (f16):    0.84 MiB
sched_reserve: reserving ...
sched_reserve: reserving ...
llama_kv_cache: size =    1.69 MiB (   256 cells,   6 layers,  1/1 seqs), K (f16):    0.84 MiB, V (f16):    0.84 MiB
sched_reserve: reserving ...
llama_kv_cache: size =    1.69 MiB (   256 cells,   6 layers,  1/1 seqs), K (f16):    0.84 MiB, V (f16):    0.84 MiB
sched_reserve: reserving ...
llama_kv_cache: size =    1.69 MiB (   256 cells,   6 layers,  1/1 seqs), K (f16):    0.84 MiB, V (f16):    0.84 MiB
sched_reserve: reserving ...
llama_kv_cache: size =    1.69 MiB (   256 cells,   6 layers,  1/1 seqs), K (f16):    0.84 MiB, V (f16):    0.84 MiB
sched_reserve: reserving ...
llama_kv_cache: size =    1.69 MiB (   256 cells,   6 layers,  1/1 seqs), K (f16):    0.84 MiB, V (f16):    0.84 MiB
llama_kv_cache: size =    1.69 MiB (   256 cells,   6 layers,  1/1 seqs), K (f16):    0.84 MiB, V (f16):    0.84 MiB
sched_reserve: reserving ...
sched_reserve: reserving ...
sched_reserve: layer 0 is assigned to device SYCL0 but the Flash Attention tensor is assigned to device CPU (usually due to missing support)
sched_reserve: Flash Attention was auto, set to disabled
sched_reserve: layer 0 is assigned to device SYCL0 but the Flash Attention tensor is assigned to device CPU (usually due to missing support)
sched_reserve: Flash Attention was auto, set to disabled
sched_reserve: Flash Attention was auto, set to enabled
sched_reserve: layer 0 is assigned to device SYCL0 but the Flash Attention tensor is assigned to device CPU (usually due to missing support)
sched_reserve: Flash Attention was auto, set to disabled
llama_kv_cache: size =    1.69 MiB (   256 cells,   6 layers,  1/1 seqs), K (f16):    0.84 MiB, V (f16):    0.84 MiB
sched_reserve: reserving ...
llama_kv_cache: size =    1.69 MiB (   256 cells,   6 layers,  1/1 seqs), K (f16):    0.84 MiB, V (f16):    0.84 MiB
sched_reserve: reserving ...
sched_reserve: Flash Attention was auto, set to enabled
sched_reserve: Flash Attention was auto, set to enabled
sched_reserve: layer 0 is assigned to device SYCL0 but the Flash Attention tensor is assigned to device CPU (usually due to missing support)
sched_reserve: Flash Attention was auto, set to disabled
sched_reserve: Flash Attention was auto, set to enabled
sched_reserve:        CPU compute buffer size =     4.13 MiB
sched_reserve: graph nodes  = 193
sched_reserve: graph splits = 1
sched_reserve: reserve took 1.18 ms, sched copies = 1
sched_reserve: layer 0 is assigned to device SYCL0 but the Flash Attention tensor is assigned to device CPU (usually due to missing support)
sched_reserve: Flash Attention was auto, set to disabled
sched_reserve:        CPU compute buffer size =     4.13 MiB
sched_reserve: graph nodes  = 193
sched_reserve: graph splits = 1
sched_reserve: reserve took 1.06 ms, sched copies = 1
sched_reserve:      SYCL0 compute buffer size =     4.08 MiB
sched_reserve:  SYCL_Host compute buffer size =     0.10 MiB
sched_reserve: graph nodes  = 222
sched_reserve: graph splits = 2
sched_reserve: reserve took 1.69 ms, sched copies = 1
sched_reserve:      SYCL0 compute buffer size =     4.08 MiB
sched_reserve:  SYCL_Host compute buffer size =     0.10 MiB
sched_reserve: graph nodes  = 222
sched_reserve: graph splits = 2
sched_reserve: reserve took 1.31 ms, sched copies = 1
sched_reserve:        CPU compute buffer size =     4.13 MiB
sched_reserve: graph nodes  = 193
sched_reserve: graph splits = 1
sched_reserve: reserve took 1.35 ms, sched copies = 1
sched_reserve:      SYCL0 compute buffer size =     4.08 MiB
sched_reserve:  SYCL_Host compute buffer size =     0.10 MiB
sched_reserve: graph nodes  = 222
sched_reserve: graph splits = 2
sched_reserve: reserve took 1.69 ms, sched copies = 1
sched_reserve: layer 0 is assigned to device SYCL0 but the Flash Attention tensor is assigned to device CPU (usually due to missing support)
sched_reserve: Flash Attention was auto, set to disabled
sched_reserve:        CPU compute buffer size =     4.13 MiB
sched_reserve: graph nodes  = 193
sched_reserve: graph splits = 1
sched_reserve: reserve took 1.39 ms, sched copies = 1
sched_reserve: layer 0 is assigned to device SYCL0 but the Flash Attention tensor is assigned to device CPU (usually due to missing support)
sched_reserve: Flash Attention was auto, set to disabled
sched_reserve: layer 0 is assigned to device SYCL0 but the Flash Attention tensor is assigned to device CPU (usually due to missing support)
sched_reserve: Flash Attention was auto, set to disabled
sched_reserve:      SYCL0 compute buffer size =     4.08 MiB
sched_reserve:  SYCL_Host compute buffer size =     0.10 MiB
sched_reserve: graph nodes  = 222
sched_reserve: graph splits = 2
sched_reserve: reserve took 1.14 ms, sched copies = 1
sched_reserve:      SYCL0 compute buffer size =     4.08 MiB
sched_reserve:  SYCL_Host compute buffer size =     0.10 MiB
sched_reserve: graph nodes  = 222
sched_reserve: graph splits = 2
sched_reserve: reserve took 1.73 ms, sched copies = 1
sched_reserve:      SYCL0 compute buffer size =     4.08 MiB
sched_reserve:  SYCL_Host compute buffer size =     0.10 MiB
sched_reserve: graph nodes  = 222
sched_reserve: graph splits = 2
sched_reserve: reserve took 2.85 ms, sched copies = 1
sched_reserve:      SYCL0 compute buffer size =     4.08 MiB
sched_reserve:  SYCL_Host compute buffer size =     0.10 MiB
sched_reserve: graph nodes  = 222
sched_reserve:      SYCL0 compute buffer size =     4.08 MiB
sched_reserve: graph splits = 2
sched_reserve:  SYCL_Host compute buffer size =     0.10 MiB
sched_reserve: reserve took 2.72 ms, sched copies = 1
sched_reserve: graph nodes  = 222
sched_reserve: graph splits = 2
sched_reserve: reserve took 2.66 ms, sched copies = 1
Model 2/3, Context 4/4: The meaning of life is on the ground that is just a few moments to begin. But this is the one which is the best thing that is available to you.
One day, the little girl was in the park. She was so excited because she was wearing a bright yellow coat. She looked around and saw a big tree with a big yellow bird in the branches.
The bird was sitting on the same branch she had seen earlier. She looked so close to it and saw the yellow bird. She was very excited and ran over to it. 
The bird flew down and landed on the ground. The little girl went to sit next

Model 2/3, Context 2/4: The meaning of life is a brilliant day! It is the only way to become something special.
Mum has told him it is time to go to the park. She said it will make him so happy!
On the way to the park, Mum pointed at a big tree. It was a bright yellow and orange! She pointed at it and said "Look at that tree! It's so pretty!"
Mum called the park ranger and told him to come over. He walked up to the big, orange tree and said "Hello! Do you like it?"
The park ranger laughed and said "Yes! It's

Model 2/3, Context 3/4: The meaning of life is about the importance of being modest, humble. But one day, a storm came and the rain made the ground so muddy and slippery. It was so strong that the muddy ground was sunk to the bottom of a hill. It was too heavy for the little girl.
The little girl was so scared and she ran inside the house. She was very sad because she had missed the safety of her home.
She had never felt so alone and sad. She was never able to share her stories with anyone, but it was too late. The ground was too sour and she could not understand why

Model 2/3, Context 1/4: The meaning of life is on a modern school. The school has lots of books and computers. In the school there was a classroom with lots of children.
The children were playing games and having lots of fun. Then it started to get dark outside. The teacher said, "We are all very cold. Let's go home."
So the children followed the teacher. But, suddenly the teacher started to sneeze. He sneezed and sneezed until he couldn't sneeze anymore.
The children were sad and scared. They went to their homes and stayed there for the night. 


Model 1/3, Context 4/4: The meaning of life is

Model 3/3, Context 1/4: The meaning of life is

Model 1/3, Context 2/4: The meaning of life is

Model 3/3, Context 3/4: The meaning of life is

corrupted double-linked list

      Start 33: test-arg-parser
32/41 Test #33: test-arg-parser ...................   Passed    0.66 sec
      Start 34: test-opt
33/41 Test #34: test-opt ..........................   Passed    0.17 sec
      Start 35: test-gguf
34/41 Test #35: test-gguf .........................   Passed    0.34 sec
      Start 36: test-backend-ops
35/41 Test #36: test-backend-ops ..................   Passed  112.30 sec
      Start 41: test-barrier
36/41 Test #41: test-barrier ......................   Passed    1.14 sec
      Start 42: test-quantize-fns
37/41 Test #42: test-quantize-fns .................   Passed   12.12 sec
      Start 43: test-quantize-perf
38/41 Test #43: test-quantize-perf ................   Passed    0.09 sec
      Start 44: test-rope
39/41 Test #44: test-rope .........................   Passed    0.09 sec
      Start 45: test-m.html-c-api
40/41 Test #45: test-m.html-c-api ...................   Passed    0.05 sec
      Start 46: test-alloc
41/41 Test #46: test-alloc ........................   Passed    0.04 sec

95% tests passed, 2 tests failed out of 41

Label Time Summary:
main    = 146.79 sec*proc (40 tests)

Total Test time (real) = 162.98 sec

The following tests FAILED:
	 14 - test-tokenizers-ggml-vocabs (Failed)
	 32 - test-thread-safety (Subprocess aborted)
Errors while running CTest

real	2m43.016s
user	3m20.985s
sys	1m8.564s
```
