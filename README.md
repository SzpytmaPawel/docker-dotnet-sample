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
.e-treeview .e-list-item {
    font-size: 0.9rem;
    margin: 0;
    padding: 5px 0 5px 0;
    font-weight: 500; 
    color: black; 
    cursor: pointer;
}

/* Only the hovered item changes color */
.e-treeview .e-list-item:hover .e-anchor-wrap {
    color: #0d6efd; /* Highlight color on hover */
}

/* Active item styling */
.e-treeview .e-list-item.e-active .e-anchor-wrap {
    color: #0d6efd;
    font-weight: bold;
}

/* Text content color for active item */
.e-treeview .e-list-item.e-active > .e-text-content .e-list-text {
    color: black !important;
}

/* Expand/collapse icon color for active item */
.e-treeview .e-list-item.e-active > .e-text-content .e-icon-collapsible,
.e-treeview .e-list-item.e-active > .e-text-content .e-icon-expandable {
    color: black !important;
}

/* General styling to ensure white background and black text */
.e-treeview, .e-list-item, .e-active > .e-fullrow {
    background-color: white !important;
    border: none !important;
    color: black !important;
}

.e-treeview, .e-list-item, .e-hover > .e-fullrow {
    background-color: white !important;
    border: none !important;
    color: black !important;
}
