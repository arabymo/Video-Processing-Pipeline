# YouTube Video Processor

This project provides a pipeline for downloading YouTube videos, splitting them into equal parts, extracting frames, and performing various operations on the frames, such as annotating frame numbers and selecting random frames for further analysis.

## Features

1. **Download Videos from YouTube**: Utilizes the `pytubefix` library to download videos directly from YouTube.
2. **Split Videos into Equal Parts**: The downloaded video is split into equal-length segments (4 segments by default).
3. **Extract Frames**: All frames from each segment are extracted.
4. **Organize Frames**: Each segment's frames are stored in a separate folder.
5. **Annotate Frames**: Frame numbers are written directly onto each image using the `cv2` library.
6. **Random Frame Selection**: Selects 4 random frames from each folder for further processing or analysis.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/arabymo/Video-Processing-Pipeline.git
   cd Video-Processing-Pipeline
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt

# Random Frames Extracted
## First Frame
![frame_10084](https://github.com/user-attachments/assets/59dbd3df-5112-45c7-9a50-8040efc5ec72)
## Second Frame
![frame_33377](https://github.com/user-attachments/assets/161c18b9-a6b6-4fc6-be3f-9585178e1dfc)
## Third Frame
![frame_67634](https://github.com/user-attachments/assets/285e6a23-c687-4b9b-a70e-0207987980ac)
## Fourth Frame
![frame_101005](https://github.com/user-attachments/assets/5b09e43b-1a60-4373-8f77-af6ec018615f)





