# NNPapers
Summary of papers about neural networks

### Asynchronous Bidirectional Decoding for Neural Machine Translation

- Source: AAAI
- Year: 2018
- Institute: Xiamen University | Tsinghua University
- Code: https://github.com/DeepLearnXMU/ABD-NMT
- Ideas: Encoder + Backward Decoder -> Source-side hidden states + Backward target-side hidden states -> Forward Decoder

### Deliberation Networks: Sequence Generation Beyond One-Pass Decoding

- Source: NIPS
- Year: 2017
- Institute: University of Science and Technology of China | Microsoft Research
- Ideas: Encoder -> First-Pass Decoder -> Second-Pass Decoder

### Neural Text Generation in Stories Using Entity Representations as Context

- Source: NAACL
- Year: 2018
- Institute: University of Washington
- Code: https://github.com/eaclark07/engen
- Ideas: Combine three contextual information: context from current sentence, context from previous sentence and current state of mentioned entities.

### Deep Cascade Multi-task Learning for Slot Filling in Chinese E-commerce Shopping Guide Assistant

- Source: arXiv
- Year: 2018
- Institute: Alibaba | Shanghai Jiao Tong University
- Ideas: Deep Cascade Multi-task (segment tagging -> named entity tagging -> slot filling) learning model with cascade and residual connections.

### When to Finish? Optimal Beam Search for Neural Text Generation (modulo beam size)

- Source: EMNLP
- Year: 2017
- Institute: Oregon State University
- Ideas: An efficient and provably optimal beam search algorithm with bounded length reward.

### Sequential Copying Networks

- Source: AAAI
- Year: 2018
- Institute: Harbin Institute of Technology | Microsoft Research
- Ideas: Sequential Copying Network which leverages pointer networks to dynamically extract/copy spans  instead of single word from input sentence during the decoding process.

### Personalizing Dialogue Agents: I have a dog, do you have pets too?

- Source: arXiv
- Year: 2018
- Institute: Montreal Institute for Learning Algorithms | Facebook AI Research
- Code: https://github.com/facebookresearch/ParlAI/tree/master/projects/personachat
- Ideas: Collect a dataset called PERSONA-CHAT where each of the pair of speakers condition their dialogue on a given profile which each consists of at least 5 profile sentences.

### Paper Abstract Writing through Editing Mechanism

- Source: ACL
- Year: 2018
- Institute: Rensselaer Polytechnic Institute | University of Southern California
- Code: https://github.com/EagleW/Writing-editing-Network
- Ideas: Design a novel Writing-Editing Network that can attend to both the title and the previously generated abstract drafts and then iteratively revise and polish the abstract.

### Dialog Generation Using Multi-turn Reasoning Neural Networks

- Source: NAACL
- Year: 2018
- Institute: Microsoft Development Co., Ltd. | Nara Institute of Science and Technology
- Ideas: Propose a generalizable dialog generation approach that adapts multi-turn reasoning, to generate responses by taking current conversation sessioncontext as a "document" and current query as a "question".

### Zero-Shot Dialog Generation with Cross-Domain Latent Actions、

- Source: SIGDIAL
- Year: 2018
- Institute: Carnegie Mellon University
- Code: https://github.com/snakeztc/NeuralDialog-ZSDG
- Ideas: Propose an end-to-end generative dialog system which can generalize to new domains with only domain descriptions and no training dialogs, by leveraging Action Matching  learns a cross-domain embedding space that models the semantics of dialog responses.