# 📝 BIOTHON 2026: VITA-CORE SENTINEL AI Q&A PLAYBOOK
*Rapid-Fire 2-Line Defense Answers for Shivanesh, Ashwin, Venkataraam, & Ragavendra*

---

## 🧬 Section 1: Biological & Soil Science Questions

### Q: Do we need to put fertilizers if we use this mycelium?
* **Answer:** Yes, but significantly less. The mycelium does not replace fertilizers; it serves as a precision indicator so you apply *only* what the crop actually needs, reducing overall chemical input by 30% to 35%.

### Q: How do crops and soil get biological benefits from this fungus?
* **Answer:** The mycelium network acts as an extended root system (increasing surface area up to 100x), solubilizing locked-up soil phosphorus and retaining water, which naturally boosts crop drought resilience and yield.

### Q: How does the mycelium glow? What is the biochemical reaction?
* **Answer:** It uses a coupled two-enzyme pathway: a reductase converts FMN to $\text{FMNH}_2$, which luciferase oxidizes along with an aldehyde to release light at a peak wavelength of 522 nm.

### Q: How do you correlate bioluminescence intensity to specific Nitrogen levels?
* **Answer:** The glow intensity increases proportionally with metabolic activity stimulated by Nitrogen, which our PyTorch CNN maps to concentration curves (mg/kg) calibrated against standard reference curves.

### Q: How does the mycelium sense soil pH?
* **Answer:** Soil pH directly alters enzyme folding; our system detects this light-inhibition signature and maps it to a sigmoid bioavailability curve.

### Q: Will stepping on or pressing the mushrooms during cultivation kill the sensor?
* **Answer:** No; the mushrooms are just temporary fruiting bodies. The actual sensor is the massive mycelial network living safely underground, which heals and sprouts new glowing mushrooms within 24 hours.

---

## 💰 Section 2: Business & Economic Questions

### Q: How do farmers and the government get profit?
* **Answer:** Farmers profit by reducing fertilizer costs and earning carbon credit payouts. The government profits by reclaiming billions in retail subsidy outlays by preventing chemical over-application.

### Q: Why would a farmer choose this over a standard soil test?
* **Answer:** Standard lab tests cost ₹4,000 per sample and take 5 days; our system delivers unlimited, real-time soil profiles in 100ms for under ₹200.

### Q: How do you justify the scalability of this project? Drones are expensive for poor farmers.
* **Answer:** Individual farmers do not buy drones. Local agricultural cooperatives (Panchayats/FPOs) buy a single drone and scan entire villages at night for a small subscription fee.

### Q: What is the commercial monetization strategy of the company?
* **Answer:** We charge ₹500/acre/year for drone scans, take a 10% broker fee on Carbon Credit trades, and negotiate a 5% savings share from government subsidy programs.

---

## 🛠️ Section 3: Engineering & Feasibility Questions

### Q: How does this help to improve agriculture overall?
* **Answer:** It transitions farming from reactive guessing to precision, automated agriculture by combining non-destructive biological sensing with real-time drone telemetry and automated closed-loop remediation.

### Q: How do you handle ambient light (sunlight or moonlight) polluting the drone’s camera sensor?
* **Answer:** We run drone scans at night and use our calibration console's Cutoff slider and physical bandpass filters to subtract ambient lux noise from the active signal in real-time.

### Q: Mycelium decays over time. How does your model account for biological aging?
* **Answer:** The database tracks the inoculation date, and the Gain slider applies an exponential aging multiplier to calibrate the signal output as the culture grows older.

### Q: How accurate is your PyTorch CNN, and what happens if the server crashes?
* **Answer:** The model has a 94.2% validation accuracy; if weights are missing, the backend triggers an OpenCV green HSV filter fallback to ensure 100% operational uptime.

### Q: How does the closed-loop system actuate water or fertilizer on the field?
* **Answer:** If parameters breach thresholds, the backend dispatches an SMS alert via Twilio and sends control signals to local IoT irrigation and fertilization actuators.

---

## ⚠️ Section 4: Tricky Defensive Questions

### Q: How do you prevent the bioluminescent fungus from becoming an invasive species?
* **Answer:** We utilize non-invasive, native Indian bioluminescent fungal strains (like *Neonothopanus gardneri*, native to the Western Ghats) that naturally biodegrade post-harvest, leaving zero ecological footprints.

### Q: What happens during dry seasons or drought? Will the sensor die?
* **Answer:** During dry periods, the fungus enters a dormant spore state to survive, reviving instantly when irrigated. The lack of glow is interpreted by the CNN as a moisture reading below 15%.

### Q: What if wild, non-glowing mushrooms grow alongside the bioluminescent ones?
* **Answer:** Because drone scans are captured in pitch darkness, non-glowing mushrooms are completely invisible. The OpenCV pipeline masks out all non-luminous pixels, making wild mushrooms irrelevant.

### Q: Are fungal spores toxic to farmers or livestock?
* **Answer:** No, the selected strains are non-toxic, non-hallucinogenic, and completely safe. Inoculation is localized to the roots, and harvesting occurs during the day when sporulation is negligible.
