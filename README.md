# ⚡ ```{ LaravelArtisan }``` ⚡


<div align="center">
  
![Banner](https://capsule-render.vercel.app/api?type=waving&color=FF2D20&height=300&section=header&text=Experienced%20Laravel%20Developer&fontSize=50&fontAlignY=40&desc=Crafting%20elegant%20web%20solutions%20with%20Laravel%20expertise&fontColor=FFFFFF&animation=fadeIn)

</div>

## `$ php artisan profile:show`

```php
<?php

namespace App\Developers;

use App\Traits\LaravelExpert;
use App\Traits\FullStackDeveloper;
use App\Interfaces\BlockchainEnthusiast;

class Profile extends Developer implements BlockchainEnthusiast
{
    use LaravelExpert, FullStackDeveloper;
    
    protected $name = 'Abdallah Khattab';
    protected $title = 'Experienced Laravel Developer';
    protected $experience = [
        'laravel' => 'Advanced',
        'php' => 'Expert',
        'mysql' => 'Advanced',
        'frontend' => 'Proficient',
        'blockchain' => 'Experienced',
    ];
    
    protected $currentFocus = 'Building scalable Laravel applications';
    
    public function getExpertise()
    {
        return [
            'Laravel Architecture',
            'RESTful API Development',
            'Database Optimization',
            'Backend Performance',
            'Custom Laravel Packages',
            'Laravel + Web3 Integration'
        ];
    }
}
```

<br>

## `$ php artisan skills:list --format=json`

```json
{
  "primary": {
    "backend": {
      "frameworks": ["Laravel", "Laravel Livewire"],
      "language": "PHP",
      "databases": ["MySQL", "Redis"],
      "patterns": ["MVC", "Repository", "Service Layer", "SOLID"]
    }
  },
  "secondary": {
    "frontend": {
      "languages": ["HTML5", "CSS3", "JavaScript"],
      "frameworks": ["Vue.js","Tailwind CSS", "Bootstrap"],
      "libraries": ["jQuery", "Alpine.js"],
      "techniques": ["AJAX", "Responsive Design"]
    }
  },
  "additional": {
    "tools": ["Git", "Composer", "Artisan", "WSL"],
    "testing": ["PHPUnit", "Laravel Dusk"],
    "deployment": ["Laravel Forge", "CI/CD", "Docker"],
    "blockchain": {
      "languages": ["Solidity"],
      "tools": ["Web3.js", "Hardhat"],
      "experience": ["Smart Contract Development", "Sepolia ETH Deployment"]
    }
  }
}
```

<br>

## `$ php artisan render:tech-stack`

<div align="center">
<table border="0" style="border-collapse: collapse; width: 100%; max-width: 600px;">
  <tr>
    <td align="center" width="96">
      <img src="https://cdn.simpleicons.org/laravel/FF2D20" width="65" height="65" alt="Laravel" />
      <br>Laravel
    </td>
    <td align="center" width="96">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" width="65" height="65" alt="PHP" />
      <br>PHP
    </td>
    <td align="center" width="96">
      <img src="https://techstack-generator.vercel.app/mysql-icon.svg" width="65" height="65" alt="MySQL" />
      <br>MySQL
    </td>
    <td align="center" width="96">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="65" height="65" alt="Git" />
      <br>Git
    </td>
    <td align="center" width="96">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="65" height="65" alt="HTML5" />
      <br>HTML5
    </td>
  </tr>
  <tr>
    <td align="center" width="96">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="65" height="65" alt="CSS3" />
      <br>CSS3
    </td>
    <td align="center" width="96">
      <img src="https://techstack-generator.vercel.app/js-icon.svg" width="65" height="65" alt="JavaScript" />
      <br>JavaScript
    </td>
    <td align="center" width="96">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vuejs/vuejs-original.svg" width="65" height="65" alt="Vue.js" />
      <br>Vue.js
    </td>
    <td align="center" width="96">
      <img src="https://cdn.simpleicons.org/tailwindcss/38B2AC" width="65" height="65" alt="Tailwind CSS" />
      <br>Tailwind CSS
    </td>
    <td align="center" width="96">
      <img src="https://cdn.simpleicons.org/bootstrap/7952B3" width="65" height="65" alt="Bootstrap" />
      <br>Bootstrap
    </td>
  </tr>
  <tr>
    <td align="center" width="96">
      <img src="https://cdn.simpleicons.org/jquery/0769AD" width="65" height="65" alt="jQuery" />
      <br>jQuery
    </td>
    <td align="center" width="96">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" width="65" height="65" alt="Docker" />
      <br>Docker
    </td>
    <td align="center" width="96">
      <img src="https://techstack-generator.vercel.app/github-icon.svg" width="65" height="65" alt="GitHub" />
      <br>GitHub
    </td>
    <td align="center" width="96">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" width="65" height="65" alt="Linux/WSL" />
      <br>Linux/WSL
    </td>
    <td align="center" width="96">
      <img src="https://cdn.simpleicons.org/ethereum/3C3C3D" width="65" height="65" alt="Ethereum" />
      <br>Ethereum
    </td>
  </tr>
  <tr>
    <td align="center" width="96">
      <img src="https://img.icons8.com/ios/452/api.png" width="65" height="65" alt="RESTful API" />
      <br>RESTful API
    </td>
    <td align="center" width="96">
      <img src="https://cdn.simpleicons.org/postman/FF6C37" width="65" height="65" alt="Postman" />
      <br>Postman
    </td>
    <td align="center" width="96"></td>
    <td align="center" width="96"></td>
    <td align="center" width="96"></td>
  </tr>
</table>
</div>
<br>


<br>

## `$ vim laravel_expertise.blade.php` 

<div style="background-color: #1E1E1E; border-radius: 10px; padding: 15px; border-left: 4px solid #FF2D20;">

```php
<!-- My Laravel Expertise -->
<div class="expertise-container">
    @foreach ($expertiseAreas as $area)
        <div class="expertise-card">
            <div class="card-header">
                <h3>{{ $area['title'] }}</h3>
            </div>
            <div class="card-body">
                <ul>
                    @foreach ($area['skills'] as $skill)
                        <li>{{ $skill }}</li>
                    @endforeach
                </ul>
            </div>
        </div>
    @endforeach
</div>

@php
$expertiseAreas = [
    [
        'title' => 'Laravel Architecture',
        'skills' => [
            'MVC Implementation',
            'Service Layer Pattern',
            'Repository Pattern',
            'Domain-Driven Design',
            'Custom Laravel Packages',
        ]
    ],
    [
        'title' => 'API Development',
        'skills' => [
            'RESTful APIs',
            'API Resources',
            'API Authentication',
            'API Versioning',
            'API Documentation',
        ]
    ],
    [
        'title' => 'Database Management',
        'skills' => [
            'Eloquent ORM Mastery',
            'Database Optimization',
            'Complex Query Building',
            'Database Migrations',
            'Data Seeding',
        ]
    ],
    [
        'title' => 'Laravel Advanced',
        'skills' => [
            'Custom Artisan Commands',
            'Task Scheduling',
            'Laravel Queues',
            'Event Broadcasting',
            'Caching Systems',
        ]
    ],
    [
        'title' => 'Deployment & Hosting',
        'skills' => [
            'cPanel Management',
            'Database Configuration via cPanel',
            'Domain Management and DNS Setup',
            'MySQL Database Setup',
            'Laravel .env Configuration for Production',
            'File Permissions and Security',
            'Composer Dependency Management via SSH',
            'Error Logs Monitoring and Debugging',
            'Setting Up Cron Jobs for Laravel',
            'Setting Up and Managing Subdomains',
        ]
    ],
];

@endphp
```

</div>

<br>

## `$ php artisan showcase:projects`
### My most advanced Laravel & Vue.js builds

---

<table>
  <tr>
  <td valign="top">
    
### 📸 Instagram Clone SPA  
> **Vue.js 3 | Laravel | Inertia.js | WebSockets | SPA**  
A full-featured Instagram clone built as a Single Page Application.

[![Instagram Clone](https://cdn.dribbble.com/users/1299339/screenshots/14101681/media/1ede59d94e4d80731226ab39c22f8ead.gif)](https://nawasrah.site/instagram/login)

#### 🔧 Features:
- 🔐 Complete user authentication (Register/Login)
- 📸 Full CRUD for posts with image upload
- ⏳ 24-hour auto-deleting Stories
- 💬 Real-time messaging with Laravel WebSockets
- 🤝 Follow/Unfollow system with suggestions
- ❤️ Like & comment on posts
- 🔍 Explore page + trending posts
- 🔎 Advanced search (posts & users)
- 🔔 Real-time notifications
- 👤 Profile editing
- ⏰ Scheduled commands for story cleanup

[![Live Demo](https://img.shields.io/badge/LIVE_DEMO-FF2D20?style=for-the-badge&logo=vue.js&logoColor=white)](https://nawasrah.site/instagram/login)  
[![Source Code](https://img.shields.io/badge/SOURCE_CODE-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/abdallahkhattab/laravel-instagram-clone)

</td>
<td valign="top">
  
### 🖼️ NFT Marketplace  
> **Laravel | Solidity | Web3.js | MetaMask | Hardhat | Alchemy | Pinata**  
A Laravel-based NFT marketplace integrated with smart contracts.

[![NFT Marketplace](https://cdn.dribbble.com/users/1973718/screenshots/16382668/media/8837b6099cfd622bb1cc78a16535ceff.gif)](https://sepolia.etherscan.io/address/0x636937bac8A853767CF2422D4eDcCd2CC9e190d0#code)

#### 🔧 Features:
- 🖼️ Mint NFTs with IPFS-hosted media via **Pinata**
- 🪙 Trade and sell digital assets on-chain
- 🔐 MetaMask integration for secure user auth
- 🔗 Smart contract written in **Solidity** and deployed on **Sepolia Testnet**
- ⚙️ Smart contract compiled/tested using **Hardhat**
- 🌐 Blockchain communication via **Web3.js**
- ⚡ Powered by **Alchemy** for reliable blockchain access
- 📄 [Smart Contract on Etherscan](https://sepolia.etherscan.io/address/0x636937bac8A853767CF2422D4eDcCd2CC9e190d0#code)

[![Smart Contract](https://img.shields.io/badge/VIEW_CONTRACT-636937?style=for-the-badge&logo=ethereum&logoColor=white)](https://sepolia.etherscan.io/address/0x636937bac8A853767CF2422D4eDcCd2CC9e190d0#code)  
[![Source Code](https://img.shields.io/badge/SOURCE_CODE-181717?style=for-the-badge&logo=github&logoColor=white)](#)

</td>
  </tr>
<tr>
  <td valign="top">
    
### ✍️ Medium Clone  
> **Laravel 12 | MySQL | TailwindCSS | Alpine.js | Pusher | Postman**  
A Medium-style blogging platform with clean UI & backend.

[![Medium Clone](https://cdn.dribbble.com/users/5921388/screenshots/15376622/media/47c09313a5fded3c0c0e83f3a5a43d70.gif)](https://nawasrah.site/medium)

#### 🔧 Features:
- 🔐 User Authentication & Roles
- ✍️ Post creation/editing/deletion
- 💬 Commenting system
- 👏 Claps (like feature)
- 🤝 Follow/Unfollow authors
- 🔔 Real-time notifications (Pusher)
- 💬 Live chat between users
- 🔁 RESTful API tested with Postman

[![Live Demo](https://img.shields.io/badge/LIVE_DEMO-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)](https://nawasrah.site/medium)  
[![Source Code](https://img.shields.io/badge/SOURCE_CODE-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/abdallahkhattab/laravel-medium-clone)

</td>
<td valign="top">

### 🧠 MoodSync API  
> **Laravel 12 | Sanctum | MySQL | TailwindCSS | Scribe | Postman**  
Mental health tracking API with role-based access & docs.

[![MoodSync](https://cdn.dribbble.com/users/5921388/screenshots/15376622/media/47c09313a5fded3c0c0e83f3a5a43d70.gif)](https://nawasrah.site/moodsync)

#### 🔧 Features:
- 🔐 User Authentication with Laravel Sanctum  
- 📆 Mood tracking with daily entries, intensity, and notes  
- 🚨 Crisis detection system based on inactivity and keyword analysis  
- 🧑‍⚕️ Role-based access (Admin, Professional, User) using Spatie  
- 📊 Admin dashboard with mood analytics and user oversight  
- ✉️ Admin notes for professional mental health tracking  
- 🧠 Mood-based personalized recommendations  
- 📘 Interactive API documentation with Scribe  
- 🛡️ Mood entry validation to prevent duplicates  
- 🔁 RESTful API tested with Postman

[![Live Demo](https://img.shields.io/badge/LIVE_DEMO-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)](https://nawasrah.site/moodsync)  
[![Source Code](https://img.shields.io/badge/SOURCE_CODE-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/abdallahkhattab/laravel-moodsync-api)

</td>
  </tr>
</table>
<br>

## `$ php artisan github:stats`

<div align="center">
  
<!-- Replace with your actual GitHub username in the URLs -->
  
<img src="https://github-readme-stats.vercel.app/api?username=abdallahkhattab&show_icons=true&theme=dracula&bg_color=1E1E1E&hide_border=true&count_private=true&title_color=FF2D20&icon_color=FF2D20" width="45%" alt="GitHub Stats"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=abdallahkhattab&theme=dracula&background=1E1E1E&hide_border=true&fire=FF2D20&ring=FF2D20&currStreakLabel=FF2D20" width="45%" alt="GitHub Streak"/>

<br>

<img src="https://github-profile-trophy.vercel.app/?username=abdallahkhattab&theme=dracula&row=1&column=6&margin-w=15&margin-h=15&title_color=FF2D20" alt="GitHub Trophies" width="92%"/>

<br>

<div style="display: flex; justify-content: center;">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=abdallahkhattab&layout=compact&theme=dracula&bg_color=1E1E1E&hide_border=true&title_color=FF2D20" alt="Most Used Languages" width="45%"/>
</div>

</div>

<br>

## `$ php artisan development:philosophy`

<div align="center">
  
<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=FF2D20&center=true&vCenter=true&width=800&lines=Clean+code+is+not+written+by+chance;Elegant+solutions+through+Laravel+best+practices;Scalable+architectures+that+grow+with+your+business;Optimized+performance+for+exceptional+user+experience;Secure+by+design,+not+as+an+afterthought" alt="Typing SVG" />

</div>

<br>

## `$ php artisan connect:social`

<div align="center">
  
[![LinkedIn](https://img.shields.io/badge/-%E2%86%92%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](www.linkedin.com/in/abdallah-khattab-73081b2b7)
[![Twitter](https://img.shields.io/badge/-%E2%86%92%20Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/yourusername)
[![Portfolio](https://img.shields.io/badge/-%E2%86%92%20Portfolio-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)](https://abdallahkhattab.github.io/my-portfolio)
[![Email](https://img.shields.io/badge/-%E2%86%92%20Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:boodykhattab97@gmail.com)
[![Laravel Community](https://img.shields.io/badge/-%E2%86%92%20Laravel%20Community-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)](https://laracasts.com/@yourusername)

</div>

<br>

## `$ php artisan quote:laravel`

<div align="center">
  <blockquote>
    <p><i>"Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling."</i></p>
    <footer>— Taylor Otwell, Creator of Laravel</footer>
  </blockquote>
</div>

---
<!--
<div align="center">
  <img src="https://raw.githubusercontent.com/Trilokia/Trilokia/379277808c61ef204768a61bbc5d25bc7798ccf1/bottom_header.svg" width="100%">
</div>

<div align="center">
  <img src="https://profile-counter.glitch.me/{abdallahkhattab}/count.svg" alt="Visitor Count" />
  <br>
  <img src="https://img.shields.io/github/last-commit/abdallahkhattab/abdallahkhattab?style=for-the-badge&color=FF2D20" alt="Last updated" />
</div>
-->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/abdallahkhattab/abdallahkhattab/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/abdallahkhattab/abdallahkhattab/output/github-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/abdallahkhattab/abdallahkhattab/output/github-snake.svg" />
</picture>




<!-- Replace all instances of "yourusername" with your actual GitHub username -->
<!-- Add your actual project screenshots, links, and descriptions -->

