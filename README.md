# DICOM Toolbox

**DICOM Toolbox** is a versatile and user-friendly Windows application developed in C# for the comprehensive management of DICOM files. Tailored for medical imaging professionals, researchers, and students, this tool simplifies the viewing, editing, and batch processing of medical imaging data. Its clean, intuitive interface ensures a smooth and efficient workflow.

![Main Interface](https://raw.githubusercontent.com/sghmire/DicomToolBox/main/ss/main_interface.png)

---

## Core Features

* **Advanced DICOM Viewer**: Visualize images with multi-planar (Axial, Sagittal, and Coronal) views.
* **Metadata Editor**: View and modify DICOM tags through a clean, editable table.
* **Anonymizer Tool**: Quickly remove patient-identifying information to ensure privacy.
* **Batch Renamer**: Systematically rename large sets of DICOM files based on their metadata.
* **Folder-Based Processing**: Open and manage entire folders of DICOM files for efficient batch operations.
* **Lightweight & Fast**: A minimalist design focused on core functionality without unnecessary overhead.

---

## Getting Started

### Prerequisites

-   Windows 10 or later
-   [.NET Desktop Runtime](https://dotnet.microsoft.com/download/dotnet)

### Installation

1.  Navigate to the **[Releases page](https://github.com/sghmire/DicomToolBox/releases)**.
2.  Download the latest `DicomToolBox.exe` file.
3.  Run the executable. No complex installation is required.

---

## Features in Action

### Comprehensive CT Viewer
Navigate through DICOM series with our integrated multi-planar viewer. Instantly switch between **Axial**, **Sagittal**, and **Coronal** views to get a complete picture of the imaging data, all synchronized in one window.

![CT Viewer](https://raw.githubusercontent.com/sghmire/DicomToolBox/main/ss/CT_viewer.png)

### Intuitive Metadata Editor
Take full control of your DICOM data. The main interface provides a clear and editable table of all DICOM tags. Click on any value to modify it instantly—perfect for correcting information or adding annotations on the fly.

![DICOM Tag Editor](https://raw.githubusercontent.com/sghmire/DicomToolBox/main/ss/main_interface.png)

### Quick & Easy Anonymization
Protect patient privacy with the built-in Anonymizer. This simple tool allows you to strip sensitive information like patient names and MRNs from DICOM files with a single click, ensuring your data is safe for research and sharing.

![Anonymizer Tool](https://raw.githubusercontent.com/sghmire/DicomToolBox/main/ss/dicom_anyon.png)

### Powerful Batch Renaming
Organize large datasets effortlessly. The Batch Renamer lets you define a custom naming convention using DICOM tags (like `StudyID`, `SeriesDate`, etc.) and applies it to an entire folder of files at once, saving you hours of manual work.

![Batch Renaming Utility](https://raw.githubusercontent.com/sghmire/DicomToolBox/main/ss/batch_renamer.png)

---

## License

This project is currently not under a specific license. Please contact the author for inquiries regarding commercial use.

---

Built by [Sagar Ghimire](https://github.com/sghmire)
