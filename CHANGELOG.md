# 📜 Changelog  

## [Unreleased]  
- [ ] Add pull request templates  
- [ ] Improve documentation  

---

## [0.3.0] – 2025-08-26  
### Added  
- Issue templates for:  
  - 🐞 Bug Reports  
  - ✨ Feature Requests  
  - 🔧 Improvements  
- `.github/ISSUE_TEMPLATE/config.yml` to disable blank issues and redirect support to Discussions  

### Changed  
- Repository workflow improved with structured issue handling  

---

## [0.2.0] – 2025-08-26  
### Fixed  
- Resolved `ModuleNotFoundError: googleapiclient` by:  
  - Correcting dependency in `requirements.txt`  
  - Pinning Python version via `runtime.txt`  
- Cleaned up production URL with Streamlit Cloud custom subdomain  

### Added  
- `runtime.txt` to enforce stable Python environment  
- Initial `CHANGELOG.md`  

---

## [0.1.0] – 2025-08-20  
### Added  
- Initial release of **Smart Assist App**  
- Integrated YouTube API via `googleapiclient.discovery.build`  
- Basic Streamlit UI with random responses + API key support  
