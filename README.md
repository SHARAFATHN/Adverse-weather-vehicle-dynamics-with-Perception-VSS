# Adverse-weather-vehicle-dynamics-with-Perception-VSS
Two-stage video pipeline. Qwen2-VL-7B analyzes one frame every 10s, outputting JSON per frame (scene, objects, activity, anomaly). These are flattened into a timestamped text timeline. Qwen2.5-7B then answers questions over that text, citing timestamps. Splitting vision from reasoning means the costly VLM runs once; Q&amp;A stays cheap.
