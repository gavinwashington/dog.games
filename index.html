// =====================================
// KIWI HOMEPAGE - JAVASCRIPT
// =====================================

const sites = [
    {
        name: "DuckDuckGo",
        url: "https://duckduckgo.com",
        icon: "🦆"
    },
    {
        name: "TikTok",
        url: "https://www.tiktok.com",
        icon: "🎵"
    },
    {
        name: "Twitch",
        url: "https://www.twitch.tv",
        icon: "🟣"
    }
];

let favorites = [];

// =====================================
// CREATE WEBSITE TILES
// =====================================

function loadSites() {
    const container = document.getElementById("siteGrid");

    if (!container) {
        console.error("Missing element: siteGrid");
        return;
    }

    container.innerHTML = "";

    sites.forEach((site, index) => {
        const tile = document.createElement("div");

        tile.className = "site-tile";

        tile.innerHTML = `
            <div class="site-icon">${site.icon}</div>
            <div class="site-name">${site.name}</div>
            <button class="favorite-button">
                ${favorites.includes(index) ? "★" : "☆"}
            </button>
        `;

        tile.addEventListener("click", () => {
            openSite(index);
        });

        tile.querySelector(".favorite-button")
            .addEventListener("click", (event) => {
                event.stopPropagation();
                toggleFavorite(index);
            });

        container.appendChild(tile);
    });
}

// =====================================
// OPEN POPUP
// =====================================

function openSite(index) {
    const site = sites[index];

    const overlay = document.getElementById("siteOverlay");
    const frame = document.getElementById("siteFrame");
    const title = document.getElementById("popupTitle");

    if (!overlay || !frame || !title) {
        console.error("Popup elements are missing.");
        return;
    }

    title.textContent = site.name;

    frame.src = site.url;

    overlay.style.display = "flex";
}

// =====================================
// CLOSE POPUP
// =====================================

function closePopup() {
    const overlay = document.getElementById("siteOverlay");
    const frame = document.getElementById("siteFrame");

    overlay.style.display = "none";
    frame.src = "about:blank";
}

// =====================================
// RELOAD POPUP
// =====================================

function reloadPopup() {
    const frame = document.getElementById("siteFrame");

    frame.src = frame.src;
}

// =====================================
// FAVORITES
// =====================================

function toggleFavorite(index) {
    if (favorites.includes(index)) {
        favorites = favorites.filter(item => item !== index);
    } else {
        favorites.push(index);
    }

    loadSites();
}

// =====================================
// SEARCH
// =====================================

function searchSites() {
    const search = document
        .getElementById("searchBar")
        .value.toLowerCase();

    const tiles = document.querySelectorAll(".site-tile");

    tiles.forEach((tile, index) => {
        const name = sites[index].name.toLowerCase();

        tile.style.display = name.includes(search)
            ? "block"
            : "none";
    });
}

// =====================================
// BOOKMARK SHORTCUT
// =====================================

document.addEventListener("keydown", (event) => {
    if (event.ctrlKey && event.key.toLowerCase() === "d") {
        event.preventDefault();
        alert("Kiwi homepage bookmarked!");
    }

    if (event.key === "Escape") {
        closePopup();
    }
});

// =====================================
// START KIWI
// =====================================

document.addEventListener("DOMContentLoaded", () => {
    loadSites();

    document
        .getElementById("searchBar")
        ?.addEventListener("input", searchSites);
});
