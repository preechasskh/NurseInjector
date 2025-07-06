# PyNurseInjector Documentation Website

เว็บไซต์เอกสารสำหรับ DotNurseInjector - A Simple, Lightweight & Useful Dependency Injector for .NET

## 🌐 เกี่ยวกับเว็บไซต์

PyNurseInjector เป็นเว็บไซต์เอกสารที่ออกแบบมาเพื่อนำเสนอข้อมูลและวิธีการใช้งาน DotNurseInjector ซึ่งเป็น Dependency Injection Library สำหรับ .NET ที่ช่วยลดความซับซ้อนในการเขียนโค้ดและทำให้การจัดการ Dependencies เป็นเรื่องง่าย

## 📋 คุณสมบัติของเว็บไซต์

### 1. **การออกแบบที่ทันสมัย**
- 🎨 ดีไซน์แบบ Modern และ Clean
- 📱 Responsive Design รองรับทุกขนาดหน้าจอ
- 🌈 Color Scheme ที่สบายตาและเป็นมืออาชีพ
- ✨ Gradient Background ที่สวยงาม

### 2. **การนำทางที่ใช้งานง่าย**
- 🧭 Navigation Bar ที่ติดอยู่ด้านบน (Sticky)
- 📑 Sidebar Navigation ในหน้าเอกสาร
- 🔗 Smooth Scrolling สำหรับ Anchor Links
- 📱 Mobile Menu ที่ใช้งานง่าย

### 3. **ฟีเจอร์สำหรับนักพัฒนา**
- 💡 Syntax Highlighting ด้วย Prism.js
- 📋 ปุ่ม Copy Code ในทุกตัวอย่างโค้ด
- 🏷️ Code Tabs สำหรับแสดงตัวอย่างต่างๆ
- 📝 ตัวอย่างโค้ดที่ครอบคลุมและเข้าใจง่าย

### 4. **เนื้อหาที่ครบถ้วน**
- 📚 Getting Started Guide
- ⚡ Features Overview
- 💻 Real-World Examples
- 📖 Complete API Reference
- 🔄 Migration Guide

### 5. **User Experience ที่ดี**
- ⬆️ ปุ่ม Back to Top
- 🔍 Active Section Highlighting
- ⚡ Fast Loading
- 🎯 Clear Typography

## 📁 โครงสร้างไฟล์

```
PyNurseInjector/
├── 📄 index.html              # หน้าหลัก - แนะนำ DotNurseInjector
├── 📄 getting-started.html    # คู่มือเริ่มต้นใช้งาน
├── 📄 features.html          # รายละเอียดคุณสมบัติทั้งหมด
├── 📄 examples.html          # ตัวอย่างการใช้งานจริง
├── 📄 api-reference.html     # API Documentation แบบละเอียด
├── 📄 404.html              # หน้า Error 404 ที่สวยงาม
├── 📄 README.md             # ไฟล์นี้
├── 📁 css/
│   └── 🎨 styles.css        # Stylesheet หลักของเว็บไซต์
├── 📁 js/
│   └── ⚙️ script.js         # JavaScript สำหรับ Interactive Features
└── 📁 assets/               # โฟลเดอร์สำหรับรูปภาพและไฟล์อื่นๆ
```

## 🚀 การติดตั้งและใช้งาน

### วิธีที่ 1: เปิดดูแบบ Local

1. Clone หรือ Download โปรเจค
2. เปิดไฟล์ `index.html` ด้วย Web Browser

### วิธีที่ 2: Host บน GitHub Pages

1. สร้าง Repository ใหม่บน GitHub
2. Upload โฟลเดอร์ `PyNurseInjector` ทั้งหมด
3. ไปที่ **Settings > Pages**
4. เลือก **Source**: Deploy from a branch
5. เลือก **Branch**: main, **Folder**: /PyNurseInjector
6. คลิก **Save** และรอสักครู่
7. เว็บไซต์จะพร้อมใช้งานที่ `https://[username].github.io/[repository-name]/`

### วิธีที่ 3: Host บน Web Server อื่นๆ

- Upload ไฟล์ทั้งหมดไปยัง Web Server
- ไม่ต้องการ Server-side processing (เป็น Static Website)
- รองรับทุก Web Server (Apache, Nginx, IIS, etc.)

## 🎯 กลุ่มเป้าหมาย

- 👨‍💻 .NET Developers ที่ต้องการใช้ Dependency Injection
- 🎓 นักเรียน/นักศึกษาที่กำลังเรียนรู้ DI Pattern
- 🏢 ทีมพัฒนาที่ต้องการลดความซับซ้อนของโค้ด
- 🔧 Developers ที่ต้องการ migrate จาก manual DI

## 💡 จุดเด่นของ DotNurseInjector

### 1. **Namespace-Based Registration**
```csharp
services.AddServicesFrom("MyApp.Services");
```

### 2. **Attribute-Based Configuration**
```csharp
[RegisterAs(typeof(IUserService))]
[ServiceLifeTime(ServiceLifetime.Singleton)]
public class UserService : IUserService { }
```

### 3. **Property Injection**
```csharp
public class MyController
{
    [InjectService] 
    public IUserService UserService { get; private set; }
}
```

## 🛠️ เทคโนโลยีที่ใช้

- **HTML5** - โครงสร้างเว็บไซต์
- **CSS3** - การจัดรูปแบบและ Responsive Design
- **JavaScript (ES6+)** - Interactive Features
- **Prism.js** - Syntax Highlighting
- **Font Awesome** - Icons
- **Google Fonts** - Typography

## 📈 Performance

- ⚡ **Lightweight** - ไม่มี Heavy Frameworks
- 🚀 **Fast Loading** - Optimized Assets
- 📱 **Mobile Optimized** - Touch-friendly Interface
- ♿ **Accessible** - Semantic HTML

## 🔄 การอัพเดต

เว็บไซต์นี้สร้างขึ้นเพื่อรองรับ DotNurseInjector version 2.5.0 หากมีการอัพเดต API หรือฟีเจอร์ใหม่ สามารถแก้ไขไฟล์ HTML ได้โดยตรง

## 📝 License

เว็บไซต์นี้สร้างขึ้นเพื่อเป็นเอกสารประกอบสำหรับ DotNurseInjector โดย Enis Necipoglu

## 🤝 Contributing

หากต้องการปรับปรุงเว็บไซต์:
1. Fork repository
2. สร้าง branch ใหม่
3. ทำการแก้ไข
4. ส่ง Pull Request

## 📞 Contact

- **Original Project**: [DotNurseInjector](https://github.com/enisn/DotNurseInjector)
- **Documentation Website**: PyNurseInjector

---

🎉 **Happy Coding with DotNurseInjector!**