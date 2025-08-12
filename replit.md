# AI Workshop Resource Hub

## Overview

This is a multi-page educational website for an AI workshop that spans 5 days. The site serves as a comprehensive resource hub providing access to various AI tools, activities, and learning materials. It's designed as a static website using HTML, CSS, and JavaScript with Bootstrap for responsive styling. The website organizes AI tools and resources by categories (text, voice, image, video, coding) across different daily sessions, making it easy for workshop participants to find and access the tools they need for each day's activities.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
The website follows a traditional multi-page static site architecture with shared components:

- **Static HTML Pages**: Six main pages (index.html for home and day1-day5.html for each workshop day)
- **Shared Navigation**: Consistent sticky navigation bar across all pages using Bootstrap navbar component
- **Responsive Design**: Bootstrap 5.3.0 framework provides mobile-first responsive grid system
- **Component Reuse**: Common navigation and styling patterns are replicated across pages for consistency

### Styling and UI Framework
- **Bootstrap 5.3.0**: Primary CSS framework for responsive layout, components, and utilities
- **Font Awesome 6.4.0**: Icon library for visual elements and navigation enhancements
- **Custom CSS**: Additional styling in assets/style.css with CSS custom properties for theming
- **Color System**: Predefined color variables for consistent theming across the site

### JavaScript Functionality
The site includes interactive enhancements through assets/script.js:
- **Navigation Enhancement**: Scroll effects and smooth scrolling for better user experience
- **Progressive Enhancement**: Features gracefully degrade if JavaScript is disabled
- **Lazy Loading**: Performance optimization for loading resources
- **Animation System**: Smooth transitions and interactive feedback

### Content Structure
Each day page follows a consistent structure:
- **Page Header**: Color-coded headers to distinguish between different days
- **Tool Categories**: Organized sections for different types of AI tools
- **External Links**: All tool links open in new tabs to preserve the workshop hub

### Design Patterns
- **Mobile-First Responsive**: Bootstrap's responsive grid ensures compatibility across devices
- **Progressive Disclosure**: Information is organized hierarchically from overview to specific tools
- **Consistent Navigation**: Sticky top navigation with active state indication
- **Visual Hierarchy**: Clear typography and spacing to guide user attention

## External Dependencies

### CSS Frameworks and Libraries
- **Bootstrap 5.3.0**: Complete CSS framework for responsive design and components
- **Font Awesome 6.4.0**: Icon library for navigation and visual elements

### External AI Tools and Services
The website provides links to numerous third-party AI platforms organized by category:

**Text and Research AI**:
- LMArena, Hugging Face Chat, Poe, Deepseek, Perplexity, Gemini, ChatGPT, Grok

**Voice and Audio AI**:
- ElevenLabs, Murf, Google Speech-to-Text, Suno AI, Soundraw, Pi AI, Character.ai, Replika

**Interactive Learning Tools**:
- Google's Thing Translator, Quick Draw, various educational AI demonstrations

### File Hosting and Sharing
- **Google Drive**: Workshop resource storage and file sharing
- **Padlet**: Collaborative board for student project sharing and showcase

### Content Delivery Networks
- **Bootstrap CDN**: For CSS framework delivery
- **Font Awesome CDN**: For icon font delivery
- **jsDelivr**: Reliable CDN for both Bootstrap and Font Awesome assets

The architecture prioritizes simplicity, maintainability, and ease of use for educational purposes while providing a professional and polished experience for workshop participants.