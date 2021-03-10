# Anyska Beauty Diary

## Table of contents

- [Purpose](#purpose)
- [Structure](#structure)
  - [Mobile approach](#mobile-approach)
  - [Desktop approach](#desktop-approach)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)

## Purpose
This website's story is quite short and concise. It is intented to come as a tool for bloggers with low financial resources that cannot afford to hire someone to develop their website. It needs just a json file to be changed in order to be personalized for each of their needs. 

In terms of design, altough the website will be a very simple one it will be a good touch and it will look similar to [Anyska's beauty diary](https://anyskabeautydiary.wordpress.com/). 

## Structure
The website structure will be simple as mentioned above and it will include a mobile version and a desktop version. The reason why the website will be structured on a mobile first approach is that nowadays most people spend more time on their mobile devices as it is much easier and quicker than a computer. 

### Mobile approach
Regarding the mobile version of the website, it presents a direct visualization of the latest articles posted on the blog, from the newest ones to the oldest one.
Apart from the topics, the website includes at the top a burger menu and the text `SHOW` where the viewers can click to see the blogger's avatar followed by some social icons like Facebook, Instagram, Twitter and LinkedIn. The social icons are clickable and they will guide the viewer to the blogger's specific social media account selected. 
Another section from the `SHOW` option is the implicit menu containing `Home`, `About me` and `Contact me`, all three options redirecting the viewer to the selected subsection. 
The third section of the `SHOW` option is a search bar where the viewer can browse on the website through a specific word and will get as result a specific topic/article from the blog where that word is present.

### Desktop approach
The desktop version is pretty similar to the mobile one but here the viewers have everything just in from of their eyes. The content from the burger menu (described above as the view got when `SHOW` is clicked) is present in the left side of the website and the topics/articles of the blog are now in the right side.


## Prerequisites
The project requires NodeJS v.4+

To install NodeJS visit [nodejs download page](https://nodejs.org/en/download/) download the appropiate package for your operatin system, click on the downloaded file, open it and follow the installation procees. If you don't know much about it, just click ALL the NEXT and or INSTALL buttons and choose "I agree" when prompted and you should be fine.


## Installation

**BEFORE YOU INSTALL:** please read the [prerequisites](#prerequisites)

```bash
$ npm i
```

or

```bash
$ npm install
```

Note: if you run into an pngquant-bin error on Windows try running:

```
npm install imagemin-pngquant@5.0.1 -D
npm install pngquant-bin@3.1.1 -D
```


## Usage

To run the project in development mode and open a local server that synchronizes across multiple devices use:

```bash
npm start
```

or

```bash
npm run dev
```
