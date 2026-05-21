# I Built a Search Agent, Then Spent Months Teaching It When Not to Answer

Slides from my talk at the [Paris Machine Learning Meetup](https://www.meetup.com/Paris-Machine-learning-applications-group/) on 20 May 2026.

> A good search agent is not the one that always answers.
> It is the one that knows when it has enough evidence,
> when it needs a tool, and when it should stay silent.

## About the talk

The story of building a search-based assistant for customer-service knowledge — templates, PDFs, operational rules, structured store data — and the practical decisions needed to make it reliable in production.

The talk walks through three iterations:

1. **Naive RAG** — the PoC. Chunk, embed, retrieve, generate. Demos beautifully, breaks on contact with real users.
2. **"Advanced" RAG** — query rewrites, reranking, hierarchical indexing. Better recall, same blind spots.
3. **Modular RAG** — routing, source prioritization, SQL-backed tools, PII detection, moderation, verification, and an explicit abstention path.

The focus is not a perfect architecture, but the trade-offs of running this in production: latency, evaluation, over-refusal, and the cost of silence.

## Slides

- [Paris_ML_Meetup_20-05-2026.pdf](./Paris_ML_Meetup_20-05-2026.pdf) — the deck as presented

## Citation

If you use or reference these slides, please cite as:

```bibtex
@misc{bensaad2026searchagent,
  author       = {Ben Saad, Wajdi},
  title        = {I Built a Search Agent, Then Spent Months Teaching It When Not to Answer},
  howpublished = {Paris Machine Learning Meetup},
  year         = {2026},
  month        = {May},
  url          = {https://www.wajdibensaad.com}
}
```

Or in plain text:

> Ben Saad, W. (2026). *I Built a Search Agent, Then Spent Months Teaching It When Not to Answer.* Paris Machine Learning Meetup, 20 May 2026.

## About me

Wajdi Ben Saad — statistician, researcher, working on small language models, efficient training and inference, and RL & agentic systems. I also teach data visualization at Université Paris Cité.

- Site: [wajdibensaad.com](https://www.wajdibensaad.com)

## License

Slides released under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/). Free to share and adapt for non-commercial use, with attribution.