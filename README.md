# Anime Senpai

A modern, interactive anime trivia quiz game built with pure HTML, CSS, and JavaScript. Test your anime knowledge with dynamically generated questions powered by AI.

🚀 **[Live Demo](https://anisenpai.vercel.app/)**

## What It Does

**Anime Senpai** is an intelligent anime quiz application that creates unique trivia questions in real-time. The game features:

- **AI-Generated Questions**: Uses advanced AI to create contextually accurate anime trivia questions on-demand
- **Smart Duplicate Prevention**: Implements sophisticated tracking to ensure no question is repeated, even if reworded differently
- **Customizable Experience**: Users can focus on specific anime series, genres, or play with mixed content
- **Adaptive Difficulty**: Four difficulty levels from Novice to Senpai with dynamic scoring
- **Real-Time Feedback**: Instant answer validation with visual feedback and score tracking
- **Responsive Design**: Seamless experience across desktop and mobile devices
- **Beautiful UI**: Modern gradient-based design with smooth animations and transitions

## Core Features

- **Dynamic Question Generation**: Each question is uniquely generated based on user preferences
- **Anti-Repetition System**: Advanced tracking prevents duplicate questions across multiple sessions
- **Timed Challenges**: Dynamic timer based on question difficulty
- **Score System**: Points awarded based on difficulty level and response time
- **Keyboard Navigation**: Full keyboard support for accessibility
- **Session Management**: Secure user authentication with PuterJS integration

## Technology Stack

### Frontend
- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with CSS Grid, Flexbox, and custom animations
- **Vanilla JavaScript**: ES6+ features with modular architecture
- **GSAP**: Hardware-accelerated animations and transitions

### AI & Backend Services
- **PuterJS**: Cloud-based authentication and AI integration
- **AI Language Models**: Dynamic question generation and content validation
- **Real-time Processing**: Instant question generation and validation

### Deployment
- **Vercel**: Edge-optimized hosting with global CDN
- **Continuous Deployment**: Automated builds from Git repository
- **Performance Optimization**: Built-in caching and compression

### Architecture
- **Single Page Application**: No page refreshes, smooth user experience
- **Event-Driven Design**: Modular component system with clean separation of concerns
- **State Management**: Centralized game state with persistent tracking
- **Error Handling**: Comprehensive error recovery and user feedback systems

### Key Algorithms
- **Semantic Duplicate Detection**: Advanced text normalization and similarity checking
- **Question History Tracking**: Maintains context to prevent conceptual duplicates
- **Dynamic Difficulty Scaling**: Intelligent question complexity adjustment
- **Answer Validation**: Multi-layer verification system for accuracy

## Performance Features

- **Preloading System**: Next questions generated in background for seamless experience
- **Efficient Caching**: Smart state management reduces redundant API calls
- **Optimized Rendering**: Minimal DOM manipulation with hardware acceleration
- **Progressive Enhancement**: Graceful degradation for older browsers
- **Global CDN**: Fast loading times worldwide via Vercel's edge network
