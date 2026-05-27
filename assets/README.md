# Assets Folder

This folder contains images and videos for the QMR Heavy Machinery Movers website.

## Structure

```
assets/
├── images/
│   ├── machinery-lifting-1.jpg
│   ├── equipment-moving-1.jpg
│   ├── roller-movement-1.jpg
│   ├── machine-positioning-1.jpg
│   ├── installation-support-1.jpg
│   ├── team-work-1.jpg
│   └── project-completion-1.jpg
└── videos/
    └── demo-video.mp4 (or YouTube/Vimeo embed)
```

## Instructions

1. **Add Images:** Upload your machinery photos to the `assets/images/` folder
2. **Add Videos:** 
   - Option A: Upload video files to `assets/videos/`
   - Option B: Use YouTube or Vimeo links (recommended for better performance)
3. **Update index.html:** Replace placeholder URLs with your actual image/video paths

## Placeholder URLs

The website currently uses placeholder images from `https://via.placeholder.com/`. Replace these with your actual image URLs in the `index.html` file.

## Video Integration

To add a YouTube video:
- Find the video URL: `https://www.youtube.com/watch?v=VIDEO_ID`
- Convert to embed URL: `https://www.youtube.com/embed/VIDEO_ID`
- Replace in the gallery items array in `index.html`

## Image Optimization Tips

- Use JPEG for photos (smaller file size)
- Use PNG for images with transparency
- Compress images before uploading (use online tools like TinyPNG)
- Recommended size: 800x600px for gallery display
- Recommended size: 400x400px for thumbnails
