07 AI IMAGE, VIDEO & AUDIO
==========================

Skills that generate media with AI: images (GPT Image, FLUX, Nano Banana, Qwen), video (Veo,
Seedance, Higgsfield), voice and music (ElevenLabs), avatars, podcasts, upscaling and editing.

60 skills in this folder. Each sub-folder contains a SKILL.md (the instructions an AI agent reads) plus any supporting files.
To use a skill in Claude Code / Claude Cowork, copy its folder into your project's .claude/skills/ directory (or ~/.claude/skills/ for all projects).
Search all skills in plain English with the 'Skills Search.html' file in the top-level folder.

QUICK LIST
----------
  - ai-avatar-video
  - ai-content-pipeline
  - ai-image-generation
  - ai-marketing-videos
  - ai-music-generation
  - ai-podcast
  - ai-podcast-creation
  - ai-product-photography
  - ai-video-generation
  - ai-voice-cloning
  - background-removal
  - character-design-sheet
  - dialogue-audio
  - elevenlabs-dialogue
  - elevenlabs-dubbing
  - elevenlabs-music
  - elevenlabs-sound-effects
  - elevenlabs-stt
  - elevenlabs-tts
  - elevenlabs-voice-changer
  - elevenlabs-voice-isolator
  - explainer-video-guide
  - flux-image
  - generate-image
  - google-veo
  - gpt-image
  - happyhorse
  - higgsfield-brandkit
  - higgsfield-generate
  - higgsfield-marketplace-cards
  - higgsfield-product-photoshoot
  - higgsfield-soul-id
  - higgsfield-video-explainer
  - higgsfield-youtube-thumbnail
  - image
  - image-manipulation-image-magick
  - image-to-video
  - image-upscaling
  - nano-banana
  - nano-banana-2
  - nano-banana-pro-openrouter
  - nanobanana
  - og-image-design
  - p-image
  - p-video
  - p-video-avatar
  - product-photography
  - qwen-image-2
  - qwen-image-2-pro
  - remotion
  - remotion-render
  - seedance
  - speech-to-text
  - storyboard-creation
  - talking-head-production
  - text-to-speech
  - video
  - video-ad-specs
  - video-prompting-guide
  - youtube-thumbnail-design

SKILL DETAILS
-------------

[ai-avatar-video]
    Source: inference.sh superpowers
    What it does: Creates talking-head videos featuring an AI presenter who speaks your script
    with synced lips, using built-in voices or your own audio.
    When to use: You want a spokesperson or explainer video without filming a real person.
    Search terms: ai avatar, talking head, ai presenter, lip sync, heygen alternative, synthesia
    alternative, spokesperson video, ugc video, explainer video, digital human, virtual
    presenter
    Original description: Create AI avatar and talking head videos via inference.sh CLI.
    Recommended: P-Video-Avatar (fastest, cheapest, built-in TTS). Also: OmniHuman, Fabric,
    PixVerse. Audio: Inworld TTS-2 (100+ languages, emotion steering for characters),
    ElevenLabs, Kokoro. Capabilities: audio-driven avatars, text-to-avatar, lipsync videos,
    talking head generation, virtual presenters, UGC content. Use for: AI presenters, explainer
    videos, virtual influencers, dubbing, marketing videos, UGC ads, gaming avatars, NPC
    dialogue. Triggers: ai avatar, talking head, lipsync, avatar video, virtual presenter, ai
    spokesperson…

[ai-content-pipeline]
    Source: inference.sh superpowers
    What it does: Chains multiple AI tools together to produce finished content, for example
    generating an image, animating it, adding a voiceover, and mixing in music.
    When to use: You want to automate producing videos or social posts from start to finish.
    Search terms: content automation, video workflow, ai content factory, youtube videos, social
    media content, batch content, multi step, content at scale, marketing materials, pipeline
    Original description: Build multi-step AI content creation pipelines combining image, video,
    audio, and text. Workflow examples: generate image -> animate -> add voiceover -> merge with
    music. Tools: FLUX, Veo, Kokoro TTS, OmniHuman, media merger, upscaling. Use for: YouTube
    videos, social media content, marketing materials, automated content. Triggers: content
    pipeline, ai workflow, content creation, multi-step ai, content automation, ai video
    workflow, generate and edit, ai content factory, automated content creation, ai production
    pipeline, media pipeline, content at scale

[ai-image-generation]
    Source: inference.sh superpowers
    What it does: Generates images from text descriptions using over 50 AI models including GPT-
    Image, FLUX, and Gemini, and can edit, upscale, or restyle existing images.
    When to use: You need artwork, product mockups, or social graphics without hiring a
    designer.
    Search terms: ai image, generate image, text to image, midjourney alternative, dall-e, flux,
    gemini image, ai art, create picture, image generator, stable diffusion, marketing visuals
    Original description: Generate AI images with GPT-Image-2, FLUX, Gemini, Grok, Seedream,
    Reve and 50+ models via inference.sh CLI. Models: GPT-Image-2, FLUX Dev LoRA, FLUX.2 Klein
    LoRA, Gemini 3 Pro Image, Grok Imagine, Seedream 4.5, Reve, ImagineArt. Capabilities: text-
    to-image, image-to-image, inpainting, LoRA, image editing, upscaling, text rendering. Use
    for: AI art, product mockups, concept art, social media graphics, marketing visuals,
    illustrations. Triggers: flux, image generation, ai image, text to image, stable diffusion,
    generate image, ai art, midjourney alternative, dall-e alternative, text2img, t2i, i…

[ai-marketing-videos]
    Source: inference.sh superpowers
    What it does: Produces marketing videos such as product demos, testimonials, explainers, and
    social ads using AI video and voiceover models.
    When to use: You need an ad or promo video for Facebook, YouTube, Instagram, or TikTok.
    Search terms: marketing video, ad video, promo video, commercial, product video, facebook
    ad, youtube ad, tiktok ad, instagram ad, launch video, brand video
    Original description: Create AI marketing videos for ads, promos, product launches, and
    brand content. Models: Veo, Seedance, Wan, FLUX for visuals, Kokoro for voiceover. Types:
    product demos, testimonials, explainers, social ads, brand videos. Use for: Facebook ads,
    YouTube ads, product launches, brand awareness. Triggers: marketing video, ad video, promo
    video, commercial, brand video, product video, explainer video, ad creative, video ad,
    facebook ad video, youtube ad, instagram ad, tiktok ad, promotional video, launch video

[ai-music-generation]
    Source: inference.sh superpowers
    What it does: Creates original songs, instrumentals, jingles, and soundtracks from a text
    description, with commercial-use licensing available.
    When to use: You need royalty-free background music or a jingle for a video, podcast, or ad.
    Search terms: ai music, generate song, background music, jingle, soundtrack, royalty free
    music, suno alternative, udio alternative, elevenlabs music, text to music, beat maker
    Original description: Generate AI music and songs with ElevenLabs, Diffrythm, Tencent Song
    Generation via inference.sh CLI. Models: ElevenLabs Music (up to 10 min, commercial
    license), Diffrythm (fast song generation), Tencent Song Generation (full songs with
    vocals). Capabilities: text-to-music, song generation, instrumental, lyrics to song,
    soundtrack creation. Use for: background music, social media content, game soundtracks,
    podcasts, royalty-free music. Triggers: music generation, ai music, generate song, ai
    composer, text to music, song generator, create music with ai, suno alternative, udio
    alternative, ai s…

