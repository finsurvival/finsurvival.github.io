# FinSurvival Challenge Website

A modern, responsive website for the FinSurvival Challenge - a machine learning competition focused on advancing deep survival modeling for financial transactions using DeFi data from the Aave V3 protocol.

## Overview

This website showcases the FinSurvival Challenge, which is held in conjunction with the ACM AI in Finance conference (ICAIF'25) in Singapore from November 15-18, 2025. The challenge focuses on time-to-event prediction in financial scenarios using survival analysis techniques.

## Features

- **Responsive Design**: Fully responsive layout that works on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations and transitions
- **Interactive Elements**: Smooth scrolling navigation, hover effects, and fade-in animations
- **Comprehensive Content**: All competition details including overview, task description, evaluation criteria, timeline, and organizer information
- **Call-to-Action Buttons**: Direct links to the ICAIF'25 conference, Discord community, and Codabench submission platform
- **Discord Integration**: Prominent Discord community links for participant engagement and support

## Competition Details

### Dataset Information
- **Source**: Aave V3 Ethereum protocol transactions
- **Size**: 21.8M+ records with 90 engineered features
- **Time Period**: March 12, 2022 - July 2, 2024
- **Tasks**: 16 unique event transition predictions
- **Evaluation**: Concordance Index (C-index) metric

### Competition Phases
- **Development Phase** (Sep 15 - Oct 14, 2025): 5 submissions/day, 100 total submissions
- **Final Phase** (Oct 15 - Oct 20, 2025): 2 submissions total, evaluated against holdout test set

### Event Transitions
Participants must create models for 16 unique event pairs:
- **Borrow →** Deposit, Repay, Withdraw, Liquidated
- **Deposit →** Borrow, Repay, Withdraw, Liquidated  
- **Repay →** Borrow, Deposit, Withdraw, Liquidated
- **Withdraw →** Borrow, Deposit, Repay, Liquidated

## Website Sections

1. **Hero Section**: Eye-catching introduction with call-to-action buttons including Discord community link
2. **Challenge Overview**: Detailed explanation of survival modeling in finance
3. **Task Description**: Competition objectives and dataset information
4. **Evaluation Protocol**: Rules, criteria, and submission guidelines
5. **Timeline**: Key dates and milestones
6. **Organizers**: Team information with photos
7. **Submission**: Final call-to-action for participation with Discord support

## Technical Details

- **HTML5**: Semantic markup for accessibility and SEO
- **CSS3**: Modern styling with Flexbox and Grid layouts
- **JavaScript**: Smooth scrolling and intersection observer for animations
- **Font Awesome**: Icons for enhanced visual appeal
- **Google Fonts**: Inter font family for modern typography

## Getting Started

1. Clone or download the repository
2. Open `index.html` in a web browser
3. The website is self-contained and doesn't require any build process

## Customization

### Adding Organizer Photos
Replace the placeholder icons in the organizer cards with actual photos:

```html
<div class="organizer-photo">
    <img src="path/to/photo.jpg" alt="Organizer Name" style="width: 100%; height: 100%; object-fit: cover; border-radius: 50%;">
</div>
```

### Updating Codabench Link
When the Codabench competition page is ready, update the submission button:

```html
<a href="https://codabench.org/competitions/finsurvival" class="btn btn-primary">
    <i class="fas fa-upload"></i>
    Submit on Codabench
</a>
```

### Discord Community Integration
The website includes Discord community links for participant engagement:

```html
<a href="https://discord.gg/jyN2nDWj" class="btn btn-discord" target="_blank">
    <i class="fab fa-discord"></i>
    Join Discord Community
</a>
```

### Adding More Content
The website structure is modular and easy to extend. Simply add new sections following the existing pattern:

```html
<section id="new-section" class="section">
    <h2>Section Title</h2>
    <p>Section content...</p>
</section>
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Community & Support

### Discord Community
Join our Discord server for real-time discussions, questions, and collaboration:
- **Discord Link**: [https://discord.gg/jyN2nDWj](https://discord.gg/jyN2nDWj)
- **Purpose**: Technical discussions, Q&A, and community support
- **Official Website**: [https://finsurvival.github.io/](https://finsurvival.github.io/)

---

*This website is designed to promote the FinSurvival Challenge and provide comprehensive information to potential participants.*
