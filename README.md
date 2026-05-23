# ArrhythmiaGuard — Real-Time Cardiac Arrhythmia Detection

An edge AI wearable that detects cardiac arrhythmia in real time on ESP32-S3 
— no internet, no cloud, full inference on-device.

## Hardware
- ESP32-S3 N16R8 (16MB Flash, 8MB PSRAM)
- AD8232 ECG Sensor
- SSD1306 OLED Display
- Buzzer + LEDs

## Key Results
- AUC: 0.908 validated on 44,054 heartbeats
- Model size: 30.4 KB (TFLite INT8 quantized)
- Custom feature: rr_dev_ctx — ranked #1 by SHAP analysis
- Fully offline inference — no cloud dependency

## Tech Stack
TFLite Micro · 1D CNN · ESP-IDF · Embedded C · Signal Processing