[ai-podcast]
    Source: inference.sh superpowers
    What it does: Builds a full multi-person video podcast from scratch: creates the hosts,
    voices their lines, animates them as talking heads, and stitches the clips together.
    When to use: You want a podcast-style video conversation without real hosts or cameras.
    Search terms: ai podcast, video podcast, talking heads, multi speaker, virtual hosts,
    conversation video, avatar podcast, podcast maker, ai hosts
    Original description: Generate multi-person talking head podcast videos from scratch using
    AI — character creation, TTS, avatar animation, and video stitching. Use when the user wants
    to create a podcast, talking head video, or multi-speaker conversation video.

[ai-podcast-creation]
    Source: inference.sh superpowers
    What it does: Produces audio podcasts with AI voices, multiple speakers, background music,
    and intros and outros, all the way to a finished episode.
    When to use: You want to turn written content into a podcast, audiobook, or audio
    newsletter.
    Search terms: podcast, ai podcast, text to speech, audiobook, audio newsletter, voice over,
    multi voice, notebooklm alternative, podcast maker, ai narrator
    Original description: Create AI-powered podcasts with text-to-speech, music, and audio
    editing. Tools: Kokoro TTS, DIA TTS, Chatterbox, AI music generation, media merger.
    Capabilities: multi-voice conversations, background music, intro/outro, full episodes. Use
    for: podcast production, audiobooks, voice content, audio newsletters. Triggers: podcast, ai
    podcast, text to speech podcast, audio content, voice over, ai audiobook, multi voice,
    conversation ai, notebooklm alternative, audio generation, podcast automation, ai narrator,
    voice content, audio newsletter, podcast maker

[ai-product-photography]
    Source: inference.sh superpowers
    What it does: Generates professional-looking product photos, lifestyle shots, and mockups
    with AI, including studio lighting and packaging scenes.
    When to use: You need e-commerce or ad images for your products without a photo shoot.
    Search terms: product photos, product photography, amazon listing images, shopify images,
    product mockup, studio shot, lifestyle image, ecommerce photos, packshot, ai product images
    Original description: Generate professional AI product photography and commercial images.
    Models: FLUX, Imagen 3, Grok, Seedream for product shots, lifestyle images, mockups.
    Capabilities: studio lighting, lifestyle scenes, packaging, e-commerce photos. Use for:
    e-commerce, Amazon listings, Shopify, marketing, advertising, mockups. Triggers: product
    photography, product shot, commercial photography, e-commerce images, amazon product photo,
    shopify images, product mockup, studio product shot, lifestyle product image, advertising
    photo, packshot, product render, product image ai

[ai-video-generation]
    Source: inference.sh superpowers
    What it does: Creates videos from text or still images using Google Veo, Seedance, Wan, and
    40+ other AI models, with options for lip sync, upscaling, and sound effects.
    When to use: You want a short video for social media, marketing, or a product demo made by
    AI.
    Search terms: ai video, generate video, text to video, image to video, veo, sora
    alternative, runway alternative, animate photo, video maker, seedance, kling alternative,
    marketing video
    Original description: Generate AI videos with Google Veo, Seedance 2.0, HappyHorse, Wan,
    Grok and 40+ models via inference.sh CLI. Models: Veo 3.1, Veo 3, Seedance 2.0, HappyHorse
    1.0, Wan 2.5, Grok Imagine Video, OmniHuman, Fabric, HunyuanVideo. Capabilities: text-to-
    video, image-to-video, reference-to-video, video editing, lipsync, avatar animation, video
    upscaling, foley sound. Use for: social media videos, marketing content, explainer videos,
    product demos, AI avatars. Triggers: video generation, ai video, text to video, image to
    video, veo, animate image, video from image, ai animation, video generator, genera…

[ai-voice-cloning]
    Source: inference.sh superpowers
    What it does: Generates realistic AI speech in many voices, languages, and emotional styles,
    including long narration, conversations, and voice transformation.
    When to use: You need a voiceover, narration, or character voice without recording it
    yourself.
    Search terms: voice cloning, text to speech, ai voice, voice over, narration, elevenlabs,
    voice generator, audiobook voice, voice changer, inworld, realistic speech
    Original description: AI voice generation, text-to-speech, and voice synthesis via
    inference.sh CLI. Models: Inworld TTS-2 (100+ languages, emotion/non-verbal steering),
    Inworld TTS 1.5 (ultra-low latency), ElevenLabs (22+ premium voices, 32 languages), Kokoro
    TTS, DIA, Chatterbox, Higgs, VibeVoice for natural speech. Capabilities: multiple voices,
    emotions, accents, long-form narration, conversation, voice transformation, delivery mode
    control, character voices. Use for: voiceovers, audiobooks, podcasts, video narration,
    accessibility, gaming NPCs, avatar audio, UGC. Triggers: voice cloning, tts, text to speech,
    a…

[background-removal]
    Source: inference.sh superpowers
    What it does: Removes the background from photos to produce clean transparent PNGs, ideal
    for product shots and portraits.
    When to use: You need a cutout of a product or person for a listing, ad, or design.
    Search terms: remove background, transparent background, cutout, remove bg, product photo
    editing, transparent png, photo cutout, background remover, rembg
    Original description: Remove backgrounds from images with BiRefNet via inference.sh CLI.
    Model: BiRefNet (high accuracy background removal). Use for: product photos, portraits,
    e-commerce, transparent PNGs, photo editing. Triggers: remove background, background
    removal, remove bg, transparent background, cut out image, background remover, rembg,
    product photo editing, cutout, transparent png, bg removal, photo cutout

[character-design-sheet]
    Source: inference.sh superpowers
    What it does: Helps you keep an AI-generated character looking the same across many images
    using reference sheets, turnaround views, expression sheets, and color palettes.
    When to use: You are making a mascot, comic, game, or brand character and need it to stay
    consistent.
    Search terms: character design, consistent character, mascot, character sheet, reference
    sheet, comic art, game art, turnaround, illustration, brand character
    Original description: Character consistency across AI-generated images with reference sheets
    and LoRA techniques. Covers turnaround views, expression sheets, color palettes, and style
    consistency tricks. Use for: character design, game art, illustration, animation, comics,
    visual novels. Triggers: character design, character sheet, character consistency, character
    reference, turnaround sheet, expression sheet, character art, consistent character,
    character concept, reference sheet, character creation, oc design, character bible

