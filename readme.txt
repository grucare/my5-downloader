Steps

I. Installation
 1. Install Python (3.6 recommended)
 2. run `pip install -r requirements.txt`
 3. (If not on windows)
  - On macOs
    run `brew install yt-dlp ffmpeg mp4decrypt`
  - On Linux
    run `sudo apt install yt-dlp ffmpeg mp4decrypt`

II. Config
  1. Open `config.json` and fill in the optional fields if you want to change the default values
  2. (If on windows)
    set USE_BIN_DIR=True

III. Run
  1. run `python my5_loader.py`
  2. 
    - Select yes (using allows) if you want to search with a keyword and hit enter
    - Select no (using allows) if you want to input the direct url instead
  3. Enter the keyword on next step and hit enter
  4. 
    - Select confirm if the results are correct and hit enter
    - Select no if the results are not correct and hit enter to return to search
  5. The results will be a list of all episodes, select the ones you need by checking the boxes (using space)
  6. Hit enter to start downloading
  7. Wait for the download to finish
  8. The downloaded files will be in the `downloads` folder

You can find downloaded files on `downloads` folder, not tmp folder.
The tmp folder is just for remerging by itself. :)

