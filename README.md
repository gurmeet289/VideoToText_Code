# VideoToText_Code
Can convert your video file (like mp4,mkv) into text 

Library installed-
1)	IBM Watson
2)	Python ffmpeg


# 1. Extract Audio

	#Here we are calling the moviepy library to convert the video to mkv
	#Than converted the mkv file to wav file

# 2. Setup STT Service
	
	#Navigate to https://cloud.ibm.com/catalog?category=ai#servicesv
	#Than click on speech to text 
	#Than check the box and click on create and than navigate to manage to get your api key and url

# 3. Compress and Split Audio

	#With the help of ffmpeg library converted the wav file to mp3 than from .mp3 file to segment of files with 360sec

# 4. Perform Conversion

	#Used the model 'en-AU_NarrowbandModel' 
	#appended the mp3 files
	#appended the text

# 5. Save to output file

	#Save the text to the output file

