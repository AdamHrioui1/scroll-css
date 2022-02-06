# scroll-css


/* SCROLLBAR */
/* Let's get this party started */
::-webkit-scrollbar {
    width: 6px;
    cursor: pointer;
}

/* Track */
::-webkit-scrollbar-track {
    background: var(--blue-sky-color);
    border: 4px solid transparent;
    background-clip: content-box;   /* THIS IS IMPORTANT */
    cursor: pointer;
}

/* Handle */
::-webkit-scrollbar-thumb {
    background: var(--blue-sky-color);
    border: 1px solid var(--blue-sky-color);
    cursor: pointer;
}
::-webkit-scrollbar-thumb:hover {
    background: var(--black-blue-sky-color);
    border-radius: 3px;
    cursor: pointer;
}
