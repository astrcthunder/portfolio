
/*
    Student Name: Day Clayton
    File Name: script.js
    Date: 11/17/2026
*/

// Function to toggle the mobile navigation menu
function toggleMenu() {
    const menu = document.getElementById("navigation-links");
    const button = document.querySelector(".menu-toggle");

    const isOpen = menu.classList.toggle("menu-open");

    button.setAttribute("aria-expanded", isOpen);
    button.setAttribute(
        "aria-label",
        isOpen ? "Close navigation menu" : "Open navigation menu"
    );
}