# Open-source contributions

Bugs I found and fixes I sent to LLM-evaluation, AI-safety, AI infrastructure and research libraries. Each fix starts with an issue that shows the bug, then a pull request with a test.

## Pull requests

| Project | Area | What was wrong | Pull request | Status |
|---|---|---|---|---|
| UK AI Security Institute, control-arena | AI safety | Evaluation bugs | [#970](https://github.com/UKGovernmentBEIS/control-arena/pull/970), [#971](https://github.com/UKGovernmentBEIS/control-arena/pull/971) | Under review |
| LiteLLM | AI gateway | Azure server errors skipped the configured retries | [#54864](https://github.com/BerriAI/litellm/pull/54864) | Under review |
| DeepEval | LLM evaluation | Strict-mode judge accepted off-scale scores | [#3773](https://github.com/confident-ai/deepeval/pull/3773) | Under review |
| Ragas | LLM evaluation | Numeric and ranking metrics accepted judge scores outside the allowed range | [#3151](https://github.com/vibrantlabsai/ragas/pull/3151) | Under review |
| Ragas | LLM evaluation | Concurrent judge calls sent each other's number of completions | [#3167](https://github.com/vibrantlabsai/ragas/pull/3167) | Under review |
| Ragas | Test-set generation | Single-hop questions all came from the first document | [#3166](https://github.com/vibrantlabsai/ragas/pull/3166) | Under review |
| Ragas | Test-set generation | Email extractor regex slowed down badly on long input | [#3170](https://github.com/vibrantlabsai/ragas/pull/3170) | Under review |
| TruLens | LLM evaluation | Agreement grade read on the wrong scale | [#3105](https://github.com/truera/trulens/pull/3105) | Approved by area reviewers |
| TruLens | LLM evaluation | Agreement prompt fix | [#3107](https://github.com/truera/trulens/pull/3107) | Under review |
| TruLens | LLM evaluation | Agreement check asked for its reference answer without the question | [#3111](https://github.com/truera/trulens/pull/3111) | Approved by area reviewers |
| TruLens | LLM evaluation | Groundedness dropped an answer that was just a number | [#3114](https://github.com/truera/trulens/pull/3114) | Approved by area reviewer |
| Opik | LLM evaluation | G-Eval reason parsing | [#9777](https://github.com/comet-ml/opik/pull/9777) | Under review |
| LangChain openevals | LLM evaluation | JSON-match rubric schema missing required fields | [#330](https://github.com/langchain-ai/openevals/pull/330) | Under review |
| Braintrust autoevals | LLM evaluation | ExactMatch docs example used the wrong key order | [#285](https://github.com/braintrustdata/autoevals/pull/285) | Under review |
| W&B Weave | ML tooling | Summarisation scorer crashed on empty output | [#8115](https://github.com/wandb/weave/pull/8115) | Under review |
| bunny.net Terraform provider | Infrastructure | Secret settings were not marked sensitive | [#108](https://github.com/BunnyWay/terraform-provider-bunnynet/pull/108) | Under review |
| bunny.net token authentication | Infrastructure | Node.js signer sorted parameters differently from the other languages | [#25](https://github.com/BunnyWay/BunnyCDN.TokenAuthentication/pull/25) | Under review |
| bunny.net token authentication | Infrastructure | README showed the wrong signing order | [#26](https://github.com/BunnyWay/BunnyCDN.TokenAuthentication/pull/26) | Under review |
| sbi | Statistics | z-scoring bug with independent priors | [#2226](https://github.com/sbi-dev/sbi/pull/2226) | Under review |

## Bugs reported

| Project | Area | What was wrong | Issue |
|---|---|---|---|
| CrewAI | AI agents | A `None` tool argument reached the tool as the text "None" | [#9879](https://github.com/crewAIInc/crewAI/issues/9879) |
| CrewAI | AI agents | Tool instructions showed optional arguments as required | [#9882](https://github.com/crewAIInc/crewAI/issues/9882) |
| Snowflake Snowpark | Data tooling | Local testing gave wrong results for DATEDIFF, MOD, SMALLINT and decimals | [#4561](https://github.com/snowflakedb/snowpark-python/issues/4561), [#4562](https://github.com/snowflakedb/snowpark-python/issues/4562), [#4563](https://github.com/snowflakedb/snowpark-python/issues/4563), [#4564](https://github.com/snowflakedb/snowpark-python/issues/4564) |
| Cloudflare workers-sdk | Developer tooling | `wrangler dev` ignored edits to `.dev.vars` while running | [#17157](https://github.com/cloudflare/workers-sdk/issues/17157) |

Last updated: 28 November 2026.
