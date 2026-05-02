# Local AI Chat

This is a local AI chat web application built with React, TypeScript, and Vite. It allows you to chat with AI models running locally on your machine without relying on external APIs, ensuring complete privacy.

## Fitur Utama & Teknologi

Proyek ini dibangun menggunakan modern stack untuk memastikan performa yang cepat dan pengalaman pengguna yang mulus:

- **Local AI Models:** Terintegrasi dengan [Ollama](https://ollama.com/) untuk menjalankan berbagai model AI secara lokal di perangkat Anda.
- **Local Storage:** Riwayat percakapan disimpan dengan aman di browser menggunakan **Dexie.js** (IndexedDB wrapper), sehingga data chat Anda tidak pernah meninggalkan perangkat.
- **Frontend Stack:** 
  - **React** dengan **TypeScript** & **Vite**.
  - **Tailwind CSS** untuk styling.
  - Komponen UI dari **Radix UI**.
- **Markdown Support:** Pesan dari AI dirender dengan **React Markdown**, mendukung format seperti code block.
- **Routing & Forms:** Menggunakan **React Router** untuk navigasi dan **React Hook Form** + **Zod** untuk handling input.

## Acknowledgements & Credits

This project was built following a tutorial and using a UI boilerplate provided by **VoidFnc**. Huge thanks for the helpful resources!

- **Creator:** VoidFnc
- **YouTube Tutorial:** [Video Link](https://www.youtube.com/watch?v=VxGPm5ffPTc&t=4937s)
- **Base UI Template Repository:** [theodevoid/local-ai-chat - branch: 1-base-ui-template](https://github.com/theodevoid/local-ai-chat/tree/1-base-ui-template)

## Getting Started

To run this project locally:

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the development server:
   ```bash
   npm run dev
   ```
