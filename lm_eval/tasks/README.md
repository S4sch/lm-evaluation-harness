# v1.0 Tasks
This list keeps track of which tasks' implementations have been ported to YAML / v2.0 of the Eval Harness.

Boxes should be checked iff tasks are implemented in the refactor and tested for regression. Tasks should be struck through if checked *against original introducing paper* implementation or popularizing implementation. (WIP) Denotes that there exists a PR or person working on this task already.

- [ ] Glue (Lintang)
- [x] SuperGlue
- [ ] CoQA (Lintang)
- [ ] DROP (Lintang)
- [x] ~~Lambada~~
- [x] Lambada (Cloze variants)
- [x] ~~Lambada (Multilingual)~~
- [x] Wikitext
- [x] PiQA
- [x] PROST
- [ ] MCTACO (Lintang)
- [x] Pubmed QA
- [x] SciQ
- [ ] QASPER
- [x] QA4MRE
- [ ] TriviaQA (Lintang)
- [x] AI2 ARC
- [x] LogiQA
- [x] HellaSwag
- [x] SWAG
- [x] OpenBookQA
- [ ] SQuADv2 (Lintang)
- [x] RACE
- [x] HeadQA
- [x] MathQA
- [x] WebQs
- [ ] WSC273 (Lintang)
- [x] Winogrande
- [x] ANLI
- [x] Hendrycks Ethics (missing some tasks/metrics, see PR 660: <https://github.com/EleutherAI/lm-evaluation-harness/pull/660> for more info)
- [x] TruthfulQA (mc1) (Lintang)
- [ ] TruthfulQA (mc2) (Lintang)
- [ ] TruthfulQA (gen) (Lintang)
- [ ] MuTual
- [ ] Hendrycks Math (Hailey)
- [ ] Asdiv
- [ ] GSM8k
- [x] Arithmetic
- [ ] MMMLU (Hailey)
- [ ] Translation (WMT) suite (Hailey)
- [x] Unscramble
- [x] ~~Pile (perplexity)~~
- [ ] BLiMP (Lintang)
- [x] ToxiGen
- [ ] StoryCloze (Lintang)
- [ ] NaturalQs (Hailey)
- [x] CrowS-Pairs
- [x] XCopa
- [ ] BIG-Bench (Hailey)
- [ ] XStoryCloze (Lintang)
- [x] XWinograd
- [ ] PAWS-X (Lintang)
- [ ] XNLI (Lintang)
- [ ] MGSM (Lintang)
- [ ] SCROLLS
- [x] Babi

# Novel Tasks
Tasks added in the revamped harness that were not previously available. Again, a strikethrough denotes checking performed *against the original task's implementation or published results introducing the task*.

# Task Wishlist

- [ ] TheoremQA
- [ ] Theorem Proving evaluations
- [ ] Chain of Thought
- [ ] Self-consistency ; Least-to-Most prompting, etc.
- [ ] Summarization Tasks
- [ ] Anthropic Model-Written Evals