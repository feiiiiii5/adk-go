# Changelog

## [2.7.2](https://github.com/google/adk-go/compare/v2.7.1...v2.7.2) (2026-11-04)


### Bug Fixes

* **adka2a:** convert empty A2A text parts instead of failing ([#2088](https://github.com/google/adk-go/issues/2088)) ([ee8d5ca](https://github.com/google/adk-go/commit/ee8d5ca44fe26532730ba1bbcf599c91247f58cc))
* **adka2a:** keep LLM agent instructions out of agent card skills ([#2110](https://github.com/google/adk-go/issues/2110)) ([1c35470](https://github.com/google/adk-go/commit/1c3547019cb4d661ce5f4b3cbff8af65e11eb6bb))
* **adkrest:** answer [] from /run when a run yields no events ([#2090](https://github.com/google/adk-go/issues/2090)) ([0159a2e](https://github.com/google/adk-go/commit/0159a2e7ff83cbc07ec52d339d5dd4433fc80d47))
* **adkrest:** let AutoCreateSession reach /run and /run_sse ([#2106](https://github.com/google/adk-go/issues/2106)) ([f6da03a](https://github.com/google/adk-go/commit/f6da03ab78210ab24f4a63c192a37dfe385b2694))
* **exampletool:** write example call arguments in a stable order ([#2073](https://github.com/google/adk-go/issues/2073)) ([e342d2f](https://github.com/google/adk-go/commit/e342d2f6c7493bdc373190518c726d5d5228359d))
* **functioncallmodifier:** leave content-less responses to the rest of the chain ([#2080](https://github.com/google/adk-go/issues/2080)) ([128135a](https://github.com/google/adk-go/commit/128135a82ba5c9af89e1ed381aa848ab2cbbb9b4))
* **llminternal:** end the turn when a preprocessed tool response is final ([#2104](https://github.com/google/adk-go/issues/2104)) ([074b087](https://github.com/google/adk-go/commit/074b087948ec7f8d4f6a9708b0c84c3a4981b8c8))
* **runner:** run OnEvent and AfterRun for a BeforeRun reply in RunLive ([#2105](https://github.com/google/adk-go/issues/2105)) ([dbaca47](https://github.com/google/adk-go/commit/dbaca475d108ac5da198b7fa80fce8b8aa7dd294))
* **sequentialagent:** append the live completion instruction to an InstructionProvider ([#2079](https://github.com/google/adk-go/issues/2079)) ([dd39c80](https://github.com/google/adk-go/commit/dd39c80a1e3db243823cc71fbb78682a8d12690a))
* **session/vertexai:** drop temp: keys from the initial state on Create ([#2100](https://github.com/google/adk-go/issues/2100)) ([0c109f7](https://github.com/google/adk-go/commit/0c109f7dad33815bcee4f101b7b724a1293d8823))
* **telemetry:** leave gcp.project_id off the resource when no project is known ([#2082](https://github.com/google/adk-go/issues/2082)) ([9679009](https://github.com/google/adk-go/commit/967900997525ac42f580eb43436ef8148d69b764))

## [2.7.1](https://github.com/google/adk-go/compare/v2.7.0...v2.7.1) (2026-11-04)


### Bug Fixes

* **agentanalytics:** classify Write API errors and split oversized batches ([#2016](https://github.com/google/adk-go/issues/2016)) ([2466e97](https://github.com/google/adk-go/commit/2466e976ac371b8e2074315c70cbbdaf9b1f2498))
* **model/openaimodel:** refuse media in system and developer Responses messages ([#2025](https://github.com/google/adk-go/issues/2025)) ([40f132d](https://github.com/google/adk-go/commit/40f132d697752596c79d307c4ef2bfb70c55ad9c))
* **model/openaimodel:** refuse non-text payloads beside system instruction text ([#2113](https://github.com/google/adk-go/issues/2113)) ([fe99252](https://github.com/google/adk-go/commit/fe992528e7d1c7e9f648158d47957c241c569ff3)), closes [#2112](https://github.com/google/adk-go/issues/2112)
