This dataset contains the shot cut groundtruth for all 5 videos of the TestSet.
Each file contains a list of frame numbers that correspond to shot boundaries. Each number marks the beginning of a new shot and the frame number is the first frame of the new shot.

Example:

If the file looks like this:
1
25
340

we have 3 shots in the clip.
Shot 1: 1   - 24
Shot 2: 25  - 339
Shot 3: 340 - last frame

The filenames are in the same format than the video files, but the extension is *.txt.