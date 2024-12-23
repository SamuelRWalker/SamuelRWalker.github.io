---
layout: page
title: Matrix Methods Applications
---

Below is the report for the final project: SVD Image Compression.

### Final Project: SVD Image Compression
This project explores the application of Singular Value Decomposition (SVD) for compressing images. By retaining the most significant singular values and discarding less important ones, SVD enables reduced storage requirements for RGB image matrices with a trade-off in image quality. The project compares SVD-based compression with conventional image formats such as BMP, PNG, and JPG.

<object data="/assets/pdf/matmeth/finalreport.pdf" type="application/pdf" width="700px" height="700px">
    <embed src="/assets/pdf/matmeth/finalreport.pdf">
        <p>Your browser does not support PDFs. Please download the PDF to view it:  
        <a href="/assets/pdf/matmeth/finalreport.pdf">Download PDF</a>.  
        </p>
    </embed>
</object>

**Key Highlights:**  
- **Understanding SVD**: Decomposed matrices reveal underlying data structures for efficient manipulation and dimensionality reduction.  
- **Custom Implementation**: Implemented a custom SVD function to demonstrate understanding, with comparisons to NumPy's `linalg.svd`.  
- **Compression Effectiveness**: Evaluated the impact of small singular value removal and its effects on image file sizes.  
- **Benchmarking**: Compared SVD compression against BMP, PNG, and JPG using Kodak Image Set.

**Conclusions:**  
SVD provides insights into the foundational principles of image compression. Although not competitive with industry standards like PNG or JPG, SVD demonstrates flexibility in adjusting compression levels and offers educational value in understanding data compression techniques.

Check out the detailed report for a comprehensive breakdown, implementation details, and results.