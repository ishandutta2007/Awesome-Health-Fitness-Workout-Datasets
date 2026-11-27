# Awesome-Health-Fitness-Workout-Datasets

# Awesome-Health-Fitness-Workout-Datasets



Top Health Fitness Workout Datasets (Opensource) 🌟 Star if you like it! 🌟



A curated list of top health, fitness, exercise, biomechanics, and wearable biometric datasets—featuring commercial/hosted data platforms and aggregators alongside open-source datasets, libraries, and self-hosted equivalents.



---



## Table of Contents



- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source Equivalents & Datasets](#open-source-equivalents--datasets)

  - [Exercise & Workout Databases](#exercise--workout-databases)

  - [Wearable Biometrics & Activity Recognition Datasets](#wearable-biometrics--activity-recognition-datasets)

  - [Biomechanics, Pose & Motion Datasets](#biomechanics-pose--motion-datasets)

  - [Nutrition & Food Databases](#nutrition--food-databases)

  - [Self-Hosted Fitness Trackers & Health Data Aggregators](#self-hosted-fitness-trackers--health-data-aggregators)

- [Contributing](#contributing)



---



## Sector Overview & Market Dynamics

The global wearable technology and digital health market is valued at approximately **$90B–$100B+** (projected to surpass $250B+ by 2030), with the underlying health data integration and healthcare API infrastructure market representing roughly **$1.3B–$2.0B**. The sector is **moderately fragmented**: while foundational wearable consumer hardware has major players (Apple, Google/Fitbit, Garmin, Samsung), the software ecosystem of biometrics, research platforms, remote patient monitoring (RPM), and data normalization APIs remains fragmented across specialized niche aggregators and multi-device middleware providers competing against custom proprietary vendor APIs.

---

## SaaS/Hosted Platforms

Commercial, cloud-hosted platforms, proprietary data marketplaces, and managed wearable APIs for health, fitness, and athletic telemetry.

| Platform | Description | Size (Revenue / Valuation) | Starting Pricing | Free Tier / Trial Limits |
| :--- | :--- | :--- | :--- | :--- |
| **[Strava Metro](https://strava.com)** | Aggregated, de-identified human-powered mobility, running, and cycling geospatial data for urban planning and public transit research. | **$2.2B Valuation** (~$415M–$490M ARR) | **Free** for qualified public sector / academic partners; commercial enterprise data licensing starts at custom quotes ($10,000+/yr) | **Free indefinitely** for qualifying municipal agencies, transportation departments, active transit advocacy groups, and approved university researchers via Metroview application. |
| **[Validic](https://validic.com)** | Enterprise digital health IoT and remote care platform aggregating biometrics and connecting wearables/RPM devices into EHR systems. | **$31.6M Total Funding** (Acquired by ChartSpan, 2026; est. $10M–$25M ARR) | Developer tier is free; production/commercial deployment tiers start at **$500/month** (scaling with connected active patient volume and EHR integration depth) | **Free Developer Tier** available for testing, prototyping, and sandbox integration with synthetic and developer test devices. |
| **[Human API](https://humanapi.co)** | Health data aggregation network connecting consumer wearables, wellness apps, and EHR/clinical records. | **$36M–$44M Total Funding** (Acquired by LexisNexis Risk Solutions / RELX; est. $5M–$10M ARR) | Enterprise production data access starts at **$500/month** (scaling with volume of retrieved health and wellness records) | **30-day free developer sandbox** with access to sample and test patient health/wellness data connections. |
| **[Terra API](https://tryterra.co)** | Unified developer API providing normalized access to health, sleep, and fitness data across 500+ wearables and fitness apps. | **$2.8M Seed Funding** (est. $1M–$3M ARR) | **$399/month** (annual billing) or **$499/month** (monthly billing) including core integrations and active user credit pool; streaming API available at +$99/month | **No permanent free tier**; offers a **30-day money-back evaluation guarantee** on standard plans, and up to $100,000 in credits over 6 months via competitive application to the Terra Startup Accelerator. |
| **[Fitrockr](https://fitrockr.com)** | Research and fleet management SaaS specialized in raw high-resolution sensor extraction and analytics from Garmin smartwatches. | **Profitable / Bootstrapped** (est. $500K–$1.5M ARR; 40%–87% annual revenue growth) | **$27.50 per connected device** (minimum 3-month commitment, including hosting and unlimited admin/user accounts) | **14-day free trial** with full access to test Garmin device fleet management and data export tools. |
| **[Fitabase](https://fitabase.com)** | Cloud data aggregation and device management platform for clinical research studies using Fitbit and Garmin devices. | **Bootstrapped** (~$200K–$300K ARR; Small Steps Labs LLC) | **$10 per participant per month** (billed as participant-month credits for the study duration) | **14-day free trial** for research teams to test device pairing, data syncing, and study management workflows. |



---



## Open-Source Equivalents & Datasets



Free and open-source datasets (FOSS), public repositories, and self-hosted software alternatives for exercise catalogs, biometric telemetry, and wearable data aggregation.



### Exercise & Workout Databases



* **[Exercises Dataset (hasaneyldrm)](https://github.com)** - Open-source structured dataset of strength and fitness exercises categorized by target muscles, equipment, and mechanics.

* **[Free Exercise DB (yuhonas)](https://github.com)** - Public domain open-source JSON database containing over 800 exercises with instructions, muscle groups, and images.

* **[wger Workout Manager](https://github.com)** - Free, open-source self-hosted fitness, workout, and weight manager with an open REST API and crowd-sourced exercise database.

* **[OpenFitness](https://github.com)** - Open-source collection of workout routines, exercise definitions, and fitness schemas in machine-readable formats.

* **[ExerciseDB Open Data](https://github.com)** - Open-source JSON repository detailing gym exercises, primary/secondary muscles, and difficulty levels.



### Wearable Biometrics & Activity Recognition Datasets



* **[PAMAP2 Physical Activity Monitoring](https://uci.edu)** - Open UCI dataset featuring IMU and heart rate monitor data across 18 different physical activities.

* **[WISDM Smartphone & Smartwatch Activity Dataset](https://uci.edu)** - Open dataset of accelerometer and gyroscope time-series data collected from smartwatches and smartphones during workouts.

* **[MHEALTH Dataset](https://uci.edu)** - Open mobile health dataset recording body motion and vital signs (ECG, acceleration, gyro, magnetometer) during 12 physical exercises.

* **[WESAD (Wearable Stress and Affect Detection)](https://uni-siegen.de)** - Public multimodal dataset containing physiological and motion data from chest- and wrist-worn devices.

* **[Opportunity Activity Recognition Dataset](https://uci.edu)** - Open dataset of wearable, object, and ambient sensors capturing naturalistic human physical activities.

* **[PPGDalia](https://uci.edu)** - Open dataset for PPG-based heart rate estimation during daily life and physical exercise with 3D accelerometer data.



### Biomechanics, Pose & Motion Datasets



* **[Human3.6M](http://imar.ro)** - Large-scale open dataset of 3D human poses and corresponding motion capture data across 15 everyday and exercise scenarios.

* **[InfiniteRep (Workout Repetition Counting)](https://github.com)** - Open synthetic video dataset by Google Research for fitness exercise classification and repetition counting.

* **[Countix](https://github.com)** - Open video dataset derived from Kinetics focused specifically on repetitive physical exercises and workout movements.

* **[MM-Fit](https://github.io)** - Multimodal open dataset combining inertial sensor data from smartwatches/earbuds with multi-view RGB-D video for full-body workouts.

* **[Penn Action Dataset](http://github.io)** - Open dataset of over 2,300 video sequences annotated with 2D human joint locations and sports/exercise action labels.



### Nutrition & Food Databases



* **[Open Food Facts](https://openfoodfacts.org)** - Free, open, collaborative database of food products worldwide with macro/micronutrient profiles and open APIs.

* **[USDA FoodData Central](https://usda.gov)** - Public domain nutritional database providing comprehensive macro, vitamin, and mineral breakdowns for raw and packaged foods.

* **[Open Nutrition](https://github.com)** - Open-source nutrition datasets and barcode-lookup tools designed for privacy-first calorie and macro tracking apps.



### Self-Hosted Fitness Trackers & Health Data Aggregators



* **[Open Wearables / Gadgetbridge](https://codeberg.org)** - Open-source Android application allowing users to sync, store, and export raw fitness data from Pebble, Mi Band, Amazfit, and Garmin without vendor clouds.

* **[GoldenCheetah](https://github.com)** - Free, open-source performance analysis software for cyclists, runners, and triathletes supporting FIT, TCX, and GPX telemetry files.

* **[FitTrackee](https://github.com)** - Self-hosted, open-source outdoor workout tracker (running, cycling, hiking) built as a privacy-respecting alternative to Strava.

* **[Endurain](https://github.com)** - Self-hosted open-source fitness tracking service that ingests GPX/FIT files and visualizes training metrics.

* **[Health Auto Export (Open Schemas) / Open mHealth](https://github.com)** - Open-source data schemas and tooling standardizing mobile health and wearable JSON formats as an alternative to Terra and Validic.

* **[SparkyFitness](https://github.com)** - Open-source, self-hosted fitness, workout, and nutrition tracking web app designed as an alternative to MyFitnessPal.



---



## Contributing



Contributions are welcome! Feel free to open a Pull Request to add more open-source health datasets, workout repositories, or self-hosted fitness tools.



1. Fork the repository.

2. Add your dataset or tool under the appropriate category with a concise description.

3. Submit a Pull Request.
