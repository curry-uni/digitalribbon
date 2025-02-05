---
{"dg-publish":true,"permalink":"/entre-the-lab/","updated":"2025-02-05T11:07:22.437+00:00"}
---


human A549 carcinoma lung cells

.lab-container {display: flex; flex-direction: column; gap: 20px;}

.lab-station {position: relative; padding: 20px; border: 2px solid #000; background-color: #fff; cursor: pointer; text-align: center; transition: all 0.3s ease-in-out;}


.lab-station:hover {
    background-color: #f0f0f0;
    transform: scale(1.05);
}

.station-title {
    font-size: 24px;
    font-weight: bold;
    color: #333;
}

.station-description {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    background-color: #000;
    color: #fff;
    padding: 10px;
    width: 80%;
    opacity: 0;
 




<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Interactive Lab</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            display: flex;
            justify-content: center;
            padding: 20px;
        }

        .lab-container {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
            width: 80%;
        }

        .lab-station {
            position: relative;
            width: 100%;
            border: 2px solid #000;
            border-radius: 10px;
            overflow: hidden;
        }

        .lab-station img {
            width: 100%;
            height: auto;
            transition: transform 0.3s ease;
        }

        .lab-station:hover img {
            transform: scale(1.05);
        }

        .description {
            position: absolute;
            bottom: 0;
            left: 0;
            right: 0;
            background-color: rgba(0, 0, 0, 0.7);
            color: #fff;
            font-size: 14px;
            padding: 10px;
            opacity: 0;
            transition: opacity 0.3s ease;
            text-align: center;
        }

        .lab-station:hover .description {
            opacity: 1;
        }

        .lab-station h3 {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            color: white;
            font-size: 20px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.7);
            opacity: 0;
            transition: opacity 0.3s ease;
        }

        .lab-station:hover h3 {
            opacity: 1;
        }
    </style>
</head>
<body>

<div class="lab-container">
    <div class="lab-station">
        <img src="https://via.placeholder.com/300" alt="Research Bench">
        <div class="description">A deep dive into asthma research using fungal models. Key findings on epithelial damage.</div>
        <h3>Research Bench</h3>
    </div>
    <div class="lab-station">
        <img src="https://via.placeholder.com/300" alt="Publications Table">
        <div class="description">Publications and articles showcasing research on immune responses and biomarker identification.</div>
        <h3>Publications Table</h3>
    </div>
    <div class="lab-station">
        <img src="https://via.placeholder.com/300" alt="Experiment Station">
        <div class="description">Hands-on experimentation with different assays to explore immune signaling pathways.</div>
        <h3>Experiment Station</h3>
    </div>
</div>

</body>
</html>


