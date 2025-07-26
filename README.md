# Scavenger Love - A Journey 💕

A beautiful, romantic website that takes your loved one on an emotional journey through your feelings. Perfect for anniversaries, proposals, or just expressing your love in a unique way.

## ✨ Features

- **Interactive Homepage**: Countdown timer showing time since you met
- **Romantic Poem**: Beautiful verses about your feelings
- **Clickable Love Reasons**: 9 interactive hearts revealing reasons why you love them
- **Love Playlist**: Your favorite songs with personal messages
- **Response Page**: Easy way for them to respond back to you
- **Beautiful Animations**: Soft, romantic design with floating hearts and smooth transitions

## 🎨 Customization Guide

### 1. Update Contact Information

In `index.html`, find the contact buttons on Page 4 and update:

```html
<!-- Email Button -->
<a href="mailto:YOUR_EMAIL@example.com?subject=I love you too ❤️&body=...">
  <!-- Text Button -->
  <a
    href="sms:+YOUR_PHONE_NUMBER&body=I love you too! Your scavenger hunt was beautiful ❤️"
  ></a
></a>
```

### 2. Set Your Special Date

In `script.js`, line 29, update the date to when you first met or another meaningful date:

```javascript
const specialDate = new Date("2023-01-01T00:00:00"); // Change this date!
```

### 3. Personalize the Poem

In `index.html`, find the poem section (Page 1) and replace the verses with your own words:

```html
<p class="verse">
  Your own beautiful words here...<br />
  About how they make you feel...<br />
</p>
```

### 4. Customize Love Reasons

In `index.html`, find the reason cards (Page 2) and update the `data-reason` and `data-emoji` attributes:

```html
<div
  class="reason-card"
  data-reason="Your custom reason here"
  data-emoji="😊"
></div>
```

### 5. Update the Playlist

In `index.html`, find the playlist section (Page 3) and replace with your favorite songs:

```html
<div class="song-item">
  <div class="song-info">
    <span class="song-title">Your Song Title</span>
    <span class="song-artist">Why this song is special to you</span>
  </div>
</div>
```

### 6. Personal Message

In `index.html`, update the heart message on Page 3:

```html
<p class="heart-message">
  "Your personal message about what music means to your relationship."
</p>
```

## 🚀 How to Use

1. Customize all the content as described above
2. Open `index.html` in any web browser
3. Share the link or files with your loved one
4. Watch their heart melt! 💖

## 🎯 Tips for Maximum Impact

- **Choose the right moment**: Share this when you have privacy and time to talk
- **Personal touch**: The more specific your reasons and memories, the more meaningful it becomes
- **Follow up**: Be available to receive their response - this is about connection!
- **Make it yours**: Don't just use the default content - personalize everything

## 💡 Ideas for Customization

- Add photos by replacing text with `<img>` tags
- Include inside jokes in your love reasons
- Reference specific memories in the poem
- Add songs that tell your love story
- Include dates and locations that are meaningful to you both

## 🌟 Features Explained

- **Responsive Design**: Works beautifully on phones, tablets, and computers
- **Smooth Animations**: Professional-quality transitions and effects
- **Interactive Elements**: Click, hover, and keyboard navigation
- **Romantic Color Scheme**: Soft pinks, purples, and warm tones
- **Typography**: Elegant fonts that enhance the romantic mood

---

Made with 💕 for expressing love in the digital age.

_Remember: The most important part isn't the technology - it's the genuine feelings you express through it._
