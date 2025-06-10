---
layout: post
title:  "DiffCheck: a Scan-CAD Evaluation Tool for Digital Manufacturing and Assembly Processes in Timber Construction"
date:   2025-05-27 14:30:00 +02:00
image:  /assets/img/image00.png
category: paper
tags:
  - grasshopper-plugin
  - point-clouds
---

**Team:** Andrea Settimi*, Damien Gilliard*, Eleni Skevaki*, Dr. Marirena Kladeftira, Julien Gammero, Dr. Prof. Stefana Parascho,  Prof. Yves Weinand

<!-- Download button -->
<p>
  <a
    href="{{ '/assets/papers/25_diffcheck.pdf' | relative_url }}"
    download
    class="btn download-btn">
    📄 Download Full Paper (PDF)
  </a>
</p>

In digital timber construction, scanning technologies and point cloud data are
widely used due to the accessibility of affordable 3D sensors, photogrammetry, and user-friendly
CAD tools. While typically not employed for accuracy checks in timber fabrication due to the precision of standard machinery, 
experimental research and prototyping with joinery and assembly can benefit from precision and accuracy evaluation tools.
We introduce diffCheck, a C++/Python software integrated into Grasshopper to address this
need. It uses advanced point cloud analysis to compare scans of fabricated timber structures with
their respective CAD models, helping to identify discrepancies. Tested on various timber elements and digital fabrication methods like robotic assembly, AR-assisted woodworking, and CNC machining, diffCheck aims to establish a user-friendly benchmark framework for digital fabrication systems using timber components, 
with the potential to find applications in other materials. Its source code and the analyzed data are openly shared with the digital fabrication community
under a permissive license.
Keywords: point cloud processing, CAD-scan comparison, timber construction, digital fabrication