[dialogue-audio]
    Source: inference.sh superpowers
    What it does: Creates multi-speaker conversation audio with distinct voices, emotion, and
    pacing using ElevenLabs and Dia text-to-speech.
    When to use: You need two or more voices talking to each other for a podcast, ad, or
    explainer.
    Search terms: dialogue audio, two voices, multi speaker, conversation audio, elevenlabs, dia
    tts, character voices, podcast audio, voice acting, script to audio
    Original description: Multi-speaker dialogue audio creation with ElevenLabs and Dia TTS.
    Covers speaker tags, emotion control, pacing, conversation flow, and post-production. Use
    for: podcasts, audiobooks, explainers, character dialogue, conversational content. Triggers:
    dialogue audio, multi speaker, conversation audio, dia tts, two speakers, podcast audio,
    character voices, voice acting, dialogue generation, conversation tts, multi voice, speaker
    tags, dialogue recording, elevenlabs dialogue, eleven labs conversation

[elevenlabs-dialogue]
    Source: inference.sh superpowers
    What it does: Generates a conversation between multiple ElevenLabs voices from a script into
    a single audio file, with control over delivery.
    When to use: You have a script with several speakers and want it voiced as one audio track.
    Search terms: elevenlabs, dialogue, multi speaker, conversation audio, script to audio, two
    voices, podcast dialogue, character voices, voice acting
    Original description: ElevenLabs multi-speaker dialogue generation - create conversations
    with different voices in a single audio file via inference.sh CLI. Capabilities: multi-voice
    dialogue, script-based generation, voice direction, conversation audio. Use for: podcasts,
    audiobooks, explainers, tutorials, character dialogue, video scripts. Triggers: elevenlabs
    dialogue, eleven labs dialogue, multi speaker, conversation audio, dialogue generation, text
    to dialogue, multi voice, voice acting, podcast dialogue, character voices, script to audio,
    elevenlabs conversation, two speakers

[elevenlabs-dubbing]
    Source: inference.sh superpowers
    What it does: Translates and dubs your audio or video into 29 languages while keeping the
    original speaker's voice.
    When to use: You want to release your video or podcast in other languages without re-
    recording.
    Search terms: dubbing, translate video, video translation, audio translation, localization,
    elevenlabs, multilingual, foreign language version, auto dub, voice translation
    Original description: ElevenLabs automatic dubbing - translate and dub audio/video into 29
    languages while preserving speaker voice via inference.sh CLI. Capabilities: auto speaker
    detection, voice-preserving translation, video dubbing, audio localization. Use for: content
    localization, video translation, multilingual content, international distribution. Triggers:
    dubbing, dub video, translate audio, video translation, audio translation, localize content,
    elevenlabs dubbing, eleven labs dub, multilingual dub, voice translation, auto dub, language
    dub, content localization

[elevenlabs-music]
    Source: inference.sh superpowers
    What it does: Composes original royalty-free music from a text prompt with ElevenLabs, up to
    10 minutes long with control over genre, mood, and instruments.
    When to use: You need background music, a jingle, or a soundtrack you can use commercially.
    Search terms: elevenlabs music, ai music, background music, jingle, soundtrack, royalty
    free, compose music, generate song, music generator
    Original description: ElevenLabs AI music generation - create original music from text
    prompts via inference.sh CLI. Capabilities: text-to-music, custom duration up to 10 minutes,
    genre/mood/instrument control, royalty-free commercial use. Use for: background music,
    soundtracks, jingles, podcasts, video scores, game audio. Triggers: elevenlabs music, eleven
    labs music, ai music, generate music, music generation, compose music, ai composer, create
    song, soundtrack, background music, jingle, elevenlabs compose, music ai

[elevenlabs-sound-effects]
    Source: inference.sh superpowers
    What it does: Generates custom sound effects from a text description, such as ambient noise,
    cinematic hits, or game sounds, with royalty-free use.
    When to use: You need a specific sound effect for a video, game, podcast, or presentation.
    Search terms: sound effects, sfx, foley, ai sound, ambient sound, game sounds, elevenlabs,
    sound design, audio effects, text to sound
    Original description: Generate AI sound effects from text descriptions with ElevenLabs via
    inference.sh CLI. Capabilities: text-to-sound-effect, custom duration, royalty-free audio.
    Use for: video production, game audio, podcasts, films, presentations, social media.
    Triggers: sound effects, sfx, sound generation, ai sound effects, generate sound, foley,
    audio effects, sound design, text to sound, elevenlabs sound, eleven labs sfx, ambient
    sound, cinematic sound, game sound effects

[elevenlabs-stt]
    Source: inference.sh superpowers
    What it does: Transcribes speech to text with ElevenLabs Scribe at high accuracy across 90+
    languages, identifying speakers and producing word-level timings and subtitles.
    When to use: You need an accurate transcript or subtitles for a meeting, podcast, or video.
    Search terms: transcription, speech to text, subtitles, elevenlabs scribe, meeting
    transcript, podcast transcript, speaker identification, captions, word timestamps,
    transcribe audio
    Original description: ElevenLabs speech-to-text with Scribe models and forced alignment via
    inference.sh CLI. Models: Scribe v1/v2 (98%+ accuracy, 90+ languages). Capabilities:
    transcription, speaker diarization, audio event tagging, word-level timestamps, forced
    alignment, subtitle generation. Use for: meeting transcription, subtitles, podcast
    transcripts, lip-sync timing, karaoke. Triggers: elevenlabs stt, elevenlabs transcription,
    scribe, elevenlabs speech to text, forced alignment, word alignment, subtitle timing,
    diarization, speaker identification, audio event detection, eleven labs transcribe

[elevenlabs-tts]
    Source: inference.sh superpowers
    What it does: Converts text into natural-sounding speech with ElevenLabs' premium voices in
    32 languages, with control over stability and style.
    When to use: You want a high-quality voiceover or narration in a realistic voice.
    Search terms: elevenlabs, text to speech, ai voice, voice over, narration, realistic voice,
    multilingual tts, audiobook, ivr voice, professional voice
    Original description: ElevenLabs text-to-speech with 22+ premium voices, multilingual
    support, and voice tuning via inference.sh CLI. Models: eleven_multilingual_v2 (highest
    quality), eleven_turbo_v2_5 (low latency), eleven_flash_v2_5 (ultra-fast). Capabilities:
    text-to-speech, voice selection, stability/style control, 32 languages. Use for: voiceovers,
    audiobooks, video narration, podcasts, accessibility, IVR. Triggers: elevenlabs, eleven
    labs, elevenlabs tts, premium tts, professional voice, ai voice, high quality tts,
    multilingual tts, eleven labs voice, voice generation, natural speech, realistic voice,
    voice o…

[elevenlabs-voice-changer]
    Source: inference.sh superpowers
    What it does: Transforms a recording of one voice into a different voice while keeping the
    words and emotion intact.
    When to use: You recorded something yourself but want it to sound like a different speaker.
    Search terms: voice changer, change voice, voice swap, speech to speech, voice disguise,
    elevenlabs, voice conversion, character voice, accent change
    Original description: ElevenLabs voice changer - transform any voice to a different voice
    while preserving speech content and emotion via inference.sh CLI. Models:
    eleven_multilingual_sts_v2 (70+ languages), eleven_english_sts_v2. Capabilities: speech-to-
    speech, voice transformation, accent change, voice disguise. Use for: content creation,
    voice acting, privacy, dubbing, character voices. Triggers: voice changer, speech to speech,
    voice transformation, change voice, voice swap, voice conversion, voice disguise, eleven
    labs voice changer, elevenlabs sts, transform voice, ai voice changer, voice modifier

