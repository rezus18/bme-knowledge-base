# Medical Imaging

## Overview
Medical imaging refers to various techniques used to create visual representations of the interior of the human body for clinical analysis and medical intervention.

## Main Modalities

### 1. X-Ray
- Uses ionizing radiation to image dense structures (bones)
- Fast and widely available
- Limited soft tissue contrast
- Common use: fractures, chest imaging

### 2. CT (Computed Tomography)
- Multiple X-ray images combined into 3D cross-sections
- Higher radiation dose than plain X-ray
- Excellent for trauma, lung, and abdominal imaging
- Hounsfield Units (HU) used to quantify tissue density

### 3. MRI (Magnetic Resonance Imaging)
- Uses magnetic fields and radio waves — **no ionizing radiation**
- Superior soft tissue contrast
- Based on **nuclear magnetic resonance (NMR)** of hydrogen atoms
- Key parameters: T1, T2 relaxation times
- Common use: brain, spine, joints, tumors

### 4. Ultrasound
- Uses high-frequency sound waves (2–18 MHz)
- Real-time, portable, no radiation
- Limited penetration through bone and air
- Common use: obstetrics, cardiac imaging (echocardiography)

### 5. PET (Positron Emission Tomography)
- Functional imaging using radioactive tracers (e.g., FDG)
- Shows metabolic activity — useful in oncology and neurology
- Often combined with CT (PET-CT)

## Image Processing Concepts
- **Segmentation** — identifying structures (e.g., tumors, organs)
- **Registration** — aligning images from different modalities
- **Reconstruction** — creating 2D/3D images from raw data

## DICOM Standard
- **DICOM** (Digital Imaging and Communications in Medicine)
- Universal format for storing and transmitting medical images
- Contains both image data and patient metadata

## AI in Medical Imaging
- Deep learning models (CNNs) used for automated diagnosis
- Examples: detecting diabetic retinopathy, lung nodules, fractures
- Tools: TensorFlow, PyTorch, MONAI framework
