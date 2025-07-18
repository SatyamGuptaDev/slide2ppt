# YouTube Study Platform

A personal, distraction-free YouTube platform for educational purposes. This project provides two different approaches to YouTube video consumption without the typical distractions found on the main YouTube website.

## 🎯 Features

### Main Platform (`youtube-study-platform.html`)
- **🔍 Advanced Search**: Search videos, channels, and playlists with filters
- **📱 Responsive Design**: Works on desktop and mobile devices
- **💾 Local Library**: Save videos and playlists to your personal library
- **📊 Session Statistics**: Track your study sessions
- **🎛️ Customizable Filters**: Filter by duration, upload date, relevance, etc.
- **📋 URL Paste**: Directly paste YouTube URLs to search
- **🎨 Dark Theme**: Eye-friendly dark interface
- **🔒 Privacy-Focused**: No tracking, data stored locally

### Alternative Platform (`youtube-alternative-player.html`)
- **🎬 Multiple Playback Methods**: Thumbnail preview, iframe, and external links
- **🔗 External Service Integration**: Links to Invidious, NewPipe, and other privacy-friendly services
- **⚠️ Corporate-Friendly**: Designed for restricted environments
- **🛡️ Privacy-Enhanced**: Alternative viewing options for maximum privacy

## 🚀 Quick Start

### 1. Get YouTube Data API Key (Free)

1. Go to [Google Cloud Console](https://console.developers.google.com/)
2. Create a new project or select an existing one
3. Enable the **YouTube Data API v3**
4. Create credentials (API Key)
5. Copy your API key

### 2. Setup

1. Download both HTML files
2. Open either file in your web browser
3. Enter your YouTube Data API key in the provided field
4. Start searching and watching videos!

## 📖 How to Use

### Main Platform Features

#### Search and Discovery
- **Basic Search**: Enter any search term in the search box
- **URL Paste**: Click "Paste URL" to directly load a YouTube video/channel/playlist
- **Advanced Filters**: Use dropdowns to filter by content type, order, and duration

#### Video Management
- **Play Videos**: Click "Play" on any video card to watch in the embedded player
- **Save to Library**: Save videos to your personal library for later viewing
- **Session Tracking**: Monitor your study progress with built-in statistics

#### Library Management
- **Personal Library**: All saved videos are stored locally in your browser
- **Quick Access**: Click any saved video to instantly play it
- **Organization**: Videos are saved with title, channel, and timestamp

### Alternative Platform Features

#### Playback Methods
1. **Thumbnail Preview**: Shows video thumbnail with play overlay
2. **Standard iframe**: Traditional YouTube embed (may be blocked in some environments)
3. **External Links**: Direct links to privacy-friendly services

#### Privacy-Friendly Options
- **Invidious**: Privacy-focused YouTube frontend
- **NewPipe**: Android app for YouTube without Google services
- **Direct YouTube**: Standard YouTube links

## 🔧 Technical Details

### API Usage and Limits
- **Free Tier**: 10,000 units per day (sufficient for personal use)
- **Search Cost**: 100 units per search
- **Video Details**: 1 unit per video
- **Typical Usage**: ~100 searches per day within free limits

### Data Storage
- **Local Storage**: All saved videos stored in browser's local storage
- **Session Storage**: Session statistics stored temporarily
- **No Server**: Everything runs client-side, no backend required

### Browser Compatibility
- **Modern Browsers**: Chrome, Firefox, Safari, Edge
- **Mobile Support**: Responsive design works on all devices
- **No Plugins**: Pure HTML, CSS, and JavaScript

## 🛡️ Privacy and Security

### What We DON'T Store
- ❌ No video content downloaded or cached
- ❌ No personal information collected
- ❌ No tracking or analytics
- ❌ No server-side data storage

### What We DO Store (Locally)
- ✅ Your API key (in browser's local storage)
- ✅ Your saved video library (in browser's local storage)
- ✅ Session statistics (temporary, cleared when browser closes)

## 🚨 Important Notes

### YouTube's Restrictions
- **iframe Limitations**: Some corporate networks block YouTube embeds
- **API Limits**: Free tier has daily quotas (10,000 units/day)
- **Content Restrictions**: Some videos may not be playable due to restrictions

### Alternative Solutions
- **Invidious**: Privacy-focused YouTube frontend
- **NewPipe**: Android app for YouTube without Google services
- **Corporate Networks**: Use the alternative platform for restricted environments

## 📋 Setup Instructions

### For Personal Use
1. Open `youtube-study-platform.html`
2. Enter your YouTube Data API key
3. Start searching and learning!

### For Restricted Environments
1. Open `youtube-alternative-player.html`
2. Enter your YouTube Data API key
3. Use "External Links" playback method
4. Click external service links to watch videos

## 🎨 Customization

### Themes
Both platforms use a dark theme optimized for extended viewing sessions. The CSS can be easily modified to change colors, fonts, and layout.

### Features
The JavaScript is modular and can be extended with additional features:
- Custom video categories
- Advanced search filters
- Export/import functionality
- Multiple API key support

## 🔍 Troubleshooting

### Common Issues

#### "API request failed"
- Check your API key is correct
- Ensure YouTube Data API v3 is enabled in Google Cloud Console
- Verify you haven't exceeded daily quota

#### "Video not found"
- Video may be private or deleted
- Check the video ID/URL is correct
- Try searching for the video instead

#### "iframe blocked"
- Use the alternative platform
- Select "External Links" playback method
- Use Invidious or other alternative services

### Browser Issues
- **Clear Cache**: If videos don't load, clear browser cache
- **Enable JavaScript**: Both platforms require JavaScript
- **Check Console**: Open browser dev tools to see any error messages

## 🚀 Advanced Usage

### Keyboard Shortcuts
- **Enter**: Submit search
- **Escape**: Close video player

### URL Formats Supported
- `https://www.youtube.com/watch?v=VIDEO_ID`
- `https://youtu.be/VIDEO_ID`
- `https://www.youtube.com/channel/CHANNEL_ID`
- `https://www.youtube.com/playlist?list=PLAYLIST_ID`

### API Optimization
- **Batch Requests**: The platform automatically optimizes API calls
- **Caching**: Video metadata is cached during the session
- **Rate Limiting**: Built-in protection against exceeding API limits

## 📚 Educational Use Cases

### Study Sessions
- Search for educational content by topic
- Save videos to create custom learning playlists
- Track study time and progress

### Research
- Quickly find and organize research materials
- Save important videos for reference
- Access content without YouTube's distracting interface

### Corporate Training
- Use in restricted environments
- Focus on content without recommendations
- Create curated learning libraries

## 🤝 Contributing

This is a personal project, but suggestions and improvements are welcome! The code is designed to be:
- **Simple**: Easy to understand and modify
- **Modular**: Features can be added or removed easily
- **Self-contained**: No external dependencies

## 📄 License

This project is for educational and personal use only. Please respect YouTube's Terms of Service and API usage policies.

## 🆘 Support

If you encounter issues:
1. Check the troubleshooting section above
2. Verify your API key and quota usage
3. Test with different videos/searches
4. Check browser console for error messages

Remember: This platform is designed for personal, educational use. Please use responsibly and respect content creators' rights.

---

**Happy Learning! 🎓**
