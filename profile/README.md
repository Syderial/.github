<p align="left">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="syderial-lockup-light.png">
    <img src="syderial-lockup-ink.png" alt="Syderial" width="213">
  </picture>
</p>

# The system of record for intelligence

Intelligence has no system of record. We think it should.

Every agent your business runs is only as accurate as the context it's provided, and only as safe as the policy it acts under. Syderial keeps both for the whole business, as a record: the context and the policy of record, for humans and agents, under whatever harness, model and provider you choose.

Your teams choose the agents, the models and the harnesses. Syderial is the layer under all of them. Each claim cites its evidence, who asserted it and when it applied. Each policy rule has its version. When an agent acts, Syderial brings the two together: the operation goes ahead only when the record entails it and the policy allows it, and a signed receipt shows both.

## How it works

Six stations, in order.

1. **Capture** records the source, the author and the time.
2. **Bound** sets who can read it.
3. **Entail** checks that the claim follows the evidence.
4. **Compile** builds the packet an agent is provided.
5. **Gate** checks an action against the grounding and the policy.
6. **Receipt** signs what was provided and the rule as applied.

The record doesn't assert truth. It says what is in it, where it came from, on whose authority, and what it doesn't know. Corrections are new entries; nothing is overwritten. When a question falls outside the record, the answer says so, with a receipt that cites nothing.

People reach the same record from the assistant they already use, through MCP scoped to what they can read, and approve grants and decisions from the phone. The check applies when the agent's tool calls go through Syderial's gate: a harness hook, MCP or the gateway.

## Try it

- **Walkthrough:** [demo.syderial.ai](https://demo.syderial.ai). A synthetic oil and gas operator, Northwind Energy, Well 47. No account. Every sentence in an answer cites a record; open the receipt and verify the hashes in your browser. The answers come from the live runtime; only the data is made up.
- **Film:** [Well 47, the night the record mattered](https://youtu.be/QHwq43pFDNs).
- **Research:** [What the next model inherits](https://syderial.ai/research/what-the-next-model-inherits).

## What is open

The record belongs to the business that keeps it, and anyone it hands a receipt to can check that receipt without asking us. [receipt-verifier](https://github.com/Syderial/receipt-verifier) checks a signed action receipt or audit-chain event offline in a browser or Node, no dependencies, Apache-2.0. What you can do with it now: run its tests, verify the bundled example receipt, change one byte and watch it fail, and read the receipt format. The signing keys are published at [api.syderial.ai/.well-known/syderial-signing-keys.json](https://api.syderial.ai/.well-known/syderial-signing-keys.json). Receipts you can take from the walkthrough come next, so a receipt from Well 47 verifies against those keys the same way. The record format follows. The runtime that keeps the record is what we sell, in your cloud, on-prem or air-gapped.

## Talk to us

Syderial works with design partners in regulated operations, starting with energy.

- **Inquiries and early access:** [hello@syderial.ai](mailto:hello@syderial.ai)
- **Site:** [syderial.ai](https://syderial.ai)
- **X:** [@SyderialAI](https://x.com/SyderialAI)
- **LinkedIn:** [Syderial](https://www.linkedin.com/company/syderial)

Free the reasoning. Govern the hands.
