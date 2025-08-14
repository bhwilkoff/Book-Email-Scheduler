# 📚 Book Email Scheduler

Transform any book into a personalized email reading series that delivers bite-sized portions directly to your inbox over time.

## ✨ Features

- **Universal File Support**: Upload PDF, ePub, or TXT files up to 50MB
- **Smart Content Processing**: Automatically extracts and organizes text content from any format
- **Flexible Scheduling**: Choose from daily, weekly, or morning & night delivery options
- **Customizable Chunking**: Split your book into 1-100 email parts based on your reading preference
- **Beautiful Email Design**: Clean, readable emails with progress tracking and styling
- **Easy Stop Mechanism**: One-click unsubscribe system with multi-account Google support
- **Management Dashboard**: Built-in functions to check status, test functionality, and troubleshoot
- **Self-Hosted**: Runs entirely on your Google Apps Script - no external servers or accounts needed

## 🚀 How It Works

1. **Upload Your Book**: Drag and drop any PDF, ePub, or text file
2. **Configure Schedule**: Set your email, frequency, timezone, and number of parts
3. **Generate Script**: Get a custom Google Apps Script tailored to your book
4. **Deploy & Enjoy**: Set up the script in Google Apps Script and start receiving emails

## 📖 Perfect For

- **Busy Professionals**: Read books gradually without dedicating large time blocks
- **Commuters**: Perfect bite-sized content for daily commutes
- **Book Clubs**: Synchronized reading schedules for group discussions
- **Students**: Digest academic texts over semester timelines
- **Habit Building**: Establish consistent daily reading routines
- **Attention Management**: Break large texts into manageable portions

## 🛠️ Technical Stack

- **Frontend**: Vanilla HTML/CSS/JavaScript with modern ES6+
- **File Processing**: 
  - PDF.js for PDF text extraction
  - JSZip for ePub file handling
  - Native JavaScript for text file processing
- **Backend**: Google Apps Script (serverless)
- **Email Delivery**: Gmail API through Google Apps Script
- **Scheduling**: Google Apps Script time-based triggers
- **Storage**: Google Apps Script Properties Service

## 📋 Requirements

- Google account
- Modern web browser
- No additional software or accounts needed

## 🎯 Key Benefits

- **Privacy-First**: Your books and data never leave Google's ecosystem
- **Zero Cost**: Completely free using Google's generous Apps Script quotas
- **No Maintenance**: Set it up once and let it run automatically
- **Full Control**: You own and control the entire system
- **Customizable**: Modify the generated script to fit your exact needs

## 📊 Smart Features

### Intelligent Content Processing
- **PDF**: Extracts text while preserving structure and handling multi-column layouts
- **ePub**: Parses book structure, skips front matter, and identifies actual content
- **Text**: Intelligently splits on paragraph boundaries for natural reading flow

### Advanced Email Management
- **Progress Tracking**: Shows reading percentage and estimated completion time
- **Stop Protection**: Secure unsubscribe system that works across multiple Google accounts
- **Status Monitoring**: Check if your series is active, paused, or completed
- **Test Functions**: Verify setup and troubleshoot issues easily

### Robust Scheduling
- **Timezone Support**: Delivers emails at the right time regardless of your location
- **Flexible Frequency**: Daily, weekly, or twice-daily options
- **Automatic Cleanup**: Removes triggers and sends completion notification when finished

## 📱 Screenshots

*[Add screenshots of the main interface, email examples, and setup process]*

## 🤝 Contributing

Contributions are welcome! This project helps people develop better reading habits through technology.

### Ideas for Contributions
- Additional file format support (MOBI, DOC, etc.)
- Enhanced email templates
- Reading analytics and tracking
- Integration with reading apps
- Mobile-responsive improvements
- Accessibility enhancements

## 📄 License

MIT License - Feel free to use, modify, and distribute as needed.

## 🎉 Success Stories

*"I finally finished reading 'War and Peace' by getting just 2 pages in my email every morning. Game changer!"* - Early User

*"Perfect for our book club - everyone gets the same chapters at the same time."* - Book Club Organizer

## 🔧 Advanced Usage

The generated Google Apps Script includes several management functions:

- `checkSeriesStatus()` - View progress and current status
- `testStopLink()` - Debug unsubscribe functionality  
- `sendTestEmail()` - Send immediate test email
- `resetScheduler()` - Restart series from beginning

## 💡 Pro Tips

- **Large Books**: Use more email parts (50-100) for better digestibility
- **Academic Texts**: Choose weekly delivery for deeper reflection time
- **Fiction**: Daily delivery maintains story momentum
- **Reference Books**: Use fewer parts for quicker completion

## 🌟 Why This Project?

In our fast-paced world, finding time to read complete books is challenging. This tool bridges the gap between wanting to read and actually reading by seamlessly integrating books into your daily routine. No apps to remember, no additional subscriptions - just books delivered to the inbox you already check.

---

**Ready to transform your reading habits?** [Get started now](#) by uploading your first book!