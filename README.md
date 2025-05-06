
# AR VR Group Project - CS595 - Milestone 2
Class: [[CS595 Augmented and Virtual Reality]]

Team:
- Alex Azroui
- Lucas Ferguson 
- Kaung (Nick) Myat Naing

Goal: Build a markdown notetaking client for the Meta Quest 3 and 3S, which allows users to attach notes to QR codes it real life using the new alpha Meta Pass-through Camera API. 

Code:
- Python + Flask Project [GitHub - LucasFerguson/ObsidiScan-md-server: Provides notes to the Meta Quest Unity App](https://github.com/LucasFerguson/ObsidiScan-md-server)
- Unity Project: [GitHub - LucasFerguson/ObsidiScan-md](https://github.com/LucasFerguson/ObsidiScan-md)
- AI [GitHub - KaungMyatNaing9/VR-Agent-sever: A backend sever for LLM endpoints for VR integration](https://github.com/KaungMyatNaing9/VR-Agent-sever)

## Project Architecture Diagram (Not fully implemented yet)
![AR VR Group Project CS595 Plan](https://github.com/user-attachments/assets/fae4249e-af23-40a1-8491-167b64e4bc49)

## Timeline
- **Week 1 Milestone**  
	- [x] ● Everyone on team installs Unity  
	- [x] ● Read and implement Get Started with Passthrough  
	- [x] ● Add ability for user to import obsidian note collection  
	- [x] ● Implement database, Learn RAG  
	- [x] ● Finalize which LLM,models or architecture we are going to use for the AI part  
- **Week 2 Milestone**  
	- [x] ● Use cameras (Passthrough API) to recognize QR codes on objects  
	- [x] ● Display window attached to the real world objects.  
		- [x] ○ Allow users to attach notes from their database (Obsidian) to these objects  
	- [x] ● Learn how to draw the 3D character and put in AR  
- **Week 3 Milestone**  
	- [ ] ● Support for cameras to recognize all objects (Including those without a QR code)  
	- [ ] ● Add a button to the display window to prompt the LLM on specific questions to that  
	- [ ] object.  
	- [ ] ● Have 3D character appear in AR
