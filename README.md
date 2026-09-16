<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Cascadia+Code&weight=700&size=17&color=0078D7&center=true&pause=100000&lines=Hi,+I'm+Lin+Hongyu.+AI-Native+Engineer" alt="Hi, I'm Lin Hongyu. AI-Native Engineer" />
  <p>
    <img src="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif" width="28px" height="28px" alt="Waving hand" />
    <strong>I'm currently focused on AI-native systems and open-source infrastructure.</strong>
  </p>
  <p>
    <code>Xiamen University · M.Sc. in Artificial Intelligence</code>
  </p>
</div>

<table>
<tr>
<td valign="top" width="50%">

#### 💼 Experience & Research

📄 [View Offers →](offer.md)

- **SDIC Intelligence** · LLM Algorithms
- **Xiamen University** · Artificial Intelligence, 2025–2028
- **Focus** · AI Agents, Memory, RAG, and Evaluation

</td>
<td valign="top" width="50%">

#### 💻 Open Source Experience

🏅 [View Awards →](Awards.md)

- **25 merged PRs** across **17 upstream projects**
- **Agent runtime & memory** — [OpenClaw](https://github.com/openclaw/openclaw) · [nanoclaw](https://github.com/nanocoai/nanoclaw) · [IronClaw](https://github.com/nearai/ironclaw) · [ZeroClaw](https://github.com/zeroclaw-labs/zeroclaw)
- **RAG & retrieval** — [LightRAG](https://github.com/HKUDS/LightRAG) · [Haystack](https://github.com/deepset-ai/haystack) · [WeKnora](https://github.com/Tencent/WeKnora) · [Qdrant Client](https://github.com/qdrant/qdrant-client)
- **Document & data infra** — [Unstructured](https://github.com/Unstructured-IO/unstructured) · [Apache Arrow-rs](https://github.com/apache/arrow-rs) · [OCRmyPDF](https://github.com/ocrmypdf/OCRmyPDF) · [Apache Flink Agents](https://github.com/apache/flink-agents)

</td>
</tr>
</table>

### 🔧 Selected Merged Contributions

Fixes to correctness and safety contracts at cross-boundary seams — each with a
reproduction, a regression test that fails on the pre-fix code, and an explicit
scope limit.

| Project | Contribution | PR |
|---|---|---|
| [openclaw/openclaw](https://github.com/openclaw/openclaw) | Agent memory search was non-monotonic — asking for fewer results dropped the best match, because each retrieval leg truncated its candidate set before ranking | [#136984](https://github.com/openclaw/openclaw/pull/136984) |
| [HKUDS/LightRAG](https://github.com/HKUDS/LightRAG) | `join_unique` merged via a `set`, so provenance order shifted across processes while `source_id` / `file_path` are truncated positionally | [#3928](https://github.com/HKUDS/LightRAG/pull/3928) |
| [nanocoai/nanoclaw](https://github.com/nanocoai/nanoclaw) | Update transactions snapshotted symlinked mutable roots as links, so rollback replaced the operator's external data layout | [#3689](https://github.com/nanocoai/nanoclaw/pull/3689) |
| [openclaw/openclaw](https://github.com/openclaw/openclaw) | Trajectory export redacted successful paginated `read` output as malformed JSON, losing the evidence | [#143930](https://github.com/openclaw/openclaw/pull/143930) |
| [deepset-ai/haystack](https://github.com/deepset-ai/haystack) | DBSF fusion flattened zero-variance score lists, erasing the ranking signal | [#12508](https://github.com/deepset-ai/haystack/pull/12508) |
| [genkit-ai/genkit](https://github.com/genkit-ai/genkit) | `stream_options` leaked into non-streaming OpenAI calls | [#6297](https://github.com/genkit-ai/genkit/pull/6297) |
| [Tencent/WeKnora](https://github.com/Tencent/WeKnora) | An explicit "clear" was indistinguishable from "field absent" across the TypeScript–JSON–Go boundary, so cleared knowledge bases came back | [#3043](https://github.com/Tencent/WeKnora/pull/3043) |
| [Unstructured-IO/unstructured](https://github.com/Unstructured-IO/unstructured) | Per-section rescans made multi-section DOCX partitioning quadratic | [#4471](https://github.com/Unstructured-IO/unstructured/pull/4471) |

<sub>Full list: 25 merged PRs across 17 projects — see
[all merged PRs](https://github.com/search?q=is%3Apr+author%3Alinhongyu510+is%3Amerged+-user%3Alinhongyu510&type=pullrequests).</sub>
