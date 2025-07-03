backend = "glx";
vsync = true;
corner-radius = 8;
rounded-corners-exclude = ["class_g = 'Terminator'"];

blur-method = "dual_kawase";
blur-strength = 5;
blur-background = true;
blur-background-exclude = ["window_type = 'dock'", "class_g = 'Conky'", "class_g = 'Xfce4-notifyd'"];

inactive-opacity = 0.9;
active-opacity = 1.0;
frame-opacity = 0.9;
opacity-rule = [
  "90:class_g = 'Terminator'"
];

fading = true;
fade-in-step = 0.03;
fade-out-step = 0.03;
fade-delta = 10;
