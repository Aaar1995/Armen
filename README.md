#Armen
/* Common Styles */

body {
  font-family: 'Inter', sans-serif;
  margin: 0;
}

/* Desktop */

body.desktop {
  position: relative;
  width: 1440px;
  height: 980px;
  background: #0E1014;
  color: #E4E5EA;
}

/* Red light */
body.desktop .red-light {
  position: absolute;
  width: 311px;
  height: 311px;
  left: -102px;
  top: 251px;
  background: #961A1A;
  opacity: 0.5;
  filter: blur(196px);
}

/* Purple light */
body.desktop .purple-light {
  position: absolute;
  width: 259px;
  height: 259px;
  left: 602px;
  top: -154px;
  background: #833AB4;
  opacity: 0.5;
  filter: blur(196px);
}

/* Red ball */
body.desktop .red-ball {
  position: absolute;
  width: 28px;
  height: 28px;
  left: 851px;
  top: 547px;
  background: radial-gradient(64% 64% at 27.25% 26.5%, rgba(255, 208, 208, 0.48) 0%, rgba(212, 93, 93, 0.248) 59.67%, rgba(167, 49, 49, 0.264) 78.59%, rgba(130, 25, 25, 0.232) 100%);
  box-shadow: 3px 6px 27px -10px rgba(223, 125, 125, 0.25);
  filter: blur(2.5px);
  backdrop-filter: blur(2px);
}

/* Red ball (larger) */
body.desktop .red-ball-larger {
  position: absolute;
  width: 83px;
  height: 83px;
  left: 519px;
  top: 83px;
  background: radial-gradient(64% 64% at 27.25% 26.5%, rgba(255, 208, 208, 0.536) 0%, rgba(212, 93, 93, 0.264) 59.67%, rgba(167, 49, 49, 0.248) 78.59%, rgba(130, 25, 25, 0.248) 100%);
  box-shadow: 3px 6px 27px -10px rgba(223, 125, 125, 0.25);
  backdrop-filter: blur(2px);
}

/* Purple ball */
body.desktop .purple-ball {
  position: absolute;
  width: 60px;
  height: 60px;
  left: 868px;
  top: -2px;
  background: radial-gradient(64% 64% at 27.25% 26.5%, rgba(236, 208, 255, 0.64) 0%, rgba(161, 93, 207, 0.24) 59.67%, rgba(118, 49, 164, 0.208) 78.59%, rgba(86, 24, 128, 0.232) 100%);
  box-shadow: 3px 6px 27px -10px rgba(177, 118, 217, 0.25);
  filter: blur(5px);
  backdrop-filter: blur(2px);
}

/* Ready Solutions and Widgets */
body.desktop .ready-solutions {
  position: absolute;
  width: 89px;
  height: 40px;
  left: 1036px;
  top: 336px;
  font-family: 'Montserrat';
  font-weight: 400;
  font-size: 16px;
  line-height: 20px;
  text-align: right;
}

body.desktop .widgets {
  position: absolute;
  width: 101px;
  height: 22px;
  left: 1024px;
  top: 308px;
  font-family: 'Inter';
  font-weight: 500;
  font-size: 18px;
  line-height: 22px;
  text-align: right;
  letter-spacing: 0.05em;
  text-transform: uppercase;
  color: #E4E5EA;
}

/* Mobile */

body.mobile {
  position: relative;
  width: 320px;
  height: 1115px;
  background: #0E1014;
  color: #E4E5EA;
}

/* main screen */
body.mobile .main-screen {
  position: absolute;
  width: 320px;
  height: 451px;
  left: 0px;
  top: 55px;
}

/* bg */
body.mobile .bg {
  position: absolute;
  width: 320px;
  height: 445px;
  left: 0px;
  top: 0px;
}

/* red ball */
body.mobile .red-ball {
  position: absolute;
  width: 18px;
  height: 18px;
  left: 278px;
  top: 563px;
  background: radial-gradient(64% 64% at 27.25% 26.5%, rgba(255, 208, 208, 0.48) 0%, rgba(212, 93, 93, 0.248) 59.67%, rgba(167, 49, 49, 0.264) 78.59%, rgba(130, 25, 25, 0.232) 100%);
  box-shadow: 3px 6px 27px -10px rgba(223, 125, 125, 0.25);
  filter: blur(2.5px);
  backdrop-filter: blur(2px);
}

/* purple ball */
body.mobile .purple-ball {
  position: absolute;
  width: 40px;
  height: 40px;
  left: 296px;
  top: 236px;
  background: radial-gradient(64% 64% at 27.25% 26.5%, rgba(236, 208, 255, 0.64) 0%, rgba(161, 93, 207, 0.24) 59.67%, rgba(118, 49, 164, 0.208) 78.59%, rgba(86, 24, 128, 0.232) 100%);
  box-shadow: 3px 6px 27px -10px rgba(177, 118, 217, 0.25);
  filter: blur(5px);
  backdrop-filter: blur(2px);
}

/* yellow ball */
body.mobile .yellow-ball {
  position: absolute;
  width: 25
