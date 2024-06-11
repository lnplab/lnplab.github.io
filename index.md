---
layout: page
---

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Research Team</title>
    <style>
        .content {
            display: flex;
            flex-direction: column;
            align-items: flex-start;
            margin: 20px;
            position: relative;
        }
        .content img {
            width: 800px; /* Set the width of the image */
            height: auto; /* Maintain aspect ratio */
            float: left; /* Float the image to the left */
            margin-left: 20px; /* Add some space between the image and the text */
            margin-bottom: 20px; /* Add some space below the image */
        }
        .content .text {
            width: 100%; /* Ensure the text takes full width */
        }
    </style>
</head>
<body>
    <div class="content">
        <img src="/images/teams/group1.jpg" alt="Research Team">
        <div class="text">
            <p>We are dedicated to developing nucleic acid-based therapies, achieving this goal through the synthesis of lipid nanoparticles. Our research team, composed of passionate and innovative scientists, focuses on exploring cutting-edge biotechnology to advance medical progress. Whether it's RNA vaccines, gene therapy, or other nucleic acid drugs, we are constantly striving to contribute to improving human health. Visit our lab's homepage to learn more about our latest research developments and achievements.</p>
        </div>
    </div>
</body>

---
<h1 style="font-size: 32px;">Highlight</h1>


<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Gallery with Titles and Descriptions</title>
    <style>
        .image-container {
            display: flex;
            justify-content: center;
            flex-wrap: wrap; /* Allow images to wrap on smaller screens */
            gap: 20px; /* Add space between images */
            margin: 20px;
        }
        .image-item {
            width: 800px; /* Set a fixed width for all image items */
            text-align: center;
        }
        .image-item img {
            width: 100%; /* Image will take up the full width of its container */
            height: auto; /* Maintain aspect ratio */
            border: 1px solid #ccc;
        }
        .image-title {
            font-weight: bold;
            margin: 10px 0 5px; /* Add some space around the title */
        }
        .image-description {
            font-size: 0.9em;
        }
    </style>
</head>
<body>
    <div class="image-container">
        <div class="image-item">
            <img src="images/article/article1.jpg" alt="article1">
            <div class="image-info">
                <h5 class="image-title"><a href="https://www.pnas.org/doi/10.1073/pnas.2116271119">Lung-selective mRNA delivery of synthetic lipid nanoparticles for the treatment of pulmonary lymphangioleiomyomatosis</a></h5>
                <p class="image-description"></p>
            </div>
        </div>
        <div class="image-item">
            <img src="images/article/article2.jpg" alt="Image 2 Description">
            <div class="image-info">
                <h5 class="image-title"><a href="https://www.pnas.org/doi/full/10.1073/pnas.2020401118">Lipid nanoparticle-mediated codelivery of Cas9 mRNA and single-guide RNA achieves liver-specific in vivo genome editing of Angptl3</a></h5>
                <p class="image-description"></p>
            </div>
        </div>
        <div class="image-item">
            <img src="images/article/article3.jpg" alt="Image 3 Description">
            <div class="image-info">
                <h5 class="image-title"><a href="https://pubs.acs.org/doi/10.1021/acs.accounts.1c00500">Developing Biodegradable Lipid Nanoparticles for Intracellular mRNA Delivery and Genome Editing</a></h5>
                <p class="image-description"></p>
            </div>
        </div>
    </div>
</body>
