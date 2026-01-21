# FineWeb Seminar Poster - Resources & References
This repository accompanies a seminar poster examining "The FineWeb Datasets: Decanting the Web for the Finest Text Data at Scale" (Penedo et al., 2024) from an archaeologist perspective, with an emphasis on prior and subsequent work. It provides references and additional resources to support and contextualize the poster content.

## References 

**FineWeb**

Penedo, et al., "The FineWeb Datasets: Decanting the Web for the Finest Text Data at Scale", 2024.
https://arxiv.org/abs/2406.17557

**RefinedWeb**

Penedo, et al., "The RefinedWeb Dataset for Falcon LLM: Outperforming Curated Corpora with Web Data, and Web Data Only", 2023.
https://arxiv.org/abs/2306.01116

**FineWeb2**

Penedo, et al., "FineWeb2: One Pipeline to Scale Them All -- Adapting Pre-Training Data Processing to Every Language", 2025.
https://arxiv.org/abs/2506.20920

## Additional Material

**HuggingFace Resources**

HuggingFace website: https://huggingface.co/

HuggingFace organization site for the FineData team: https://huggingface.co/HuggingFaceFW

HuggingFace dataset site for FineWeb: https://huggingface.co/datasets/HuggingFaceFW/fineweb

HuggingFace dataset site for FineWeb Edu: https://huggingface.co/datasets/HuggingFaceFW/fineweb-edu

HuggingFace blogpost on FineWeb: https://huggingface.co/spaces/HuggingFaceFW/blogpost-fineweb-v1

HuggingFace dataset site for Falcon RefinedWeb: https://huggingface.co/datasets/tiiuae/falcon-refinedweb

HuggingFace dataset site for FineWeb2: https://huggingface.co/datasets/HuggingFaceFW/fineweb-2

**Common Crawl**

Common Crawl website: https://commoncrawl.org/

## Summary: Archaeologist Perspective

### RefinedWeb 2023 (Prior Work)

- extractes high-quality English web text from Common Crawl snapshots
- uses filtering and deduplication 
- showed that filtered web data alone can compete with curated datasets such as The Pile
- **Influence of FineWeb:** FineWeb is based on RefinedWeb and the idea that careful multi-step filtering and deduplication of raw web text can scale for LLM pre-training

### FineWeb 2024

- represents a quality and scale improvement over RefinedWeb
- pipeline refinement: multistep filterting and dedupulication
- benchmark evaluation
- basis for subsequent datasets such as FineWeb Edu and FineWeb 2

### FineWeb2 2025 (Subsequent Work)

- extends FineWeb to 1000 languages
- introduces langauge-adaptive filtering
- scaling beyonfd the English language

## Takeaways

- Prior work: showed that only filtered web data can compete and outperform curated datasets (RefinedWeb)
- FineWeb: scales and optimizes LLM pre-training datasets (also makes it open-source)
- Subsequent work:
  - adapts approach for educational and academic purposes (FineWeb Edu)
  - adapts the methadology to more languages, creating a multilingual dataset (FineWeb2)
- Insights:
  - A technological evolution is clearly visible when looking at RefinedWeb, FineWeb and FineWeb2
  - smaller English datasets -> large English datasets -> multilingual high-quality datasets
