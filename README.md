# RK4-Orbiting-Satellite

Program that simulates the orbit of an orbiting mass around a central mass(satellite and earth) using the Runge-Kutta 4th Order numerical method. The initial conditions of the satellite are those find for a geostationary orbit. With an initial position above the Earth's surface of 35786 kilometres and an initial velocity of 3.07 kilometres per second resulting in a circular orbit. Modifying the initial speed slightly changes the eccentricity of the orbit, making it more elliptical the more the value is changed from 3.07 km/s. The period of the simulation can be changed, however, currently is set for one day, as a geostationary takes around that much time for single orbit. The entire animation is written using the tkinter module and optional things like colour, canvas dimensions and even tracer and radial lines(tracer and radial lines being graphical features I have added) can be changed or disabled.