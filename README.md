# Generative Music Playground by Perth Machine Learning Group
## Description
Links for music + machine learning. 
This is a curated list of links for people who want to explore generating music with deep learning. 

Check https://www.meetup.com/Perth-Machine-Learning-Group/events for updates on in-person meetups


Recommended|   |   |   |   |   |   |
---------------|---|---|---|---|---|---|
**Name**                 |**Description**|**Demo**|**Code**|**Paper**|**Suitable for**|**Released**|
**Generating Audio(.wav or .mp3 files)**
[**MusicFX (Google)**](https://aitestkitchen.withgoogle.com/tools/music-fx)|Generate music from text|[Blog](https://google-research.github.io/seanet/musiclm/musicfx/)<br><br>[Audio](https://google-research.github.io/seanet/musiclm/examples/)<br></br>[Youtube](https://www.youtube.com/watch?v=g6FRkAbZPQo)||[Paper](https://arxiv.org/abs/2301.11325)|Non-coders|December 2023|
[**Stable Audio (Stability AI)**](https://stability.ai/stableaudio)|Generate music and sound effects from text.|||[Research Blog](https://stability.ai/research/stable-audio-efficient-timing-latent-diffusion)<br><br>[Github](https://github.com/Stability-AI/stable-audio-tools)<br><br>|Non-coders|September 2023|
[**MusicGen (Meta AI)**](https://github.com/facebookresearch/audiocraft)|Generate music from text (controllable)|[Hugging Face Spaces](https://huggingface.co/spaces/facebook/MusicGen)<br><br>[Audio](https://huggingface.co/papers/2306.05284)|[Google Colab](https://colab.research.google.com/drive/1-Xe9NCdIs2sCUbiSmwHXozK6AAhMm7_i?usp=sharing)|[Paper](https://arxiv.org/abs/2306.05284)|Non-coders|June 2023|
[Make An Audio (ByteDance)](https://github.com/Text-to-Audio/Make-An-Audio)||[Github Pages](https://text-to-audio.github.io/)<br><br>[Hugging Face Spaces](https://huggingface.co/spaces/AIGC-Audio/Make_An_Audio)|[Github](https://github.com/Text-to-Audio/Make-An-Audio)|[Paper](https://text-to-audio.github.io/paper.pdf)||June 2023|
[Harmonai (Stability AI)](https://www.harmonai.org/)|Generate novel audio from pretrained models or fine-tune with your own audio tracks|[Hugging Face Spaces](https://huggingface.co/spaces/harmonai/dance-diffusion)<br /><br />[24/7 Youtube stream](https://www.youtube.com/watch?v=kJgxC9d0p50)|[Dance Diffusion](https://colab.research.google.com/github/Harmonai-org/sample-generator/blob/main/Dance_Diffusion.ipynb)<br /><br />[Fine-tuning Dance Diffusion](https://colab.research.google.com/github/Harmonai-org/sample-generator/blob/main/Finetune_Dance_Diffusion.ipynb)<br></br>[Github](https://github.com/Harmonai-org/sample-generator)|[Guide](https://drive.google.com/file/d/1nEFEpK27v0nytNXmmYQb06X_RI6kKPve/view)<br /><br />[WandB article](https://wandb.ai/wandb_gen/audio/reports/A-Gentle-Introduction-to-Dance-Diffusion--VmlldzoyNjg1Mzky)|Non-coders (Hugging Face), coders (Google Colab)|Oct 2022|
[Jukebox (OpenAI)](https://openai.com/blog/jukebox/)|Choose artist, genre, lyrics, and generate audio|[Audio](https://jukebox.openai.com/)|[Google Colab](https://colab.research.google.com/github/openai/jukebox/blob/master/jukebox/Interacting_with_Jukebox.ipynb)|[Paper](https://arxiv.org/abs/2005.00341)|Coders (Google Colab)|April 2020|
**Generating MIDI(.mid files)**
[**MuseNet (OpenAI)**](https://openai.com/blog/musenet)|Generate new melodies(MIDI file). Scroll down to "Compose in the style of Chopin", generate a continuation of that song, and download the MIDI |[Audio](https://soundcloud.com/openai_audio/sets/musenet)|||Non-coders|Apr 2019|
[**Piano Transformer (Google)**](https://magenta.tensorflow.org/piano-transformer)|Generate piano MIDI notes from scratch or from a starting MIDI file|[Audio](https://magenta.tensorflow.org/assets/piano_transformer/clair_de_lune_continuation.mp3)|[Google Colab](https://colab.research.google.com/notebooks/magenta/piano_transformer/piano_transformer.ipynb)||Non-coders|Sep 2019|
**Other resources**
**MIDI(.mid files)**
[Basic Pitch (Spotify)](https://basicpitch.spotify.com)|Audio-to-MIDI converter with pitch bend detection. Record with your device, or upload an audio file to obtain a MIDI transcription||||Non-coders|June 2022|
[Hello Magenta (Google)](https://colab.research.google.com/notebooks/magenta/hello_magenta/hello_magenta.ipynb)|Introduction to Google Magenta - includes MelodyRNN and MusicVAE||[Google Colab](https://colab.research.google.com/notebooks/magenta/hello_magenta/hello_magenta.ipynb)<br /><br />[Magenta.js](https://hello-magenta.glitch.me/)||Coders|
[Music Autobot](https://musicautobot.com)|Generate MIDI - song generation, harmonization, generating melodies, and remixing existing songs.||||Non-coders,non-musicians|
[FreeMIDI](https://freemidi.org/)|Download free MIDI files here||||Non-coders,non-musicians|
[Online Sequencer](https://onlinesequencer.net/)|Make your own MIDI file from scratch||||Non-coders,non-musicians|
[Magenta Studio (Google)](https://magenta.tensorflow.org/studio)|Compose multitrack melodies/chords in Ableton Live (music production software)||||Ableton users, music producers|
**Audio(.wav or .mp3 files)**
[Spleeter by Deezer](https://deezer.io/releasing-spleeter-deezer-r-d-source-separation-engine-2b88985e797e)|Music source separation library. Upload an audio file, isolate vocals or instrumental||[Github](https://github.com/deezer/spleeter)<br /><br />[Google Colab](https://colab.research.google.com/github/deezer/spleeter/blob/master/spleeter.ipynb)||Non-coders, coders|Nov 2019|
[MusicVAE (Google)](https://magenta.tensorflow.org/music-vae)|Generate audio, interpolate between 2 different melodies or drum beats |[Audio](https://magenta.tensorflow.org/assets/music_vae/mel_2bar-b2m.mp3)|[Google Colab](https://colab.research.google.com/notebooks/magenta/music_vae/music_vae.ipynb)|[Paper](https://arxiv.org/abs/1806.00195)|Non-coders|
[GANSynth](https://magenta.tensorflow.org/gansynth)|Upload a MIDI file,download an audio file of the interpolation between different instruments|[Audio](https://storage.googleapis.com/magentadata/papers/gansynth/index.html)|[Google Colab](https://colab.research.google.com/notebooks/magenta/gansynth/gansynth_demo.ipynb)|[Paper](https://openreview.net/forum?id=H1xQVn09FX)|Non-coders|
**Introduction to Music**||||||
[Chrome Music Lab](https://musiclab.chromeexperiments.com/Experiments)||||||
[Learning Music with Ableton](https://learningmusic.ableton.com/)||||||
[Learning Synths (Ableton)](https://learningsynths.ableton.com/)||||||
[Music Theory](https://www.musictheory.net/lessons/)||||||
**Miscellaneous**||||||
[Microsoft - Muzic](https://github.com/microsoft/muzic)|Research project on AI music that empowers music understanding and generation with deep learning and artificial intelligence||[Github](https://github.com/microsoft/muzic)<br><br>[Github Pages](https://ai-muzic.github.io/)|||
[NVIDIA - Maxine Audio Effects SDK](https://github.com/NVIDIA/MAXINE-AFX-SDK)|API Source Code and Sample Applications. Various audio effects for broadcast use cases with real-time audio processing||[Github](https://github.com/NVIDIA/MAXINE-AFX-SDK)<br><br>[NVIDIA Broadcast SDK](https://www.nvidia.com/en-au/geforce/broadcasting/broadcast-sdk/resources/)<br><br>[NVIDIA NGC](https://catalog.ngc.nvidia.com/orgs/nvidia/teams/maxine/collections/maxine)|||
[PapersWithCode - Music Generation](https://paperswithcode.com/task/music-generation)|Papers, code, evaluation papers, datasets|||||
[PapersWithCode - Music Source Separation](https://paperswithcode.com/task/music-source-separation)|Papers, code, evaluation papers, datasets|||||
[Talks/presentations by Google Magenta](https://magenta.tensorflow.org/talks)|||||
[Python In Music](https://wiki.python.org/moin/PythonInMusic)|List of music software written in Python,music software supporting Python,music programming in Python, etc.|||||
[Github - Deep Learning for Music Generation by Carlos Hernández-Oliván](https://github.com/carlosholivan/DeepLearningMusicGeneration)|List of articles related to deep learning applied to music generation|||||
[Github - Deep Learning papers in music by Yann Bayle](https://github.com/ybayle/awesome-deep-learning-music)|List of articles related to deep learning applied to music|||||
[TorchAudio](https://pytorch.org/audio/stable/index.html)|Library for audio and signal processing with PyTorch|||||
[Deep Learning with audio thread - Fast.AI forum](https://forums.fast.ai/t/deep-learning-with-audio-thread/38123)|List of links related to deep learning applied to audio|||||
[International Society for Music Information Retrieval(ISMIR)](https://www.ismir.net/resources/)|Links to datasets, educational material, tutorials, software related to music information retrieval|||||
[NLP4MusA Youtube channel](https://www.youtube.com/channel/UCtWGAGz6I_1aRetS8U4rYcA)|Natural Language Processing for Music and Audio - Zoom talks by NLP+music researchers|||||
[SigSep](https://sigsep.github.io/literature/)|Open resources for music source separation. Datasets, code, literature, tutorials||[Github](https://github.com/sigsep/open-unmix-pytorch)|||
[Google Experiments - Music](https://experiments.withgoogle.com/search?q=music)||||||
[List of examples of music generated by our group](https://docs.google.com/spreadsheets/d/1UaZt1CDtC_UegLOfZwn2-SHIsvfXWAaMjEfhmdx8dvI/edit?usp=sharing)|Add your link to your generated music here|||||
