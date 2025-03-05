<div align="center">

# Open Linktree

---

**A futuristic social links landing page for developers and creators**
  
[![GitHub stars](https://img.shields.io/github/stars/inulute/socials-page?style=for-the-badge&color=blue)](https://github.com/inulute/socials-page/stargazers)
[![License](https://img.shields.io/github/license/inulute/socials-page?style=for-the-badge&color=blue)](https://github.com/inulute/socials-page/blob/main/LICENSE)

<img src="image.png" alt="Socials Page Preview"/>

[**View Live Demo**](https://socials.inulute.com/)

</div>

## ✨ Features

- 🎨 **Eye-catching Design** - Futuristic animations and stunning visuals
- 🧩 **Fully Modular** - Simple configuration through a single file
- 🚀 **25+ Social Platforms** - Pre-configured with all major networks
- 📱 **Responsive Layout** - Optimized for all devices
- ⚡ **Fast Performance** - Smooth animations and quick loading times

## 📦 Quick Start

1. **Fork the repository** at [GitHub](https://github.com/inulute/open-linktree)
2. **Clone** your forked repo to your local machine
3. **Open** the project in your preferred code editor
4. **Modify** the configuration file with your personal details (see below)
5. **Deploy** to your preferred hosting platform. This project is optimized for Netlify.

```bash

## ⚙️ Configuration Guide

Create or edit the `SocialLinksConfig.ts` file with your personal information:

```typescript
// Profile configuration
export const myProfileConfig = {
  logo: "https://your-logo-url.svg", // Replace with your logo URL
  title: "Your Name or Brand", // Your name or brand name
  description: "Your personal tagline or description", // Brief description
  stats: [
    {
      icon: "Heart",
      value: "1K+ Followers", // Replace with your follower count
      color: "text-red-400" // Tailwind text color class
    },
    {
      icon: "Code",
      value: "10+ Projects", // Replace with your project count
      color: "text-blue-400"
    }
  ],
};

// Social links configuration
export const mySocialsConfig = [
  {
    name: 'GitHub',
    icon: 'Github',
    href: 'https://github.com/yourusername', // Replace with your GitHub profile URL
    gradient: 'from-gray-600 to-gray-400',
    description: 'Open Source Projects & Tools',
    tag: 'Code',
    isActive: true // Set to false to hide
  },
  {
    name: 'Twitter',
    icon: 'Twitter',
    href: 'https://twitter.com/yourusername',
    gradient: 'from-blue-600 to-cyan-600',
    description: 'Tech Updates & Development Journey',
    tag: 'Updates',
    isActive: true
  },
  // Modify more social links as needed...
];
```

## 🔗 Available Social Platforms

Pre-configured platforms you can use:
- GitHub
- Twitter
- LinkedIn
- YouTube
- Instagram
- Telegram
- Discord
- Medium
- Dev.to
- Hashnode
- CodePen
- ProductHunt
- Twitch
- Ko-fi
- Patreon
- Email
- Portfolio
- Reddit
- Stack Overflow
- Mastodon
- Website
- WhatsApp
- Facebook
- Snapchat
- GitLab
- Dribbble

## 🎨 Customization Reference

### Social Link Properties

| Property | Description | Required |
|----------|-------------|----------|
| `name` | Display name of the platform | Yes |
| `icon` | [Lucide icon](https://lucide.dev/) name | Yes |
| `href` | URL to your profile | Yes |
| `gradient` | Tailwind gradient classes for hover effect | Yes |
| `description` | Brief description | No |
| `tag` | Category label | No |
| `isActive` | Whether to display this link | Yes |

### Background Properties

| Property | Description |
|----------|-------------|
| `particleColors` | Array of color hex codes for particles |
| `particleCount` | Number of particles to display |
| `gridPattern` | Whether to show the grid pattern |
| `orbs` | Array of glowing orbs in the background |

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Support

- GitHub: [Create an issue](https://github.com/inulute/socials-page/issues)
- Email: support@inulute.com
- Twitter: [@inulute](https://twitter.com/inulute)

---

<p align="center">
  Made with ❤️ by <a href="https://inulute.com">inulute</a>
</p>