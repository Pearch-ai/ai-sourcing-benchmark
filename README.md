# AI Sourcing Benchmark

Benchmarking AI recruitment tools vs. LinkedIn Recruiter using human and LLM evaluations.

📄 [Read the paper](https://github.com/vslaykovsky/ai-sourcing-benchmark/blob/master/ai-sourcing-benchmark.pdf)

## Tools Compared
- Pearch.ai
- LinkedIn Recruiter
- JuiceBox (PeopleGPT)
- Exa.ai

## Highlights
- Pearch.ai ranked highest by both humans and LLM.
- Used Elo scoring on pairwise relevance comparisons.
- Strong alignment: LLM vs. human (r = 0.82).

## Files
- `ai-sourcing-benchmark.ipynb` — Main notebook
- `data/` — Queries, labels, and results

## Run
```bash
git clone https://github.com/vslaykovsky/ai-sourcing-benchmark.git
cd ai-sourcing-benchmark
jupyter notebook ai-sourcing-benchmark.ipynb
```
 
## Citation

If you use this benchmark or code, please cite:

> Vladimir Slaykovskiy, Maksim Zvegintsev, Yury Sakhonchyk, and Hrachik Ajamian.  
> **“Evaluating AI Recruitment Sourcing Tools by Human Preference.”**  
> arXiv:2504.02463 [cs.IR], 2025. https://doi.org/10.48550/arXiv.2504.02463

### BibTeX

```bibtex
@article{slaykovskiy2025evaluating,
  title         = {Evaluating AI Recruitment Sourcing Tools by Human Preference},
  author        = {Slaykovskiy, Vladimir and Zvegintsev, Maksim and Sakhonchyk, Yury and Ajamian, Hrachik},
  journal       = {arXiv preprint arXiv:2504.02463},
  year          = {2025},
  archivePrefix = {arXiv},
  eprint        = {2504.02463},
  primaryClass  = {cs.IR},
  doi           = {10.48550/arXiv.2504.02463},
}
