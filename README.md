# N46Whisper

Fork from https://github.com/Ayanaminn/N46Whisper

## AI translation
The notebook now allow users to translate transcribed subtitle text line by line using AT translation tools.

Users can also upload local subtitle files or select files from google drive for translation.

Currently, it supports `chatGPT` translation. 

The translated text will be append in the same line after the original text and sepearted by `/N`, such that a new bilingual subtitle file is generated.

For instance: 

![QQ截图20230312155700](https://user-images.githubusercontent.com/49441654/224525469-18a43cbc-33b9-4b2f-b7ca-7ae0c1865b17.png)

An example of bilingual subtitle:

![QQ截图20230312160015](https://user-images.githubusercontent.com/49441654/224525526-51e2123c-6e1c-427c-8d67-9ccd4a7e6630.png)

To use the AI translation, users must use their own OpenAI API Key. To obtain a free Key, go to https://platform.openai.com/account/api-keys

Please note there will be limitaions on usage for free keys, choose a paid plan to speed up at your own cost.

## Split lines
Users can choose to split text in a single line by space.The child lines will have same time stamp with the parent line, respectively.

For instance, for a line contains multiple long sentences:
>Dialogue: 0,0:01:00.52,0:01:17.52,default,,0,0,0,,Birthday Liveについて話そうかなと思います よろしくお願いします

After split:
>Dialogue: 0,0:01:00.52,0:01:17.52,default,,0,0,0,,Birthday Liveについて話そうかなと思います(adjust_required)

>Dialogue: 0,0:01:00.52,0:01:17.52,default,,0,0,0,,ろしくお願いします(adjust_required)

## Support
The application could significantly reduce the labour and time costs of sub-groups or individual subbers. However, despite its impressive performance, the Whisper model and the application itself are not without limitations.Please read the orgininal documents and Discussions to learn more about the usage of Whisper and the common issues.

However, if you have any throughts, requests or questions that directly related to making subtitiles for Sakamichi group girls, please feel free to post here or [contact me](mailto:admin@ikedateresa.cc)

## License
The code is released under the MIT license. See [License](./LICENSE.md) for details.

