# 🌟 Professional Portfolio Website

<div align="center">
  <h3>🚀 A Modern, Responsive Portfolio Website for Fullstack Web Developer</h3>
  
  ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
  ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
  ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
  ![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
  
  <p>สร้างและออกแบบเพื่อแสดงผลงานและทักษะการพัฒนาเว็บไซต์แบบ Fullstack</p>
  
  <h2>🌐 <a href="https://ovenkung.github.io/Portfolio/" target="_blank">Live Demo</a></h2>
  <p><strong>👆 Click to view the portfolio!</strong></p>
</div>

---

## 📋 Table of Contents

- [🌟 Features](#-features)
- [🛠️ Tech Stack](#️-tech-stack)
- [🚀 Getting Started](#-getting-started)
- [📂 Project Structure](#-project-structure)
- [📱 Responsive Design](#-responsive-design)
- [🎨 Design Features](#-design-features)
- [📊 Performance](#-performance)
- [🔧 Customization](#-customization)
- [📞 Contact](#-contact)
- [📄 License](#-license)

---

## 🌟 Features

### 🎯 **Core Sections**
- **🏠 Hero Section** - แนะนำตัวและ Call-to-Action ที่น่าสนใจ
- **👨‍💻 About Me** - ข้อมูลส่วนตัวและประวัติความเป็นมา
- **💼 Work Experience** - ประสบการณ์การทำงานและการฝึกงาน
- **🛠️ Skills** - ทักษะด้าน Frontend และ Backend Development
- **🚀 Projects** - ผลงานโปรเจกต์ที่สำคัญพร้อมลิงก์
- **📞 Contact** - ช่องทางการติดต่อและฟอร์มส่งข้อความ

### ✨ **Advanced Features**
- **📱 Responsive Design** - รองรับทุกขนาดหน้าจอตั้งแต่มือถือถึง 4K
- **🎭 Smooth Animations** - แอนิเมชันที่นุ่มนวลด้วย AOS และ GSAP
- **🌈 Modern UI/UX** - ดีไซน์ที่ทันสมัยด้วย Glass Morphism และ Gradient
- **⚡ Fast Loading** - โหลดเร็วด้วยการ optimize CSS และ images
- **🔍 SEO Friendly** - เตรียมพร้อมสำหรับ Search Engine Optimization
- **♿ Accessibility** - รองรับผู้พิการและมาตรฐาน Web Accessibility

---

## 🛠️ Tech Stack

### **Frontend Framework & Libraries**
- **HTML5** - Semantic markup และ structure
- **CSS3** - Advanced styling พร้อม Custom Properties
- **JavaScript (ES6+)** - Interactive functionality
- **Bootstrap 4.5.2** - Responsive grid system และ components

### **Animation & Effects**
- **AOS (Animate On Scroll)** - Scroll-triggered animations
- **GSAP 3.7.1** - High-performance animations
- **Animate.css 4.1.1** - Pre-built CSS animations
- **Custom CSS Animations** - Particle effects และ transitions

### **Typography & Icons**
- **Google Fonts (Poppins)** - Modern typography
- **Font Awesome 5.15.3** - Icon library
- **Custom Icon Animations** - 3D effects และ hover states

### **Development Tools**
- **Vanilla JavaScript** - Pure JS without frameworks
- **CSS Grid & Flexbox** - Modern layout systems
- **CSS Variables** - Dynamic theming capabilities

---

## 🚀 Getting Started

### Prerequisites
- **Web Browser** (Chrome, Firefox, Safari, Edge)
- **Text Editor** (VS Code, Sublime Text, Atom)
- **Live Server** (สำหรับ development - optional)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/OvenKung/CS319-Portfolio.git
   cd CS319-Portfolio
   ```

2. **Open in browser**
   ```bash
   # Option 1: Direct file opening
   open index.html
   
   # Option 2: Using Live Server (VS Code extension)
   # Right-click on index.html > "Open with Live Server"
   
   # Option 3: Using Python (if installed)
   python -m http.server 8000
   # Then open http://localhost:8000
   ```

3. **Start customizing**
   - Edit `index.html` for content
   - Modify `main.css` for styling
   - Update images in `images/` folder

---

## 📂 Project Structure

```
CS319-Portfolio/
├── 📄 index.html              # Main HTML file
├── 🎨 main.css               # Combined stylesheet
├── 📖 README.md              # Project documentation
├── 🖼️ images/               # Image assets
│   ├── me.jpg               # Profile photo (Hero section)
│   └── me2.jpg              # About section photo
└── 📋 styles.css            # Legacy styles (deprecated)
```

### **File Descriptions**

| File | Purpose | Description |
|------|---------|-------------|
| `index.html` | Main Page | Complete portfolio with all sections |
| `main.css` | Styles | Combined CSS with all components |
| `images/` | Assets | Profile photos and project images |
| `README.md` | Documentation | This file with setup instructions |

---

## 📱 Responsive Design

### **Breakpoint System**
```css
/* Mobile First Approach */
.container {
  /* Mobile: 320px - 767px */
  max-width: 100%;
}

@media (min-width: 768px) {
  /* Tablet: 768px - 991px */
  .container { max-width: 750px; }
}

@media (min-width: 992px) {
  /* Desktop: 992px - 1199px */
  .container { max-width: 970px; }
}

@media (min-width: 1200px) {
  /* Large Desktop: 1200px+ */
  .container { max-width: 1140px; }
}
```

### **Device Coverage**

| 📱 Device Type | 📏 Screen Size | 🎨 Layout | 🔧 Optimizations |
|----------------|----------------|-----------|------------------|
| **Mobile** | 320px - 767px | Single Column | Touch-friendly UI |
| **Tablet** | 768px - 991px | 2 Columns | Hybrid interface |
| **Desktop** | 992px - 1199px | Multi-column | Mouse optimized |
| **Large** | 1200px+ | Full layout | High-res ready |

---

## 🎨 Design Features

### **Visual Elements**
- **🌈 Gradient Backgrounds** - Beautiful color transitions
- **✨ Particle Animation** - Dynamic background effects
- **🎭 Hover Effects** - Interactive card animations
- **💫 Loading States** - Progress bars with animations
- **🔮 Glass Morphism** - Transparent card effects

### **Animation System**
```javascript
// GSAP Timeline Example
gsap.from('.hero-section h1', { 
  opacity: 0, 
  y: 50, 
  duration: 1, 
  delay: 0.2 
});

// AOS Configuration
AOS.init({
  duration: 800,
  easing: 'ease-in-out',
  once: true
});
```

### **Color Palette**
- **Primary**: `#4e73df` (Royal Blue)
- **Secondary**: `#36b9cc` (Cyan)
- **Success**: `#1cc88a` (Green)
- **Warning**: `#f6c23e` (Yellow)
- **Danger**: `#e74a3b` (Red)

---

## 📊 Performance

### **Optimization Features**
- ⚡ **Lightweight CSS** - Single combined stylesheet
- 🖼️ **Optimized Images** - WebP format with fallbacks
- 📦 **Minimal Dependencies** - Only essential libraries
- 🔄 **Lazy Loading** - Images load when needed
- 📱 **Mobile-First** - Optimized for mobile devices

### **Performance Metrics**
```
Lighthouse Score (Target):
🎯 Performance: 95+
♿ Accessibility: 90+
💡 Best Practices: 90+
🔍 SEO: 85+
```

---

## 🔧 Customization

### **Updating Personal Information**

1. **Profile Photos**
   ```html
   <!-- Hero Section -->
   <img src="images/your-photo.jpg" alt="Profile">
   
   <!-- About Section -->
   <img src="images/your-about-photo.jpg" alt="About">
   ```

2. **Personal Details**
   ```html
   <!-- Update in About section -->
   <div class="media">
     <h6 class="media-title">E-mail</h6>
     <label class="d-block long-content">your-email@example.com</label>
   </div>
   ```

3. **Work Experience**
   ```html
   <!-- Add new experience in timeline -->
   <div class="timeline-item left" data-aos="fade-right">
     <div class="timeline-content">
       <div class="timeline-date">2024 - Present</div>
       <!-- Your experience details -->
     </div>
   </div>
   ```

### **Adding New Projects**
```html
<div class="col-md-4 mb-4" data-aos="zoom-in" data-aos-delay="100">
  <div class="project-card">
    <div class="project-img">
      <img src="project-image.jpg" alt="Project Name">
      <div class="project-overlay">
        <div class="project-buttons">
          <a href="live-demo-url" class="btn btn-sm btn-light mr-2">
            <i class="fas fa-eye"></i> View
          </a>
          <a href="github-repo-url" class="btn btn-sm btn-light">
            <i class="fab fa-github"></i> Code
          </a>
        </div>
      </div>
    </div>
    <div class="project-info">
      <h5 class="project-title">Your Project Name</h5>
      <p class="text-muted">Project description...</p>
      <div class="project-tags">
        <span class="badge badge-primary">Technology 1</span>
        <span class="badge badge-info">Technology 2</span>
      </div>
    </div>
  </div>
</div>
```

### **Customizing Colors**
```css
:root {
  --primary-color: #4e73df;
  --secondary-color: #36b9cc;
  --success-color: #1cc88a;
  --warning-color: #f6c23e;
  --danger-color: #e74a3b;
}
```

---

## 📞 Contact

### **Get In Touch**
- **📧 Email**: [ovenlovenyou@gmail.com](mailto:ovenlovenyou@gmail.com)
- **💼 LinkedIn**: [Your LinkedIn Profile](https://linkedin.com/in/your-profile)
- **🐙 GitHub**: [@OvenKung](https://github.com/OvenKung)
- **📱 Phone**: 092-272-7229

### **Project Links**
- **🌐 Live Demo**: [Portfolio Website](https://your-portfolio-url.com)
- **📂 Repository**: [GitHub Repo](https://github.com/OvenKung/CS319-Portfolio)
- **🐛 Issues**: [Report Issues](https://github.com/OvenKung/CS319-Portfolio/issues)

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2025 OvenKung

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

---

## 🙏 Acknowledgments

### **Special Thanks**
- **🎨 Design Inspiration** - Modern web design trends
- **📚 Learning Resources** - CS319 Course Materials
- **🛠️ Development Tools** - VS Code, GitHub, Vercel
- **🎯 UI/UX Libraries** - Bootstrap, Font Awesome, Google Fonts
- **✨ Animation Libraries** - AOS, GSAP, Animate.css

### **Resources Used**
- [Bootstrap Documentation](https://getbootstrap.com/docs/4.5/)
- [Font Awesome Icons](https://fontawesome.com/)
- [Google Fonts](https://fonts.google.com/)
- [AOS Animation Library](https://michalsnik.github.io/aos/)
- [GSAP Animation Platform](https://greensock.com/gsap/)

---

<div align="center">
  <h3>⭐ If you like this portfolio, please give it a star! ⭐</h3>
  <p>Made with ❤️ for CS319 Course</p>
  
  <p>
    <strong>Created by:</strong> 
    <a href="https://github.com/OvenKung">OvenKung</a>
  </p>
  
  <p>
    <em>🚀 "Building the future, one line of code at a time"</em>
  </p>
</div>

---

## 📈 Project Statistics

```
📊 Portfolio Stats:
├── 📄 Lines of Code: ~720 (HTML) + ~1000 (CSS)
├── 🎨 Components: 6 major sections
├── 📱 Responsive Breakpoints: 4 main sizes
├── ✨ Animations: 15+ different effects
├── 🛠️ Skills Showcased: 12 technologies
├── 🚀 Projects Featured: 3 main projects
└── ⚡ Load Time: <3 seconds
```

**Last Updated**: September 2025  
**Version**: 1.0.0  
**Status**: ✅ Active Development

