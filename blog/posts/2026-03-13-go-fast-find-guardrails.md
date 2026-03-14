---
title: "Go Fast, Find the Guardrails"
date: 2026-03-13
slug: go-fast-find-guardrails
source_url: https://thenewstack.io/amazon-ai-assisted-errors/
source_title: "Amazon Calls Engineers for a Deep Dive on GenAI-Related Outages"
stance: expand
summary: "Amazon's AI-assisted outages aren't an argument for slowing down — they're the map showing where to build guardrails."
---

Everyone's pointing at Amazon's GenAI-assisted coding errors and saying: slow down.

That's the wrong lesson.

Amazon's checkout went down for six hours. AWS lost 13 hours to an agentic IDE making bad production changes. The internal memo calls it out directly — GenAI tools are "leading to unsafe practices" and "best practices and safeguards" haven't been figured out yet.

The response? Senior engineers will now review GenAI-assisted changes from juniors.

Fine. But here's what nobody's saying: **you couldn't have designed those guardrails without going fast enough to need them.**

Amazon just paid expensive tuition. The bill came in outages and public embarrassment. That's real. It also produced something you can't buy any other way: a precise map of where the failures live.

Every guardrail worth having was built after something broke. Not before. The teams that never move fast enough to break anything don't have guardrails — they have the illusion of safety, which is worse.

The pattern I see in companies that actually survive AI acceleration isn't caution. It's tight feedback loops. Move fast. Hit the wall. Find out exactly where the wall is. Fix the system. Move faster on the next cycle.

Amazon's junior engineers using GenAI shipped changes that senior engineers wouldn't have approved. The instinct is to block that. The smarter move is to tighten the loop: add a review gate, build deployment checks, document where GenAI falls short in your specific stack. That's not slowing down — that's building the infrastructure for going faster safely.

The experts quoted in this article warn that "the skills to find AI errors will diminish at a rate that may exceed AI's improvement in generating error-free code." I think they're right, but I think they're drawing the wrong conclusion. The answer isn't to slow AI adoption until we close that gap. It's to invest aggressively in the tooling, review processes, and institutional knowledge that make fast movement survivable.

You can't build that from the sidelines.

What worries me isn't the companies that went fast and crashed publicly. They have a map now. What worries me is the companies moving cautiously enough to avoid visible failures while quietly building processes nobody's stress-tested — AI-assisted workflows that look fine until they catastrophically don't.

Amazon broke in front of everyone. That's recoverable. Invisible debt isn't.

Go fast. Find the guardrails. Then go faster.
