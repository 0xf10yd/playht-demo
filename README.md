# TTS cross-sp 
speech synthesizer built with react, node and sanity and sanity editor, to annotate the text and choose special synthesis for any of the text.
what's cool about it is that you can change your tts provider with ease, so it doesn't matter if it's Google TTS / Azure cognitive TTS / etc.

## Getting started

1. Clone this repository

2. Upgrade or install the Sanity CLI (this project requires 0.140.0 or higher):

```shell
npm install --global @sanity/cli
```

3. In the studio folder, install dependencies

```shell
sanity install
```

4. Initialize this studio with your own project. 

```shell
sanity init
```

Answer *Y* on the prompt that asks you to reconfigure the studio, and follow the instructions for creating a new project.

5. Adding Speech Synthesis preview

If you want the preview button for editor to work, you'll have to add [a token for Google’s text-to-speech API](https://console.cloud.google.com/apis/api/texttospeech.googleapis.com/credentials) in [`schemas/ssml-editor/PreviewButton.js`](https://github.com/0xf10yd/playht-demo/blob/master/schemas/ssml-editor/PreviewButton.js#L7).

6. To start the studio locally:

```shell
sanity start
```

7. To deploy the studio:

```shell
sanity deploy
```

## Now you can do the following things:

- [Read “getting started” in the docs](https://www.sanity.io/docs/introduction/getting-started?utm_source=readme)
- [Join the community Slack](https://slack.sanity.io/?utm_source=readme)
- [Extend and build plugins](https://www.sanity.io/docs/content-studio/extending?utm_source=readme)
