/* General Styles */
.nav-section {
    margin-bottom: 20px; 
}

.nav-link p {
    font-size: 0.9rem;
    margin: 0; 
    padding: 5px 0 5px 0; 
    font-weight: bold;
}

.nav-link.active p {
    color: #0d6efd; 
}

.nav-link:hover p {
    color: #0d6efd;
}

/* TreeView Styles */

/* Base item styles */
.e-treeview .e-list-item .e-text-content .e-list-text {
    font-size: 0.9rem;
    font-weight: 500;
    color: black; /* Set base text color */
}

/* Item container styles */
.e-treeview .e-list-item {
    margin: 0;
    padding: 5px 0;
    cursor: pointer;
    background-color: white;
    border: none;
}

/* Hover effect: Only the hovered item changes color */
.e-treeview .e-list-item:hover .e-text-content .e-list-text {
    color: #0d6efd; /* Highlight color on hover */
}

/* Active item styling: Only the active item is styled */
.e-treeview .e-list-item.e-active .e-text-content .e-list-text {
    color: #0d6efd;
    font-weight: bold;
}

/* Remove the color override from general styles */
.e-treeview, .e-list-item, .e-active > .e-fullrow,
.e-treeview, .e-list-item, .e-hover > .e-fullrow {
    background-color: white !important;
    border: none !important;
    /* Removed color: black !important; */
}
