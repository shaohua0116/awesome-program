# Awesome Program
## Description
This repo contains a curated list of papers related to <b>program synthesis</b>, <b>program induction</b>, <b>program execution</b>, <b>program and code repair</b>, and <b>programmatic reinforcement learning</b>. This list is maintained by [Shao-Hua Sun](https://shaohua0116.github.io/). 

You are more than welcome to contribute by suggesting changes to make the list more comprehensive or correcting errors. Please simply create a pull request or contact me via email. If you find this repo useful for your research, please consider [citing](#bibtex) this list.
## Content
- [Program Synthesis](#synthesis)
- [Program Induction](#induction)
- [Program Execution](#execution)
- [Program and Code Repair](#repair)
- [Programmatic Reinforcement Learning](#policy)
## <a name="synthesis"></a>Program Synthesis
The goal of program synthesis is to construct a human-readable program that satisﬁes task specifications represented as input/output pairs, demonstrations, natural language instructions, etc. Recent works also explore representing images and 3D shapes using programs, allowing applications such as editing, scene understanding, analogy-making, reverse engineering, etc.
- 31 papers

| Paper Title | Conference | Year | Link |
| ---- | ---- | ---- | ---- |
|Latent Attention For If-Then Program Synthesis|NIPS|2016|[link](https://proceedings.neurips.cc/paper/2016/hash/716e1b8c6cd17b771da77391355749f3-Abstract.html)|
|Neural Scene De-rendering|CVPR|2017|[link](http://nsd.csail.mit.edu/)|
|DeepCoder: Learning to Write Programs|ICLR|2017|[link](https://arxiv.org/abs/1611.01989)|
|Neuro-Symbolic Program Synthesis|ICLR|2017|[link](https://openreview.net/forum?id=rJ0JwFcex)|
|RobustFill: Neural Program Learning under Noisy I/O|ICML|2017|[link](https://arxiv.org/abs/1703.07469)|
|Differentiable Programs with Neural Libraries|ICML|2017|[link](https://arxiv.org/abs/1611.02109)|
|pix2code: Generating Code from a Graphical User Interface Screenshot|arXiv|2017|[link](https://arxiv.org/abs/1705.07962)|
|Seq2SQL: Generating Structured Queries from Natural Language using Reinforcement Learning|arXiv|2017|[link](https://arxiv.org/pdf/1709.00103.pdf)|
|NL2Bash: A Corpus and Semantic Parser for Natural Language Interface to the Linux Operating System|ELRA|2018|[link](https://www.aclweb.org/anthology/L18-1491.pdf)|
|Leveraging Grammar and Reinforcement Learning for Neural Program Synthesis|ICLR|2018|[link](https://arxiv.org/abs/1805.04276)|
|Towards Synthesizing Complex Programs from Input-Output Examples|ICLR|2018|[link](https://arxiv.org/abs/1706.01284)|
|Neural Program Synthesis from Diverse Demonstration Videos|ICML|2018|[link](http://proceedings.mlr.press/v80/sun18a.html)|
|Improving Neural Program Synthesis with Inferred Execution Traces|NeurIPS|2018|[link](https://proceedings.neurips.cc/paper/2018/hash/7776e88b0c189539098176589250bcba-Abstract.html)|
|Automatic Program Synthesis of Long Programs with a Learned Garbage Collector|NeurIPS|2018|[link](https://arxiv.org/abs/1809.04682)|
|Neural Program Synthesis with Priority Queue Training|arXiv|2018|[link](https://arxiv.org/abs/1801.03526)|
|Recent Advances in Neural Program Synthesis|arXiv|2018|[link](https://arxiv.org/abs/1802.02353)|
|Watch, Reason and Code- Learning to Represent Videos Using Program|ACM Multimedia|2019|[link](https://digital.library.adelaide.edu.au/dspace/bitstream/2440/129989/2/hdl_129989.pdf)|
|Program-Guided Image Manipulators|ICCV|2019|[link](https://arxiv.org/abs/1909.02116)|
|Execution-Guided Neural Program Synthesis|ICLR|2019|[link](https://openreview.net/forum?id=H1gfOiAqYm)|
|Learning to Describe Scenes with Programs|ICLR|2019|[link](https://openreview.net/forum?id=SyNPk2R9K7)|
|Learning to Infer and Execute 3D Shape Programs|ICLR|2019|[link](https://openreview.net/forum?id=rylNH20qFQ)|
|Synthetic Datasets for Neural Program Synthesis|ICLR|2019|[link](https://openreview.net/forum?id=ryeOSnAqYm)|
|Ain’t Nobody Got Time For Coding: Structure-Aware Program Synthesis From Natural Language|arXiv|2019|[link](https://arxiv.org/pdf/1810.09717.pdf)|
|Learning Compositional Rules via Neural Program Synthesis|NeurIPS|2020|[link](https://arxiv.org/abs/2003.05562)|
|Synthesize, Execute and Debug: Learning to Repair for Neural Program Synthesis|NeurIPS|2020|[link](https://arxiv.org/abs/2007.08095)|
|PLANS: Neuro-Symbolic Program Learning from Videos|NeurIPS|2020|[link](https://proceedings.neurips.cc/paper/2020/hash/fe131d7f5a6b38b23cc967316c13dae2-Abstract.html)|
|Neural Program Synthesis with a Differentiable Fixer|arXiv|2020|[link](https://arxiv.org/abs/2006.10924)|
|Learning to Infer Shape Programs Using Self Training|arXiv|2020|[link](https://arxiv.org/abs/2011.13045)|
|SpreadsheetCoder: Formula Prediction from Semi-structured Context|ICML|2021|[link](https://arxiv.org/abs/2106.15339)|
|Latent Execution for Neural Program Synthesis Beyond Domain-Specific Languages|arXiv|2021|[link](https://arxiv.org/abs/2107.00101)|
|Learning to Combine Per-Example Solutions for Neural Program Synthesis|arXiv|2021|[link](https://arxiv.org/abs/2106.07175)|
## <a name="induction"></a>Program Induction
Unlike program synthesis works that are designed to explicitly synthesize programs, program induction methods aim to implicitly induce the underlying programs to mimic the desired behaviors demonstrated in task specifications (e.g. execution traces) to solve algorithmic tasks such as digit addition and string transformations and achieve better generalization.
- 18 papers

| Paper Title | Conference | Year | Link |
| ---- | ---- | ---- | ---- |
|Neural Turing Machines|arXiv|2014|[link](https://arxiv.org/abs/1410.5401)|
|Learning Simple Algorithms from Examples|arXiv|2015|[link](https://arxiv.org/abs/1511.07275)|
|Reinforcement Learning Neural Turing Machines-Revised|arXiv|2015|[link](https://arxiv.org/abs/1505.00521)|
|Neural GPUs Learn Algorithms|arXiv|2015|[link](https://arxiv.org/abs/1511.08228)|
|Neural Random-Access Machines|arXiv|2015|[link](https://arxiv.org/abs/1511.06392)|
|Neural Programmer-Interpreters|ICLR|2016|[link](https://arxiv.org/abs/1511.06279)|
|Extensions and Limitations of the Neural GPU|arXiv|2016|[link](https://arxiv.org/abs/1611.00736)|
|Neural Program Lattices|ICLR|2017|[link](https://openreview.net/forum?id=HJjiFK5gx)|
|Making Neural Programming Architectures Generalize via Recursion|ICLR|2017|[link](https://openreview.net/forum?id=BkbY4psgg)|
|Neural Program Meta-Induction|NIPS|2017|[link](https://arxiv.org/abs/1710.04157)|
|Improving the Universality and Learnability of Neural Programmer-Interpreters with Combinator Abstraction |ICLR|2018|[link](https://openreview.net/forum?id=rJlMAAeC-)|
|Neural Task Programming: Learning to Generalize Across Hierarchical Tasks|ICRA|2018|[link](https://arxiv.org/abs/1710.01813)|
|Memory Augmented Policy Optimization for Program Synthesis with Generalization|NeurIPS|2018|[link](https://arxiv.org/abs/1807.02322)|
|Neural Task Graphs: Generalizing to Unseen Tasks from a Single Video Demonstration|CVPR|2019|[link](https://arxiv.org/abs/1807.03480)|
|Learning Compositional Neural Programs with Recursive Tree Search and Planning|NeurIPS|2019|[link](https://arxiv.org/abs/1905.12941)|
|Learning Algorithmic Solutions to Symbolic Planning Tasks with a Neural Computer Architecture|arXiv|2019|[link](https://arxiv.org/abs/1911.00926)|
|DreamCoder: Growing generalizable, interpretable knowledge with wake-sleep Bayesian program learning|arXiv|2020|[link](https://arxiv.org/abs/2006.08381)|
|Strong Generalization and Efficiency in Neural Programs|arXiv|2020|[link](https://arxiv.org/abs/2007.03629)|
## <a name="execution"></a>Program Execution
Program execution works explore domains such as utilizing programs as instructions to guide reinforcement learning agents and improving program synthesis performance by executing partially generated programs.
- 9 papers

| Paper Title | Conference | Year | Link |
| ---- | ---- | ---- | ---- |
|Programmable Agents|NIPS|2017|[link](https://arxiv.org/abs/1706.06383)|
|Write, Execute, Assess Program Synthesis with a REPL|NeurIPS|2019|[link](https://arxiv.org/abs/1906.04604)|
|A Composable Specification Language for Reinforcement Learning Tasks|NeurIPS|2019|[link](https://arxiv.org/abs/2008.09293)|
|Program Guided Agent|ICLR|2020|[link](https://openreview.net/forum?id=BkxUvnEYDH)|
|Neural Execution Engines- Learning to Execute Subroutines|NeurIPS|2020|[link](https://arxiv.org/abs/2006.08084)|
|Learning to Execute Programs with Instruction Pointer Attention Graph Neural Networks|NeurIPS|2020|[link](https://arxiv.org/abs/2010.12621)|
|Reinforcement Learning of Implicit and Explicit Control Flow in Instructions|ICML|2021|[link](https://arxiv.org/abs/2102.13195)|
|Latent Execution for Neural Program Synthesis Beyond Domain-Specific Languages|arXiv|2021|[link](https://arxiv.org/abs/2107.00101)|
|Program Synthesis Guided Reinforcement Learning|arXiv|2021|[link](https://arxiv.org/abs/2102.11137)|
## <a name="repair"></a>Program and Code Repair
Program and code repair methods aim to automatically identify bugs in code and potentially propose solutions to fix them to alleviate the burden of programmers.
- 11 papers

| Paper Title | Conference | Year | Link |
| ---- | ---- | ---- | ---- |
|SemFix: Program Repair via Semantic Analysis|ICSE|2013|[link](https://staff.fmi.uvt.ro/~daniela.zaharie/ma2016/projects/techniques/AutomatedProgramRepair/ProgramRepair%2BSemanticAnalysis.pdf)|
|DynaMoth: Dynamic Code Synthesis for Automatic Program Repair|AST|2016|[link](https://hal.archives-ouvertes.fr/hal-01279233/document)|
|Leveraging syntax-related code for automated program repair|ASE|2017|[link](http://cs.brown.edu/people/qxin/papers/repair_ase17_preprint.pdf)|
|Contract-Based Program Repair without the Contracts|ASE|2017|[link](http://ira.lib.polyu.edu.hk/bitstream/10397/76937/1/ASE2017_jaid.pdf)|
|Shaping program repair space with existing patches and similar code|ACM SIGSOFT|2018|[link](http://hongyujohn.github.io/Shaping.pdf)|
|LSRepair: Live Search of Fix Ingredients for Automated Program Repair|APSEC|2018|[link](https://orbilu.uni.lu/bitstream/10993/37414/1/LSRepair.pdf)|
|Automated Program Repair|CACM|2019|[link](https://par.nsf.gov/servlets/purl/10135834)|
|Sorting and Transforming Program Repair Ingredients via Deep Learning Code Similarities|SANER|2019|[link](https://arxiv.org/abs/1707.04742)|
|FixMiner: Mining Relevant Fix Patterns for Automated Program Repair|ESEJ|2020|[link](https://arxiv.org/abs/1810.01791)|
|Graph-based, Self-Supervised Program Repair from Diagnostic Feedback|ICML|2020|[link](https://arxiv.org/abs/2005.10636)|
|DLFix: Context-based Code Transformation Learning for Automated Program Repair|ICSE|2020|[link](https://dl.acm.org/doi/10.1145/3377811.3380345)|
## <a name="policy"></a>Programmatic Reinforcement Learning
To solve tasks described by MDPs, the goal of programmatic reinforcement learning is to learn programmatic policies that are more structured, verifiable, interpretable, and generalizable. The following papers represent programmatic policies using representations such as decision trees, finite state machines, or programs structured in domain-specific languages.
- 7 papers

| Paper Title | Conference | Year | Link |
| ---- | ---- | ---- | ---- |
|Programmable Reinforcement Learning Agents|NIPS|2000|[link](https://people.eecs.berkeley.edu/~russell/papers/nips00-pham.pdf)|
|Programmatically Interpretable Reinforcement Learning|ICML|2018|[link](https://arxiv.org/abs/1804.02477)|
|Verifiable Reinforcement Learning via Policy Extraction|NeurIPS|2018|[link](https://arxiv.org/abs/1805.08328)|
|Towards Mixed Optimization for Reinforcement Learning with Program Synthesis|arXiv|2018|[link](https://arxiv.org/abs/1807.00403)|
|Synthesizing Programmatic Policies that Inductively Generalize|ICLR|2019|[link](https://openreview.net/forum?id=S1l8oANFDH)|
|Learning Finite State Representations of Recurrent Policy Networks|ICLR|2019|[link](https://openreview.net/forum?id=S1gOpsCctm)|
|Imitation-Projected Programmatic Reinforcement Learning|NeurIPS|2019|[link](https://arxiv.org/abs/1907.05431)|
## <a name="bibtex"></a>Cite this list
```
@misc{sun2021programpaperlist,
    author = {Sun, Shao-Hua},
    title = {Program paper list: program synthesis, program induction, program execution, program and code repair, and programmatic reinforcement learning},
    year = {2021},
    journal = {GitHub repository},
    url = {https://github.com/shaohua0116/awesome-program},
}
```
