FINAL WORKING FRONT-END
- Username/password login UI
- IndexedDB document storage in the browser
- Upload PDF/JPG/PNG and keep the file locally
- Search, categories, document list, delete/download
- JPG -> PDF
- PDF -> JPG
- Image compression
- Merge PDF
- Split PDF by page numbers
- Scan/camera image -> PDF
- PIN disabled

The PDF/image libraries are loaded from CDNs. For a production APK, bundle these libraries locally and connect Firebase Authentication + Realtime Database/Cloud Storage using your own Firebase project configuration. Do not put service-account/private keys in the app.
