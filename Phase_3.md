```mermaid
flowchart LR

A[Video Frame]

-->

B[YOLOv8]

-->

C[Detect Vehicles]

-->

D[Car]

C-->E[Bus]

C-->F[Truck]

C-->G[Motorcycle]

D-->H[Bounding Boxes]
E-->H
F-->H
G-->H
```
