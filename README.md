#AUDIO CONVERTER
This project is hosted privately. For more information, please contact the owner.



My project is an audio conversion tool developed using a Windows Forms application in C#. The application allows users to select audio files, process them, and convert them into different formats along with duration calculation and generating the details in excel. A key focus is on reducing the file size without compromising on quality. The application supports various audio file formats such as .mp3,.wav,.wma,.m4a,.dss,.mp4 and enables batch processing. It incorporates UI enhancements using Guna.UI2.WinForms and handles file operations and conversions through FFMpegCore.

TECHNOLOGIES USED:

*Windows Forms Application (C#)*:

Purpose: The core of my application, providing a graphical user interface (GUI) for users to interact with the audio conversion functionalities.
Features:
Allows users to select individual files or entire folders for processing.
Handles file selection, folder browsing, and file operations (e.g., saving, overwriting).
Manages the flow of conversion processes, including UI updates and user notifications.
Ensures that the layout adjusts dynamically based on the window size, providing a responsive user experience.

*Guna.UI2.WinForms*:

Purpose: A UI toolkit for Windows Forms that provides enhanced visual elements and components.
Application:
Used to create a modern and visually appealing interface for the application.
Provides custom controls, animations, and themes to improve the user experience.
Helps in designing a responsive and attractive UI that adjusts to different screen sizes and resolutions.

*FFMpegCore*:

Purpose: A .NET wrapper for the FFMpeg multimedia framework, enabling audio and video processing within .NET applications.
Application:
Handles the conversion of audio files between different formats (e.g., MP3 to WAV, WAV to WAV with different settings).
Supports the adjustment of bitrate, sample rate, and other audio parameters to achieve the desired output quality and file size.
Manages file overwriting by prompting the user for confirmation before proceeding with conversions that might overwrite existing files.
Resolves issues related to file handling, such as ensuring that files are not overwritten while still being processed.

*File Handling and Overwriting Logic*:

Purpose: Ensures that the application handles files efficiently, especially during conversions.
Application:
Implements logic to check if a file already exists and prompts the user for overwriting permission.
Utilizes temporary files to avoid conflicts where FFMpeg might attempt to overwrite files that are still being read.
Facilitates batch processing by ensuring that the overwrite prompt appears only once for multiple file conversions, streamlining the user experience.


