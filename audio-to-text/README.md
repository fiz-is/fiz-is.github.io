# Audio to Text preview

This is a standalone, one-page, browser-based transcription experiment hosted under `/audio-to-text/` for visual and functional testing. It does not require an account, backend, API key or payment.

Audio is decoded and transcribed locally with Whisper Tiny through Transformers.js. Model weights and runtime are downloaded from third-party CDNs on first use. Supports browser-decodable audio and some video codecs; current limits are 75 MB and 15 minutes. Results can be edited, copied or downloaded as TXT.

## Launch gate

This version is intentionally `noindex,nofollow`. Validate real MP3/WAV transcription, first-run model download, Chrome/Safari performance, mobile usability and privacy disclosures before using a production domain. Browser-side Tiny transcription may be slow or inaccurate for long/noisy recordings. No Google Analytics or tracking is installed.

The preview does not alter or link from the parent GitHub Pages homepage.
