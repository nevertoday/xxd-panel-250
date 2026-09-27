<div align="center">

# XXD Panel 250｜建筑几何诗

Keep the photograph above. Below, compress the scene into abstract architectural contours, geometric modules and quiet editorial space.

<a href="README.md">简体中文</a> · <a href="README.en.md">English</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

> Original prompt (five-language entry): [简中](references/original-prompt/zh-CN.md) · [English](references/original-prompt/en.md) · [日本語](references/original-prompt/ja.md) · [한국어](references/original-prompt/ko.md) · [العربية](references/original-prompt/ar.md).

## 3:4 Top–Bottom Samples

Twenty independent photographs, each rebuilt as one complete 3:4 top–bottom canvas. The photograph stays in the upper half and this Panel's design fills the lower half, exact 50:50. Visible copy is generated from the current photograph. The language rotates across Chinese, English, Japanese, Korean and Arabic.

<table>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-01.png" alt="XXD Panel 250 sample 01"></td>
    <td width="50%"><img src="./assets/examples/sample-02.png" alt="XXD Panel 250 sample 02"></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-03.png" alt="XXD Panel 250 sample 03"></td>
    <td width="50%"><img src="./assets/examples/sample-04.png" alt="XXD Panel 250 sample 04"></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-05.png" alt="XXD Panel 250 sample 05"></td>
    <td width="50%"><img src="./assets/examples/sample-06.png" alt="XXD Panel 250 sample 06"></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-07.png" alt="XXD Panel 250 sample 07"></td>
    <td width="50%"><img src="./assets/examples/sample-08.png" alt="XXD Panel 250 sample 08"></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-09.png" alt="XXD Panel 250 sample 09"></td>
    <td width="50%"><img src="./assets/examples/sample-10.png" alt="XXD Panel 250 sample 10"></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-11.png" alt="XXD Panel 250 sample 11"></td>
    <td width="50%"><img src="./assets/examples/sample-12.png" alt="XXD Panel 250 sample 12"></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-13.png" alt="XXD Panel 250 sample 13"></td>
    <td width="50%"><img src="./assets/examples/sample-14.png" alt="XXD Panel 250 sample 14"></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-15.png" alt="XXD Panel 250 sample 15"></td>
    <td width="50%"><img src="./assets/examples/sample-16.png" alt="XXD Panel 250 sample 16"></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-17.png" alt="XXD Panel 250 sample 17"></td>
    <td width="50%"><img src="./assets/examples/sample-18.png" alt="XXD Panel 250 sample 18"></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-19.png" alt="XXD Panel 250 sample 19"></td>
    <td width="50%"><img src="./assets/examples/sample-20.png" alt="XXD Panel 250 sample 20"></td>
  </tr>
</table>

## Best-fit situations and problems solved

For deriving a spatial moment that stands on its own. The upper half is the photograph. The lower half does not keep every object. It builds a skeleton from abstract architectural contours, flat structure and a few color modules. The subject may sit off-center, touch an edge, float or be cropped.

Forms stay simple, with slightly irregular edges, between organic geometry and playful minimalism. Avoid a realistic panorama, piled detail and a tracing of the photograph.

## Usage tips

- **Start with one clear photo:** choose a source whose subject, action, and relationships are easy to recognize before choosing the delivery format.
- **Join the parameters in one sentence:** say “top-bottom / left-right / design-only + 16:9 / 3:4 / phone wallpaper”; you can also name desktop, tablet, or smartwatch sizes.
- **State what must stay:** identify the people, objects, actions, relationships, and copy to preserve, while leaving room for the style to design the layout.
- **Choose a text mode:** let the model write from the image, lock exact wording with `--text exact --copy`, or remove text completely with `--text none`.
- **Clarify reality and design regions:** for top-bottom or left-right, say which region keeps the photograph and which region is redesigned; for design-only and wallpapers, say that the whole canvas is redesigned.
- **Test one image before batching:** confirm mode, ratio, text, and language on one source, then reuse the settings for a folder; change one variable per iteration.

## Getting started

Install from GitHub:

```bash
npx skills add https://github.com/xiaoxiaodong-ai/xxd-panel-250 --skill xxd-panel-250
```

Restart the agent session after installation, then invoke `$xxd-panel-250`. Add `--global --agent codex --yes` when a user-level Codex installation is wanted.

Common examples:

```text
/xxd-panel-250 photo.jpg --mode top-bottom --size 3:4 --text prompt --locale en-US
/xxd-panel-250 photo.jpg --mode left-right --size 16:9 --text prompt --locale en-US
/xxd-panel-250 photo.jpg --mode design-only --size 9:16 --text none --prefs off
/xxd-panel-250 ./photos --mode design-only --size auto,3:4 --text prompt --locale ja-JP
```