[elevenlabs-voice-isolator]
    Source: inference.sh superpowers
    What it does: Cleans up audio by removing background noise and isolating the speaker's
    voice.
    When to use: You have a noisy recording of an interview, podcast, or call that needs
    cleaning up.
    Search terms: remove background noise, clean audio, noise removal, isolate voice, audio
    cleanup, elevenlabs, denoise, podcast cleanup, audio restoration, vocal isolation
    Original description: ElevenLabs voice isolator - remove background noise and isolate vocals
    from audio via inference.sh CLI. Capabilities: noise removal, voice extraction, audio
    cleanup, background removal. Use for: podcast cleanup, interview audio, music vocals, noisy
    recordings, audio restoration. Triggers: voice isolator, noise removal, background removal,
    isolate voice, clean audio, remove background noise, audio cleanup, voice extraction,
    elevenlabs isolator, eleven labs noise, vocal isolation, denoise, audio restoration, voice
    separation

[explainer-video-guide]
    Source: inference.sh superpowers
    What it does: Walks you through producing an explainer video: writing the script, pacing,
    planning scenes, recording voiceover, and assembling visuals.
    When to use: You want a product demo, how-it-works, or onboarding video and need a proven
    process.
    Search terms: explainer video, product demo video, video script, how to make a video,
    tutorial video, onboarding video, video production, animated explainer, walkthrough video
    Original description: Explainer video production guide: scripting, voiceover, visuals, and
    assembly. Covers script formulas, pacing rules, scene planning, and multi-tool pipelines.
    Use for: product demos, how-it-works videos, onboarding videos, social explainers. Triggers:
    explainer video, how to make explainer, product video, demo video, video production, video
    script, animated explainer, product demo video, tutorial video, onboarding video,
    walkthrough video, video pipeline

[flux-image]
    Source: inference.sh superpowers
    What it does: Generates images with Black Forest Labs' FLUX models, including custom styles
    trained via LoRA and image-to-image edits.
    When to use: You specifically want to use FLUX for image generation or a custom visual
    style.
    Search terms: flux, black forest labs, ai image, image generation, custom style, lora, text
    to image, flux dev, image to image
    Original description: Generate images with FLUX models (Black Forest Labs) via inference.sh
    CLI. Models: FLUX Dev LoRA, FLUX.2 Klein LoRA with custom style adaptation. Capabilities:
    text-to-image, image-to-image, LoRA fine-tuning, custom styles. Triggers: flux, flux.2, flux
    dev, flux schnell, flux pro, black forest labs, flux image, flux ai, flux model, flux lora

[generate-image]
    Source: awesome-copilot
    What it does: Generates images, icons, textures, sprites, and mockups using OpenAI's GPT-
    Image or Google Gemini, given an API key.
    When to use: You need a quick AI-generated image or visual asset from inside your coding
    tool.
    Search terms: generate image, ai image, icons, mockups, openai image, gemini, nano banana,
    copilot, textures, visual assets
    Original description: Generate images using AI. Use when asked to generate, create, or make
    images, textures, icons, sprites, artwork, visual assets, or mockups. Supports OpenAI (gpt-
    image-2) and Google Gemini (Nano Banana). Requires an API key for the chosen provider.

[google-veo]
    Source: inference.sh superpowers
    What it does: Generates high-quality cinematic videos from text using Google's Veo family of
    models.
    When to use: You want to use Google Veo specifically to produce a video clip.
    Search terms: veo, google veo, ai video, text to video, google video, cinematic video, veo
    3, vertex ai, video generation
    Original description: Generate videos with Google Veo models via inference.sh CLI. Models:
    Veo 3.1, Veo 3.1 Fast, Veo 3, Veo 3 Fast, Veo 2. Capabilities: text-to-video, cinematic
    output, high quality video generation. Triggers: veo, google veo, veo 3, veo 2, veo 3.1,
    vertex ai video, google video generation, google video ai, veo model, veo video

[gpt-image]
    Source: inference.sh superpowers
    What it does: Generates and edits images with OpenAI's GPT-Image-2, including inpainting,
    mask-based edits, and working from multiple reference images.
    When to use: You want OpenAI's image model for creating or retouching visuals.
    Search terms: gpt image, openai image, dall-e, chatgpt image, image editing, inpainting,
    photo manipulation, product mockup, ai image, marketing visuals
    Original description: Generate and edit images with OpenAI GPT-Image-2 via inference.sh CLI.
    Models: GPT-Image-2. Capabilities: text-to-image, image editing, inpainting, mask-based
    editing, multi-image reference, batch generation. Use for: product mockups, marketing
    visuals, image editing, concept art, inpainting, photo manipulation. Triggers: gpt image,
    gpt-image-2, openai image, chatgpt image, dall-e, dalle, openai image generation, gpt image
    edit, gpt inpainting, openai dall-e, gpt 4o image

[happyhorse]
    Source: inference.sh superpowers
    What it does: Generates and edits videos with Alibaba's HappyHorse models, including text-
    to-video, image-to-video, and natural-language video editing up to 1080p.
    When to use: You want to create or edit a realistic short video using HappyHorse.
    Search terms: happyhorse, alibaba video, ai video, video editing ai, text to video, image to
    video, character consistent video, product demo video, ai video editor
    Original description: Generate and edit videos with Alibaba HappyHorse 1.0 models via
    inference.sh CLI. Models: HappyHorse T2V, I2V, R2V, Video Edit. Capabilities: text-to-video,
    image-to-video, reference-to-video, video editing with natural language, character
    preservation, 720P/1080P, up to 15 seconds. Use for: physically realistic video, video
    editing, character-consistent content, product demos, social media. Triggers: happyhorse,
    happy horse, alibaba video, happyhorse 1.0, dashscope video, alibaba happyhorse, video
    editing ai, ai video editor

[higgsfield-brandkit]
    Source: higgsfield skills
    What it does: Creates a complete visual brand system through Higgsfield: color palettes,
    logo marks, typography, mockups, social graphics, packaging, signage, merchandise, and an
    editable brand book.
    When to use: You are launching or refreshing a brand and need a full visual identity
    package.
    Search terms: brand kit, visual identity, logo design, brand book, brand guidelines, color
    palette, packaging design, signage, higgsfield, branded assets, merchandise
    Original description: Create and extend complete visual brand systems through the Higgsfield
    CLI and bundled deterministic local tooling: palettes, SVG logo marks, typography, mockups,
    social graphics, packaging, signage, merchandise, posters, presentation decks, and editable
    PPTX/PDF brandbooks. Preserves official supplied assets, persists approvals locally, and
    regenerates only dependent outputs. Use when: "create a brand kit", "make a visual
    identity", "design a logo and brandbook", "apply this logo to branded assets", "make
    packaging or signage", or "extend our existing branding". Chain with higgsfield-generate…

