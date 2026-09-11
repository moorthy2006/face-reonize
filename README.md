# FaceAI — Complete AI Face Detection & Analysis Website

## Features
- Image upload and drag/drop
- Multiple face detection
- Live webcam detection
- Bounding boxes
- Estimated age
- Estimated gender presentation
- Facial-expression / reaction estimation
- Detection confidence
- Separate result cards for multiple faces
- Browser-based processing
- No face recognition or identity matching

## Files
FaceAI/
├── index.html
├── style.css
├── script.js
└── README.md

## Run
1. Create a folder named `FaceAI`.
2. Save the three code files in the folder.
3. Open it in VS Code.
4. Run with Live Server, or use:
   `python -m http.server 5500`
5. Open `http://localhost:5500`.

Camera access requires a secure context such as localhost or HTTPS.

## AI Models
The JavaScript loads face-api.js TinyFaceDetector, FaceLandmark68Net, AgeGenderNet and FaceExpressionNet models.

## Privacy
The supplied application processes images/camera frames in the browser. It does not contain a backend upload service and does not attempt to identify people.

## Disclaimer
Age, gender presentation and facial expression are AI estimates and can be inaccurate. Do not treat them as guaranteed facts or use them for high-impact decisions.
