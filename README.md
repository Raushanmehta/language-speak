LanguageSpeak

LanguageSpeak is a web application that allows users to translate text between various languages, upload files for text extraction, and paste content from URLs. The application features text-to-speech functionality and allows users to interact with the translation results by copying, liking, or saving them as favorites.

Features

Text Translation: Translates input text into a selected target language using OpenAI's GPT model.
Speech Recognition: Converts spoken words into text.
File Upload: Extracts text from uploaded RTF files.
Link Paste: Fetches and extracts text from URLs.
Text-to-Speech: Reads out the source or translated text.
Favorites: Save and manage favorite translations.
Like/Dislike: Interact with translations.
Technologies Used
React: Frontend framework
OpenAI GPT: Text translation
SpeechSynthesis API: Text-to-speech functionality
FileReader API: Handling file uploads


Usage
Text Input:

Enter text in the "Source Language" textarea.
Select the target language from the dropdown.
The translated text will appear in the "Target Language" textarea.
Speech Recognition:

Click the microphone icon to start speech recognition.
Speak the text you want to be transcribed.
File Upload:

Click the upload button to select and upload an RTF file.
The text from the file will be extracted and displayed in the "Source Language" textarea.
Link Paste:

Paste a URL in the provided input field to fetch and display its content in the "Source Language" textarea.
Text-to-Speech:

Click the speaker icon to hear the spoken version of the text in either the source or target language.
Favorites and Interactions:

Click the star icon to save or remove the current translation from your favorites.
Click the thumbs up or thumbs down icons to like or dislike the translation.
Click the copy icon to copy the translated text to the clipboard.


Contact
For any questions or feedback, please contact:

Email: raushanmehta2184@gmail.com
GitHub: Raushanmehta


This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
