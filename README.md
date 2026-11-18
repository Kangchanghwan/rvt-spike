# rvt-spike

Browser-only spike: live text detection on the camera preview, line boxes grouped into paragraph blocks, tap a block to crop it and run OCR in the background, text appended in tap order.

- Demo: https://kangchanghwan.github.io/rvt-spike/
- Engine: [ppu-paddle-ocr](https://github.com/PT-Perkasa-Pilar-Utama/ppu-paddle-ocr) 6.7.1 (PP-OCRv6 tiny) on onnxruntime-web, loaded from jsDelivr
- Images and text stay in the browser. Only the app and model files are downloaded.
- `sample.jpg` is a synthetic image for testing without a camera.
