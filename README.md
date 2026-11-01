# Burma Cat engines

Engine files for the Burma Cat phone app. The app downloads each file once, from this repository's releases, and keeps
it only when its SHA-256 matches the one written into the app. Nothing here needs to be downloaded by hand.

| Release | Files | Licence |
|---|---|---|
| `engines-1` | `voice-1-encoder.z`, `voice-1-prenet.z`, `voice-1-step.z`, `voice-1-voice.bin` (the voice engine) | CC0 1.0 (public domain) |
| `engines-1` | `voice-1-vocoder.z` (the voice engine's vocoder) | MIT: Copyright (c) 2024 KdaiP |
| `engines-1` | `captions-1-small.bin` (the caption engine) | MIT: Copyright (c) 2022 OpenAI; Copyright (c) 2023-2024 The ggml authors |

`.z` files are packed with raw deflate; the app unpacks them.

## MIT License (the copyright lines above)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated
documentation files (the "Software"), to deal in the Software without restriction, including without limitation the
rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit
persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the
Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE
WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR
OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
