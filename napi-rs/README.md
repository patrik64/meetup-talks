# Using Rust to speed up Node  

12.11.2026 - Node.js Meetup Vienna   
https://www.meetup.com/nodejs-vienna/events/316960156  

slides are in the above [talk.html](https://github.com/patrik64/meetup-talks/blob/main/napi-rs/talk.html) file, simply open it in your browser.  

Demo apps:  

https://github.com/patrik64/rust-napi-rs-demo  
https://github.com/patrik64/rust-neon-demo  

Links:  

https://napi.rs  
https://github.com/napi-rs/napi-rs  

https://neon-rs.dev  
https://github.com/neon-bindings/neon  




Usually, just before I start my talk, I let Claude create a demo application while I am doing the talk.  
To recreate the demo application from this talk ([napi-rs-pdf-writer](https://github.com/patrik64/napi-rs-pdf-writer)) follow these steps:

1. create a folder called napi-rs-pdf-writer and open Claude Code in it
2. set the model to Sonnet 5.5
3. set the effort to low
4. use the following prompt:  
```  
Create a Sveltekit application that showcases the use of napi-rs framework in the following way:
  - create rust code that uses typst's pdf-writer (https://github.com/typst/pdf-writer) that creates 100000 example pdf files 
  - the example pdf files should be something like invoice for an online service
  - use napi-rs to create node native library from that rust code
  - use rayon rust library to parallelize the work
  - create several generation options (single thread vs. rayon, in memory only vs. disk I/O, JS loop vs single napi call, JS worker threads) -
  - the best would be 6 buttons - 3x2 where columns would be rust->disk, rust->memory, JS->memory and rows single thread and rayon
  - use EmbedPDF library to show the generated pdfs (use absolute path to pdfium.wasm)
  - provide statistics about how fast is the pdf files generation
  - create a progress bar that tracks generation
  - claude-in-chrome is working
  - use pnpm  
```