[higgsfield-generate]
    Source: higgsfield skills
    What it does: Generates images, videos, 3D models, and audio through Higgsfield AI,
    including animating photos, editing or restyling images, making ads and UGC videos, and
    predicting video virality.
    When to use: You want to produce almost any kind of AI media, from a single picture to a
    full ad, through Higgsfield.
    Search terms: higgsfield, generate image, make a video, animate photo, image to video,
    create an ad, ugc video, 3d model, sound effect, ai media, virality predictor
    Original description: Generate images/videos/3D assets/audio via Higgsfield AI. Defaults:
    GPT Image 2 for image/design/text, Seedance 2.0 for video, Nano Banana 2/Lite/Pro for
    character/reference images, Marketing Studio for ads, Seed Audio 1.0 for audio. Use when:
    "generate an image", "make a video", "animate this photo", "image-to-video",
    "edit/stylize/remix this image", "reframe this video", "edit this video from a sketch",
    "create a 3D model/GLB", "create a sound effect", "make music", "text-to-audio", "create an
    ad", "make a UGC video", "unboxing", "presenter video", "import product from URL", or
    "analyze vide…

[higgsfield-marketplace-cards]
    Source: higgsfield skills
    What it does: Creates sets of marketplace-compliant product listing images through
    Higgsfield: main image, secondary shots, infographics, and A+ style content modules.
    When to use: You are listing a product on Amazon or another marketplace and need the full
    image set.
    Search terms: amazon listing images, marketplace images, product cards, a+ content, product
    infographics, listing photos, ecommerce images, higgsfield, product detail images, secondary
    images
    Original description: Generate marketplace product image cards through Higgsfield: compliant
    main image, secondary product images, and A+ style content modules. Use when the user asks
    for marketplace listing images, product detail cards, secondary product images, product
    infographics, lifestyle listing shots, A+ style content, marketplace image sets, or sales-
    ready product visuals. Backend owns marketplace compliance references and prompt templates;
    this skill only routes user intent to the CLI. NOT for generic brand product photography
    without marketplace/listing context (use higgsfield-product-photoshoot), video …

[higgsfield-product-photoshoot]
    Source: higgsfield skills
    What it does: Produces brand-quality product images through Higgsfield, from studio shots
    and lifestyle scenes to Pinterest pins, banners, carousels, ad creative packs, and virtual
    try-ons.
    When to use: You need polished product or paid-social visuals without a photographer.
    Search terms: product photoshoot, product photos, lifestyle image, ad creative, meta ads
    images, virtual try on, hero banner, carousel, pinterest pin, higgsfield, studio shot
    Original description: Generate brand-quality product images through Higgsfield product-
    photoshoot prompt enhancement on GPT Image 2 / gpt_image_2. Entry point for professional
    brand/product visuals. Use when: "product photo", "studio shot", "lifestyle image",
    "Pinterest pin", "hero/banner", "carousel", "ad creative", "Meta ads", "virtual try-on",
    "model wearing", "person holding product", "closeup with hands", "levitating/floating/splash
    product", "CGI/surreal product", "restyle", "seasonal/aesthetic variation", or any product,
    brand, or paid-social creative. Modes: product_shot, lifestyle_scene, closeup_product_wi…

[higgsfield-soul-id]
    Source: higgsfield skills
    What it does: Trains a personalized Higgsfield 'Soul' model on a person's face so later
    images and videos can feature them realistically.
    When to use: You want your own face or a team member's to appear in AI-generated images and
    videos.
    Search terms: digital twin, train my face, avatar of me, my face in ai images, personal ai
    model, higgsfield soul, identity consistency, ai likeness, custom character
    Original description: Train a Soul Character — a personalized model on a person's face that
    Higgsfield uses for identity-faithful image and video generation. Use when: "create my
    Soul", "train my face", "make my digital twin", "build me an avatar", "learn my appearance",
    "create a character of me", "set up identity for video", "I want my face in generated
    images". Chain: train Soul (one-time, returns reference_id) → use in higgsfield-generate via
    `--soul-id <id>` with models like `text2image_soul_v2` or `soul_cinema_studio`. NOT for:
    one-shot face swaps (use higgsfield-generate with --image), named-character / non-…

[higgsfield-video-explainer]
    Source: higgsfield skills
    What it does: Builds a complete narrated, animated explainer or story video from a topic or
    document, assembled from 10-second blocks in a consistent visual style with optional
    subtitles.
    When to use: You want to turn a topic or document into a faceless narrated video.
    Search terms: explainer video, narrated video, faceless video, animated video, document to
    video, story video, higgsfield, educational video, subtitles, video from text
    Original description: Build a complete non-photoreal narrated explainer or story video from
    ordered 10-second blocks: one narrator, one universal style key, one Seed Audio take and one
    Gemini Omni clip per block, then server-side assembly with explainer_video. Use when: "make
    an explainer video", "explain this in a video", "turn this topic or document into a narrated
    video", "tell this story as an animated video", "make a faceless narrated video", or "show
    me explainer styles". Supports live CMS presets, custom style references, mascot/faceless
    modes, two aspects, and optional burned subtitles. NOT for: photoreal f…

[higgsfield-youtube-thumbnail]
    Source: higgsfield skills
    What it does: Designs high-click YouTube thumbnails and vertical video covers through
    Higgsfield, preserving real people's likenesses and including logos and variants.
    When to use: You have a video ready and need a thumbnail that gets clicks.
    Search terms: youtube thumbnail, video cover, shorts cover, instagram cover, click through,
    thumbnail design, higgsfield, mrbeast style, thumbnail maker
    Original description: Create high-click-through YouTube thumbnails and vertical video covers
    through the Higgsfield CLI. Builds a truthful information-gap concept, preserves up to three
    referenced identities, supports logos and controlled variants, renders the main image with
    Nano Banana Pro, and applies focused Seedream edits. Use when: "make a YouTube thumbnail",
    "thumbnail for this video", "MrBeast-style cover", "Shorts cover", or "Instagram video
    cover". Chain after any video workflow once its truthful topic and visual direction are
    known. NOT for producing the video itself (use higgsfield-generate), product ca…

[image]
    Source: coreyhaines31 marketingskills
    What it does: Creates, edits, and optimizes marketing images such as blog headers, social
    graphics, product mockups, banners, and link-preview images using a range of AI tools.
    When to use: You need a visual for a blog post, social account, or listing and want it done
    fast.
    Search terms: marketing images, social media graphic, blog hero image, product mockup,
    banner, og image, image optimization, compress images, canva, midjourney, ai image
    Original description: When the user wants to create, generate, edit, or optimize images for
    marketing — blog heroes, social graphics, product mockups, profile banners, listing visuals,
    or brand assets. Also use when the user mentions 'AI image generation,' 'generate an image,'
    'create a graphic,' 'product mockup,' 'hero image,' 'social media graphic,' 'banner image,'
    'cover photo,' 'profile banner,' 'listing screenshot,' 'Flux,' 'Flux Kontext,' 'Midjourney,'
    'DALL-E,' 'GPT Image,' 'ChatGPT Images,' 'Ideogram,' 'Gemini image,' 'Nano Banana,'
    'Recraft,' 'Stable Diffusion,' 'Canva,' 'Figma,' 'image optimization,' 'com…

