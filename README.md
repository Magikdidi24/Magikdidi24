# Samuel Berthelot

AI engineering student at EPITA (France), on exchange at Shibaura Institute of Technology in Tokyo right now.
I work on image reconstruction with PyTorch, and on compilers and developer tooling.

[Portfolio](https://magikdidi24.github.io) - [LinkedIn](https://www.linkedin.com/in/berthelot11) - samuel.berthelot11@gmail.com

## What I've worked on

- Hyperspectral reconstruction at the LRE, EPITA's research lab (2026). Convex reconstruction of photon-starved SEM-EDS cubes of meteorites in PyTorch on GPU, guided by the backscattered-electron image. +1.5 dB PSNR on a synthetic ground truth. The code stays with the lab.
- Compiler work at Faveod in Paris. Bug fixes and optimization on a multi-source compiler, the pipeline went from 17 to 9 minutes. I also made compilation 3x faster in the Roslyn C# engine and switched the parser from whitequark to Prism (20% faster parsing). I improved the pretty-printer and parenthesization too, and moved the project from Node.js to Deno with much stricter generated TypeScript.
- Open source: four merged PRs to [RuboCop](https://github.com/rubocop/rubocop/pulls?q=author%3AMagikdidi24) (the `rubocop:push` / `rubocop:pop` directives and some fixes), and a [fork of tree-sitter-ruby](https://github.com/Magikdidi24/tree-sitter-ruby) that I maintain, with Ruby 3.0+ syntax and parser fixes.
- Private EPITA projects: a Tiger compiler in C++, a POSIX shell (42sh) and malloc in C, Go microservices with Docker, a Quarkus REST backend.

## Public projects

| Project | What it is | Stack |
| --- | --- | --- |
| [llama-from-scratch](https://github.com/Magikdidi24/llama-from-scratch) | Small Llama-style LLM pretrained from scratch on TinyStories, plus scaling law, Muon and MoE experiments | Python, PyTorch |
| [tiny-chronos](https://github.com/Magikdidi24/tiny-chronos) | Chronos-style forecasting model trained only on synthetic data, tested zero-shot on ETTh1/ETTm1 | Python, PyTorch |
| [breast-ultrasound-cnn](https://github.com/Magikdidi24/breast-ultrasound-cnn) | ResNet-34 classification and U-Net segmentation of breast ultrasound images, tested on a dataset from another hospital | Python, PyTorch |
| [nlp2-project-2026](https://github.com/Magikdidi24/nlp2-project-2026) | How much meaning NLLB-200 loses through chained back-translation | Python, PyTorch, Hugging Face |
| [TIPE](https://github.com/Magikdidi24/TIPE) | Genetic algorithm evolving neural networks that play Snake, my TIPE from prépa | Python, NumPy, pygame |
| [ChessBoard](https://github.com/Magikdidi24/ChessBoard) | Chess in Rust with my own engine (negamax, alpha-beta, quiescence search) | Rust, macroquad |
| [py-allumette-optimize](https://github.com/Magikdidi24/py-allumette-optimize) | Race car speed and trajectory optimization, MPC vs MPC with a learned residual, autodiff written from scratch | Python |
| [Fluid_Simulation](https://github.com/Magikdidi24/Fluid_Simulation) | 2D liquid simulator (cellular automaton) with 20 liquids of different densities | C, SDL3 |
| [playground_ruby](https://github.com/Magikdidi24/playground_ruby) | Local Ruby playground, the code runs in a locked-down container | React, Node.js, Docker |
| [tsa_absenteeism_at_work](https://github.com/Magikdidi24/tsa_absenteeism_at_work) | Time series analysis and classification on absenteeism data | Python, Jupyter |

There's a bit more about each one on [my site](https://magikdidi24.github.io/projects/).

## Stack

Python, PyTorch, NumPy, C, C++, Rust, Ruby, Go, Java, SQL, Bash, Git, LaTeX
