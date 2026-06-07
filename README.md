# Mukta Kala - Art Gallery

A static art gallery website hosted on GitHub Pages.

## How to Add New Artwork

1. Add your image to the images/ folder
2. Edit data.json and add an entry to the "artworks" array:

{
  "id": "2",
  "title": "Your Artwork Title",
  "category": "Painting",
  "image": "images/your-image.jpg",
  "date": "2026-06-07"
}

3. Commit and push. The gallery updates automatically!

## Categories Available
- Painting
- Digital Art
- Sketch
- Photography
- Mixed Media

## Files
- index.html : Public gallery (visitors see this)
- admin.html : Instructions and quick-add helper
- data.json  : All artwork data (edit this to manage gallery)
- images/    : Store all artwork images here

## Hosting on GitHub Pages
1. Push this folder to a GitHub repo
2. Go to Settings > Pages > Deploy from branch main
3. Your gallery will be live at https://yourusername.github.io/repo-name/