[image-manipulation-image-magick]
    Source: awesome-copilot
    What it does: Resizes, converts, and batch-processes images using ImageMagick, and reads
    image details like dimensions and format.
    When to use: You have a folder of images that need resizing, converting, or thumbnailing in
    bulk.
    Search terms: resize images, convert image format, batch images, thumbnails, imagemagick,
    image processing, bulk resize, image metadata, compress photos
    Original description: Process and manipulate images using ImageMagick. Supports resizing,
    format conversion, batch processing, and retrieving image metadata. Use when working with
    images, creating thumbnails, resizing wallpapers, or performing batch image operations.

[image-to-video]
    Source: inference.sh superpowers
    What it does: Turns a still image into a short video clip with motion and camera movement,
    and advises which AI model to use for each situation.
    When to use: You have a photo or graphic you want to bring to life as a video.
    Search terms: image to video, animate photo, animate image, bring image to life, motion from
    still, photo to video, product animation, wan, seedance
    Original description: Still-to-video conversion guide: model selection, motion prompting,
    and camera movement. Covers Wan 2.5 i2v, Seedance, Fabric, Grok Video with when to use each.
    Use for: animating images, creating video from stills, adding motion, product animations.
    Triggers: image to video, i2v, animate image, still to video, add motion to image, image
    animation, photo to video, animate still, wan i2v, image2video, bring image to life, animate
    photo, motion from image

[image-upscaling]
    Source: inference.sh superpowers
    What it does: Enlarges and sharpens low-resolution images with AI upscalers, restoring old
    photos and making AI art print-ready.
    When to use: You have a blurry or small image and need a crisp, high-resolution version.
    Search terms: upscale image, enhance image, increase resolution, enlarge photo, 4k upscale,
    restore old photo, image enhancement, sharpen image, real esrgan, topaz
    Original description: Upscale and enhance images with Real-ESRGAN, Thera, Topaz, FLUX
    Upscaler via inference.sh CLI. Models: Real-ESRGAN, Thera (any size), FLUX Dev Upscaler,
    Topaz Image Upscaler. Use for: enhance low-res images, upscale AI art, restore old photos,
    increase resolution. Triggers: upscale image, image upscaler, enhance image, increase
    resolution, real esrgan, ai upscale, super resolution, image enhancement, upscaling, enlarge
    image, higher resolution, 4k upscale, hd upscale

[nano-banana]
    Source: inference.sh superpowers
    What it does: Generates and edits images with Google's Gemini native image models (Nano
    Banana), including multi-image input.
    When to use: You want to use Google's Gemini image model for creating or editing a picture.
    Search terms: nano banana, gemini image, google image generation, ai image, image editing,
    text to image, gemini 3 pro image, google ai
    Original description: Generate images with Google Gemini native image models via
    inference.sh CLI. Models: Gemini 3 Pro Image, Gemini 2.5 Flash Image. Capabilities: text-to-
    image, image editing, multi-image input. Triggers: nano banana, gemini image, gemini 3 pro
    image, gemini 2.5 flash image, google image generation, native image generation, gemini
    native image

[nano-banana-2]
    Source: inference.sh superpowers
    What it does: Generates and edits images with Google's Gemini 3.1 Flash Image (Nano Banana
    2), accepting up to 14 reference images and grounding results with Google Search.
    When to use: You want the newest Gemini image model, especially when combining many
    reference images.
    Search terms: nano banana 2, gemini image, google image generation, ai image, image editing,
    reference images, gemini 3.1 flash, google ai
    Original description: Generate images with Google Gemini 3.1 Flash Image Preview (Nano
    Banana 2) via inference.sh CLI. Capabilities: text-to-image, image editing, multi-image
    input (up to 14 images), Google Search grounding. Triggers: nano banana 2, nanobanana 2,
    gemini 3.1 flash image, gemini 3 1 flash image preview, google image generation

[nano-banana-pro-openrouter]
    Source: awesome-copilot
    What it does: Generates or edits images via OpenRouter using the Gemini 3 Pro Image model,
    with 1K to 4K output and multi-image compositing.
    When to use: You want Gemini image generation routed through OpenRouter.
    Search terms: openrouter, nano banana pro, gemini image, ai image, image editing, 4k image,
    compositing, google image, copilot
    Original description: Generate or edit images via OpenRouter with the Gemini 3 Pro Image
    model. Use for prompt-only image generation, image edits, and multi-image compositing;
    supports 1K/2K/4K output.

[nanobanana]
    Source: opc-skills
    What it does: Generates and edits images using Google Gemini 3 Pro Image (Nano Banana Pro),
    with various aspect ratios and 2K/4K output.
    When to use: You want a high-resolution AI image from Google's Gemini model.
    Search terms: nano banana pro, gemini image, ai image, generate image, image editing, 4k
    image, google ai, aspect ratio, text to image
    Original description: Generate and edit images using Google Gemini 3 Pro Image (Nano Banana
    Pro). Supports text-to-image, image editing, various aspect ratios, and high-resolution
    output (2K/4K). Use when user wants to generate images, create images, use Gemini image
    generation, or do AI image generation.

[og-image-design]
    Source: inference.sh superpowers
    What it does: Designs the preview images that appear when your links are shared on social
    media, with correct sizes, text placement, and branding for each platform.
    When to use: You want your website or blog links to look good when shared on LinkedIn, X, or
    Facebook.
    Search terms: og image, link preview, social sharing image, twitter card, open graph, blog
    thumbnail, social card, linkedin preview, meta image
    Original description: Open Graph and social sharing image design with platform specs, text
    placement, and branding. Covers OG meta tags, Twitter cards, LinkedIn previews, and dynamic
    generation. Use for: social sharing images, blog thumbnails, link previews, social cards.
    Triggers: og image, open graph, social sharing image, twitter card, social card, link
    preview image, og meta, sharing preview, social thumbnail, meta image, og:image,
    twitter:image, linkedin preview

[p-image]
    Source: inference.sh superpowers
    What it does: Generates and edits images quickly and cheaply with Pruna's optimized P-Image
    models, including custom styles and multi-image compositing.
    When to use: You need lots of images fast on a budget.
    Search terms: pruna, p-image, fast image generation, cheap image generation, ai image, image
    editing, budget images, bulk images, optimized flux
    Original description: Generate images with Pruna P-Image models via inference.sh CLI.
    Models: P-Image, P-Image-LoRA, P-Image-Edit, P-Image-Edit-LoRA. Capabilities: text-to-image,
    image editing, LoRA styles, multi-image compositing, fast inference. Pruna optimizes models
    for speed without quality loss. Triggers: pruna, p-image, pruna image, fast image
    generation, optimized flux, pruna ai, p image, fast ai image, economic image generation,
    cheap image generation

