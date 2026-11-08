# Awesome AI Clipping [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Tools and resources for AI video clipping: turning long YouTube, Twitch and Kick videos and podcasts into vertical shorts.

The list covers hosted clipping tools, the open-source building blocks behind them, platform specs, research datasets and paid clipping work. Entries are in alphabetical order inside each section.

## Contents

- [AI Clipping Tools](#ai-clipping-tools)
- [Streamer and Gaming Clippers](#streamer-and-gaming-clippers)
- [Podcast Clippers](#podcast-clippers)
- [Mobile Apps](#mobile-apps)
- [Captions and Subtitles](#captions-and-subtitles)
- [Auto-Posting and Scheduling](#auto-posting-and-scheduling)
  - [Platform APIs](#platform-apis)
- [Open-Source Projects](#open-source-projects)
  - [Downloading](#downloading)
  - [Transcription](#transcription)
  - [Editing and Processing](#editing-and-processing)
  - [Face and Object Tracking](#face-and-object-tracking)
  - [End-to-End Clippers](#end-to-end-clippers)
- [Guides](#guides)
- [Datasets and Benchmarks](#datasets-and-benchmarks)
- [Clipping as a Job](#clipping-as-a-job)

## AI Clipping Tools

- [2short.ai](https://www.2short.ai/) - Turns long videos into Shorts, TikToks and Reels with face tracking and animated subtitles.
- [ClipX](https://clipx.io/) - AI clipper that turns long YouTube, Twitch and Kick videos and podcasts into vertical shorts with captions, an editor and auto-posting.
- [Descript](https://www.descript.com/) - Text-based video and podcast editor with a feature that finds short clips in long recordings.
- [Kapwing AI Clip Maker](https://www.kapwing.com/ai/clip-maker) - Pulls clips from your footage based on a text prompt and resizes them for TikTok, Instagram and YouTube.
- [Klap](https://klap.app/) - Turns YouTube links or uploaded videos into captioned vertical clips with auto reframing and scheduled posting.
- [OpusClip](https://www.opus.pro/) - Turns long videos into short captioned clips, reframes them for vertical formats and publishes them to social platforms.
- [quso.ai](https://quso.ai/) - Formerly vidyo.ai. Turns long videos, podcasts and streams into captioned clips and schedules posts.
- [VEED AI Clip Generator](https://www.veed.io/tools/auto-video-editor/ai-clip-generator) - Online editor tool that extracts short clips from podcasts, webinars and other long videos.
- [Vizard](https://vizard.ai/) - Turns long videos into clips for TikTok, Reels and YouTube Shorts, with AI reframing, captions and an editor.

## Streamer and Gaming Clippers

- [Eklipse](https://eklipse.gg/) - Finds highlights in Twitch, Kick and YouTube streams and turns them into vertical clips.
- [Powder](https://www.powder.gg/) - Windows app that finds highlights in gameplay recordings and finished streams and turns them into clips and vertical edits.
- [StreamLadder](https://www.streamladder.com/) - Turns Twitch, YouTube and Kick streams into vertical clips, with an AI clip finder and post scheduling.

## Podcast Clippers

- [Headliner](https://www.headliner.app/) - Podcast video tool that makes audiograms and AI-selected captioned clips from episodes.
- [Podsqueeze](https://podsqueeze.com/) - Turns podcast episodes into transcripts, show notes, clips and audiograms.
- [Riverside Magic Clips](https://riverside.com/magic-clips) - Finds highlights in recordings and turns them into short clips with presets for YouTube, TikTok and Instagram.
- [Swell AI](https://www.swellai.com/) - Podcast tool for transcripts, show notes and suggested clip sections.

## Mobile Apps

- [CapCut](https://www.capcut.com/) - Video editor for mobile, desktop and web with automatic captions.
- [Captions](https://captions.ai/) - AI video editor app for iOS and Android.
- [OpusClip for iOS](https://www.opus.pro/mobile-app) - iPhone app that turns long videos into short captioned clips.

## Captions and Subtitles

- [Submagic](https://www.submagic.co/) - Caption editor with styled captions in many languages and a feature that cuts long videos into shorts.
- [Zubtitle](https://zubtitle.com/) - Online editor that adds captions, headlines and branding to talking videos and resizes them for each platform.

## Auto-Posting and Scheduling

- [Buffer](https://buffer.com/) - Social media scheduler that posts to TikTok, Instagram, YouTube Shorts and other networks.
- [Later](https://later.com/) - Social media scheduler that posts to TikTok, Instagram, YouTube Shorts, Snapchat and other networks.
- [Metricool](https://metricool.com/) - Scheduling and analytics tool for TikTok, YouTube, Instagram, Twitch and other networks.

### Platform APIs

- [Instagram Content Publishing](https://developers.facebook.com/docs/instagram-platform/content-publishing) - Official docs for publishing Reels and other posts through the Instagram API.
- [TikTok Content Posting API](https://developers.tiktok.com/docs/en/content-posting-api-get-started) - Official guide to posting videos directly to a creator's TikTok account.
- [YouTube Data API uploads](https://developers.google.com/youtube/data/guides/uploading_a_video) - Official guide and Python sample for uploading videos through the YouTube Data API.

## Open-Source Projects

### Downloading

- [Streamlink](https://github.com/streamlink/streamlink) - Command-line tool that pipes live streams from Twitch and other services into a video player or file.
- [TwitchDownloader](https://github.com/lay295/TwitchDownloader) - Downloads Twitch VODs, clips and chat, and renders chat as video.
- [yt-dlp](https://github.com/yt-dlp/yt-dlp) - Command-line audio and video downloader for YouTube and many other sites.

### Transcription

- [faster-whisper](https://github.com/SYSTRAN/faster-whisper) - Whisper reimplementation on CTranslate2 for faster transcription.
- [NeMo Speech](https://github.com/NVIDIA-NeMo/Speech) - NVIDIA toolkit for speech recognition and speech models, including Parakeet and Canary.
- [pyannote.audio](https://github.com/pyannote/pyannote-audio) - Speaker diarization toolkit that tells who spoke when.
- [whisper-timestamped](https://github.com/linto-ai/whisper-timestamped) - Whisper with word-level timestamps and confidence scores.
- [Whisper](https://github.com/openai/whisper) - OpenAI speech recognition model and code (MIT).
- [whisper.cpp](https://github.com/ggml-org/whisper.cpp) - Port of OpenAI Whisper to C/C++.
- [WhisperX](https://github.com/m-bain/whisperX) - Whisper with word-level timestamps and speaker diarization.

### Editing and Processing

- [auto-editor](https://github.com/WyattBlue/auto-editor) - Cuts silent parts from video by audio loudness and exports to Premiere Pro, DaVinci Resolve and Final Cut Pro.
- [FFmpeg](https://ffmpeg.org/) - Command-line tools and libraries to decode, encode, cut, crop and filter audio and video.
- [LosslessCut](https://github.com/mifi/lossless-cut) - Desktop app for lossless trimming and cutting of video and audio files.
- [MoviePy](https://github.com/Zulko/moviepy) - Python library for video editing.
- [OBS Studio](https://github.com/obsproject/obs-studio) - Software for live streaming and screen recording.
- [PySceneDetect](https://github.com/Breakthrough/PySceneDetect) - Python and OpenCV tool that detects scene cuts and transitions.

### Face and Object Tracking

- [InsightFace](https://github.com/deepinsight/insightface) - Face detection and analysis toolkit. Check the licence of the model weights as well as the code.
- [MediaPipe](https://github.com/google-ai-edge/mediapipe) - Google on-device ML solutions for media, including face detection and landmarks.
- [Ultralytics](https://github.com/ultralytics/ultralytics) - YOLO models for object detection, pose estimation and tracking (AGPL-3.0).

### End-to-End Clippers

- [AI-Youtube-Shorts-Generator](https://github.com/Anil-matcha/AI-Youtube-Shorts-Generator) - Python pipeline that turns YouTube videos into 9:16 shorts with Whisper transcription, LLM highlight selection and face-tracked crops (MIT).

## Guides

- [Google Ads square and vertical video](https://support.google.com/google-ads/answer/9128498) - Official guide to 1:1 and 9:16 video ads, with safe-zone guidance.
- [Meta Instagram Reels ad specs](https://www.facebook.com/business/ads-guide/update/video/instagram-reels) - Official Reels specs: ratio, resolution and the safe zone at the top, bottom and sides.
- [Safe Zones and Aspect Ratios for the For You Feed](https://clipx.io/academy/safe-zones-aspect-ratios-for-you-feed) - How to frame vertical video so platform buttons and text do not cover key content on Shorts, TikTok and Reels.
- [TikTok In-Feed Ads specs](https://ads.tiktok.com/resources/help/article/tiktok-auction-in-feed-ads) - Official aspect ratios, minimum resolutions and durations for TikTok in-feed video.
- [YouTube Shorts: get started](https://support.google.com/youtube/answer/10059070) - Official help on how to create Shorts.
- [YouTube Shorts: three-minute Shorts](https://support.google.com/youtube/answer/15424877) - Official help on which videos count as Shorts and the rules for Shorts up to three minutes.
- [YouTube Shorts: upload from a computer](https://support.google.com/youtube/answer/12779649) - Official help on Shorts uploads, length and aspect ratio.

## Datasets and Benchmarks

- [Mr. HiSum](https://github.com/MRHiSum/MR.HiSum) - About 32,000 YouTube-8M videos with highlight scores from YouTube "Most replayed" data (NeurIPS 2023).
- [QVHighlights](https://github.com/jayleicn/moment_detr) - YouTube videos with text queries, moment annotations and clip saliency scores, released with Moment-DETR (NeurIPS 2021).
- [SumMe and TVSum mirror](https://zenodo.org/records/4884870) - Archive of the original SumMe and TVSum videos with extracted GoogleNet features.
- [TVSum](https://github.com/yalesong/tvsum) - 50 YouTube videos with shot-level importance scores from 20 annotators each (CVPR 2015).
- [YouTube Highlights](https://github.com/aliensunmin/DomainSpecificHighlight) - Raw and edited YouTube video pairs in six domains for highlight ranking (ECCV 2014).

## Clipping as a Job

- [Content Rewards](https://contentrewards.com/) - Platform where brands fund campaigns and creators get paid for posts by views or per post.
- [Whop Content Rewards](https://docs.whop.com/memberships-and-access/third-party-apps/content-rewards) - Whop tool where brands pay clippers and other creators for the views their approved posts get.

## Contributing

Contributions are welcome. Read the [contribution guidelines](CONTRIBUTING.md) first.

---

Maintained by the team at ClipX (clipx.io). PRs welcome; we list competitors on the same terms.
