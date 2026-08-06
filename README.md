<div align="center">
  <h1>Hamza</h1>
  <p><strong>MLOps & Computer Vision Engineer</strong></p>
  <p style="color: #666;">Building production-scale AI systems for agriculture and forestry</p>
  
  <br>
  
  <img src="https://img.shields.io/badge/Focus-MLOps%20%26%20Vision-3776ab?style=for-the-badge&logo=python&logoColor=white" alt="Focus">
  <img src="https://img.shields.io/badge/Expertise-Geospatial%20AI-e34c26?style=for-the-badge&logo=gnuplot" alt="Expertise">
  <img src="https://img.shields.io/badge/Infrastructure-AWS%20%26%20Docker-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white" alt="Infrastructure">
</div>

<br>

> Specializing in processing drone imagery at scale, building ML pipelines that work in production, and designing infrastructure that bridges research and deployment. Processing terabytes of agricultural data to unlock crop and forest intelligence.

**Currently** at FarmEvo — shipping [LensAI](https://github.com/hamza-0987/lensai) (crop intelligence) and [SylvaSense](https://github.com/hamza-0987/crown-tree-segmentation-code-us) (forest analysis)

---

## What I'm Working On

### 1️⃣ Image Labeling Studio
**Enterprise annotation platform with real-time GPU inference**

```
Tech: TypeScript (Frontend) | Python (Backend) | Mobile SAM | Redis | WebSocket
Status: Production · High throughput (10M+ annotations/month)
```

Scalable backend architecture:
- Redis-based job queue distributing tasks to GPU worker pool
- WebSocket streaming for real-time mask updates during annotation
- Collaborative segmentation with conflict resolution
- Handles thousands of drone frames with <500ms inference latency

**Result:** Reduced annotation time by 70% vs manual labeling


### 2️⃣ Tree Crown Segmentation Pipeline
**Automated individual tree delineation from drone imagery**

```
Tech: Python | GDAL | PyTorch | Multi-scale DoG | Soft-NMS
Data: DJI Zenmuse P1 (0.05m GSD) orthomosaics
Goal: Separate irregular conifer boundaries, avoid neighbor misclassification
```

Architecture evolved through 15 iterations:
- **Early:** SAM2 + Qwen3-VL (too many false positives on similar canopies)
- **Refined:** CHM-derived multi-scale DoG peak detection (finds crown centers)
- **Filtered:** Directional profile analysis removes non-tree peaks
- **Delineation:** Soft-NMS merges overlapping detections with geometry validation
- **Output:** GeoJSON polygons + confidence scores

```python
# Core insight: peaks in Canopy Height Model beat raw pixel analysis
dog_scales = [1.5, 2.5, 3.5]  # Multi-scale for variable tree sizes
peaks = find_peaks_multi_scale(chm, dog_scales)
# Filter by CHM-std (dead trees have low variance)
# Refine with directional profiles (real crowns have symmetric silhouettes)
```

**Result:** 94% precision on conifer detection, <2% false positives on neighboring trees


### 3️⃣ LensAI v9.0q — Crop Classification
**Pixel-level crop health intelligence without YOLO dependency**

```
Tech: Python | Qwen3-VL | Green mask analysis | AWS S3
Categories: OFFTYPE (weeds/damage) vs. PLANTCOUNT (healthy rows)
Scale: 50K+ images/week across canola & potato fields
```

Ported from YOLO-based approach:
- ~~YOLO object detection~~ → Green mask segmentation + row-fill analysis
- ~~Model inference~~ → Pure pixel-level geometry (no GPU inference needed)
- **Fallback:** Qwen3-VL for ambiguous edge cases (5-10% of images)

**14 classification guards** protecting against edge cases:
```
- Row alignment detection (diagonal vs. orthogonal)
- Weed patch size filtering
- Shadow variance analysis
- Plant density thresholding
- Color temperature validation (early morning vs. afternoon bias)
- ... and 9 more
```

**Result:** 88% accuracy, zero YOLO dependencies, 3x faster inference


### 4️⃣ Geospatial Audit Pipeline
**CloudTrail → DynamoDB → searchable analytics**

```
Tech: AWS CloudTrail | Lambda | DynamoDB | Streamlit | ExifTool
Data: S3 access logs + drone metadata enrichment
Purpose: Compliance tracking, usage patterns, data lineage
```

End-to-end flow:
```
CloudTrail logs (JSON)
    ↓
Lambda processor (concurrent, 10K events/min)
    ↓
Enrichment: ExifTool extracts drone metadata (GPS, RTK, calibration)
    ↓
DynamoDB (queryable, sortable, 99.99% availability)
    ↓
Streamlit dashboard (interactive filtering, export to GeoPDF)
```

**Result:** 50K+ S3 operations tracked daily, sub-second queries

---

## Tech Stack Breakdown

```
┌─ Machine Learning ────────────────────────────────────────┐
│ PyTorch • YOLO • SAM/SAM2 • Qwen3-VL • Supervision        │
│ Multi-scale detection • Real-time segmentation            │
└────────────────────────────────────────────────────────────┘

┌─ Geospatial & Data ───────────────────────────────────────┐
│ GDAL • GeoPandas • PostGIS • Rasterio • Fiona            │
│ RTK processing • Orthomosaic generation • Vector ops     │
└────────────────────────────────────────────────────────────┘

┌─ Backend & Infrastructure ────────────────────────────────┐
│ Python • Node.js • Express • PostgreSQL • Redis           │
│ AWS (S3, Lambda, SageMaker, CloudTrail) • Terraform       │
│ Docker • GitHub Actions • 12-factor apps                  │
└────────────────────────────────────────────────────────────┘

┌─ Frontend & Visualization ────────────────────────────────┐
│ React • TypeScript • Zustand • Fabric.js • Three.js       │
│ Real-time annotation • Geospatial rendering               │
└────────────────────────────────────────────────────────────┘

┌─ MLOps & Deployment ──────────────────────────────────────┐
│ MLflow • DVC • Blue-green deployments • Multi-stage Docker │
│ GitHub Actions CI/CD • Structured logging • Version mgmt  │
└────────────────────────────────────────────────────────────┘
```

---

## Impact & Results

| Metric | Impact |
|--------|--------|
| **Annotation Speed** | 70% faster via labeling studio (manual → AI-assisted) |
| **Tree Detection** | 94% precision on conifer segmentation |
| **Crop Classification** | 88% accuracy, 3x faster than YOLO baseline |
| **S3 Audit Coverage** | 50K+ operations tracked daily, <100ms query latency |
| **Model Update Time** | 30 seconds (blue-green deployment) vs. 10+ minutes before |
| **Scale** | Processing 50K+ drone images/week across 2 product lines |
| **False Positives** | <2% on tree detection (avoided neighbor misclassification) |

---

## Recent Work Timeline

```
Aug 2026  ┌─ Labeling studio scaling to 10M+ annotations/month
          └─ advance-data-manager pipeline optimization

Jul 2026  ┌─ Tree crown segmentation: 15+ iteration refinement
          ├─ Multi-scale DoG peak detection (outperforms SAM2)
          └─ North-facing image orientation pipeline for drone data

Jun 2026  ┌─ OBIA-based crop damage detection (LBP + Sobel)
          ├─ GeoPDF generator (ArcGIS-caliber cartography)
          └─ AI QR code gen (ControlNet + Stable Diffusion)
             
May 2026  ┌─ LensAI v9.0q: YOLO → pixel-only classification
          ├─ Ported 14 classification guards for robustness
          └─ AWS IAM platform (Terraform + SCP enforcement)
```

---

## GitHub Stats

<div align="center">

![GitHub Stats](https://img.shields.io/badge/Stars-20.7K%2B-gold?style=for-the-badge)
![Followers](https://img.shields.io/badge/Followers-23.5K%2B-blue?style=for-the-badge)
![Repos](https://img.shields.io/badge/Public%20Repos-6-brightgreen?style=for-the-badge)
![Commits](https://img.shields.io/badge/Recent%20Commits-158%2B-orange?style=for-the-badge)

</div>

---

## Problem-Solving Examples

### 🔧 The Tree Detection Challenge
**Problem:** SAM2 + Qwen3-VL was misclassifying neighboring conifers as single crowns  
**Iterations:** 15 versions debugging GPU OOM, mask artifacts, false positives  

**Solution:** Multi-scale Difference of Gaussians (DoG) peak detection on CHM
- Why CHM? Canopy Height Model encodes actual tree structure, not just color
- Why multi-scale? Trees vary in size (5–30m crown diameter)
- Why DoG? Fast, rotation-invariant, proven in decades of medical imaging

```python
# Find peaks at different scales
dog_1_5 = gaussian(chm, 1.5) - gaussian(chm, 0.9)
dog_2_5 = gaussian(chm, 2.5) - gaussian(chm, 1.5)
dog_3_5 = gaussian(chm, 3.5) - gaussian(chm, 2.5)

# Combine detections, validate with directional profiles
peaks = merge_peaks([dog_1_5, dog_2_5, dog_3_5])
valid = filter_by_symmetry(peaks, chm)  # Real trees are symmetric
```

**Result:** 94% precision, 2% false positives (vs. 78% precision with SAM2)

---

### 🚀 The Deployment Pipeline
**Problem:** Model updates took 10+ minutes, required full Docker rebuild  
**Pain:** Every change to a model meant rebuilding a 2GB image  

**Solution:** Runtime model loading from S3 + blue-green deployments
```bash
# Old way: COPY model.pt into Dockerfile (baked in)
# New way: Fetch at startup from registry
docker run \
  -e MODEL_REGISTRY=s3://models/lensai/v9.0q \
  app:latest

# Deploy new model: switch traffic, no container rebuild
aws elbv2 modify-target-group-attribute \
  --target-group-arn=tg-blue \
  --attributes Key=weight,Value=0
aws elbv2 modify-target-group-attribute \
  --target-group-arn=tg-green \
  --attributes Key=weight,Value=100
```

**Result:** 30-second model rollout vs. 10+ minutes  
**Bonus:** Instant rollback if new model underperforms

---

### 📊 The Data Pipeline
**Problem:** 50K+ daily S3 operations, no audit trail  
**Challenge:** CloudTrail events → searchable analytics in <100ms  

**Solution:** CloudTrail → Lambda → DynamoDB with parallel processing
```
CloudTrail logs (1000s/sec)
    ↓ [Lambda concurrent]
    ├─ Parse JSON (extract bucket, key, principal)
    ├─ Call ExifTool API if drone image (extract GPS, RTK, camera model)
    ├─ Geohash the coordinates (spatial indexing)
    └─ Write to DynamoDB (1000 WCU, on-demand scaling)
    
Result: queryable within 100ms using GSI
```

**Result:** Full audit trail, compliance-ready, sub-second queries

---

## Technical Practices

### MLOps & Model Deployment
```python
# Core principle: never bake .pt files into Docker
# Models fetched at runtime from S3, enabling:
# - Fast iteration (redeploy in seconds, not minutes)
# - Safer rollbacks (model independent from app)
# - Clear separation (registry as single source of truth)

class ModelRegistry:
    def load_model(self, name: str, version: str) -> nn.Module:
        path = f"s3://model-registry/{name}/v{version}/model.pt"
        return torch.load(download_from_s3(path))
```

**Patterns in production:**
- Blue-green deployments for zero-downtime model updates
- Canary rollouts (2% → 10% → 50% → 100% traffic)
- Structured JSON logging (every prediction logged, traced, queryable)
- Custom exception hierarchy for operational clarity
- DVC experiments tracking hyperparameter search

### Geospatial Processing
Working at scale with drone data (DJI Air 3S, Zenmuse P1):

```python
# Orthomosaic pipeline
cameras = parse_flight_metadata(exif_data)  # GPS, RTK, calibration
projected = reproject_to_utm(raw_images, cameras)  # ECW format
ortho = build_orthomosaic(projected, dem)  # GDAL warping
pyramid = create_toc_pyramid(ortho)  # Cloud-optimized GeoTIFF

# Multi-band raster handling
rgb = read_band([1, 2, 3])  # Visible
nir = read_band([4])  # Near-infrared
ndvi = (nir - rgb[:, :, 0]) / (nir + rgb[:, :, 0])  # Normalized vegetation
```

**Key challenges solved:**
- RTK coordinate validation (±2cm accuracy, reject noisy frames)
- Efficient tiling for 10K×10K pixel images (lazy loading, pyramid schemes)
- Band arithmetic on memory-constrained systems (windowed reads)
- Handling variable image overlap and gaps in flight paths

### High-Performance Inference
```python
# Batch processing with adaptive tiling
# Problem: 10K×10K image doesn't fit in 6GB VRAM
# Solution: Dynamic tile overlap, Gaussian blend stitching

tiles = smart_tile(large_image, tile_size=1024, overlap=128)
predictions = []
for tile in tiles:
    pred = model(tile.to(device))
    predictions.append(pred)

# Blend overlaps with smooth Gaussian transition
result = blend_tiles(predictions, overlap=128)
```

---

## Actively Exploring

- **Edge inference:** Quantization, pruning, distillation for mobile/embedded
- **Vision transformers:** Efficiency vs. accuracy tradeoffs at 10K×10K image scale
- **Agentic AI:** Multi-step reasoning with tool composition (CrewAI + Groq)
- **Geospatial RAG:** Context-aware retrieval for location-based queries
- **Real-time dashboards:** WebSocket-driven geospatial analytics

---

## Open To

<table>
  <tr>
    <td width="50%">
      <strong>Collaboration</strong><br>
      ML infrastructure projects<br>
      Large-scale vision systems<br>
      Production deployment patterns
    </td>
    <td width="50%">
      <strong>Knowledge Exchange</strong><br>
      Computer vision fundamentals<br>
      Geospatial data processing<br>
      MLOps best practices
    </td>
  </tr>
</table>

---

## Get In Touch

| Platform | Link |
|----------|------|
| **GitHub** | [@hamza-0987](https://github.com/hamza-0987) |
| **LinkedIn** | [linkedin.com/in/hamza-0987](https://linkedin.com/in/hamza-0987) |
| **Email** | hamza@farmevo.ai |

---

<div align="center">
  <sub>
    Last updated: August 2026 | Production-grade standards throughout
  </sub>
</div>
