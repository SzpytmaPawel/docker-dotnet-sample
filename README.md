/* General styling */
.nav-section {
    margin-bottom: 20px;
}

.nav-link p {
    font-size: 0.9rem;
    margin: 0;
    padding: 5px 0 5px 0;
    font-weight: bold;
}

/* Active item styling for NavLinks */
.nav-link.active p {
    color: #0d6efd;
}

.nav-link:hover p {
    color: #0d6efd;
}

/* TreeView styling */
.e-treeview .e-list-item {
    font-size: 0.9rem;
    margin: 0;
    padding: 5px 0 5px 0;
    font-weight: 500;
    color: black;
    cursor: pointer;
}

/* Apply white background and black text for all items by default */
.e-treeview,
.e-list-item,
.e-active > .e-fullrow {
    background-color: white !important;
    border: none !important;
    color: black !important;
}

/* Isolate hover styling: Only the hovered item turns blue */
.e-treeview .e-list-item:hover .e-anchor-wrap {
    color: #0d6efd; /* Blue text for hovered item */
}

/* Styling for active (selected) item */
.e-treeview .e-list-item.e-active .e-anchor-wrap {
    color: #0d6efd; /* Blue text for active item */
    font-weight: bold;
}

/* Ensuring active item text remains black except for hover/active color */
.e-treeview .e-list-item.e-active > .e-text-content .e-list-text {
    color: black !important;
}

/* Control color of expand/collapse icons only on active item */
.e-treeview .e-list-item.e-active > .e-text-content .e-icon-collapsible,
.e-treeview .e-list-item.e-active > .e-text-content .e-icon-expandable {
    color: black !important;
}
