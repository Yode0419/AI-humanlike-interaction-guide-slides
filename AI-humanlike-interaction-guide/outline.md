# AI 越像人越好嗎？人機互動設計指南 - Outline

## Deck Setup

- Slide count: 15
- Language: Traditional Chinese
- Aspect ratio: 16:9
- Content sources:
  - `../source/AI 越像人越好嗎？人機互動設計指南.md`
  - `../source/pair-account-for-human-like-interaction-bilingual.md`
- Visual identity: polished UX / human-computer interaction guide, bright neutral background, restrained technical diagrams, friendly but not childish.
- Style system: 2D technical spec diagrams for information + one consistent original 3D compact utility robot for narrative.
- Deck-level character reference:
  - `../assets/mo-reference.png`
  - Usage: broad visual reference for an original compact utility robot character across all slides.
  - Fidelity: do not directly copy the referenced character; preserve only abstract traits such as compact white shell, dark visor, yellow pixel-like eyes, matte utility-product material, and small wheeled base.
  - Required image mapping: all slides should use this as a style / character reference when generating images, not as a strict embedded asset.

## Slide 1: AI 越像人越好嗎？

- Role: cover
- Key points:
  - Introduce the central question: whether AI should become more human-like.
  - Frame the deck around expectation gaps caused by human-like interaction.
  - Subtitle: 探討「類人化互動」帶來的期待落差與設計解方
- Visual idea:
  - Large whitespace cover.
  - Original compact robot and an abstract human silhouette observing each other.
  - Minimal spec tags: `human-like`, `trust`, `expectation`.
- Layout intent:
  - Quiet, premium opening with one strong focal relationship.

## Slide 2: 今天會聊些什麼？

- Role: agenda / deck map
- Key points:
  - 大腦為何把 AI 當人
  - AI 太像人的四大風險
  - 實際設計解方
- Visual idea:
  - Three connected signal paths.
  - The same robot moves along the route in three distinct poses.
  - Use blue for system feedback, orange for social expectation, green for resolution.
- Layout intent:
  - Make the audience understand the whole arc before entering details.

## Slide 3: 從一個日常小現象說起

- Role: story / context
- Key points:
  - People often say "thank you" to voice assistants.
  - Rationally we know it is software.
  - In the moment, natural conversation triggers automatic social response.
- Visual idea:
  - Single everyday scene: user thanks a voice assistant or small robot device.
  - Two spec labels:
    - 理性認知：這是程式
    - 自動反應：把它當社交對象
- Layout intent:
  - Let the situation be understood visually before relying on text.

## Slide 4: 本能 vs. 設計

- Role: concept comparison
- Key points:
  - 擬人化（Anthropomorphization）是大腦的本能。
  - 人性化（Humanization）是刻意加入人類特徵的設計選擇。
  - 兩者混淆時，使用者期待容易被拉高。
- Visual idea:
  - Left side: human projection onto a machine, with automatic brain shortcut labels.
  - Right side: designer adding voice / tone / human-like cues intentionally.
  - Robot in the center as the comparison object.
- Layout intent:
  - Clear left-right contrast without making the page feel like a generic two-card layout.

## Slide 5: 當 AI 擁有身體

- Role: concept explanation
- Key points:
  - Embodied AI occupies physical or visual space.
  - Movement and spatial presence trigger stronger perception of agency.
  - This makes projection stronger than voice-only interaction.
- Visual idea:
  - Spatial perception diagram with movement path, attention cone, and distance rings.
  - Robot moves through the scene, triggering human gaze-tracking.
- Layout intent:
  - Use space, motion, and distance as the main information carriers.

## Slide 6: 心理模型與期待落差

- Role: concept explanation / sample candidate
- Key points:
  - People reuse human-social rules when facing conversational or embodied AI.
  - AI operates through features, pixels, patterns, and model confidence.
  - Expectation gaps appear when users expect human-like understanding.
- Visual idea:
  - Two-layer diagram:
    - Top: 人類期待 / social mental model
    - Bottom: AI 實際運作 / feature recognition pipeline
  - Example: face recognized, back view not understood.
- Layout intent:
  - Test whether abstract ideas can be explained with clean diagrams and limited Chinese text.

## Slide 7: 風險一：拿 AI 跟人比較

- Role: risk series
- Key points:
  - Users compare generative AI with themselves or human experts.
  - Early fluency creates over-trust.
  - One basic error can create a sharp trust collapse.
- Visual idea:
  - Trust curve rises then drops suddenly.
  - `Situation` and `Impact` labels beside the curve.
  - Robot stands near the drop point with a caution state.
- Layout intent:
  - Start the risk section with a clear emotional arc.

## Slide 8: 風險二：界線模糊

- Role: risk series
- Key points:
  - A universal AI assistant without clear limits creates uncertainty.
  - Users may wonder what the system can or cannot do.
  - Ambiguous limits reduce trust.
- Visual idea:
  - Capability boundary map.
  - Robot stands beside a fading or broken boundary line.
  - Unknown zone shown with muted risk color.
- Layout intent:
  - Keep series consistency with Slide 7 while changing composition.

