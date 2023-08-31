# ffmpeg-converter

My bash script to convert video by predefined mode to mkv container. Works best custom context menu in a file managers.

My predifined modes work specifically with av1 and vorbis codec.

# Usage
```bash
ffmpeg-convert <mode> [videos]
```

# Predefined modes
| Mode  | Description |
| :-------------: | ------------- |
| av1_40  | Encode to av1 with -cfr 40  |
| av1_40_FHD  | Encode to av1 with -cfr 40 and scale to fullHD  |
| av1_40_scale  | Encode to av1 with -cfr 40 and scale to fullHD preserving aspect ratio |
| av1_40_scale_l  | Encode to av1 with -cfr 40 and scale to fullHD preserving aspect ratio, <br>potentially lowering one dimension below FHD resolution |
