# Mobile-Scroling-Menu

@media(max-width:767px){

/* Basic reset */
selector .elementor-nav-menu--main  {
  overflow-x: auto;
  -webkit-overflow-scrolling: touch;
  scroll-snap-type: x mandatory;
}

selector .elementor-nav-menu {
  display: flex;
  flex-wrap: nowrap;
  list-style: none;
  margin: 0;
  padding: 0;
  width: max-content;
}

selector .elementor-nav-menu li {
  flex: 0 0 auto;
  scroll-snap-align: start;
  padding: 0px 15px;
  white-space: nowrap;
}

selector .elementor-nav-menu li a {
  text-decoration: none;
  font-weight: bold;
  color: #333;
}

/* Optional: hide scrollbar */
selector .elementor-nav-menu--main::-webkit-scrollbar {
  display: none;
}

}