## Slide 9: 風險三：過度依賴與隱私危機

- Role: risk series
- Key points:
  - Empathic AI can make users feel understood.
  - Users may reveal sensitive information.
  - AI must not replace professional medical or counseling support.
- Visual idea:
  - Private information stream moving toward AI.
  - Robot uses distance, warning light, or a small barrier to slow the flow.
  - Use risk pink plus limited yellow warning.
- Layout intent:
  - Make privacy risk visible without using fear-based visuals.

## Slide 10: 風險四：對專業工具造成反效果

- Role: risk series / comparison
- Key points:
  - Human-like hesitation may reduce expectation in casual contexts.
  - In expert tools, "I am not sure..." can signal unreliability.
  - Humanization should fit the task domain.
- Visual idea:
  - Left-right scenario comparison:
    - Casual context: uncertainty feels approachable.
    - Medical / finance expert context: uncertainty undermines confidence.
  - Robot changes posture between approachable and constrained system state.
- Layout intent:
  - Close risk section with a strong design tradeoff.

## Slide 11: 建議一：承認我是 AI

- Role: design recommendation
- Key points:
  - Clearly disclose that the product is AI-driven, not a person.
  - Disclosure protects users who may misread the system.
  - This creates the first safety boundary.
- Visual idea:
  - Robot actively displays an `AI SYSTEM` identity label.
  - Simple interface disclosure panel with readable short text.
  - Blue + green shift to mark the start of solutions.
- Layout intent:
  - Turn the visual tone from risk to practical design guidance.

## Slide 12: 建議二：讓使用者自己驗證

- Role: design recommendation / process
- Key points:
  - Do not present AI output as one absolute answer.
  - Provide sources, facts, or multiple viewpoints.
  - Let users calibrate trust by verifying.
- Visual idea:
  - Verification loop: AI output -> sources -> user judgment -> calibrated trust.
  - Robot presents options rather than one final answer.
- Layout intent:
  - Show trust calibration as a repeatable interaction pattern.

## Slide 13: 建議三：給予明確的互動引導

- Role: design recommendation / sample candidate
- Key points:
  - AI needs clearer input than human conversation often requires.
  - Input templates define the system's useful range and show users how to formulate requests.
  - Clarifications should ask questions or suggest additions when input is underspecified.
  - User control is strengthened when the system pauses instead of guessing.
  - When meaning is unclear, the system should ask: "你的意思是 A 還是 B？"
- Visual idea:
  - Ambiguous input splits into A / B branches.
  - Robot stops and asks instead of making an assumption.
  - Use green for control returned to the user.
- Layout intent:
  - Recommended first sample slide because it tests Chinese text, 2D branching diagram, robot consistency, and solution-section tone.

## Slide 14: 建議四：真的需要人性化嗎？

- Role: design recommendation / decision gate
- Key points:
  - Not every AI system needs human-like cues.
  - First ask whether humanization helps users complete the task.
  - Then ask whether AI capability can support the expectations users will project onto it.
  - Finally ask whether these cues will distract, mislead, or make users overestimate the system.
  - If the answers are not clear, do not add humanization yet.
- Visual idea:
  - Decision-gate / funnel flow instead of a matrix.
  - Start from `想加入人性化線索`, then pass through three gates:
    - `有助任務？`
    - `能力匹配期待？`
    - `不會造成誤導？`
  - Outcomes:
    - Green path: `加入，但保持揭露與邊界`
    - Grey path: `不加入，維持工具感`
  - Robot appears as a design reviewer beside the gates.
- Layout intent:
  - Directly answer the title question: whether the product really needs humanization.

## Slide 15: 結語與帶走原則

- Role: closing summary
- Key points:
  - 最好的設計往往帶有一種克制。
  - 明確揭露 AI 身分。
  - 校準信任與能力期待。
  - 只有在有助任務時才加入人性化。
- Visual idea:
  - Three takeaway principles arranged with generous whitespace.
  - Robot appears as a reliable tool beside a clean interface, not pretending to be human.
- Layout intent:
  - Calm, concise ending with no new complex concepts.

## Sample Slide Recommendation

- First sample: Slide 13.
- Backup sample: Slide 6.
- Additional alternatives: Slide 7 or Slide 10 if risk-section color and composition need earlier validation.
- Do not use only the cover as the sample because it does not test content density, Chinese text clarity, or diagram quality.

## Global Visual Constraints

- Keep at least 35-40% whitespace per slide.
- Use one main visual focus per slide.
- Use at most three major information groups per slide.
- Keep colors semantic:
  - `#4DA3FF` for AI information flow / system feedback
  - `#FFB38A` for human emotion / social expectation
  - `#F59B9B` for risk / expectation mismatch
  - `#7BC8A4` for appropriate interaction / solution
  - `#FFD84D` for robot attention / perception
- Avoid dense small Chinese text; move detail and references into speaker notes.
- Avoid direct copying of M-O or any existing movie character.
- Avoid human faces, humanoid proportions, five-finger hands, cyberpunk, heavy HUD, dark sci-fi, and repeated three-card layouts.


