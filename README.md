# infotainment-system-autopmtestproject

## 🚗 Description
Next-generation in-vehicle infotainment system with Android Automotive OS integration

## ✨ Key Features
- Voice-activated navigation and controls
- Wireless Android Auto and Apple CarPlay integration
- Over-the-air (OTA) update capabilities
- Multi-zone audio management system
- Real-time traffic and weather integration

## 🛠️ Technology Stack
- Android Automotive
- Kotlin
- C++
- AAOS
- Gradle

## 📋 Prerequisites
- Automotive-grade development environment
- CAN/LIN bus simulation tools (Vector CANoe/CANalyzer recommended)
- ISO 26262 compliance documentation (for safety-critical modules)
- Hardware-in-the-loop (HIL) testing setup

## 🚀 Installation
```bash
git clone https://github.com/Adhivp/infotainment-system-autopmtestproject.git
cd infotainment-system-autopmtestproject

# Install dependencies
pip install -r requirements.txt  # For Python modules
# OR
./scripts/build.sh  # For embedded C/C++ projects
```

## 🔧 Configuration
Configure your vehicle parameters in `config/vehicle_params.yaml`:
```yaml
vehicle_type: sedan
can_bitrate: 500000
lin_baudrate: 19200
```

## 📖 Usage
Refer to `docs/USER_GUIDE.md` for detailed usage instructions.

## 🧪 Testing
```bash
# Run unit tests
pytest tests/

# Run HIL tests
./scripts/run_hil_tests.sh

# Generate coverage report
pytest --cov=src tests/
```

## 🏗️ Architecture
See `docs/ARCHITECTURE.md` for detailed software architecture and component diagrams.

## 🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first.
Ensure all changes comply with ISO 26262 and AUTOSAR guidelines.

## 📄 License
MIT License - see LICENSE file for details

## ⚠️ Safety Notice
This software is intended for development and testing purposes. 
Ensure proper validation before deployment in production vehicles.
