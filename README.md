# Ambee (ambee)

Ambee is an environmental-intelligence company that aggregates satellite, sensor, and ground-station data into a unified REST API. The Ambee API delivers hyperlocal air quality, pollen, weather, wildfire, soil, and NDVI/vegetation data worldwide via simple lat/lng, postal-code, and place lookups secured with an x-api-key header.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/ambee/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ambee/refs/heads/main/apis.yml)

## Tags

- Environmental Intelligence
- Air Quality
- Weather
- Pollen
- Geospatial

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Ambee Air Quality API

Hyperlocal air quality and AQI data (PM2.5, PM10, NO2, O3, SO2, CO) by latitude/longitude, city, country code, or postal code, plus historical and forecast lookups.

- **Human URL:** [https://www.getambee.com/api/air-quality](https://www.getambee.com/api/air-quality)
- **Base URL:** `https://api.ambeedata.com`

#### Tags

- Air Quality
- AQI
- Pollution

#### Properties

- [Documentation](https://docs.ambeedata.com/apis/overview)
- [API Reference](https://docs.ambeedata.com/apis/playground)
- [OpenAPI](openapi/ambee-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ambee.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ambee.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ambee Pollen API

Hyperlocal pollen counts and risk levels for tree, grass, and weed pollen by latitude/longitude or place, with latest, historical, and 120-hour forecast endpoints.

- **Human URL:** [https://www.getambee.com/api/pollen](https://www.getambee.com/api/pollen)
- **Base URL:** `https://api.ambeedata.com`

#### Tags

- Pollen
- Allergens
- Health

#### Properties

- [Documentation](https://docs.ambeedata.com/apis/overview)
- [OpenAPI](openapi/ambee-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ambee.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ambee.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ambee Weather API

Hyperlocal micro-weather including temperature, humidity, wind, pressure, precipitation, UV index, and cloud cover by latitude/longitude, with latest, historical, and forecast endpoints.

- **Human URL:** [https://www.getambee.com/api/weather](https://www.getambee.com/api/weather)
- **Base URL:** `https://api.ambeedata.com`

#### Tags

- Weather
- Micro Weather
- Forecast

#### Properties

- [Documentation](https://docs.ambeedata.com/apis/overview)
- [OpenAPI](openapi/ambee-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ambee.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ambee.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ambee Fire API

Active wildfire detections and fire-risk assessments by latitude/longitude or place, sourced from satellite hotspot feeds.

- **Human URL:** [https://www.getambee.com/api/fire](https://www.getambee.com/api/fire)
- **Base URL:** `https://api.ambeedata.com`

#### Tags

- Wildfire
- Fire Risk
- Hazards

#### Properties

- [Documentation](https://docs.ambeedata.com/apis/overview)
- [OpenAPI](openapi/ambee-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ambee.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ambee.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ambee Soil API

Soil temperature and soil moisture data at multiple depths by latitude/longitude or place, for agriculture, irrigation, and yield planning.

- **Human URL:** [https://www.getambee.com/api/soil](https://www.getambee.com/api/soil)
- **Base URL:** `https://api.ambeedata.com`

#### Tags

- Soil
- Agriculture
- Geospatial

#### Properties

- [Documentation](https://docs.ambeedata.com/apis/overview)
- [OpenAPI](openapi/ambee-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ambee.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ambee.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ambee NDVI / Vegetation API

Normalized Difference Vegetation Index (NDVI/EVI) values by latitude/longitude or place for monitoring vegetation density, agroforestry, and crop health over time.

- **Human URL:** [https://www.getambee.com/api/ndvi-evi](https://www.getambee.com/api/ndvi-evi)
- **Base URL:** `https://api.ambeedata.com`

#### Tags

- NDVI
- Vegetation
- Remote Sensing

#### Properties

- [Documentation](https://docs.ambeedata.com/apis/overview)
- [OpenAPI](openapi/ambee-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ambee.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ambee.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/ambeedata)
- [LinkedIn](https://www.linkedin.com/company/getambee)
- [Website](https://www.getambee.com)
- [Documentation](https://docs.ambeedata.com)
- [Plans](plans/ambee-plans-pricing.yml)
- [Rate Limits](rate-limits/ambee-rate-limits.yml)
- [Fin Ops](finops/ambee-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
