transition: color 250ms cubic-bezier(0.4, 0, 0.2, 1),
background-color 250ms cubic-bezier(0.4, 0, 0.2, 1),
box-shadow 250ms cubic-bezier(0.4, 0, 0.2, 1);

.filter-btn:hover,
.filter-btn:focus,
.filter-btn:active {
background-color: var(--active-color);
color: var(--white-color);
box-shadow: 0px 3px 1px rgba(0, 0, 0, 0.1),
0px 1px 2px rgba(0, 0, 0, 0.08),
0px 2px 2px rgba(0, 0, 0, 0.12);

.is-hidden {
visibility: hidden;
opacity: 0;
pointer-events: none;
transition: opacity 5000ms cubic-bezier(0.4, 0, 0.2, 1), visibility 5000ms cubic-bezier(0.4, 0, 0.2, 1);
}
