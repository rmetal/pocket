# Pokémon TCG Pocket - Promo Card Gallery

A web-based gallery for viewing Pokémon Trading Card Game Pocket promotional cards.

## Description

This project provides an interactive gallery to browse and view promotional cards from Pokémon TCG Pocket. The gallery features two separate collections (Promo-A and Promo-B) with an easy-to-use tabbed interface.

## Features

- **Dual Gallery System**: Browse Promo-A and Promo-B card collections separately
- **Auto-Loading**: Automatically detects and loads available card images
- **Image Caching**: Smart caching system for faster loading on subsequent visits
- **Modal View**: Click on any card to view it in full size
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Dark Theme**: Clean, modern dark interface

## Usage

1. Visit the gallery page
2. Select either Promo-A or Promo-B tab
3. Click "카드 로드" (Load Cards) button to load the card collection
4. Click on any card to view it in larger size
5. Use "캐시 초기화" (Clear Cache) button to reset cached data if needed

## Folder Structure
```
repository-root/
├── index.html          # Main gallery page
├── nail.png           # Thumbnail for latest video
├── promo-a/           # Promo-A card images
│   ├── 1.png
│   ├── 2.png
│   └── ...
└── promo-b/           # Promo-B card images
    ├── 1.png
    ├── 2.png
    └── ...
```

## Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript
- IndexedDB for data persistence
- Cache API for image caching

## License

This project is for informational and viewing purposes only. All Pokémon card images and related content are property of The Pokémon Company.

## Note

This is an unofficial fan-made gallery and is not affiliated with or endorsed by The Pokémon Company, Nintendo, or Creatures Inc.
