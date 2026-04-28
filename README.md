# Webecon — Ruby SDK (v17.2.6 PRO)

Official Ruby SDK for the **Webecon Universal Animated Icon Engine**. 

### **1,031+ Premium Animated Icons | Professional Themes | 100% Free for Commercial Use**

Webecon is a professional-grade iconography ecosystem. This SDK allows Ruby developers to generate themeable, animated icon tags natively in Rails, Sinatra, or any Ruby environment.

---

## 🚀 Quick Start

### Installation
Add this line to your application's Gemfile:
```ruby
gem 'webecon'
```
And then execute:
```bash
bundle install
```

### Usage
```ruby
require 'webecon'

# Generate a high-performance icon tag
icon = Webecon::Webecon.icon("rocket")
                       .size(64)
                       .theme("shine")
                       .trigger("hover")
                       .build()

puts icon 
# Output: <webecon-icon name='rocket' size='64' ...></webecon-icon>
```

---

## 🌟 Key Features
- **✨ Professional Themes**: Shine (Glossy), Duo Tone, Glitch, Neon, and Glassmorphism.
- **🎨 Dual-Color System**: Full support for Primary and Secondary branding colors.
- **🎬 20+ Motion Presets**: Pulse, Spin, Jello, Rubber-Band, and more.
- **🦾 Ruby Native**: Clean, idiomatic Ruby implementation.

---

## 📝 Commercial License
Webecon is 100% Free for commercial projects. Standalone resale of the icons is prohibited.

Produced by **Aditya Divte Production**  
Official Website: [adityadivte.com](https://adityadivte.com)  
Visit - [webecon.adityadivte.com](https://webecon.adityadivte.com/) for more info