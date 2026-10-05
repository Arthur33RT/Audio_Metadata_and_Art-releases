# Audio Metadata & Art

A Windows application that scans your local music library and retrieves
artwork from **fanart.tv** and metadata from **TheAudioDB**, **Last.fm**, and
**MusicBrainz**. Matching is anchored on MusicBrainz artist and release-group IDs.

This repository hosts **downloadable releases only**. 

## Download

Get the latest version from https://github.com/git-arthur33/Audio_Metadata_and_Art-releases/releases 
Download the `.zip` file, extract it to any folder, and run `AudioMetadata.App.exe`.
No installer is needed.

## Requirements

- Windows 10 or 11, 64-bit
- [.NET 8 Desktop Runtime (x64)](https://dotnet.microsoft.com/download/dotnet/8.0)
  (free from Microsoft). Under ".NET Desktop Runtime", choose **x64**.
  The plain ".NET Runtime" is not enough.
- *Optional, for animated artwork preview:* FFmpeg 7.x **shared** libraries.
  Download them yourself and point the app at the folder in Options.
  Other FFmpeg versions may not work.
- Your own free API keys for the services you want to use
  (fanart.tv, TheAudioDB, Last.fm). Enter them in the app's Options.
  No keys are included.

## Notes

- Settings and API keys are stored locally on your computer.
- This is an early release (v0.1.x). Expect rough edges.

## License and terms

The Audio Metadata & Art application is released under the [MIT License](LICENSE).
Third-party components keep their own licenses.

