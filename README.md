# Claude animation setup

Reference repos for making videos and animations with Claude, cloned into `repos/` (ignored by git).

Requirements: Node.js 22+, git, ffmpeg (and git-lfs for HyperFrames).

| Repo | What it's for |
|---|---|
| [PDoomVideo](https://github.com/JohnHeibel/PDoomVideo) | Source of the Opus 5.5 music video "I'm Upping My P(doom)", a full worked example of a Claude-made animation |
| [ClaudeAnimationBase](https://github.com/JohnHeibel/ClaudeAnimationBase) | Starter kit (p5.js + p5.brush, ANIMATION_GUIDE.md) for animating the Clawd character into an MP4 |
| [claude-animation-skill](https://github.com/buildwithhanif/claude-animation-skill) | Claude skill for hand-drawn-looking 2D animation as code (Node + ffmpeg, rigs, synthesized sound) |
| [hyperframes](https://github.com/heygen-com/hyperframes) | HeyGen's framework for writing HTML compositions and rendering them to video, built for agents |
| [Battle-of-Austerlitz-Film](https://github.com/WinterArc21/Battle-of-Austerlitz-Film) | A 5-minute historical film made entirely in code (WebGL frames, synthesized audio and narration) |
| [awesome-ai-motion](https://github.com/guanmo-ai/awesome-ai-motion) | Curated gallery of 400+ AI-made videos and animations, with creator prompts and sources |
| [awesome-opus-5-5-videos](https://github.com/athemeroy/awesome-opus-5-5-videos) | Curated, source-linked list of videos made with Claude 5.5 models |

## Re-create

```sh
mkdir -p repos && cd repos
git clone https://github.com/JohnHeibel/PDoomVideo
git clone https://github.com/JohnHeibel/ClaudeAnimationBase
git clone https://github.com/buildwithhanif/claude-animation-skill
GIT_LFS_SKIP_SMUDGE=1 git clone https://github.com/heygen-com/hyperframes
git clone https://github.com/WinterArc21/Battle-of-Austerlitz-Film
git clone https://github.com/guanmo-ai/awesome-ai-motion
git clone https://github.com/athemeroy/awesome-opus-5-5-videos
```
