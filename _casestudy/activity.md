---
title: "Interactive Activity"
layout: default
---

Loot boxes come in many shapes and forms, though the initial idea remains the same, A virtual ‘box’ containing trivial in-game items based on RNG (random number generators).

Content for your interactive activity.

![it isn't working, boss](https://smith128-ux.github.io/ethics_fall2025/files/cardpack_unopened.png)

<button onclick="goToRandomPage()">Click To Open!</button>

<script>
    const pageUrls = [
        "https://smith128-ux.github.io/ethics_fall2025/casestudy/ethicalconcerns/",
        "https://smith128-ux.github.io/ethics_fall2025/casestudy/abstract/",
        "https://smith128-ux.github.io/ethics_fall2025/casestudy/stakeholder1/"
    ];

    function goToRandomPage() {
        const randomIndex = Math.floor(Math.random() * pageUrls.length);
        window.location.href = pageUrls[randomIndex];
    }
</script>

[Go to potential solutions](https://smith128-ux.github.io/ethics_fall2025/casestudy/potentialsolutions/)

[Go back to Stakeholder 1](https://smith128-ux.github.io/ethics_fall2025/casestudy/stakeholder1/)