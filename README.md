# UNDIFINED ENGINE (UDE)

**UNDIFINED ENGINE** is an open-source, cinematic AAA game engine built on a fork, stride, optimized for high-fidelity visual rendering, VR support, and cross-platform deployment. UDE is designed to deliver out-of-the-box cinematic quality with modular architecture and plugin-based extensibility.

## 🎬 UDE Core Features

- **2D & 3D Support**: Full support for both 2D and 3D rendering workflows
- **Cinematic Rendering**: Powered by advanced graphics pipeline (Vulkan, DirectX 12 support)
- **ECS Architecture**: Entity-Component-System design combined with Data-Oriented Design (DOD)
- **Cross-Platform**: Native deployment to Windows, Linux, macOS, iOS, Android, Consoles, and WebGL (20+ platforms)
- **VR Ready**: Built-in VR framework support
- **Plugin System**: Modular plugin architecture for rendering, physics, animation, culling, and resolution upscaling
- **Live Collaboration**: RAID LIVE EDITING (RLE) for local network co-editing, UNIVERSAL LIVE EDITING (ULE) for cloud-based teams
- **Marketplace**: Integrated asset and plugin marketplace with Python-based procedural generation
- **Royalty System**: 5% royalty after $300,000 gross revenue
- **Resolution Scaling**: Dynamic resolution quality management (standard 2K locked, supports FSR 3.1, DLSS, AMD FidelityFX)

## 🚀 Quick Start

Create and manage UDE projects from the command line:

```bash
dotnet tool install -g UDE.Cli

ude sdk install                  # Install the latest UDE engine
ude new game -n MyProject        # Create a new UDE project
cd MyProject && dotnet run --project MyProject.Windows

ude studio                       # Open UDE Studio (visual editor)
```

## 🎨 UI Design

UDE Studio features a professional dark blue UI with white, red, and yellow accent colors:

- **Central 3D Viewport**: Main scene editing area with gizmo controls
- **Scene Hierarchy (Left)**: ECS world structure and entity management
- **Inspector (Right)**: Component and property editing
- **Asset Browser (Bottom-Left)**: Project assets, textures, models
- **Material Graph (Bottom-Middle)**: Shader and material visual editor
- **Toolbar (Top)**: Scene tools, viewport controls, marketplace access, 2D/3D mode toggle

## 📋 Phase 1: Stride Fork Transformation

This is the Phase 1 branch, focusing on:

1. **Rebranding**: Converting Stride fork identity to UDE
2. **Namespace Updates**: Stride → UDE namespacing throughout codebase
3. **UI Color Scheme**: Removing Stride orange/teal branding, applying UDE blue/white/red/yellow theme
4. **Build System**: Updating project files and configurations to reflect UDE identity
5. **Documentation**: Updating all references from Stride to UDE

**Status**: In Progress

## 🔧 Building from Source

### Prerequisites

1. **Git** (with LFS enabled) — Get it from [git-scm.com](https://git-scm.com/downloads)
2. **Visual Studio 2026** (Community edition is free) with:
   - .NET desktop development (bundles .NET 10 SDK)
   - Desktop development with C++

### Build Steps

1. Clone the UDE repository:
   ```bash
   git clone https://github.com/simonmalungane8-crypto/UNDIFINED-ENGINE.git
   cd UNDIFINED-ENGINE
   ```

2. Open the solution in Visual Studio 2026:
   ```
   build/UDE.slnx
   ```

3. Build the `UDE.GameStudio` project (main editor)

## 📚 Documentation

- [Build Instructions](docs/build/README.md)
- [SDK Guide](docs/build/SDK-GUIDE.md)
- [Contributing Guidelines](CONTRIBUTING.md)
- [Roadmap](https://github.com/simonmalungane8-crypto/UNDIFINED-ENGINE/wiki/Roadmap)

## 🤝 Contributing

See [Contributing Guidelines](CONTRIBUTING.md) for how to:
- Report bugs
- Submit pull requests
- Participate in the UDE development process

## 🛡️ License

UDE is covered by the [MIT License](LICENSE.md). See [THIRD PARTY.md](THIRD%20PARTY.md) for third-party dependencies.

## 🏦 Accounts & Hardware Hash

- Single account per platform device with hardware hash persistence
- Account survives reinstallation
- Automatic project folder storage in platform home directory
- Seamless project sync across platforms

## 📤 Export & Import

- **Export**: Save your UDE project folder to Git repositories (free, even with unpaid bills)
- **Import**: Import project folders from Git repos with debt settlement validation
- Full project state preservation across platforms

## 💳 Payments & Royalties

UDE uses:
- **Paystack**, **PayPal**, and **Stripe** for payments
- **5% royalty** on games earning over $300,000 gross
- Automatic compile unlock upon payment through account linking

## 🔒 Code Protection

UDE engine is compiled with:
- C++ AOT/Native AOT compilation
- Symbol stripping (`strip symbols=none`)
- Closed-source obfuscation
- Full decompilation protection

Projects created with UDE compile fully within the engine—external compilation is not supported.

## 🎯 Upcoming Phases

- **Phase 2**: 2D & 3D support refinement
- **Phase 3**: Thunder Manager (memory, audio, encryption)
- **Phase 4**: ANCIENT-CINEMATIC RENDER GRAPHICS (ACRG)
- **Phase 5**: UDE Greek Physics
- **Phase 6**: Animation system (UDE Raid Bodeia)
- **Phase 7**: Resolution quality (UDERESOLQUALITY)
- **Phase 8**: Scripting engine (C++, C#, Python)
- **Phase 9**: Royalty system
- **Phase 10**: Project deletion, import/export workflows
- **Phase 11**: Marketplace and asset management
- **Phase 12**: Code protection and obfuscation
- **Phase 13**: Compression and optimization
- **Phase 14**: Live editing and collaboration
- **Phase 15**: Account and hardware management
- **Phase 16**: Advanced UI and RapidDev

---

**Owner & Contact**: Simon Malungane (`simonmalungane8-crypto`)  
**Royalties Email**: malunganemiracle100@gmail.com (private)

