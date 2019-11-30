# BatchMOVtoGIF

## Usage

### Multiple file conversion on macOS

1. Change directory to working directory.
2. Put MOV files (ex. something.mov) to src directory.
3. Run python script.
  `python convert.py`
4. All MOV files inside ./src will be converted and saved to ./dst

## Options

Actual command for conversion with ffmpeg is following code.

```python
command = "ffmpeg -i " + source + " -r 10 -s 960x540 -loop -1 " + dist
```
