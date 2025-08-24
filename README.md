# Projects Hub

This repository serves as a centralized index for all development projects and utilities.

## Project Structure

### Newratek (NRC/HaLow Solutions)

#### Core Components
- **[nrc](./newracom/nrc/)** - NRC Wireless Driver for IEEE 802.11ah HaLow
  - Kernel-space wireless driver with mac80211 integration
  - Repository: [oyongjoo/nrc](https://github.com/oyongjoo/nrc)
  - Status: ✅ Production Ready

#### SoluM Yard
- **[nrc_rtcm_ie](./newratek/solum-yard/nrc_rtcm_ie/)** - NRC RTCM IE package for OpenWrt HaLow
  - Enhanced RTCM processing with LED events and WSIO features
  - Repository: [oyongjoo/nrc-rtcm-ie](https://github.com/oyongjoo/nrc-rtcm-ie)
  - Status: ✅ Active Development

- **[cli_app](./newratek/solum-yard/cli_app/)** - NRC CLI Application for HaLow Control
  - Command-line interface for wireless configuration and control
  - Repository: [oyongjoo/cli-app](https://github.com/oyongjoo/cli-app)
  - Status: ✅ Active Development

- **[sta_surge](./newratek/solum-yard/sta_surge/)** - Station Surge Testing Utility
  - Performance testing for HaLow wireless network capacity
  - Repository: [oyongjoo/sta-surge](https://github.com/oyongjoo/sta-surge)
  - Status: ✅ Active Development

## Getting Started

### Clone All Projects
```bash
git clone --recursive https://github.com/oyongjoo/projects.git
```

### Clone Specific Project
```bash
git clone https://github.com/oyongjoo/nrc-rtcm-ie.git
```

### Update Submodules
```bash
git submodule update --remote --recursive
```

## Project Categories

- **Wireless Drivers**: Kernel-space drivers for HaLow chipsets
- **Command Line Tools**: CLI applications for configuration and control
- **Testing Utilities**: Performance and load testing frameworks  
- **Network Utilities**: OpenWrt packages and networking tools
- **HaLow Development**: IEEE 802.11ah related implementations
- **RTCM Processing**: Real-time kinematic positioning utilities

## Contributing

Each project has its own repository with independent version control. Please refer to individual project repositories for contribution guidelines.

---

*Last updated: 2025-01-10*