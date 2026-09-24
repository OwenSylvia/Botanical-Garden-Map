# Botanical Garden Infrastructure Mapping Project

An interactive, multi-layered GIS deployment mapping the structural, recreational, and operational facilities at **River View Park (Buellton, California)**. This project demonstrates a clear spatial data split between public guest engagement features and hidden back-of-house utility infrastructure using advanced layer visibility logic.

---

## Live Interactive Map Deployments

This project utilizes a **Dual-View Deployment Strategy** hosted on Felt. Both views run from the same master map dataset, using native URL string parameters to seamlessly hide or unhide critical operational layers.

### 1. General Guest & Public Map View
This clean, user-facing layout is designed for standard visitors, tourists, and public park attendees. It highlights primary orientation paths, botanical features, gardens, and family amenities while completely restricting industrial infrastructure from the map canvas and legend sidebar menu.

➡️ **[Launch Live Public Map View](https://felt.com/map/Botanical-Garden-Infrastructure-PF9Bk44T6RV2urAAVlQf3GD?loc=34.616992,-120.208637,18.1z)**

###  2. VIP & Facility Director View
This administrative map layer profile dynamically overrides default visibility settings upon launch. Intended strictly for grounds management, municipal engineers, and maintenance crews, this link forces open our restricted backend utility data layers.

➡️ **[Launch Live VIP Administrative Map View](https://felt.com/map/Botanical-Garden-Infrastructure-PF9Bk44T6RV2urAAVlQf3GD?loc=34.617123,-120.209167,18.4z)**


---

## Data Schema & Feature Catalog

Every object on the canvas has been hand-digitized, styled according to its operational hierarchy, and embedded with high-resolution photo assets.

### Polygons & Footprints
* **North Grass Zone:** The primary expansive clearing of the grounds. Features manicured open lawn framed by the park’s northern boundaries. Highly versatile and sun-drenched, providing an open gateway to the trail networks.
* **Willow Maze:** The premier interactive living installation on the grounds. A beautifully sculpted botanical labyrinth grown entirely from native willow species, functioning as a high-traffic destination.
* **Main Plaza & Secondary Plaza Courtyards:** Hardscaped gathering nodes and pedestrian crossroads serving as orientation centers connecting the main lawn hubs to trailing corridors.
* **Amphitheater Stage:** An open-air performance platform integrated directly into the landscape with optimized natural acoustics for community gatherings.

### Public Assets & Points of Interest (Blue Pins)
* **Main Entrance Hub:** The orientation and arrival gateway anchoring vehicular traffic transitions.
* **Parking Lot & Roundabout:** A continuous-flow drop-off configuration engineered to manage visitor arrival loops seamlessly.
* **Central Estate Fountain:** A signature visual centerpiece introducing a calming, sensory soundscape to the hardscaped courtyard.
* **Historic Canopy Bridge:** A timber-framed crossing spanning natural water features to seamlessly connect walking trails.
* **Monarch & Pollinator Photo Post:** An eco-educational photo-op station located right next to native pollinator preservation zones.
* **Community Seesaw & Wooden Play Train:** Durable, multi-generational recreational installations safely positioned inside family areas.
* **Nature Trail Scenic Lookout:** An elevated viewing deck rewarding hikers with panoramic vistas of the valley and lower riparian habitats.
* **Indigenous Chumash Cultural Exhibit:** An educational heritage site featuring a traditional dwelling replica celebrating the history of the region's original stewards.
* **Watershed Hydrology Sign:** An interpretive environmental station detailing groundwater mechanics and local drainage dynamics.

### Natural Boundaries & Corridors
* **Nature Trail:** A serene, shaded pedestrian walkway winding tightly through the mature tree canopy along the southern boundary ridge.
* **Riparian Creek Corridor:** The vital natural aquatic edge lining the lower valley, packed with native oaks and willows, acting as a crucial regional drainage and wildlife corridor.

### Restricted Administrative Utility Layers (VIP Group)
* **Aerobic Composting Facility:** The primary closed-loop sustainability zone where organic landscaping clippings and organic matter are processed into nutrient-dense soil conditioning compost.
* **Subsurface Wastewater & Sewage Drainage Point:** Critical municipal infrastructure routing wastewater effluent out of public areas. Strictly isolated for safety compliance, monitoring, and facility operations.

---
