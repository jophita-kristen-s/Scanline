Scanline 

Scanline is a browser-based smart checkout tool that scans items laid out on a flat surface and automatically calculates the total price — no barcode scanner, no manual entry.

Status: In Testing — Scanline is currently under active development and testing. Accuracy, performance, and supported item sets are still being refined. Not yet ready for production use.

How It Works
Lay out your items — Place all the products you want to buy visibly on a flat surface (table, counter, mat), making sure they don't overlap and are clearly separated.
Scan — Point your camera (webcam or phone camera) at the surface. Scanline captures the frame and detects each item individually.
Identify — Each detected item is matched against a product catalog/database to identify what it is.
Calculate — Scanline looks up the price of each identified item and sums them to give you the total bill instantly.
Features
Single-shot multi-item detection — scan an entire spread of items in one camera pass, rather than one at a time.
Automatic price calculation — no manual lookups or barcode scanning required.
Runs in-browser — no app install needed.
Still evolving — detection accuracy and item catalog are actively being improved during this testing phase.

Tech Stack - camera capture API, object detection model, product database, frontend framework.

Frontend: TBD
Item detection / object recognition: TBD
Price database: TBD
Current Limitations (Testing Stage)
Items must be placed flat and non-overlapping for reliable detection.
Lighting conditions can affect detection accuracy.
Product catalog coverage is limited — items not in the database won't be priced correctly.
Detection accuracy is still being validated across different item types and packaging.
Roadmap
 Improve detection accuracy for overlapping/occluded items
 Expand product catalog
 Add support for handwritten/custom price tags
 Mobile camera optimization
 Receipt export (PDF/CSV)
