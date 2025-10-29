<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kerala Flood Disaster Management</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #007bff;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            padding: 20px 0;
        }
        section {
            background: white;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            color: #007bff;
            border-bottom: 2px solid #007bff;
            padding-bottom: 10px;
        }
        .image-gallery {
            display: flex;
            justify-content: space-around;
            gap: 20px;
            margin-bottom: 20px;
        }
        .image-item {
            flex: 1;
            text-align: center;
        }
        .image-item img {
            width: 100%;
            height: auto;
            max-height: 250px; /* Limits the size of the images */
            object-fit: cover; /* Ensures the image covers the area without distortion */
            border: 5px solid #ccc;
            border-radius: 8px;
            margin-bottom: 10px;
        }
        .map-container {
            text-align: center;
            margin: 20px 0;
        }
        .map-container img {
            width: 90%;
            max-width: 800px;
            height: auto;
            border: 5px solid #28a745;
            border-radius: 8px;
        }
        .info-card {
            padding: 15px;
            background-color: #e9ecef;
            border-left: 5px solid #ffc107;
            margin-top: 15px;
        }
        
        /* Responsive Design */
        @media (max-width: 768px) {
            .container {
                width: 95%;
            }
            .image-gallery {
                flex-direction: column;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>Kerala Flood Disaster Management & Relief 🌊</h1>
        <p>Preparedness, Response, and Recovery</p>
    </header>

    <div class="container">

        <section id="flood-comparison">
            <h2>Before and After Floods</h2>
            <div class="info-card">
                🚨 **ACTION REQUIRED:** Replace the `src` attribute value (`"path/to/image.jpg"`) below with the actual link or file path to your images!
            </div>
            <div class="image-gallery">
                <div class="image-item">
                    <img src="path/to/before_flood_image.jpg" alt="A street in Kerala before the flood, showing normal activity.">
                    <strong>Before Flood</strong>
                    <p>Shows a normal, dry area, essential for comparing the impact.</p>
                </div>
                <div class="image-item">
                    <img src="path/to/after_flood_image.jpg" alt="The same street in Kerala after the flood, showing inundation and damage.">
                    <strong>After Flood</strong>
                    <p>Illustrates the extent of the damage and need for recovery.</p>
                </div>
            </div>
        </section>

        <hr>

        <section id="kerala-map">
            <h2>Map of Kerala: Flood Zone Overview</h2>
            <div class="map-container">
                <img src="path/to/kerala_flood_map.png" alt="A map of Kerala highlighting the districts and flood-affected regions.">
                <figcaption>Map showing the geographical layout and highlighting flood-vulnerable areas of Kerala.</figcaption>
            </div>
            <p style="text-align: center; margin-top: 15px;">
                For official, interactive hazard maps, please visit the 
                <a href="https://sdma.kerala.gov.in/hazard-maps/" target="_blank">Kerala State Disaster Management Authority (KSDMA) website</a>.
            </p>
        </section>

        <hr>

        <section id="management-guide">
            <h2>Disaster Management Steps</h2>
            <div style="display: flex; gap: 20px;">
                <div style="flex: 1;">
                    <h3>Preparation (Before) ✅</h3>
                    <ul>
                        <li>**Emergency Kit:** Assemble a 72-hour survival kit.</li>
                        <li>**Evacuation Plan:** Know your highest ground and evacuation route.</li>
                        <li>**Insurance:** Check your flood insurance policy.</li>
                    </ul>
                </div>
                <div style="flex: 1;">
                    <h3>Recovery (After) 🛠️</h3>
                    <ul>
                        <li>**Safety Check:** Do not enter submerged buildings until checked for structural damage.</li>
                        <li>**Avoid Water:** Floodwaters may be contaminated or electrically charged.</li>
                        <li>**Clean-up:** Document damage and clean/disinfect all wet items immediately.</li>
                    </ul>
                </div>
            </div>
        </section>

    </div>

    <footer>
        &copy; 2025 Disaster Management Information | Emergency Contact: 📞 1077 (State Control Room)
    </footer>

</body>
</html>