See [SKILL.md](SKILL.md) for the full runtime contract and the [English](references/xxd-panel-250-prompt.en.md) or [Chinese](references/xxd-panel-250-prompt.zh-CN.md) runtime adapter.

## Original prompt

The [complete Chinese source](references/original-prompt/zh-CN.md) is preserved verbatim and is the sole creative and aesthetic authority at runtime. This batch provides five-language usage documentation, without four additional long-form translations. Style summaries are for discovery only and never replace the source.

## Quick fit check

Keep the source identity while redirecting composition; retain the material signature while actively leaving space. Choose exact text, generated copy or no text, with single-image or recursive directory processing and the four delivery modes below.

## Four output modes

- `top-bottom`: exactly two full-width regions, reality above and design below, 50% each.
- `left-right`: exactly two full-height regions, reality left and design right, 50% each; it never rotates into a top-bottom layout.
- `design-only`: the full canvas contains only Panel 250's designed translation; the photograph remains a non-visible reference.
- `wallpaper-pack`: creates complete artworks for phone, iPad, desktop, and watch, either `linked` as a coherent family or `independent` as four separate works.

Modes and sizes may be combined. Supported sizes include `1:1`, `3:4`, `4:3`, `4:5`, `5:4`, `2:3`, `3:2`, `9:16`, `16:9`, `21:9`, `5:7`, `7:5`, and exact pixels. Text can be prompt-generated, user-exact, or absent. A directory is inventoried recursively and every source is isolated while sharing one set of delivery settings; final PNG files remain flat in one fresh task directory.

<!-- xxd-readme-ads:start -->
## About XXD

XXD is Xiaoxiaodong's abbreviated brand name. This project is created and maintained by [@xiaoxiaodong01](https://x.com/xiaoxiaodong01).

## Xiaoxiaodong multi-platform membership · CNY 699/year

> **Advertising disclosure:** The QR code, membership, and paid-service links below are XXD promotional information. Scanning or purchasing is entirely optional and does not affect access to this open-source project.

One annual membership unlocks three benefits together: **Knowledge Planet + the XXD Member Prompt Library + membership for all General Skills**. They are included in one membership; no separate purchase is required.

<!-- xxd-panel-command-system:start -->

### How the Skills work together

| Level | Included | What it does |
|---|---|---|
| **General** | [`xxd-panel-all`](https://github.com/xiaoxiaodong-ai/xxd-panel-all) | Detects available numbered Skills, recommends them by image, theme, or use, and organizes multi-style and batch tasks. |
| **Soldier** | `xxd-panel-NNN` | Each numbered Skill follows its own original brief and aesthetic to complete the specific task assigned by the General. |

<!-- xxd-panel-command-system:end -->

### What you receive

1. **One-to-one WeChat AI learning and project support**
   Add Xiaoxiaodong on WeChat via the QR code below to discuss AI learning, tools, and real projects one to one, with practical guidance and answers. Representative questions may be organized into member resources.
2. **A growing member prompt library**
   The [XXD Member Prompt Library](https://vip.xiaoxiaodong.ai/) currently contains about 32,000 prompts and will keep expanding, with a goal of exceeding 100,000.
3. **All General Skills and usage support**
   One membership covers every General Skill, with usage guidance and Q&A when you need help.
4. **Priority for high-need requests**
   Frequently requested, high-need prompts and Skills are reviewed and developed first where appropriate.

### How to join

- [Activate membership on the member website](https://vip.xiaoxiaodong.ai/).
- Or scan the QR code below to add Xiaoxiaodong on WeChat for one-to-one activation support.

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="Contact Xiaoxiaodong" width="280"></a></p>
<!-- xxd-readme-ads:end -->

## License

This project—including the Skill, prompts, scripts, documentation, and accompanying sample images—is licensed under the **PolyForm Noncommercial License 1.0.0**. See [LICENSE](LICENSE) for the full legal text and <https://polyformproject.org/licenses/noncommercial/1.0.0> for the official page.

In plain language:

- Individuals may use it for study, research, experimentation, testing, hobby projects, and private entertainment. Charities, educational institutions, public research, safety or health organisations, environmental organisations, and government institutions may also use it.
- For **noncommercial purposes**, you may use, copy, modify, create derivative works, and share it. When sharing, you must also provide this license (or the link above) and every `Required Notice:` statement supplied by the author.
- It may not be used in commercial products or services, paid delivery, sale of access or licences, or any use expected to lead to commercial application. Obtain separate written permission from the copyright holder before commercial use.
- The agreement grants only the copyright licence and limited patent licence expressly stated. It grants no trademarks, brand names, or other unstated rights, and you may not sublicense your licence to others.
- After written notice of a violation, you must return to compliance and take practical remedial steps within 32 days, or the licences terminate immediately. A written patent-infringement claim also terminates the patent licence.
- The material is provided “as is”, without warranty to the extent permitted by law. Users bear the risks and potential losses arising from its use.
