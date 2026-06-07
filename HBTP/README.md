# HBTP

**HBTP: Heuristic Behavior Tree Planning with Large Language Model Reasoning** — ICRA 2025.

This repository hosts the project page for HBTP, a reliable and efficient framework that integrates BT planning with LLM reasoning for behavior tree generation.

## Project structure

```
HBTP/
├── index.html              # Main project page (semantic HTML5)
├── css/style.css           # Single stylesheet
├── images/
│   ├── logo.png            # Favicon / brand mark
│   ├── framework.png       # Framework overview figure
│   └── RW_{1,2,3}.svg      # Planned behavior trees (Easy / Medium / Hard)
├── videos/
│   ├── ICRA2025_30m.mp4    # Conference video
│   └── RW_{1,2,3}.mp4      # RoboWaiter demonstrations
└── README.md
```

## Local preview

```bash
python3 -m http.server 8765
# open http://localhost:8765
```

## Citation

```bibtex
@article{cai2024hbtp,
  title   = {HBTP: Heuristic Behavior Tree Planning with Large Language Model Reasoning},
  author  = {Yishuai Cai and Xinglin Chen and Yunxin Mao and Minglong Li and Shaowu Yang and Wenjing Yang and Ji Wang},
  year    = {2024},
  url     = {https://arxiv.org/abs/2406.00965},
  journal = {arXiv preprint arXiv:2406.00965},
}
```

Page template adapted from the [Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template).