[p-video]
    Source: inference.sh superpowers
    What it does: Generates text-to-video and image-to-video clips quickly and affordably with
    Pruna's P-Video and WAN models, up to 1080p with audio.
    When to use: You need short AI videos produced fast and inexpensively.
    Search terms: pruna, p-video, fast video generation, cheap video generation, ai video, text
    to video, image to video, wan, budget video
    Original description: Generate videos with Pruna P-Video and WAN models via inference.sh
    CLI. Models: P-Video, WAN-T2V, WAN-I2V. Capabilities: text-to-video, image-to-video, audio
    support, 720p/1080p, fast inference. Pruna optimizes models for speed without quality loss.
    Triggers: pruna video, p-video, pruna ai video, fast video generation, optimized video, wan
    t2v, wan i2v, economic video generation, cheap video generation, pruna text to video, pruna
    image to video

[p-video-avatar]
    Source: inference.sh superpowers
    What it does: Turns a portrait photo into a realistic talking video with built-in text-to-
    speech in 30 voices and 10 languages, much faster and cheaper than competing tools.
    When to use: You want a talking presenter video from just a photo and a script.
    Search terms: talking head, ai avatar, avatar video, ai presenter, lipsync, heygen
    alternative, synthesia alternative, pruna avatar, digital human, spokesperson video, photo
    to talking video
    Original description: Generate talking head avatar videos with Pruna P-Video-Avatar via
    inference.sh CLI. Turn a portrait image into a realistic speaking video with built-in TTS.
    18x faster and 6x cheaper than competitors. Models: P-Video-Avatar, P-Image (for portrait
    generation). Capabilities: text-to-avatar, audio-driven avatars, 30 voices, 10 languages,
    720p/1080p, built-in TTS, dynamic backgrounds, full-body control. Use for: AI presenters,
    product demos, explainer videos, virtual influencers, marketing, education, multilingual
    content, UGC, gaming avatars. Triggers: avatar video, talking head, ai avatar, p-vid…

[product-photography]
    Source: inference.sh superpowers
    What it does: Teaches the conventions of good product photography for AI generation: angles,
    lighting, backgrounds, shadows, hero shots, and e-commerce image requirements.
    When to use: You want your AI product shots to look like a professional studio made them.
    Search terms: product photography, product photos, packshot, ecommerce images, amazon
    product photo, studio lighting, hero shot, lifestyle product, product listing image
    Original description: AI product photography with studio lighting, lifestyle shots, and
    packshot conventions. Covers angles, backgrounds, shadow types, hero shots, and e-commerce
    image requirements. Use for: product photos, e-commerce images, Amazon listings, packshots,
    lifestyle photography. Triggers: product photography, product photo, packshot, e-commerce
    photography, product shot, product image, studio photography, lifestyle product, amazon
    product photo, product listing image, hero shot, product mockup, commercial photography

[qwen-image-2]
    Source: inference.sh superpowers
    What it does: Generates and edits images with Alibaba's Qwen-Image-2.0 models, notable for
    handling complex text inside images.
    When to use: You want an image that includes readable text, such as a poster or sign.
    Search terms: qwen image, alibaba image, ai image, text in images, image editing, text
    rendering, poster generator, dashscope
    Original description: Generate and edit images with Alibaba Qwen-Image-2.0 models via
    inference.sh CLI. Models: Qwen-Image-2.0 (fast), Qwen-Image-2.0-Pro (professional text
    rendering). Capabilities: text-to-image, multi-image editing, complex text rendering.
    Triggers: qwen image, qwen-image, alibaba image, dashscope image, qwen image 2, qwen image
    pro

[qwen-image-2-pro]
    Source: inference.sh superpowers
    What it does: Generates detailed, realistic images with Alibaba's Qwen-Image-2.0-Pro,
    designed for posters, banners, and text-heavy designs.
    When to use: You need a polished poster or banner with accurate text rendered by AI.
    Search terms: qwen image pro, alibaba image, poster design, banner design, text rendering,
    ai image, realistic image, text heavy design
    Original description: Generate images with Alibaba Qwen-Image-2.0-Pro via inference.sh CLI.
    Professional text rendering, fine-grained realism, enhanced semantic adherence. Ideal for
    posters, banners, and text-heavy designs. Triggers: qwen image pro, qwen-image-pro, qwen 2
    pro, alibaba image pro, dashscope pro, professional text rendering

[remotion]
    Source: stitch
    What it does: Creates walkthrough videos of Stitch design projects using Remotion, with
    smooth transitions, zooms, and text overlays.
    When to use: You designed something in Stitch and want a polished video tour of it.
    Search terms: stitch, remotion, walkthrough video, design demo, product tour, screen
    recording alternative, video transitions, ui video, showcase
    Original description: Generate walkthrough videos from Stitch projects using Remotion with
    smooth transitions, zooming, and text overlays

[remotion-render]
    Source: inference.sh superpowers
    What it does: Renders MP4 videos from React/Remotion code, so animated graphics and data-
    driven videos can be produced programmatically.
    When to use: You have Remotion code and want a finished video file out of it.
    Search terms: remotion, react video, code to video, motion graphics, animated video,
    programmatic video, render mp4, data driven video, tsx to video
    Original description: Render videos from React/Remotion component code via inference.sh.
    Pass TSX code, get MP4. Supports all Remotion APIs: useCurrentFrame, useVideoConfig, spring,
    interpolate, AbsoluteFill, Sequence. Configurable resolution, FPS, duration, codec. Use for:
    programmatic video generation, animated graphics, motion design, data-driven videos, React
    animations to video. Triggers: remotion, render video from code, tsx to video, react video,
    programmatic video, remotion render, code to video, animated video, motion graphics code,
    react animation video

[seedance]
    Source: inference.sh superpowers
    What it does: Generates videos with synchronized audio from text, images, or reference clips
    using ByteDance's Seedance 2.0, up to 1080p and 15 seconds.
    When to use: You want an AI video that comes with sound built in.
    Search terms: seedance, bytedance video, ai video, video with audio, text to video, image to
    video, music video, product demo, social media video
    Original description: Generate videos with ByteDance Seedance 2.0 via inference.sh CLI.
    Unified model for text-to-video, image-to-video, and reference-to-video with synchronized
    audio, up to 1080p, 4-15s duration. Pro and Fast variants. Studio variants with private
    asset library for portrait consistency. Use for: social media videos, music videos, product
    demos, animated content, AI video with sound. Triggers: seedance, seedance 2, bytedance
    video, seedance t2v, seedance i2v, seedance r2v, video with audio, seedance 2.0, bytedance
    seedance, seedance studio

[speech-to-text]
    Source: inference.sh superpowers
    What it does: Transcribes audio into text using ElevenLabs Scribe or Whisper, with
    timestamps, speaker identification, and translation.
    When to use: You need a transcript of a meeting, podcast, interview, or voice note.
    Search terms: transcription, speech to text, transcribe audio, whisper, subtitles, meeting
    transcript, voice to text, podcast transcript, captions, voice notes
    Original description: Transcribe audio to text with ElevenLabs Scribe and Whisper models via
    inference.sh CLI. Models: ElevenLabs Scribe v2 (98%+ accuracy, diarization), Fast Whisper
    Large V3, Whisper V3 Large. Capabilities: transcription, translation, multi-language,
    timestamps, speaker diarization, audio event tagging. Use for: meeting transcription,
    subtitles, podcast transcripts, voice notes. Triggers: speech to text, transcription,
    whisper, audio to text, transcribe audio, voice to text, stt, automatic transcription,
    subtitles generation, transcribe meeting, audio transcription, whisper ai, elevenlabs stt,
    scr…

