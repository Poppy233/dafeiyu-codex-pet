# DaFeiYu · 大肥鱼

A blue-haired whale-maid companion for research and coding, inspired by the DSH community character 大肥鱼. Noncommercial fan art, shared under **CC BY-NC-SA 4.0**.

![DaFeiYu animation preview](assets/all-states.gif)

## Use the pet

### ChatGPT Work

[Open the shared pet](https://chatgpt.com/s/sharepet_6afad1beab908191be77234ac2d15f8f).

The full v2 sprite sheet is [assets/spritesheet-v2.png](assets/spritesheet-v2.png). It contains nine animation states and sixteen look directions in a 1536 × 2288 transparent atlas.

### Codex desktop / community catalogs

The repository root contains the conventional nine-row package: `pet.json` and `spritesheet.webp` (1536 × 1872, 192 × 208 cells). Copy those files together with `LICENSE` and `ATTRIBUTION.md` into `${CODEX_HOME:-$HOME/.codex}/pets/dafeiyu/`, then choose DaFeiYu in the app's pet picker.

On Windows, the usual destination is `%USERPROFILE%\.codex\pets\dafeiyu\`.

This compatibility package retains the original nine animation rows. The additional sixteen look directions remain in the full v2 atlas; they are not included in the nine-row package. Package structure follows the [OpenAI Codex pet contract](https://github.com/openai/skills/blob/main/skills/.curated/hatch-pet/references/codex-pet-contract.md).

## Animations

Idle, move right, move left, wave, jump, failure reaction, waiting, working, and review.

![Idle and jump preview](assets/idle-jump-idle.gif)

![Sixteen look directions](assets/look-loop.gif)

The original v2 atlas passed the ChatGPT Pets sprite preflight. Some intermediate look-direction transitions have small continuity/ambiguity warnings; the four cardinal directions passed review. The compatibility package was made by cropping and losslessly encoding approved pixels; it has not been installed in a separate Codex desktop session as part of this release.

## Attribution

Source: [PC2005-cloud/dsh-pet](https://github.com/PC2005-cloud/dsh-pet). Original 溟月 character: [@上善无形](https://space.bilibili.com/4456176). DeepSeek whale-maid design: [@ZipZipPipe](https://space.bilibili.com/4168597). This is community fan art and is not an official DeepSeek mascot.

See [ATTRIBUTION.md](ATTRIBUTION.md) and [LICENSE](LICENSE) for the required credits and **noncommercial, share-alike** terms. This pet is offered for free; commercial use is not permitted by its character license.
