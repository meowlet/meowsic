# Introduction

This is the source code for my blog. After completing four web programming credits at school, I wanted to continue using my web writing knowledge to create a blog website myself. Here, the content I post will be quite eclectic, from thoughts on anime, visual novels, to various technologies I’ve used or am interested in. Oh, the first post I want to write seems to be about how I’ve been learning Chinese over the past year, analyzing the pros and cons of my learning method, hoping to help those who are planning to learn Chinese.

But let’s not get ahead of ourselves, the first thing to complete is web programming knowledge. Writing a “readable” blog is easy, but what I’m aiming for is a complete, optimized, fast, and most importantly, beautiful website. So, the road ahead is long, from the time I write these words to when the blog is completed won’t be quick. I hope I can wait.

Above are a few words I wanted to write before getting started. While I’m at it, let me talk about the technologies I used to build this website.

| Things        | Frameworks    |
| :------------ | :------------ |
| Front-end     | Astro.build   |
| CSS           | Tailwind CSS  |
| (updating...) | (updating...) |

## Project Structure

Inside of the project, you'll see the following folders and files:

```text
/
├── public/
├── src/
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

## Want to learn more?

Feel free to check [the documentation](https://docs.astro.build).