[storyboard-creation]
    Source: inference.sh superpowers
    What it does: Plans a video or film shot by shot with proper storyboard panels, shot types,
    camera angles, and continuity rules.
    When to use: You are planning an ad, video, or animation and want it mapped out before
    production.
    Search terms: storyboard, shot list, video planning, pre production, camera angles, scene
    planning, ad storyboard, visual script, animatic
    Original description: Film and video storyboarding with shot vocabulary, continuity rules,
    and panel layout. Covers shot types, camera angles, movement, 180-degree rule, and
    annotation format. Use for: video planning, film pre-production, ad storyboards, music video
    planning, animation. Triggers: storyboard, storyboarding, shot list, film planning, video
    planning, pre production, shot composition, camera angles, scene planning, visual script,
    animatic, storyboard panels, video storyboard

[talking-head-production]
    Source: inference.sh superpowers
    What it does: Guides production of talking-head videos with AI avatars, covering portrait
    requirements, audio quality, and lip sync workflows across several tools.
    When to use: You want a presenter-style video for a course, pitch, or social post without
    filming.
    Search terms: talking head, ai avatar, ai presenter, lip sync, spokesperson video, course
    video, presenter video, omnihuman, virtual presenter, video without camera
    Original description: Talking head video production with AI avatars, lipsync, and voiceover.
    Recommended: P-Video-Avatar (fastest, cheapest, built-in TTS). Also covers OmniHuman,
    PixVerse, Fabric. Portrait requirements, audio quality, production workflows. Use for:
    spokesperson videos, course content, social media, presentations, demos. Triggers: talking
    head, avatar video, lipsync, lip sync, ai spokesperson, virtual presenter, ai presenter,
    omnihuman, talking avatar, video presenter, ai talking head, presenter video, ai face video,
    p-video-avatar

[text-to-speech]
    Source: inference.sh superpowers
    What it does: Converts text into natural speech using Inworld, ElevenLabs, Kokoro, and other
    voices, with options for emotion, multiple speakers, and voice cloning.
    When to use: You need a voiceover, narration, or spoken version of written content.
    Search terms: text to speech, tts, ai voice, voice over, narration, elevenlabs, inworld,
    audiobook, voice cloning, ai narrator, podcast voice
    Original description: Convert text to natural speech with Inworld TTS, ElevenLabs, DIA TTS,
    Kokoro, Chatterbox, and more via inference.sh CLI. Models: Inworld TTS-2 (100+ languages,
    emotion steering), Inworld TTS 1.5 (ultra-low latency), ElevenLabs (premium, 22+ voices, 32
    languages), DIA TTS (conversational), Kokoro TTS, Chatterbox, Higgs Audio, VibeVoice
    (podcasts). Capabilities: text-to-speech, voice cloning, multi-speaker dialogue, podcast
    generation, expressive speech, emotion/delivery steering, character voices. Use for:
    voiceovers, audiobooks, podcasts, accessibility, video narration, IVR, voice assistants, …

[video]
    Source: coreyhaines31 marketingskills
    What it does: Creates and produces video content using AI tools like Veo, Sora, HeyGen, and
    Runway or code-based frameworks like Remotion, and can copy the style of a reference video.
    When to use: You want a marketing, explainer, or social video made with AI.
    Search terms: make a video, ai video, video production, heygen, synthesia, veo, sora,
    runway, explainer video, product demo, talking head, copy this edit
    Original description: When the user wants to create, generate, or produce video content
    using AI tools or programmatic frameworks. Also use when the user mentions 'video
    production,' 'AI video,' 'Remotion,' 'Hyperframes,' 'HeyGen,' 'Synthesia,' 'Veo,' 'Sora,'
    'Runway,' 'Kling,' 'Seedance,' 'Hailuo,' 'MiniMax,' 'Pika,' 'Hunyuan,' 'Wan,' 'video
    generation,' 'AI avatar,' 'talking head video,' 'programmatic video,' 'video template,'
    'explainer video,' 'product demo video,' 'video pipeline,' 'copy this edit,' 'match this
    video style,' 'reverse-engineer this video,' 'edit like this reference,' or 'make me a
    video.' Use t…

[video-ad-specs]
    Source: inference.sh superpowers
    What it does: Provides the exact dimensions, length limits, and caption rules for video ads
    on TikTok, Instagram, YouTube, Facebook, and LinkedIn, plus a proven ad structure.
    When to use: You are making a video ad and need it to meet each platform's requirements.
    Search terms: video ad specs, ad dimensions, tiktok ad, instagram ad, youtube ad, facebook
    ad, linkedin ad, reels ad, stories ad, paid social video, ad sizes
    Original description: Video ad creation with exact platform-specific specs for TikTok,
    Instagram, YouTube, Facebook, LinkedIn. Covers dimensions, duration limits, AIDA framework,
    and caption requirements. Use for: video ads, social media ads, paid media creative, video
    marketing, ad production. Triggers: video ad, social media ad, tiktok ad, instagram ad,
    youtube ad, facebook ad, linkedin ad, video creative, ad specs, paid media, video marketing,
    ad production, reels ad, stories ad, pre roll, bumper ad

[video-prompting-guide]
    Source: inference.sh superpowers
    What it does: Teaches how to write effective prompts for AI video tools like Veo, Seedance,
    Runway, and Sora, covering shots, camera moves, lighting, and style words.
    When to use: Your AI videos are not turning out well and you want better, more consistent
    results.
    Search terms: video prompts, how to prompt ai video, better ai video, veo prompts, prompt
    tips, cinematography, prompt examples, video generation tips, sora prompts
    Original description: Best practices and techniques for writing effective AI video
    generation prompts. Covers: Veo, Seedance, Wan, Grok, Kling, Runway, Pika, Sora prompting
    strategies. Learn: shot types, camera movements, lighting, pacing, style keywords, negative
    prompts. Use for: improving video quality, getting consistent results, professional video
    prompts. Triggers: video prompt, how to prompt video, veo prompts, video generation tips,
    better ai video, video prompt engineering, video prompt guide, video prompt template, ai
    video tips, video prompt best practices, video prompt examples, cinematography prompts

[youtube-thumbnail-design]
    Source: inference.sh superpowers
    What it does: Designs YouTube thumbnails that get clicks, covering dimensions, contrast,
    safe zones, text placement, facial expressions, and A/B testing.
    When to use: You want more people clicking on your YouTube videos.
    Search terms: youtube thumbnail, thumbnail design, click through rate, video cover,
    thumbnail maker, youtube growth, ctr, thumbnail tips, video preview image
    Original description: YouTube thumbnail design with specific dimensions, contrast rules, and
    mobile preview optimization. Covers safe zones, text placement, face expression psychology,
    and A/B testing. Use for: YouTube thumbnails, video cover images, click-through
    optimization. Triggers: youtube thumbnail, thumbnail design, video thumbnail, click through
    rate, ctr optimization, youtube cover, video cover image, thumbnail maker, thumbnail tips,
    youtube design, video preview image
